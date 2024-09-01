---
---


```
def function4 ():
    print ("Inside function4")
    count = 0
    while count < 20:
        count = count + 1
        if count == 12:
            print ("Going to run inner for loop")
            for i in range (20):
                if i == 14:
                    print ("Count is 14, so going to return")
                    continue
                print (i)
        print (count)
    print ("Done with function4")
Test_return = function4 ()
print (Test_return)
```

1 : In the case of outer while loop which all numbers get printed before it executes Line 7?  

a) 0 to 11   
b) 1 to 11   
c) 0 to 12   
d) 0 to 11  

**Answer** b) 

**Description**

The print will start from 1, because there is no print statement when count = 0. Then we are checking whether count &lt; 20 and increasing the count by 1. Then we are checking whether count is equal to 12. It is not 12, it is 1, so will execute print statement and 1 is getting printed. Like that up to 11 it will print. When count becomes 12, it will execute Line 7. That is, it will print “Going to run inner for loop”. So before printing Line 7 it will print from 1 to 11.

---
---


```
def function4 ():
    print ("Inside function4")
    count = 0
    while count < 20:
        count = count + 1
        if count == 12:
            print ("Going to run inner for loop")
            for i in range (20):
                if i == 14:
                    print ("Count is 14, so going to return")
                    continue
                print (i)
        print (count)
    print ("Done with function4")
Test_return = function4 ()
print (Test_return)
```

2 : In the outer while loop of the program whether 0 will get printed or not?  

a) Will get printed   
b) Will not get printed   
c) May get printed   
d) None of the above  

**Answer** b) 

**Description**

The print will start from 1, because there is no print statement when count = 0. Then we are checking whether count &lt; 20 and increasing the count by 1. Then we are checking whether count is equal to 12. It is not 12, it is 1, so will execute print statement and 1 is getting printed.  

---
---


```
def function4 ():
    print ("Inside function4")
    count = 0
    while count < 20:
        count = count + 1
        if count == 12:
            print ("Going to run inner for loop")
            for i in range (20):
                if i == 14:
                    print ("Count is 14, so going to return")
                    continue
                print (i)
        print (count)
    print ("Done with function4")
Test_return = function4 ()
print (Test_return)
```

3 : At which count of outer while loop it will enter the inner for loop?  

a) 10   
b) 12   
c) 0   
d) 1  

**Answer** b) 

**Description**

In Line 6 we are checking if count = = 12. So, at 12th count of outer while loop, it will enter into the inner for loop and outer while loop will print up to 11.  

---
---



