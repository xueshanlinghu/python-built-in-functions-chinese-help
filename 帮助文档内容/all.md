**all(iterable)**
Return True if all elements of the iterable are true (or if the iterable is empty). Equivalent to:
**返回`True`如果迭代中所有的元素都是true（或者如果迭代为空）。等价于如下代码：**

```python
def all(iterable):
    for element in iterable:
        if not element:
            return False
    return True
```
