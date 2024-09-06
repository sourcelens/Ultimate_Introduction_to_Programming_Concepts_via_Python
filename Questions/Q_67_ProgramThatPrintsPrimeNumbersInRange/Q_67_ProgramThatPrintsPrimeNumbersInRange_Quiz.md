---
---


```
num = 100
for n in range(1,num):
    for i in range(2,n):
        if(n % i == 0):
            break
    else:
        print(n)
```

1 : In the above lines of code, which loop does the else statement belong to?  

a) First for loop   
b) Second for loop   
c) If condition   
d) None of the above  

**Answer** b) 

**Description**

The else is not the part of the if condition. This else is part of the nested for loop (inner for loop).  

---
---


```
num = 100
for n in range(1,num):
    for i in range(2,n):
        if(n % i == 0):
            break
    else:
        print(n)
```

2 : In the above lines of code what operation is done in Line 4?  

a) Modulo operation  
b) Percentage  
c) Equal to operation  
d) Assignment operation  

**Answer** a) 

**Description**  

%  is the Modulo operator. It gives the remainder of division, which means it is checking if ‘n’ is perfectly divisible by ‘i’ or it is checking if ‘i’ is a factor of ‘n’.  

---
---


```
num = 100
for n in range(1,num):
    for i in range(2,n):
        if(n % i == 0):
            break
    else:
        print(n)
```

3 : When does the print(n) statement execute in the above code?  

a) When n is a prime number  
b) When n is divisible by 3  
c) Quit the program   
d) None of the above  

**Answer** a) 

**Description**

The print(n) statement executes when the inner loop (for i in range(2, n)) completes without finding any divisor for n other than 1 and n itself. This condition is true only for prime numbers.

---
---



