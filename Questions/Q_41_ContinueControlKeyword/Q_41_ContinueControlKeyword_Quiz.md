---
---


```
for count in range(0, 10):
    if(count == 7):
        print("I am here this is 7")
        continue
    print("Not broken so printing count = " + str(count))
```

1 : In the iteration where count becomes 7 whether it will execute Line 5 or not?  

a) Will print Line 5   
b) Won’t print Line 5   
c) May print Line 5   
d) None of the above  

**Answer** b) 

**Description**

Here in the program if count becomes 7 it will print ‘I am here this is 7’ and continue to the for loop. It will not execute Line 5 because in Line 4 we are giving continue keyword. So. It will not execute Line 5 and continue the for loop and count becomes 8.

---
---


```
for count in range(0, 7):
    if(count == 5):
        print("I am here this is 5")
        continue
    print("Not broken so printing count = " + str(count))
```

2 : In the execution of the above program whether “not broken so printing count = 5” will get printed or not?  

a) Will get printed   
b) Will not get printed   
c) May get printed   
d) None of the above  

**Answer** b) 

**Description**

Here in the program if count becomes 5 it will print ‘I am here this is 5’ and continue to the for loop. It will not execute Line 5 because in Line 4 we are giving continue keyword. So, It will not execute Line 5 and continue the for loop and count becomes 6.

---
---


```
while True:
    print("This loop will run forever!")
```

3 : Which kind of while loop is given in the above program?  

a) Normal loop   
b) Infinite loop   
c) Any of the above  
d) None of the above  

**Answer** b) 

**Description**

The while loop in the above program is an infinite loop. The while loop is considered an infinite loop because the condition True will always evaluate to true, causing the loop to run indefinitely without any terminating condition.

---
---


```
i = 5
while i <= 15:
    print(i)
    i = i + 1
    if i >= 9:
        continue
```

4 : Which kind of while loop is given in the above program?  

a) Finite while loop   
b) Infinite loop   
c) Any of the above   
d) None of the above  

**Answer** a) 

**Description**

In the above program it will print upto 15 and will not become an infinite loop. Because we are giving continue at last. So, if i becomes 9, it will continue while loop and print the rest upto 15. 

---
---


```
for i in range(20):
    if i == 12:
        print("This will not get printed")
        continue
    print(i)
```

5 : In the above program which is the number that will not get printed ?  

a) 0   
b) 19   
c) 12   
d) Both b) & c)  

**Answer** c) 

**Description**

It will not print 12. In this program 12 won’t get printed. Because when i becomes 12 if condition will get executed, that is it will print “This will not get printed”. Then we are giving continue in Line 4. So, Line 5 will not get executed and so 12 not get printed.  

---
---


```



