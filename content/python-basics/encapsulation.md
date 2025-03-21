---
title: Encapsulation
date: 2025-03-21
author: Your Name
cell_count: 2
score: 0
---

```python
class BankAccount:
    def __init__(self, balance):
        self.__balance = balance  # Private attribute

    def deposit(self, amount):
        self.__balance += amount

    def withdraw(self, amount):
        if amount > self.__balance:
            print("Insufficient funds")
        else:
            self.__balance -= amount

    def get_balance(self):
        return self.__balance

account = BankAccount(100)
account.deposit(50)
account.withdraw(330)
print(f"your available balance is: {account.get_balance()}")
```

    Insufficient funds
    your available balance is: 150



```python

```


---
**Score: 0**