---
---


```
def vowel_count(input_str):
    count = 0
    vowels = "aeiouAEIOU"
    for character in input_str:
        if character in vowels:
            count = count + 1
    print("count=",count)

str = "Sourcelens is a Training and Consulting Company"
vowel_count(str)
```

1 : The above program is for ______  

a) Printing the vowels in a string   
b) Calculating the number of vowels in a string   
c) Printing the string  
d) None of the above  

**Answer** b) 

**Description**  

This program is for calculating the number of vowels in a string. We are iterating through each character in the string (Line 4) and checking whether it is in the vowels (Line 5). If it is in the vowels string, we are incrementing the count by 1 (Line 6) and finally printing the count in Line 7.   

---
---


```
def vowel_count(input_str):
    count = 0
    vowels = "aeiouAEIOU"
    for character in input_str:
        if character in vowels:
            count = count + 1
    print("count=",count)

str = "Sourcelens is a Training and Consulting Company"
vowel_count(str)
```

2 : In the above program the function definition starts in _______  

a) Line 1   
b) Line 10   
c) Line 9   
d) Line 4  

**Answer** a) 

**Description**  

Here the function definition starts in Line 1 with def keyword.

---
---


```
def vowel_count(input_str):
    count = 0
    vowels = "aeiouAEIOU"
    for character in input_str:
        if character in vowels:
            count = count + 1
    print("count=",count)

str = "Sourcelens is a Training and Consulting Company"
vowel_count(str)
```

3 : In the above program where we are calling the function?  

a) Line 1   
b) Line 10   
c) Line 9   
d) Line 4  

**Answer** b) 

**Description**

Here we are calling the function in Line 10 as vowel_count (str) and passing the string.  

---
---


```
def vowel_count(input_str):
    count = 0
    vowels = "aeiouAEIOU"
    for character in input_str:
        if character in vowels:
            count = count + 1
    print("count=",count)

str = "Sourcelens is a Training and Consulting Company"
vowel_count(str)
```

4 : In the above program, what action are we taking when a character from the input string (input_str) is found in the string of vowels (vowels)?  

a) Incrementing count by 1   
b) Printing count   
c) Printing the character   
d) None of the above  

**Answer** a) 

**Description**

If the character is there in the vowels, we are incrementing the count by 1, that is in Line 6 count = count + 1.

---
---


```
def vowel_count(input_str):
    count = 0
    vowels = "aeiouAEIOU"
    for character in input_str:
        if character in vowels:
            count = count + 1
    print("count=",count)

str = "Sourcelens is a Training and Consulting Company"
vowel_count(str)
```

5 : What does the function vowel_count( ) do in the above lines of code?  

a) Incrementing count by 1  
b) Printing count which is the number of vowels in the string  
c) Printing all the characters  
d) None of the above  

**Answer** b) 

**Description**

The function vowel_count iterates through each character in input_str (str). It checks if each character is present in the vowels string ("aeiouAEIOU"). Each time a vowel is found, the count variable is incremented by 1. Finally, it prints the total count of vowels found in the string str.  

---
---


```
def vowel_count(input_str):
    count = 0
    vowels = "aeiouAEIOU"
    for character in input_str:
        for vowel in vowels:
            if character == vowel:
                count = count + 1  
                break
    print("count =",count)
    
str = "Sourcelens is a Training and Consulting Company"
vowel_count(str)
```

6 : In the above program the for loop in Line 5 is a _______  

a) Normal for loop   
b) Nested for loop   
c) Both of the above  
d) None of the above  

**Answer** b) 

**Description**

It is a nested for loop because it is again inside a for loop.  

---
---





