---
---


```
def is_sum_even(number):
    sum = 0
    while number > 0:
        sum = sum + number % 10
        number = number // 10
    
    if sum % 2 == 0:
        return True
    else:
        return False
    
number = 10
if is_sum_even(number):
    print("The sum of digits of", number, "is even.")
else:
    print("The sum of digits of", number, "is odd.")
```

1 : In the above program, function is_sum_even(number) is called in _______  

a) Line 12   
b) Line 13  
c) Line 14   
d) Line 1  

**Answer** b) 

**Description**

The function name which we are giving is ‘is_sum_even’. Then we are calling it at Line 13 as ‘if is_sum_even (number).   

---
---


```
def is_sum_even(number):
    sum = 0
    while number > 0:
        sum = sum + number % 10
        number = number // 10
    
    if sum % 2 == 0:
        return True
    else:
        return False
    
number = 10
if is_sum_even(number):
    print("The sum of digits of", number, "is even.")
else:
    print("The sum of digits of", number, "is odd.")
```

2 : In the above program what we are doing in Line 5?  

a) Modulo operation  
b) Floor division   
c) Normal division   
d) None of the above  

**Answer** b) 

**Description**

In Line 5 we are doing Floor division. In floor division we divide a number with another number and give only its whole number part. We will discard the decimal part.

---
---


3 : What is the symbol for Floor division?  

a) /   
b) //   
c) %   
d) *   

**Answer** b) 

**Description**

// is the symbol used for Floor division.  

---
---


```
def is_sum_even(number):
    sum = 0
    while number > 0:
        sum = sum + number % 10
        number = number // 10
    
    if sum % 2 == 0:
        return True
    else:
        return False
    
number = 10
if is_sum_even(number):
    print("The sum of digits of", number, "is even.")
else:
    print("The sum of digits of", number, "is odd.")
```

4 : If the sum of the digits returning from the function is even which print statement will execute?  

a) Line 14   
b) Line 15   
c) Line 16   
d) Line 13  

**Answer** a) 

**Description**

If the sum of the digits is even the if condition in Line 13 become True and will print Line 14.  

---
---


```
def is_sum_even(number):
    sum = 0
    while number > 0:
        sum = sum + number % 10
        number = number // 10
    
    if sum % 2 == 0:
        return True
    else:
        return False
    
number = 10
if is_sum_even(number):
    print("The sum of digits of", number, "is even.")
else:
    print("The sum of digits of", number, "is odd.")
```

5 : If the sum of the digits returning from the function is odd which print statement will execute?  

a) Line 14   
b) Line 15   
c) Line 16  
d) Line 13   

**Answer** c) 

**Description**

If the sum of the digits returning from the function is odd, the if condition will become false and will print Line 16.  

---
---


```
def is_sum_even(number):
    sum = 0
    while number > 0:
        sum = sum + number % 10
        number = number // 10
    
    if sum % 2 == 0:
        return True
    else:
        return False
    
number = 10
if is_sum_even(number):
    print("The sum of digits of", number, "is even.")
else:
    print("The sum of digits of", number, "is odd.")
```

6 : In the above program where we are finding the sum of digits in the given number?  

a) Line 2 to Line 5   
b) Line 7 to Line 10   
c) Both a) & b)   
d) None of the above  

**Answer** a) 

**Description**

In Line 2 to Line 5 we are finding the sum of digits of the number given. We are achieving this with the help of modulo division and floor division.  

---
---


```
def is_sum_even(number):
    sum = 0
    while number > 0:
        sum = sum + number % 10
        number = number // 10
    
    if sum % 2 == 0:
        return True
    else:
        return False
    
number = 10
if is_sum_even(number):
    print("The sum of digits of", number, "is even.")
else:
    print("The sum of digits of", number, "is odd.")
```

7 : In the above program where we are checking the sum of digits of the given number is even or odd?

a) Line 2 to Line 5  
b) Line 7 to Line 10   
c) Both a) & b)   
d) None of the above  

**Answer** b) 

**Description**

We are finding whether the sum of digits of the given number is even or odd in Line 7 to Line 10 using modulo operation.

---
---


```
def is_sum_even(number):
    sum = 0
    while number > 0:
        sum = sum + number % 10
        number = number // 10
    
    if sum % 2 == 0:
        return True
    else:
        return False
    
number = 10
if is_sum_even(number):
    print("The sum of digits of", number, "is even.")
else:
    print("The sum of digits of", number, "is odd.")
```

8 : If the sum of the digits is even, what will the function return?  

a) It will return True   
b) It will return False  

**Answer** a) 

**Description**

It will return True. In Line 7 we are doing modulo operation, that is we are checking whether the number is divisible by 2. If divisible it will be equal to 0. So, if the sum of digits is even it will be divisible by 2, remainder will be 0 and it will return True.

---
---


```
def is_sum_even(number):
    sum = 0
    while number > 0:
        sum = sum + number % 10
        number = number // 10
    
    if sum % 2 == 0:
        return True
    else:
        return False
    
number = 10
if is_sum_even(number):
    print("The sum of digits of", number, "is even.")
else:
    print("The sum of digits of", number, "is odd.")
```

9 : If the sum of the digits is odd, what will the function return?  

a) It will return True   
b) It will return False  

**Answer** b) 

**Description**

It will return false. In Line 7 we are doing modulo operation, that is we are checking whether the number is divisible by 2. If divisible it will be equal to 0. If sum of digits is odd modulo operation result will be 1 and not equal to 0. So, it will return false.  

---
---


```
def is_sum_even(number):
    sum = 0
    while number > 0:
        sum = sum + number % 10
        number = number // 10
    
    if sum % 2 == 0:
        return True
    else:
        return False
    
number = 10
if is_sum_even(number):
    print("The sum of digits of", number, "is even.")
else:
    print("The sum of digits of", number, "is odd.")
```

10 : In the above program is_sum_even function definition is from _______  

a) Line 1 to Line 16   
b) Line 1 to Line 10   
c) Line 12 to Line 16  
d) None of the above  

**Answer** b) 

**Description**

In the above program function definition is from Line 1 to Line 10, because it all comes under the def keyword, which is the keyword for function.  

---
---





