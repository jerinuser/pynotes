---
title: Data3-Pandas
date: 2025-03-16
author: Your Name
cell_count: 5
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
import pandas as pd
import numpy as np
```


```python
d = {'col1': [1, 2], 'col2': [3, 4]}

df = pd.DataFrame(data=d)

#print(df)

print(df.dtypes)
```

    col1    int64
    col2    int64
    dtype: object



```python

```


---
**Score: 5**