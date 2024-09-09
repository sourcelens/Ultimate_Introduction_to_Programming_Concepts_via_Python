---
---


```
dict1 = { "dog": "boblie", "cat": " dablu"}
print(dict1['rabbit'])
```

1 : In the above program what will happen if executed?  

a) Program will execute correctly   
b) Program crashes & exception occurs  
c) Any of the above   
d) None of the above  

**Answer** b) 

**Description**

In the above we are trying to take the value of rabbit which is not there in the dictionary. So, the program will crash, that is it will stop execution and exception will occur.   

---
---


2 : In which method of exception handling, we prevent the happening of the exception?  

a) try, except method   
b) if, else method   
c) Both of the above  
d) None of the above  

**Answer** b) 

**Description**  

In if, else first we are checking whether the exception is going to happen. If it is going to happen, we are switching to else condition. So, in this method we prevent the happening of exception.

---
---


3 : In which method of exception handling, we handle the exception after it happens?  

a) try, except method  
b) if, else method  
c) Both of the above   
d) None of the above  

**Answer** a) 

**Description**  

In try, except method if exception happens, we are giving it to except block, which will give some user-friendly information and handles exception gracefully. 

---
---


```
dict1 = { "dog": "boblie", "cat": " dablu"}

if 'rabbit' in dict1:
    print(dict1['rabbit'])

else:
    print("We have no rabbits")
```

4 : In the above program the exception handling is done in a _______  

a) Preventive way   
b) Handled after it happens   
c) Any of the above   
d) None of the above  

**Answer** a) 

**Description**  

if, else method of handling exception prevents the occurring of exception. That is why we are checking if rabbit is there in the dictionary as a key. If not, we are going to the else condition, So, we prevent the occurrence of exception.  

---
---


```
dict1 = { "dog": "boblie", "cat": " dablu"}

try:
    print(dict1['rabbit'])

except:
    print("We have no rabbits")
```

5 : In the above program the exception handling is done in a _______  

a) Preventive way  
b) Handled after it happens   
c) Any of the above  
d) None of the above  

**Answer** b) 

**Description**

In try except exception handling, try block contains code which might raise an exception and except block contains code which get executed if an exception occurs. 

---
---







