---
---


```
def dec2bin(number):
    ans = ""
    if( number == 0):
        return 0
    while ( number ):
        ans = str(number & 1) + ans
        number = number >> 1
    return ans

number = 60
print(f"The Binary of the number { number} is { dec2bin(number) }")
```

1 : In the above lines of code what we are doing in Line 2?

a) Initializing an empty string variable  
b) Printing a string   
c) Both of the above   
d) None of the Above  

**Answer** a)  

**Description** 

Here we are assigning the variable ‘ans’, an empty string, that is initializing an empty string variable.  

---
---


```
def dec2bin(number):
    ans = ""
    if( number == 0):
        return 0
    while ( number ):
        ans = str(number & 1) + ans
        number = number >> 1
    return ans

number = 60
print(f"The Binary of the number { number} is { dec2bin(number) }")
```

2 : In the above program dec2bin function definition is from____?  

a) Line 1 to Line 11   
b) Line 1 to Line 8   
c) Line 8 to Line 11   
d) None of the Above  

**Answer** b)  

**Description**

Here Line 1 to Line 8 comes under the def keyword. So, that it is the function definition.  

---
---


```
def dec2bin(number):
    ans = ""
    if( number == 0):
        return 0
    while ( number ):
        ans = str(number & 1) + ans
        number = number >> 1
    return ans

number = 60
print(f"The Binary of the number { number} is { dec2bin(number) }")
```

3 : In the above program dec2bin function is called in_____?  

a) Line 1   
b) Line 11   
c) Line 10   
d) Line 3  

**Answer** b)  

**Description**

Here the function call happens at Line 11 in print statement, dec2bin(number) is where we are calling the function.

---
---


```
def dec2bin(number):
    ans = ""
    if( number == 0):
        return 0
    while ( number ):
        ans = str(number & 1) + ans
        number = number >> 1
    return ans

number = 60
print(f"The Binary of the number { number} is { dec2bin(number) }")
```

4 : What Line 8 is doing in the above lines of code?  

a) Printing ans   
b) Returning ans   
c) Checking ans   
d) None of the above  

**Answer** b)  

**Description**

return ans terminates the function dec2bin and returns the value of ans to the caller.  

---
---


```
def dec2bin(number):
    ans = ""
    if( number == 0):
        return 0
    while ( number ):
        ans = str(number & 1) + ans
        number = number >> 1
    return ans

number = 60
print(f"The Binary of the number { number} is { dec2bin(number) }")
```

5 : In the above program what & does in Line 6?  

a) bitwise OR operation   
b) bitwise AND operation   
c) Both of the above  
d) None of the above  

**Answer** b)  

**Description**

&amp; operator performs a bitwise AND operation. Here it is an operation between the variable number and 1.  

---
---



