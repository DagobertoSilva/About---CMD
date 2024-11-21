# About-CMD
## This repository contains studies about Windows CMD

### General configuration and management commands
1. change directory
```bash
C:\Users> cd destinationdirectory/myfolder
```

```bash
C:\Users\destinationdirectory\myfolder>
```
-> command alternative
```bash
C:\Users> chdir destinationdirectory/myfolder
```

```bash
C:\Users\destinationdirectory\myfolder>
```
->return to previous directory
```bash
C:\Users> cd ..
```

```bash
C:\>
```

2. check the contents of a directory
```bash
C:\Users\John> dir
```
```bash
The volume in drive C is bumblebee  
The Volume Serial Number is XX00-0X0Y
Directory of C:\Users\John

11/20/2024  03:45 PM    <DIR>          .  
11/20/2024  03:40 PM    <DIR>          ..  
11/20/2024  03:30 PM           320.450 ITA2025_Guide.pdf  
11/20/2024  03:44 PM           512.700 Study_Schedule.xlsx  
               2 File(s)        833.150 bytes  
               2 Dir(s)    85.324.211.200 bytes free
```
```bash
creationDate  creationTime <directory(DIR) or File> directoryOrFileName
              amountOfFiles  SizeOccupiedByFiles
              numberofdirectories sizeOfAvailableBytes
```

3. consult all available commands
```bash
C:\Users\John>help
```
```bash
C:\Users\John>help
 For more information on a specific command,  
 type HELP command_name  
ASSOC          Displays or modifies file extension associations.  
ATTRIB         Displays or changes file attributes.  
BREAK          Sets or clears extended CTRL+C checking.  
BCDEDIT        Sets properties in the boot database to control startup loading.  
CACLS          Displays or modifies access control lists (ACLs) of files.  
CALL           Calls a batch program from another batch program.  
CD             Displays the name of or changes the current directory.  
CHCP           Displays or sets the active code page number.  
CHDIR          Displays the name of or changes the current directory.  
CHKDSK         Checks a disk and displays a status report.  
CHKNTFS        Displays or modifies disk checking at startup.  
CLS            Clears the screen.  
CMD            Starts a new instance of the Windows command interpreter.  
COLOR          Sets the default console foreground and background colors.  
COMP           Compares the contents of two files or sets of files.  
COMPACT        Displays or alters the compression of files on NTFS partitions.  
CONVERT        Converts FAT volumes to NTFS. Cannot convert the current drive.  
COPY           Copies one or more files to another location.  
DATE           Displays or sets the date.  
DEL            Deletes one or more files.  
DIR            Displays a list of files and subdirectories in a directory.  
DISKPART       Displays or configures disk partition properties.  
DOSKEY         Edits command lines, recalls Windows commands, and creates macros.  
DRIVERQUERY    Displays the current device driver status and properties.  
ECHO           Displays messages or turns command echoing on or off.  
ENDLOCAL       Ends localization of environment changes in a batch file.  
ERASE          Deletes one or more files.  
EXIT           Exits the CMD.EXE program (command interpreter).  
FC             Compares two files or sets of files and displays the differences.  
FIND           Searches for a text string in one or more files.  
FINDSTR        Searches for text strings in files.  
FOR            Runs a specified command for each file in a set of files.  
FORMAT         Formats a disk for use with Windows.  
FSUTIL         Displays or configures file system properties.  
FTYPE          Displays or modifies the file types used in file extension associations.  
GOTO           Directs the Windows command interpreter to a labeled line in a batch program.  
GPRESULT       Displays Group Policy information for the computer or user.  
GRAFTABL       Enables Windows to display an extended character set in graphics mode.  
HELP           Provides help information for Windows commands.  
ICACLS         Display, modify, back up, or restore file and directory ACLs.  
IF             Performs conditional processing in batch files.  
LABEL          Creates, changes, or deletes the volume label of a disk.  
MD             Creates a directory.  
MKDIR          Creates a directory.  
MKLINK         Creates symbolic and hard links.  
MODE           Configures a system device.  
MORE           Displays output one screen at a time.  
MOVE           Moves one or more files from one directory to another.  
OPENFILES      Displays files opened by remote users for a file share.  
PATH           Displays or sets a search path for executable files.  
PAUSE          Suspends the processing of a batch file and displays a message.  
POPD           Restores the previous value of the current directory saved by PUSHD.  
PRINT          Prints a text file.  
PROMPT         Changes the Windows command prompt.  
PUSHD          Saves the current directory and then changes it.  
RD             Removes a directory.  
RECOVER        Recovers readable information from a defective or damaged disk.  
REM            Writes comments in batch files or the CONFIG.SYS file.  
REN            Renames one or more files.  
RENAME         Renames one or more files.  
REPLACE        Replaces files.  
RMDIR          Removes a directory.  
ROBOCOPY       Advanced utility to copy files and directory trees.  
SET            Displays, sets, or removes Windows environment variables.  
SETLOCAL       Begins localization of environment changes in a batch file.  
SC             Displays or configures services (background processes).  
SCHTASKS       Schedules commands and programs to run on a computer.  
SHIFT          Changes the position of replaceable parameters in a batch file.  
SHUTDOWN       Allows proper local or remote shutdown of the computer.  
SORT           Sorts input.  
START          Starts a separate window to run a specified program or command.  
SUBST          Associates a path with a drive letter.  
SYSTEMINFO     Displays machine-specific configuration and properties.  
TASKLIST       Displays all currently running tasks, including services.  
TASKKILL       Ends or stops a running process or application.  
TIME           Displays or sets the system time.  
TITLE          Sets the window title for a CMD.EXE session.  
TREE           Graphically displays the directory structure of a drive or path.  
TYPE           Displays the contents of a text file.  
VER            Displays the Windows version.  
VERIFY         Tells Windows to verify that files are written correctly to a disk.  
VOL            Displays a disk’s volume label and serial number.  
XCOPY          Copies files and directory trees.  
WMIC           Displays WMI information in an interactive command shell.  

For more information on tools, see the command line reference in online help.  

```

-> Ask for help for a specific command

```bash
C:\Users\John>help CommandName
```

4. clear the screen
### Before
C:\Users\John> dir
```
```bash
The volume in drive C is bumblebee  
The Volume Serial Number is XX00-0X0Y
Directory of C:\Users\John

11/20/2024  03:45 PM    <DIR>          .  
11/20/2024  03:40 PM    <DIR>          ..  
11/20/2024  03:30 PM           320.450 ITA2025_Guide.pdf  
11/20/2024  03:44 PM           512.700 Study_Schedule.xlsx  
               2 File(s)        833.150 bytes  
               2 Dir(s)    85.324.211.200 bytes free
```
```bash
C:\Users\John>cls
```
### After

```bash
C:\Users\John> 









```

5. shows the current date and allows you to change the system date
```bash
C:\Users\John>date
```
```bash
C:\Users\John>date
Current date: 11/21/2024
Enter the new date: (mm-dd-yy)

```
#### If you don't want to change it, just click the ENTER key again.

6. similar to the previous command, it allows you to change and modify the time
```bash
C:\Users\John>time
```
```bash
C:\Users\John>time
Current time:  1:05:56.44 AM  
Enter the new time:

```
#### If you don't want to change it, just click the ENTER key again.

7. show computer name
```bash
C:\Users\John>hostname
LAPTOP-0XXXX0xx
```
8. show the current version of your machine
```bash
C:\Users\John>ver
Microsoft Windows [versão 10.0.22631.4317]
```

9. Close CMD
```bash
C:\Users\John>exit
```

10. change CMD colors
```bash
C:\Users\John>color backgroundcolorFontColor
```
### example
```bash
C:\Users\John>color 0A
```
### for more colors, seek help with the help command

#### to return to the default color just type the word color
```bash
C:\Users\John>color
```

11. turn off the computer

```bash
C:\Users\John>shutdown 
```

### for more options for this command, just search for the help command followed by the command name
