---
---


```
#
num = 12345

reversed_num = 0
while num != 0:
    digit = num % 10
    reversed_num = reversed_num * 10 + digit
    num = num // 10

print("The reversed number is:",reversed_num)
```

1 : In the above code what is the purpose of Line 6?  

a) To get Remainder  
b) To get sum  
c) None of the Above  
d) All of the above  

**Answer** a) 

**Description** 

Modulo operator is used to get the remainder of a division. Whenever a modulo operation of a number is done with 10, the remainder is always the last digit of that number.   

---
---


```
#
num = 12345

reversed_num = 0
while num != 0:
    digit = num % 10
    reversed_num = reversed_num * 10 + digit
    num = num // 10

print("The reversed number is:",reversed_num)
```

2 : What will be the value of ‘digit’ in first iteration?  

a) 5  
b) 1  
c) 2345  
d) None of the above  

**Answer** a) 

**Description**

Modulo operator is used to get the remainder of a division. Whenever a modulo operation of a number is done with 10, the remainder is always the last digit of that number and here it is 5.  

---
---


```
#
num = 12345

reversed_num = 0
while num != 0:
    digit = num % 10
    reversed_num = reversed_num * 10 + digit
    num = num // 10

print("The reversed number is:",reversed_num)
```

3 : What will be the order of precedence of operations in line 7?  

a) *,+  
b) +,*  
c) +,=,*  
d) None of the above  

**Answer** a) 

**Description**

Multiplication happens first. Multiplication has precedence over addition. After multiplication addition takes place. After multiplication and addition, the result is assigned to the variable reversed_num.  

---
---


```
#
num = 12345

reversed_num = 0
while num != 0:
    digit = num % 10
    reversed_num = reversed_num * 10 + digit
    num = num // 10

print("The reversed number is:",reversed_num)
```

4 : In the above lines of code what will be the value of reversed_num in first iteration?  

a) 5  
b) 0  
c) 1234  
d) None of the above  

**Answer** a) 

**Description**

Multiplication happens first. Multiplication has precedence over addition. After multiplication addition takes place. After multiplication and addition, the result is assigned to the variable reversed_num. Here 0*10+5=5. So the value of reversed_num becomes 5.

---
---


```
#
num = 12345

reversed_num = 0
while num != 0:
    digit = num % 10
    reversed_num = reversed_num * 10 + digit
    num = num // 10

print("The reversed number is:",reversed_num)
```

5 : In the above lines of code what operation we are doing in Line 8?  

a) Floor division  
b) Modulo operator  
c) Assignment operator  
d) None of the above  

**Answer** a) 

**Description**

// This operation is floor division. It divides a number and ignores the decimals. In the first iteration, after the execution of line 8, ‘num’ is going to be 1234.  The initial value of num is 12345 and num // 10 is going to be 1234. This new value is assigned to ‘num’ in line 8.

---
---


```
#
num = 12345

reversed_num = 0
while num != 0:
    digit = num % 10
    reversed_num = reversed_num * 10 + digit
    num = num // 10

print("The reversed number is:",reversed_num)
```

6 : What will be the operator precedence in Line 8?  

a) // , =  
b) = , //  
c) Same precedence  
d) None of the above  

**Answer** a) 

**Description**

First the priority is for floor operator (//) and then assignment (=) operator. Almost always equal to is the least priority.  

---
---


```
#
num = 12345

reversed_num = 0
while num != 0:
    digit = num % 10
    reversed_num = reversed_num * 10 + digit
    num = num // 10

print("The reversed number is:",reversed_num)
```

7 : What does the above lines of code do?  

a) Code to find out the reverse of a number  
b) Code to find out the last digit of a number  
c) Code to find out the number of digits in a number  
d) None of the above  

**Answer** a) 

**Description**

The above code represents the code to find out the reverse of the given number using modulo operator and floor division operator.  

---
---


```
#
num = 12345

reversed_num = 0
while num != 0:
    digit = num % 10
    reversed_num = reversed_num * 10 + digit
    num = num // 10

print("The reversed number is:",reversed_num)
```

8 : What will be the output of the above code?  

a) The reversed number is: 54321  
b) The reversed number is: 12345  
c) 0  
d) None of the above  

**Answer** a) 

**Description**

54321 which is the reverse of 12345. We are finding it by using modulo operator and floor division operator.  

---
---


```
#
num = 5678

reversed_num = 0
while num != 0:
    digit = num % 10
    reversed_num = reversed_num * 10 + digit
    num = num // 10

print("The reversed number is:",reversed_num)
```

9 : What will be the output of the above code?  

a) The reversed number is: 8765  
b) The reversed number is: 5678  
c) 0  
d) None of the above  

**Answer** a) 

**Description**

8765 which is the reverse of 5678. We are finding it by using modulo operator and floor division operator.

---
---





