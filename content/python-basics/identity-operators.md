---
title: Identity-Operators
date: 2025-01-25
author: Your Name
cell_count: 28
score: 25
---

```python
#  created : 20250113
```


```python
#  https://www.scientecheasy.com/2022/10/identity-operators-in-python.html/
```


```python
#  Identity Is operator (is)
```


```python
x = 20
y = 20
result = x is y
```


```python
print(result)
```

    True



```python
str1 = "Python"
str2 = "Python"
result = str1 is str2
```


```python
print(result)
```

    True



```python
name1 = "John"
name2 = "Jack"
result = name1 is name2
```


```python
print(result)
```

    False



```python
a = True
b = 1
result = a is b

```


```python
print(result)
```

    False



```python
p = "20"
q = 20
result = p is q
```


```python
print(result)
```

    False



```python
list1 = [10, 20.5, 30, 'text']
list2 = [10, 20.5, 30, 'text']
result = list1 is list2
```


```python
print(result)

```

    False



```python
dict1 = {
    'name': 'Jack',
    'age': 22,
}
dict2 = {
    'name': 'Jack',
    'age': 22,
}
result = dict1 is dict2
```


```python
print(result)

```

    False



```python
tuple1 = (1, 2.5, 3, 'Technology')
tuple2 = (1, 2.5, 3, 'Technology')
result = tuple1 is tuple2
```


```python
print(result)
```

    False



```python
# Identity Is not operator (is not)
```


```python
num1 = 30
num2 = 40
print(num1 is not num2)
```

    True



```python
num2 = 30
print(num1 is not num2)
```

    False



```python
str1 = 'Python'
str2 = 'Language'
print(str1 is not str2)
```

    True



```python
list1 = [2, 4, 6, 8, 10]
list2 = [12, 14, 16]
print(list1 is not list2)
```

    True



```python
num1 = 20
num2 = 20

print("num1 = ", num1, " ", "id(num1): ", id(num1))
print("num2 = ", num2, " ", "id(num2): ", id(num2))
```

    num1 =  20   id(num1):  8910408
    num2 =  20   id(num2):  8910408



```python
if(num1 is num2):
    print('num1 and num2 have the same identity')
else:
    print('num1 and num2 do not have the same identity')

if(id(num1) == id(num2)):
    print('num1 and num2 have the same identity')
else:
    print('num1 and num2 do not have the same identity')

```

    num1 and num2 have the same identity
    num1 and num2 have the same identity



```python
num2 = 40
print("num1 = ", num1, " ", "id(num1): ", id(num1))
print("num2 = ", num2, " ", "id(num2): ", id(num2))

if(num1 is not num2):
    print('num1 and num2 do not have the same identity')
else:
    print('num1 and num2 have the same identity')
```

    num1 =  20   id(num1):  8910408
    num2 =  40   id(num2):  8911048
    num1 and num2 do not have the same identity



```python

```


---
**Score: 25**