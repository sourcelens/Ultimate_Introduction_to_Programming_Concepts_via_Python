---
---


```
num = 9
if num % 2 == 0:
    print("{0} is even".format (num))
else:
    print("{0} is odd".format(num))
```

1 : In the above program we are finding whether a number is _______  

a) int or float  
b) Even or odd  
c) Both of the above  
d) None of the above  

**Answer** b) 

**Description** 

Here in the program, we are finding whether a number is even or odd. For this we are % it with 2 (Line 2) which gives the remainder. If the remainder is 0, we are printing the number is even. If not, number is odd. % is called Modulo operator. It finds the remainder after division.  

---
---


```
num = 9
if num % 2 == 0:
    print("{0} is even".format (num))
else:
    print("{0} is odd".format(num))
```

2 : In the above program what operation we are doing in Line 2?  

a) Modulo operation  
b) Multiplication  
c) Addition  
d) Subtraction  

**Answer** a) 

**Description** 

It is called Modulo operation. In this we are dividing the number with another number and taking the remainder. Eg:- 2 % 2 is 0, 17 % 10 is 7.  

---
---


3 : Which is the symbol of modulo operator?  

a) %  
b) +  
c) *  
d) –  

**Answer** a) 

**Description**

% is the sign of modulo operator.  

---
---


```
num = 9
if num % 2 == 0:
    print("{0} is even".format (num))
else:
    print("{0} is odd".format(num))
```

4 : In the above program which print will execute?  

a) Line 3 print  
b) Line 5 print  
c) Any of the above  
d) None of the above  

**Answer** b) 

**Description**

Here the number 9 is not completely divisible by 2. There will be remainder which is 1. So, the if condition will become false and else statement will execute and so print of Line 5 will happen.  

---
---


```
num = 9
if num % 2 == 0:
    print("{0} is even".format (num))
else:
    print("{0} is odd".format(num))
```

5 : In the above program whether the number (num) is even or odd?  

a) Even  
b) Odd  
c) Complex number  
d) Real number  

**Answer** b) 

**Description**

Here the number 9 is not completely divisible by 2. There will be remainder which is 1. So, the if condition will become false and else statement will execute and so print of Line 5 will happen which says the number is odd.  

---
---


```
num = 8
if num % 2 == 0:
    print("{0} is even".format (num))
else:
    print("{0} is odd".format(num))
```

6 : In the above program which print will execute?  

a) Line 3 print  
b) Line 5 print  
c) Any of the above  
d) None of the above  

**Answer** a) 

**Description**

Here the number is completely divisible by 2 and the remainder will be 0. So, the if statement is true and Line 3 will execute.

---
---


```
num = 8
if num % 2 == 0:
    print("{0} is even".format (num))
else:
    print("{0} is odd".format(num))
```

7 : In the above program whether the number (num) is even or odd?  

a) Even  
b) Odd  
c) Complex number  
d) Real number  

**Answer** a) 

**Description**

Here the number is completely divisible by 2 and the remainder will be 0. So, the if statement is true and Line 3 will execute which says the number is even.

---
---


```
print("{0} is odd".format (9, "num", "anything"))
```

8 : In the above code what will get printed?  

a) 9 is odd  
b) num is odd  
c) anything is odd  
d) All of the above  

**Answer** a) 

**Description**

Here 9 will get printed, because the format function’s first argument is 9. {0} stands for the first argument given for format function. Here it is 9. So “9 is odd” will get printed. 

---
---


```
print("{1} is odd".format (9, "num", "anything"))
```

9 : In the above code what will get printed?  

a) 9 is odd  
b) num is odd  
c) anything is odd  
d) All of the above  

**Answer** b)  

**Description**  

Here num will get printed, because the format function’s second argument is num. {1} stands for the second argument given for format function. Here it is num. So “num is odd” will get printed.  

---
---


```
print("{2} is odd".format (9, "num", "anything"))
```

10 : In the above code what will get printed?  

a) 9 is odd  
b) num is odd  
c) anything is odd  
d) All of the above  

**Answer** c)  

**Description** 

Here anything will get printed, because the format function’s third argument is anything. {2} stands for the third argument given for format function. Here it is anything. So “anything is odd” will get printed.  

---
---


```
num = 9
if num % 2 == 0:
    print("{0} is even".format (num))
else:
    print("{0} is odd".format(num))
```

11 : In the above program in Line 2 which operation happens first?  

a) Comparison operation  
b) Modulo operation  
c) Any of the above  
d) None of the above  

**Answer** b)  

**Description**

Modulo operation has more priority in this and will happen first and then only comparison operation will happen.

---
---




