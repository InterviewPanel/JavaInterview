# 《String》面试问题链

String字符串是面试的常客,必问,并且通过String可以问到很深层次的问题

## String、StringBuffer、StringBuilder的区别
从线程安全上看:

从性能上看:

### String的值为什么是不变的?

### 是否可以继承String类
因为String是final类,是不可以被继承的.

### 字符串链接为什么不推荐用String的“+”

#### 什么情况下用+运算符,必调用StringBuffer或者Stringbuilder的append方法连接字符串性能更好

### 如果将String重新赋值给另一个String,会发生什么?

#### 具体一点,JVM内存会是什么样的操作 