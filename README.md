# Firewall-PowerShell-Scripting
Assignment 3 for firewalls vpns endpoints

Assignment 3

Introduction
Windows firewall is one of the most used application firewalls in use today. The majority of its operation
is transparent to most users. As security professionals you must be familiar with its usage and
configuration.
Purpose
The purpose of this assignment is to add rules to a Windows firewall using a PowerShell script.
Resources
• Windows 10 or 11 VM (do not use bare metal or your own PC’s) which will be the attackers
• Introduction to Scripting in PowerShell Link
• Managing Windows Firewall with command line Link
Tasks
Complete the following tasks:
On a Windows VM of your choosing, create a script with an appropriate name that will implement the
following firewall rules in your Windows firewall. You MUST comment your script to describe what the
next action in the script does.
Note: The following commands from 1 – 6 are to be issued from within your script.
1. Put a comment at the top of your script containing the filename of your script, assignment number
and title, your name as author, the original creation date of the script and the date of your last revision
to the script; make sure to label each so others will know what the information is.
2. Define the following variables: a. SERVER1 as 192.168.4.2 b. TECHSUPPORT1 as 192.168.4.5 c.
UPDATESERVER as 192.168.4.7
3. Allow incoming SSH traffic from TECHSUPPORT1 to your VM. Name your rule techsupportssh.
4. Allow outgoing FTP traffic from your VM to SERVER1 and incoming FTP traffic from UPDATESERVER to
your VM. Name your rules serverftp and updateftp respectively.
5. Enable Logging of allowed connections ONLY on your firewall to a file called allowedconnectionlog. To
prove that your logfile was created, take a screen grab of the directory where it exists and submit this
image within your document.
6. Use your Windows GUI to display the details of each rule and capture your screen to an image for the
rules defined at 3 and 4 above. You will include these screen capture images in your submission
document (remember to show the actual contents of the rule not just its name in the list). This will
require two screen shots for each rule. (1) The contents of the General tab for the rule properties, and
(2) the contents of the Protocols and Ports tab for the rule properties. 
