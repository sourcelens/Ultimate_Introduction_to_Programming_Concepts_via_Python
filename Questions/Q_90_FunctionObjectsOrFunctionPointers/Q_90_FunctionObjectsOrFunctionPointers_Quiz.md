---
---


1 : A Function object or function pointer is a _______

a) Variable pointing to a code  
b) Variable containing a number   
c) Variable containing a string   
d) All of the above  

**Answer** a) 

**Description**

Function object or function pointer is a variable which is pointing to a Function.  

---
---


2 : What are the other names of function objects or function pointers?  

a) Function variables   
b) Method objects  
c) Call backs  
d) All of the above  

**Answer** d) 

**Description**  

All of them are the same. Has different names in different programming languages.  

---
---


3 : Function objects or function pointers have a lot of applications which include _______  

a) Decorators  
b) Call backs or delegates   
c) Multithreading or concurrency   
d) All of the above  

**Answer** d) 

**Description**  

All of them are applications of function objects.  

---
---


```
a = 100

def myfun():
    print("hi")

b = myfun

print(a)
print(b)
b()
```

4 : In the above code, b is having a ______ ?  

a) Function object   
b) string  
c) Both of the above   
d) None of the above  

**Answer** a) 

**Description** 

b = myfun: This assigns the function object myfun to the variable b. 

---
---


```
a = 100

def myfun():
    print("hi")

b = myfun

print(a)
print(b)
b()
```

5 : In the above code the function call of myfun happens in _______  

a) Line 6  
b) Line 10   
c) Line 9   
d) Line 3  

**Answer** b) 

**Description**

Here the function call happens in Line 10 as b().  

---
---


6 : For display purposes the binary numbers are represented as _______  

a) Decimal numbers   
b) Hexadecimal numbers   
c) Octa decimal numbers   
d) None of the above  

**Answer** b) 

**Description**

For display purposes the binary numbers are represented as hexadecimal numbers. They are 16 based numbers with digits from 0 to 9 and alphabets from A to F.  

---
---


```
def addprocessor(s):
    for i in s:
        print(i + 100)

def subprocessor(s):
    for i in s:
        print(i - 100)

def processNumbers(nums, processor_callback):
    processor_callback(nums)

intarry = [1, 20, 3, 9, 4]

processNumbers(intarry, addprocessor)
processNumbers(intarry, subprocessor)
```

7 : In the above code the Function object is _______  

a) addprocessor   
b) subprocessor   
c) processor_callback   
d) All of the above  

**Answer** c) 

**Description**

processor_callback is a function object because it is pointing to a function, as when we are calling the function processNumbers second argument is a function.  

---
---


```
def addprocessor(s):
    for i in s:
        print(i + 100)

def subprocessor(s):
    for i in s:
        print(i - 100)

def processNumbers(nums, processor_callback):
    processor_callback(nums)

intarry = [1, 20, 3, 9, 4]

processNumbers(intarry, addprocessor)
processNumbers(intarry, subprocessor)
```

8 : In the above program when we are calling the function processNumbers in Line 14, the function object processor_callback points to which function code?  

a) subprocessor (s)   
b) addprocessor (s)   
c) Any of the above  
d) None of the above  

**Answer** b) 

**Description**  

In the above program, when we are calling the function processNumbers in Line 14, the function object processor_callback points to the addprocessor function. In Line 14, processNumbers(intarry, addprocessor) is called. At this point: intarry is passed as the argument nums. addprocessor is passed as the argument processor_callback. Thus, within the processNumbers function, processor_callback(nums) effectively becomes addprocessor(nums). Therefore, during the execution of this call, processor_callback points to the addprocessor function.

---
---


```
def addprocessor(s):
    for i in s:
        print(i + 100)

def subprocessor(s):
    for i in s:
        print(i - 100)

def processNumbers(nums, processor_callback):
    processor_callback(nums)

intarry = [1, 20, 3, 9, 4]

processNumbers(intarry, addprocessor)
processNumbers(intarry, subprocessor)
```

9 : In the above program when we are calling the function processNumbers in Line 15, the function object processor_callback points to which function code?  

a) subprocessor (s)   
b) addprocessor (s)   
c) Any of the above   
d) None of the above   

**Answer** a) 

**Description**  

In Line 15, processNumbers(intarry, subprocessor) is called. At this point: intarry is passed as the argument nums. subprocessor is passed as the argument processor_callback. Thus, within the processNumbers function, processor_callback(nums) effectively becomes subprocessor(nums). Therefore, during the execution of this call, processor_callback points to the subprocessor function.

---
---










