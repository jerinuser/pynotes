---
title: Identifiers
date: 2025-03-16
author: Your Name
cell_count: 14
score: 10
---

```python
#  created : 20250112
```


```python
#  https://www.scientecheasy.com/2022/09/identifiers-in-python.html/
```


```python
#  Identifiers in Python

```


```python
class = 10
print(class)
```


      Cell In[2], line 1
        class = 10
              ^
    SyntaxError: invalid syntax




```python
class_ = "RSVM"
print(class_)
```

    RSVM



```python
#  identifiers should not include special characters 

```


```python
school@ = "RSVM"
print(school@)
```


      Cell In[5], line 1
        school@ = "RSVM"
                ^
    SyntaxError: invalid syntax




```python
#  valid class identifiers 

```


```python
class SchoolName:
    def __init__(self,name,location):
        self.name = name 
        self.location = location

    def display_info(self):
        print(f"School Name: {self.name}")
        print(f"Location : {self.location}")

        
```


```python
school = SchoolName("Jerin","Chennai")
```


```python
school.display_info()
```

    School Name: Jerin
    Location : Chennai



```python
class MyFamousCollection:
    def __init__(self):
        self.items = []
        
    def add_item(self,item):
        self.items.append(item)

    def show_collection(self):
        print("Famous Collection Item")

        for item in self.items:
            print(item)
            
```


```python
my_collection=MyFamousCollection()
my_collection.add_item("mona lisa painting")
my_collection.add_item("hi jerin")
my_collection.show_collection()
```

    Famous Collection Item
    mona lisa painting
    hi jerin



```python

```


---
**Score: 10**