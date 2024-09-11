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


