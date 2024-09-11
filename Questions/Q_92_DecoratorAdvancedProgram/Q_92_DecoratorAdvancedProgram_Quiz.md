---
---


```
#
def decor1(func):
    def inner():
        x = func()
        return x * x
    return inner

def decor(func):
    def inner():
        x = func()
        return 2 * x
    return inner

@decor1
@decor

def num():
    return 10

@decor
@decor1

def num2():
    return 10

print( num() )
print( num2() )
```

1 : In the above lines of code what is Line 2, 8 doing?  

a) Function Calling   
b) Function Definitions  
c) Function Overloading  
d) None of the above  

**Answer** b) 

**Description**

They are function definitions; nothing is getting executed here. We are taking only the definitions of two functions.  

---
---


```
#
def decor1(func):
    def inner():
        x = func()
        return x * x
    return inner

def decor(func):
    def inner():
        x = func()
        return 2 * x
    return inner

@decor1
@decor

def num():
    return 10

@decor
@decor1

def num2():
    return 10

print( num() )
print( num2() )
```

2 : In the above lines of code what is Line 14, 15 doing?  

a) Decorator Functions   
b) Pointer Functions   
c) Function Overloading  
d) None of the above  

**Answer** a) 

**Description**

Line 14 and 15 are the decorators. To decorate num we need to get into the definition of Line 15 and 14 because those are the lines of code which will decorate the function at Line 17. So, we need to get into the code of that and we will get into the order first Line 15 and then Line 14. Because first we need to decorate num with @decor then with @decor1.  

---
---


```
#
def decor1(func):
    def inner():
        x = func()
        return x * x
    return inner

def decor(func):
    def inner():
        x = func()
        return 2 * x
    return inner

@decor1
@decor

def num():
    return 10

@decor
@decor1

def num2():
    return 10

print( num() )
print( num2() )
```

3 : In the above lines of code, while we executing @decor, the control will go to Line_____?  

a) Line 3   
b) Line 9   
c) Line 26   
d) None of the above  

**Answer** b) 

**Description**

Line 9 is the definition of @decor, the first decorator or the immediate decorator. We are taking that definition and decorate num. Here we are only taking the definition and using it for decoration, not getting executed yet.

---
---


```
#
def decor1(func):
    def inner():
        x = func()
        return x * x
    return inner

def decor(func):
    def inner():
        x = func()
        return 2 * x
    return inner

@decor1
@decor

def num():
    return 10

@decor
@decor1

def num2():
    return 10

print( num() )
print( num2() )
```

4 : In the above lines of code, while we executing @decor1, the control will go to Line_____?  

a) Line 3   
b) Line 9  
c) Line 26   
d) None of the above  

**Answer** a) 

**Description**

Line 3 is the definition of @decor1. Here we are only taking the definition and using it for decoration, not getting executed yet.  

---
---


```
#
def decor1(func):
    def inner():
        x = func()
        return x * x
    return inner

def decor(func):
    def inner():
        x = func()
        return 2 * x
    return inner

@decor1
@decor

def num():
    return 10

@decor
@decor1

def num2():
    return 10

print( num() )
print( num2() )
```

5 : In the above lines of code, what is happening at Line 17?  

a) Executing the function  
b) Calling the function  
c) Making the definition   
d) None of the above  

**Answer** c) 

**Description**

At Line 17 we are making the definition of the function num, not executing the function yet. We are preparing this function here with all the decorators and its definitions.  

---
---


```
#
def decor1(func):
    def inner():
        x = func()
        return x * x
    return inner

def decor(func):
    def inner():
        x = func()
        return 2 * x
    return inner

@decor1
@decor

def num():
    return 10

@decor
@decor1

def num2():
    return 10

print( num() )
print( num2() )
```

6 : In the above lines of code, what is happening at Line 26?

a) Executing the function  
b) Decorating the function   
c) Making the definition   
d) None of the above  

**Answer** a) 

**Description**  

Here is the actual function is going to get executed. This code has rewritten with two decorators. @decor is the inner decorator, @decor1 is the outer decorator. So, the call is going to come to the outer decorator first that is where the first decorator is present. The function we are passing to Line3 is the decorated version of num.

---
---











