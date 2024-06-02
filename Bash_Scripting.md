https://www.youtube.com/watch?v=boqC9QenshY&list=PLT98CRl2KxKGj-VKtApD8-zCqSaN2mD4w&index=2
### I used this course
## Change the shell from zsh to bash
### Checkin the shell command : echo $SHELL
### find the bash at which bash
### chsh -s /bin/bash
## Darra~ you need to restart the kali or your linux
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/59901b3d-9a70-4d69-a61c-2bb6aea6a492)
### Now you have the bash
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/17f7fbab-43f8-466e-8ba4-dff70fc8595d)
### to execute get the permission same with 755 code
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/1b2b3b90-45f9-4185-999a-d86889f23b16)
### Because of the shebang we can expect it runs on the bash
### Hello world : echo "Hello World!"
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/0a623342-6ee9-4086-91fa-2c4d2b4bda75)
### bash has same reference method with javascript just use $variable_name
#### echo $var only react when you designate
### bash use $ sign to discrete with the command or others
### if you exit the variable is cleaned
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/7c9b0c18-a2f0-4806-9f6b-6fdbabbdc77f)
##### you need to use "" when you want to reference if you use '' they get as string
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/6db6c060-d003-4f75-9854-656c4f8c4020)
### It shous why we use script. youo can save time from retyping
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/a0276e99-af92-4c12-92ec-e330d7a88b06)
#### When you want to use command with variable utilize $()
##### The point is variable save your time and you can set the value or command with variable
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/204f3627-d87f-42e1-94bc-7e21d0ac9476)
#### USER is default variable
#### using lowercase prevent the overrlap

# 24.06.01
## basic math in linux
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/ef429657-0729-427b-9a86-4ebd891adf58)
#### + - * % / all you can use with expr
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/69f72510-2d00-43bf-8e10-2bd92815d711)
### you can use variable in math but need to use $ sign to call them
## if statement in linux
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/946416b8-3494-4c07-b8ef-87d26a0eb90c)
### -eq is command for checking equal
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/d2dda12b-1202-4bcf-9559-b4db9f4c415e)
#### else is same with other programming language and ! mean neagtive
#### but in linux you can use -ne (not equal)
### -gt greater than
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/a436433e-6596-41ad-ad12-0bb100cf9445)
### when you find file you can use -f / in case of directory you can use -d
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/1a990d81-33f9-4c1e-9ab9-07e852b8a8a3)
### with touch and rm you can cotrol the file system 
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/8f7b1c68-15b6-4a68-b3b4-9c79235acd66
### In here, commanmd variable calll the htop. and if there is package it runs the package. but if there isn't we are going to install using sudoo command

### apt update : checking the package available
### apt upgrade : this is the actual update
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/28728b8f-4cb2-4819-8102-94701fe7823d)
### It is almost same. but oon if line command -v $command use noramlly to find a pacakge. command is not relevant with variable nmae that is literally commamnd lol
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/36036fbf-832e-49b8-8883-6869680de5b9)
## Exit codes
### when the command works / echo $? shows 0 , but when command doesn't work echo $? shows 2
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/b640ba44-c39f-4485-9cac-b398850f746f)
### redesigned the code for checking exit code
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/f765d600-38b8-432f-adf3-3c79a6219287)
### script using exit codes
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/f6714b76-f354-4cb5-8202-572513bfc058)
### control the file where the result saves so when you check the list after run this code. you can see the package_install_results.log or failure.log on the list
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/2bba403c-37be-4613-a1f3-7f311e3f9a28)
### The line of exit determine the code so echo $? there is no need to run
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/9984b656-33d9-4df7-8d2a-cf0d9f33820e)
## while loop in linux
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/d2e2ef23-c8eb-4a33-9ff7-b0df214896c2)
## second example for linux
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/203839f4-95d3-49c0-b3af-6400ead78f65)
## Univalsal update in linux
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/351124be-5551-462a-b9d8-855ac77f95fc)
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/568536a3-2dbb-40c0-b896-5bafb4624127)
## for loops
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/52d06b29-573c-4e37-aa48-099cc64ebd17)
### simple for loops you can use {1..10} instead of 1 2 3 4 5 6 7 8 9 10
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/ec568b00-c50e-4db9-a5f6-647b42bbd601)
### for loops targeting the files in logfiles directory and has .log extenstion
#### tar command : 'tar' is a command in Linux used for creating, viewing, and extracting files from archives. 
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/7978b602-99a0-4b3e-9bdc-ba6d6058f83f)
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/5225a8a4-6cb8-4ad2-a1e6-40b7f226fae1)
### In tutorial they used ) cp /var/log/*.log logfiles/
#### but there is not log files in my /var
#### i just use touch command to make file in logfiles/ (directory)
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/ba5a583b-ff28-4dcb-905f-ad255d9cf7fc)
#### to test i also made .txt file for checking ability of for loop
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/b24c38af-817b-4a0c-821d-7ee840063db6)
### my for loops made .tar.gz which has .log file (.txt file is just there)
# 2024.06.02
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/b336c8aa-9708-4e45-8a60-17227097f545)
#### There is one script to run. but sometime running at /home woould not the best choice. so if you can move to the local directory, it could be better
### i used move command and changed the permission to root 
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/b7fb2cfe-2a25-4d5a-b66b-60d476350c0b)
#### This code help you set the PATH variable
## When your script is under the default path you don't need to set the path additionally but if you want to store your own directory which is not saved in PATH variable. you need to set the PATh
### That image is for set the path. but when you store the scripts in the /usr/bin/local you don't need to set it 
## Data stream in linux
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/b0042748-f5c7-4045-9ec8-e0d41da7be87)
### This is when i use find command and somewhere they show the permission issue
### But when i type $ find /etc -type f 2> /dev/null
### There is no error about permission but when i type $ echo $? it shows 1 > it means that the code was not perfectly done
## In here i just hide by redirectioning the files to the /dev/null if i erase the 2 i only see the error message like this
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/8fa77a4f-31d7-44e6-940d-70b2bb8c111f)
### actually when you redirection file 1 is default so even you type 1 it will be same result.
### And youcan move the output with 1
### >>  0 for input 1 for output 2 for error 
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/3e721003-bbeb-4c68-8d66-7d1412afb121)
### This command mean send the standard output to result.txt and error to error.txt
## > and >> difference
### both are parse the data but > is overwritten if the file exist, >> is contain the previous and new data.
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/3a960373-1cba-4dd1-b32c-2b70fac885fa)
### simple class in linux
#### semicolone is essential
## if you want to do add while loop put the while [ condition ] /n do and the end add the done line
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/9f648983-e071-47b1-9b1d-d4130c22ae89)
#### when you want to run while loop the end code should be later
![image](https://github.com/DocodeLee/Learning-cloud/assets/167724096/5c2e4ca9-359e-4422-bf94-37b46ae92e11)
#### in here i set the variable to run the while loop, until you change this you can run the while loop
