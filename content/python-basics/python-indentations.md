---
title: Python-Indentations
date: 2025-01-25
author: Your Name
cell_count: 25
score: 25
---

```python
#  created : 20250112
```


```python
#  https://www.scientecheasy.com/2022/09/indentation-in-python.html/
```


```python
#  Python indentations

#  in python indendation means the whitespace 
```


```python
#  after function definition we have to give four indendation
```


```python
def display():
  var = "Scientech Easy" 
  print(var)

```


```python
display()
```

    Scientech Easy



```python
def display(parameter):
    var = "Hello" 
    print(var) 
    print(var, parameter)

```


```python
display("Python")
```

    Hello
    Hello Python



```python
name = 'Ivaan'
if name == 'Ivaan':
    print('WelCome Ivaan..') 
    print('How are you, today?') 
else:
    print('Dude! whoever are you ') 
    print('Why are you here?') 
```

    WelCome Ivaan..
    How are you, today?



```python
print('I am fine, thank you!')
print('Have a nice day!')
```

    I am fine, thank you!
    Have a nice day!



```python

```


```python
def school(parameter):
  print(parameter) 

def city(parameter):
    print(parameter) 
```


```python
school("carmel school")
```

    carmel school



```python
city("chennai")
```

    chennai



```python
#  error code for indentation
```


```python
if(6 > 3):
print("6 is greater than 3")
```


      Cell In[29], line 2
        print("6 is greater than 3")
        ^
    IndentationError: expected an indented block after 'if' statement on line 1




```python
if(6 > 3):
    print("6 is greater than 3") # --> corrected code 
```

    6 is greater than 3



```python
if(6 > 3):
          print("6 is greater than 3")
```

    6 is greater than 3



```python
a = 10
b = 20
c = 30
if(b > a):
  print("b is greater than a")
    print("b is greater than a but less than c") # --> mismatch indentation
```


      Cell In[1], line 6
        print("b is greater than a but less than c")
        ^
    IndentationError: unexpected indent




```python
a = 10
b = 20
c = 30
if(b > a):
    print("b is greater than a")
    print("b is greater than a but less than c")
```

    b is greater than a
    b is greater than a but less than c



```python
def display(parameter):
    institute = "Scientech Easy"
  print(institute) # mismatch indentation
    print(parameter)
display('Dhanbad')
```


      File <tokenize>:3
        print(institute) # mismatch indentation
        ^
    IndentationError: unindent does not match any outer indentation level




```python
def display(parameter):
    institute = "Scientech Easy"
    print(institute)
    print(parameter)

```


```python
display('Dhanbad')
```

    Scientech Easy
    Dhanbad



```python

```


```python

```


---
**Score: 25**