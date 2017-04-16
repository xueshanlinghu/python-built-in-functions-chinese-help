**any(iterable)**
Return True if any element of the iterable is true. If the iterable is empty, return False. Equivalent to:
**返回`True`如果迭代中的任意一个元素为true。如果迭代为空，返回`False`。等价于如下代码：**
```python
def any(iterable):
    for element in iterable:
        if element:
            return True
    return False
```
