注意句尾分号
重要的开头： ``using namespace std;``
使用变量前先定义
函数尽量用到之前就写，否则就要写声明



### 主函数
	int main(){
		return 0
	}

### 输出
``#include<iostream>``
``cout <<"Hello world!";``

换行：``cout <<"Hello world!\n";``
	或者： ``cout <<"Hello world!"<< endl;``

### 输入
``#include<iostream>``
``cin >> x``

#### 多输入
用空格分隔的输入：

	while(cin >> num){// 遇到回车就停止输入 
		nums.push_back(num); 
		if(getchar()=='\n') 
			break;//只能放这里，不然会少了最后一个输入值 }
或者：

	cin >> x >> y;  //已知输入有多少个且量少

### 运算符
% 代表取余
/ 代表整除
& 代表与
| 代表或
^ 代表异或
`>>`代表右移
`<<`代表左移
&& || ！

### 字符串
`#include<string>`
字符串组合：

	string firstname = "Hong";
	string lastname = "Belinda";
    string fullname = firstname + lastname;
    fullname = firstname.append(lastname);
字符串长度：

	txt.length();
	txt.size();
字符串中字符单独修改（可以直接通过类似数组形式修改）

	mystring[0] ='J'

### 算术
`#include<cmath>`
max(x,y)
min(x,y)
sqrt(64)=8
pow(3,2)=9
abs(-5)=5

### 条件语句
第一种写法：

	if (a > b)
		x = 5
	else if (a = b)
		x = 4
	else 
		x = 3

第二种写法：
`string result = (time <18)? "Good day." : "Good eveing" ;`

第三种写法：

	switch(day)
    {
        case 1: 
            cout << "Monday";
            break;
        case 2:
            cout << "Tuesday";
            break;
        case 3:
            cout << "Wednesday";
            break;
        case 4:
            cout << "Thursday";
            break;
        case 5:
            cout << "Friday";
            break;
        case 6:
            cout << "Saturday";
            break;
        case 7:
            cout << "Sunday";
            break;
        default:
            cout << "the number is over seven"<<endl;
    }

### 循环语句
while循环：
	 while(i < 5) {
		 cout << i <<"\n";
	    i++;
     }
for循环：
	for (int j = 0 ; j<5 ; j++) {
	    cout << j << endl;
     }
     其中 `break;` 表示跳出循环
     其中 `continue;`表示结束本次循环，直接进入下一次循环

### 数组
	string bands[] = {"volvo","byd","ford","mazda","tesla"};//不定长数组
	int mynum[3] = {10,20,30};//整型数组

不能以变量来衡量数组长度 如`int n[k]`，只能尽量先开个大的数组再往里填

二维数组：


### 指针与引用
引用（取地址）： &变量
	
    string food = "Pizza";
    string &meal = food;

指针（用于存储地址）：`*指针 = 变量值`

	string food = "Pizza";
	    string *ptr = &food;//定义该变量为指针变量时，*的位置靠近变量名称还是数据类型都没关系
	    cout << food <<endl;//输出“Pizza”
	    cout << &food << endl;//输出food的内存地址
	    cout << ptr << endl;//输出food的内存地址
	    cout << *ptr <<endl;//输出“Pizza”，调用ptr内容对应的数据地址的

！在函数中的应用：这里swap2 和 swap3 都可以成功交换

	void swapt2 (int &x, int &y)//这里是引用符号，不是取地址符号。相当于x=外面调用它的变量，指向同一个内存块，函数形参能够调用外部实参                           
	{
	    int z = x;              
	    x = y;                 
	    y = z;
	}
	 
	void swapt3 (int *x, int *y)
	{
	    int temp;
	    temp = *x;
	    *x = *y;
	    *y = temp;  
	}


### 类
有很多的成分

	class car                //类定义
	{
	    private:
		    string master;
	    pubulic:             //访问关键字 
	        string  brand;   //类中的变量叫做属性
	        string  model;
	        int year;
	        void mymethod() 
			 {
			    cout << "Hello world!"; }

		    
	};   //类定义最后这个分号不要漏掉
	int car::speed(int maxspeed) //方法声明，要在多加上类名：：
    {
	    return maxspeed;
	}

    car::car(string x,string y, int z ) //构造函数，前面没有返回值类型
	{
		brand = x; //类中属性可以直接被调用
	    model = y;
	    year = z ;
	}
	 
	int main ()
	{
	    car carobject1;  //声明类的对象,又称为实例,实例后才真正的分配内存
	    car car1("byd","..", 1)
	    carobject1.brand  = "BYD";
	    carobject1.model  = "song plus";`
	    cout << car1.speed(300) << endl;
	}

类的继承：

	class car :: public vehicle //子类，继承了vehicle 中public的内容
	{
		public:
		string model = "Mustang"；//子类新增属性
    }

### 排序
	#include<algorithm>
	using namespace std;
	// 自己编写函数来实现升序排列
	bool compare (int a,int b)
	{
	    // 升序排列，如果改为return a>b ,则为降序
	    return a<b;
	}
	int main()
	{
	    int a[10] = {7,4,5,23,2,73,41,52,28,60},i;
	    for(i=0;i<10;i++)
	        cout<<a[i]<<" ";
	    cout<<endl;
	    sort(a,a+10,compare);
	    for(i=0;i<10;i++)
	        cout<<a[i]<<" ";
	    return 0;
	}

如果是vector，要这么写：
	
	sort(arr.begin(),arr.end(),compare)
