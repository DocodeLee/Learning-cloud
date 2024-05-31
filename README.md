# 2024 05 29 linux-basic-for hacking
For the whole day i spent to learn kali linux.
Firt They cannot find the filename, and even i couldn't run virtual box.
I don't have enough space so i clear some files.
But there was no iso image even i download the full file. and i release
The problem was simple just download 
https://www.kali.org/get-kali/#kali-installer-images
Let me dive into Linux
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/bdf21f45-2409-4107-9450-017ef30d5c9c)
This is the first access to kali
## Binary: files that can be executed
## Case sensitivity 
## Directory -Folder
## Home : their own /home directory
## Shell This is an environment and interpreter for running commands in Linux.
Linux has many different shell environments, the most popular is the bash shell,

## File system in linux
 Linux doesn’t have a physical drive (such as the C: drive) at the base of the filesystem but uses a logical filesystem instead.
 ![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/c054105a-e93d-4f80-8584-64c9809956ef)
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/ef61a437-12c2-4b51-b0d4-5482b401f882)
### pwd: finding yourself
### whoami checking login
### cd: change the directories
### ls -1 provides us with significantly more information, such as whether an object is a file or directory, the number of links, the owner, the group, its size, when it was created or modified, and its name.
### ls -la shows hidden file
## Getting help
>aircrack-ng --help
>nmap -h
## most commands and applications have a manual (man) page with more information
## Searching with locate
Use the locate buut locate command is not perfect
## If you are finding Binary file you can use whereis command
## which command is even more specific: it only returns the location of the binaries in the patH variable
## FIND
### find / -type f -name apache2
It browse every file so it takes time. so if you can specify the file can save the tiem (/etc /bin ....)
## Filtering with grep
###  grep command is often used when output is piped from one command to another.
Linux (and Windows for that matter) allows us to take the output of one command and send it as input to another command.
we use the | command to do it
 ps command is used to display information about processes running on the machine. 
 ![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/6b41bca9-4c4c-4e8e-9c98-4fdd39e57a6f)
 #### I met new problem the permission problem. i search for the solutions
  - sudo, chom didn't work
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/239b5825-c1d2-44c4-9657-a0d2d8885591)
#### I found that the root was the problem
# 2024 05 30
### When you use the cat command after you finish the input ctrl + D will be reform the commnad line
### CAT vs TOUCH
Touch command is used to create a new empty file without preview and also used to update a time and date stamp of a file which is already exist. And the cat command is used to create a new single or multiple file with preview and also used to dump(view) file data in a terminal.
## Creating Directory
### Directory is folder you can save file in directory
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/07fe8b73-d70f-424b-8416-463c2c607679)
#### when you copy to file to other place use cp filename root(~/newdirectory)
## Renaming the name
In linux there is no command for rename for this you need to use move command. $move original-name new-name
## Removing
rm is for file rmdir is for directory
but you cannot remove the directory which is not empty/ if you delete the all the content. rm -r command will help to delete the directory
## network intrusion detection system
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/1b0d2912-52a2-4b75-8233-93d200be98c4)
#### I downloaded the snort from the kali homepage
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/e64e84ae-ec97-4510-b77f-0330ba37acee)
#### Even i downloaded i cannot find snort.conf
#### The reason was they changed the filename from conf to lua lol
### head /etc/snort/snort.lua (head -number /....) set the line you want to see 
### tail will show the last part
## Thre is no mysql in snort.lua
In the book they find mysql using cat /etc/snort/snort.lua | grep mysql
but i don't have my sql in this version or maybe i am wrong.
#### if you want to copy specific content use this
sed s/mysql/MySQL/g /etc/snort/snort.conf > snort2.conf
##### this mean replace mysql to MYSQL, g means globally and result will be saved in snort2.conf
## when you are working with large file, more or less will be better than cat
# CH.3
## ifconfig shows some useful information about the active network interfaces on the system
Eth0 mean ethernet0 = first wired connection
Second line showed me the IP address.
#### broadcast address, which is the address used to send out information to all IPs on the subnet; and finally the network mask
### lo : short for loopback address and is sometimes called localhost.
## Changing Your IP Address
#### I couldn't change the IP by ifconfig eth0 [IP ADDRESS]
#### I used sudo infront of the command
#### ifconfig ethO 192.168.181.115 netmask 255.255.0.0 broadcast 192.168.1.255
#### DHCP : a networking protocol for dynamically assigning IP addresses to each host on your organization's network
## dig, which offers a way to gather DNS information about a target domain.
#### dig hackers-arise.com ns ...... ns is shortname for nameserver

#### dig hackers-arise.com mx ...... mx is shortname for mail exhcange server

## For changing DNS you can use leafpad
### leafpad /etc/resolv.conf
### echo "nameserver 8.8.8.8"> /etc/resolv.conf
This comand change the nameserver and store it
## Download the software
### apt-cache search keyword / help you to find the software
### apt-get install package / download the software you want
### when you want to remove ] apt-get remove package / will be used
but it remains the configuration files so if you want to all-clear need to use apt-get purge package
#### The servers that hold the software for particular distributions of Linux are known as repositories.
## USING A GUI-BASED INSTALLER
apt-get install synaptic
And i can find the files or directory in GUI
#### you can clone the ]git clone git-url
#### when you want to change owner chown command is the thing you find
#### file you don’t have permission to execute and give yourself execute permissions using the chmod command. 
## Viewing process
ps command is best choice
PID : process ID
