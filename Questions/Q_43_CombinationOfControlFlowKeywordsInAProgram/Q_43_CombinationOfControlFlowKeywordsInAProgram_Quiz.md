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
                if i ==14:
                    print ("Count is 14, so going to return")
                    return "This is it"
                print (i)
        print (count)
    print ("Done with function4")
Test_return = function4 ()
print (Test_return)
```

1 : In the above program the for loop in Line 8 is a _______  

a) Normal for loop   
b) Nested for loop   
c) Both of the above   
d) None of the above  

**Answer** b)

**Description**

It is a nested for loop, because it is inside a while loop.

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
                if i ==14:
                    print ("Count is 14, so going to return")
                    return "This is it"
                print (i)
        print (count)
    print ("Done with function4")
Test_return = function4 ()
print (Test_return)
```

2 : In the case of outer while loop which all numbers get printed before it executes Line 7?  

a) 0 to 11   
b) 1 to 11   
c) 0 to 12   
d) 0 to 11  

**Answer** b)

**Description**

The print will start from 1, because there is no print statement when count = 0. Then we are checking whether count &lt; 20 and increasing the count by 1. Then we are checking whether count is equal to 12. It is not 12, it is 1, so will execute print statement and 1 is getting printed. Like that upto 11 it will print. When count becomes 12, it will execute Line 7. That is, it will print “Going to run inner for loop”. So before printing Line 7 it will print from 1 to 11.

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
                if i ==14:
                    print ("Count is 14, so going to return")
                    return "This is it"
                print (i)
        print (count)
    print ("Done with function4")
Test_return = function4 ()
print (Test_return)
```

3 : In the above program what Line 5 does?  

a) Incrementing the count   
b) Decrementing the count   
c) Checking the count   
d) None of the above  

**Answer** a)

**Description**

In Line 5 we are incrementing the count by 1, that is count = count + 1.

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
                if i ==14:
                    print ("Count is 14, so going to return")
                    return "This is it"
                print (i)
        print (count)
    print ("Done with function4")
Test_return = function4 ()
print (Test_return)
```

4 : In the outer while loop of the program whether 0 will get printed or not?  

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
                if i ==14:
                    print ("Count is 14, so going to return")
                    return "This is it"
                print (i)
        print (count)
    print ("Done with function4")
Test_return = function4 ()
print (Test_return)
```

5 : In the outer while loop of the program whether 12 will get printed or not?  

a) Will get printed   
b) Will not get printed   
c) May get printed   
d) None of the above  

**Answer** b)

**Description**

The print will start from 1, because there is no print statement when count = 0. Then we are checking whether count &lt; 20 and increasing the count by 1. Then we are checking whether count is equal to 12. It is not 12, it is 1, so will execute print statement and 1 is getting printed. Like that upto 11 it will print. When count becomes 12, it will execute Line 7. That is it will print “Going to run inner for loop”. So before printing Line 7 it will print from 1 to 11 and it will not print 12.

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
                if i ==14:
                    print ("Count is 14, so going to return")
                    return "This is it"
                print (i)
        print (count)
    print ("Done with function4")
Test_return = function4 ()
print (Test_return)
```

6 : At which count of outer while loop it will enter the inner for loop?  

a) 10  
b) 12  
c) 0   
d) 1    

**Answer** b)

**Description**

In Line 6 we are checking if count = = 12. So, at 12th count of outer while loop, it will enter into the inner for loop and outer while loop will print up to 11.

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
                if i ==14:
                    print ("Count is 14, so going to return")
                    return "This is it"
                print (i)
        print (count)
    print ("Done with function4")
Test_return = function4 ()
print (Test_return)
```

7 : Which number will get printed for outer while loop just before it enters the inner for loop and prints Line 7, that is “Going to run inner for loop”?  

a) 12   
b) 10   
c) 11   
d) 0  

**Answer** c)

**Description**

In Line 6 we are checking if count = = 12. So, at 12th count of outer while loop, it will enter into the inner for loop and outer while loop will print upto 11.

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
                if i ==14:
                    print ("Count is 14, so going to return")
                    return "This is it"
                print (i)
        print (count)
    print ("Done with function4")
Test_return = function4 ()
print (Test_return)
```

8 : In the above program which all numbers will get printed for the inner for loop?  

a) 0 to 13   
b) 1 to 12  
c) 0 to 14   
d) 1 to 14  

**Answer** a)

**Description**

For inner for loop we are giving a range from 0 to 20. In the immediate next line we are checking if i = = 14. It is not true, because at start i will be 0. So, it will execute Line 12 not Line 10. So, the first print will be 0. Then when it will become 14, the if condition will become true and so it will execute Line 10 and then we are giving return. So it will end the function and 14 will not get printed. So, 0 to 13 will get printed.

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
                if i ==14:
                    print ("Count is 14, so going to return")
                    return "This is it"
                print (i)
        print (count)
    print ("Done with function4")
Test_return = function4 ()
print (Test_return)
```

9 : In the above program when i becomes 14 for inner for loop what will happen?  

a) Will print “This is it” & program ends   
b) Inner for loop will end & execution of while loop continues   
c) Execution of inner loop continues   
d) None of the above  

**Answer** a)

**Description**

return is a keyword which ends the function. So, it will end the inner for loop, outer while loop and will end the function.

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
                if i ==14:
                    print ("Count is 14, so going to return")
                    break
                print (i)
        print (count)
    print ("Done with function4")
Test_return = function4 ()
print (Test_return)
```

10 : In the above program which all numbers will get printed for the inner for loop?  

a) 0 to 13   
b) 1 to 12   
c) 0 to 14   
d) 1 to 14  

**Answer** a)

**Description**

For inner for loop we are giving a range from 0 to 20. In the immediate next line, we are checking if i = = 14. It is not true, because at start i will be 0. So, it will execute Line 12 not Line 10. So, the first print will be 0. Then when it will become 14, the if condition will become true and so it will execute Line 10 and then we are giving break. So, it will break from for loop and Line 12 will not get executed and so 14 will not get printed. So, 0 to 13 will get printed.

---
---


```






