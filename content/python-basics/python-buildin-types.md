---
title: Python-Buildin-Types
date: 2025-01-13
author: Your Name
cell_count: 42
score: 40
---

```python
#  created : 20250113
```


```python
#  https://www.scientecheasy.com/2022/09/data-types-in-python.html/
```


```python
#  Dynamic data

#  which means we dont want to specify a data type when assigning to a variable
#  the change in the value leads to a change in data type
```


```python
my_var = "Hi Friends!" # holding string.
my_var = 25 # same variable holding numeric value.
my_var = True #holding a boolean 
```


```python
# print(my_var)
```


```python
num1 = 10 #--> string value 
percentage = 80.50 # --> floating value
```


```python
print(num1)
print(percentage)
```

    10
    80.5



```python
#  Int Data type
```


```python
num1 = 10
num2 = 20
num3 = 30
```


```python
print(num1)
print(num2)
print(num3)
```

    10
    20
    30



```python
#  Floating data type
```


```python
num1 = 10.555
num2 = 20.99
result = num1 + num2
```


```python
print(result)
```

    31.544999999999998



```python
#  Complex Data type
```


```python
num1 = 2 + 5j
num2 = 3.5 + 7.5j
result = num1 + num2
```


```python
print(result)
```

    (5.5+12.5j)



```python
#  determine the type of variable
```


```python
num1 = 50
num2 = 20.50
num3 = 3.5 + 7.5j
```


```python
print(type(num1))
print(type(num2))
print(type(num3))

```

    <class 'int'>
    <class 'float'>
    <class 'complex'>



```python
num1 = 20
num2 = 50

```


```python
del num1
print(num1) # --> iwll raise error because num1 deleted 
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    Cell In[3], line 2
          1 del num1
    ----> 2 print(num1)


    NameError: name 'num1' is not defined



```python
# Boolean Data type

```


```python
a = (10 >= 4)
b = (25 == 5 * 5)
c = (18 != 2 * 9)
```


```python
print(a, b, c)
```

    True True False



```python
# None Data type
```


```python
a = None
print(a)
print(type(a))
```

    None
    <class 'NoneType'>



```python
#  String Data type
```


```python
str1 = "Hello Jerin"
str2 = 'How are you ?'
```


```python
print(str1)
print(str2)
print(type(str1))
```

    Hello Jerin
    How are you ?
    <class 'str'>



```python
#  List Data type
```


```python
list = [10, 20.50, "Python", True]
```


```python
print(list)
print(type(list))
```

    [10, 20.5, 'Python', True]
    <class 'list'>



```python
num_list = [10, 20, 30, 40]
print(num_list)

```

    [10, 20, 30, 40]



```python
num_list[2] = 50 
print(num_list)
```

    [10, 20, 50, 40]



```python
# Tuple Data type
#
```


```python
t = (10, 20, "Python", 2 + 10j)
print(t)
print(type(t))
```

    (10, 20, 'Python', (2+10j))
    <class 'tuple'>



```python
# Set Data type
```


```python
s = {1, 2, 'Hello', 4 + 50j}
print(s)
print(type(s))
```

    {1, 'Hello', 2, (4+50j)}
    <class 'set'>



```python
# Dictionary Data type

```


```python
dict = {1 : 'Orange',
        2 : 'Apple',
        3 : 'Banana'}
```


```python
print(dict)
print(type(dict))
```

    {1: 'Orange', 2: 'Apple', 3: 'Banana'}
    <class 'dict'>



```python

```


---
**Score: 40**