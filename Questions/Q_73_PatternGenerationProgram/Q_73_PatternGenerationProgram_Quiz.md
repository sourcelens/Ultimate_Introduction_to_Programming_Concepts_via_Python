---
---


```
def triangle(levels):
    decreasingcounter = levels
    for increasingcounter in range(0,levels):
        decreasingcounter = decreasingcounter -1
        for i in range(0,decreasingcounter):
            print(end=" ")
        for i in range(0,increasingcounter + 1):
            print("*",end= " ")
        print("\r")
levels = 10
triangle(levels)
```

1 : In the above lines of code what we are going to print_________?  

a) A pattern of Triangle   
b) A pattern of Square  
c) A pattern of Circle   
d) A pattern of Rectangle  

**Answer** a) 

**Description**  

This program will generate a pattern of Triangle with *. Here we are giving level 10. So, we get 10 levels of triangle. If we are giving 2, we will get 2 levels. If 3 then three levels and so on.  

---
---


```
def triangle(levels):
    decreasingcounter = levels
    for increasingcounter in range(0,levels):
        decreasingcounter = decreasingcounter -1
        for i in range(0,decreasingcounter):
            print(end=" ")
        for i in range(0,increasingcounter + 1):
            print("*",end= " ")
        print("\r")
levels = 10
triangle(levels)
```

2 : In the above lines of code what the function triangle does?  

a) Printing the pattern   
b) Returning levels   
c) Calculate the number of characters in the pattern   
d) None of the above  

**Answer** a) 

**Description**

The triangle() function in the code generates a triangle pattern of asterisks (*), with the number of levels (or rows) specified by the input parameter levels.   

---
---


3 : What are the different types of white spaces in Text files?  

a) Space   
b) Tab  
c) New Lines   
d) All of the above  

**Answer** d) 

**Description**

All are different types of white spaces in Text files. Space we can see as dots. Tab as small arrow. Another one is new lines. In Notepad++, we can see the white spaces by click on the following option. View -&gt;Appearance -&gt;Render Whitespace. If we uncheck, we can’t see the white space.   

---
---


```
def triangle(levels):
    decreasingcounter = levels
    for increasingcounter in range(0,levels):
        decreasingcounter = decreasingcounter -1
        for i in range(0,decreasingcounter):
            print(end=" ")
        for i in range(0,increasingcounter + 1):
            print("*",end= " ")
        print("\r")
levels = 10
triangle(levels)
```

4 : In the above lines of code what does the print statement in Line 6 do?  

a) Printing empty string   
b) Printing *   
c) Printing spaces before the start of each level's star   
d) Printing new line  

**Answer** c) 

**Description**  

Line 6 is responsible for printing spaces before the start of each level's star. If levels is 3, then it will print   Level 1: (2 spaces) *    Level 2: (1 space) * *    Level 3: (0 spaces) * * *    (Note: line 6 prints the spaces before the start of each level, not betweenstars.)  

---
---


```
def triangle(levels):
    decreasingcounter = levels
    for increasingcounter in range(0,levels):
        decreasingcounter = decreasingcounter -1
        for i in range(0,decreasingcounter):
            print(end=" ")
        for i in range(0,increasingcounter + 1):
            print("*",end= " ")
        print("\r")
levels = 10
print("test 1",end = " ")
print("test 2")
#triangle(levels)
```

5 : In the above lines of code what will be the output?  

a) test 1  test 2  
b) test 1  
   test 2  
c) test 2 test 1   
d) None of the above  

**Answer** a) 

**Description**

print("test 1",end = " "): This prints "test 1" and, instead of ending with the default newline character (\n), it ends with a space (" "). This means "test 1" will be followed by a space, and the cursor stays on the same line waiting for the next print instruction.   print("test 2"): This prints "test 2", followed by the default newline character since no end parameter is specified. Hence, "test 2" starts right after "test 1 ", and after printing "test 2", the cursor moves to the next line. The output will be test 1 test 2 

---
---


```
def triangle(levels):
    decreasingcounter = levels
    for increasingcounter in range(0,levels):
        decreasingcounter = decreasingcounter -1
        for i in range(0,decreasingcounter):
            print(end=" ")
        for i in range(0,increasingcounter + 1):
            print("*",end= " ")
        print("\r")
levels = 10
triangle(levels)
```

6 : In the above lines of code what happens when line 4 to line 9 is executed in first iteration?  

a) Prints the complete pattern   
b) First level/row of triangle is printed  
c) Prints white spaces   
d) None of the above  

**Answer** b) 

**Description**

From Line 4 to 9 one level of triangle printing occurs.  

---
---


```
def triangle(levels):
    decreasingcounter = levels
    for increasingcounter in range(0,levels):
        decreasingcounter = decreasingcounter -1
        for i in range(0,decreasingcounter):
            print(end=" ")
        for i in range(0,increasingcounter + 1):
            print("*",end= " ")
        print("\r")
levels = 10
triangle(levels)
```

7 : What is the purpose of print(“\r”) in Line 9?  

a) New line   
b) New paragraph  
c) New Triangle   
d) None of the above  

**Answer** a) 

**Description**

We are printing the new line character which is \r.   

---
---





