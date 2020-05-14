# my-blogs
 一些关于技术的博客

## 理论
* 操作系统
    * 文件系统
    * 进程线程
    * 内存管理
* 计算机网络
* 数据结构与算法
* 数据库
    * mysql
    * redis
    * es
* 分布式
    * 分布式算法与理论
        * CAP
        * 2pc/3pc
        * raft
        * paxos
    * 分布式中间件
        * [zookeeper](https://zookeeper.apache.org/)
        * RPC
        * seata
* 设计模式
* JAVA
    * 集合
    * 并发
    * IO/NIO/Netty
    * JVM
    * spring
    * servlet服务器: tomcat

## 技术栈
* 登录认证
    * spring-security-oauth2
* 数据源
    * [hikariCP](https://github.com/brettwooldridge/HikariCP)
* 分库分表
    * [sharding-jdbc](https://shardingsphere.apache.org/document/current/cn/manual/sharding-jdbc/)
* SOA
    * [sofastack](https://www.sofastack.tech/)
    * [spring-cloud-alibaba](https://github.com/alibaba/spring-cloud-alibaba)
    * [protobuf](https://developers.google.com/protocol-buffers)
* DB
    * [mysql](https://dev.mysql.com/doc/refman/5.7/en/select-benchmarking.html)
        * 解析binlog
            * maxwell
            * canal
    * [redis cluster](https://redis.io/topics/cluster-tutorial)
    * [elk](https://www.elastic.co/cn/)
* im
    * [goim](https://github.com/Terry-Mao/goim)
    * netty
* MQ
    * rocketmq
    * kafka
* 管理后台
    * [RuoYi](https://gitee.com/y_project/RuoYi)
* H5通信
    * websocket
* 定时器
    * xxl-job

## 一些有价值的设计方案
* 缓存
    * redis缓存更新的最佳实践
    * redis缓存穿透
    * redis hash存储的一些思考
    * [美团-聊聊MyBatis缓存机制](https://tech.meituan.com/2018/01/19/mybatis-cache.html)
* 交易
    * 如何避免重复下单
    * 账户以及账单表设计
* im
    * [服务器如何判断用户是否离线？](design/im/服务器如何判断用户是否离线.md)
    * [如何用redis存储在线用户列表？](http://blog.huangz.me/diary/2016/redis-count-online-users.html)
    * [微博-如何设计社交关系？](https://www.infoq.cn/article/weibo-relation-service-with-redis)

## 问题排查
* [线上Java应用CPU占用过高排查](java-blogs/线上Java应用CPU占用过高排查.md)
* [美团-常见性能优化策略的总结](https://tech.meituan.com/2016/12/02/performance-tunning.html)