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


```

