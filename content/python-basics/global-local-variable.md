---
title: Global-Local-Variable
date: 2025-03-16
author: Your Name
cell_count: 19
score: 15
---

```python
#  created : 20250113
```


```python
#  https://www.scientecheasy.com/2022/09/global-and-local-variables-in-python.html/
```


```python
#  Global and Local Variables
```


```python
x = 10 # --> global variable
def numm():
    print("Inside function: ",x)
    
```


```python
numm()
print("outside function: ",x)
```

    Inside function:  10
    outside function:  10



```python
x = 20 # a global variable.
def my_function():

    x = 20 * 30 # Here, interpreter will treat as a local variable.
    print("Inside function: ", x)
```


```python
my_function()
print("Outside function: ", x)
```

    Inside function:  600
    Outside function:  20



```python
name = 'John' # a global variable.
def my_function1():
    global name
    name = 'Bob' # Here, changing the value of global variable inside the

    print("Inside function: ",name)
```


```python
def my_function2():
    print("Inside another function: ",name)
```


```python
my_function1()
my_function2()
print("Outside function: ",name)
```

    Inside function:  Bob
    Inside another function:  Bob
    Outside function:  Bob



```python
city = 'New York' # a global variable.
def my_function1():
    global city # -->assigned a new value to a variable
    city = 'Dhanbad'
    print("Inside my_function1: ", city)
def my_function2():
    global city  # --> assigend a new value to a variable
    city = 'Sydney'
    print("Inside my_function2: ",city)
```


```python
my_function1()
my_function2()
print("Outside function: ", city)
```

    Inside my_function1:  Dhanbad
    Inside my_function2:  Sydney
    Outside function:  Sydney



```python
#  Local Variable
```


```python
def my_func():
    city = 'Dhanbad'
    print(city)

```


```python
my_func()
print(city)
```

    Dhanbad
    Sydney



```python
message1 = "This is a global variable, and we can access it anywhere in the program."
```


```python
def display():
# Declare a local variable and assign it a value.
    message2 = "This is a local variable, and we can access it only inside the function body."
    print(message2) # Accessing local variable from inside the function.

print(message1); # Accessing the global variable.
display() 
```

    This is a global variable, and we can access it anywhere in the program.
    This is a local variable, and we can access it only inside the function body.



```python
# Declare global variables.
student1 = "John"
student2 = "Larry"

def showMe():
    student2 = "Harry" # Here, local variable is sharing the same name as global variable.
    student3 = "Deep"
    print(student2, " ",student3)

showMe()
print(student1, " ", student2)
```

    Harry   Deep
    John   Larry



```python

```


---
**Score: 15**