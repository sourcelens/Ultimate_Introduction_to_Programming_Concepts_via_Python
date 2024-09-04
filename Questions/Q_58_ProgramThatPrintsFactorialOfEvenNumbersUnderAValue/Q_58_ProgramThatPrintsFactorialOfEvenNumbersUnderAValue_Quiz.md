---
---


```
#
num=4
factorial=1
for i in range(1,num+1):
    factorial = i * factorial
print(factorial)
```

1 : What does the above program do?  

a) Finding Factorial  
b) Finding Average  
c) Multiplication  
d) Addition  

**Answer** a) 

**Description**

This program represents the factorial of a number. Here 4! =24.

---
---


2 : What are the different ways to do factorial program?  

a) Recursion  
b) Loop methodology  
c) Both a) and b)  
d) None of the above  

**Answer** c) 

**Description**

We have two methods to find out factorial of a number. One is Recursion but it has some issues.   Another is the Loop methodology and we prefer Loop methodology.  

---
---


```
#
num=4
factorial=1
for i in range(1,num+1):
    factorial = i * factorial
print(factorial)
```

3 : In the above program what is the value of i in the first iteration?  

a) 1  
b) 0  
c) 4  
d) 24  

**Answer** a) 

**Description**

i in range(1,num+1) So the range starts from 1. The value of i in the first iteration will be 1.  

---
---


```
#
def findfactorial(num):
    factorial=1
    for i in range(1,num+1):
        factorial = i * factorial
    return factorial
```

4 : What does the above lines of code represent?  

a) Definition of findfactorial() function  
b) Function call  
c) Concatenation  
d) None of the above   

**Answer** a) 

**Description**

Here we are defining the findfactorial function, taking num as argument and it will return the factorial as output.

---
---



