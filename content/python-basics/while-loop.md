---
title: While-Loop
date: 2025-05-17
author: Your Name
cell_count: 9
score: 5
---

```python
#  created : 20250125
```


```python
#  https://www.scientecheasy.com/2022/10/while-loop-in-python.html/
```


```python
count = 0
# Declare the while loop statement.
# Loop continuation condition expression that must ends with a colon (:).
while count < 5:
# Body of the loop.
    print('Hello Python') # This statement will execute as long as the condition is true.
    count += 1 # It counts the number of executions, and increments count by 1.
print('Loop finished.')
```

    Hello Python
    Hello Python
    Hello Python
    Hello Python
    Hello Python
    Loop finished.



```python
i = 1 # Initialization.
while i <= 5:
    print('Current value of i is ',i)
    i = i + 1
```

    Current value of i is  1
    Current value of i is  2
    Current value of i is  3
    Current value of i is  4
    Current value of i is  5



```python
i = 0 # Initialization.
name = input('Enter your name: ')
while i < 5:
    print(name)
    i = i + 1
```

    Enter your name:  2


    2
    2
    2
    2
    2



```python
i = 5 # Initialization.
while i >= 1:
    print(i)
    i = i - 1 
print('Loop finished')
```

    5
    4
    3
    2
    1
    Loop finished



```python
num = int(input('Enter a number up to which you want to calculate average: '))
i = 0
sum = 0
count = 0 # Initialization.
while i < num:
    i = i + 1 # Increment by 1.
    sum = sum + i
    count = count + 1
average = sum / count
print('Average of', num,'natural numbers = ', average)
```

    Enter a number up to which you want to calculate average:  30


    Average of 30 natural numbers =  15.5



```python
sum = 0
count = 0 # Initialization.
while count <= 10:
    sum = sum + count
    count = count + 1
print('Sum of 10 natural numbers = ', sum)
```

    Sum of 10 natural numbers =  55



```python

```


---
**Score: 5**