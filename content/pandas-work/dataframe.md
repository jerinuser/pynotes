---
title: Dataframe
date: 2025-01-13
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
import pandas as pd
```


```python
continents_and_medals = {};
continent = 'asia';
```


```python
sports = {};
sports['athletics'] = 1;

continents_and_medals['asia'] = {};
continents_and_medals['asia']['fencing'] = 1;

```


```python
print(continents_and_medals[continent]['fencing']);

```

    1



```python

```


---
**Score: 5**