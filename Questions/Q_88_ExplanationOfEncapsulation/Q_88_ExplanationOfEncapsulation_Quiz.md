---
---


```
#
class Car():
    wheels = 4

    def __init__(self,name,enginetype):
        self.name = name
        self.__enginetype = enginetype

    def run(self):
        print("Running car with engine type" + self.__enginetype)

myCar = Car("S1car","Turbo")
myCar.run()

print("Num of wheel of myCar",myCar.wheels)
print("Name of myCar is" + myCar.name)
```

1 : What kind of variable is wheels in line 3?  

a) class variable   
b) object variable   
c) protected variable   
d) None of the above  

**Answer** a) 

**Description**  

Class variables are defined within the class. 'wheels' is defined directly within the class Car, outside of any functions. Class variables are shared among all instances (objects) of the class Car. They are accessed using the class name (Car.wheels) or through an object (myCar.wheels). In this case, myCar.wheels accesses the class variable wheels through the object myCar.  

---
---


```
#
class Car():
    wheels = 4

    def __init__(self,name,enginetype):
        self.name = name
        self.__enginetype = enginetype

    def run(self):
        print("Running car with engine type" + self.__enginetype)

myCar = Car("S1car","Turbo")
myCar.run()

print("Num of wheel of myCar",myCar.wheels)
print("Name of myCar is" + myCar.name)
```

2 : In the above lines of code how self.name differs from wheels?  

a) Specific to object   
b) Member function   
c) Class variable   
d) All of the above  

**Answer** a) 

**Description**

In line 6, the variable self.name, initialized inside the __init__ function is specific to the object.  

---
---


```
#
class Car():
    wheels = 4

    def __init__(self,name,enginetype):
        self.name = name
        self.__enginetype = enginetype

    def run(self):
        print("Running car with engine type" + self.__enginetype)

myCar = Car("S1car","Turbo")
myCar.run()

print("Num of wheel of myCar",myCar.wheels)
print("Name of myCar is" + myCar.name)
```

3 : In the above lines of code what is done by Line 7?  

a) Private variable   
b) Public variable   
c) Private function  
d) None of the above  

**Answer** a) 

**Description**

The function __init__ is an internal function and it has an internal variable called __enginetype in Line 7. This is a private variable of the object.  The use of double underscores (__enginetype) indicates that __enginetype is intended to be a private variable.  

---
---


```
#
class Car():
    wheels = 4

    def __init__(self,name,enginetype):
        self.name = name
        self.__enginetype = enginetype

    def run(self):
        print("Running car with engine type" + self.__enginetype)

myCar = Car("S1car","Turbo")
myCar.run()

print("Num of wheel of myCar",myCar.wheels)
print("Name of myCar is" + myCar.name)
```

4 : In the above code, what distinguishes Line 6 (self.name = name) from Line 7 (self.__enginetype = enginetype)?  

a) Both are public variables   
b) Public and Private object variable  
c) None of the above  
d) All of the above  

**Answer** b) 

**Description**

Line 6 (self.name = name): This line initializes a public object variable name. Public variables in Python classes are accessible directly from outside the class. Line 7 (self.__enginetype = enginetype): This line initializes a private object variable __enginetype. Private variables in Python are denoted by names starting with double underscores (__). They are intended for internal use within the class. Accessing it directly from outside the class (like myCar.__enginetype) would typically result in an AttributeError. But it can be accessed by (myCar._Car__enginetype).   

---
---


```
#
class Car():
    wheels = 4

    def __init__(self,name,enginetype):
        self.name = name
        self.__enginetype = enginetype

    def run(self):
        print("Running car with engine type" + self.__enginetype)

myCar = Car("S1car","Turbo")
myCar.run()

print("Name of wheel of myCar",myCar.wheels)
print("Name of myCar is" + myCar.name)

myGreenCar = Car("Tesla","ElonMusk")
myGreenCar.run()

print("Num of wheel of myGreenCar",myGreenCar.wheels)
print("Name of myCar is" + myGreenCar.name)
print("Name of myCar is" + myCar.name)

myGreenCar.run()
myCar.run()
```

5 : In the provided code, what are myCar = Car("S1car","Turbo") and myGreenCar = Car("Tesla","ElonMusk")? (Line 12 and Line 18)  

a) Two objects of class Car   
b) Two functions of class Car   
c) Two variables of class Car   
d) All of the above  

**Answer** a) 

**Description**

They are two objects of the same class Car. Here there is no relation with the two objects. They are completely unrelated.  

---
---


```
#
class Car():
    wheels = 4

    def __init__(self,name,enginetype):
        self.name = name
        self.__enginetype = enginetype

    def run(self):
        print("Running car with engine type" + self.__enginetype)

myCar = Car("S1car","Turbo")
myCar.run()

print("Num of wheel of myCar",myCar.wheels)
print("Name of myCar is" + myCar.name)

print("Engine type of myCar",myCar.__enginetype)

myGreenCar = Car("Tesla","ElonMusk")
myGreenCar.run()

print("Num of wheel of myGreenCar",myGreenCar.wheels)
print("Name of myCar is" + myGreenCar.name)
print("Name of myCar is" + myCar.name)

myGreenCar.run()
myCar.run()
```

6 : What will happen if we try to execute Line 18?  

a) Executes normally   
b) We get an Attribute error   
c) We get Syntax error  
d) All of the above  

**Answer** b) 

**Description**  

We have a variable __ enginetype which is initialized in Line 7. In Line 18 we are trying to access the variable from here, then we will get an Attribute Error because the’ Car’ object has no attribute ‘__enginetype’. Because the variable is internal to the class. We are not supposed to access it from outside.

---
---


```
#
class Animal:
    def speak(self):
        raise NotImplementedError("Subclass must implement this method")
    
class Dog(Animal):
    def speak(self):
        return " Baaw"
    
class Cat(Animal):
    def speak(self):
        return " Meeow"
    
animals = [ Dog() , Cat() ]

for animal in animals:
    print(animal.speak())
```

7 : In the above lines of code what is the purpose of Line 4?  

a) raising exception   
b) Implementing exception  
c) Calling the function   
d) All of the above  

**Answer** a) 

**Description**

It is an example for implementation of Polymorphism. We have a class called Animal which is the parent or base class and Dog and Cat are derived from the base class Animal. Inside the speak function in base class we are raising an exception, not implemented error. If a function is not implemented in base class, we can raise this exception. This is also a way of letting the derived classes to implement that function.  

---
---


```
#
class Animal:
    def speak(self):
        raise NotImplementedError("Subclass must implement this method")
    
class Dog(Animal):
    def speak(self):
        return " Baaw"
    
class Cat(Animal):
    def speak(self):
        return " Meeow"
    
animals = [ Dog() , Cat() ]

for animal in animals:
    print(animal.speak())
```

8 : In the above lines of code what we are doing in Line14?  

a) Creating Array of objects   
b) Implementing exception  
c) Calling the function   
d) All of the above  

**Answer** a) 

**Description**

Dog() and Cat() are constructor calls that create new objects of the Dog and Cat classes, respectively. These objects are then stored in an array assigned to the variable animals.  

---
---





