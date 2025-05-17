---
title: Python-Tokens
date: 2025-05-17
author: Your Name
cell_count: 10
score: 10
---

```python
#  created : 20250113
```


```python
#  https://www.scientecheasy.com/2022/09/python-tokens.html/
```


```python
#  python tokens
```


```python
# Keywords (Reserved words) : True, False, None, class, continue, break, if, elif, else, from, or, def, del, import, etc.
# Identifier : User-defined names
# Literals : String, Numeric, Boolean, Collection,
# Delimeters : ( ), { }, [ ], :, ., =, ;, +=, -=, *=, /=, %=, etc.
# Operators : +, -, *, **, /, %, <<, >>, etc.
```


```python
x = int(input("Enter your first number = ")) # --> in this line every single word and parentheses are called as tokens
y = int(input("Enter your second number = "))
sub = x - y
print(sub)
```

    Enter your first number =  2
    Enter your second number =  3


    -1



```python
 # there is a specific library to find a tocken in python 
#  that is nltk
#  to install pip install nltk
```


```python
!pip install nltk

```

    Requirement already satisfied: nltk in /home/jerin/miniconda3/envs/py311/lib/python3.11/site-packages (3.9.1)
    Requirement already satisfied: click in /home/jerin/miniconda3/envs/py311/lib/python3.11/site-packages (from nltk) (8.1.8)
    Requirement already satisfied: joblib in /home/jerin/miniconda3/envs/py311/lib/python3.11/site-packages (from nltk) (1.4.2)
    Requirement already satisfied: regex>=2021.8.3 in /home/jerin/miniconda3/envs/py311/lib/python3.11/site-packages (from nltk) (2024.11.6)
    Requirement already satisfied: tqdm in /home/jerin/miniconda3/envs/py311/lib/python3.11/site-packages (from nltk) (4.67.1)



```python
from nltk.tokenize import word_tokenize

```


```python
text= "hi my name is jerin and my age is 23"
tokens = word_tokenize(text)
print(tokens)
```

    ['hi', 'my', 'name', 'is', 'jerin', 'and', 'my', 'age', 'is', '23']



```python

```


---
**Score: 10**