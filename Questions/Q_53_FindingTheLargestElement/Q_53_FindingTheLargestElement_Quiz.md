---
---


```
def myMax (list1):
    max = list1[0]
    for x in list1:
        if x > max:
            max = x
    return max
list1 = [10, 20, 4, 45, 99]
print ("Largest element is: ", myMax (list1))
```

1 : The above program is for finding _______  

a) Smallest number in a list   
b) Largest number in a list   
c) Average of the list   
d) None of the above  

**Answer** b) 

**Description** 

The above program gives the largest number in the given list1. It compares each element in the list and print the maximum value element in the list.  

---
---


```
def myMax (list1):
    max = list1[0]
    for x in list1:
        if x > max:
            max = x
    return max
list1 = [10, 20, 4, 45, 99]
print ("Largest element is: ", myMax (list1))
```

2 : In Line 2 we are initializing a variable max with which value?  

a) First element of the array   
b) Second element of the array   
c) Third element of the array   
d) None of the above  

**Answer** a) 

**Description**

In Line 2 we are giving a value to the variable max and that is list1[0], which is 0th index of the list and it will be the first element of the list1.  

---
---


```
def myMax (list1):
    max = list1[0]
    for x in list1:
        if x > max:
            max = x
    return max
list1 = [10, 20, 4, 45, 99]
print ("Largest element is: ", myMax (list1))
```

3 : In the above program what we are doing in Line 4?  

a) Checking x is greater than max   
b) Checking max is greater than x   
c) Checking x is less than max   
d) None of the above  

**Answer** a) 

**Description**

In Line 4 we are doing a comparison with greater than operator ‘&gt;’ and checking whether x is greater than the value in the max.  

---
---


```
def myMax (list1):
    max = list1[0]
    for x in list1:
        if x > max:
            max = x
    return max
list1 = [10, 20, 4, 45, 99]
print ("Largest element is: ", myMax (list1))
```

4 : In the above program if x is greater than max in Line 4, what we are doing next?  

a) Replacing max with x   
b) Replacing x with max   
c) Any of the above   
d) None of the above  

**Answer** a) 

**Description**

In Line 4 we are checking whether x is greater than max. If it is True we are changing the value of max with the value of x (Line 5).

---
---


```
def myMax (list1):
    max = list1[0]
    for x in list1:
        if x > max:
            max = x
    return max
list1 = [10, 20, 4, 45, 99]
print ("Largest element is: ", myMax (list1))
```

5 : In the above program how many times the for loop will run?  

a) 4   
b) 5   
c) 6  
d) 1  

**Answer** b) 

**Description**

Here in the list1 there are 5 elements. for loop will check the condition x &gt; max for all these 5 elements. So, it will run 5 times.  

---
---


```
def myMax (list1):
    max = list1[0]
    for x in list1:
        if x > max:
            max = x
    return max
list1 = [10, 20, 4, 45, 99]
print ("Largest element is: ", myMax (list1))
```

6 : Which value will get printed at Line 8 for the above program?  

a) 10   
b) 20  
c) 45   
d) 99  

**Answer** d) 

**Description**

This program is for finding the largest value in list1. So, 99 will get printed which is the largest value.  

---
---


```
def myMax (list):
    max = list[0]
    for x in list:
        if x > max:
            max = x
    return max
mylistoflist = [[101, 220, 43, 445, 929], [120, 230, 47, 485, 969]]
count = 0
for item in mylistoflist:
    x = myMax(item)
    count = count +1
    print ("The maximum of list " + str(count) + " is " + str(x))
```

7 : In the above program we are finding the maximum value in _______  

a) 1 max value from each list  
b) A single max value with both list combined  
c) Any of the above   
d) None of the above  

**Answer** a) 

**Description**

Here we are finding the maximum value in each of the lists, because we are iterating through each list in Line 9 with the for loop. Then we are giving each list to the function separately in Line 10 (myMax(item)). So, it will find and print the maximum value in each list separately.  

---
---


```
def myMax (list):
    max = list[0]
    for x in list:
        if x > max:
            max = x
    return max
mylistoflist = [[101, 220, 43, 445, 929], [120, 230, 47, 485, 969]]
count = 0
for item in mylistoflist:
    x = myMax(item)
    count = count +1
    print ("The maximum of list " + str(count) + " is " + str(x))
```

8 : Which will get printed as maximum value in the case of list1 [101, 220, 43, 445, 929]?  

a) 929  
b) 445   
c) 220   
d) 43  

**Answer** a) 

**Description**

929 will get printed for list1. It is the maximum value in list1.  

---
---


```
def myMax (list):
    max = list[0]
    for x in list:
        if x > max:
            max = x
    return max
mylistoflist = [[101, 220, 43, 445, 929], [120, 230, 47, 485, 969]]
count = 0
for item in mylistoflist:
    x = myMax(item)
    count = count +1
    print ("The maximum of list " + str(count) + " is " + str(x))
```

9 : Which will get printed as maximum value in the case of list2 [120, 230, 47, 485, 969]?  

a) 485   
b) 969   
c) 47   
d) 230  

**Answer** b) 

**Description**

969 will get printed for list2. It is the maximum value in list2.  

---
---


```
def myMax (list):
    max = list[0]
    for x in list:
        if x > max:
            max = x
    return max
mylistoflist = [[101, 220, 43, 445, 929], [120, 230, 47, 485, 969]]
count = 0
for item in mylistoflist:
    x = myMax(item)
    count = count +1
    print ("The maximum of list " + str(count) + " is " + str(x))
```

10 : How many times the for loop in Line 9 will run for the above program?  

a) 1   
b) 2   
c) 3   
d) 4  

**Answer** b) 

**Description**

There are 2 items in the list which are again 2 lists. The for loop will iterate through both the items, so it will run for 2 times.  

---
---


```
def myMax (list):
    max = list[0]
    for x in list:
        if x > max:
            max = x
    return max
mylistoflist = [[101, 220, 43, 445, 929], [120, 230, 47, 485, 969], [10, 20, 4, 45, 99]]
count = 0
for item in mylistoflist:
    x = myMax(item)
    count = count +1
    print ("The maximum of list " + str(count) + " is " + str(x))
```

11 : How many times the for loop in Line 9 will run for the above program?  

a) 1   
b) 2  
c) 3   
d) 4  

**Answer** c) 

**Description**

There are 3 items in the list which are again 3 lists. The for loop will iterate through each of the items, so it will run for 3 times.  

---
---









