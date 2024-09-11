---
---


```
import threading

counter = 0


def incrementcounter1():
    global counter
    
    while ( counter < 1000):
        counter = counter + 1
        print(counter)
   

def incrementcounter2():
    global counter
    
    while ( counter < 1000):
        counter = counter + 1
        print(counter)
     

x = threading.Thread(target=incrementcounter1)
x.start() 

x = threading.Thread(target=incrementcounter2)
x.start()
```

1 : In the above program printing of numbers on the screen occurs _______  

a) In order from 1 to 1000   
b) In random order  
c) Any of the above   
d) No printing will happen  

**Answer** b) 

**Description**  

Here the printing will happen in a weird manner or in random order. Because when one function is printing the number, the other function which is doing the same operation (printing) takes the screen and prints. So, the printing will happen in a very weird manner, when we execute the program. Here the critical region of the code which is printing is shared between two threads.  

---
---


```
import threading

counter = 0


def incrementcounter1():
    global counter
    
    while ( counter < 1000):
        counter = counter + 1
        print(counter)
   

def incrementcounter2():
    global counter
    
    while ( counter < 1000):
        counter = counter + 1
        print(counter)
     

x = threading.Thread(target=incrementcounter1)
x.start() 

x = threading.Thread(target=incrementcounter2)
x.start()
```

2 : How can we correct the weird printing (random printing of numbers)which will happen in the above program?  

a) By using Locks in the code   
b) By using conditionals   
c) By using function objects   
d) None of the above  

**Answer** a) 

**Description**  

By using Locks in code, we can correct this.  

---
---


```
import threading

counter = 0
lock = threading.Lock()

def incrementcounter1():
    global counter
    lock.acquire()
    while ( counter < 1000):
        counter = counter + 1
        print(counter)
    lock.release()

def incrementcounter2():
    global counter
    lock.acquire()
    while ( counter < 1000):
        counter = counter + 1
        print(counter)
    lock.release() 

x = threading.Thread(target=incrementcounter1)
x.start() 

x = threading.Thread(target=incrementcounter2)
x.start()
```

3 : In the above program printing of numbers on the screen occurs _______  

a) In order from 1 to 1000   
b) In a weird manner from 1 to 1000   
c) Any of the above   
d) No printing will happen   

**Answer** a) 

**Description**

The printing of numbers on the screen occurs in an orderly manner from 1 to 1000, due to the use of lock in the program.

---
---





