---
title: Membership-Operator
date: 2025-01-25
author: Your Name
cell_count: 12
score: 10
---

```python
#  created : 20250113
```


```python
#  https://www.scientecheasy.com/2022/10/membership-operators-in-python.html/
```


```python
#  Membership In operator
# in 
# not in
```


```python
my_string = 'Every person loves his country in the world.'
print('E' in my_string)
print('country' in my_string)
print('like' in my_string)
print('lo' in my_string)
```

    True
    True
    False
    True



```python
my_list = [2, 4, 6, 8, 10, 12]
print(6 in my_list)
print(5 in my_list)
```

    True
    False



```python
my_dict = {
    1: 'Orange',
    2: 'Banana',
    3: 'Apple'
}
```


```python
print(1 in my_dict)
print(3 in my_dict)
print('Banana' in my_dict)
```

    True
    True
    False



```python
# Membership Not in operator

```


```python
my_string = 'I love Python programming'
print('love' not in my_string)
print('like' not in my_string)
print('pro' not in my_string)
```

    False
    True
    False



```python
my_list = [10, 20, 30, 40, 50]
print(15 not in my_list)
print(20 not in my_list)
```

    True
    False



```python
num1  = 10
num2 = 30
my_list = [10, 20, 40, 50, 60 ]

if(num1 in my_list):
    print(num1, 'is present in the given list.')
else:
    print(num1, 'is not present in the given list.')

if(num2 not in my_list):
    print(num2, 'is not present in the given list.')
else:
    print(num2, 'is present in the given list.')
```

    10 is present in the given list.
    30 is not present in the given list.



```python

```


---
**Score: 10**