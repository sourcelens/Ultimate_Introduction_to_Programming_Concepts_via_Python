---
---


1 : Arrays are represented in Python within _______

a) Square brackets [ ]  
b) Parenthesis ( )  
c) Within quotes  
d) All of the above  

**Answer** a) 

**Description**

Arrays are represented in Python within Square brackets [ ]. Eg:- fruits = [ “mango”, “apple”, “grapes” ]  

---
---


2 : Elements in an array in Python starts with which index number?

a) 0  
b) 1  
c) 2  
d) -1 

**Answer** a) 

**Description**

Indexing in Python array starts at 0. This means that the first element in a list has an index of 0, the second element has an index of 1, and so on.  

---
---


```
fruits = [ "mango", "apple", "tomato"]
print (fruits)
```

3 : In the above code which will get printed on the screen?  

a) 'mango'  
b) 'apple'  
c) 'tomato'  
d) All will get printed   

**Answer** d) 

**Description**

print (fruits) will print all the elements of the array to the screen.    


---
---


```
fruits = [ "mango", "apple", "tomato"]
print (fruits[0])
```

4 : In the above code which will get printed on the screen?  

a) mango  
b) apple  
c) tomato  
d) All will get printed  

**Answer** a) 

**Description**

The variable fruits is initialized as an array containing three string elements: "mango", "apple", and "tomato". In Python, list indexing starts from 0. Therefore, fruits[0] accesses the first element in the list fruits, which is "mango".

---
---


```
fruits = [ "mango", "apple", "tomato"]
print (fruits[1])
```

5 : In the above code which will get printed on the screen?  

a) mango  
b) apple  
c) tomato  
d) All will get printed  

**Answer** b) 

**Description**

fruits is a list containing three elements. Lists in Python are zero-indexed, meaning the first element has an index of 0. Since the element at index 1 in the fruits list is "apple", when print(fruits[1]) is executed, it will print "apple" to the screen.  

---
---


```
fruits = [ "mango", "apple", "tomato"]
print (fruits[2])
```

6 : In the above code which will get printed on the screen?  

a) mango  
b) apple  
c) tomato  
d) All will get printed  

**Answer** c) 

**Description**

fruits is a list containing three elements. Lists in Python are zero-indexed, meaning the first element has an index of 0. Since the element at index 2 in the fruits list is "tomato", when print(fruits[2]) is executed, it will print "tomato" to the screen.  

---
---


7 : Can a Python array contain both strings and numbers?  

a) Yes  
b) No  

**Answer** a) 

**Description**

In Python we can put different types of literals in an array. Eg:- fruits = [ “mango”, 1, “apple” ]. Languages like C, C++ won’t allow this.

---
---


```
fts = [1, 2, 3]
fts.append(10)
print(fts)
```

8 : In the above code which will get printed on the screen?  

a) [ 1, 2, 3]  
b) [1, 2, 3, 10]  
c) [ 1, 2]  
d) [ 1 ]  

**Answer** b) 

**Description**

append function will add an element to the array. So, here the array will become [1, 2, 3, 10 ].  The append() function is used to add the number 10 to the end of the list fts.  

---
---


```
fts = [1, 2, 3, 10]
fts.pop ()
print(fts)
```

9 : In the above code which will get printed on the screen?  

a) [ 1, 2, 3 ]  
b) [1, 2, 3, 10 ]  
c) [ 1, 2 ]  
d) [ 1 ]  

**Answer** a) 

**Description**

Pop function will remove the last item from the array. So, it will become [ 1, 2, 3 ].  

---
---


```
fts = [1, 2, 3]
fts.remove (2)
print(fts)
```

10 : In the above code what will get printed on the screen?  

a) [ 1, 2, 3 ]  
b) [1, 2, 3, 10 ]  
c) [ 1, 3, 10 ]  
d) [ 1, 3 ]  

**Answer** d) 

**Description**

This function will remove the element 2 and the array will become [ 1, 3 ].

---
---


```
fts = [1, 2, 3]
fts.reverse ()
print(fts)
```

11 : In the above code which will get printed on the screen?  

a) [ 1, 2, 3 ]  
b) [3, 2, 1 ]  
c) [ 1, 3, 2 ]  
d) [ 1, 3 ]  

**Answer** b) 

**Description**

reverse function will reverse the order of elements in the array.

---
---


```
fts = [2, 3, 1]
fts.sort ()
print(fts)
```

12 : In the above code which will get printed on the screen?

a) [ 1, 2, 3 ]  
b) [3, 2, 1 ]  
c) [ 1, 3, 2 ]  
d) [ 1, 3 ]  

**Answer** a) 

**Description**

sort function will sort the numbers in the array in order. Initially, fts is assigned the list [2, 3, 1]. The sort() function is then called on fts. This sorts the elements of the list in ascending order.

---
---









