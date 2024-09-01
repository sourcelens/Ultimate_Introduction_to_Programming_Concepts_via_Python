---
---


```
testvariable = 10

def function1():
    print("Inside function1")
    testvariable = 1000
    print( testvariable )
    for i in range(2):
        print( testvariable )
        testvariable = 2000
        print( testvariable )
        if i == 1:
            print( testvariable )
            testvariable = 3000
            print( testvariable )
        print( testvariable )    
    print( testvariable )
    print("Done with Function1")

def function2():
    print("Inside function2")
    for i in range(2):
        if (i == 0 ):
            testvariable = 3000
            print( testvariable )
        print( testvariable )    
    print( testvariable )
    print("Done with Function2")  

function1()
print( testvariable )
function2()
print( testvariable )
```

1 : In the above lines of code which one is the Global variable?  

a) Line 1  
b) Line 5  
c) Line 23  
d) Line 9  

**Answer** a) 

**Description**

Line 1 is the global variable which is available throughout the program and local variables are available throughout the function.  

---
---


```
testvariable = 10

def function2():
    print("Inside function2")
    for i in range(2):
        if (i == 0 ):
            testvariable = 3000
            print( testvariable )
        print( testvariable )    
    print( testvariable )
    print("Done with Function2")  

function2()
print( testvariable )
```

2 : What Line 3 to Line 11 in the above lines of code do?  

a) Definition of function2  
b) Definition of function1  
c) Calling function1  
d) Calling function2  

**Answer** a) 

**Description**

It is the definition of function2. We have an if condition in Line 6 and the variable definition is inside the if condition. The variable creation is happening in the innermost if condition, in Line 7.  

---
---


```
testvariable = 10

def function1():
    print("Inside function1")
    testvariable = 1000
    print( testvariable )
    for i in range(2):
        print( testvariable )
        testvariable = 2000
        print( testvariable )
        if i == 1:
            print( testvariable )
            testvariable = 3000
            print( testvariable )
        print( testvariable )    
    print( testvariable )
    print("Done with Function1")

function1()
print( testvariable )
```

3 : What the above lines of code from Line 3 to Line 17 does?  

a) Function call  
b) Definition of function 1  
c) Definition of function 2  
d) None of the above  

**Answer** b) 

**Description**

Line 3 to 17 constitute the definition of function1. Most of it is different types of print statements and we have a variable which is the test variable and it is a Local variable. We have a for loop also.

---
---





