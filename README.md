>不定期分享一些与后端相关不错的资源学习网站

## Markdown
- [Markdown语法](https://www.cnblogs.com/miki-peng/p/12502985.html)

## 社区
- [stackoverflow](https://stackoverflow.com/)
- [掘金](https://juejin.cn/)
- [NODE中文社区](https://cnodejs.org/)
- [Processon免费在线流程图思维导图](https://processon.com/)

## 数据库工具
> + [Navicat](http://www.navicat.com.cn/download/navicat-for-mysql)

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
> ## Rabbit面试题
> + [RabbitMQ面试题整理（含答案解析）](https://blog.csdn.net/m0_68102173/article/details/124299647)

## JAVA
> + ## 什么是序列化
> + 序列化： 将 java对象信息 转换成 二进制数据流的过程
> + 反序列化： 将 二进制数据流 转换成 java对象信息的过程
> + [分布式架构知识体系](https://blog.csdn.net/IT1124/article/details/122384828)
> ## Jrestcontroller和controller区别是什么?
> + 1.用Controller配合视图解析器才能返回到指定页面。在对应的方法上加上ResponseBody注解才能返回JSON，XML或自定义mediaType的内容到页面。
> + 2.不可以只用RestController注解Controller，因为这样会让Controller中的内容不能返回jsp页面，而且会直接返回Return里的内容。
> + 3.RestController相当于Controller和ResponseBod两者合并起来的作用。
> + [JAVA对数据按照日期排序，同一天为一组](https://blog.csdn.net/dadada_youzi/article/details/109092639)

## Mysql
> ## 1.mysql相关内容
> + [Mysql官网](https://www.mysql.com/)
> + [linux环境中执行Mysql脚本](https://www.cnblogs.com/bulesea/p/16490020.html)
> ## 2.mysql常见问题解决方案
> + [连接Mysql出现时区对不上(The server time zone value '?й???????')报错](https://blog.csdn.net/mk1843109092/article/details/102652767)
> + [MySQL错误ERROR 1046 (3D000): No database selected解决方案](https://blog.csdn.net/qq_43128354/article/details/120081214)
> + [MySQL数据库安装步骤及报错1251解决方案](https://blog.csdn.net/weixin_53182715/article/details/123591762)

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
> + [Linux目录解析之/usr与/opt与/dev](https://blog.csdn.net/w2009211777/article/details/123853355)
> + [Linux中常用命令](https://blog.csdn.net/qq_40649503/article/details/123677656)
> + [Linux-vim快捷键](https://blog.csdn.net/sinat_36670490/article/details/118500419)

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
          
 
