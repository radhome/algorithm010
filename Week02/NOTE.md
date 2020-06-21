学习笔记

#### HashMap实现原理
HashMap的主干是一个Node数组。Node是HashMap的基本组成单元，每一个Entry包含一个key-value键值对。
简单来说，HashMap由数组+链表+红黑树实现的。
HashMap使用哈希表来存储。

HashMap的数组长度一定是2的次幂。

HashMap线程不安全,put的时候多线程可能会导致数据不一致；自动扩容时可能出现多个线程同时修改链表结构。

#### 1.7和1.8的HashMap实现区别
JDK1.8在JDK1.7的基础上增加了红黑树来进行优化。即当链表超过8时，链表就转换为红黑树，利用红黑树快速增删改查的特点提高HashMap的性能。
