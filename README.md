#### **Introduction-to-Linux (1.0)** ######

#Getting started with Linux :-

#### 1. **Change the hostname**:
  ----> sudo hostnamectl set-hostname <your hostname>
  ----> exec bash 

#### 2. **To view the username**:
  -----> whoami

#### 3. **Hostname of the server**:
 ----> hostname 

#### 4. **Location where we are present** 
-----> pwd

#### 5. **Command that lists out the contenet with metadata**
------> ls -l

#### 6. Command that list out all the metadata of normalfiles,directories and hidden files and directories
-----> ls -al

##### 7. gives the output of ls -al command 
-----> ll

##### 8. get the output for the ls command 
------> l

##### 9. To find the shell interpreter assigned
------> echo $SHELL

##### 10. To view/switch to other shell interpreters
------> cat /etc/shells

Choose a shell type that you want to switch to by typing 

/bin/<shelltype>
/bin/sh 
...
...
To exit the out of the shell and get back to default, exit

**(Various shell interpreters are present in a Linux server and every interpreter has its own way of interpreting the commands Always prefer to choose /bin/bash shell interpreter)**
