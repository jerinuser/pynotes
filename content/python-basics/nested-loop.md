---
title: Nested-Loop
date: 2025-05-17
author: Your Name
cell_count: 17
score: 15
---

```python
#  created : 20250125
```


```python
#  https://www.scientecheasy.com/2022/11/nested-loops-in-python.html/
```


```python

```


```python
# Outer for loop.
for x in 1, 2:
    print('Value of x = ',x) # It will execute two times.
  # Inner for loop.
    for y in 1, 2:
        print('Value of y = ',y) # It will execute four times.
print('Nested loops ends here...')
```

    Value of x =  1
    Value of y =  1
    Value of y =  2
    Value of x =  2
    Value of y =  1
    Value of y =  2
    Nested loops ends here...



```python
# Nested While loops in Python

```


```python
x = 1 # Initialization for outer while loop.
y = 1 # Intialization for the inner while loop.
# Outer while loop.
while x < 3:
    print('Outer while loop') # This statement will execute two times.
  # Inner while loop.
    while y < 3:
        print('Inner while loop') # This statement will execute two times for the first outer loop.
        y = y + 1
    x = x + 1
print('Nested while loops end here...')
```

    Outer while loop
    Inner while loop
    Inner while loop
    Outer while loop
    Nested while loops end here...



```python
# Outer for loop.
print('Math table of 2: ')
for x in range(2, 3): # This loop will only repeat 1 time.
    for y in range(1, 11): # Inner for loop will repeat 10 times.
        t = x * y
        print(x,'*',y,'=',t)
    print()
print('Nested for loops ends here...')
```

    Math table of 2: 
    2 * 1 = 2
    2 * 2 = 4
    2 * 3 = 6
    2 * 4 = 8
    2 * 5 = 10
    2 * 6 = 12
    2 * 7 = 14
    2 * 8 = 16
    2 * 9 = 18
    2 * 10 = 20
    
    Nested for loops ends here...



```python
x = 1
while x <= 5: # Outer while loop.
    t, y = 1, 1
    print()
    print('Math table for',x,':')
    while y <= 10: # Inner while loop.
        t = x * y
        print(x,'*',y,'=',t)
        y = y + 1
    x = x + 1
print('Nested while loops ends here...')
```

    
    Math table for 1 :
    1 * 1 = 1
    1 * 2 = 2
    1 * 3 = 3
    1 * 4 = 4
    1 * 5 = 5
    1 * 6 = 6
    1 * 7 = 7
    1 * 8 = 8
    1 * 9 = 9
    1 * 10 = 10
    
    Math table for 2 :
    2 * 1 = 2
    2 * 2 = 4
    2 * 3 = 6
    2 * 4 = 8
    2 * 5 = 10
    2 * 6 = 12
    2 * 7 = 14
    2 * 8 = 16
    2 * 9 = 18
    2 * 10 = 20
    
    Math table for 3 :
    3 * 1 = 3
    3 * 2 = 6
    3 * 3 = 9
    3 * 4 = 12
    3 * 5 = 15
    3 * 6 = 18
    3 * 7 = 21
    3 * 8 = 24
    3 * 9 = 27
    3 * 10 = 30
    
    Math table for 4 :
    4 * 1 = 4
    4 * 2 = 8
    4 * 3 = 12
    4 * 4 = 16
    4 * 5 = 20
    4 * 6 = 24
    4 * 7 = 28
    4 * 8 = 32
    4 * 9 = 36
    4 * 10 = 40
    
    Math table for 5 :
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
    Nested while loops ends here...



```python
# Outer for loop.
print('Multiplication tables from 1 to 5: ')
for x in range(1, 6):
    for y in range(1, 11): # Inner for loop.
        t = x * y
        print(t, end=' ')
    print()
print('Nested for loops ends here...')
```

    Multiplication tables from 1 to 5: 
    1 2 3 4 5 6 7 8 9 10 
    2 4 6 8 10 12 14 16 18 20 
    3 6 9 12 15 18 21 24 27 30 
    4 8 12 16 20 24 28 32 36 40 
    5 10 15 20 25 30 35 40 45 50 
    Nested for loops ends here...



```python
# Outer for loop.
print('Displaying a triangle of *: ')
for x in range(1, 6):
    for y in range(1, x + 1): # Inner for loop.
        print('* ',end='')
    print()
print('Loops end here...')
```

    Displaying a triangle of *: 
    * 
    * * 
    * * * 
    * * * * 
    * * * * * 
    Loops end here...



```python
# Outer for loop.
print('Displaying a triangle of numbers: ')
for x in range(1, 6):
    for y in range(1, x + 1): # Inner for loop.
        print(y,' ',end='')
    print()
print('Loops end here...')
```

    Displaying a triangle of numbers: 
    1  
    1  2  
    1  2  3  
    1  2  3  4  
    1  2  3  4  5  
    Loops end here...



```python
print('Displaying a right triangle pattern of numbers: ')
z = 1
for x in range(1, 6):
    for y in range(1, x + 1): # Inner for loop.
        print(z,' ',end='')
    z += 1
    print()
print('Loops end here...')
```

    Displaying a right triangle pattern of numbers: 
    1  
    2  2  
    3  3  3  
    4  4  4  4  
    5  5  5  5  5  
    Loops end here...



```python
# Outer for loop.
for x in range(6, 1, -1):
    for y in range(1, x): # Inner for loop.
        print(y,' ',end='')
    print()
print('Loops end here...')
```

    1  2  3  4  5  
    1  2  3  4  
    1  2  3  
    1  2  
    1  
    Loops end here...



```python
print("Displaying a right triangle of characters ")
# Outer for loop.
for x in range(65, 70):
    for y in range(65, x + 1): # Inner for loop.
        print(chr(y),' ',end='')
    print()
print('Loops end here...')
```

    Displaying a right triangle of characters 
    A  
    A  B  
    A  B  C  
    A  B  C  D  
    A  B  C  D  E  
    Loops end here...



```python
print("Displaying a reverse right triangle of characters ")
# Outer for loop.
for x in range(70, 65, -1):
    for y in range(65, x): # Inner for loop.
        print(chr(y),' ',end='')
    print()
print('Loops end here...')
```

    Displaying a reverse right triangle of characters 
    A  B  C  D  E  
    A  B  C  D  
    A  B  C  
    A  B  
    A  
    Loops end here...



```python
# Python program to find the sum of series.
import math # Using this module, we will call pow() function.
x = int(input('Enter the value of x: '))
n = int(input('Enter the value of n: '))
S = 1.0 + x
term = 1
count = 1
while count <= n: # Outer while loop.
    power = math.pow(x, count)
    fact = 1
    for i in range(1, count + 1): # Inner for loop.
        fact = fact * 1
    S = S + (power/count)
    count = count + 1
print('Sum of the series = %.2f'%S)
```

    Enter the value of x:  5
    Enter the value of n:  6


    Sum of the series = 3450.58



```python

```


---
**Score: 15**