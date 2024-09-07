---
---


```
#
import os
print(os.environ)
print(os.environ.get('USER'))
```

1 : The above lines of code are for printing___________?  

a) Environment variables   
b) Loops  
c) Functions   
d) All of the above  

**Answer** a)  

**Description**

This program is for Printing the current environment variables and the value of the USER environment variable (if it exists).  

---
---


2 : What are environment variables?  

a) Key value pairs  
b) Integers   
c) Text editors  
d) All of the above  

**Answer** a)  

**Description**

Environment variables are nothing but key value pair. The three main places an application get environment variables are from system environment variables, next from user environment variables and then from the parent process ( application that starts another application ).  

---
---


3 : From where python.exe is getting environment variables?  

a) sys env, user env, cmd  
b) Only from cmd  
c) Only from sys env   
d) All of the above  

**Answer** a)  

**Description**

It is getting environment variables mainly from three sources. One is System Environment Variables, then from User Environment Variables. Third is Environmental variables from parent process that starts python.exe. If python program is started from  cmd, it inherits the environment variables from that parent process.  

---
---


4 : start -> env -> Edit the system environment variables will give access to __________?  

a) To access system and user environment variables  
b) To access processes   
c) To access cmd  
d) All of the above  

**Answer** a)  

**Description**

In windows to access system and user environment variables go to start, env, edit the system environment variables. System variables are injected into all the programs running on the system, doesn’t matter it is started by which user or network.  

---
---


5 : The command to add environment variables via cmd in windows is _______?  

a) set   
b) get   
c) put   
d) All of the above  

**Answer** a)  

**Description**

The command to add environment variables in windows is set. set USER = Thisistestvariable. Here USER is the variable we are going to add which is the key and Thisistestvariable is the value of that variable. If we add space inside value like This is test variable ensure that it is enclosed within “”.

---
---


6 : Which module is used to access environment variables in a Python program?  

a) import os   
b) import sys   
c) import system   
d) All of the above  

**Answer** a)  

**Description**

 It is accessed by import os. Here os means operating system. os.environ is the object we are using.  

 ---
 ---


 
