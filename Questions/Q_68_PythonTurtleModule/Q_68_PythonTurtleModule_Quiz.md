---
---


```
import turtle
x = turtle.Turtle()

def square(angle):
    x.forward(100)
    x.right(angle)
    x.forward(100)
    x.right(angle)
    x.forward(100)
    x.right(angle)
    x.forward(100)
    x.right(angle+5)

for i in range(72):
    square(90)
```

1 : What does Line 2 in the code do?  

a) Imports the turtle module   
b) Creates an instance of the Turtle class from the turtle module and assigns it to the variable x   
c) Both of the above  
d) None of the above  

**Answer** b) 

**Description** 

Line 2 creates an instance of the Turtle class from the turtle module and assigns it to the variable x. Line 1 Imports the turtle module into your Python environment.   

---
---


```
import turtle
x = turtle.Turtle()

def square(angle):
    x.forward(100)
    x.right(angle)
    x.forward(100)
    x.right(angle)
    x.forward(100)
    x.right(angle)
    x.forward(100)
    x.right(angle+5)

for i in range(72):
    square(90)
```

2 : In the above lines of code, what the function square does?  

a) Drawing a Square  
b) Drawing a Circle  
c) Drawing a Triangle   
d) None of the above  

**Answer** a) 

**Description**

The function in Line 4 draws a square.  

---
---


```
import turtle
x = turtle.Turtle()

def square(angle):
    x.forward(100)
    x.right(angle)
    x.forward(100)
    x.right(angle)
    x.forward(100)
    x.right(angle)
    x.forward(100)
    x.right(angle+5)

for i in range(72):
    square(90)
```

3 : In the above lines of code how many squares we are drawing?  

a) 72   
b) 100   
c) 90   
d) None of the above  

**Answer** a) 

**Description**

Here we are drawing 72 squares, passing 90 as the angle. Number of times this particular function square (90) is called is 72(0-71). That means 72 times we are drawing the square or calling this function.  

---
---


```
import turtle
x = turtle.Turtle()

def square(angle):
    x.forward(100)
    x.right(angle)
    x.forward(100)
    x.right(angle)
    x.forward(100)
    x.right(angle)
    x.forward(100)
    x.right(angle+5)

for i in range(72):
    square(90)
```

4 : In the above lines of code what is the meaning of x.forward (100)?  

a) Draws a line forward of length 100   
b) Draws a line forward of length 90   
c) Draws a line backward of length 100   
d) Draws a line backward of length 5  

**Answer** a) 

**Description**

x.forward (100) draws a line forward of lenght 100.  

---
---


```
import turtle
x = turtle.Turtle()

def square(angle):
    x.forward(100)
    x.right(angle)
    x.forward(100)
    x.right(angle)
    x.forward(100)
    x.right(angle)
    x.forward(100)
    x.right(angle+5)

for i in range(72):
    square(90)
```

5 : In the above lines of code what x.right(angle) does?  

a) Changing the angle 90-degree  
b) Changing the angle 72-degree   
c) Changing the angle 100-degree   
d) Changing the angle 5-degree  

**Answer** a) 

**Description**

In this case it is changing the angle 90 degree. We are passing the angle value in Line 15.  

---
---


```
import turtle
x = turtle.Turtle()

def square(angle):
    x.forward(100)
    x.right(angle)
    x.forward(100)
    x.right(angle)
    x.forward(100)
    x.right(angle)
    x.forward(100)
    x.right(angle+5)

for i in range(72):
    square(90)
```

6 : In the above lines of code what is the meaning of x.right(angle+5)?  

a) Rotates the turtle x to the right by an angle  angle + 5 degrees  
b) Slightly changing the drawing color   
c) Slightly changing the drawing thickness   
d) None of the above  

**Answer** a) 

**Description**

The line x.right(angle+5) in the code instructs the turtle object x to rotate or turn right by the specified angle, which in this case is angle + 5 degrees.   Here,we are passing 90 as the argument for angle when we call square(90) inside the loop. Thus, within the function, angle + 5 translates to 90 + 5 = 95 degrees.   So, every time x.right(angle+5) is executed, it means that the turtle turns 95 degrees to the right. This slight extra turn (5 degrees more than a perfect right angle) causes the drawing to create a spiral pattern instead of a simple square. 

---
---




