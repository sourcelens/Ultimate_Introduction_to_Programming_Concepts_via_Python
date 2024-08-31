---
---


1 : Keys in Python dictionary are ______  

a) Sorted  
b) Not sorted   
c) May be sorted   
d) None of the above  

**Answer** a) 

**Description** 

 Keys in Python dictionary are sorted. So, it is easy to look up a particular key in Python dictionary.  

 ---
 ---


 2 : Values in Python dictionary are ______  

 a) Sorted   
 b) Not sorted   
 c) May be sorted   
 d) None of the above  

 **Answer** b) 

**Description**

Values in Python dictionary are not sorted.   

---
---


3 : Data structure in which repetition is not allowed is _______  

a) Set   
b) Dictionary   
c) Array   
d) All of the above  

 **Answer** a) 

**Description**

Data structure in which repetition is not allowed is set.  

---
---


4 : Key or value in a dictionary can be _______  

a) Number   
b) String   
c) Any other data structure   
d) All of the above  

 **Answer** d) 

**Description**

It can be any data structure.  

---
---


```
employdetails = {
      "name":"James",
      "number":"123456",
      "Address":"Test address, NSW 1234"
      }
```

5 : In the given dictionary, what will be the result of adding the following lines of code?

```
employdetails["car"] = "honda"
print (employdetails)
```

a) “car”: “honda” will get added to the dictionary  
b) It will not get added   
c) May be added   
d) None of the above  

 **Answer** a) 

**Description**

If you add the line employdetails["car"] = "honda", it will add a new key-value pair to the dictionary. The updated dictionary will include the new key "car" with the value "honda". print (employdetails) will print all the key:value pair in the dictionary including 'car': 'honda'.

---
---


```
employdetails = {
      "name":"James",
      "number":"123456",
      "Address":"Test address, NSW 1234"
      }
```

6 : What will get printed after adding the below line in the dictionary?  

```
print ( employdetails.keys () )
```

a) It will print all the values 
b) It will print all keys  
c) It will print the dictionary   
d) None of the above  

 **Answer** b) 

**Description**

This is the method to print all the keys in the dictionary.

---
---


```
employdetails = {
      "name":"James",
      "number":"123456",
      "Address":"Test address, NSW 1234"
      }

print(employdetails["Address"])
```

7 : What will be the output of the above program?  

a) Will print the value of address   
b) Will print the value of name   
c) Nothing will get printed   
d) None of the above  

 **Answer** a) 

**Description**

This line print(employdetails["Address"]) accesses the value associated with the key "Address" in the employdetails dictionary and prints it to the console. When you run the code with the print(employdetails["Address"]) statement, it will output "Test address, NSW 1234" because that is the value stored in the dictionary under the key "Address".

---
---


```
employdetails = {
      "name":"James",
      "number":"123456",
      "Address":"Test address, NSW 1234"
      }

print(employdetails["name"])
```

8 : What will be the output of the above code?  

a) Will print the value of address   
b) Will print the value of name   
c) Nothing will get printed  
d) None of the above  

 **Answer** b) 

**Description**

This line print(employdetails["name"]) accesses the value associated with the key "name" in the employdetails dictionary and prints it to the console. When you run the code with the print(employdetails["name"]) statement, it will output "James" because that is the value stored in the dictionary under the key "name".  

---
---


```
employdetails = {
      "name":"James",
      "number":"123456",
      "Address":"Test address, NSW 1234"
      }
```

9 : What will happen if we add the below lines after the dictionary and execute the code?

```
employdetails.pop ("number")
```

a) The element number will be removed  
b) The element name will be removed   
c) The element Address will be removed   
d) None of the above  

 **Answer** a) 

**Description**

adding employdetails.pop("number") removes the "number" key-value pair from the employdetails dictionary.

---
---


```
employdetails = {
      "name":"James",
      "number":"123456",
      "Address":"Test address, NSW 1234"
      }

employdetails.pop ("name")
```

10 : What will be the output of the code?  

a) The element number will be removed   
b) The element name will be removed   
c) The element Address will be removed   
d) None of the above   

 **Answer** b) 

**Description**

adding employdetails.pop("name") removes the "name" key-value pair from the employdetails dictionary.  

---
---


```
employdetails = {
      "name":"James",
      "number":"123456",
      "Address":"Test address, NSW 1234"
      }
```

11 : What will happen if we add the below line after the dictionary and execute the code?

```
employdetails.pop ("Address")
```

a) The element number will be removed   
b) The element name will be removed   
c) The element Address will be removed   
d) None of the above  

 **Answer** c) 

**Description**

adding employdetails.pop("Address") removes the "Address" key-value pair from the employdetails dictionary.  

---
---










 
