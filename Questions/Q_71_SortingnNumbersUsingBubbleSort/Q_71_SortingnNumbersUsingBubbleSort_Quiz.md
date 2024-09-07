---
---


```
def bubble_sort(arr):
    n = len(arr)
    for i in range(n):
        for j in range(0, n-i-1):
            if arr[j] > arr[j+1]:
                temp = arr[j]
                arr[j] = arr[j+1]
                arr[j+1] = temp
    return arr

arr = [64,34,25,12,22,11,90]
print("Original array is :",arr)
bubble_sort(arr)
print("Sorted array is :",arr)
```

1 : In the above program the function name is _______  

a) bubble_sort ()   
b) arr ()   
c) Both of the above  
d) None of the above  

**Answer** a) 

**Description**

The function name will be there just after the def keyword. So, here the function name is bubble_sort ().  

---
---


```
def bubble_sort(arr):
    n = len(arr)
    for i in range(n):
        for j in range(0, n-i-1):
            if arr[j] > arr[j+1]:
                temp = arr[j]
                arr[j] = arr[j+1]
                arr[j+1] = temp
    return arr

arr = [64,34,25,12,22,11,90]
print("Original array is :",arr)
bubble_sort(arr)
print("Sorted array is :",arr)
```

2 : In the above program we are initializing n with _______  

a) Length of the array   
b) Length of the array – 1   
c) Any of the above   
d) None of the above  

**Answer** a) 

**Description**  

In Line 2 we are giving n the value which is the length of the given array that is n = len(arr).  

---
---


```
def bubble_sort(arr):
    n = len(arr)
    for i in range(n):
        for j in range(0, n-i-1):
            if arr[j] > arr[j+1]:
                temp = arr[j]
                arr[j] = arr[j+1]
                arr[j+1] = temp
    return arr

arr = [64,34,25,12,22,11,90]
print("Original array is :",arr)
bubble_sort(arr)
print("Sorted array is :",arr)
```

3 : How many for loops are there in the above program?  

a) 1  
b) 2   
c) 3  
d) 4  

**Answer** b) 

**Description**

There are 2 for loops in the above program in Line 3 &amp; Line 4.

---
---


```
def bubble_sort(arr):
    n = len(arr)
    for i in range(n):
        for j in range(0, n-i-1):
            if arr[j] > arr[j+1]:
                temp = arr[j]
                arr[j] = arr[j+1]
                arr[j+1] = temp
    return arr

arr = [64,34,25,12,22,11,90]
print("Original array is :",arr)
bubble_sort(arr)
print("Sorted array is :",arr)
```

4 : In the above program the for loop in Line 4 is a _______  

a) Nested for loop   
b) Normal for loop   
c) Both of the above   
d) None of the above  

**Answer** a) 

**Description**

It is a nested for loop because it is inside another for loop.

---
---


```
def bubble_sort(arr):
    n = len(arr)
    for i in range(n):
        for j in range(0, n-i-1):
            if arr[j] > arr[j+1]:
                temp = arr[j]
                arr[j] = arr[j+1]
                arr[j+1] = temp
    return arr

arr = [64,34,25,12,22,11,90]
print("Original array is :",arr)
bubble_sort(arr)
print("Sorted array is :",arr)
```

5 : In the above program if one number in the array is greater than its succeeding number, what we are doing?  

a) Swapping the numbers   
b) Printing the numbers  
c) Not doing anything  
d) None of the above  

**Answer** a) 

**Description**

 If the number on the left is greater than its succeeding number, we are swapping it to the right. If we find that an element arr[j] is greater than its succeeding element arr[j+1], we are performing a swap between these two elements.  

 ---
 ---


 ```
def bubble_sort(arr):
    n = len(arr)
    for i in range(n):
        for j in range(0, n-i-1):
            if arr[j] > arr[j+1]:
                temp = arr[j]
                arr[j] = arr[j+1]
                arr[j+1] = temp
    return arr

arr = [64,34,25,12,22,11,90]
print("Original array is :",arr)
bubble_sort(arr)
print("Sorted array is :",arr)
```

6 : In the above program swapping of numbers is done in _______  

a) Line 4 & 5   
b) Line 6 to Line 8   
c) Line 9   
d) None of the above  

**Answer** b) 

**Description**

In the above program we are doing swapping from Line 6 to Line 8. For that we are creating another temporary variable called temp.  

---
---


```
def bubble_sort(arr):
    n = len(arr)
    for i in range(n):
        for j in range(0, n-i-1):
            if arr[j] > arr[j+1]:
                temp = arr[j]
                arr[j] = arr[j+1]
                arr[j+1] = temp
    return arr

arr = [64,34,25,12,22,11,90]
print("Original array is :",arr)
bubble_sort(arr)
print("Sorted array is :",arr)
```

7 : In the above program what we are doing?  

a) Sorting numbers in an array   
b) Printing numbers in an array   
c) Any of the above   
d) None of the above  

**Answer** a) 

**Description**

In the above program we are sorting the numbers given in the array in ascending order.  

---
---


```
def bubble_sort(arr):
    n = len(arr)
    for i in range(n):
        for j in range(0, n-i-1):
            if arr[j] > arr[j+1]:
                temp = arr[j]
                arr[j] = arr[j+1]
                arr[j+1] = temp
    return arr

arr = [64,34,25,12,22,11,90]
print("Original array is :",arr)
bubble_sort(arr)
print("Sorted array is :",arr)
```

8 : In which Line of the program we are modifying the code for optimization?  

a) Line 3   
b) Line 4  
c) Line 5   
d) Line 6  

**Answer** b) 

**Description**

In Line 4 we are giving “for j in range (0, n - i – 1):” Here we are giving n - i – 1 for code optimization. If it is given n, the loop will run unnecessarily, which is not needed, which will in turn increase the work load of the CPU. So, we are optimizing the code to avoid this and to reduce the number of iterations.  

---
---









