

# 	eat-distribution

小白的 分布式 学习之路

> 寻找了快5年，才发现这才是自己最热爱的方向，冲冲冲



## 分布式算法

- [x] 1 basic
- [x] 2 分布式协调与同步
  - [x] 分布式互斥
  - [x] 分布式选举
  - [x] 分布式共识
  - [x] 分布式事务



## 网络

- [x] HTTP
  - [x] 发展历程
  - [x] 网络模型
  - [x] 域名
  - [x] 报文结构
  - [x] 请求方法
  - [x] URI
  - [x] 响应状态码
  - [x] HTTP的优缺点
  - [x] HTTP的实体数据
  - [x] HTTP传输大文件的方法
  - [x] HTTP连接管理
  - [x] HTTP的重定向和跳转
  - [x] HTTP的Cookie机制
  - [x] HTTP的缓存控制
  - [x] HTTP的代理服务
  - [x] HTTP的缓存代理
  - [x] HTTPS与SSL/TLS
  - [x] 对称加密与非对称加密
  - [x] 数字签名与证书

  > skip

  - [ ] TLS1.2连接过程解析
  - [ ] TLS1.3特性解析
  - [ ] HTTPS的优化
  - [ ] HTTPS迁移

  > skip end

  - [x] HTTP2特性
  - [x] HTTP2内核剖析
  - [x] HTTP3
  - [x] HTTP2迁移
  - [x] WebSocket
  - [x] HTTP优化



**面试题重构**

- OSI与TCP/IP协议族

  - 协议族各层的结构与功能？
  - 各层的主要协议及其功能？
  - 在浏览器中输入url地址到显示主页的过程？

- HTTP

  







## 微服务



## 鉴权



## 服务发现



## Kafka



## Spring



## Spring boot



## Spring cloud



## Dubbo



## Redis



## JVM

- 



## Mysql

- [x] 1 基础架构
  - [x] MySQL框架有几个组件, 各有什么作用?（一句SQL的执行流程）
  - [x] Server层和存储引擎层各有什么作用?
  - [x] 长连接和短链接的区别和应用场景？
  - [x] 对于表的操作权限验证在哪里进行?
  - [x] 在词法分析和语法分析阶段分别会做什么？
- [x] 2 日志系统
  - [x] redo log的是什么? 为什么会存在？
  - [x] 如果数据库误操作, 如何执行数据恢复?
  - [x] 什么是两阶段提交？为什么需要两阶段提交？两阶段提交怎么保证数据库中两份日志间的逻辑一致性?
  - [x] 如果不是两阶段提交, 先写redolog和先写binlog两种情况各会遇到什么问题?
- [x] 3 事务隔离
  - [x] 事务的概念是什么？
  - [x] 事务隔离级别读未提交, 读已提交, 可重复读, 串行各是什么?
  - [x] 事务隔离是怎么通过read-view(读视图)实现的?
  - [x] 可重复读的使用场景举例? 
  - [x] 事务的启动方式有哪几种?
  - [x] 长事务
    - [x] 使用长事务有什么弊病? 
    - [x] 如何避免长事务的出现？
    - [x] 怎么查询各个表中的长事务?
    - [x] commit work and chain 语法是做什么用的?
- [x] 04-05 索引
  - [x] 索引的常见模型
  - [x] InnoDB的索引模型
  - [x] 索引维护
  - [x] 覆盖索引
  - [x] 最左前缀原则
  - [x] 索引下推
- [x] 06 全局锁和表锁
  - [x] MySQL从加锁范围上分为哪三类?
  - [x] 全局锁加锁方法的执行命令是什么?主要的应用场景是什么?
  - [x] 做整库备份时为什么要加全局锁?
  - [x] MySQL的自带备份工具, 使用什么参数可以确保一致性视图, 在什么场景下不适用?
  - [x] 不建议使用set global readonly = true的方法加全局锁有哪两点原因?
  - [x] 表级锁有哪两种类型? 各自的使用场景是什么?
  - [x] MDL中读写锁之间的互斥关系怎样的?
  - [x] 如何安全的给小表增加字段?

- [x] 07 行锁
  - [x] 两阶段锁的概念是什么？对事务使用有什么帮助？
  - [x] 死锁的概念是什么？举例说明出现死锁的情况
  - [x] 死锁的处理策略有哪两种？
  - [x] 等待超时处理死锁的机制是什么？有什么局限？
  - [x] 死锁检测的机制是什么？有什么局限？
  - [x] 有哪些思路可以解决热点更新导致的并发问题？
- [ ] 08 事务隔离
- [ ] 09 普通索引和唯一索引，应该怎么选择？



SQL

- [x] 01 了解SQL
- [x] 02 DBMS的前世今生
- [x] 03 SQL是如何执行的
- [x] 04 使用DDL创建数据库&数据表时需要注意什么？
- [x] 05 检索数据
- [x] 06 数据过滤







## 并发





## Flink