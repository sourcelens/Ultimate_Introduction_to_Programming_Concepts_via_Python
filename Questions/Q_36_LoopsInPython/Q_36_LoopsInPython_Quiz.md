---
---


1 : _______ is the way to do things in repeated pattern in Python.  

a) Loops   
b) Function   
c) Both of the above  
d) None of the above  

**Answer** a) 

**Description**

A common way to perform operations in a repeated pattern in Python is by using loops, such as for and while loops.  

---
---


2 : Which is the easiest way to print ‘hello world’ a hundred times in Python?  

a) Using functions   
b) Using loops   
c) Both of the above   
d) None of the above  

**Answer** b) 

**Description**

Loops is the easiest way to print ‘hello world’ a hundred times in Python.  

---
---


3 : Example of nesting include _______

a) List of list   
b) List of dictionaries   
c) Dictionaries with value as arrays   
d) All of the above  

**Answer** d) 

**Description**

Nesting is a common concept in both programming and the real world, where items are contained within one another. It allows for hierarchical structuring, and there can be any number of nested levels.  

---
---

```
fruits = ["apple", "orange", "mango", "grapes"]
for f in fruits:
    print(f)
```

4 : What will be the output of the above program?  

a) It will print 4 items in the array one by one  
b) apple will get printed   
c) orange will get printed   
d) mango will get printed  

**Answer** a) 

**Description**

It is a for loop. It will iterate through each item in the list and print them one by one.  

---
---


```
fruits = ["apple", "orange", "mango", "grapes"]
for f in fruits:
    print(f)
print("hello world")
```

5 : In the above program will ‘hello world’ get printed in loop?  

a) It Will loop  
b) Will not  
c) Any of the above  
d) None of the above  

**Answer** b) 

**Description**

In the above program, "hello world" will not be printed inside the loop. The for loop iterates over each element (f) in the list fruits and prints each fruit name. After completing the loop, it moves to the next statement which is print("hello world"). This statement is outside the loop block, so it will execute only once after the loop has finished iterating through all the elements in the fruits list. Therefore, "hello world" will be printed once, but it will not be part of the loop execution. To loop it must have same indentation as Line 3 and within the for loop.

---
---


```
fruits = ["apple", "orange", "mango", "grapes"]
for f in fruits:
    print(f)
    print("hello world"
```

6 : In the above program will ‘hello world’ get printed in loop?  

a) Yes  
b) No  
c) Any of the above   
d) None of the above  

**Answer** a) 

**Description**

print("hello world") has the same indentation as print (f) and is inside the for loop. So, print("hello world") gets printed in loop.  

---
---


```
for n in range(0, 10):
    print(n)
```

7 : What will get printed on the screen for the above program?  

a) 0 to 10   
b) 0 to 9   
c) 1 to 10   
d) 1 to 9  

**Answer** b) 

**Description**

It will print 0 to 9. 10 will not get printed.  

---
---


```
for n in range(1, 9):
    print(n)
```

8 : What will get printed on the screen for the above program?  

a) 1 to 8   
b) 1 to 9   
c) 1 to 10   
d) 2 to 9  

**Answer** a) 

**Description**

It will print 1 to 8. 9 will not get printed.  


---
---





