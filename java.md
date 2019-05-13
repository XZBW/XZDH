1.java基础！

一.java三大特性
	1.封装
	2.继承
	3.多态

二.基本数据类型
	(byte、short、int、long、float、double、char、boolean)
	对应的包装类
	(Byte、Short、Integer、Long、Float、Double、Character、Boolean)

三.String(引用类型)
	1.String(引用类型)
	2.StringBuilder(可对字符串进行操作，非线程安全)
	3.StringBuffer(线程安全)

四.Java常用的包、类、接口
  （1）类
	1.Object
	2.Sting
	3.System
	4.file
	5.FileInputStream
	6.Date
	7.Long
  （2）包
	1.Java.lang
	2.java.util
	3.java.io
	4.java.net
	5.java.sql
	6.java.awt
	7.java.text
  （3）接口
	1.Map
	2.List
	3.Set
	4.Iterator
	5.Runnable
	6.Connection
	7.Comparable

五.怎么理解面向对象
	面向对象是向现实世界模型的自然延伸，这是一种”万物皆对象”的编程思想。

六.什么是多态
	“多种状态”。在面向对象语言中，接口的多种不同的实现方式即为多态。
	方法的重写和重载是java多态性的不同表现。！

七.什么是封装
	封装，即隐藏对象的属性和实现细节，仅对外公开接口，控制在程序中属性的读和修改的访问级别

八.什么是继承
	子类继承父类，表明子类是一种特殊的父类，并且具有父类所不具有的 一些属性或方法。

九.java.io中常用的流
	1.字节流
	2.字符流
	3.输入流
	4.输出流
	5.节点流
	6.处理流

2.集合!

集合一共有3种：list（列表），map（映射），set（集），还有一种是Queue（队列）jdk5中加上的

一.list（有序、可重复）：List里存放的对象是有序的，同时也是可以重复的，
		      List关注的是索引，拥有一系列和索引相关的方法，查询速度快。
		      因为往list集合里插入或删除数据时，会伴随着后面数据的移动，
 		      所有插入删除数据速度慢。(可用HashSet去重)
	(使用add添加数据)
	list实现类：ArrayList(用于查多，增删少的)
	LinkedList(用于增删多，查找少的)
	Vector(线程安全)
	遍历方式：(for循环，For-Each循环，Iterator(迭代器))
