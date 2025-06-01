	def makeclear(n:int):
	    if n <= 0:
	        return "error"
	    else:
	        sum = 0
	        for i in range(1,n+1):
	            sum += i
	        return sum

	def main():
	    # 主程序逻辑写在这里
	    n = (int)(input())
	    ans = makeclear(n)
	    print(ans)
	if __name__ == "__main__":
	    main()


python的print末尾自带换行


## 一些有用的函数：
### split(分隔符") 分割字符串返回一个列表
`letters = 'a,b,c,d,e,f'`
`letters.split(',') ['a', 'b', 'c', 'd', 'e', 'f']

反向操作：
`','.join(letters_list)`

正常的处理输入：
`n, k = map(int, input().split())`
`nums = list(map(int, input().split()))`

### replace(a,b,i)
setup = 'a boy likes playing basketball.' 
setup.replace('boy','girl') 
'a girl likes playing basketball.' 
setup.replace('a', 'b') 
'b boy likes plbying bbsketbbll.' 
setup.replace('a', 'b', 1) 
'b boy likes playing basketball.'

### input()
`a = input(msg)`打印出msg，并从键盘输入一个变量赋值给a，a为str类型。

### List
使用`insert(offset,value)`,当offset为0时则插入到头部，当offset超过了尾部，则会插入到最后，并不会引起异常。
使用`del`则是删除指定位置的元素
使用`remove()`则是删除指定值的数
使用`pop()`则是弹栈操作，返回最后一位元素，即栈顶元素。

使用`in`判断元素是否存在
`count()`记录特定值出现次数
`index()`查询具有特定值的元素位置
word = [1,2,3,4,5,1,1,2] 
1 in word 
True 
word.count(1) 
3 
word.index(1) 
0
word.index(1,1) 
5 
word.index(1,6) 
6

使用`sort()`与`sorted()`排列数组
默认都是升序排列，加上参数`reverse=True`则降序排列。
- `sort()`会对原列表进行排序，改变原列表内容。s.sort()
- `sorted()`则会返回排序好的列表副本，原列表内容不变。 s1 = sorted(s)

tuple:
初始化： a = [1,2,3]  a = tuple(a)

set:
初始化：a=[1,2,3] a=set(a)

![[列表推导式.png]]


string.ascii_lowercase  #小写字母

python中的startswith函数，可以判断字符串是否为前缀

	def countPrefixes(self, words: List[str], s: str) -> int:
	        ans = 0
	        for word in words:
	            if s.startswith(word):
	                ans += 1
	        return ans