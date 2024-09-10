---
---


```
class Anything():
    pass
s=Anything()
print(s)
```

1 : What do the above lines of code demonstrate?  

a) creation of a basic class and the creation of an object from that class  
b) Intializing a list  
c) Dictionary   
d) All of the above  

**Answer** a) 

**Description**

The above lines show the simplest example of a class and usage of a class. Class is a template for an object and it is created using the class keyword. In Line 1 we created a class called Anything with an open and close parenthesis, ending with a colon. The Above code is an example for the shortest possible class in python.  

---
---


```
class Anything():
    pass
s=Anything()
print(s)
```

2 : In the above lines of code what Line 1,2 does?  

a) Defines a new class named Anything  
b) Creating List   
c) Creating Dictionary   
d) All of the above  

**Answer** a) 

**Description**

Class is a template for an object and it is created using the class keyword. In Line 1 we created a class called Anything with an open and close parenthesis, ending with a colon. Here we don’t have anything to implement inside the class. We just giving a pass, not created an object yet. Just defining how an object of this type, anything will look.  

---
---


3 : Class is also called ________in programming terminology?  

a) Type  
b) Real Object  
c) Array   
d) None of the above  

**Answer** a) 

**Description**

Class is also called type in programming terminology. type has more general meaning than class.  

---
---


```
class Anything():
    pass
s=Anything()
print(s)
```

4 : Which line of code in the above program creates an object of class or type Anything?  

a) s = Anything()   
b) class Anything():   
c) def Anything():  
d) All of the above  

**Answer** a) 

**Description**

In Line 3 we are creating an object of type Anything and assigning it to s.   

---
---


```
class Anything():
    pass
s=Anything()
print(s)
```

5 : In the above lines of code what Line 4 does?  

a) prints the memory address of the instance s of the class Anything   
b) printing the object   
c) None of the above  
d) All of the above  

**Answer** a) 

**Description**

It will print the the memory address of the instance s of the class Anything    . eg: &lt;__main__.Anything object at 0x000001926EA4B0A0. (address varies. This is just an example).  

---
---


```
class shape():
    def __init__(self):
        self.shape = 'Shape'

    def __str__(self):
        return "I am a {}.".format(self.shape)
    
s = shape()
print(s)
```

6 : What concept in object-oriented programming is demonstrated in the provided code snippet?  

a) Encapsulation  
b) Inheritance  
c) Visibility   
d) All of the above  

**Answer** a) 

**Description**  

In object-oriented programming these two functions ( __init__() __str__() ) are internal to the class . We are not supposed to access it from outside directly. They start and end with underscore underscore. This is the python way of handling private data to a class. By using underscores, Python adopts a convention for encapsulation, safeguarding certain aspects of a class from external access.  

---
---


7 : What is meant by a member variable in the context of a class?  

a) strings and integers  
b) variable which are not part of the class  
c) variable which is part of the class   
d) All of the above  

**Answer** c) 

**Description**

Member variable is a variable which is part of the class, getting initialized each time when we create an object.   

---
---


8 : What is meant by Constructor?  

a) used to Initialize members of the class   
b) used to create variables of the class  
c) Not part of the class  
d) All of the above  

**Answer** a) 

**Description**

Constructor is used to initialize the members of the class. It has the same name of the class, Initializing the objects of type or class.  

---
---


```
#
class shape():
    def __init__(self):
        self.shape = 'Shape'

    def __str__(self):
        return "I am a {}.".format(self.shape)
    
s = shape()
print(s)

class Polygon(shape):

    def __init__(self):
        self.shape = 'Polygon'
        self.side_lengths = None
    
    def compute_perimeter(self):
        return sum(self.side_lengths)
    
    def get_number_of_edges(self):
        return len(self.side_lengths)
    
p = Polygon()
print(p)
print(p.shape)
```

9 : In the provided code snippet, which class extends the shape class through inheritance?  

a) shape  
b) Polygon  
c) None of the above  
d) All of the above  

**Answer** b) 

**Description**

In the provided code snippet, the Polygon class extends the shape class through inheritance. This is indicated by the line class Polygon(shape):, where shape is specified as the base class from which Polygon inherits.

---
---


```
#
class shape():
    def __init__(self):
        self.shape = 'Shape'

    def __str__(self):
        return "I am a {}.".format(self.shape)
    
s = shape()
print(s)

class Polygon(shape):

    def __init__(self):
        self.shape = 'Polygon'
        self.side_lengths = None
    
    def compute_perimeter(self):
        return sum(self.side_lengths)
    
    def get_number_of_edges(self):
        return len(self.side_lengths)
    
p = Polygon()
print(p)
print(p.shape)
```

10 : What is function overriding?  

a) Priority to child class  
b) Priority to parent class  
c) None of the above  
d) All of the above  

**Answer** a) 

**Description**

In Python, when both a parent class (superclass) and a child class (subclass) have functions with the same name, the function defined in the child class takes precedence over the function in the parent class. This concept is known as function overriding.  

---
---


```
class Anything():
    pass

s=Anything()
print(s)


class shape():
    
    def __init__(self):
        self.shape = 'Shape'

    def __str__(self):
        return "I am a {}.".format(self.shape)
    
s = shape()
print(s)


class Polygon(shape):

    def __init__(self):
        self.shape = 'Polygon'
        self.side_lengths = None
    
    def compute_perimeter(self):
        return sum(self.side_lengths)
    
    def get_number_of_edges(self):
        return len(self.side_lengths)
    
p = Polygon()
print(p)
print(p.shape)

p.compute_perimeter()
p.get_number_of_edges()
```

11 : What will happen if we execute the above code?  

a) Executes normally   
b) Error will occur  
c) Runs successfully  
d) All of the above  

**Answer** b) 

**Description**

In the provided code snippet, lines 36 and 37 call functions compute_perimeter() and get_number_of_edges() on an instance of the Polygon class (p). However, there is an issue in the Polygon class constructor (__init__) where self.side_lengths is initialized to None. This will cause compute_perimeter() to raise an exception when sum(self.side_lengths) is called because None is not iterable.  To correct this and ensure that these functions execute without errors, you need to properly initialize self.side_lengths as a list (or any iterable) containing the side lengths of the polygon.  

---
---


```
#
class Anything():
    pass

s=Anything()
print(s)


class shape():
    
    def __init__(self):
        self.shape = 'Shape'

    def __str__(self):
        return "I am a {}.".format(self.shape)
    
s = shape()
print(s)


class Polygon(shape):

    def __init__(self):
        self.shape = 'Polygon'
        self.side_lengths = None
    
    def compute_perimeter(self):
        return sum(self.side_lengths)
    
    def get_number_of_edges(self):
        return len(self.side_lengths)
    
p = Polygon()
print(p)
print(p.shape)

p.compute_perimeter()
p.get_number_of_edges()


class Rectangle(Polygon):
    
    def __init__(self):
        self.shape = 'Rectangle'
        self.side_lengths = [1,1,1,1]
    
obj = Rectangle()
print(obj)
print(obj.get_number_of_edges())
print(obj.compute_perimeter())
```

12 : How the side_lengths attribute is initialized in the Rectangle class?  

a) self.side_lengths = [1,1,1,1]   
b) Error will come   
c) Rectangle.side_lengths = [1,1,1,1]   
d) None of the above  

**Answer** a) 

**Description**

In the Rectangle class, the __init__ function initializes self.side_lengths to [1, 1, 1, 1]. This sets the side lengths of the rectangle to 1 unit each for all four sides, effectively defining a square with side length 1.  

---
---







