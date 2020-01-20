# 题库整理

**！！！重点复习JD上要求的知识点及简历上写到的知识点**

**推荐链接**
- [几率大的xxx面试题（含答案）](https://blog.csdn.net/Butterfly_resting/article/details/89704636)


## Java基础
## Java8新特性
## Java框架、类库及工具
### Spring
### SpringMVC
### SpringBoot
### MyBatis
### Spring Cloud
### Maven
### Swagger
### Netty
### Tomcat
### Jedis
### JConsole
### JetBrains IDEA
### FastJson
### Apache Common Utils
## JVM
## 并发
### 线程池
## 数据库
### MySQL
1. 什么是聚集索引和非聚集索引？
1. InnoDB为什么要用自增id作为主键？
1. 什么是分库分表？有什么优点？
1. 事务的ACID特性？
1. 事务带来的问题？
1. 事务的四种隔离级别？
1. MySQL默认的事务隔离级别？
1. MySQL常见的存储引擎InnoDB、MyISAM的区别及适用场景？
1. 数据库的三大范式？


#### SQL
#### 索引
#### 事务
#### 分库分表
### Redis
1. Redis的数据结构及应用场景？
1. 大量的key设置在同一时间过期，需要注意什么？
1. Redis分布式锁的实现方式
1. setnx后未成功执行expire（如进程挂掉），会出现什么情况，如何避免？
1. 如何找出以特定前缀开头的key列表？
1. 在正在线上服务的Redis上使用keys指令会有什么问题？
1. keys指令和scan指令的优缺点？
1. Redis如何实现异步队列，有哪些注意事项？
    两种方式：
    1. list  
    注意事项：pop无限轮询拉高CPU，线程一直阻塞导致的空闲连接被释放
    2. pub/sub
    优点：实现一生产者对多消费者的消息队列
    缺点：无重试、ACK等机制，可能丢失消息
1. Redis如何实现延时队列
1. Redis两种持久化方式及优缺点，最佳的持久化方式是？
1. Redis的Pipeline的优点及注意事项？和mset/mget的差别？
1. Redis如何保证高可用与扩展性？
1. Redis集群如何实现主从复制？
1. Redis相比Memcached有哪些优势？
1. Redis的数据淘汰策略有哪些？默认的策略是？
1. 一个字符串类型的值能存储最大容量是多少？
1. Redis和Redisson有什么关系？  
   Redisson是一个高级的分布式协调Redis的客户端，帮助用户在分布式环境中轻松实现一些Java的对象 
   (Bloom filter, BitSet, Set, SetMultimap, ScoredSortedSet, SortedSet, Map, ConcurrentMap, List, ListMultimap, Queue, BlockingQueue, Deque, BlockingDeque, Semaphore, Lock, ReadWriteLock, AtomicLong, CountDownLatch, Publish / Subscribe, HyperLogLog等)
1. Jedis和Redisson优缺点？
1. 什么是Redis哈希槽？  
   Redis集群没有使用一致性hash,而是引入哈希槽概念，Redis集群有16384个哈希槽（类似表分区），每个key通过CRC16校验后对16384取模来决定放置哪个槽，集群的每个节点负责一部分hash槽。
1. Redis集群写操作可能丢失吗？为什么？
1. 什么是缓存雪崩、缓存穿透、缓存预热、缓存击穿、缓存降级、缓存更新？
1. Redis为什么这么快？
1. Redis IO多路复用原理？
## Nginx
1. Nginx的优点？
2. Nginx性能为什么高？
3. 为什么要做动静分离？
4. 什么是负载均衡，有哪些负载均衡策略？
## Socket编程

## 消息队列
## 网络
### 协议
#### Http协议
#### UDP协议
#### TCP/IP协议
### 请求/响应
### 数据交换格式
#### JSON
#### XML
## 算法
## 测试
### 接口测试
### 压力测试
### 单元测试
## 版本控制
### Git
## Linux
### 文件管理
#### 文件查看
#### 文件编辑
### 网络命令
### 进程管理
### CPU
### 内存
### 定时任务
### 后台脚本
### 环境变量及host
## 软件设计
### 设计模式
### Restful接口设计
### 接口幂等性
## 软件架构
### 分布式
#### RPC
#### 分布式配置中心
#### 分布式锁
#### 分布式事务
#### 分布式缓存
#### 分布式链路追踪
#### 分布式配置中心
#### 分布式任务调度
#### Zk分布式协调工具
#### Elastic Stack分布式日志收集
#### 四七层负载均衡
### 微服务
#### 注册中心
#### 微服务网关
#### 服务限流
#### 服务降级熔断
#### 微服务监控
### 中台
### 容器
#### Docker
#### Kubernetes(K8s)
## 编程规范
