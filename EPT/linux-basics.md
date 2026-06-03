# Linux Basics

This file contains fundamental Linux commands and concepts learned during my Ethical Hacking & Penetration Testing subject and hands-on practice.

---

## What is Linux?

Linux is an open-source operating system widely used in cybersecurity, servers, and penetration testing environments. It is known for its flexibility, security, and command-line interface.

---

## File System Navigation

### pwd (Print Working Directory)
Shows the current directory location.

### ls (List Files)
Lists files and folders in the current directory.

ls
ls -l   # detailed view
ls -a   # includes hidden files

### cd (Change Directory)
Moves between directories.

cd /home/user
cd ..
cd ~

### mkdir (Make Directory)
Creates a new folder.

mkdir test_folder  

### touch (Create File)
Creates an empty file.

touch file.txt  

### chmod (Change Permissions)
Controls who can read, write, or execute a file.

chmod 755 script.sh

Permission Breakdown:
r = read
w = write
x = execute

### sudo (Superuser Do)
Allows a permitted user to run commands as an administrator.

sudo apt update

Important for performing system-level tasks securely.

### cat (Concatenate)
Used to read, create, and combine file contents.

cat file.txt

### less
View large files page by page

less file.txt

### grep
Searches for patterns inside files.

grep "password" file.txt


# Why This Matters for Cybersecurity
Linux is widely used in servers and security tools
Many penetration testing tools run on Linux
Understanding permissions helps prevent privilege abuse
Command-line skills are essential for cybersecurity roles

# What I Learned
Linux is a command-line driven system used heavily in cybersecurity
File navigation and permissions are critical for system control
Tools like grep and chmod are essential for security analysis
sudo allows controlled privilege escalation for administrative tasks