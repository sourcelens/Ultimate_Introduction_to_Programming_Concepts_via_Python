---
---


```
try:
    index = 0
    even_numbers = [0, 2, 4, 6, 8]
    print(10/even_numbers[index])
except ZeroDivisionError as e:
    print("Denominator cannot be zero")
except IndexError as e:
    print("Index out of bound")
```

1 : In the above program what is/are the exception/s which can happen?  

a) Zero division exception  
b) Index out of bound exception  
c) Both of the above   
d) None of the above  

**Answer** c) 

**Description**  

The first number in the even_numbers array is 0. In Line 4 we have 0 as denominator. So, it is an exception that can happen called as ZeroDivisionError, as division with 0 is not defined in mathematics. Here in the even numbers array, we have got 5 elements, that is index numbers from 0 to 4. So, if index is greater than 4, we will get an exception that is Index out of bound exception.  

---
---


```
try:
    index = 0
    even_numbers = [0, 2, 4, 6, 8]
    print(10/even_numbers[index])
except ZeroDivisionError as e:
    print("Denominator cannot be zero")
except IndexError as e:
    print("Index out of bound")
```

2 : In the above program, what will be the output?  

a) Denominator cannot be zero  
b) Index out of bound  
c) Both of the above  
d) None of the above  

**Answer** a) 

**Description**

The first number in the even_numbers array is 0. In Line 4 we have 0 as denominator. division with 0 is not defined in mathematics. This division by zero operation (10 / 0) triggers a ZeroDivisionError. Therefore, the corresponding except ZeroDivisionError block is executed, printing "Denominator cannot be zero".  

---
---


3 : In official documentation of Python ZeroDivisionError comes under which category?

a) ArithmeticError   
b) OverflowError   
c) FloatingPointError   
d) None of the above  

**Answer** a) 

**Description**

In official documentation of Python ZeroDivisionError comes under ArithmeticError category.  

---
---


4 : In official documentation of Python IndexError comes under which category?  

a) LookupError   
b) KeyError   
c) OsError  
d) None of the above  

**Answer** a) 

**Description**

In official documentation of Python IndexError comes under LookupError category.  

---
---


```
try:
    num = 1
    assert num % 2 == 0
except:
    print("String entered is not an even number")
else: 
    try:
        reciprocal = 1 / num
        print(reciprocal)
    except ZeroDivisionError:
        print("Sorry zero is not allowed")
```

5 : In the above program which Except block will execute?  

a) Line 4 Except block   
b) Line 10 except block  
c) Both of the above   
d) None of the above  

**Answer** a) 

**Description**

Here the number is 1. So, in Line 3 ‘num % 2 == 0’ will evaluate false. So, the Except block in Line 4 will execute and will print that “String entered is not an even number”.  

---
---


```
try:
    num = 0
    assert num % 2 == 0
except:
    print("String entered is not an even number")
else: 
    try:
        reciprocal = 1 / num
        print(reciprocal)
    except ZeroDivisionError:
        print("Sorry zero is not allowed")
```

6 : In the above program which Except block will execute?  

a) Line 4 Except block  
b) Line 10 except block  
c) Both of the above   
d) None of the above  

**Answer** b) 

**Description**

Here the number is 0. So, in Line 3 there will be no problems. But in Line 8 we are finding the reciprocal. Division with 0 is not defined in mathematics. So, it will go to Line 10 Except block and print “Sorry zero is not allowed”.  

---
---


```
try:
    num = 2
    assert num % 2 == 0
except:
    print("String entered is not an even number")
else: 
    try:
        reciprocal = 1 / num
        print(reciprocal)
    except ZeroDivisionError:
        print("Sorry zero is not allowed")
```

7 : In the above program whether any except block will execute?  

a) Will execute   
b) Will not execute  
c) Any of the above  
d) None of the above  

**Answer** b) 

**Description**  

In the above program there will not be any exception because the number is 2. It will print the correct reciprocal of 2 which is 0.5. The number 2 is an even number and also no ZeroDivisionError will happen.

---
---


```
try:
    numerator = 10
    denominator = 0

    result = numerator/denominator
    print(result)

except:
    print("Error : Denominator cannot be 0.")

finally:
    print("This is finally block.")
```

8 : finally block will get executed if _______

a) Exception happens  
b) Exception not happens   
c) Both of the above  
d) None of the above  

**Answer** c) 

**Description**

finally block will get executed if exception happens or not.  

---
---


```
try:
    numerator = 10
    denominator = 0

    result = numerator/denominator
    print(result)

except:
    print("Error : Denominator cannot be 0.")

finally:
    print("This is finally block.")
```

9 : Whether finally block is a part of exception handling or not?  

a) Is a part of exception handling   
b) Is not a part of exception handling   
c) Any of the above  
d) None of the above  

**Answer** a) 

**Description**  

finally block is a part of exception handling.

---
---




