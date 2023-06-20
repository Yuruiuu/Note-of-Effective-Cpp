# Item 1: 将c++视为语言联合体

将C++的主要子语言视为一体

+ C ——归根结底，C++ 依然是基于 C 的。
> blocks（模块），statements（语句），preprocessor（预处理器），built-in data types（内建数据类型），arrays（数组），pointers（指针）等等，全都来自于 C。

+ Object-Oriented C++ —— C++ 的这部分就是 C with Classes 涉及到的全部
> classes（类），encapsulation（封装），inheritance（继承），polymorphism（多态），virtual functions (dynamic binding)（虚拟函数（动态绑定））等。

· Template C++ ——这是 C++ 的 generic programming（泛型编程）部分。

· STL —— STL 是一个 template library（模板库）
> 它将 containers（容器），iterators（迭代器），algorithms（算法）和 function objects（函数对象）非常优雅地整合在一起.

# Item 2: 用consts, enums和inlines取代#defines
即“用 compiler（编译器）取代 preprocessor（预处理器）”

用constant（(常量）来取代macro (宏）:
