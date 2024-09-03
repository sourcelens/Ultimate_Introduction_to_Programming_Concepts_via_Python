---
---


1 : What is meant by Linear Search in an Array?  

a) Finding out the Index of a particular element in an array  
b) Finding out the largest Number in an Array  
c) Finding out the Largest Number in an Array  
d) Finding out the Smallest Number in an Array  

**Answer** a) 

**Description**

Linear search means finding out the index of a particular element in an Array. It is one of the simplest forms of search option and the goal is to finding out something.  

---
---


```
#
def findNinMints(input,n):
    for index,integerI in enumerate(input):
        if(integerI == n):
            return index
    return "not found"
ints = [2,4,5,8,9,0]
print(findNinMints(ints,0))
```

2 : In the above program Line 7 indicates what?

a) List of integers separated by comma
b) List of strings
c) List of lists
d) None of the above

**Answer** a) 

**Description**

Indicates an array, a list of integers inside a square bracket and the numbers are separated by commas. We are putting the list into the variable ints.  

---
---


```
#
def findNinMints(input,n):
    for index,integerI in enumerate(input):
        if(integerI == n):
            return index
    return "not found"
ints = [2,4,5,8,9,0]
print(findNinMints(ints,0))
```

3 : In Line  8 what are the arguments passed to the function findNinMints?  

a) ints,0  
b) [2,4,5,8,9,0]  
c) None of the above  
d) Both a & b  

**Answer** a) 

**Description**

We are calling the function and passing the list along with a number and this is the number we are trying to find out and the function is supposed to return the index or position of the number.

---
---


```
#
def findNinMints(input,n):
    for index,integerI in enumerate(input):
        if(integerI == n):
            return index
    return "not found"
ints = [2,4,5,8,9,0]
print(findNinMints(ints,0))
```

4 : What will be the output of the above program?  

a) 5  
b) 8  
c) None of the above  
d) Null  

**Answer** a) 

**Description**

0 is in the 5th position so we will get 5 as the answer.

---
---


```
#
def findNinMints(input,n):
    for index,integerI in enumerate(input):
        if(integerI == n):
            return index
    return "not found"
ints = [2,4,5,8,9,0]
print(findNinMints(ints,8))
```

5 : What will be the output of the above program if the number becomes 8?  

a) 3  
b) 8  
c) None of the above  
d) Null  

**Answer** a) 

**Description**

8 is in the 3rd position so we will get 3 as the answer.

---
---


```


