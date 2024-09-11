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

6 : What Line 13 does in the above lines of code?  

a) Calling my_decorator()   
b) Calling decorator()   
c) Calling my_result()  
d) None of the above  

**Answer** a) 

**Description**

Here we are calling the function my_decorator. This function will return innerdecorfunc function. That means it is returning the function object. It is taking an input function object and decorating like Line 3,5. In the middle it is calling the actual function. So, inputfunc() is the function to be decorated. So, this is how it is getting called in Line 14, the result_function and we are passing the function to be decorated and it will come in Line 2.  

---
---


```
#
def my_decorator(inputfunc):
    def innerdecorfunc():
        print("Inside innerdecorfunc Before inputfunc execution")
        inputfunc()
        print("Inside innerdecorfunc After inputfunc execution")
    return innerdecorfunc


def function_2b_decorated():
    print("Inside the function_2b_decorated")

resultfunction = my_decorator(function_2b_decorated)
resultfunction()
```

7 : What the above lines of code does?  

a) Scope of the inputfunc shared between two functions  
b) Scope of the inputfunc not shared between two functions   
c) Scope of the inputfunc shared between three functions  
d) None of the above  

**Answer** a) 

**Description**

Here innerdecorfunc() is kept inside the my_decorator() function and the scope of the variable inputfunc is shared between these two functions. my_decorator function is returning the function object innerdecorfunc. my_decorator function is called in such a way that we are passing the decorator function object. When we start execution Line 3 will return Line 7 because the innerdecorfunc() is calling only at Line 14.  

---
---


```
def my_decorator(inputfunc):
    def innerdecorfunc():
        print("Inside innerdecorfunc Before inputfunc execution")
        inputfunc()
        print("Inside innerdecorfunc After inputfunc execution")
    return innerdecorfunc

def function_2b_decorated_with_no_sugar():
    print("Inside the function_2b_decorated_with_no_sugar")

function_2b_decorated_with_no_sugar = my_decorator(function_2b_decorated_with_no_sugar)
function_2b_decorated_with_no_sugar()

@my_decorator
def anotherFunctionToBeDecoratedWithSugarOfSyntax():
    print("Inside anotherFunctionToBeDecoratedWithSugarOfSyntax")

anotherFunctionToBeDecoratedWithSugarOfSyntax()
```

8 : What Line 15 does in the above lines of code?  

a) Replacement syntax   
b) Decoration syntax   
c) Sharing syntax   
d) None of the above  

**Answer** a) 

**Description**

Line 15 is a replacement for Line 12. Syntax is @ and name of the decorator. Line 9 is another function we are going to decorate. Line 13 is actually same as Line 19.  

---
---


```
#
def hello_decorator(func):
    def inner1(a,b):
        print("Before Execution")
        returned_value = func(a,b)
        print("After Execution")
        return returned_value
    return inner1

@hello_decorator
def sum_two_numbers(a,b):
    print("Inside the function")
    return a+b
print("Sum=",sum_two_numbers(1,2))
```

9 : What is Line 11 to 13 doing in the above lines of code?  

a) Returns sum   
b) Returns division  
c) Returns hello   
d) None of the above  

**Answer** a) 

**Description**

The function takes arguments a, b and returns the sum a+b. we are decorating the sum function.  

---
---


```
#
def decor1(func):
    def inner():
        x = func()
        return x * x
    return inner

def decor(func):
    def inner():
        x = func()
        return 2 * x
    return inner

@decor1
@decor

def num():
    return 10

@decor
@decor1

def num2():
    return 10

print( num() )
print( num2() )
```

10 : What is the meaning of the above lines of code?  

a) Nesting of decorators   
b) Nesting of classes   
c) Nesting of variables   
d) None of the above  

**Answer** a) 

**Description**

This code is for testing decorator chaining. Line 2 is the definition of the function and nothing is get executed here. In this code we can see Nesting of decorators. We have two decorators decor1 and decor. Both has inner functions and we are decorating two functions. The challenge here is to understand the order of execution.  

---
---



