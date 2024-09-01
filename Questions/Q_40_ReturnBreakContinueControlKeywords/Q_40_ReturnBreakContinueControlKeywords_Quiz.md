---
---


1 : Which of the following is/are control flow keyword/s?

a) return   
b) break   
c) continue   
d) All of the above  

**Answer** d) 

**Description**

All are control flow keywords. They are used to stop or restart loops.  


---
---


```
for count in range(0, 10):
    if (count == 7):
        print("I am here, this is 7")
        break
    print("not broken so printing count =" + str(count))
```

2 : In the above program Line 5 will execute till which count?  

a) 9   
b) 10   
c) 6   
d) 7  

**Answer** c) 

**Description**

It will execute till 6, that is “not broken so printing count = 6”. Then it will break and last print will be “I am here this is 7”. This is because of Line 4 which is break keyword.   

---
---


```
for count in range(0, 10):
    if (count == 7):
        print("I am here, this is 7")
    print("not broken so printing count =" + str(count))
```

3 : In the above program Line 4 will execute till which count?  

a) 10   
b) 9   
c) 7  
d) 8  

**Answer** b) 

**Description**

Here the last print will be “not broken so printing count = 9”. When count == 7 it will also print “I am here this is 7” along with "not broken so printing count =7". We are not giving break keyword after this print. So, it will continue and execute the for loop till 9.  

---
---


```
i = 5
while i <= 15:
    print(i)
    if i >= 9:
        break
    i = i + 1
```

4 : In the above program which number will get printed last?  

a) 9   
b) 15   
c) 14  
d) 8  

**Answer** a) 

**Description**

The last number which get printed in the above program will be 9. This is because we are prematurely ending the while loop, that is if i &gt;= 9: break. So, it will end the loop after printing 9.

---
---


```
i = 5
while i <= 15:
    print(i)
    if i == 9:
        print("This is 9")
    i = i + 1
```

5 : In the above program which number will get printed last?  

a) 9   
b) 15   
c) 14   
d) 8  

**Answer** b) 

**Description**

Here it will print till 15. At i == 9 it will print that “This is 9” after printing 9. Then it will continue till 15.  

---
---


6 : Which is the keyword in Python for ending a loop?  

a) break  
b) continue   
c) Both a) & b)   
d) None of the above  

**Answer** a) 

**Description**

break is the keyword to end a loop in Python.

---
---







