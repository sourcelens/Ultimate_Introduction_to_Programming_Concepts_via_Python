---
---


```
temperature = 30
humidity = 90
if (temperature == 30 and humidity > 80):
    print ("There will be rain today")
```

1 : Regarding the above program, which among the below statement/s is/are correct?  

a) There will be rain today will get printed  
b) Nothing will be printed  
c) May get printed  
d) None of the above  

**Answer** a) 

**Description**

Here “There will be rain today” will get printed onto the screen. In the if statement we are checking two conditions. Both are true in this case, so print statement will execute in this case. Here we are giving the keyword ‘and’. So, print will happen only if both conditions are true.  

---
---


```
temperature = 30
humidity = 70
if (temperature == 30 and humidity > 80):
    print ("There will be rain today")
```

2 : In the above program what will get printed after execution?  

a) There will be rain today will get printed  
b) Nothing will be printed  
c) May get printed  
d) None of the above  

**Answer** b) 

**Description**

Here print statement will not get executed, because one condition is false, that is humidity is not greater than 80. So, in this case of ‘and’ keyword both conditions must be true to execute the print statement.

---
---


```
temperature = 30
humidity = 70
if (temperature > 30 and humidity > 80):
    print ("There will be rain today")
```

3 : What is the output of the above program?  

a) There will be rain today will get printed  
b) Nothing will be printed on screen  
c) May get printed  
d) None of the above  

**Answer** b) 

**Description**

Here both conditions are false. So, print statement will not execute.  

---
---


```
temperature = 30
humidity = 80
if (temperature == 30 or humidity > 80):
    print ("There will be rain today")
```

4 : What is the output of the above program?  

a) There will be rain today will get printed   
b) Nothing will be printed   
c) May get printed   
d) None of the above  

**Answer** b) 

**Description**

Here print statement will get executed as one condition is true, that is temperature == 30. If we are using ‘or’ keyword the print statement will execute if one condition is true.

---
---


```
temperature = 30
humidity = 70
if (temperature > 30 or humidity > 80):
    print ("There will be rain today")
```

5 : What will be the output of the above lines of code?  

a) There will be rain today will get printed   
b) Nothing will be printed   
c) May get printed   
d) None of the above  

**Answer** b) 

**Description**

Here both conditions are false. temperature &gt; 30, humidity &gt; 80 both conditions evaluate to false.So, print statement will not execute.

---
---


```
temperature = 30
humidity = 90
if (temperature == 30 or humidity > 80):
    print ("There will be rain today")
```

6 : What is the output of the program?  

a) There will be rain today will get printed   
b) Nothing will be printed   
c) May get printed   
d) None of the above  

**Answer** a) 

**Description**

Here both conditions are true and so the print statement will get executed. Since it is "or" only 1 condition needs to be true. But here both conditions, temperature == 30, humidity &gt; 80 are true.  

---
---


7 : Not equal to in Python program is represented by the symbol _______

a) = =  
b) ! =   
c) < =   
d) > =  

**Answer** b) 

**Description**

In Python programming not equal to is represented by ‘ ! = ‘  

---
---


```
temperature = 30
humidity = 80
if (temperature != 25 or humidity != 70):
    print ("There will be rain today")
```

8 : What will get printed after the execution of the above program?  

a) There will be rain today will get printed  
b) Nothing will be printed  
c) May get printed   
d) None of the above  

**Answer** a) 

**Description**

Here both conditions are true, that is temperature is not equal to 25 , humidity is not equal to 70, and so the print statement will execute. Even if one condition becomes false still Line 4 gets executed. Because the keyword is "or".

---
---


```
raintoday = 1
temperature = 30
humidity = 90
if (temperature == 30 or humidity > 80 and raintoday == 1):
    print ("There will be rain today")
```

9 : What is the output of the above program?  

a) There will be rain today will get printed   
b) Nothing will be printed  
c) May get printed   
d) None of the above  

**Answer** a) 

**Description**

Here there are three conditions. raintoday is 1 and humidity greater than 80 statements are true. Then temperature = 30 is also true. So the whole will be evaluated as true and print will happen. But try to avoid using three conditions, because it will be confusing in real world programming.

---
---






