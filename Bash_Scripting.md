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
