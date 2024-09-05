---
---


1 : What are the rules to check whether a year is a leap year?  

a) Divisible by 400  
b) Divisible by 100 and not divisible by 400  
c) Divisible by 4 and not divisible by 100  
d) Both a) and c)  

**Answer** d) 

**Description**

Both the conditions are true for a leap year. If the year / number is divisible by 400 it is a leap year. Eg: -400,800,8000,1200,2000....Anything which is divisible by 4 and not divisible by 100 is a leap year. 	Eg:- 4,8,12…

---
---


2 : According to the leap year rule check whether 100 is a leap year or not?

a) Leap year  
b) Not a Leap year  
c) May or may not leap year  
d) None of the above  

**Answer** b) 

**Description**

If a number is divisible by 4 it is a leap year unless it is divisible by 100. Here 100 is a multiple of 4 and is divisible by 100 also. So, 100 is not a leap year.  

---
---


```
year=1990
if (year % 4) == 0:
    if(year % 100) == 0:
        if(year % 400) == 0:
            print(year,"is a leap yaer")
        else:
            print(year,"not a leap year")
    else:
        print(year,"is a leap yaer")
else:
    print(year,"not a leap year")
```

3 : This program is for finding ________  

a) Leap year  
b) Factorial  
c) Even or Odd  
d) Sum of numbers  

**Answer** a) 

**Description**

This program checks whether the given number or year is a leap year or not. Here we are checking the year 1990 is a leap year or not.  

---
---


```
year=1990
if (year % 4) == 0:
    if(year % 100) == 0:
        if(year % 400) == 0:
            print(year,"is a leap yaer")
        else:
            print(year,"not a leap year")
    else:
        print(year,"is a leap year")
else:
    print(year,"not a leap year")
```

4 : In the above lines of code what is the meaning of % operator?  

a) Modulo operator  
b) Percentage  
c) Division  
d) None of the above  

**Answer** a) 

**Description**

This is the Modulo operator. It checks for the remainder of the division. If the remainder is zero it means that this is fully divisible by that number.  

---
---


```
year=2020
if (year % 4) == 0:
    if(year % 100) == 0:
        if(year % 400) == 0:
            print(year,"is a leap yaer")
        else:
            print(year,"not a leap year")
    else:
        print(year,"is a leap year")
else:
    print(year,"not a leap year")
```

5 : In the above lines of code if the year is divisible by 4 and not divisible by 100 then what will get printed?  

a) Is a leap year  
b) Not a leap year  
c) May or may not be a leap year  
d) None of the above  

**Answer** a) 

**Description**

In this program if the given number is divisible by 4 and not divisible by 100 it will print the year ‘is a leap year’. So, the control will go to line number 9 and it will print the given year is a leap year. Any number which is divisible by 4 and not divisible by 100 is a leap year. eg.2020  

---
---


```
year=1900
if (year % 4) == 0:
    if(year % 100) == 0:
        if(year % 400) == 0:
            print(year,"is a leap yaer")
        else:
            print(year,"not a leap year")
    else:
        print(year,"is a leap year")
else:
    print(year,"not a leap year")
```

6 : In the above lines of code if the given year is divisible by 4, divisible by 100 and not divisible by 400 what will be the output?  

a) Is a leap year  
b) Not a leap year  
c) May or may not be a leap year  
d) None of the above  

**Answer** b) 

**Description**

In this program if the given year is divisble by 4, is divisible by 100 and not divisible by 400 it will print the year is ‘not a leap year’. So, the control will go to line number  7 and it will print the given year is not a leap year. Any number which is divisible by 100 and not divisible by 400 is not a leap year.  

---
---


```
year=1990
if (year % 4) == 0:
    if(year % 100) == 0:
        if(year % 400) == 0:
            print(year,"is a leap yaer")
        else:
            print(year,"not a leap year")
    else:
        print(year,"is a leap year")
else:
    print(year,"not a leap year")
```

7 : In the above lines of code if the given number is not completely divisible by 4 then what will get printed?  

a) Is a leap year  
b) Is not a leap year  
c) May or may not be a leap year  
d) None of the above  

**Answer** b) 

**Description**

If the given number is not divisible by 4 then the control will enter into line number 11 and it will print the given year is not a leap year. Any number which is not divisible by 4 is not a leap year.eg:-3,2,5,6….all those numbers are not leap years because they are not divisible by 4.  

---
---


```
year=2020
if (year % 4) == 0:
    if(year % 100) == 0:
        if(year % 400) == 0:
            print(year,"is a leap yaer")
        else:
            print(year,"not a leap year")
    else:
        print(year,"is a leap year")
else:
    print(year,"not a leap year")
```

8 : In the above lines of code if the given number is divisible by 4 then what will happen next?  

a) The program will end  
b) Print not a leap year  
c) Enter into next condition if(year % 100) == 0 and checks the condition  
d) None of the above  

**Answer** c) 

**Description**

If a number is divisible by 4 it goes to line if(year % 100) == 0: and checks whether this condition is satisfied or not.  

---
---


```
year=2000
if(year % 4 == 0 and ( year % 100 != 0 or year % 400== 0)):
    print("The year is a leap year")
else:
    print("The year isn't a leap year")
```

9 : In the above lines of code how the condition checking takes place?  

a) Checks only one condition  
b) Checks condition in brackets only  
c) Checks the ‘and’ and ‘or’ conditions  
d) None of the above  

**Answer** c) 

**Description**

The first thing it checks is the number is divisible by 4.it is checking either number is divisible by 4 like 8,12,16,20 etc. If that is the case, next thing, it is going to check is the whole thing within the brackets. If the number is divisible by 4 it is not going to stop there it is going to check the condition inside the ( ) also. Because the condition in ( ) is an ’OR' condition, to make this ( year % 100 != 0 or year % 400== 0) true any one of condition needs to be true.  

---
---


```
year=2000
if(year % 4 == 0 and ( year % 100 != 0 or year % 400== 0)):
    print("The year is a leap year")
else:
    print("The year isn't a leap year")
```

10 : In the above lines of code what will get printed if the given year is divisible by 4 and any one of the or conditions become true?  

a) Print The year is a leap year  
b) Print The year isn't a leap year  
c) Checks the ‘and’ and ‘or’ conditions  
d) None of the above  

**Answer** a) 

**Description**

It will print the year is a leap year. The control will go to line number 3.  

---
---


```
year=1990
if(year % 4 == 0 and ( year % 100 != 0 or year % 400== 0)):
    print("The year is a leap year")
else:
    print("The year isn't a leap year")
```

11 : In the above lines of code what will get printed if the given year is not divisible by 4?  

a) Print The year isn't a leap year  
b) Print The year is a leap year  
c) Checks the ‘and’ and ‘or’ conditions  
d) None of the above  

**Answer** a) 

**Description**

It will print the year isn’t a leap year. The control will go to line number 5. If the given year is not divisible by 4 then it is not a leap year.  

---
---


```
def leapyr(year):
    if year % 400 == 0:
        return True
    if year % 100 == 0:
        return False
    if year % 4 == 0:
        return True
    return False
print(leapyr(2000))
```

12 : In the above lines of code what will get printed if the given year is divisible by 400?  

a) True
b) False  
c) Program Ends  
d) None of the above  

**Answer** a) 

**Description**

If the year is divisible by 400 it will return True. Return will end the function execution. The function will return True if the given year is divisible by 400.  

---
---


```
def leapyr(year):
    if year % 400 == 0:
        return True
    if year % 100 == 0:
        return False
    if year % 4 == 0:
        return True
    return False
print(leapyr(1901))
```

13 : In the above lines of code what will get printed if none of the if conditions are true?  

a) True  
b) False  
c) Program Ends  
d) None of the above  

**Answer** b) 

**Description**

It will come to line number 8 and return False.  

---
---


```
year=2000
if(year % 400 == 0):
    print("{0} is a leap year".format(year))
elif(year % 4 == 0) and (year % 100 != 0):
    print("{0} is a leap year".format(year))
else:
    print("{0} is not a leap year".format(year))
```

14 : In the above lines of code what will get printed if the given year is divisible by 400?  

a) 2000 is a leap year  
b) 2000 is not a leap year  
c) Program Ends  
d) None of the above  

**Answer** a) 

**Description**

It will come to line number 3 and print the given year (here it is 2000) is a leap year.  

---
---


```
year=1900
if(year % 400 == 0):
    print("{0} is a leap year".format(year))
elif(year % 4 == 0) and (year % 100 != 0):
    print("{0} is a leap year".format(year))
else:
    print("{0} is not a leap year".format(year))
```

15 : In the above lines of code what will happen if the given year is not divisible by 400?  

a) Checks the elif condition  
b) Year is not a leap year  
c) Program Ends  
d) None of the above  

**Answer** a) 

**Description**

If year is not divisible by 400 elif condition will be checked. Whether the year is divisible by 4 and not divisible by 100.if any of the and conditions become false it will print the year is not a leap year (Line 7). otherwise if both condition in elif is satisfied the program prints the year is a leap year.

---
---






