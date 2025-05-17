---
title: Second-Large-Numbers
date: 2025-05-17
author: Your Name
cell_count: 4
score: 0
---

```python

```


```python
def second_largest(numbers):
    if len(numbers) < 2:
        return "Error: List must have at least two distinct numbers."

    # Remove duplicates
    unique_numbers = list(set(numbers))

    if len(unique_numbers) < 2:
        return "Error: Not enough distinct numbers to determine the second largest."

    # Sort the unique numbers in descending order
    unique_numbers.sort(reverse=True)
    
    # Return the second largest number
    return unique_numbers[1]

# Example usage
print(second_largest([5, 3, 9, 1, 3, 9]))  # Output: 5
print(second_largest([7, 7, 7]))           # Output: Error: Not enough distinct numbers to determine the second largest.
print(second_largest([10]))               # Output: Error: List must have at least two distinct numbers.

```


```python

```


```python

```


---
**Score: 0**