---
title: Advanced-For-Loop
date: 2025-03-16
author: Your Name
cell_count: 6
score: 5
---

```python
#  created : 20250125
```


```python
#  https://www.scientecheasy.com/2022/10/for-loop-in-python.html/
```


```python
num = int(input('Enter a number: '))
even = 0
odd = 0
for x in range(num):
    if x % 2 == 0:
        even = even + x
    else:
        odd = odd + x
print('Sum of even numbers = ',even)
print('Sum of odd numbers = ',odd)

```

    Enter a number:  5


    Sum of even numbers =  6
    Sum of odd numbers =  4



```python
# Python program to find the factorial of a number.
num = int(input('Enter a number: '))
fact = 1
if num < 0:
    print('Please enter a positive number because factorial does not exist for negative number.')
elif num == 0:
    print('The factorial of 0 is 1.')
else:
    for x in range(1, num + 1):
        fact = fact * x
print('The factorial of number', num,'=', fact)
```

    Enter a number:  5


    The factorial of number 5 = 120



```python
# Python program to print a list of numbers in reverse order.
nlist = [2, 4, 6, 8, 10, 12]
print('List of original numbers: ')
for x in nlist:
    print(x, end= ' ')
num = len(nlist) # Here, function len() returns the number of items in the container.
i = 0
j = -1
print('\nList of numbers in reverse order: ')
while i <= num - 1:
    print(nlist[j], end=' ')
    j -= 1
    i += 1
```

    List of original numbers: 
    2 4 6 8 10 12 
    List of numbers in reverse order: 
    12 10 8 6 4 2 


```python

```


---
**Score: 5**