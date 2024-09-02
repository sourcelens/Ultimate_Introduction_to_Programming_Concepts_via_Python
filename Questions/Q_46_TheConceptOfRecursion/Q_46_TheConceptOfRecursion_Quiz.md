---
---


1 : What is recursion in Python programming language?  

a) Function calling another function inside  
b) Function calling same function inside  
c) Both of the above  
d) None of the above  

**Answer** b) 

**Description**

Recursion in Python programming is, a defined function calling itself.  

---
---


2 : In mathematics 4 factorial is _______  

a) 1     
b) 2  
c) 6  
d) 24  

**Answer** d) 

**Description**

Factorial of a number means multiply it with its previous digits. Eg:- 4 factorial is 1 * 2 * 3 * 4 which is equal to 24, 3 factorial is 1 * 2 * 3 = 6.  

---
---


3 : In mathematics n factorial is _______  

a) n    
b) 2  
c) 6  
d) 1 * 2 * 3 * ……. * n  

**Answer** d) 

**Description**

Factorial of a number means multiply it with its digits. Eg:- 4 factorial is 1 * 2 * 3 * 4 which is equal to 24, 3 factorial is 1 * 2 * 3 = 6. So n factorial is, 1 * 2 * 3 * ……. * n.  

---
---


```
num = 7
def factorial_func (n):
    if n == 1:
        return 1
    else:
        return (n * factorial_func (n-1))
factorial_recur = factorial_func (num)
print (factorial_recur)
```

4 : The above program is an example of _______  

a) Nested loop   
b) Normal loop   
c) Recursion   
d) All of the above  

**Answer** c) 

**Description**

This program is an example of recursion, because we are calling the same function, factorial_func inside again (Line 6).  

---
---


```
num = 7
def factorial_func (n):
    if n == 1:
        return 1
    else:
        return (n * factorial_func (n-1))
factorial_recur = factorial_func (num)
print (factorial_recur)
```

5 : In the above program how many stack frames will come in the call stack before multiplication happens?  

a) 7   
b) 1   
c) 6   
d) 0  

**Answer** a) 

**Description**

In this program we are giving num = 7. In Line 6 the value of n changes to 6 as we are calling the function with (n-1). So, a stack frame with 7 is created and the function call will be still in action. Then a stack frame with 6 is created, then 5 and upto n = 1 will be created. Then if n = 1 comes, then only the multiplication will take place and each of the stack frames get used up, upto 7. So, there will be 7 stack frames created in the call stack.

---
---


```
num = 7
def factorial_func (n):
    if n == 1:
        return 1
    else:
        return (n * factorial_func (n-1))
factorial_recur = factorial_func (num)
print (factorial_recur)
```

6 : In the above program what will get printed to the screen at last?  

a) 24   
b) 6   
c) 5040  
d) 0  

**Answer** c) 

**Description**

In this program we are giving num = 7. In Line 6 the value of n changes to 6 as we are calling the function with (n-1). So, a stack frame with 7 is created and the function call will be still in action. Then a stack frame with 6 is created, then 5 and upto n = 1 will be created. Then if n = 1 comes, then only the multiplication will take place and each of the stack frames get used up, upto 7.So, there will be 7 stack frames created in the call stack. So, the multiplication will happen like 1 * 2 * 3 * 4 * 5 * 6 * 7 which will be 7 factorial and it is 5040.  

---
---


7 : Recursion uses a very scarce resource called _______ In the Operating system.  

a) Stack memory   
b) Functions   
c) Variables   
d) All of the above  

**Answer** a) 

**Description**

Recursion programs creates stack frames and it utilizes a very scarce resource in the operating system called stack memory.  

---
---


8 : When the number of recursions are high in the program, it will cause a complication in memory called _______  

a) Function overflow   
b) Stack overflow   
c) Both of the above  
d) None of the above  

**Answer** b) 

**Description**

When number of recursions are high, it will create as much stack frames and causes stack overflow. That is why we are trying to avoid recursions.  

---
---


9 : Everything which we are doing in recursion can be done with _______  

a) Variables   
b) Loops  
c) Both of the above  
d) None of the above  

**Answer** b) 

**Description**

Everything which can be done in recursion can be done in loops as well. Sometimes it is straight forward, but sometimes not. Sometimes recursion logic is easier to visualize and write. But always loops are preferred.  

---
---











