---
title: Logical-Operators-In-If-Statements
date: 2025-03-21
author: Your Name
cell_count: 11
score: 10
---

```python
#  created : 20250125
```


```python
#  https://www.scientecheasy.com/2022/10/if-statement-in-python.html/
```


```python
def logical():
    x, y, z = 20, 40, 50
    if((y > x) and (y < z)): # True 
         print("y is greater than x but smaller than z") 
    if((x > y) and (y < z)): # False
         print("z is greater than x, y")
    if(y % x == 0 and x != 0): # True
         print("y is divisible by x")
```


```python
logical()
```

    y is greater than x but smaller than z
    y is divisible by x



```python
def logical1():
    x, y, z = 2, 1, 4
    if(value := x > y or y < z): 
        print(value) 
    if(value := x > y or y > z):
        print(value)
    
    if(value := x < y or y < z):
        print(value)
    if(value := x < y or y > z):
        print(value)
```


```python
logical1()
```

    True
    True
    True



```python
def logical2():
    age = 25
    income =int(input("enter your amount: "))

    if age > 18 and income > 30000:
        print("Eligible for a credit card")
    else:
        print("Not eligible")
```


```python
logical2()
```

    enter your amount:  40000


    Eligible for a credit card



```python
def logical3():
    age = int(input("enter your age:"))
    has_membership = True
    is_guest = False
    
    if (age > 18 and has_membership) or (age > 18 and is_guest):
        print("Access granted")
    else:
        print("Access denied")
```


```python
logical3()
```

    enter your age: 23


    Access granted



```python

```


---
**Score: 10**