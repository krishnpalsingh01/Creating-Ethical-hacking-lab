#Ethical Hacking Lab Setup Using VirtualBox
Introduction
This guide outlines the steps to set up an Ethical Hacking Lab using VirtualBox. 

System Requirements
Host OS: Windows, Linux, or macOS
RAM: Minimum 8GB
Storage: 20GB+ free space

Software:
VirtualBox
Windows 10 Superlite Ghost ISO
VirtualBox Guest Additions
Ethical Hacking Tools

Installation Guide

Step 1: Download Required Files
VirtualBox: Download from here. https://www.virtualbox.org/wiki/Downloads
Windows 10 Superlite Ghost ISO: Download from here. https://archive.org/details/ghost-spectre-windows-10
Guest Additions: Download from here. https://www.virtualbox.org/manual/ch04.html
Lab Setup Folder: Save your ethical hacking tools in this folder.

Step 2: Create a Virtual Machine
Open VirtualBox and click "New".
Name: EthicalHackingLab, Type: Microsoft Windows, Version: Windows 10 (64-bit).
Allocate 4GB RAM and 20GB+ storage.
Attach the Windows 10 Superlite ISO and start installation.

Step 3: Install VirtualBox Guest Additions
After Windows installation, go to Devices > Insert Guest Additions CD Image.
Run VBoxWindowsAdditions.exe and restart the VM.

Step 4: Share Lab Tools Folder
Go to Settings > Shared Folders in VirtualBox and add your Lab Setup Folder.
Enable Auto-mount and start the VM to access the shared folder.
Note:(Folder will not be shared by me i had provided link of resources that are available in folder you can download resources and
insert all item in one folder and can attempt this step.)

Step 5: Install Hacking Tools
Python: Install from python.org, then install libraries using pip.
Java JDK: Download from Oracle.
MySQL: Download from MySQL.
SSMS: Download from Microsoft.
Browsers: Install Google Chrome and Mozilla Firefox.
Metasploit: Install from Metasploit.
Wireshark: Download from Wireshark.
Burp Suite: Download from Burp Suite.

Step 6: Finalize Setup
Take a snapshot of the VM for easy restoration.
Test each tool to ensure everything works as expected.




