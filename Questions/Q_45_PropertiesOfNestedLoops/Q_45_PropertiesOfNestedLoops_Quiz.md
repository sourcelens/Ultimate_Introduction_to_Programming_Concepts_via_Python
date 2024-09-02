---
---


```
fruits = [ "apple", "orange", "mango", "grapes"]
for f in fruits:
    if (f == "apple"):
        print (f)
```

1 : In the above program which all will get printed on to the screen?  

a) ‘apple’  
b) ‘orange’  
c) ‘mango’  
d) All of the above  

**Answer** a) 

**Description** 

In the program it will iterate through all of the four fruits because there is a for loop, but only print ‘apple’. This is because we are giving an if condition that f = = ‘apple’, then print. So, only apple will get printed.  

---
---


```
fruits = [ "apple", "orange", "mango", "grapes"]
for f in fruits:
    if (f == "mango"):
        print (f)
```

2 : In the above program which all will get printed on to the screen?  

a) ‘apple’  
b) ‘orange’  
c) ‘mango’  
d) All of the above  

**Answer** c) 

**Description**

In the program it will iterate through all of the four fruits because there is a for loop, but only print ‘mango’. This is because we are giving an if condition that f = = ‘mango’, then print. So, only mango will get printed.

---
---


```
fruits = [ "apple", "orange", "mango", "grapes"]
for f in fruits:
    if (f == "orange"):
        print (f)
```

3 : In the above program which all will get printed on to the screen?  

a) ‘apple’  
b) ‘orange’  
c) ‘mango’  
d) All of the above  

**Answer** b) 

**Description**

In the program it will iterate through all of the four fruits because there is a for loop, but only print ‘orange’. This is because we are giving an if condition that f = = ‘orange’, then print. So, only orange will get printed.  

---
---


```
fruits = [ "apple", "orange", "mango", "grapes"]
for f in fruits:
    if (f == "grapes"):
        print (f)
```

4 : In the above program which all will get printed on to the screen?  

a) ‘grapes’  
b) ‘orange’  
c) ‘mango’  
d) All of the above  

**Answer** a) 

**Description**

In the program it will iterate through all of the four fruits because there is a for loop, but only print ‘grapes’. This is because we are giving an if condition that f = = ‘grapes’, then print. So, only grapes will get printed.

---
---


```
fruits = [ "apple", "orange", "mango", "grapes"]
for f in fruits:
    for n in range (0, 3):
        print (str (n) + " for fruit " + f)
```

5 : In the above program how many times will Line 4 print statement execute?  

a) 4  
b) 3  
c) 12  
d) 11  

**Answer** c) 

**Description**

Here in the program the first for loop will have 4 iterations, because there are 4 items in the array given. Then for each item in the array the inner loop will run 3 times, because we are giving a range ( 0, 3 ). So, for apple Line 4 will execute 3 times and the same for orange, mango &amp; grapes. So, there will be total 3 * 4 = 12 times the print statement will execute.  

---
---


```
fruits = [ "apple", "orange", "mango", "grapes"]
for f in fruits:
    for n in range (0, 3):
        print (str (n) + " for fruit " + f)
```

6 : What will get printed on the screen for the 3 iterations of inner for loop for the first item apple in the array?  

a) 0 for fruit apple

   1 for fruit apple 

   2 for fruit apple  

b) 0 for fruit orange 

   1 for fruit orange 

   2 for fruit orange  

c) 1 for fruit apple 

   2 for fruit apple

   3 for fruit apple  

d) 1 for fruit orange

   2 for fruit orange

   3 for fruit orange   

**Answer** a) 

**Description** 

It will print 0, 1, 2 for apple. This is because we are giving the range ( 0, 3 ). So, it starts from 0 and go as 0, 1, 2 for apple.  

---
---


```
fruits = [ "apple", "orange", "mango", "grapes"]
for f in fruits:
    for n in range (0, 3):
        print (str (n) + " for fruit " + f)
```

7 : What will get printed on the screen for the 3 iterations of inner for loop for the third item mango in the array?  

a) 0 for fruit mango 

   1 for fruit mango

   2 for fruit mango  

 b) 1 for fruit mango

    2 for fruit mango 

    3 for fruit mango  

 c) 0 for fruit orange 

    1 for fruit orange 

    2 for fruit orange  

 d) 1 for fruit orange

    2 for fruit orange

    3 for fruit orange  

**Answer** a) 

**Description**

It will print 0, 1, 2 for mango. This is because we are giving the range ( 0, 3 ). So, it starts from 0 and go as 0, 1, 2 for mango.  

---
---


```
fruits = [ "apple", "orange", "mango", "grapes"]
for f in fruits:
    for n in range (100, 103):
        if (f == "apple"):
            print (str(n) + " just for fruit " + f + " only")
```

8) In the above program how many times Line 3 will be executed?  

a) 12   
b) 11  
c) 3  
d) 4  

**Answer** a) 

**Description**

The inner for loop will run 3 times for each item in the array, that is for 100, 101 &amp; 102. So, total 4 items in the array, so total of 3 * 4 = 12 times. But printing happens only for apple, because we are giving a condition in Line 4 that if (f = = apple), then only print. So, print will happen only for apple 3 times. 

---
---


```
fruits = [ "apple", "orange", "mango", "grapes"]
for f in fruits:
    for n in range (100, 103):
        if (f == "apple"):
            print (str(n) + " just for fruit " + f + " only")
```

9 : In the above program how many times the print statement ( Line 5 ) will execute?  

a) 12    
b) 11  
c) 3   
d) 4  

**Answer** c) 

**Description**

The inner for loop will run 3 times for each item in the array, that is for 100, 101 &amp; 102. So, total 4 items in the array, so total of 3 * 4 = 12 times. But printing happens only for apple, because we are giving a condition in Line 4 that if (f = = apple), then only print. So, print will happen only for apple 3 times.  

---
---





   






