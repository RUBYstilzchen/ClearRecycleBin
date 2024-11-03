To have this .bat file run every time you shut down your PC, use one of the following methods:

    Method 1:
Using Local Group Policy (for Windows Pro and above)
Press Win + R, type gpedit.msc, and press Enter to open the Local Group Policy Editor.
Navigate to Computer Configuration > Windows Settings > Scripts (Shutdown).
In the window on the right, double-click Shutdown, then click Add.
Click Browse and select your .bat file (ClearRecycleBin.bat) saved earlier.
Click OK to confirm.


    Method 2:
Using the Job Scheduler (suitable for all versions of Windows)
Open Task Scheduler via the Start menu or by searching for it.
Select Action > Create Task....
Give the task a name, for example, “ Clear Recycle Bin on Shutdown”.
Click the Triggers tab and click Create....
In the Start task field, select When shutdown occurs.
Go to the Actions tab and click Create....
In the Program or Script field, specify the path to your .bat file.
Click OK to save the task.


Now the Recycle Bin will be automatically emptied every time you shut down your computer.

You can also run the file manually at any time, which will clear the recycle bin instantly.