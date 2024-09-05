---
---


```
year=1990
if (year % 4) == 0:
    if(year % 100) == 0:
        if(year % 400) == 0:
            print(year,"is a leap year")
        else:
            print(year,"not a leap year")
    else:
        print(year,"is a leap year")
else:
    print(year,"not a leap year")
```

1 : What will be the output of the above code?  

a) 1990 is not a leap year  
b) 1990 is a leap year  
c) Ordinary year  
d) None of the above  

**Answer** a) 

**Description**

The year we are passing,1990 is not a multiple of 4 and it returns False. The remainder is 2. This will come to line number 11 and exit.  

---
---


```
year=1992
if (year % 4) == 0:
    if(year % 100) == 0:
        if(year % 400) == 0:
            print(year,"is a leap year")
        else:
            print(year,"not a leap year")
    else:
        print(year,"is a leap year")
else:
    print(year,"not a leap year")
```

2 : What will be the output of the above code?  

a) 1992 is a leap year  
b) 1992 is not a leap year  
c) Ordinary year  
d) None of the above  

**Answer** a) 

**Description**

1992 is a multiple of 4 but not a multiple of 100. So, it is a coming to line number 9 and print1992 is a leap year.  

---
---


```
#
year=1900
if (year % 4) == 0:
    if(year % 100) == 0:
        if(year % 400) == 0:
            print(year,"is a leap year")
        else:
            print(year,"not a leap year")
    else:
        print(year,"is a leap year")
else:
    print(year,"not a leap year"
```

3 : What will be the output of the above code?  

a) 1900 is a leap year  
b) 1900 not a leap year  
c) Ordinary year  
d) None of the above  

**Answer** b) 

**Description**

Here line number 3 and 4 returns True but Line number 5 returns False. Then it will come to line number 8 and print not a leap year.  

---
---


```
#
year=2000
if (year % 4) == 0:
    if(year % 100) == 0:
        if(year % 400) == 0:
            print(year,"is a leap year")
        else:
            print(year,"not a leap year")
    else:
        print(year,"is a leap year")
else:
    print(year,"not a leap year")
```

4 : What will be the output of the above code?  

a) 2000 is a leap year  
b) 2000 not a leap year  
c) Ordinary year  
d) None of the above  

**Answer** a) 

**Description**

Here line number 3,4 and 5 returns True. So, 2000 is a leap year.  

---
---


```
year=1990
if(year % 4 == 0 and ( year % 100 != 0 or year % 400== 0)):
    print("The year is a leap year")
else:
    print("The year isn't a leap year")
```

5 : What will be the output of the above code?  

a) The year isn't a leap year  
b) The year is a leap year  
c) Ordinary year  
d) None of the above  

**Answer** a) 

**Description**  

1990 is not a multiple of 4 and it will print the year isn’t a leap year.  

---
---


```
#
year = 1992
if(year % 4 == 0 and ( year % 100 != 0 or year % 400 == 0 )):
    print("The year is a leap year")
else:
    print("The year isn't a leap year")
```

6 : What will be the output of the above code?  

a) The year is a leap year  
b) The year isn’t a leap year  
c) Ordinary year  
d) None of the above  

**Answer** a) 

**Description** 

1992 is a multiple of 4.  So this year % 4 == 0 condition is satisfied. 1992 % 100 is not equal to 0. One among the "or" condition is also satisfied.Since Line 3 becomes True, Line 4 gets executed and print the year is a leap year.  

---
---


```
#
year = 1900
if(year % 4 == 0 and ( year % 100 != 0 or year % 400 == 0 )):
    print("The year is a leap year")
else:
    print("The year isn't a leap year"
```

7 : What will be the output of the above code?  

a) The year is a leap year  
b) The year isn’t a leap year  
c) Ordinary year  
d) None of the above  

**Answer** b) 

**Description**

year % 4 == 0 condition is satisfied. But none of the conditions in the parenthesis is not satisfied. 1900 % 100 is 0 and 1900 % 400 is 300. So Line 3 evaluates to be False and the control goes to Line 6 which prints "The year isn't a leap year".  

---
---


```
#
year = 2000
if(year % 4 == 0 and ( year % 100 != 0 or year % 400 == 0 )):
    print("The year is a leap year")
else:
    print("The year isn't a leap year")
```

8 : What will be the output of the above code?  

a) The year is a leap year  
b) The year isn’t a leap year  
c) Ordinary year  
d) None of the above   

**Answer** a) 

**Description**

The condition 2000 % 4 == 0 is satisfied. 2000 % 100 is zero (that condition becomes false). 2000% 400 is indeed 0 (this condition becomes true). So one condition in the “or” statements becomes true and the Line 3 becomes True. If the condition in Line 3 is satisfied the program prints “The year is a leap year”.  

---
---


```
#
year = 2000
def leapyr(year):
    if year % 400 == 0:
        return True
    if year % 100 == 0:
        return False
    if year % 4 == 0:
        return True
    return False
print(leapyr(year))
```

9 : What will be the output of the above code?  

a) True  
b) False  
c) Ordinary year  
d) None of the above  

**Answer** a) 

**Description**

2000 is a multiple of 400, if condition in Line 4 is true and the function will return True. Since it is a return, rest of the lines inside the function will not get executed.  

---
---


```
#
year = 1990
def leapyr(year):
    if year % 400 == 0:
        return True
    if year % 100 == 0:
        return False
    if year % 4 == 0:
        return True
    return False
print(leapyr(year))
```

10 : What will be the output of the above code?  

a) True  
b) False  
c) Ordinary year  
d) None of the above  

**Answer** b) 

**Description**

Since 1990 is not divisible by 400, the condition if year % 400 == 0: is not satisfied. The function then checks if the year is divisible by 100. This is also not satisfied. The function then checks if the year,1990 is divisible by 4. This condition is not satisfied either. Since none of the conditions for a leap year are satisfied, the function returns False (Line 10).  

---
---


```
#
year = 1992
def leapyr(year):
    if year % 400 == 0:
        return True
    if year % 100 == 0:
        return False
    if year % 4 == 0:
        return True
    return False
print(leapyr(year))
```

11 : What will be the output of the above code?  

a) True  
b) False  
c) Ordinary year  
d) None of the above  

**Answer** a) 

**Description**

The function leapyr checks if the year is divisible by 400.Since 1992 is not divisible by 400, this condition is not satisfied. The function then checks if the year is divisible by 100.Since 1992 is not divisible by 100, this condition is also not satisfied. The function then checks if the year is divisible by 4. Since the year 1992 is divisible by 4 the function returns True (Line 9 is executed). Thus the output of the above code is True.

---
---


```
#
year = 1900
def leapyr(year):
    if year % 400 == 0:
        return True
    if year % 100 == 0:
        return False
    if year % 4 == 0:
        return True
    return False
print(leapyr(1900))
```

12 : What will be the output of the above code?  

a) True  
b) False  
c) Ordinary year  
d) None of the above  

**Answer** b) 

**Description**

1900 is not a multiple of 100 and it will return False. That means not a leap year.  

---
---


```
#
year=1990
if(year % 400 == 0):
    print("{0} is a leap year".format(year))
elif(year % 4 == 0) and (year % 100 != 0):
    print("{0} is a leap year".format(year))
else:
    print("{0} is not a leap year".format(year))
```

13 : What will be the output of the above code?  

a) 1990 is not a leap year  
b) 1990 is a leap year  
c) Ordinary year  
d) None of the above  

**Answer** a) 

**Description**

1990 is not a multiple of 400 and 4. Since if and elif conditions are not satisfied the control goes to Line 8 and prints 1990 is not a leap year  

---
---


```
#
year=1992
if(year % 400 == 0):
    print("{0} is a leap year".format(year))
elif(year % 4 == 0) and (year % 100 != 0):
    print("{0} is a leap year".format(year))
else:
    print("{0} is not a leap year".format(year))
```

14 : What will be the output of the above code?  

a) 1992 is not a leap year  
b) 1992 is a leap year  
c) Ordinary year  
d) None of the above   

**Answer** b) 

**Description**

1992 is a not a multiple of 400. So control goes to elif statement.Since 1992 is a multiple of 4 and not a multiple of 100, the condition in Line 5 is satisfied and prints Line 6 1992 is a leap year  

---
---


```




