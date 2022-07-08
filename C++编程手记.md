# 输入规范
1. 读取整行：cin.getline(&,size)读取换行符并替换为'\0'，cin.get(&,size)不读取换行符而将其保留在输入队列因此连用两次回有问题，常与cin.get()(不带参数版本)连用。
2. cin忽略空格和换行且发送给cin的输入先被缓冲只有按下回车时才被发送给程序。int a ;cin.get(a);将检查输入是否正常。cctype库函数isalpha()检测字母isdigits()检测数字isspace()检测空格。
     
# 类特性
1. 类成员属性private只能由该类成员访问无法由子类访问，protected可以由子类访问。
   
# C++新特性
1. const,enum类型。
2. new动态分配内存：int* pt=new int; \*pt=1;分配内存空间,赋值。delete pt;int size;cin>>size;int* ps=new int \[size]; 深度拷贝：先分配空间，再strcpy（&，&）复制目标，用strlen获取所需空间大小。
3. 基于范围的for循环：double prices[5]; for(double x:prices) cout << x << std::endl;
   
# 容器
1. vector对象存储在自由存储区或堆，效率较低，array存储在栈，与数组一样效率较高。但array需指定长度，vector不必指定。
   
# 系统操作
1. 获取系统时间：clock_t start=clock(); while(clock()-start < n*CLOCKS_PER_SEC);

# markdown贴图
需图片与md在同一目录下
 <!-- <img src="G:\Coding\markdown\00000002.jpg" /> -->
[TOC]

