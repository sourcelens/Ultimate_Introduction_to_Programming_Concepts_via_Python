---
---


```
import os
curdir = os.getcwd()

os.system("echo Hello from the other side ! > test1.txt")
os.chdir('c:\\User\\sourc')
os.system("echo Hello from the other side ! > test2.txt")?
```

1 : What does os.getcwd() do in the code?  

a) Retrieves the current working directory  
b) Explains the use of current program   
c) Explains the use of current function   
d) None of the above  

**Answer** a) 

**Description**  

os.getcwd(): This retrieves the current working directory (cwd) of the Python script. curdir variable will store the current working directory path.  

---
---


```
import os
curdir = os.getcwd()

os.system("echo Hello from the other side ! > test1.txt")
os.chdir('c:\\User\\sourc')
os.system("echo Hello from the other side ! > test2.txt")
```

2 : In the above lines of code what we are doing in Line 4?  

a) Creating a text file and redirect output to that text file   
b) Creating a solution   
c) Creating a variable   
d) None of the above  

**Answer** a) 

**Description**  

We are executing the echo command and we are creating a text file here and redirecting the output of echo to that text file.

---
---


3 : What is the use of os.chdir function?  

a) Changing the current directory to a different path  
b) Creating a solution   
c) Creating a variable   
d) None of the above  

**Answer** a) 

**Description** 

This is how we are changing the current directory to a different path.

---
---


```
import os
curdir = os.getcwd()

os.system("echo Hello from the other side ! > test1.txt")
os.chdir('c:\\User\\sourc')
os.system("echo Hello from the other side ! > test2.txt")
```

4 : Are the files created by running the above code created in the same location?  

a) No, Creates the files in different locations   
b) Yes, Creates in same location  
c) Only a single file is created  
d) None of the above  

**Answer** a) 

**Description**

curdir = os.getcwd() retrieves the current working directory when the script starts executing. This directory is stored in the variable curdir. os.system("echo Hello from the other side ! &gt; test1.txt") and os.system("echo Hello from the other side ! &gt; test2.txt") are used to create files test1.txt and test2.txt respectively. os.chdir('c:\\User\\sourc') changes the current working directory to c:\User\sourc. test2.txt is created in this location. test1.txt, however, is created in the original current working directory that was obtained with os.getcwd() in the beginning of the program.  

---
---



