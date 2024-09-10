---
---


```
#
def innerdecorfunc(inputfunc):
    print("Inside innerdecorfunc Before inputfunc execution")
    inputfunc()
    print("Inside innerdecorfunc After inputfunc execution")

def my_decorator():
    return innerdecorfunc

def function_2b_decorated():
    print("Inside the function_2b_decorated")

result_function = my_decorator()
result_function(function_2b_decorated)
```

1 : The above lines of code are used to represent_________?  

a) Decorator  
b) Member variable  
c) Member function  
d) All of the above  

**Answer** a) 

**Description**  

The above lines of code is an application of Decorators using function objects.   

---
---


2 : What is a decorator?  

a) Using to modify the behavior of classes   
b) Using to modify the behavior of functions   
c) Using to modify the behavior of variables  
d) All of the above  

**Answer** b) 

**Description**

Modifying the behavior of a function without changing the function itself is the purpose of a decorator. That means adding additional code to a function without modifying the real function. We can decorate a function or a group of functions.  

---
---


```
#
def innerdecorfunc(inputfunc):
    print("Inside innerdecorfunc Before inputfunc execution")
    inputfunc()
    print("Inside innerdecorfunc After inputfunc execution")

def my_decorator():
    return innerdecorfunc

def function_2b_decorated():
    print("Inside the function_2b_decorated")

result_function = my_decorator()
result_function(function_2b_decorated)
```

3 : In the above lines of code name the function which we are trying to decorate?  

a) my_decorator()   
b) inputfunc()   
c) function_2b_decorated()   
d) None of the above  

**Answer** c) 

**Description**

We are going to decorate the function, function_2b_decorated() and the decorations we are going to add is in Line 3, 5. These decorations are inside the function innerdecor() and passing a function object as argument to this function. Here we are calling the actual function before and after the print statements.  

---
---


```
#
def innerdecorfunc(inputfunc):
    print("Inside innerdecorfunc Before inputfunc execution")
    inputfunc()
    print("Inside innerdecorfunc After inputfunc execution")

def my_decorator():
    return innerdecorfunc

def function_2b_decorated():
    print("Inside the function_2b_decorated")

result_function = my_decorator()
result_function(function_2b_decorated)
```

4 : In the above lines of code what is Line 7, 8 doing?  

a) Returns decorated version  
b) Returns original version   
c) Returns Nothing   
d) None of the above  

**Answer** a) 

**Description**

When you call my_decorator(), it returns innerdecorfunc as a result, allowing innerdecorfunc to be used to decorate another function. So the final output is the decorated function.   

---
---


```
#
def innerdecorfunc(inputfunc):
    print("Inside innerdecorfunc Before inputfunc execution")
    inputfunc()
    print("Inside innerdecorfunc After inputfunc execution")

def my_decorator():
    return innerdecorfunc

def function_2b_decorated():
    print("Inside the function_2b_decorated")

result_function = my_decorator()
result_function(function_2b_decorated)
```

5 : What Line 10 does in the above lines of code?  

a) Function to be decorated   
b) Decorated version of the function  
c) Both of the above  
d) None of the above  

**Answer** a) 

**Description**

This is the function to be decorated.   

---
---


```

