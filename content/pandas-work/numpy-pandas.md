---
title: Numpy-Pandas
date: 2025-03-21
author: Your Name
cell_count: 7
score: 5
---

```python
import pyutil as pyu
pyu.get_local_pyinfo()
```




    'conda env: py311; pyv: 3.11.9 (main, Apr 19 2024, 16:48:06) [GCC 11.2.0]'




```python
print(pyu.ps2("pandas"))
```

    pandas==2.2.3
    



```python
import pandas as pd;
import numpy as np;
```


```python
sizes = np.full((10), 8, dtype=int);    
print(sizes);
```

    [8 8 8 8 8 8 8 8 8 8]



```python
from functools import reduce
product = reduce((lambda x, y: x * y), [1, 2, 3, 4])
```


```python
print(product)
```

    24



```python

```


---
**Score: 5**