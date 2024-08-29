---
---


```
def xyz1():
    print("Inside function")
print("Before function")
xyz()
print("After function")
```

1 : When we execute the above program which error we will get?  

a) NameError  
b) Syntax error  
c) Both error  
d) None of the above  

**Answer** a) 

**Description**

When you run the provided code, you will get a NameError because the function xyz() is called, but there is no function named xyz defined in the code. The function name defined in code is xyz1. The error is "Exception has occurred: NameError name 'xyz' is not defined".  

---
---


```
def xyz():
    print("Inside function")
  print("Wrong line")
print("Before function")
xyz()
print("After function")
```

2 : In the above program which error you will get?  

a) Indentation error  
b) Function not defined error  
c) Both error  
d) None of the above  

**Answer** a) 

**Description**

In the provided code, you will encounter an IndentationError because the line print("Wrong line") is incorrectly indented. The exact error is: "IndentationError: unindent does not match any outer indentation level".  

---
---


```
def xyz1():
    print("Inside function")
print("Before function")
xyz1()
print("After function")
```

3 : In the above program which print statement is part of the function definition?  

a) print (“Inside function”)  
b) print (“Before function”)  
c) print (“After function”)  
d) All of the above  

**Answer** a) 

**Description**

This is part of the function definition, as it comes under def xyz1 (). It has spaces infront.

---
---


```
def mysum(a, b):
    c = a + b
    return c
print("Before function")
x = 100
y = 200
result = mysum(x, y)
print(result)
print("After function")
```

4 : In the above program a & b are called _______  

a) Arguments  
b) String literal  
c) Number literal  
d) All of the above  

**Answer** a) 

**Description**

a & b are called arguments to the function mysum (). We can give any value to a &amp; b and get the result. We can give any number of arguments to a function. In the below code the function "mysum" takes 2 arguments.

---
---


```
def mysum(a, b):
    c = a + b
    return c
print("Before function")
x = 100
y = 200
result = mysum(x, y)
print(result)
print("After function")
```

5 : What will be printed on the screen after executing Line 8 in the above program?  

a) 100  
b) 200  
c) 300  
d) 400  

**Answer** c) 

**Description**

a and b are the arguments to the function mysum(). Inside the function, we add a and b and assign the result to c, which is then returned. In Line 7, we pass the values 100 and 200 to the arguments a and b. Consequently, the function adds 100 and 200 and returns the result, which is displayed as 300 in Line 8.

---
---


```
def myresult(a, b):
    c = a * b
    return c
print("Before function")
x = 20
y = 10
result = myresult(x, y)
print(result)
print("After function")
```

6 : What will be printed on the screen after executing Line 8 in the above program?

a) 100  
b) 200  
c) 30  
d) 10  

**Answer** b) 

**Description**

a and b are the arguments to the function myresult(). Inside the function, we multiply a and b, assign the result to c, and return c. In Line 7, we pass the values 20 and 10 to the arguments a and b. Consequently, the function multiplies 20 and 10 and returns the result, which is displayed as 200 in Line 8.

---
---


```
def myresult(a, b):
    c = a - b
    return c
print("Before function")
x = 20
y = 10
result = myresult(x, y)
print(result)
print("After function")
```

7 : What will be printed on the screen after executing Line 8 in the above program?  

a) 10  
b) 20  
c) 30  
d) 40  

**Answer** a) 

**Description**

a and b are arguments to the function myresult(). Inside the function, we subtract b from a, assign the result to c, and return c. In Line 7, we pass the values 20 and 10 to the arguments a and b. Consequently, the function performs the subtraction a - b and returns the result, which is displayed as 10 in Line 8.

---
---


```
def myresult(a, b):
    c = a / b
    return c
print("Before function")
x = 20
y = 10
result = myresult(x, y)
print(result)
print("After function")
```

8 : What will be printed on the screen after executing Line 8 in the above program?  

a) 1.0  
b) 2.0  
c) 3.0  
d) 4.0  

**Answer** b) 

**Description**

a and b are arguments to the function myresult(). Inside the function, we divide a by b, assign the result to c, and return c. In Line 7, we pass the values 20 and 10 to the arguments a and b. Consequently, the function performs the division a/b and returns the result, which is displayed as 2.0 in Line 8.

---
---



