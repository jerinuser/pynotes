---
title: Multible-Inheritance
date: 2025-01-03
author: Your Name
cell_count: 3
score: 0
---

```python
class Father:
    def skill(self):
        print("Driving")

class Mother:
    def skill(self):
        print("Cooking")

class Child(Father, Mother):
    pass

child = Child()
child.skill()
```

    Driving



```python
class GrandParent:
    def display(self):
        print("GrandParent Display")

class Parent(GrandParent):
    pass

class Child(Parent):
    pass

child = Child()
child.display()
```

    GrandParent Display



```python

```


---
**Score: 0**