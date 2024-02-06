# Keen-Able-Internship
(**Based on November-2023 batch**)
![photo_6303038419151993282_y](https://github.com/Akshaykumar05/Keen-Able-Internship/assets/114390890/6411af82-8b52-405d-b2a7-632e3404cf51)

* In this repo I am summarising all the related things of this training. There are two parts of the internship.
1. Non-technical
2. Technical

## 1. Non-Tech (6 Tasks) 

| Skills Measuring                                                         | Task                                                                                 
| :------------------------------------------------------------------ | :--------------------------------------------------------------------------------------- |
| 1. Written Communication Skills/ Quality of Work/ Planning & Problem-Solving Skills/ Teamwork | Diwali Office Decoration
| 2. Ability to Learn | Learn Google Spreadsheets.
| 3. Research Skills/ Quality of Work | Search Engine Questionnaire
| 4. Problem-Solving Skills | Brainteaser
| 5. Communication Skills/ Research Skills/ Quality of Work/ Planning & Problem Solving | Teach a Topic
| 6. Research Skills/ Communication Skills/ Quality of Work | Group Discussion

#### [My WBS of these 6 tasks](https://docs.google.com/spreadsheets/d/1XqhWew23b-FNKplvbDdNHRxFnZZv6ZabzMsyWrOodGE/edit?usp=sharing)
#### [DPT Sample](https://docs.google.com/spreadsheets/d/15wWwTZIbxCZoAYrP4czUjAf2vSXrMcjXT2A3DeH6neU/edit?usp=sharing)
#### [DSR Sample](https://docs.google.com/spreadsheets/d/1txpPFfq3oH3lkPiDeoKKaU6cgyGa5g01IISc8BMECJI/edit?usp=sharing)

# Other Tools to learn
* Google Spreadsheet
* Redmine

### Redmine
![](https://raw.githubusercontent.com/docker-library/docs/969091c4c590befe236a71d4a7bce5823fff020d/redmine/logo.png)
* Redmine is a **free and open source**, web-based project management and **issue tracking tool**. It allows users to manage multiple projects and associated subprojects. It features per project wikis and forums, time tracking, and flexible, role-based access control. It includes a calendar and Gantt charts to aid visual representation of projects and their deadlines. Redmine integrates with various version control systems and includes a repository browser and diff viewer.
#### Main features
* Manage all your projects with one Redmine instance
* Each user can have a different role on each project
* Each project can be declared as public (visible by anyone) or private (visible by project members only)
* Modules (eg. wiki, repository, issue tracking, ...) can be enabled/disabled at project level

# Sessions 
1. Public Speaking
2. Email and Google Spreadsheet
3. Empathy and Proactive Behaviour
4. Discussion on GitHub - Discussion among interns.
5. On-line session by Shreesh Chaudhary on "Storytelling". (I shared my Vipassana experience along with PPT) (18/11/23)
6. Book Reading **"But How Do It Know? - The Basic Principles of Computers for Everyone"**. Purpose: to develope curiosity.
   * [Book link](https://www.amazon.in/But-How-Know-Principles-Computers-ebook/dp/B00F25LEVC)
8. How to ask Good Questions.
9. How to search on Google.
10. Book reading **"Mother Pious Lady: Making Sense of Everyday India"**
   [](https://4.bp.blogspot.com/_VMCCOqUYc5c/S_z8Ror_C1I/AAAAAAAABDg/4FYCRI-1DwE/w1200-h630-p-k-no-nu/Mother.bmp)
    * [Book link](https://www.amazon.in/Mother-Pious-Lady-Making-Everyday/dp/8172238649)
11. Experience Sharing Session (By- Ashish Jha, Keenable Employee)
* My Takeaway from the session:
  * Keep the interest in learning (that can be either in your technical stuff or any hobby)
  * Find out the solution if you phase any challange (so that it can't repeat in future)
    
# 2. Technical 
## Documentation
## (Linux 40 task) 🐧
1. File and Folder Create Command (TOUCH, MKDIR, VIM )
* Touch: used to create, change and modify the timestamps of a file.
  - Syntax touch file_name
  - **cat command**: It is used to create the file with content.
  - Sytax: cat file_name
  - **Touch command**: It is used to create a file without any content. The file created using the touch command is empty. This command can be used when the user doesn’t have data to store at the time of file creation.
* mkdir: used used to make a new directory.
* vim: Vim is an advanced and highly configurable text editor built to enable efficient text editing. It supports most file types and vim editor is also known as a programmer’s editor. We can use its plugin based on our needs.
  - Sytax vim file_name
  
2. File and Folder Permission (CHOWN, CHMOD, CHGRP)
* **chown**: used to change the file Owner or group. Whenever you want to change ownership, you can use chown command.
  - Syntax: chown owner_name file_name
* **chmod**
* [Reference](https://www.geeksforgeeks.org/chown-command-in-linux-with-examples/)
4. Check File/Folder/Content (LS, LL, CAT, GREP, HEAD, TAIL, LESS, MORE, ECHO)
5. Copy and Move Command (RM, CP, MV, SCP, RSYNC)
  - **RM Command**: rm stands for remove here. rm command is used to remove objects such as files, directories, symbolic links and so on from the file system like UNIX.
  - Syntax: rm [OPTION]... FILE...
  - **CP Command**: cp stands for a copy. This command is used to copy files or groups of files or directories. It creates an exact image of a file on a disk with a different file name.
  - Syntax: cp [Source_file] [Destination_file]
  - **MV Command**:The mv command in Linux is used to move or rename files and directories. Here are some common use cases:
  - Sytax:mv source_file destination_directory
  - Replace source_file with the name of the file you want to move and destination_directory with the path to the directory where you want to move the file.
  - Renaming a File:

    To rename a file, you can use the mv command as follows:
  - Syntax:mv old_file_name new_file_name
  - Replace old_file_name with the current name of the file and new_file_name with the desired new name.
  - Moving Multiple Files:mv file1.txt file2.txt file3.txt /path/to/destination/




  - **SCP Command**:The scp command in Linux is used for securely copying files between hosts on a network. It stands for "secure copy" and uses the SSH (Secure Shell) protocol for data transfer.
    
  - Syntax:scp [options] [source] [destination]
  -     [options]: Optional parameters that modify the behavior of the scp command. Some common options include:
        -r: Recursively copy entire directories.
        -p: Preserves modification times, access times, and modes from the original file.
        -i <identity_file>: Specifies the identity file (private key) for public key authentication.

    [source]: The file or directory you want to copy. This can be a local path or a path on a remote server specified in the format [user@]host:file.

    [destination]: The location where the file or directory will be copied. This can be a local path or a path on a remote server specified in the format [user@]host:file.

    - Examples:

    Copy a file from local to remote:

    Syntax :scp /path/to/local/file.txt username@remote:/path/on/remote/


  - **RSYNC Command**:
6. User/Group and Access (USERADD, USERDEL, USERMOD, GROUPADD, GROUPDEL, SU, SUDO, SSH,)

    File and Directory Commands:
    
        ls: List files and directories.
    
        cd: Change directory.
    
        pwd: Print working directory.
    
        cp: Copy files or directories.
    
        mv: Move or rename files or directories.
    
        rm: Remove files or directories.
    
        mkdir: Create a new directory.
    
        rmdir: Remove an empty directory.

    Text Processing Commands:
    
        cat: Concatenate and display the content of files.
    
        grep: Search for patterns in files.
    
        sed: Stream editor for filtering and transforming text.
    
        awk: Pattern scanning and processing language.

    File Permissions:
    
        chmod: Change file mode (permissions).
    
        chown: Change file owner and group.

    System Information:
    
        uname: Display system information.
    
        df: Display disk space usage.
    
        free: Display free and used memory.

    User Management:
    
        passwd: Change user password.
    
        useradd: Add a new user.
    
        userdel: Delete a user.
    
        usermod: Modify user properties.

    Process Management:
    
        ps: Display information about active processes.
    
        top: Display and update sorted information about processes.
    
        kill: Terminate processes.
    

    Network Commands:
    
        ifconfig or ip: Display and configure network interfaces.
    
        ping: Check network connectivity.
    
        nslookup or dig: Query DNS information.
    
        netstat: Display network connections, routing tables, interface statistics, masquerade connections, etc.

    Package Management:
    
        apt (Debian/Ubuntu) or yum (Red Hat/Fedora): Install, update, or remove software packages.
    
        dpkg (Debian/Ubuntu) or rpm (Red Hat/Fedora): Package management tools.

    Compression and Archiving:
    
        tar: Create or extract compressed archive files.
    
        gzip, bzip2, xz: Compress or decompress files.

    File System Navigation:
    
        find: Search for files in a directory hierarchy.
    
        locate: Find the location of files.

    **Shell Scripting** completed links
    **Linux networking**  contineue.



    ** Linux Booting Process https://github.com/kshitizShri929/Booting-Process


