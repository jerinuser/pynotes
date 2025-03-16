---
title: Python-Docstring
date: 2025-03-16
author: Your Name
cell_count: 12
score: 10
---

```python
#  created : 20250113
```


```python
#  https://www.scientecheasy.com/2022/09/docstring-in-python.html/
```


```python
#  docstring in python 
```


```python
# Function with a Docstring.
def getSum(x, y):
    """This is a docstring

    This method takes two argument values and returns the summation of it."""
    print("Sum = ", (x + y))
getSum(20, 40) # Calling function.
print(getSum.__doc__) # Calling __doc__ method to print docstring.
```

    Sum =  60
    This is a docstring
    
        This method takes two argument values and returns the summation of it.



```python

```


```python
def info(name:str,age:int):
    """ this funtion will get the name and age of the user
    if the age is not a integer it will raise a error
    """
    if not isinstance(age,int):
        raise ValueError("age must be a integer")
    print("details = ",(name,age))

info("jerin",23)
```

    details =  ('jerin', 23)



```python
print(info.__doc__) # --> this will print only the docstring
```

     this funtion will get the name and age of the user
        if the age is not a integer it will raise a error
        



```python
def getSum(x, y):
    """This is a docstring
This method takes two argument values and returns the summation of it."""
    print("Sum = ", (x + y))
```


```python
getSum(20, 40)
print(getSum.__doc__)
```

    Sum =  60
    This is a docstring
    This method takes two argument values and returns the summation of it.



```python
def getSquare(num):
    '''This method takes a number num and returns the square of its value.'''
    return num * num
```


```python
print(getSquare.__doc__) 
sq_value = getSquare(20) 
print(sq_value)
```

    This method takes a number num and returns the square of its value.
    400



```python

```


---
**Score: 10**