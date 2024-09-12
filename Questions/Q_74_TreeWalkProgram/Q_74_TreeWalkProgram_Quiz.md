---
---


```
#
listtoflatten = [
    1,  2,
    [
        3,4,
        [
            5,6
        ],
        7
    ],
    [
        [
            [
                8,9
            ],
            10
        ]
    ],
    [
        11,
        [12,13]
    ]
]
```

1 : What the above lines of code shows?  

a) Nested Lists   
b) A pattern of lists   
c) A pattern of Array   
d) A pattern of Class  

**Answer** a)  

**Description**  

This is a List which has many nested lists. The elements of the first list or outer list are 1,2, [3,4[5,6],7], [[[8,9],10]] and [11,[12,13]].the number of first level inner lists are Three. 

---
---


2 : What is meant by Tree in programming? Select the most appropriate answer.

a) Node and Leaf data structure  
b) A pattern of lists   
c) A pattern of Array   
d) A pattern of Class  

**Answer** a)  

**Description** 

A tree has a Node and that node has ‘n’ number of Childs of the same type and in turn it has lot of Childs. The nodes can have leaves, leaves don’t have Childs. This type of data structure in programming is called tree.   

---
---


3 : What are the different types of trees?  

a) Binary Tree   
b) Binary Search Tree  
c) AVL Tree, RBL Tree   
d) All of the above  

**Answer** d)  

**Description**

All are different types of Tree Algorithms. Programming languages use all these algorithms behind the scenes to perform search.  

---
---


4 : What is meant by Tree traversal?  

a) Going to each node and collecting all the leaves   
b) Going to each node only   
c) Going to each leaf only   
d) None of the above  

**Answer** a)  

**Description**  

Tree traversal means going to each node and collecting all the leaves.  

---
---


5 : What is meant by a Binary Tree?  

a) Only two nodes   
b) Can have many nodes   
c) Both of the above   
d) None of the above  

**Answer** a)  

**Description**

Binary tree is a special kind of tree which has only two nodes, left and right.  

---
---


6 : In programming, What is meant by pop?  

a) Taking the first element   
b) Taking the middle element   
c) removes the element at the specified position  
d) None of the above  

**Answer** c)  

**Description**

The pop() method removes the element at the specified position.  

---
---


```
#
listtoflatten = [
    1,2,
    [
        3,4,
        [
            5,6
        ],
        7
    ],
    [
        [
            [
                8,9
            ],
            10
        ]
    ],
    [
        11,
        [12,13]
    ]
]

def flatten(input_list):
    result = []
    while input_list:
        current = input_list.pop()
        if isinstance(current,list):
            input_list.extend(current)
        else:
            result.append(current)
    result.reverse()
    return result
ans = flatten(listtoflatten)
print(ans)
```

7 : What Line 27 does in the above lines of code?  

a) Taking the first element   
b) Going to iterate through all the elements inside the input_list   
c) Taking the last element   
d) None of the above  

**Answer** b)  

**Description**

It is a syntax sugar python offers. It is going to iterate through all the elements inside the input_list until the list is empty. That means run the loop while input_list is not empty. As long as there is element in the input_list it will keep running the while loop.

---
---


```
#
listtoflatten = [
    1,2,
    [
        3,4,
        [
            5,6
        ],
        7
    ],
    [
        [
            [
                8,9
            ],
            10
        ]
    ],
    [
        11,
        [12,13]
    ]
]

def flatten(input_list):
    result = []
    while input_list:
        current = input_list.pop()
        if isinstance(current,list):
            input_list.extend(current)
        else:
            result.append(current)
    result.reverse()
    return result
ans = flatten(listtoflatten)
print(ans)
```

8 : What is the statement which is removing items from the list in the above lines of code?  

a) current = input_list.pop()  
b) result.append(current)   
c) result.reverse()   
d) None of the above  

**Answer** a)  

**Description**

In Line 28 using pop we are getting the last element. input_list.pop() returns the last element or the last object inside the list. No matter if it is a number, list or string etc.  

---
---


```
#
listtoflatten = [
    1,2,
    [
        3,4,
        [
            5,6
        ],
        7
    ],
    [
        [
            [
                8,9
            ],
            10
        ]
    ],
    [
        11,
        [12,13]
    ]
]

def flatten(input_list):
    result = []
    while input_list:
        current = input_list.pop()
        if isinstance(current,list):
            input_list.extend(current)
        else:
            result.append(current)
    result.reverse()
    return result
ans = flatten(listtoflatten)
print(ans)
```

9 : What is inside the ‘current’ variable in the above lines of code?  

a) Removed element   
b) Added element   
c) Replaced element   
d) None of the above  

**Answer** a)  

**Description**

In Line 29, inside current is the last element (of each iteration), the one which we removed from the list.  

---
---


```
#
listtoflatten = [
    1,2,
    [
        3,4,
        [
            5,6
        ],
        7
    ],
    [
        [
            [
                8,9
            ],
            10
        ]
    ],
    [
        11,
        [12,13]
    ]
]

def flatten(input_list):
    result = []
    while input_list:
        current = input_list.pop()
        if isinstance(current,list):
            input_list.extend(current)
        else:
            result.append(current)
    result.reverse()
    return result
ans = flatten(listtoflatten)
print(ans)
```

10 : What Line 33 does in the above lines of code?  

a) reverses the order of the elements in the result list  
b) Adding element to current   
c) Replace element in the result list  
d) None of the above  

**Answer** a)  

**Description**

In the given code, the result.reverse() line reverses the order of the elements in the result list.

---
---




