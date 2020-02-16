#### C++ 联邦
- C
- Object-Oriented
- Template
- STL

#### 03 user const whenever possible
星号和const的位置:
int\* const 被指物
\*两边都有,则二者都是
\*前面的是对被指向对象的修饰，\*后面的是对指针本身的修饰
STL 迭代器:T\* const. 指针本身是常量,所以不能指向其他的类型.
[指针本身是常量],怎么理解呢?


#### 05 默默干了哪些事
- 构造函数
- 析构函数
- copy复制
- copy构造


#### 06 阻止拷贝和赋值构造
为了阻止编译器生成这两个函数，怎么做呢。
- 自己声明一个，但是不实现它
- 定义为private，因为编译器生成的是public的
但是member和friend函数还是能访问
- 会遇到链接错误





