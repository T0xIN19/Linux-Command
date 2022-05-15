# Linux-Command


→ ls-al: Lists files and directories with detailed information like permissions,size, owner, etc.

→ ls: Lists all files and directories in the present working directory

→ ls-R: Lists files in sub-directories as well

→ ls-a: Lists hidden files as well

→ cd or cd ~: Navigate to HOME directory

→ cd ..: Move one level up

→ cd: To change to a particular directory

→ cd /: Move to the root directory

→ cat > filename: Creates a new file

→ cat filename: Displays the file content

→ cat file1 file2 > file3: Joins two files (file1, file2) and stores the output in a new file (file3)

→ mv file "new file path": Moves the files to the new location

→ mv filename new_file_name: Renames the file to a new filename\

→ sudo: Allows regular users to run programs with the security privileges of the superuser or root

→ rm filename: Deletes a file

→ man: Gives help information on a command

→ history: Gives a list of all past commands typed in the current terminal session

→ clear: Clears the terminal

→ mkdir directory_name: Creates a new directory in the present working directory or an at the specified path

→ rmdir: Deletes a directory

→ mv: Renames a directory

→ pr -x: Divides the file into x columns

→ pr -h: Assigns a header to the file

→ pr -n: Denotes the file with Line Numbers

→ lp -nc , lpr c: Prints "c" copies of the File

→ lp-d lp-P: Specifies name of the printer

→ apt-get: Command used to install and update packages

→ mail -s 'subject' -c 'cc-address' -b 'bcc-address' 'to-address': Command to send email

→ mail -s "Subject" to-address < Filename: Command to send an email with an attachment

-------------------------------------------------------------Hardware commands--------------------------------------------------------------------

→ dmesg: Displays bootup messages

→ cat /proc/cpuinfo: Displays more information about CPU e.g model, model name, cores, vendor id

→ cat /proc/meminfo: Displays more information about hardware memory e.g. Total and Free memory

→ lshw: Displays information about system's hardware configuration

→ lsblk: Displays block devices related information

→ free -m: Displays free and used memory in the system (-m flag indicates memory in MB)

→ lspci -tv: Displays PCI devices in a tree-like diagram

→ lsusb -tv: Displays USB devices in a tree-like diagram

→ dmidecode: Displays hardware information from the BIOS

→ hdparm -i /dev/xda: Displays information about disk data

→ hdparm -tT /dev/xda <:code>: Conducts a read speed test on device xda

-----------------------------------------------------------File Permission commands-------------------------------------------------------

→ ls-l: to show file type and access permission

→ r: read permission

→ w: write permission

→ x: execute permission

→ Chown user: For changing the ownership of a file/directory

------------------------------------------------------------Network command --------------------------------------------------

→ SSH username @ ip-address or hostname: login into a remote Linux machine using SSH

→ Ping hostname="" or ="": To ping and Analyzing network and host connections

→ dir: Display files in the current directory of a remote computer

→ cd "dirname": change directory to "dirname" on a remote computer

→ put file: upload 'file' from local to remote computer

→ get file: Download 'file' from remote to local computer

→ ip addr show: Displays IP addresses and all the network interfaces

→ ifconfig: Displays IP addresses of all network interfaces

→ ping host: ping command sends an ICMP echo request to establish a connection to server / PC

→ whois domain: Retrieves more information about a domain name

→ dig domain: Retrieves DNS information about the domain

→ dig -x host: Performs reverse lookup on a domain

→ host google. com Performs an IP lookup for the domain name

→ hostname -i: Displays local IP address

→ wget file_name:: Downloads a file from an online source

→ netstat -pnltu: Displays all active listening ports

→ quit: Logout

-----------------------------Environment Variables command--------------------------------------

→ echo $VARIABLE: To display value of a variable

→ env: Displays all environment variables

→ VARIABLE_NAME= variable_value: Create a new variable

→ Unset: Remove a variable

→ export Variable=value: To set value of an environment variable

------------------------------------------------------User management commands of linux----------------------------------------

→ sudo adduser username: To add a new user to your current Linux machine

→ sudo userdel -r 'username': deluser removes a user from a specific group.

→ finger: Gives information on all logged in user



Thank you
