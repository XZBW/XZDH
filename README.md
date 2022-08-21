>不定期分享一些与后端相关不错的资源学习网站

## Markdown
- [Markdown语法](https://www.cnblogs.com/miki-peng/p/12502985.html)

## 社区
- [stackoverflow](https://stackoverflow.com/)
- [掘金](https://juejin.cn/)
- [NODE中文社区](https://cnodejs.org/)

## 数据库工具
> + [Navicat](http://www.navicat.com.cn/download/navicat-for-mysql)
## JAVA
> ## 什么是序列化
> 序列化： 将 java对象信息 转换成 二进制数据流的过程
>
> 反序列化： 将 二进制数据流 转换成 java对象信息的过程
>
> + [JAVA对数据按照日期排序，同一天为一组](https://blog.csdn.net/dadada_youzi/article/details/109092639)

## Mysql
> + [Mysql官网](https://www.mysql.com/)
> + [连接Mysql出现时区对不上(The server time zone value '?й???????')报错](https://blog.csdn.net/mk1843109092/article/details/102652767)
> + [MySQL错误ERROR 1046 (3D000): No database selected解决办法](https://blog.csdn.net/qq_43128354/article/details/120081214)
> + [linux环境中执行Mysql脚本](https://www.cnblogs.com/bulesea/p/16490020.html)

## Linux相关工具安装与配置
> 虚拟机
> + [VMware Workstation Pro v16.2.0 官方完整版(附永久激活密钥)](http://www.usbmi.com/932.html)
> + [Linux安装PCRE依赖](https://sourceforge.net/projects/pcre/files/pcre/)
> + [Linux安装Nginx](https://www.bilibili.com/video/BV1zJ411w7SV?p=5&spm_id_from=333.880.my_history.page.click)
> + [CentOS7安装MySQL8.0.28(视频教学)](https://www.bilibili.com/video/BV1qS4y1h77S?spm_id_from=333.337.search-card.all.click&vd_source=4f10ac1b3ab764a60d843b3bf8c01963)
> + [Linux-centos设置静态IP](https://blog.csdn.net/weixin_55821558/article/details/123819702)
> + [Linux-centos设置静态IP（视频教学）](https://www.bilibili.com/video/BV1WY4y1H7d3?p=21&vd_source=4f10ac1b3ab764a60d843b3bf8c01963)

> Linux相关内容
> + [Linux目录解析之/usr与/opt与/dev](https://blog.csdn.net/w2009211777/article/details/123853355)
> + [Linux中常用命令](https://blog.csdn.net/qq_40649503/article/details/123677656)
> + [Linux-vim快捷键](https://blog.csdn.net/sinat_36670490/article/details/118500419)

## Docker镜像
> + [Centos7安装Docker官方文档](https://docs.docker.com/engine/install/centos/)
> + [Docker安装视频教学](https://www.bilibili.com/video/BV1gr4y1U7CY?p=11&spm_id_from=333.880.my_history.page.click&vd_source=4f10ac1b3ab764a60d843b3bf8c01963)
> + [Dockerch常用命令](https://blog.csdn.net/leilei1366615/article/details/106267225)
> + Docker提交命令docker commit -m="vim cmd add" -a="XZBW" 094372cb612b xzbw/myubuntu1.1
> + docker commit -m="描述" -a="作者" 容器名/容器ID 储存库名（注：储存库名必须小写 xzbw/myubuntu1.1）
## Spring-Cloud
> 官方文档
> + [Spring-Cloud官方文档](https://spring.io/projects/spring-cloud/)
> + [Spring-Cloud-ALibaba官方文档](https://spring.io/projects/spring-cloud-alibaba)
> + [spring-cloud组件版本关系说明](https://github.com/alibaba/spring-cloud-alibaba/wiki/%E7%89%88%E6%9C%AC%E8%AF%B4%E6%98%8E)

## Spring-Cloud-ALibaba(Nacos服务注册发现)
> + [Nacos中文官网](https://nacos.io/zh-cn/)
> + [Nacos1.4.3下载](https://github.com/alibaba/nacos/releases/tag/1.4.3)
> + [Nacos集群与单机切换（可解决db.num is null报错）](https://blog.csdn.net/zhangsann_6/article/details/121443435)
> + [Nacos的AP与CP模式的切换](https://blog.csdn.net/jmysql/article/details/123827680)（Consistency（一致性）、 Availability（可用性）、Partition tolerance（分区容错性））
> + [Nacos配置Mysql的相关配置](https://blog.csdn.net/qq_21299835/article/details/120935616)
> + [Nacos+Mysql部署环境(单机、集群、多集群)](https://nacos.io/zh-cn/docs/deployment.html)

## Sentinel分布式系统的流量防卫兵(面向分布式的轻量级高可用流量控制组件)
> + [Sentinel中文文档介绍](https://github.com/alibaba/Sentinel/wiki/%E7%83%AD%E7%82%B9%E5%8F%82%E6%95%B0%E9%99%90%E6%B5%81)
> + [Sentinel下载](https://github.com/alibaba/Sentinel/releases)
> + [Sentinel的启动与运行](https://blog.csdn.net/qq_42393720/article/details/122213922)
> [Sentinel流控、热点、熔断(操作详解)](https://blog.csdn.net/guan1843036360/article/details/124241795)
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
> 
> + [Seata官网](https://seata.io/zh-cn/)
> + [Seata官方文档](https://seata.io/zh-cn/docs/overview/what-is-seata.html)
> + [Seata下载](https://github.com/seata/seata/tags)
> + [Seata部署所需建表sql](https://blog.csdn.net/weixin_49686768/article/details/118057890)
> + [Seata1.5版本搭建,结合nacos](https://www.jianshu.com/p/37c3640284cc)
> + [Seata1.5版本搭建Could not create connection to database server解决方法](https://blog.csdn.net/NO1_UNDERDOG/article/details/110675147)
> + [Seata0.9.0版本搭建Could not create connection to database server解决方法](https://blog.csdn.net/stephen_curry300/article/details/121585707)
          
