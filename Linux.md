

**Introduction to Linux : 

What is Linux ? what is the difference between all the available Linux distributions ?
What is a Shell ? 

**Common system commands 

how to get your current username ?
how to get your distribution's name ? 
Get your current working directory 
Get your system's date and time 
Get your system's free ram 
Check processes 
Use man, info and --help to get more info on any linux command 


**File system basics 

Hierarchy Understanding `/`, `/home`, `/etc`, `/var`, `/bin`, `/usr`, `/dev`
Overview of File System Hierarchy Standard :
https://docs.redhat.com/en/documentation/red_hat_enterprise_linux/4/html/reference_guide/s1-filesystem-fhs#s3-filesystem-mnt
Absolute and relative paths 
Symlinks

**File and Directory Commands

Folder navigation using ls, pwd, cd 
Folders and files management : `mkdir`, `rmdir`, `touch`, `rm`, `cp`, `mv`

**File Permissions

Visualize the `rwx` permissions using ls -l or ll 
Manipulate the `rwx` permissions using chmod, chown, chgrp 
Different ways of handling permissions, ( octal vs symbolic permissions)

**Text Manipulation

Experiment with the following : 
- Viewing: `cat`, `less`, `more`, `head`, `tail`.
- Searching: `grep`, `find`, `locate`.
- Editing: `nano`, `vim`, `sed`, `awk`.
- Comparing: `diff`, `cmp`.
- Sorting: `sort`, `uniq`.
- Counting: `wc`.


**Security

experiment `iptables` or `ufw` for firewall configurations
Understanding SELinux and AppArmor


**Users and groups 

Mess around with user management commands such as `adduser`, `userdel`, `passwd`
group management commands `groupadd`, `groupdel`.
switch to another user using su and sudo 


**Shell Scripting Basics

Understand why we use the shebang statement : #!/bin/bash
Variables, loops, and conditionals - while at it checkout exitcodes 
Scheduling tasks `cron`, `at`


We'll see more linux as we go 