---
---


1 : Normally functions have_______  

a) Input  
b) Output  
c) Both of the above  
d) None of the above  

**Answer** c) 

**Description** 

Functions have both input and output normally. We pass input as arguments and get output by the keyword ‘return’. Functions typically have inputs (often called parameters or arguments) and outputs (the value they return). Inputs allow functions to receive data to process, and outputs allow functions to provide the result of their processing. 

---
---


```
def mysum(a, b):
    c = a + b
    return c
print("Before function")
newresult = mysum(30, 40)
print(newresult)
```

2 : In the above program what will be the output of Line 6?  

a) 70  
b) 30  
c) 40  
d) None of the above  

**Answer** a) 

**Description**

The output of print(newresult) will be 70. The function mysum(a, b) is defined to take two inputs, a and b. Inside the function, the sum of a and b is stored in the variable c. The function then returns the value of c. The function mysum(30, 40) is called, with 30 and 40 passed as arguments. The function calculates 30 + 40 which equals 70. The result 70 is returned and assigned to the variable newresult. The print(newresult) statement outputs the value of newresult, which is 70.

---
---


```
def myresult(a, b):
    c = a - b
    return c
print("Before function")
newresult = myresult(40, 30)
print(newresult)
```

3 : In the above program what will get printed at Line 6?  

a) 30  
b) 40  
c) 10  
d) None of the above  

**Answer** c) 

**Description**

In the function we are subtracting a &amp; b and returning as output. In Line 5 we are passing values to arguments a &amp; b as 40 &amp; 30. So, 40 - 30 which will be equal to 10 which will get printed at Line 6.  

---
---


```
def myresult(a, b):
    c = a * b
    return c
print("Before function")
newresult = myresult(4, 3)
print(newresult)
```

4 : In the above program what will get printed at Line 6?  

a) 4  
b) 12  
c) 3  
d) None of the above  

**Answer** b) 

**Description**

It will not be 3, as we are multiplying 4 &amp; 3.In the function we are multiplying a &amp; b and returning as output. In Line 5 we are passing values to arguments a &amp; b as 4 &amp; 3. So, 4 * 3 which will be equal to 12 which will get printed at Line 6.  

---
---


```
def myresult(a, b):
    c = a / b
    return c
print("Before function")
newresult = myresult(6, 3)
print(newresult)
```

5 : In the above program what will get printed at Line 6?  

a) 2.0  
b) 6.0  
c) 3.0  
d) None of the above  

**Answer** a) 

**Description**

In the function we are dividing a / b and returning as output. In Line 5 we are passing values to arguments a &amp; b as 6 &amp; 3. So, 6 / 3 which will be equal to 2.0 which will get printed at Line 6.

---
---


```
def mysum(a, b):
    c = a + b
    return c
print("Before function")
newresult = mysum("30", "40")
print(newresult)
```

6 : In the above program what will get printed at Line 6?  

a) 70  
b) 30  
c) 40  
d) 3040  

**Answer** d) 

**Description**

Here 30 & 40 are treated as string literals, because they are within quotes. So, both 30 & 40 will get concatenated and we will get 3040 as printed.

---
---


```
def mysum(a, b):
    c = a + b
    return c
print("Before function")
newresult = mysum("This is a", " sample")
print(newresult)
```


7 : In the above program what will get printed at Line 6?  

a) This is a sample  
b) This is a  
c) sample  
d) None of the above  

**Answer** a) 

**Description**

The function mysum(a, b) is defined to take two inputs, a and b. Inside the function, a + b is calculated and stored in the variable c. The function then returns the value of c. The function mysum("This is a", " sample") is called, with "This is a" and " sample" passed as arguments. Since the inputs are strings, the + operator concatenates them, resulting in the string "This is a sample". The result "This is a sample" is returned and assigned to the variable newresult. The print(newresult) statement outputs the value of newresult, which is "This is a sample".

---
---








