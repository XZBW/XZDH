>不定期分享一些与后端相关不错的资源学习网站
 
## Markdown
- [Markdown语法](https://www.cnblogs.com/miki-peng/p/12502985.html)

## 社区
- [stackoverflow](https://stackoverflow.com/)
- [掘金](https://juejin.cn/)
- [NODE中文社区](https://cnodejs.org/)
- [Processon免费在线流程图思维导图](https://processon.com/)
- [hutool（糊涂）工具包](https://hutool.cn/docs/#/)
    
 
## 加油打工人！！！
> + [高并发面试题](https://blog.csdn.net/qianzhitu/article/details/108488876)
> + [分布式面试题](https://blog.csdn.net/libaowen609/article/details/125131974)
> + [多线程面试题](https://blog.csdn.net/Firstlucky77/article/details/125173318)
> + [微服务面试题总结](https://blog.csdn.net/m0_58479954/article/details/124984049)
> + [SpringCloud面试题](https://blog.csdn.net/a6636656/article/details/124429257)
> + [SpringBoot面试题](https://blog.csdn.net/qq_22075913/article/details/125826581)
> + [Spring面试题](https://blog.csdn.net/zqy_zq_zxl/article/details/125735360)
> + [SpringMVC面试题](https://blog.csdn.net/guan1843036360/article/details/123012816)
> + [AOP spring面试题](https://www.csdn.net/tags/Mtjakg4sODE0MjAtYmxvZwO0O0OO0O0O.html)
> + [IOC spring面试题](https://blog.csdn.net/qq_35757264/article/details/124217533)
> + [Redis面试题](https://blog.csdn.net/weixin_40205234/article/details/124614720)
> + [ZooKeeper面试题](https://blog.csdn.net/m0_58479954/article/details/124982935)
> + [Docker面试题](https://blog.csdn.net/qq_46654855/article/details/125742589)
> + [Linux面试题](https://blog.csdn.net/q66562636/article/details/124435549)
> + [RabbitMQ面试题](https://blog.csdn.net/m0_68102173/article/details/124299647)
> + [Mysql面试题](https://blog.csdn.net/m0_58479954/article/details/124741331)
> + [Mybatis面试题](https://blog.csdn.net/m0_58479954/article/details/124852560) 
   
## 服务搭建
> + [自己搭服务启动时遇到（Error creating bean with name 'configDataContextRefresher' defined in class path resource）boot版本依赖问题解决](https://blog.csdn.net/weixin_42194695/article/details/126075898)
> + [Lombok TableField注解 用来解决实体类中有的属性但是数据表中没有的字段](https://www.cnblogs.com/tszr/p/16282003.html)

## IDEA 
> + [IDEA官方各版本下载](https://www.jetbrains.com/zh-cn/idea/download/other.html)
> + [IDEA最新永久激活码激活教程](https://www.955code.com/768.html)
> + [IDEA文件编码格式修改](https://blog.csdn.net/weixin_64893448/article/details/126688131)
> + [IDEA导入Eclipse项目](https://blog.csdn.net/qq_41956221/article/details/117157961)
> + [IDEA界面切换中文](https://blog.csdn.net/weixin_44759556/article/details/124587458)
> + [IDEA2022开发配置最佳配置（字符编码、自动编译、注释风格、过滤文件、maven配置、字体）](https://blog.csdn.net/sinat_27933301/article/details/83903199)
> + [IDEA工具（阿里巴巴）代码规范检查插件](https://blog.csdn.net/Monsterof/article/details/108239250)
> + [IDEA配置数据库工具](https://blog.csdn.net/a15608445683/article/details/123167066)
> + [IDEA安装Mybatis log（sql执行日志插件）](https://blog.csdn.net/weixin_39183923/article/details/127806127)

## Nginx负载均衡
> ## 1.Nginx官网、下载、安装
> + [Nginx官网下载](https://nginx.org/en/download.html)
> + [Nginx安装（win/linux）](https://blog.csdn.net/qq_41755845/article/details/124368785)
> ## 2.Nginx常用命令
> + [nginx常用命令大全](https://www.cnblogs.com/Simoon/p/16452249.html)
> + [Nginx常用命令解读](https://blog.csdn.net/weixin_47194244/article/details/123498003)
> ## 3.Nginx配置文件、反向代理、负载均衡、动静分离
> + [Nginx配置文件详解](https://blog.csdn.net/qq_45794943/article/details/122722834)
> + [Nginx负载均衡的三种方式(轮询、权重、ip哈希（ip——hash）、fair(根据后端服务器响应时间分配，快的优先))](https://www.cnblogs.com/51core/articles/14303460.html)
> + [nginx的三种反向代理方式(IP代理、端口代理、域名代理)](https://m.php.cn/nginx/463019.html)
> + [nginx的优点，负载均衡以及动静分离等知识点](https://blog.csdn.net/weixin_45154837/article/details/100672566)
> + [Nginx入门：反向代理、负载均衡、动静分离](https://blog.csdn.net/qq_33491651/article/details/124123952)
> + [Nginx+keepalived 高可用双机热备（主从模式/双主模式）](https://blog.csdn.net/qq_25430563/article/details/108835063)

 
## 中间件RabbitMQ详解
> ## 使用消息队列MQ的优点？ 
> + 1.应用解耦：发送一个消息到MQ，其他系统监听MQ，只要消息还在MQ，某些服务挂了后面恢复正常依旧可以消费这个消息。（若不使用MQ则一个服务挂了就无法继续。）
> + 2.流量消峰：有了MQ可以将大量的请求放到消息队列中，服务端每次处理先从MQ中获取，并分散很长一段时间处理。（若不使用MQ很可能被大量的请求打垮。）
> + 3.异步处理：服务只需要发送一条消息到MQ，其他服务获取MQ，就可以返回用户成功了。（若不使用MQ服务接收一个请求，还需要在A,B,C多个服务同步进行写库操作，导致返回响应太久。）
> ## RabbitMQ手动应答与自动应答
> + 自动应答：一旦消费者接收到了消息，就视为自动应答了消息。
> + 手动应答-手动不确认（basicNack方法）：可以nack该消费者先前接收未ack的所有消息。nack后的消息也会被自己消费到。
> + 手动应答-手动拒绝（basicReject方法）：该方法reject后，该消费者还是会消费到该条被reject的消息。
> + 手动应答-手动确认应答（手动确认应答basicAck方法）：需要在消息处理成功后，再确认消息，这就需要手动确认。
> ## RabbitMQ核心6大工作模式（简单模式、工作模式、发布订阅、路由、主题、发布确认）
> + 简单模式
> + 工作模式
> + 发布订阅：一次发发送，多个服务接受
> + 路由
> + 主题
> + 发布确认
 
> ## 1.初始RabbitMQ
> + [RabbitMQ官网下载](https://rabbitmq.com/download.html)
> + [RabbitMQ详解](https://blog.csdn.net/qq_48721706/article/details/125194646)
> + [RabbitMQ原理和架构图解（附6大工作原理）](https://mikechen.cc/18353.html)
> ## 2.RabbitMQ部署与用户
> + [Windows环境下RabbitMQ的启动和停止命令](https://blog.csdn.net/m0_67402341/article/details/123827559)
> + [RabbitWeb页面创建用户](https://blog.csdn.net/qq_39355504/article/details/109166249)
> ## 3.RabbitMQ持久化、发布确认、权重方式（不公平分发、预取值）
> + [RabbitMQ队列持久化、消息持久化、不公平分发、预取值](https://www.cnblogs.com/hzxll/p/16297739.html)
> + [RabbitMQ发布确认（单个、批量、异步批量）](https://blog.csdn.net/dingd1234/article/details/124935443)
> + 1.单独发布消息：同步等待确认，简单，但吞吐量非常有限
> + 2.批量发布消息：批量同步等待确认，简单，合理的吞吐量，一旦出现问题但很难推断出是哪条消息出现了问题。
> + 3.异步处理：最佳性能和资源利用，在出现错误的情况下可以很好地控制，但是实现起来稍微复杂一些。
> ## 4.RabbitMQ交换机（直连、扇形、主题、首部）
> + [RabbitMQ交换机类型介绍](https://wenku.baidu.com/view/7e936b01a6e9856a561252d380eb6294dd882283.html)
> ## 5.RabbitMQ死信队列和延时队列
> + 死信队列三大来源（1.消息TTL过期、2.消息队列达到最大长度（队列满了，无法添加数据到MQ）、3.消息被拒绝并且被消费掉不放回到队列中）
> + 延迟队列使用场景（1.订单在十分钟内未支付则自动取消、2.预定会议，提前提醒会议人员参加会议、3.用户多日没登录则发消息提醒）
> + [RabbitMQ死信队列和延迟队列](https://blog.csdn.net/endless_fighting/article/details/116424018)
> + [springboot版本不兼容swagger版本报错解决Failed to start bean ‘documentationPluginsBootstrapper’](https://blog.csdn.net/FFFPAG/article/details/121700133)
> + [延迟队列插件下载github](https://github.com/rabbitmq/rabbitmq-delayed-message-exchange/tags)
> + [windows下RabbitMQ延迟队列插件安装步骤](https://blog.csdn.net/kuangpengfei/article/details/124177128)
> ## 6.RabbitMQ发布确认高级
> + 消息回退（Mandatory 参数）与备份交换机可以一起使用的时候，备份交换机优先级更高。
> + [RabbitMQ发布确认高级](https://note.oddfar.com/pages/c94906/)
> ## 7.RabbitMQ 幂等性、优先级、惰性
> + Rabbit消息被重复消费解决方法：设置一个全局唯一的id，利用Redis执行setnx命令，天然具有幂等性,从而实现不重复消费,若存在redis会返回0，则重复。反之不存在redis返回1，不重复。
> + 优先级队列：队列内消息的优先级处理。队列需要设置优先级队列，消息需要设置优先级消息，才可以对消息进行排序。
> + 惰性队列：它的一个重要的设计目标是能够支持更长的队列，即支持更多的消息存储，消息是储存在磁盘上。
> + [RabbitMQ 幂等性、优先级、惰性](https://note.oddfar.com/pages/ee71b9/#%E5%B9%82%E7%AD%89%E6%80%A7)
> ## 8.RabbitMQ集群搭建与镜像队列、联邦队列、Shovel
> + [Linux+虚拟机搭建RabbitMQ集群](https://blog.csdn.net/yanglaoda123456/article/details/46380631)
> + [Docker搭建RabbitMQ集群(多台服务器)](https://blog.csdn.net/Bejpse/article/details/123836743)
> + [RabbitMQ集群实现镜像队列(高可用)](https://blog.csdn.net/xiangjunyes/article/details/121929924?spm=1001.2101.3001.6661.1&utm_medium=distribute.pc_relevant_t0.none-task-blog-2%7Edefault%7EOPENSEARCH%7ERate-1-121929924-blog-46380631.pc_relevant_multi_platform_whitelistv4&depth_1-utm_source=distribute.pc_relevant_t0.none-task-blog-2%7Edefault%7EOPENSEARCH%7ERate-1-121929924-blog-46380631.pc_relevant_multi_platform_whitelistv4&utm_relevant_index=1)
> + [RabbitMQ联邦交换机/队列 + Shovel](https://blog.csdn.net/IT_Holmes/article/details/124996212)


## SVN
> + [SVN官网下载](https://tortoisesvn.net/downloads.html)
> + [SVN下载安装](https://blog.csdn.net/qq_20236937/article/details/118958965)
> + [svn——无法使用Subversion命令行客户端（Can‘t use Subversion command line client:svn）](https://blog.csdn.net/weixin_43361722/article/details/119325643)
> + [SVN提交报错 Commit blocked by pre-commit hook (exit code 1) with output](https://blog.csdn.net/weixin_34362875/article/details/85942257?spm=1001.2101.3001.6661.1&utm_medium=distribute.pc_relevant_t0.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-1-85942257-blog-53213821.pc_relevant_3mothn_strategy_recovery&depth_1-utm_source=distribute.pc_relevant_t0.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-1-85942257-blog-53213821.pc_relevant_3mothn_strategy_recovery&utm_relevant_index=1)

## GitHub/GitTree
> + [GIT下载安装](https://blog.csdn.net/weixin_47638941/article/details/120632890)
> + [Git常用命令](https://blog.csdn.net/qq_38111015/article/details/84885809)
> + ## git拉取项目
> + git拉项目,可以用传统的idea git 去拉，如果不行可以自己新建目录 用 gitbase 输入指令去拉取项目。拉取命令 - git clone 项目URL
> + [git中报unable to auto-detect email address 错误的解决方法](https://blog.csdn.net/liufangbaishi2014/article/details/50037507)
> + git config --global user.email "email"
> + git config --global user.name "name"
> + [IDEA中merge分支时提示refusing to merged unrelated histories](https://blog.csdn.net/aiwaston/article/details/117738262)
> + [切分支遇到Move or commit them before checkout问题解决](https://blog.csdn.net/HBella/article/details/100669009)


## Maven
> + [Maven官网下载](https://maven.apache.org/download.cgi)
> + [Idea Maven配置](https://www.cnblogs.com/ckfuture/p/15821541.html)
> + maven项目没有自动识别可以手动打开maven文件
> + [IDEA不识别Maven项目](https://blog.csdn.net/m0_67402774/article/details/126718840)
> + [idea右边找不到maven窗口不见了](https://blog.csdn.net/m0_67391121/article/details/123632847)
> + [Maven出现子项目jar包路径正确却unknown处理（Cannot resolve xxxx(依赖名):unknown）](https://blog.csdn.net/wwwwwww31311/article/details/122287281)

## JAVA

> ## JDK8新特性（[相关链接](https://blog.csdn.net/LXYDSF/article/details/125919046)）
> + [JDK8安装及配置环境变量](https://tortoisesvn.net/downloads.html)
> + 增加了新的语法：Lambda 表达式、函数式接口、方法引用与构造器引用等...（[jdk8 新特性汇总](https://blog.csdn.net/zykwblx/article/details/125959421)）

> ## Java设计模式（单例、工厂、代理、建造者、模板方法、原型、策略）需补充！
> + [Java中常用的设计模式（附代码实现和具体的应用场景）](https://blog.csdn.net/qq_45649807/article/details/124593629)
> + 单例模式：保证一个类只有一个实例，并且提供一个访问该全局访问点
> + 工厂模式（简单工厂、工厂方法、抽象工厂模式）：在工厂模式中，我们在创建对象时不会对客户端暴露创建逻辑，并且是通过使用一个共同的接口来指向新创建的对象。(IOC也是工厂模式)
> + 代理模式（静态代理、JDK 代理、CGLIB代理）：通过代理控制对象的访问，可以在这个对象调用方法之前、调用方法之后去处理/添加新的功能。(也就是AOP的实现)
> + 代理模式使用场景：Spring AOP、日志打印、异常处理、事务控制、权限控制等
> + 建造者模式：是将一个复杂的对象的构建与它的表示分离，使得同样的构建过程可以创建不同的方式进行创建。
> + 原型模式：原型模式多用于创建复杂的或者构造耗时的实例，因为这种情况下，复制一个已经存在的实例可使程序运行更高效。
> + 策略模式：将每一个算法、逻辑、操作封装起来，而且使它们还可以相互替换。
> + 观察者模式：又叫发布-订阅模式，他定义对象之间一种一对多的依赖关系，使得当一个对象改变状态，则所有依赖于它的对象都会得到通知并自动更新
> + ## 单例模式（懒汉/饿汉区别）
> + 饿汉式：类初始化时，会立即加载该对象，线程天生安全，调用效率高。
> + 懒汉式：类初始化时，不会初始化该对象，真正需要使用的时候才会创建该对象，具备懒加载功能

## JAVA接口、抽象、重载、重写、继承、多态、面向对象、面向抽象

> + ## 接口和抽象类的区别
> + 抽象类可以存在普通成员函数，而接口只能存在pubic abstract 方法。
> + 抽象类中的成员变量，可以时各种类型的，而接口中的成员变量只能是 public static final类型。
> + 抽象类只能继承一个，而接口可以实现多个。

> + ## 重载和重写的区别
> + 重载：同一个类参数类型不同，个数不同，顺序不同，但是方法返回值可以不同，和访问修饰符可以不同。
> + 重写：发生在父子类，方法名，参数表，必须相同，返回值范围小于等于父类。抛出的异常范围小于父类，访问修饰符范围大于等于父类，如果父类访问修饰符为private，那么就无法被被重写。

> + ## 相关链接
> + [接口和抽象类的区别，重载和重写的区别](https://blog.csdn.net/qq_55931917/article/details/123829613)

> ## JAVA集合
> + ## JAVA集合一共有3种（List、set、Map）
> + [常用的几种java集合类总结](https://blog.csdn.net/gejiangbo222/article/details/81540616) 
> + [List、Set和Map的各自特征及使用场景](https://www.pianshen.com/article/6554339886/)
> + ## List、Set和Map的区别（List、Set都继承自Collection接口，Map则不是）（[相关链接](https://blog.csdn.net/w759826115/article/details/122736454)）
> + ## List（LinkedList、ArrayList、Vector）
> + List的特点：元素有放入顺序，且可重复。
> + List支持for循环，也就是通过下标来遍历，也可以用迭代器。
> + List接口有三个实现类：LinkedList,ArrayList,Vector。
> + List和数组类似，List可以动态增长，查找元素效率高，插入删除元素效率低，因为会引起其他元素位置改变。
> + ## Set（HashSet、LinkedHashSet）
> + Set的特点：元素无放入顺序，且不可重复
> + Set只能用迭代器，因为他无序，无法使用下标取值
> + Set接口有两个实现类：HashSet（底层由HashMap实现），LinkedHashSet
> + Set：检索元素效率低，删除和插入效率高，插入和删除不会引起元素位置改变。
> + ## Map（HashMap、LinkedHashMap、Hashtable、TreeMap）
> + Map集合的数据结构仅仅针对键有效，与值无关。存储的是键值对形式的元素，键唯一，值可重复。

> ## HashMap
> + ## HashMap之1.7和1.8的区别（[相关链接](https://blog.csdn.net/weixin_44842613/article/details/116529880)）
> + 1.底层数据结构不一样，1.7是数组+链表，1.8则是数组+链表+红黑树结构（当链表长度大于8，转为红黑树）。
> + 2.1.7中新增节点采用头插法，1.8中新增节点采用尾插法。这也是为什么1.8不容易出现环型链表的原因。
> + 3.在扩容的时候：1.7在插入数据之前扩容，而1.8插入数据成功之后扩容。
> + ## HashMap红黑树
> + 
> + ## 相关链接
> + [HashMap之1.7和1.8的区别(详解)](https://blog.csdn.net/m0_62286364/article/details/126130219)
> + [初步了解红黑树](https://blog.csdn.net/v_july_v/article/details/6105630)
> + [深入源码解析HashMap 1.8](https://blog.csdn.net/carson_ho/article/details/79373134)

> ## 什么是序列化
> + 序列化： 将 java对象信息 转换成 二进制数据流的过程
> + 反序列化： 将 二进制数据流 转换成 java对象信息的过程

> ## 深拷贝和浅拷贝的区别是什么？
> + 浅拷贝：对于基本数据类型：直接复制数据值；对于引用数据类型：只是复制了对象的引用地址，新旧对象指向同一个内存地址，修改其中一个对象的值，另一个对象的值也随之改变。
> + 深拷贝：对于基本数据类型：直接复制数据值；对于引用数据类型：开辟新的内存空间，在新的内存空间里复制一个一模一样的对象，新老对象不共享内存，修改其中一个对象的值，不会影响另一个对象。
> + 深拷贝相比于浅拷贝速度较慢并且花销较大。

> ## Spring事务失效
> + [spring事务失效的12种场景](https://blog.csdn.net/Pastxu/article/details/124531638?utm_medium=distribute.pc_relevant.none-task-blog-2~default~baidujs_baidulandingword~default-1-124531638-blog-120098743.pc_relevant_multi_platform_whitelistv4&spm=1001.2101.3001.4242.2&utm_relevant_index=4)
> + [Spring事务失效常见场景](https://blog.csdn.net/qq_16268979/article/details/123707823?spm=1001.2101.3001.6650.2&utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-2-123707823-blog-124531638.topnsimilarv1&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-2-123707823-blog-124531638.topnsimilarv1&utm_relevant_index=5)

> ## POST和GET有哪些区别？各自应用场景？（[相关链接](https://blog.csdn.net/weixin_43595755/article/details/121877022)）
> + ## 场景：GET 用于获取资源，查询数据，而 POST 用于传输实体主体，修改数据。
> + ## GET
> + GET请求的数据是放在HTTP包头中的，也就是URL之后。GET 的参数是以查询字符串出现在 URL 中。
> + GET提交的数据比较少，最多1024B，而POST可以传送更多的数据。
> + 使用Get时，参数数据是明文传输的，而且使用GET的话，还可能造成Cross-site request forgery攻击，但GET的速度可能会快些。
> + GET请求是安全且幂等的。
> + ## POST
> + Post是把提交的数据放在HTTP正文中的, POST 的参数存储在实体主体中
> + Post的安全性要比Get高，而且POST数据则可以加密的，但GET的速度可能会快些。
> + POST请求是不安全且不幂等的，因为是新增或者提交数据的操作，会修改服务器上的资源，且多次提交数据就会创建多个资源。
> + ## HTTP协议中，除了GET和POST还有什么请求？（[相关链接](https://blog.csdn.net/weixin_42220532/article/details/104411061)）
> + OPTIONS:向Web服务器发送OPTIONS请求，可以测试服务器功能是否正常运作
> + HEAD:与GET方法一样，都是向服务器发出指定资源的请求。它的好处在于，使用这个方法可以在不必传输全部内容的情况下，就可以获取其中“关于该资源的信息”（元信息或称元数据）。
> + GET:向指定的资源发出“显示”请求。使用GET方法应该只用在读取数据。
> + POST:向指定资源提交数据，请求服务器进行处理（例如提交表单或者上传文件）。
> + PUT:向指定资源位置上传其最新内容。
> + DELETE:请求服务器删除Request-URI所标识的资源
> + TRACE:回显服务器收到的请求，主要用于测试或诊断
> + CONNECT:HTTP/1.1协议中预留给能够将连接改为管道方式的代理服务器。通常用于SSL加密服务器的链接

> ## Jrestcontroller和controller区别是什么?
> + 1.用Controller配合视图解析器才能返回到指定页面。在对应的方法上加上ResponseBody注解才能返回JSON，XML或自定义mediaType的内容到页面。
> + 2.不可以只用RestController注解Controller，因为这样会让Controller中的内容不能返回jsp页面，而且会直接返回Return里的内容。
> + 3.RestController相当于Controller和ResponseBod两者合并起来的作用。
> + [JAVA对数据按照日期排序，同一天为一组](https://blog.csdn.net/dadada_youzi/article/details/109092639)

> ## JAVA常见的异常
> + Runtime Exception、Exception、NullPointerException（空指针）、NegativeArrayException（数组下标）、IOException、SQLException（[Java常见异常种类](https://www.cnblogs.com/haoxiaonan/p/15639180.html)）

> ## String字符串
> + ## String常用方法（[相关链接](https://blog.csdn.net/m0_46400910/article/details/122361749)）
> + length（长度）、isEmpty（是否为空）、trim（去空格）、equals（比较）、substring（字符串拼接）、replace（字符串替换）
> + ##  eqsuls和==的区别与使用场景（[相关链接](https://blog.csdn.net/qq_33290787/article/details/51810529)）
> + ==：基本数据类型比较的是值或地址，引用数据类型比较的是地址。
> + equals：在不重写的情况下，和==没有任何区别，重写，可以自定义比较规则，一般重写之后都让其比较值。
> + 使用场景：
> + ==：若是两个基本数据类型的比较，例如int a = 1，b = 2；比较a是否等于b。使用==
> + equals：若是比较两个字符串，直接用equals()方法。
> + ## String、StringBuilder、StringBuff区别（[相关链接](https://blog.csdn.net/weixin_52237268/article/details/123051758)）
> + String：String类型的字符串具有不可变性，它所具有的方法无法修改原来的字符串，只能用新的字符串来接受修改结果
> + StringBuff：StringBuff的方法有synchronized修饰，所以“线程”安全，但性能差。一般修改到字符串的时候使用StringBuff可以无需考虑线程安全的问题。
> + StringBuilder：StringBuilder的方法没有synchronized修饰，所以具有“线程”不安全性，但性能好。

> ## 知识点
> + [分布式架构知识体系](https://blog.csdn.net/IT1124/article/details/122384828)
> + [JAVA高效率 (秒级) 将千万条数据导入数据库 ](https://blog.csdn.net/m0_55710969/article/details/121117481)

## Mybatis
> ## MyBatis缓存（[相关链接](https://blog.csdn.net/weixin_47404925/article/details/123113600)）
> + 一级缓存：同一个 SqlSession 对象， 在参数和 SQL 完全一样的情况下， 只执行一次 SQL 语句 （前提缓存没有过期）
> + 二级缓存：Mybatis的二级缓存是指mapper映射文件。二级缓存的作用域是同一个namespace下 的mapper映射文件内容，多个SqlSession共享。
> + ## Mybatis的一级、二级缓存（存储结构、范围、失效场景）（[相关链接](https://blog.csdn.net/weixin_42495773/article/details/106799297)）
> + 一级缓存：Mybatis的一级缓存是指SqlSession级别的，作用域是SqlSession，Mybatis默认开启一级缓存，在同一个SqlSession中，相同的Sql查询的时候，第一次查询的时候，就会从缓存中取，如果发现没有数据，那么就从数据库查询出来，并且缓存到HashMap中，如果下次还是相同的查询，就直接从缓存中查询，就不在去查询数据库，对应的就不在去执行SQL语句。当查询到的数据，进行增删改的操作的时候，缓存将会失效。在spring容器管理中每次查询都是创建一个新的sqlSession，所以在分布式环境中不会出现数据不一致的问题
> + 二级缓存：二级缓存是mapper级别的缓存，多个SqlSession去操作同一个mapper的sql语句，多个SqlSession可以共用二级缓存，二级缓存是跨SqlSession。第一次调用mapper下的sql 的时候去查询信息，查询到的信息会存放到该mapper对应的二级缓存区域，第二次调用namespace下的mapper映射文件中，相同的SQL去查询，回去对应的二级缓存内取结果，使用值需要开启cache标签，在select上添加useCache属性为true，在更新和删除时候需要手动开启flushCache刷新缓存。

> ## Mybatis基础使用
> + [mybatis 批量更新update详解](https://blog.csdn.net/yjaspire/article/details/81316885) 

## Mybaits-Plus
> + [Mybaits-Plus官网](https://baomidou.com/)
> + [Mybatis-plus开启sql日志打印](https://blog.csdn.net/qq_41995919/article/details/124994808)

## 数据库工具Navicat
> + [Navicat](http://www.navicat.com.cn/download/navicat-for-mysql)
> + [Navicat 16 破解](https://songzixian.com/javatool/1832.html)
> + [Navicat 导入dmp文件](https://blog.csdn.net/logwto/article/details/126222586)
> + [Navicat Mysql 字段设置默认时间与修改默认更新时间](http://t.zoukankan.com/sands-p-10442067.html)


## 数据库工具PLSQL
> + [PLSQL官方下载](https://www.allroundautomations.com/registered-plsqldev/)
> + [PLSQL设置中文字体](https://jingyan.baidu.com/article/d5c4b52b8b6e449b560dc5ad.html)
> + [PLSQL14-15版本破解码](https://www.cnblogs.com/Fzzf1/p/16570969.html)
> + product code: ke4tv8t5jtxz493kl8s2nn3t6xgngcmgf3
> + serial Number: 264452
> + password: xs374ca


## Mysql
> ## union默认是并集去重,union all是并集不去重

> ## 索引是一种排好序快速查找数据结构
> + ## Mysql索引口诀
> + 带头大哥不能死，中间兄弟不能断，索引列上不计算（!=或<>等等），like%加右边，范围（or）之后全失效，varchar引号不能丢
> + 索引失效会导致行锁变表锁。
> + ## 索引种类
> + 通索引、唯一索引、主键索引、组合索引、全文索引

> ## 数据库建表原则
> + 第一范式:确保每一列的原子性（做到每列不可拆分）
> + 第二范式:在第一范式的基础上，非主字段必须依赖于主字段（一个表只做一件事）
> + 第三范式:在第二范式的基础上，消除传递依赖(任何非主属性不依赖于其它非主属性)
> + 反三范式:反三范式是基于第三范式所调整的，没有冗余的数据库未必是最好的数据库，有时为了提高运行效率，就必须降低范式标准，适当保留冗余数据。

> ## MySQL内连接、左连接、右连接是什么，他们的差别，以及性能比较（[相关链接](https://blog.csdn.net/weixin_44185561/article/details/102451307)）
> + left join（左连接）:返回左表中的所有记录和右表中连接字段相等的记录。左表内容全查；右表查出没有与其对应的数据用null去填补。（以左表为参照显示数据；）
> + right join（右连接）：返回右表中的所有记录和左表中连接字段相等的记录。右表内容全查；左表查出没有与其对应的数据用null去填补。（以右表为参照显示数据；）
> + inner join（内连接）：只返回两个表中连接字段相等的行。只有两张表都匹配的行才会被显示。（显示两个表中有联系的所有数据；）
> + full join（全外连接）：返回左右表中所有的记录和左右表中连接字段相等的记录。互相之间谁没有数据就拿null去填。
> + union / union all（全连接）：显示两个表中所有数据，除被合并的列以外元素值相等只显示一行数据，值不等显示多行数据。
> + ## 性能比较（[相关链接](https://blog.csdn.net/weixin_35640856/article/details/76515968)）
> + 左连接>内连接：是因为left时，数据库在执行时，left左边的表是被优化执行的，因为left左边的表被无条件返回，left右边的表对结果集不存在影响。 但是inner的时候， 就需要对数据进行过滤。 所以速度会慢。

> ## 1.mysql相关内容
> + [Mysql官网](https://www.mysql.com/)
> + [MYsql官方下载](https://downloads.mysql.com/archives/installer/)
> + [MySQL安装及配置教程](https://blog.csdn.net/weixin_50498482/article/details/124315351)
> + [linux环境中执行Mysql脚本](https://www.cnblogs.com/bulesea/p/16490020.html)
> + [关于sql和MySQL的语句执行顺序(1.from、2.on、3.join、4.where、5.group by、6.avg,sum...、7.having、8.select、9.distinct、10.order by、11.limit)](https://blog.csdn.net/u014044812/article/details/51004754/)
> ## 2.Mysql调优
> + [MySQL-Explain详解](https://blog.csdn.net/fsdfkjai/article/details/121770629)
> + [Mysql高级篇-调优（视频教学）](https://www.bilibili.com/video/BV1KW411u7vy?p=14&vd_source=4f10ac1b3ab764a60d843b3bf8c01963)
> + [Mysql慢查询日志](https://blog.csdn.net/chengqiuming/article/details/120402562)
> + [MySQL 高级sql调优之 Show Profile](https://blog.csdn.net/lovelichao12/article/details/124087933)
> ## 3.mysql常见问题解决方案
> + [连接Mysql出现时区对不上(The server time zone value '?й???????')报错](https://blog.csdn.net/mk1843109092/article/details/102652767)
> + [MySQL错误ERROR 1046 (3D000): No database selected解决方案](https://blog.csdn.net/qq_43128354/article/details/120081214)
> + [MySQL数据库安装步骤及报错1251解决方案](https://blog.csdn.net/weixin_53182715/article/details/123591762)


## Oracle
> + ## Oracle常见问题
> + [删除表或存储过程函数等出现ERROR：ORA-04098问题解决（alter system set "_system_trig_enabled"=FALSE;）](https://blog.csdn.net/cuibai1991/article/details/100330900)
> + ## 1.Oracle官网、下载、安装
> + [Oracle官网](https://www.oracle.com/downloads/)
> + [oracle 11g安装教程完整版](https://blog.csdn.net/qq_18854761/article/details/121379382)
> + [安装oracle11g时遇到环境不满足最低要求](https://blog.csdn.net/lh756437907/article/details/97138315)
> + [安装ORACLE时出现This test checks whether the length of the environment variable “PATH“ does not exceed th](https://blog.csdn.net/u010291898/article/details/124765003)
> + [Oracle instant Client下载](https://www.oracle.com/database/technologies/instant-client/winx64-64-downloads.html#ic_winx64_inst)
> + [Ora 28547连接服务器失败问题详解](https://blog.csdn.net/qq_38149535/article/details/107733554)
> + ## 2.Oracle基础命令、新增用户、解锁用户等
> + [Oracle创建用户、角色、授权、建表](https://blog.csdn.net/zhao05164313/article/details/124172838)
> + [Oracle创建用户过程详解](https://www.jb51.net/article/219713.htm)
> + [Oracle 11g中 ORA-28000 账号被锁定的解决办法](https://blog.csdn.net/weixin_43199692/article/details/125244838)
> + [Oracle 11g中 system账号被锁定无法解锁时可用sys用户解锁](https://blog.csdn.net/u012004128/article/details/80781979)


## Linux相关工具安装与配置
> ## 1.VMware破解版下载、安装
> + [VMware Workstation Pro v16.2.0 官方完整版(附永久激活密钥)](http://www.usbmi.com/932.html)
> ## 2.Linux下载
> + [Linux安装PCRE依赖](https://sourceforge.net/projects/pcre/files/pcre/)
> + [Linux安装Nginx](https://www.bilibili.com/video/BV1zJ411w7SV?p=5&spm_id_from=333.880.my_history.page.click)
> + [CentOS7安装MySQL8.0.28(视频教学)](https://www.bilibili.com/video/BV1qS4y1h77S?spm_id_from=333.337.search-card.all.click&vd_source=4f10ac1b3ab764a60d843b3bf8c01963)
> ## 3.Linux配置
> + [Linux-centos设置静态IP](https://blog.csdn.net/weixin_55821558/article/details/123819702)
> + [Linux-centos设置静态IP（视频教学）](https://www.bilibili.com/video/BV1WY4y1H7d3?p=21&vd_source=4f10ac1b3ab764a60d843b3bf8c01963)
> ## 4.Linux常用命令
> + netstat -tunlp 查端口号进程可以加上 netstat -tunlp | grep 要查的端口号
> + [Linux目录解析之/usr与/opt与/dev](https://blog.csdn.net/w2009211777/article/details/123853355)
> + [Linux中常用命令](https://blog.csdn.net/qq_40649503/article/details/123677656)
> + [Linux-vim快捷键](https://blog.csdn.net/sinat_36670490/article/details/118500419)
> ## Linux运维
> + Linux上部署项目命令：nohup java -jar jar包所在路径/xxx.jar > 要放日志文件的地址/.log &
> + [Linux常用命令学习---将项目部署到测试环境的几个常用命令](https://blog.csdn.net/sunshine_girl_huihui/article/details/123665139)
> + [如何在Linux上部署项目](https://blog.csdn.net/weixin_42333933/article/details/125722318)


## Docker镜像
> ## 1.Docker入门
> + [DockerHub官方容器镜像查找](https://hub.docker.com/search?q=tomcat)
> + [Docker学习流程](https://blog.csdn.net/qq_46122292/article/details/124961251)
> ## 2.Docker安装
> + [Centos7安装Docker官方文档](https://docs.docker.com/engine/install/centos/)
> + [Docker安装视频教学](https://www.bilibili.com/video/BV1gr4y1U7CY?p=11&spm_id_from=333.880.my_history.page.click&vd_source=4f10ac1b3ab764a60d843b3bf8c01963)
> ## 3.Docker常用命令
> + [Dockerch常用命令](https://blog.csdn.net/leilei1366615/article/details/106267225)
> + Docker提交命令docker commit -m="vim cmd add" -a="XZBW" 094372cb612b xzbw/myubuntu1.1
> + docker commit -m="描述" -a="作者" 容器名/容器ID 储存库名（注：储存库名必须小写 xzbw/myubuntu1.1）
> ## 4.Docker容器数据卷
> + [docker 容器数据卷](https://blog.csdn.net/weixin_44830725/article/details/124317903)
> ## 5.Dockerfile
> + [Dockerfile保留字和使用DockerFile构建镜像](https://blog.csdn.net/Session_s/article/details/120147613)
> + [Dockerfile保留字详解](https://blog.csdn.net/weixin_38299159/article/details/120429294)
> + [Dockerfile保留字简介](https://www.cnblogs.com/asxf/p/11214003.html)
> + [自定义Dockerfile搭建centos7容器Failed to download metadata for repo ‘appstream‘: Cannot prepare internal mirrorlist报错解决](https://blog.csdn.net/m0_47860792/article/details/123659933)
> + [Dockerfile发布jar服务部署到docker容器](https://www.bilibili.com/video/BV1gr4y1U7CY?p=64&vd_source=4f10ac1b3ab764a60d843b3bf8c01963)
> + [外部链接docker-Mysql5.7 解决2003错误](https://www.php.cn/docker/493657.html)
> ## 6.Docker network
> + [Docker network容器网络](https://blog.csdn.net/qq_42418169/article/details/119102917)
> ## 7.Docker compose
> + [Docker compose官方文档（版本介绍）](https://docs.docker.com/compose/compose-file/compose-file-v3/)
> + [Docker下载安装docker-compose插件](https://docs.docker.com/compose/install/compose-plugin/)
> + [Docker离线下载安装docker-compose插件github](https://github.com/docker/compose/releases)
> + [Docker-Compose安装、卸载、使用详解](https://blog.csdn.net/m0_67403076/article/details/124512737)
> ## 8.Docker portainer
> + [Docker portainer 轻量级可视化应用-管理docker](https://www.portainer.io/)
> + [Docker portainer 下载（官方文档）](https://docs.portainer.io/v/be-2.10/start/install/server/docker/linux)
> ## 9.Docker-CIG容器监控
> + [Docker微服务-CIG容器监控搭建](https://blog.csdn.net/u014225032/article/details/125232424)
> + [Docker微服务-CIG容器监控搭建（视频教学）](https://www.bilibili.com/video/BV1gr4y1U7CY?p=91&vd_source=4f10ac1b3ab764a60d843b3bf8c01963)

## Redis
> ## Redis事务三大特性
> + 1.单独的隔离操作（事务中所有命令都会序列化、按顺序执行。不会被其他请求打断。）
> + 2.没有隔离级别的概念（队列中的命令没有提交之前都不会实际被执行，因为事务提交前任何指令都不会被实际执行）
> + 3.不保证原子性（事务中如果有一条命令执行失败，其后的命令仍然会被执行，没有回滚）
> ##
> + Redis属于NoSQL（非关系型数据库）常见的NoSQL有Redis、MongoDB、HBase、Neo4j(图形数据库)
> + Redis属于单线程操作也叫作原子操作，不会被线程调度机制打断的操作。（多线程中不能被其他线程打断就叫做原子操作）
> + Redis集群有16384个哈希槽
> + Redis集群的优点：（实现扩容、分摊压力、无中心配置相对简单）
> + Redis集群的缺点：（不支持多key操作、不支持多key的redis事务lua脚本不支持）
> ## 1.Redis下载
> + [Redis下载](http://redis.io/download)
> ## 2.Redis常用命令及“5种基础”数据类型+“3种特殊”数据类型介绍及相关命令与数据结构
> + [Redis常用命令](https://blog.csdn.net/weixin_60610547/article/details/125438883)
> + [Redis常用五大数据类型（string、list、set、Hash、Zset）与对应数据结构及相关命令详解](https://blog.csdn.net/m0_62436868/article/details/125241549)
> + [Redis“5种基础”数据类型+“3种特殊”数据类型（bitmaps位操作字符串、hyperloglog基数运算、geospatial根据地理信息经纬度运算）介绍及相关命令](https://baijiahao.baidu.com/s?id=1709170155160213718&wfr=spider&for=pc)
> ## 3.Redis事务
> + [Redis事务的概念与相关命令[multi(标记开始事务)、exec(执行事务)、discard(取消事务)]](https://blog.csdn.net/weixin_37548768/article/details/124538778)
> + [Redis—“事务“Lua脚本](https://blog.csdn.net/minghao0508/article/details/123895579)
> + [Redis执行lua脚本](https://blog.csdn.net/weixin_46099269/article/details/124889829)
> ## 4.Redis持久化RDB和AOF
> + [Redis持久化：RDB和AOF](https://blog.csdn.net/chairongdian/article/details/124852514)
> + [Redis的两种持久化RDB和AOF](https://blog.csdn.net/weixin_52489114/article/details/123011362)
> + [Redis持久化AOF文件损坏修复](https://blog.csdn.net/qq_44813596/article/details/123528332)
> ## 5.Redis主从架构与哨兵模式
> + [Redis 集群 主从模式(在从机上执行slaveof 主机ip 端口号)](https://blog.csdn.net/zhangxueleishamo/article/details/121470922)
> + [Redis主从架构和哨兵架构模式](https://blog.csdn.net/weixin_38192427/article/details/108458490)
> + [Redis集群+哨兵模式](https://blog.csdn.net/hyj_king/article/details/105145196)
> ## 6.Redis问题（缓存穿透、缓存击穿、缓存雪崩）
> + [Redis缓存穿透、缓存击穿、缓存雪崩解决方案](https://zhuanlan.zhihu.com/p/359118610)
> ## 什么是缓存穿透？
> + 访问一个缓存和数据库都不存在的 key，此时会直接打到数据库上，并且查不到数据，没法写缓存，所以下一次同样会打到数据库上。此时，缓存起不到作用，请求每次都会走到数据库，流量大时数据库可能会被打挂。此时缓存就好像被“穿透”了一样，起不到任何作用。
> + ## 解决方案：
> + 1、接口校验。在正常业务流程中可能会存在少量访问不存在 key 的情况，但是一般不会出现大量的情况，所以这种场景最大的可能性是遭受了非法攻击。可以在最外层先做一层校验：用户鉴权、数据合法性校验等，例如商品查询中，商品的ID是正整数，则可以直接对非正整数直接过滤等等。
> + 2、缓存空值。当访问缓存和DB都没有查询到值时，可以将空值写进缓存，但是设置较短的过期时间，该时间需要根据产品业务特性来设置。
> + 3、布隆过滤器。使用布隆过滤器存储所有可能访问的 key，不存在的 key 直接被过滤，存在的 key 则再进一步查询缓存和数据库。
> ## 什么是缓存击穿？
> + 某一个热点 key，在缓存过期的一瞬间，同时有大量的请求打进来，由于此时缓存过期了，所以请求最终都会走到数据库，造成瞬时数据库请求量大、压力骤增，甚至可能打垮数据库。
> + ## 解决方案：
> + 1、加互斥锁。在并发的多个请求中，只有第一个请求线程能拿到锁并执行数据库查询操作，其他的线程拿不到锁就阻塞等着，等到第一个线程将数据写入缓存后，直接走缓存。
> + 2、热点数据不过期。直接将缓存设置为不过期，然后由定时任务去异步加载数据，更新缓存。
> ## 什么是缓存雪崩？
> + 大量的热点 key 设置了相同的过期时间，导在缓存在同一时刻全部失效，造成瞬时数据库请求量大、压力骤增，引起雪崩，甚至导致数据库被打挂。缓存雪崩其实有点像“升级版的缓存击穿”，缓存击穿是一个热点 key，缓存雪崩是一组热点 key。
> + 1、过期时间打散。既然是大量缓存集中失效，那最容易想到就是让他们不集中生效。可以给缓存的过期时间时加上一个随机值时间，使得每个 key 的过期时间分布开来，不会集中在同一时刻失效。
> + 2、设置过期标志更新缓存，记录缓存数据是否过期（设置提前量），如果过期会触发通知另外的线程在后台去更新实际的key的缓存。
> + 3、加互斥锁。该方式和缓存击穿一样，按 key 维度加锁，对于同一个 key，只允许一个线程去计算，其他线程原地阻塞等待第一个线程的计算结果，然后直接走缓存即可。
> ## 7.Redis分布式锁
> + [Redis实现分布式锁](https://blog.csdn.net/Me_xuan/article/details/124418176)
> + ## 如何避免死锁？锁的过期时间如何设置？
> + 设置锁同时设置过期时间：set k1 v1 nx ex 10（set key value nx设置锁 ex设置超时 10超时时间设置/秒）
> + ## 为了确保分布式锁可用，至少要满足以下四个条件
> + 1.互斥性：在任意时刻，只有一个客户端能持有锁。
> + 2.不会发生死锁：设置锁的同时设置过期时间保证不会死锁。（设置锁时同时设置超时时间）
> + 3.加锁解锁都必须是同一个客户端，客户端自己不能把别人加的锁给解了。（使用uuid）
> + 4.加锁和解锁都必须具有原子性（可以使用lua脚本执行）
> ## Redis新功能之ACL、IO多线程（IO多线程只是用来处理网络数据的读写和协议解析，执行命令仍然是单线程）
> + [Redis之ACL](https://blog.csdn.net/qq_21335855/article/details/121783765)
> + [Redis 6.0 访问控制列表ACL说明](https://blog.csdn.net/qq_29235677/article/details/121475204)
> + [redis io多线程](https://blog.csdn.net/congchp/article/details/122740115)
> + [redis7.0源码阅读：Redis中的IO多线程（线程池）](https://zhuanlan.zhihu.com/p/527166907)
> 

## Spring-Cloud
> ## 1.官方文档
> + [Spring-Cloud官方文档](https://spring.io/projects/spring-cloud/)
> + [Spring-Cloud-ALibaba官方文档](https://spring.io/projects/spring-cloud-alibaba)
> + [spring-cloud组件版本关系说明](https://github.com/alibaba/spring-cloud-alibaba/wiki/%E7%89%88%E6%9C%AC%E8%AF%B4%E6%98%8E)

## Spring-Cloud-ALibaba(Nacos服务注册发现)
> ## 什么是Nacos
> + Nacos的就是一个注册中心,用来发现、配置和管理微服务。
> ## 1.Nacos文档、下载
> + [Nacos中文官网](https://nacos.io/zh-cn/)
> + [Nacos1.4.3下载](https://github.com/alibaba/nacos/releases/tag/1.4.3)
> > ## 2.Nacos配置、启动、部署、nacos持久化配置
> + [Nacos集群与单机切换（可解决db.num is null报错）](https://blog.csdn.net/zhangsann_6/article/details/121443435)
> + [Nacos的AP与CP模式的切换](https://blog.csdn.net/jmysql/article/details/123827680)（Consistency（一致性）、 Availability（可用性）、Partition tolerance（分区容错性））
> + [Nacos配置Mysql的相关配置](https://blog.csdn.net/qq_21299835/article/details/120935616)
> + [Nacos+Mysql部署环境(单机、集群、多集群)](https://nacos.io/zh-cn/docs/deployment.html)

## Sentinel分布式系统的流量防卫兵(面向分布式的轻量级高可用流量控制组件)
> ## 1.Sentine文档、下载、启动
> + [Sentinel中文文档介绍](https://github.com/alibaba/Sentinel/wiki/%E7%83%AD%E7%82%B9%E5%8F%82%E6%95%B0%E9%99%90%E6%B5%81)
> + [Sentinel下载](https://github.com/alibaba/Sentinel/releases)
> + [Sentinel的启动与运行](https://blog.csdn.net/qq_42393720/article/details/122213922)
> ## 2.Sentine的使用（流控、热点、熔断）与Nacos持久化
> + [Sentinel流控、热点、熔断(操作详解)](https://blog.csdn.net/guan1843036360/article/details/124241795)
> + [Sentinel流控、热点、熔断(视频教学)](https://www.bilibili.com/video/BV18E411x7eT?p=115&spm_id_from=333.788.top_right_bar_window_history.content.click&vd_source=4f10ac1b3ab764a60d843b3bf8c01963)
> + [sentinel持久化到Nacos](https://blog.csdn.net/qq_40777074/article/details/106860713)

## Seata开源分布式事务解决方案
> ## 什么是Seata
> Seata是由1加3的组件组成，1是指全局唯一事务ID，3是指三大组件TC事务协调（维护全局事务状态）,TM(控制全局事务发起最终提交或者回滚).RM(控制分支事务，负责分支注册协调)
>
> ## Seata工作流程
> 1.TM向TC申请开启一个全局事务，全局事务创建成功并生成一个全局唯一的XID;
> 
> 2.XID在微服务调用链路的上下文中传播;
> 
> 3.RM向TC注册分支事务，将其纳入XID对应全局事务的管辖;
> 
> 4.TM向TC发起针对XID的全局提交或回滚决议;
> 
> 5.TC调动XID下管辖的全部分支事务完成提交或回滚请求;
> ## 使用方式
> @GlobalTransactional注解在方法上
> ## 1.Seata官网文档
> + [Seata官网](https://seata.io/zh-cn/)
> + [Seata官方文档](https://seata.io/zh-cn/docs/overview/what-is-seata.html)
> ## 2.Seata下载、安装、部署
> + [Seata下载](https://github.com/seata/seata/tags)
> + [Seata部署所需建表sql](https://blog.csdn.net/weixin_49686768/article/details/118057890)
> ## 3.Seata + nacos搭建
> + [Seata1.5版本搭建,结合nacos](https://www.jianshu.com/p/37c3640284cc)
> + [Seata1.5版本搭建Could not create connection to database server解决方法](https://blog.csdn.net/NO1_UNDERDOG/article/details/110675147)
> + [Seata0.9.0版本搭建Could not create connection to database server解决方法](https://blog.csdn.net/stephen_curry300/article/details/121585707)


## Node.js
> + [Nodejs详细安装+环境配置](https://www.cnblogs.com/wanpi/p/16119433.html)
> + [解决Node js error -4048错误](https://blog.csdn.net/qq_44824148/article/details/112556127)

## Vue


