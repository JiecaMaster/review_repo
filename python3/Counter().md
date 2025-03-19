
**Counter()** 是 **collections** 库中的一个函数，可以用来统计一个 python 列表、字符串、元组等可迭代对象中每个元素出现的次数，并返回一个**字典**。

## 以统计列表中的词频为例

列表中含有一串整数，要统计每个数出现的次数，可以像下面这样：

```
from collections import Counter
nums = [1, 1, 1, 6, 6, 6, 7, 8]
count = Counter(nums)
for k, v in count.items():
	print(k, v)
print(count)
"""输出：
1 3
6 3
7 1
8 1
Counter({1: 3, 6: 3, 7: 1, 8: 1})"""
```