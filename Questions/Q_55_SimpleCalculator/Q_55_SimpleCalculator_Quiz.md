---
---


```
#
def add(x,y):
    print(x+y)

def subtract(x,y):
    print(x-y)

def multiply(x,y):
    print(x*y)

def divide(x,y):
    print(x/y)

print("Enter two elements")
n1 = input()
n2 = input()
```

1 : In the above program what is the meaning of n1=input() and n2=input()?  

a) Taking input from the user  
b) Static input  
c) Printing the value  
d) None of the above  

**Answer** a) 

**Description**

input () function will take the input from the keyboard of the user of the program. Here we are taking two inputs n1 and n2.  

---
---


```
#
def add(x,y):
    print(x+y)

def subtract(x,y):
    print(x-y)

def multiply(x,y):
    print(x*y)

def divide(x,y):
    print(x/y)

print("Enter two elements")
n1 = input()
n2 = input()

print("Enter the operation +,-,*,/")
op = input()

if op == '+':
    add( int(n1) , int(n2) )
elif op == '-':
    subtract( int(n1) , int(n2) )
elif op == '*':
    multiply( int(n1) , int(n2) )
elif op == '/':
    divide( int(n1) , int(n2) )
else:
    print("Unsupported Operation")
```

2 : In the above program what is the purpose of line number 19?  

a) Operation selection (takes input from user)  
b) Addition only  
c) Stopping the program  
d) None of the above  

**Answer** a) 

**Description**

Deciding which operation is to perform using the input values. Here the operations are +,-,*,/.

---
---


```
#
def add(x,y):
    print(x+y)

def subtract(x,y):
    print(x-y)

def multiply(x,y):
    print(x*y)

def divide(x,y):
    print(x/y)

print("Enter two elements")
n1 = input()
n2 = input()

print("Enter the operation +,-,*,/")
op = input()

if op == '+':
    add( int(n1) , int(n2) )
elif op == '-':
    subtract( int(n1) , int(n2) )
elif op == '*':
    multiply( int(n1) , int(n2) )
elif op == '/':
    divide( int(n1) , int(n2) )
else:
    print("Unsupported Operation")
```

3 : Which are the two operands in this program?  

a) n1, n2  
b) n1, 0  
c) n2, 0  
d) None of the above  

**Answer** a) 

**Description**

In this program n1 and n2 are the two operands and op is the operation we are going to perform.  

---
---


```
#
def add(x,y):
    print(x+y)

def subtract(x,y):
    print(x-y)

def multiply(x,y):
    print(x*y)

def divide(x,y):
    print(x/y)

print("Enter two elements")
n1 = input()
n2 = input()

print("Enter the operation +,-,*,/")
op = input()

if op == '+':
    add( int(n1) , int(n2) )
elif op == '-':
    subtract( int(n1) , int(n2) )
elif op == '*':
    multiply( int(n1) , int(n2) )
elif op == '/':
    divide( int(n1) , int(n2) )
else:
    print("Unsupported Operation")
```

4 : In the above program what are we doing in line number 22?  

a) Addition  
b) Subtraction  
c) Multiplication  
d) Division  

**Answer** a) 

**Description**

Here the operation is + we are going to perform addition. So, we are calling the add function.  

---
---


```
#
def add(x,y):
    print(x+y)

def subtract(x,y):
    print(x-y)

def multiply(x,y):
    print(x*y)

def divide(x,y):
    print(x/y)

print("Enter two elements")
n1 = input()
n2 = input()

print("Enter the operation +,-,*,/")
op = input()

if op == '+':
    add( int(n1) , int(n2) )
elif op == '-':
    subtract( int(n1) , int(n2) )
elif op == '*':
    multiply( int(n1) , int(n2) )
elif op == '/':
    divide( int(n1) , int(n2) )
else:
    print("Unsupported Operation")
```

5 : In the above program what are we doing by int(n1) and int(n2)?  

a) String to number conversion  
b) Number to string conversion  
c) Concatenation  
d) None of the above  

**Answer** a) 

**Description**

int() function does some kind of type conversion or Parsing. Here n1 and n2 are strings. So, the int() function parse that strings and convert into corresponding numbers.

---
---


```
#
def add(x,y):
    print(x+y)

def subtract(x,y):
    print(x-y)

def multiply(x,y):
    print(x*y)

def divide(x,y):
    print(x/y)

print("Enter two elements")
n1 = input()
n2 = input()

print("Enter the operation +,-,*,/")
op = input()

if op == '+':
    add( int(n1) , int(n2) )
elif op == '-':
    subtract( int(n1) , int(n2) )
elif op == '*':
    multiply( int(n1) , int(n2) )
elif op == '/':
    divide( int(n1) , int(n2) )
else:
    print("Unsupported Operation")
```

6 : What will be the output of the above program if the inputs are 3 and 4 and the operation performed is ‘+’?  

a) 7  
b) 34  
c) 0  
d) None of the above  

**Answer** a) 

**Description**

Here n1=3 and n2=4 which we are taking as inputs. Operation is addition. These inputs are strings but the int() function converts string 3 and 4 into numbers. So we will get 7 as the output.  

---
---


```
#
def add(x,y):
    print(x+y)

def subtract(x,y):
    print(x-y)

def multiply(x,y):
    print(x*y)

def divide(x,y):
    print(x/y)

print("Enter two elements")
n1 = input()
n2 = input()

print("Enter the operation +,-,*,/")
op = input()

if op == '+':
    add( (n1) , (n2) )
elif op == '-':
    subtract( int(n1) , int(n2) )
elif op == '*':
    multiply( int(n1) , int(n2) )
elif op == '/':
    divide( int(n1) , int(n2) )
else:
    print("Unsupported Operation")
```

7 : What will be the output of the above program if the inputs are 3 and 4 and operation done is ‘+’ ?  

a) 34  
b) 7  
c) 0  
d) None of the above   

**Answer** a) 

**Description**

Here the inputs 3,4 are strings and it is not converted to integers. String Concatenation takes place. So, the answer becomes 34.  

---
---


```
#
def add(x,y):
    print(x+y)

def subtract(x,y):
    print(x-y)

def multiply(x,y):
    print(x*y)

def divide(x,y):
    print(x/y)

print("Enter two elements")
n1 = input()
n2 = input()

print("Enter the operation +,-,*,/")
op = input()

if op == '+':
    add( int(n1) , int(n2) )
elif op == '-':
    subtract( int(n1) , int(n2) )
elif op == '*':
    multiply( int(n1) , int(n2) )
elif op == '/':
    divide( int(n1) , int(n2) )
else:
    print("Unsupported Operation")
```

8 : What will be the output of the program if the inputs are i, 4 and the operation is addition?  

a) Invalid literal for int()  
b) i4  
c) 4i  
d) 0  

**Answer** a) 

**Description**

We will get an unhandled exception. The program is technically crashed. We need exception handling techniques to solve this.   

---
---





