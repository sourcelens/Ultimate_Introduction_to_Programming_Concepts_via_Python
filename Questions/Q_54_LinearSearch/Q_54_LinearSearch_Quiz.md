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
#
def findNinMints(input,n):
    for index,integerI in enumerate(input):
        if(integerI == n):
            return index
    return "not found"
ints = [2,4,5,8,9,0]
print(findNinMints(ints,1))
```

6 : what will be the output of the above program if the number becomes 1 ?

a) 1  
b) 6  
c) not found  
d) None of the above  

**Answer** c) 

**Description**

1 is not in the list so we will get not found as the answer.

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

7 : what is the purpose of enumerate function in line number 3?

a) To get item and its index  
b) To get item only  
c) To get index only  
d) None of the above  

**Answer** a) 

**Description**

It is a built in function.It will give the index along with the item. Instead of adding a counter we can use enumerate function.  

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

8 : what is the argument of the enumerate function?  

a) input  
b) ints  
c) Null  
d) None of the above  

**Answer** a) 

**Description**

In line number 3,after 'in' we are calling the enumerate function,by passing the list as the input.

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

9 : In Line 4 if(integerI == n) what does it do?  

a) Checking each element in the list is equal to n  
b) Checking the value of input  
c) Null  
d) None of the above  

**Answer** a) 

**Description**

This line is checking each element in the list is equal to n.  

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
print(findNinMints(ints,7))
```

10 : In the above code if integerI is not equal to n in all iterations, then what will be the output?  

a) not found  
b) n  
c) integerI  
d) None of the above  

**Answer** a) 

**Description**

If the condition become false it will return not found and this return is not part of the for loop.

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

11 : In which scenario, Line 6 gets executed?  

a) The integer n is not found in the list input  
b) The integer n is found in the list input  
c) The list input contains only one element, and that element is n  
d) None of the above  

**Answer** a) 

**Description**

The statement return "not found" on Line 6 will only execute if the loop completes all its iterations without finding a match.

---
---


```
#
def findNinMints(input,n):
    for index,integerI in enumerate(input):
        if(integerI == n):
            return index
    return "not found"

listofints={3:[21,41,15,38,29,10] , 31 :[21,41,15,31,38,29,10]}
for item in listofints:
    print(findNinMints(listofints[item],item))
```

12 : In the above code what is listofints in Line 8?  

a) It is a dictionary  
b) Array  
c) List  
d) None of the above  

**Answer** a) 

**Description**

Here we created a dictionary, listofints and we make the key as the number to search in the lists.  

---
---


```
#
def findNinMints(input,n):
    for index,integerI in enumerate(input):
        if(integerI == n):
            return index
    return "not found"

listofints={3:[21,41,15,38,29,10] , 31 :[21,41,15,31,38,29,10]}
for item in listofints:
    print(findNinMints(listofints[item],item))
```

13 : In Line  10 ‘item’ means what?  

a) key  
b) value  
c) List  
d) None of the above  

**Answer** a) 

**Description**

Here the item is going to be the key.

---
---


```
#
def findNinMints(input,n):
    for index,integerI in enumerate(input):
        if(integerI == n):
            return index
    return "not found"

listofints={3:[21,41,15,38,29,10] , 31 :[21,41,15,31,38,29,10]}
for item in listofints:
    print(findNinMints(listofints[item],item))
```

14 : What is the syntax for printing the list associated to the item/key?  

a) print(listofints[item])  
b) print(listofints(item)  
c) print(listofints())  
d) None of the above  

**Answer** a) 

**Description**

This is the syntax for printing the list associated to the item/key.

---
---


```
#
def findNinMints(input,n):
    for index,integerI in enumerate(input):
        if(integerI == n):
            return index
    return "not found"

listofints={3:[21,41,15,38,29,10] , 31 :[21,41,15,31,38,29,10]}
for item in listofints:
    print(findNinMints(listofints[item],item))
```

15 : What will be the output of the above program?  

a) not found,3  
b) 3, not found  
c) NULL  
d) None of the above  

**Answer** a) 

**Description**

3 is not in the list. So we got not found.  3, index of 31  

---
---


```
#Linear Search
def findNinMints(input,n):
    for index,integerI in enumerate(input):
        if(integerI == n):
            return index
    return "not found"
# ints = [2,4,5,8,9,0]
# print(findNinMints(ints,0))

listofints={3:[21,41,15,38,29,10] , 31 :["31",41,15,41,38,29,10]}

for item in listofints:
    print(findNinMints(listofints[item],item))
```

16 : What will be the output of the above program?  

a) not found,not found  
b) not found,null  
c) NULL,not found  
d) None of the above  

**Answer** a) 

**Description**

3 is not in the list.so we got not found and here “31” is a string literal not a number.so it is not equal to 31 integers.

---
---












