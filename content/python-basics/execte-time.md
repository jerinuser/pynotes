---
title: Execte-Time
date: 2025-01-03
author: Your Name
cell_count: 3
score: 0
---

```python
import time
```


```python
def print_even_numbers():
    start_time = time.time()
    
    for i in range(20):
        if i % 2 == 0:
            print(i, end=" ")
    
    end_time = time.time()
    time_taken = end_time - start_time
    print("\nTime:", time_taken)

# Call the function
print_even_numbers()
```

    0 2 4 6 8 10 12 14 16 18 
    Time: 0.0001862049102783203



```python

```


---
**Score: 0**