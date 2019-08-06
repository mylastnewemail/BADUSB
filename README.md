# BADUSB
This project include scripts that I have created for the Rubber Ducky by HAK5 and Malduino Elite by Maltronics

Updates:

TUESDAY 06 AUGUST 2019
 - REVERSE-SHELL-INSTALLATION.txt update (1600H)
    - added alt-f4 function to close Command Line so the victim doesn't know the computer has been tampered with.
    - script is too long to be run on BadUSBs therefore the script has been split into two:
       - The installation section is still in REVERSE-SHELL-INSTALLATION.txt however the execution of script has been put in a new script called REVERSE-SHELL-EXECUTION.txt
    
MONDAY 05 AUGUST 2019
 - added folder for scripts written in Ducky language (1300H)
    - added DISABLE-REALTIME-PROTECTION.txt, this script goes through windows defender and disables real-time protection(1300H)
       - spell check correction (2100H)
    - added REVERSE-SHELL-INSTALLATION.txt, This script creates a hidden folder disguised as a Windows Drivers folder that then copies a reverse shell file to victim's computer and executes (1800H)
 - organisation of files and folders (2200H)
    - scripts have now been moved into sub-folders ready for future scripts
       - DISABLE-REALTIME-PROTECTION.txt has been moved to BADUSB\DUCKY SCRIPTS\HACKS\ANTI-VIRUS
       - REVERSE-SHELL-INSTALLATION.txt has been moved to BADUSB\DUCKY SCRIPTS\HACKS\FILE MODIFICATION
