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

1 : What will be the output of the above lines of code?  

a) Turtle application to draw a circular pattern of squares  
b) Turtle application to draw Circle  
c) Turtle application to draw Cube   
d) None of the above  

**Answer** a) 

**Description**

This is a turtle application to draw circular pattern made up of 72 squares. Each square will be drawn with sides of 100 units and rotated slightly due to the incremental rotation of 5 degrees (x.right(angle+5) ) after each square.

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
    x.right(angle+10)

for i in range(36):
    square(90)
```

2 : How many times will the square(90) function be called in the for loop?  

a) 90 times  
b) 36 times  
c) 100 times  
d) None of the above  

**Answer** b) 

**Description**

The for loop iterates 36 times (for i in range(36)), calling square(90) function in each iteration.  

---
---



