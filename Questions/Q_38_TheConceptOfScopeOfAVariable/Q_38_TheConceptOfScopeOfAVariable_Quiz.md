---
---


1 : What are different kind of scopes?  

a) Local scope  
b) Global scope   
c) Both of the above   
d) None of the above  

**Answer** c) 

**Description** 

In Python, scopes determine the visibility and lifetime of variables.They include local scope, global scope, and several other types of scopes.  

---
---


```
testvariable = 10
def function1 ():
    print("Inisde function1")
    testvariable = 1000
    print(testvariable)
function1()
print(testvariable)
```

2 : In the above program which test variable has global scope?  

a) Line 1   
b) Line 4   
c) Both of the above   
d) None of the above  

**Answer** c) 

**Description**

In Line 1 testvariable = 10 has global scope. In Line 4, testvariable has only local scope, that is it will be available only within the function. Line 1 testvariable is available outside the function and have global scope.  

---
---


```
testvariable = 10
def function1 ():
    print("Inisde function1")
    testvariable = 1000
    print(testvariable)
function1()
print(testvariable)
```

3) In the above program which test variable has local scope?  

a) Line 1   
b) Line 4   
c) Both of the above   
d) None of the above  

**Answer** b) 

**Description**

In Line 1 testvariable = 10 has global scope. In Line 4, testvariable has only local scope, that is it will be available only within the function. Line 1 testvariable is available outside the function and have global scope.  

---
---


```
testvariable = 10
def function1 ():
    print("Inisde function1")
    testvariable = 1000
    print(testvariable)
function1()
print(testvariable)
```

4 : What is the output of Line 7?  

a) 10  
b) 1000   
c) Both a) & b)   
d) 1010  

**Answer** a) 

**Description**

testvariable = 10 has global scope, that is outside the function. So, while printing outside the function 10 will get printed.  

---
---


5 : We can access global variable within a function.  

a) True  
b) False  

**Answer** a) 

**Description**

To access global variable inside a function we have to write the keyword ‘global’ before the name of the variable.  

---
---


```
testvariable = 10
def function1():
    print("Inside function1")
    global testvariable
    print(testvariable)
function1()
print(testvariable)
```

6 : In the above program what is the output of Line 5?  

a) 10  
b) Inside function  
c) 100  
d) None of the above  

**Answer** a) 

**Description**

Here we are not defining testvariable within the function. But we are adding a line ‘global testvariable’. So, it takes the global value of the testvariable which we assigned outside the function and it is 10. So, in Line 5 , 10 will get printed.

---
---


```
testvariable = 10
def function1():
    print("Inside function1")
    global testvariable
    print(testvariable)
function1()
print(testvariable)
```

7 : In the above program what is the output of Line 7?  

a) 10   
b) Inside function   
c) 100   
d) None of the above  

**Answer** a) 

**Description**

We are giving a value 10 to the testvariable globally. So, it will get printed.

---
---


```
testvariable = 10
def function1():
    print("Inside function1")
    global testvariable
    print(testvariable)
    testvariable = 1000
    print(testvariable)
function1()
print(testvariable)
```

8 : In the above program what is the output of Line 5?  

a) 1000   
b) 10   
c) 100   
d) None of the above  

**Answer** b) 

**Description**

Here we are not defining testvariable within the function. But we are adding a line ‘global testvariable’. So, it takes the global value of the testvariable which we assigned outside the function and it is 10. So, in Line 5 , 10 will get printed.

---
---


```
testvariable = 10
def function1():
    print("Inside function1")
    global testvariable
    print(testvariable)
    testvariable = 1000
    print(testvariable)
function1()
print(testvariable)
```

9 : In the above program what is the output of Line 7?  

a) 1000   
b) 10   
c) 100  
d) None of the above  

**Answer** a) 

**Description**

Here we are defining testvariable = 10 outside the function globally. Inside the function to get access to it we are adding the line global testvariable. Then we are changing the value of the testvariable to 1000 in Line 6. So, the value of the testvariable will change to 1000 globally. So, in Line 7 1000 will get printed.  

---
---


```
testvariable = 10
def function1():
    print("Inside function1")
    global testvariable
    print(testvariable)
    testvariable = 1000
    print(testvariable)
function1()
print(testvariable)
```

10 : In the above program what is the output of Line 9?  

a) 1000  
b) 10  
c) 100  
d) None of the above  

**Answer** a) 

**Description**

Here we are defining testvariable = 10 outside the function globally. Inside the function to get access to it we are adding the line global testvariable. Then we are changing the value of the testvariable to 1000 in Line 6. So, the value of the testvariable will change to 1000 globally. So, in Line 7 1000 will get printed. In Line 9 also 1000 will get printed, because we are changing the value of the testvariable globally. 

---
---


```
testvariable = 10
def function1():
    print("Inside function1")
    testvariable = 1000
    print(testvariable)
def function2():
    print("Inside function2")
    testvariable = 2000
    print(testvariable)
function1()
function2()
print(testvariable)
```

11 : Which are the types of variables in this program?  

a) 3 global variables   
b) 3 local variables   
c) 1 global variable & 2 local variables  
d) None of the above  

**Answer** c) 

**Description**

Here Line 1 is a global variable. In Line 4 we are defining a local variable which has scope only inside function1. In Line 8 we are defining another local variable which has scope inside function2. So, there are 2 local and 1 global variable.

---
---





