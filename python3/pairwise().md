## 简介

最近刷力扣好几次都遇到了`pairwise`这个函数，感觉还挺方便的，今天又遇到后，搜索了一下他的含义及其用法。

总结如下。

参考网址：

[「Python」Python 标准库之 itertools 使用指南](https://blog.csdn.net/qq_43401035/article/details/119253871)

## 1. [itertools](https://so.csdn.net/so/search?q=itertools&spm=1001.2101.3001.7020).pairwise()

首先，这个函数是Python 3.10 新特性。  
它表示的是一个迭代器（有点废话，itertools里面都是各种迭代器），他的含义是，从对象中获取连续的**重叠对**。

比如说：s= ‘abcde’，itertools.pairwise(s)的输出应该为，ab, bc, cd, de;  
如果s中的个数小于2，输出为空。

示例程序：

```
from itertools import pairwise
a = pairwise('12345') 
# 输出的a应为是 12 23 34 45

b = pairwise([1])
# b为空
```

## 2. 替换itertools.pairwise()函数

如上所述，这个函数在python3.10后才有，之前的版本中并不能使用。  
那么如果要在程序中实现这个功能，其实也很简单，一次for循环即可。

```
s = '12345'
for i in range(1,len(s)):
	k1, k2 = s[i-1], s[i] # k1,k2输出应该为1,2;2,3...
```

与迭代器pairwise相比，这个的麻烦地方在于，不能使用迭代器对`重叠对`进行比较，程序效率较慢一点。

实际上也有一些其他的pairwise函数的实例，比如：[python实现pariwise](http://t.zoukankan.com/kuzaman-p-7202146.html)。该链接中有完整的[python程序](https://so.csdn.net/so/search?q=python%E7%A8%8B%E5%BA%8F&spm=1001.2101.3001.7020)。

对象纬度较高，且不能用python3.10的情形下，可以使用该方法。
