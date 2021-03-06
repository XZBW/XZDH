# MyBatis

-MyBatis的工作流程

	1.加载配置文件并初始化
	2.接受传入的参数和执行的sql ID
	3.获取数据库连接，根据最终的sql和参数到数据库执行，并得到结果，释放连接资源
	4.返回处理结果

-MyBatis的优缺点

	优：
	   1.简单易学
	   2.灵活
	   3.低耦合
	   4.提供映射标签
	   5.提供对象关系映射
	   6.支持动态sql

	缺：
	   1.sql语句依赖数据库，不能更换数据库
	   2.二级缓存机制不佳
	   3.框架比较简陋，功能缺失
	
	总结：
	mybatis的优点也是mybatis的缺点，正因为mybatis使用简单，数据库可靠性、
	完整性多依赖于程序员对sql的使用水平上。

	MyBatis有待改进之处：
       无论什么样的数据库都要sql语句，一个应用系统要的sql语句太多了

-MyBatis的面试题

	一.#{}与${}的区别
		1.#{}是预编译，${}是字符串替换
		2.在处理#{}时会将sql中的#{}替换为？号
		3.MyBatis在处理${}时，就是把${}替换成变量的值
		4.使用#{}可以防止sql注入

	二.当实体类中的属性名和表中的字段名不一致，怎么办？
		1.定义字段名的别名让他与实体类的属性名一致
		2.通过resultMap让字段与属性一一对应

	三.模糊查询like怎么写
		1.在代码中添加sql通配符
		2.在sql语句中拼接通配符

	四.Mybatis是如何将sql执行结果封装为目标对象并返回的？都有哪些映射形式？
		1.第一种是使用<resultMap>标签
		2.第二种是使用sql列的别名功能
		3.MyBatis通过反射创建对象，并为他赋值，找不到映射关系的，无法赋值

	五.在mapper中如何传递多个参数?
		使用 @param

	六.Mybatis动态sql是做什么的？都有哪些动态sql？能简述一下动态sql的执行原理不？
		1.以标签的形式编写动态sql，完成逻辑判断和动态拼接sql的功能。
		2.Mybatis提供了9种动态sql标签：trim|where|set|foreach|if|choose|when|otherwise|bind。

	七.为什么说Mybatis是半自动ORM映射工具？它与全自动的区别在哪里？
		1.Mybatis需要手动编写sql来完成，所以，称之为半自动ORM映射工具。
		2.Hibernate可以根据对象关系模型直接获取，所以它是全自动的
