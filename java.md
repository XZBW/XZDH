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

二.map（键值对、键唯一、值不唯一）：Map集合中存储的是键值对，键不能重复，值可以重复。
	(使用put添加数据)
	Map实现类：HashMap(键值对，非线程同步，允许一个键为null)
	Hashtable(HashMap的线程安全版，它支持线程的同步，键值不能为null)
	LinkedHashMap(保存了记录的插入顺序，有序，非线程安全)
	TreeMap(能够根据键进行排序，默认是按键值的升序排序（自然顺序），非线程同步)
	遍历方式：(For-Each循环，Iterator(迭代器))

三.set（无序、不能重复）：Set里存放的对象是无序，不能重复的
	(使用add添加数据)
	HashSet(无序，不重复，非线程安全)
	LinkedHashSet(有序，非线程安全)
	遍历方式：(for循环，For-Each循环，Iterator(迭代器))

四.Iterator(迭代器)！	
	Iterator：可用来遍历Set和List集合(向前遍历)
	ListIterator：只能遍历List集合(双向遍历，多了对集合数据的增删改查功能)

3.Spring常用的设计模式！
	一共9种设计模式：
	（普通工厂模式，工厂模式，单例模式，适配器，包装器，
	策略模式，模板模式，代理模式，观察者模式)

一.普通工厂模式
	(由一个工厂类根据传入的参数，动态决定应该创建哪一个产品类,
	各种BeanFactory以及ApplicationContext创建中都用到)
	