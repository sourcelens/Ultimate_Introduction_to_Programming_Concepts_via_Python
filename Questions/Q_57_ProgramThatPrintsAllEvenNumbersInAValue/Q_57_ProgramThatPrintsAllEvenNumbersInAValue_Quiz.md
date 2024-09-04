---
---


```
def isnumbereven(num):
    if( 0 == (num % 2) ):
        return True
    else:
        return False
numbeloweven=20
for i in range(numbeloweven):
     if(True == isnumbereven(i)):
         print(str(i)+"is even")
```

1 : The above program is for printing _______  

a) Odd numbers below 20   
b) Even numbers below 20   
c) Negative numbers below 20  
d) All of the above  

**Answer** b) 

**Description** 

The above program prints all even numbers below 20 (not 20 itself). Here we are iterating through every number in range 20 (Line 7). Then for each iteration we are calling the function which checks number is even or odd using modulo operator. Then we are printing it, if it is even.  

---
---


```
def isnumbereven(num):
    if( 0 == (num % 2) ):
        return True
    else:
        return False
numbeloweven=20
for i in range(numbeloweven):
     if(True == isnumbereven(i)):
         print(str(i)+"is even")
```

2 : Will the above program print 0?  

a) Yes   
b) No  

**Answer** a) 

**Description**  

0 will get printed, because in the range the lower limit starts from 0.  

---
---


```
def isnumbereven(num):
    if( 0 == (num % 2) ):
        return True
    else:
        return False
numbeloweven=20
for i in range(numbeloweven):
     if(True == isnumbereven(i)):
         print(str(i)+"is even")
```

3 : Will 20 get printed for the above program as even number?  

a) Yes   
b) No  

**Answer** b) 

**Description** 

We are giving a range which is range(20). The numbers in this range is from 0 to 19. So 20 will not get printed.  

---
---


```
def isnumbereven(num):
    if (0 == (num % 2) and (num != 0)):
        return True
    elif (1 == (num % 2) ):
        return False
    return "Number is zero"
numbeloweven=20
for i in range(numbeloweven):
     if(True == isnumbereven(i)):
         print(str(i)+"is even")
```

4 : In the above program whether 0 will get printed as even number or not?  

a) Will get printed as even   
b) Will not get printed as even  
c) Any of the above   
d) None of the above  

**Answer** b) 

**Description**

No, 0 will not be printed as an even number because the function isnumbereven(0) returns "Number is zero", and not True. Since the condition True == isnumbereven(i) fails "zero is even" won't get printed.

---
---


```
def isnumbereven(num):
    if (0 == (num % 2) and (num != 0)):
        return True
    elif (1 == (num % 2) ):
        return False
    return "Number is zero"
numbeloweven=20
for i in range(numbeloweven):
     if(True == isnumbereven(i)):
         print(str(i)+"is even")
```

5 : Will 20 get printed for the above program as even number?  

a) Yes   
b) No  

**Answer** b) 

**Description**

In the given program, 20 will not get printed as even. The loop runs from 0 to 19.  

---
---


```
def isnumbereven(num):
    if (0 == (num % 2) and (num != 0)):
        return True
    elif (1 == (num % 2) ):
        return False
    return "Number is zero"
numbeloweven=20
for i in range(numbeloweven):
     if(True == isnumbereven(i)):
         print(str(i)+"is even")
```

6 : In the above program when will Line 3 gets executed?  

a) If both conditions are true in Line 2   
b) If one condition is true in Line 2   
c) Any of the above   
d) None of the above  

**Answer** a) 

**Description**

Here we are giving and operator. So, the statement will be true only when both conditions evaluate true. That is 0 = = num % 2 is true and number not equal to (! =) 0 is true.

---
---


```
def isnumbereven(num):
    if (0 == (num % 2) and (num != 0)):
        return True
    elif (1 == (num % 2) ):
        return False
    return "Number is zero"
numbeloweven=20
for i in range(numbeloweven):
     if(True == isnumbereven(i)):
         print(str(i)+"is even")
```

7 : In the above program when we are calling the function?   

a) Line 8  
b) Line 9   
c) Line 10   
d) Line 1  

**Answer** b) 

**Description**

We are calling the function in Line 9 as “ if (True == isnumbereven (i)).  

---
---


```
def isnumbereven(num):
    if (0 == (num % 2) and (num != 0)):
        return True
    elif (1 == (num % 2) ):
        return False
    return "Number is zero"
numbeloweven=20
for i in range(numbeloweven):
     if(True == isnumbereven(i)):
         print(str(i)+"is even")
```

8 : In the above program where we are defining the function?  

a) Line 8   
b) Line 9   
c) Line 10   
d) Line 1 - Line 6  

**Answer** d) 

**Description**

We are defining the function in Line 1 - Line 6 with def keyword.  

---
---






