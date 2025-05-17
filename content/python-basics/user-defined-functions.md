---
title: User-Defined-Functions
date: 2025-05-17
author: Your Name
cell_count: 9
score: 5
---

```python
#  created : 20250321
```


```python
#  https://www.scientecheasy.com/2022/12/user-defined-functions-in-python.html/
```


```python
# Syntax of User defined Function
```


```python
# def function_name(parameter_list): # function header
#     . . . . . .
#     body_of_the_function
#     . . . . . .
#     return <value(s)>

```


```python
# user defined function definition
def greeting():
    print('Hello world!')
    print('Welcome to the world of the programming!')
# Function calling.
greeting()

```

    Hello world!
    Welcome to the world of the programming!



```python
# Simple Python function to check even and odd.
def evenOdd(x): # function header. x is a local variable.
    if x % 2 == 0:
        print('Number',x,'is even')
    else:
        print('Number',x,'is odd')
# Calling functions by passing two argument values.
evenOdd(20)
evenOdd(25)

```

    Number 20 is even
    Number 25 is odd



```python
# Function definition having two parameters, such as name and age.
def person(name, age): # Here, name and age are local variables.
    print(name)
    print(age)
person('John', 24)

```

    John
    24



```python
# Function to find the sum of three numbers.
def sum_three_numbers(n1, n2, n3): # Here, n1, n2, n3 are local variables.
    sum = n1 + n2 + n3  # Here, sum is a local variable.
    return sum

# Calling a function by passing three argument values.
# We will store the returned value into a variable named s.
s = sum_three_numbers(20, 30, 40) # Here, s is a global variable.

# Displaying the value of s in the console.
print('Sum of three numbers = ',s)

```

    Sum of three numbers =  90



```python

```


---
**Score: 5**