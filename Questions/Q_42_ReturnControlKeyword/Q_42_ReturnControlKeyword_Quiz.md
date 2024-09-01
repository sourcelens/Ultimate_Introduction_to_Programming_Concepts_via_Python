---
---


1 : Which keyword in Python stops the execution of an entire function?  

a) break   
b) continue   
c) return   
d) All of the above  

**Answer** c) 

**Description**

The return statement will stop the execution of the entire function. If it is inside a loop, it will terminate both the loop and the function.

---
---


2 : _______ can take a value and return back to the caller of that function.  

a) break   
b) continue   
c) return   
d) All of the above  

**Answer** c) 

**Description**

return can take a value and return back to the caller of that function.  

---
---


```
def function1():
    print("inside function1")
    return
    print("Done with function1")
function1()
```

3 : In the above program will Line 4 get printed or not?  

a) Will get printed   
b) Will not get printed   
c) May get printed   
d) None of the above  

**Answer** b) 

**Description**

Here Line 4 will not get printed because we have given return in Line 3. So, it will return the function to the caller and not execute Line 4. return will end the execution of a function irrespective of which is the line above or below. 

---
---


