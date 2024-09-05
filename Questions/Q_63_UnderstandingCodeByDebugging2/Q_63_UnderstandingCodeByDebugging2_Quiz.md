---
---


```
#
num = 12345

reversed_num = 0
while num != 0:
    digit = num % 10
    reversed_num = reversed_num * 10 + digit
    num = num // 10

print("The reversed number is:",reversed_num)
```

1 : In the above code what is the purpose of Line 6?  

a) To get Remainder  
b) To get sum  
c) None of the Above  
d) All of the above  

**Answer** a) 

**Description** 

Modulo operator is used to get the remainder of a division. Whenever a modulo operation of a number is done with 10, the remainder is always the last digit of that number.   

---
---


```
#
num = 12345

reversed_num = 0
while num != 0:
    digit = num % 10
    reversed_num = reversed_num * 10 + digit
    num = num // 10

print("The reversed number is:",reversed_num)
```

2 : What will be the value of ‘digit’ in first iteration?  

a) 5  
b) 1  
c) 2345  
d) None of the above  

**Answer** a) 

**Description**

Modulo operator is used to get the remainder of a division. Whenever a modulo operation of a number is done with 10, the remainder is always the last digit of that number and here it is 5.  

---
---


```

