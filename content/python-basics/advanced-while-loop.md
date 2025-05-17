---
title: Advanced-While-Loop
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
num = int(input('Enter a number: '))
sum = 0
remainder = 0
while num != 0:
    remainder = num % 10
    sum = sum + remainder
    num = int(num / 10)
print('Sum of all digits in number = ', sum)
```

    Enter a number:  5


    Sum of all digits in number =  5



```python
# Program to find the GCD of two +ve numbers.
n1 = int(input('Enter the first positive number: '))
n2 = int(input('Enter the second positive number: '))
if(n1 == 0 and n2 == 0):
    print('Invalid input')
if(n1 == 0):
    print('GCD = ',n2)
if(n2 == 0):
    print('GCD = ',n1)
while(n1 != n2):
    if(n1 > n2):
        n1 = n1 - n2
    if(n2 > n1):
        n2 = n2 - n1
print('GCD of two numbers = ',n1)
```

    Enter the first positive number:  5
    Enter the second positive number:  5


    GCD of two numbers =  5



```python
# Program to find the Fibonacci series of numbers till 30.
num1 = 0
num2 = 1
print('Fibonacci series of numbers till 30 are: ')
print(num1, num2, end = ' ')
while num2 < 21:
    num1, num2 = num2, num1 + num2
    print(num2, end = ' ')
```

    Fibonacci series of numbers till 30 are: 
    0 1 1 2 3 5 8 13 21 


```python
# Program to print pattern.
nrows = int(input('Enter the number of rows: '))
while nrows >= 0:
    x = '* ' * nrows
    print(x)
    nrows = nrows - 1
```

    Enter the number of rows:  5


    * * * * * 
    * * * * 
    * * * 
    * * 
    * 
    



```python
# Program to print pattern.
nrows = int(input('Enter the number of rows: '))
n = 1
while n <= nrows:
    x = '* ' * n
    print(x)
    n = n + 1
```

    Enter the number of rows:  5


    * 
    * * 
    * * * 
    * * * * 
    * * * * * 



```python
# Program to print table of an input number.
num = int(input('Enter a number to find table: '))
count = 1
t = 1
while count <= 10:
    t = num * count
    print(num,'*',count,'=',t)
    count = count + 1
```

    Enter a number to find table:  5


    5 * 1 = 5
    5 * 2 = 10
    5 * 3 = 15
    5 * 4 = 20
    5 * 5 = 25
    5 * 6 = 30
    5 * 7 = 35
    5 * 8 = 40
    5 * 9 = 45
    5 * 10 = 50



```python

```


---
**Score: 5**