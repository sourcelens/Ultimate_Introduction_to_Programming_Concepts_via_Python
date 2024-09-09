---
---


1 : Array out of bound comes to ___________type of exception?  

a) Hardware exception   
b) Software exception   
c) User generated exception   
d) None of the above  

**Answer** b) 

**Description**  

In the case of exceptions like array out of bound etc. it is created by the python framework itself. It is a software generated exception.   

---
---


```
#
def myexepfun():
    raise Exception("test")
try:
    myexepfun()
except Exception as err:
    print(err)
```

2 : What it does, raise Exception(“test”) in the above lines of code?  

a) Creating an exception object   
b) Creating a solution   
c) Creating a variable  
d) None of the above  

**Answer** a) 

**Description**  

We have a function, myexepfun () which does raise Exception("test"). raise Exception("test") is creating an exception object right here and raising it. That means creating or generating an exception. raise is a keyword in python to generate exception object.

---
---


```
#
class SourceLensException(Exception):
      pass

def myexepfun():
    raise SourceLensException("Very specific SourceLens Exception")
try:
    myexepfun()
except SourceLensException as err:
    print(err)
```

3 : In the above lines of code what is Line 2,3 doing?  

a) Deriving a class   
b) Deriving a library   
c) Deriving a built-in function   
d) None of the above  

**Answer** a) 

**Description**

Using the keyword class, we are creating a custom exception class. Here we are deriving a custom class called SourceLensException from an existing class (Exception).  

---
---



