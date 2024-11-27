### **Saver** 

A Python-based GUI application that automatically backs up selected folders to a target directory at scheduled intervals. With a simple and intuitive interface, users can select folders to back up and configure where the backups will be saved. The application supports scheduling backups to run periodically, ensuring data is regularly backed up without user intervention.

### **Features**
User-Friendly GUI
Built with Tkinter, the application offers a straightforward graphical interface for selecting folders to back up and the target backup location.

Automatic Backup Scheduling
Utilize the schedule module to set periodic backup intervals, such as every 5 minutes, to automatically back up selected directories.

Recursive Folder Backup
The application walks through all subdirectories of selected folders and backs up all files, preserving the original folder structure.

Multi-Folder Support
Allows users to select multiple folders to back up at once, making it easier to manage large amounts of data.

File Copying
Automatically copies files to the designated target folder, creating any necessary subdirectories.

Background Execution
The backup process runs in the background, allowing users to continue interacting with the GUI without interruption.

Error Handling
The app silently handles errors during the backup process, ensuring continuous operation
