---
---


1 : What is meant by Multifile programming?  

a) Organizing the program into different files  
b) Organizing the program into different classes  
c) Organizing the program into different names  
d) None of the above  

**Answer** a) 

**Description**  

Multifile programming is organizing a program into different files. Whenever the program gets big, we can’t keep that in one single file. A good programming practice is 1000 to 2000 lines in a file. There are exceptions to this rule as well. Whenever the program gets big make sure that we split it into different files.   

---
---


```
#
from multifile import sum
print ( sum (1,2) )
```

2 : What do the above lines of code demonstrate? ( multifile is a file )  

a) Importing a built-in Python function to calculate the sum of two numbers  
b) Importing and using a function from a file named multifile to add two numbers  
c) Organizing the program into different names   
d) None of the above  

**Answer** b) 

**Description**

The code demonstrates importing the sum function from a Python file named multifile.py and then using this function to add the numbers 1 and 2, followed by printing the result. This indicates the use of a function defined in a separate Python file.  

---
---


```
#
def sum(a,b):
    return a+b+100

def extrasum(a,b):
    return a+b+999
```

3 : What does the above lines of code show?  

a) Definition of Functions  
b) Function call   
c) organizing the program into different functions   
d) None of the above  

**Answer** a) 

**Description**

Here we have two functions which take two arguments each. 

---
---


4 : What are the other names of Multifile programming in different programming languages?  

a) Hash define   
b) Import   
c) Package  
d) All of the above  

**Answer** d) 

**Description**

All above are the different names for this particular concept. Basically, what it means is splitting the code into different files to reduce the complexity of a particular file.  

---
---


```
#
from multifile import sum , extrasum
print ( sum (1,2) )
print( extrasum(1,2) )
```

5 : What does Line 2 in the above lines of code do?  

a) Import multiple functions from multifile   
b) Adding more stuffs into multifile   
c) Deleting functions from multifile   
d) All of the above  

**Answer** a) 

**Description**  

Line 2 performs an import operation from a file named multifile. Specifically, it imports two functions named sum and extrasum into the current namespace.   

---
---


```
#
import multifile 
print ( multifile.sum (1,2) )
print( multifile.extrasum(1,2) )
```

6 : What does the Line 2 of above code do?  

a) Import an entire module/file named multifile   
b) Adding more stuffs into multifile   
c) Deleting functions from multifile  
d) All of the above  

**Answer** a) 

**Description**

The provided code demonstrates how to import an entire file named multifile and then access functions within it using the file name as a prefix. 

---
---


```
#
import multifile as testmf 
print ( testmf.sum (1,2) )
print( testmf.extrasum(1,2) )
```

7 : What Line 2 does in the above snippet of code?  

a) Imports the multifile and calls a function 'testmf'  
b) Imports the multifile and assigns an alias 'testmf'  
c) None of the above  
d) All of the above  

**Answer** b) 

**Description**

The provided code Imports the multifile. Renames the imported file to testmf, allowing you to refer to its functions using this alias.

---
---


```
#
import innerfolder.multifile as testmf 
print ( testmf.sum (1,2) )
print( testmf.extrasum(1,2) )
```

8 : If the Python files we're trying to import are located in different directories, What will happen when we execute the code?  

a) ModuleNotFoundError   
b) Location is not important   
c) The program will end   
d) All of the above  

**Answer** a) 

**Description**

If the files are in different locations and you try to import them using relative imports, you may encounter an ModuleNotFoundError, it's because Python looks for modules in the script's directory and standard locations. To fix this, use dot notation in the import statement, like import innerfolder.multifile, to specify the library's new path.  Line 2 in the above code is to fix this error.  

---
---






