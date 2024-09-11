---
---


1 : List some programming languages which doesn’t have a Package Management?  

a) C, C++   
b) Python   
c) Both of the above   
d) None of the above  

**Answer** a) 

**Description**  

During these days almost all programming languages has a package management system. Some of the oldest languages like C, C++ doesn’t have such a solid package management system.  

---
---


2 : What is meant by Package management in programming?  

a) Managing dependencies and libraries  
b) Managing hardware components  
c) Organizing the program into different names   
d) None of the above  

**Answer** a) 

**Description** 

It helps to coordinate all the available code or libraries which can upload and download within our application at a single location. In python it is called pip.  

---
---


3 : In Python, what is the name of the package manager?  

a) import   
b) PIP   
c) Install    
d) None of the above  

**Answer** b) 

**Description**

In Python, the Package manager or the framework for managing package is called PIP and the format of pip command is pip install . It downloads the package from the package manager or the remote package manager repository or from the internet. We can mention different versions in pip.  

---
---


4 : What pip install <package name> does?  

a) downloads and installs a Python package  
b) Creates a new package  
c) Overwriting bunch of files from someone else’s repository  
d) All of the above  

**Answer** a) 

**Description**

pip install  downloads and installs a Python package

---
---


5 : How to download a package named request?  

a) pip install request  
b) import request   
c) Download request   
d) All of the above  

**Answer** a) 

**Description**

pip install  this is how we download a package in python.  

---
---


```
import requests
api_url = "https://jsonplaceholder.typicode.com/todos/1"
response = requests.get(api_url)
response.json()
```

6 : What do the above lines of code does?  

a) Imports the requests library and defines a variable api_url with a URL. It then sends a POST request to the specified URL  
b) Sends a GET request to an API endpoint, retrieves the response, and parses it as JSON  
c) To install request package  
d) All of the above  

**Answer** b) 

**Description**

api_url = "https://jsonplaceholder.typicode.com/todos/1" assigns the URL of the API endpoint to the variable api_url. response = requests.get(api_url) sends a GET request to the specified api_url. response.json() method call returns the JSON data.   

---
---





