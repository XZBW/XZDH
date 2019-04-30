#Spring面试题

   一.什么是Spring
	spring 是个Java企业级应用的开源开发框架。

   二.使用Spring框架的好处是什么？
	1.Spring是轻量级框架
	2.Spring通过控制反转实现低耦合
	3.面向切面编程（aop）：Spring支持面向切面的编程，并且把应用业务逻辑和系统服务分开。
	4.容器：Spring 包含并管理应用中对象的生命周期和配置。
	5.MVC框架，M（模型层），v（展示层），c（控制层）

   三. Spring由哪些模块组成?
	Core module
	Bean module
	Context module
	Expression Language module
	JDBC module
	ORM module
	OXM module
	Java Messaging Service(JMS) module
	Transaction module
	Web module
	Web-Servlet module
	Web-Struts module
	Web-Portlet module

   四.核心容器（应用上下文) 模块。
	这是基本的Spring模块，提供spring 框架的基础功能，它使Spring成为一个容器。

   五.BeanFactory – BeanFactory 实现举例。
	Bean 工厂是工厂模式的一个实现，提供了控制反转功能，用来把应用的配置和依赖从正真的应用代码中分离
	
   六.Spring配置文件
	Spring配置文件是个XML 文件，这个文件包含了类信息，描述了如何配置它们，以及如何相互调用。
   
   七.什么是Spring IOC 容器？
	Spring IOC 负责创建对象，管理对象，装配对象，配置对象，并且管理这些对象的整个生命周期。

   八.IOC的优点是什么？
	1.IOC 或 依赖注入把应用的代码量降到最低。
	2.低耦合
	3.IOC容器支持加载服务时的饿汉式初始化和懒加载。
 
   九.什么是Spring的依赖注入？
	这概念是说你不用创建对象，而只需要描述它如何被创建。（IOC容器）负责把他们组装起来。

   十.有哪些不同类型的IOC（依赖注入）方式？
	1.构造器依赖注入：构造器依赖注入通过容器触发一个类的构造器来实现的
	2.Setter方法注入：Setter方法注入是容器通过调用无参构造器或无参static工厂 方法实例化bean之后

   十一.使用Spring通过什么方式访问Hibernate?
	控制反转 Hibernate Template和 Callback。
	继承 HibernateDAOSupport提供一个AOP 拦截器。


   十二. Spring支持的ORM
	Hibernate
	iBatis
	JPA (Java Persistence API)
	TopLink
	JDO (Java Data Objects)
	OJB

   十三.Spring支持的事务管理类型
	编程式事务管理：这意味你通过编程的方式管理事务，给你带来极大的灵活性，但是难维护。
	声明式事务管理：这意味着你可以将业务代码和事务管理分离，你只需用注解和XML配置来管理事务。


Spring面向切面编程（AOP）

   一. 解释AOP
	1.面向切面的编程，是一种编程技术，允许程序模块化横向切割关注点，或横切典型的责任划分，如日志和事务管理。
	2.面向切面编程提供声明式事务管理 
	3.spring支持用户自定义的切面 
	4.各个步骤之间的良好隔离性 
	5.源代码无关性 

   二.在Spring AOP 中，关注点和横切关注的区别是什么？
	1.关注点是应用中一个模块的行为
	2.横切关注点是一个关注点，此关注点是整个应用都会使用的功能，比如日志，安全和数据传输

   三.连接点
	在这个位置我们可以插入一个AOP切面，它实际上是个应用程序执行Spring AOP的位置。

   四. 什么是织入。什么是织入应用的不同点？
	1.织入是将切面和到其他应用类型或对象连接或创建一个被通知对象的过程。
	2.织入可以在编译时，加载时，或运行时完成。



Spring 的MVC
   
   一.什么是Spring的MVC框架？
	Spring 的MVC框架用控制反转把业务对象和控制逻辑清晰地隔离。
		
   二.DispatcherServlet
	Spring的MVC框架是围绕DispatcherServlet来设计的，它用来处理所有的HTTP请求和响应。
   
   三.什么是Spring MVC框架的控制器？
	提供一个访问应用程序的行为，此行为通常通过服务接口实现。控制器解析用户输入并将其转换为一个由视图呈现给用户的模型。
