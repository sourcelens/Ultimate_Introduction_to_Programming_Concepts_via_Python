---
---


```
integers = [2, 5, 1, 9, 20]
sum = 0
for num in integers:
    sum = sum + num
average = sum / len(integers)
print("Avg is ", average)
```

1 : The above program is used to find the _______  

a) Sum of integers  
b) Average of integers  
c) Product of integers  
d) All of the above  

**Answer** b) 

**Description**

The above program finds the average of all the integers in the above array. For that we are iterating through every number with the for loop (Line 3), finding the sum (Line 4) and finally dividing it with the length of the array (Line 5) and printing the average (Line 6).  

---
---


```
integers = [2, 5, 1, 9, 20]
sum = 0
for num in integers:
    sum = sum + num
average = sum / len(integers)
print("Avg is ", average)
```

2 : In the above program the for loop will run how many times?  

a) 6  
b) 5  
c) 4  
d) 1  

**Answer** b) 

**Description**

There are 5 elements in the array. The for loop will iterate through each element in the array, so it will run 5 times.	  

---
---


```
integers = [2, 5, 1, 9, 20]
sum = 0
for num in integers:
    sum = sum + num
average = sum / len(integers)
print("Avg is ", average)
```

3 : What will be the output of len(integers) in the above program?  

a) 6  
b) 5  
c) 4  
d) 1  

**Answer** b) 

**Description**

There are 5 elements in the array. len(integers) will calculate the length of the array, that is the number of elements in the array. Here it is 5 and so it will show 5.  

---
---


```
def avgfun(intarray):
    sum = 0
    for num in intarray:
        sum = sum + num
    average = sum / len(intarray)
    return average
dictofNums = {"list1": [2, 5, 1, 9, 20], "list2ishere": [23, 53, 13, 93,203]}
for item in dictofNums:
    print("The avg of item " + item + " is " + str(avgfun(dictofNums[item])))
```

4 : In the above program the for loop in Line 8 will execute how many times?  

a) 1  
b) 2  
c) 3  
d) 4  

**Answer** b) 

**Description**

It will execute 2 times. We are giving the for loop such that it will iterate through each item in the dictionary. Here there are 2 items in the dictionary and so it will run 2 times.   

---
---


```
def avgfun(intarray):
    sum = 0
    for num in intarray:
        sum = sum + num
    average = sum / len(intarray)
    return average
dictofNums = {"list1": [2, 5, 1, 9, 20], "list2ishere": [23, 53, 13, 93,203]}
for item in dictofNums:
    print("The avg of item " + item + " is " + str(avgfun(dictofNums[item])))
```

5 : In the above program how many times the for loop (Line 3) will run for list1 in the dictionary?  

a) 5  
b) 6  
c) 4  
d) 2  

**Answer** a) 

**Description**

The for loop in Line 3 is iterating through the elements in the array of list1. It has 5 elements and so it will run 5 times.  

---
---


```
def avgfun(intarray):
    sum = 0
    for num in intarray:
        sum = sum + num
    average = sum / len(intarray)
    return average
dictofNums = {"list1": [2, 5, 1, 9, 20], "list2ishere": [23, 53, 13, 93,203]}
for item in dictofNums:
    print("The avg of item " + item + " is " + str(avgfun(dictofNums[item])))
```

6 : In the above program how many times the for loop (Line 3) will run for list2ishere in the dictionary?  

a) 5  
b) 6  
c) 4  
d) 2  

**Answer** a) 

**Description**

The for loop in Line 3 is iterating through the elements in the array of list2. It has 5 elements and so it will run 5 times.  

---
---


```
def avgfun(intarray):
    sum = 0
    for num in intarray:
        sum = sum + num
    average = sum / len(intarray)
    return average
dictofNums = {"list1": [2, 5, 1, 9, 20], "list2ishere": [23, 53, 13, 93,203]}
for item in dictofNums:
    print("The avg of item " + item + " is " + str(avgfun(dictofNums[item])))
```

7 : In the above program when we are calling the function?  

a) In Line 1  
b) In Line 8  
c) In Line 9  
d) In Line 7  

**Answer** c) 

**Description**

We are calling the function in Line 9 print statement, that is “str(avgfun(dictofNums[item]))”. We are giving “dictofNums[item]” as argument.  

---
---


```
def avgfun(intarray):
    sum = 0
    for num in intarray:
        sum = sum + num
    average = sum / len(intarray)
    return average
dictofNums = {"list1": [2, 5, 1, 9, 20], "list2ishere": [23, 53, 13, 93,203]}
for item in dictofNums:
    print("The avg of item " + item + " is " + str(avgfun(dictofNums[item])))
```

8 : The above program will give the average of which of the following?  

a) list1 & list2ishere separately  
b) list1 only  
c) list2ishere only  
d) None of the above  

**Answer** a) 

**Description**

It will give the average of both the list1 &amp; list2ishere separately as we are iterating through both the items in the dictionary.  

---
---



