
字典是一种可变容器模型，且可存储任意类型对象，

字典的每个键值对(key=>value)都是用冒号：分割，每个键值对之间用逗号，分割，整个字典包括在花括号{}中，格式如下：

```
my_dict = {key1:value1, key2:value2}
```

键一般是唯一的，如果重复最后的一个键值对会替换前面的，值不需要唯一。

![](https://i-blog.csdnimg.cn/blog_migrate/aa37c5ac2a8b81cf0db47ccb1708ca53.png)

值可以取任何数据类型，但键必须是不可变的，如字符串、数字或元组。(!!! 列表是不可以的，要转化成元组)

一个简单的字典实例：

```
dict = {'Alice':'2341', 'Beth':'9102', 'Cecil':3258}
```

也可以用下面的方法创建字典：

```
dict1 = {'abc':456}dict2 = {'abc':123, 98.6:37}
```

### 访问字典里的值

把相应的键放入熟悉的方括号，如下实例：

![](https://i-blog.csdnimg.cn/blog_migrate/0476778cd71a0245c05015c3341801d1.png)

如果用字典里没有的键访问数据，会输出错误如下：

![](https://i-blog.csdnimg.cn/blog_migrate/bd2ac0a76f7cfc4ee7a9088400b618a5.png)

### 修改字典

向字典添加新内容的方法是增加新的键/值对，修改或删除已有键/值对如下实例：

![](https://i-blog.csdnimg.cn/blog_migrate/fd627b369bc1bf0611d3cb4f201c90e6.png)

删除字典元素

能删除单一的元素也能清空字典，清空只需一项操作。

显示删除一个字典用del命令，如下实例：

![](https://i-blog.csdnimg.cn/blog_migrate/93156bca7250d9cc1a28e79b427b3deb.png)

清空字典只是晴空字典的所有内容，但字典还存在

del 字典  则是将字典全部删除，包括形式及内容

### 字典键的特性

字典值可以没有限制地取任何Python对象，既可以是标准的对象，也可以是用户定义的，但键不行。

两个重要的点要记住：

1）不允许同一个键出现两次。创建时如果同一个键被两次赋值，后一个值会被记住，前一个会被覆盖，如下示例：

![](https://i-blog.csdnimg.cn/blog_migrate/eaa3caf7a6320d442161631ea2676581.png)

2）键必须不可变，所以可以用数字、字符串或者元组充当，用列表就不可以，如下实例：

![](https://i-blog.csdnimg.cn/blog_migrate/756b003905318ad8da1f5746ce61e520.png)

### 字典内置的函数&方法

Python字典包含了以下内置函数：

|   |   |
|---|---|
|序号|函数及描述|
|1|cmp(dict1, dict2)<br><br>比较两个字典元素|
|2|len(dict)<br><br>计算字典元素个数，即键的总数|
|3|str(dict)<br><br>输出字典可打印的字符串表示|
|4|type(variable)<br><br>返回输入的变量类型，如果变量是字典就返回字典类型|

![](https://i-blog.csdnimg.cn/blog_migrate/05f41d1d1537848bd160bcc526a26318.png)

Python字典包含了以下内置方法：

|     |                                                                                  |
| --- | -------------------------------------------------------------------------------- |
| 序号  | 函数及描述                                                                            |
| 1   | dict.clear()<br><br>删除字典内所有元素                                                    |
| 2   | dict.copy()<br><br>返回一个字典的浅复制                                                    |
| 3   | dict.fromkeys(seq[val1,val2])<br><br>创建一个新字典，以序列seq中元素作为字典的键，val为字典所有键对应的初始值     |
| 4   | dict.get(key, default = None)<br><br>返回指定键的值，如果值不在字典中返回default值                  |
| 5   | dict.has_key(key)<br><br>如果键在字典dict中返回true，否则返回false                             |
| 6   | dict.items()<br><br>以列表返回可遍历的（键，值）元组数组 （常在循环里出现）                                 |
| 7   | dict.keys()<br><br>以列表返回一个字典所有的键                                                 |
| 8   | dict.setdefault(key, default=None)<br><br>和get()类似，但如果键不存在于字典中，将会添加键并将值设为default |
| 9   | dict.update(dict2)<br><br>把字典dict2的键/值对更新到dict里                                  |
| 10  | dict.values()<br><br>以列表返回字典中的所有值                                                |
| 11  | pop(key[,default])<br><br>删除字典给定键key所对应的值，返回值为被删除的值。key值必须给出。否则，返回default值       |
| 12  | popitem()<br><br>随机返回并删除字典中的一对键和值                                                |

![](https://i-blog.csdnimg.cn/blog_migrate/864dd0243c9b5569efde10c4252aecb5.png)

![](https://i-blog.csdnimg.cn/blog_migrate/ace1006865e5a30c95d36b5581cafe74.png)

![](https://i-blog.csdnimg.cn/blog_migrate/9c0f81cec4eb22f48c17e4250848007d.png)

![](https://i-blog.csdnimg.cn/blog_migrate/6c07b1fb339e247c35576e0f3ffd53da.png)

![](https://i-blog.csdnimg.cn/blog_migrate/f64be87b119974bc08fde82c787e4f84.png)


## 进阶——defaultdict
defaultdict是 Python 标准库collections模块中的一个类。它是内置字典dict类型的一个子类，这意味着它继承了dict的大部分基本属性和方法，同时又添加了一些特殊的功能。

1.联系：

- 数据结构本质：defaultdict和普通dict都是 Python 中的容器类型，用于存储键 - 值（key - value）对。它们的主要目的是提供一种通过键来快速访问值的方式，从数据存储和访问的基本功能角度来看，它们是相似的。
    
- 基本操作相同点：两者都支持许多相同的操作，如通过键获取值（dictionary[key]）、添加或更新键 - 值对（dictionary[key] = value）、检查键是否存在（key in dictionary）、删除键 - 值对（del dictionary[key]）等操作。例如，以下代码在dict和defaultdict中都能正常工作：
    
    ```
    my_dict = {}
    my_dict["key1"] = "value1"
    print("key1" in my_dict)
    del my_dict["key1"]
    ```
    
    ```
    from collections import defaultdict
    my_defaultdict = defaultdict(int)
    my_defaultdict["key2"] = "value2"
    print("key2" in my_defaultdict)
    del my_defaultdict["key2"]
    ```
    

2.区别：

- 键不存在时的行为
    
    - 普通dict：当使用普通dict访问一个不存在的键时，会抛出KeyError异常。例如：
        
        ```
        my_dict = {} 
        try:
            print(my_dict["nonexistent_key"])
        except KeyError as e:
            print("KeyError:", e)
        ```
        
    - defaultdict：defaultdict在访问不存在的键时，会根据其默认工厂函 数（default factory function）来自动生成一个默认值作为该键对应的值，而不会抛出KeyError异常。例如，defaultdict(int)会在访问不存在的键时返回整数 0 作为默认值：  
        收起
        
        ```
        from collections import defaultdict
        my_defaultdict = defaultdict(int)
        print(my_defaultdict["nonexistent_key"])		
        ```
        
- 初始化方式和默认值设置
    
    - 普通dict：普通dict可以通过多种方式初始化，如{}、dict()或者使用键 - 值对的序列来初始化（例如dict([(‘key1’, ‘value1’), (‘key2’, ‘value2’)])）。其初始状态下，键对应的默认值是没有定义的，只有在添加了键 - 值对之后才能通过键获取到相应的值。
        
    - defaultdict：defaultdict在初始化时需要传入一个可调用对象（如函数）作为默认工厂函数。这个函数用于在访问不存在的键时生成默认值。例如，defaultdict(list)会在访问不存在的键时调用list()函数来生成一个空列表作为默认值；defaultdict(set)会在访问不存在的键时调用set()函数来生成一个空集合作为默认值。
        
- 应用场景差异：
    
    - 普通dict：适用于明确知道所有可能的键，或者在访问键之前已经对键 - 值对进行了初始化的情况。例如，在存储用户配置信息时，如果已经预先确定了配置选项的名称（键），就可以使用普通dict。
        
    - defaultdict：在处理不确定键是否存在，并且希望在键不存在时能够自动生成默认值的场景中非常有用。例如，在统计文本中单词出现的频率时，可以使用defaultdict(int)，当遇到一个新单词（键）时，自动将其计数初始化为 0，方便后续的计数操作。
        
