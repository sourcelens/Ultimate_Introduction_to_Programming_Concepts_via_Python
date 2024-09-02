---
---


1 : When we are assigning value to variables in our program, we are using the _______  

a) Primary memory   
b) Secondary memory   
c) Both of the above  
d) None of the above  

**Answer** a) 

**Description**

Variable assignments in our program,  are using the primary memory. It gets wiped out when the program ends or during restart.

---
---


2 : a = 10. This will go to _______  

a) Primary memory   
b) Secondary memory   
c) Both of the above  
d) None of the above  

**Answer** a) 

**Description**

Variable assignments are using the primary memory. It gets wiped out when the program ends or during restart.  

---
---


3 : When we are writing programs through files, it will get stored in the _______  

a) Disk   
b) Secondary memory   
c) Primary memory   
d) Both a) & b)  

**Answer** d) 

**Description**

When we are writing programs through files, it will get stored in the Disk or secondary memory. It does not get wiped out when program ends or system restarts. But it is slower than primary memory atleast 10 to 100 times.  

---
---


```
f = open ("test.txt", "w")
f.write ("test line 1  \n")
f.close ()
```

4 : Which is correct for the above program?  

a) Reading from a file  
b) Writing to a file   
c) Modifying a file  
d) All of the above  

**Answer** b) 

**Description**  

Here we are opening or creating a file, writing to it and closing the file. “w” stands for writing mode. This file will go to Disk or secondary storage and will not get deleted when we stop the program or during restart.

---
---


```
f = open ("test.txt", "r")
print (f.readline ())
```

5 : Which is correct for the above program?  

a) Reading from a file  
b) Writing to a file  
c) Modifying a file   
d) All of the above  

**Answer** a) 

**Description**

Here we are reading from the file, as we are giving here read mode “r”.

---
---





