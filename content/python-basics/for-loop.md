---
title: For-Loop
date: 2025-03-21
author: Your Name
cell_count: 16
score: 15
---

```python
#  created : 20250125
```


```python
#  https://www.scientecheasy.com/2022/10/for-loop-in-python.html/
```


```python
for count in range(0, 5):
    print('You are the high scorer!')
```

    You are the high scorer!
    You are the high scorer!
    You are the high scorer!
    You are the high scorer!
    You are the high scorer!



```python
# Program to print the sequence.
for count in 1, 2, 3, 4:
    print('count = ',count)
```

    count =  1
    count =  2
    count =  3
    count =  4



```python
# For Loop with range() Function in Python

```


```python
print('Only stop argument values specified in the range function: ')
for x in range(3):
    print(x)
print('Start and stop argument values specified in the range function: ')
for x in range(2, 5):
    print(x)
print('Start, stop, and step argument values specified in the range function: ')
for x in range(1, 9, 3):
    print(x)
```

    Only stop argument values specified in the range function: 
    0
    1
    2
    Start and stop argument values specified in the range function: 
    2
    3
    4
    Start, stop, and step argument values specified in the range function: 
    1
    4
    7



```python
sum = 0
for num in range(1, 11):
    sum = sum + num
print('Sum of numbers between 1 to 10 = ',sum)
```

    Sum of numbers between 1 to 10 =  55



```python
# For loop with String in Python

```


```python
for ch in 'Python':
    print('Current character is ',ch)

```

    Current character is  P
    Current character is  y
    Current character is  t
    Current character is  h
    Current character is  o
    Current character is  n



```python
# For loop with List in Python

```


```python
fruits = ['Apple', 'Banana', 'Orange', 'Mango']
for item in fruits:
    print(item)
print('Loop finished...')
```

    Apple
    Banana
    Orange
    Mango
    Loop finished...



```python
# For loop with a Tuple

```


```python
color = ('Red', 'Green', 'Blue', 'Orange')
for item in color:
    print(item)
print('Loop finished...')
```

    Red
    Green
    Blue
    Orange
    Loop finished...



```python
# Else Statement with For loop in Python

```


```python
num = [3, 5, 7, 9, 11]
for n in num:
    if n % 2 == 0:
        print('List contains an even number.')
else:
    print('List does not contain any even number.')

```

    List does not contain any even number.



```python

```


---
**Score: 15**