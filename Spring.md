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

