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





