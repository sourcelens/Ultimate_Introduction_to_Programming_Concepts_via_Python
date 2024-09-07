---
---


1 : What is the idea behind the Binary search algorithm?  

a) Repeatedly dividing the search interval in half  
b) Comparing the element with the one after it, swapping their values if needed  
c) Compare each element in the array sequentially until the target element is found  
d) None of the above  

**Answer** a)  

**Description** 

The idea behind this algorithm is reducing the search area into half in each iteration. So, we are not comparing each and every element. First, we divide the list and find the mid value. Then compare the value which we have to find out is equal to mid. If it is not equal to mid, check whether the value is greater than mid. If yes search after mid. Otherwise check whether the value is less than mid, if yes search before mid. Repeating this process until we get the required output.  

---
---


```
#
def binary_search(numlist,n):
    leftindex = 0
    rightindex = len(numlist) - 1
    while leftindex <= rightindex:
        mid = leftindex + (rightindex - leftindex) // 2
        if numlist[mid] == n:
            return mid
        elif numlist[mid] < n:
            leftindex = mid + 1
        else:
            rightindex = mid - 1
    return -1


numlist = [1,3,5,8,10,14,19,21,30]
n = 9
result = binary_search(numlist,n)
if result != -1:
    print("Found",result)
else:
    print("Not Found")
```

2 : What leftindex and rightindex does in the above lines of code?  

a) leftindex pointing to the index of first value   

    right index pointing to the index of last value  

b) leftindex pointing to the index of last value   

     right index pointing to the index of first value  

c) leftindex pointing to the index of first value   

    right index pointing to the index of mid value  

d) None of the above  

**Answer** a)  

**Description**

leftindex:This variable keeps track of the leftmost index of the current search range. Initially set to 0, it represents the starting point of the array. rightindex:This variable keeps track of the rightmost index of the current search range. Initially set to len(numlist) - 1, it represents the end point of the array or endpoint of the current segment of the array being searched.  

---
---


```
#
def binary_search(numlist,n):
    leftindex = 0
    rightindex = len(numlist) - 1
    while leftindex <= rightindex:
        mid = leftindex + (rightindex - leftindex) // 2
        if numlist[mid] == n:
            return mid
        elif numlist[mid] < n:
            leftindex = mid + 1
        else:
            rightindex = mid - 1
    return -1


numlist = [1,3,5,8,10,14,19,21,30]
n = 9
result = binary_search(numlist,n)
if result != -1:
    print("Found",result)
else:
    print("Not Found")
```

3 : In the above lines of code, till when the while loop will run?  

a) leftindex <= rightindex   
b) leftindex >= rightindex   
c) leftindex ==mid   
d) None of the above  

**Answer** a)  

**Description**

While loop in Line 5 will run as long as the leftindex is less than or equal to rightindex. 

---
---


```
#
def binary_search(numlist,n):
    leftindex = 0
    rightindex = len(numlist) - 1
    while leftindex <= rightindex:
        mid = leftindex + (rightindex - leftindex) // 2
        if numlist[mid] == n:
            return mid
        elif numlist[mid] < n:
            leftindex = mid + 1
        else:
            rightindex = mid - 1
    return -1


numlist = [1,3,5,8,10,14,19,21,30]
n = 9
result = binary_search(numlist,n)
if result != -1:
    print("Found",result)
else:
    print("Not Found")
```

4 : In the above lines of code what does Line 6 do?  

a) Finding mid   
b) Finding rightindex  
c) Finding leftindex  
d) None of the above  

**Answer** a)  

**Description**

Line 6 is the most critical line in this program. We are calculating the mid here. In first iteration, leftindex is 0 and rightindex is 8. So, 0 + (8 – 0) // 2 which is equal to 0 + 4 = 4, we will get the mid = 4 which is the 4th element. In this case 10 is the mid value.  

---
---


```
#
def binary_search(numlist,n):
    leftindex = 0
    rightindex = len(numlist) - 1
    while leftindex <= rightindex:
        mid = leftindex + (rightindex - leftindex) // 2
        if numlist[mid] == n:
            return mid
        elif numlist[mid] < n:
            leftindex = mid + 1
        else:
            rightindex = mid - 1
    return -1


numlist = [1,3,5,8,10,14,19,21,30]
n = 9
result = binary_search(numlist,n)
if result != -1:
    print("Found",result)
else:
    print("Not Found")
```

5 : In the above lines of code what does Line 7 do?  

a) middle element (numlist[mid]) is compared with the target value (n)  
b) Checking whether mid is greater than the value that we are searching   
c) Checking whether mid is less than the value that we are searching  
d) None of the above  

**Answer** a)  

**Description**

numlist[mid] represents the value of the element at the middle index of the current search range. n is the value we are searching for in numlist. In numlist[mid] == n, the middle element (numlist[mid]) is compared with the target value (n).

---
---


```
#
def binary_search(numlist,n):
    leftindex = 0
    rightindex = len(numlist) - 1
    while leftindex <= rightindex:
        mid = leftindex + (rightindex - leftindex) // 2
        if numlist[mid] == n:
            return mid
        elif numlist[mid] < n:
            leftindex = mid + 1
        else:
            rightindex = mid - 1
    return -1


numlist = [1,3,5,8,10,14,19,21,30]
n = 9
result = binary_search(numlist,n)
if result != -1:
    print("Found",result)
else:
    print("Not Found")
```

6 : After the first iteration what will be the values of leftindex and rightindex in the above lines of code?  

a) leftindex = 0, rightindex = 3   
b) leftindex = 3, rightindex = 0   
c) leftindex = 3, rightindex = 8  
d) None of the above  

**Answer** a)  

**Description**

In Line 9, we are checking value of mid ie,10 is &lt; 9. That condition is not true. So, control will go to Line 12 and the value of rightindex become mid – 1 ie,4 - 1 which is equal to 3. There is no change in leftindex

---
---


```
#
def binary_search(numlist,n):
    leftindex = 0
    rightindex = len(numlist) - 1
    while leftindex <= rightindex:
        mid = leftindex + (rightindex - leftindex) // 2
        if numlist[mid] == n:
            return mid
        elif numlist[mid] < n:
            leftindex = mid + 1
        else:
            rightindex = mid - 1
    return -1


numlist = [1,3,5,8,10,14,19,21,30]
n = 9
result = binary_search(numlist,n)
if result != -1:
    print("Found",result)
else:
    print("Not Found")
```

7 : In the above lines of code when will Line 13 gets executed ?  

a) If number we are searching is not found   
b) If number we are searching is a string found   
c) If number we are searching is a roman letter found   
d) None of the above  

**Answer** a)  

**Description**

In Line 5, when leftindex is greater than rightindex we are going to exit the while loop and return -1. Because the number is not found in the list.   

---
---


8 : “In most debuggers, the WATCH window is designed for observing the values of expressions or variables as your code executes. It's generally not intended for performing assignments (=) or altering the state of the program being debugged.” Is this statement true or false?

a) True   
b) False  
c) None of the above  
d) May or may not be true  

**Answer** a)  

**Description**

This statement is true.  

---
---









    
