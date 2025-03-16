---
title: Break-Statement
date: 2025-03-16
author: Your Name
cell_count: 9
score: 5
---

```python
#  created : 20250316
```


```python
#  https://www.scientecheasy.com/2022/11/break-statement-in-python.html/
```


```python
# Example Program based on Break
```


```python
# Use of break statement inside the for loop.
for x in range(1, 11):
    if x == 5:
        break # Breaking a loop.
    print("X = ",x)
```

    X =  1
    X =  2
    X =  3
    X =  4



```python
# Use of break statement inside the while loop.
i = 1
while i <= 10:
    if i == 5:
        break # Breaking a loop.
    print("I = ",i)
    i = i + 1
```

    I =  1
    I =  2
    I =  3
    I =  4



```python
for letter in 'Python':
    if letter == 't':
        break
    print('Current letter is ',letter)
```

    Current letter is  P
    Current letter is  y



```python
# Use of break inside the inner for loop.
# Outer for loop.
for x in range(1,4):
    for y in 0, 1, 2, 3: # Inner for loop.
        if(x == 2 and y == 2):
            break # Using break statement inside inner for loop.
        print(x,y)
```

    1 0
    1 1
    1 2
    1 3
    2 0
    2 1
    3 0
    3 1
    3 2
    3 3



```python
num = int(input('Enter a number: '))
num_list = [20, 40, 60, 80, 100, 120]
for n in num_list:
    if n == num:
        print('Entered number found in the list.')
        break
else:
    print('Entered number not found in the list.')
```

    Enter a number:  62


    Entered number not found in the list.



```python

```


---
**Score: 5**