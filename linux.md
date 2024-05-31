# IMPORTANT LINUX COMMANDS

Interfaces - 1--> GUI (Graphical User Interface) 2--> CLI (Command Line Interface)
Windows focus on GUI and Linux focuses on CLI. Both have its uses and benefits.

1. ls - List Directory contents
2. pwd - Print Working Directory (print the current directory path in which you are currently working.)
3. mkdir directory_name: This command is used to create new directories with given names.
4. touch filename: This command is used to create empty files with given file name.
5. mv filename destination_directory: This command is used to move the specified file or folder from one location to another. It can also be used to rename a file or directory.
6. rm - Remove Files and Directories (Remove Files and Folders)
7. cp filepath destination_directory: This command is used to copy files or folders with given paths from one location to another.

# Users in Linux

1. Regular User: It can work inside its home directory. But it can not access other users home directory. And also it can not change the system settings and configurations. So, only regular user is able to perform all these activities.

2. Root User: Full Access. It can access all the directories. Also, it can access all the files in its own home directory as well as other users home directory. And also it can change the system settings and configurations. So, only root user is able to perform all these activities.

-   Use sudo from regular user to perform any activity that requires full access privileges by default.

3. Service User: If some service is running on Linux like Jenkins, then they have their own users.

# Absolute vs Relative Path

/ -> Root Note
Root -> bin, etc, apps ....
bin -> file1, file2

# More Commands in Linux

1. apt - We can install softwares and update softwares also update softwares.
2. sudo apt-get update: This command is used to get the update version of all the packages. So, this command is used to check for any updates available on internet and also it can be used to get the list of all the packages that are currently installed in your system.
3. sudo apt-get upgrade: This command will actually install the updated softwares. So, this command is used to update all the installed software in our system.
4. ls -R: This command will list all the files in the current directory and also all the subdirectories recursively.

-   Use this filename format to create hidden files eg .himanshu

5. ls -a: This command will list all the files in the current directory along with the hidden files
6. ls -lart: This command will list all the files in the current directory along with their attributes and also it can be used to sort all the listed files according to their last access time, last modification time or creation time respectively.
7. history: This command will give the history of all the commands you have executed in terminal

-   Filenames are case sensitive in Linux. We can create multiple files with names like Himanshu.txt, HIMANSHU.txt, Himanshu.txt etc

8. ls -l: This will give the information about who can perform which operations on the file. Who is the owner and creator file. It usually gives read,write,execute for Owner, Group and Public. Please use chmod calculator online for editing these rights.

9. chmod num filename - Use chmod calculator to get the number. And this command is used to update the read, write, execute for a file
10. chgrp group_name: Change grp for a file
11. top - This command tells which background process are taking most of the memory
12. ps - Gives the current running processes (run by user)
13. kill process_id: This command is used to kill processes like we do in task manager
14. sudo apt install vim: This command is used to install vim editor, so that we can edit files from the terminal.
15. Once you enter vim editor:

    press i to insert text into the file.
    After editing is complete. press esc to go out of editing mode
    :q! to quit without saving your changes
    :wq to quit and save the changes
