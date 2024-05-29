# 2024 05 29
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
 I met new problem the permission problem. i search for the solutions
  - sudo, chom didn't work
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/239b5825-c1d2-44c4-9657-a0d2d8885591)
I found that the root was the problem
