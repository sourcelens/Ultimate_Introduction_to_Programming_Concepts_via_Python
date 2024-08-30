---
---


```
raintoday = 1
if (raintoday == 0):
    print ("Lets play soccer")
else:
    print ("Lets play Pingpong")
```

1 : In the above program what will be the output?  

a) Lets play soccer  
b) Lets play Pingpong  
c) Line 1  
d) None of the above  

**Answer** b) 

**Description**

It will print “Lets play Pingpong” because the if condition will evaluate as false. We assigned the value 1 to raintoday. So, if false is evaluated it will print Line 5.  

---
---


```
raintoday = 0
if (raintoday == 0):
    print ("Lets play soccer")
else:
    print ("Lets play Pingpong")
```

2 : In the above program what will be the output?  

a) Lets play soccer  
b) Lets play Pingpong  
c) Line 1  
d) None of the above  

**Answer** a) 

**Description**

It will print “Lets play soccer” because the if condition will evaluate as true. We assigned the value 0 to raintoday. So, if true is evaluated it will print Line 3.

---
---


```
raintoday = 0
indoor_badminton_court = True
tennis_court_is_booked = False
if (raintoday == 1):
    print( " Rain is there we need to play indoor games" )
    if( indoor_badminton_court == True):
        print("Lets play Badminton")
    else:
        print("Lets play Chess")
elif(tennis_court_is_booked == True):
    print("Lets play Tennis")
else:
    print("Lets go for Jogging")
```

3 : In the above program, When Line 5 to 9 will get executed?  

a) When raintoday is equal to 0  
b) When raintoday is equal to 1  
c) When raintoday is equal to 2  
d) None of the above  

**Answer** b) 

**Description**

Here Line 5 to 9 are going to execute if the condition in Line 4 is evaluated true. Otherwise, it will execute Line 10 or Line 12 based on the given condition. Either the if or else condition (line 6-9) will execute based on the condition. 

---
---


```
raintoday = 0
indoor_badminton_court = True
tennis_court_is_booked = False
if (raintoday == 1):
    print( " Rain is there we need to play indoor games" )
    if( indoor_badminton_court == True):
        print("Lets play Badminton")
    else:
        print("Lets play Chess")
elif(tennis_court_is_booked == True):
    print("Lets play Tennis")
else:
    print("Lets go for Jogging")
```

4 : In the above program when Line 13 will get execute?  

a) Line 4 and 10 becomes False  
b) Line 4 and 10 becomes True  
c) Line 4 true and Line 10 False  
d) None of the above  

**Answer** a) 

**Description**

When Line 4 and Line 10 are evaluated to false Line 13 will be executed.

---
---


```






