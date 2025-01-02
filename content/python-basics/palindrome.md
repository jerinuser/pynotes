---
title: Palindrome
date: 2025-01-03
author: Your Name
cell_count: 2
score: 0
---

```python
def check_palindrome(input_string):
    # Check if the string is a palindrome (ignoring case)
    is_palindrome = input_string.lower() == input_string[::-1].lower()
    
    if is_palindrome:
        return f"{input_string} is a palindrome"
    else:
        return f"{input_string} is not a palindrome"

# Test the function
input_string = "Able was I ere I saw Elba"
print(check_palindrome(input_string))

```

    Able was I ere I saw Elba is a palindrome



```python

```


---
**Score: 0**