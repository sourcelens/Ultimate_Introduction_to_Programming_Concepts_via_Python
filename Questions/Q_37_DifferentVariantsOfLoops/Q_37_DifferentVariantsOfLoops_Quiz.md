---
---


```
for n in range(0, 10, 2):
    print(n)
```

1 : What will get printed on the screen for the above program?  

a) 0 to 9  
b) 0, 2, 4, 6, 8  
c) 0, 2, 4, 6, 8, 10   
d) 2, 4, 6, 8  

**Answer** b) 

**Description**

The range(0, 10, 2) generates numbers starting from 0 and increments by 2 until it reaches (but does not include) 10.  

---
---


```
for n in range(0, 10, 3):
    print(n)
```

2 : What will get printed on the screen for the above program?  

a) 0 to 9   
b) 0, 3, 6, 9   
c) 3, 6, 9  
d) 0, 3, 6  

**Answer** b) 

**Description**

The range(0, 10, 3) generates numbers starting from 0 and increments by 3 until it reaches (but does not include) 10.  

---
---


```
for n in ["apple", "orange", "mango", "grapes"]:
    print(n)
```

3 : What will get printed on the screen for the above program?  

a) Will print 4 items one by one  
b) apple  
c) orange   
d) mango  

**Answer** a) 

**Description**

It is a for loop. It will iterate through every item in the list and will print them one by one.  

---
---


```
count = 0
while (count < 10):
    print(count)
    count = count + 1
```

4 : What is the output of the above program?  

a) 0 to 9   
b) 1 to 9   
c) 0 to 10   
d) 1 to 10  

**Answer** a) 

**Description**

count is initialized to 0. The while loop continues to execute as long as count is less than 10. Inside the loop, print(count) outputs the current value of count. After printing, count is incremented by 1 (count = count + 1). The loop iterates from 0 to 9. In each iteration, count is printed, starting from 0 and increasing sequentially up to 9. When count reaches 10, the condition count &lt; 10 becomes False, and the loop terminates.   

---
---


```
count = 0
while (count < 10):
    print(count)
    count = count + 2
```

5 : What is the output of the above program?  

a) 0, 2, 4, 6, 8   
b) 2, 4, 6, 8   
c) 0 to 9   
d) 0, 2, 4, 6, 8, 10  

**Answer** a) 

**Description**

count is initialized to 0. The while loop continues to execute as long as count is less than 10. Inside the loop, print(count) outputs the current value of count. After printing, count is incremented by 2 (count = count + 2). The loop iterates from 0 up to 8. In each iteration, count is printed, starting from 0 and increasing by 2 in each subsequent iteration.  

---
---


```
count = 0
while (count < 10):
    print(count)
    count = count + 3
```

6 : What is the output of the above program?  

a) 0, 3, 6, 9   
b) 2, 4, 6, 8   
c) 0 to 9  
d) 0, 3, 6  

**Answer** a) 

**Description**

count is initialized to 0. The while loop continues to execute as long as count is less than 10. Inside the loop, print(count) outputs the current value of count. After printing, count is incremented by 3 (count = count + 3). The loop iterates through 0, 3, 6, and 9. In each iteration, count is printed, starting from 0 and increasing by 3 in each subsequent iteration. When count reaches 9, the condition count &lt; 10 becomes False, and the loop terminates.  

---
---


```
count = 0
while (count < 10):
    print(count)
```

7 : What will get printed on the screen for the above program?  

a) 0 to 9   
b) 1 to 9   
c) 0 to 10   
d) Infinite loop of 0   

**Answer** d) 

**Description**

This will become an infinite loop. Here we are not increasing the count. So, count is always 0, which is always less than 10. So, this loop will not end and become an infinite loop.  

---
---









