# 36tz_cn_290
扛得住的MySQL数据库架构
扛得住的MySQL数据库架构
👇👇👇👇👇👇👇👇点击下载地址👇👇👇👇👇👇👇
[![download](https://51xueit.vip/muke_img/5fcdf2d4098322fc05400304.jpg "下载地址")](http://www.36tz.cn "下载地址")
### 第1章 实例和故事 

#### 决定电商11大促成败的各个关键因素。
1-1 什么决定了电商双11大促的成败 (04:04)

1-2 在双11大促中的数据库服务器 (06:03)

1-3 在大促中什么影响了数据库性能 (07:55)

1-4 大表带来的问题 (14:13)

1-5 大事务带来的问题 (17:27)

1-6 【讨论题】在日常工作中如何应对高并发大数据量对数据库性能挑战

1-7 【讨论题】在MySQL中事务的作用是什么？


### 第2章 什么影响了MySQL性能 

#### 详细介绍影响性能各个因素，包括硬件、操作系统等等。
2-1 影响性能的几个方面 (04:08)

2-2 CPU资源和可用内存大小 (10:54)

2-3 磁盘的配置和选择 (04:44)

2-4 使用RAID增加传统机器硬盘的性能 (11:30)

2-5 使用固态存储SSD或PCIe卡 (08:35)

2-6 使用网络存储SAN和NAS (07:16)

2-7 总结：服务器硬件对性能的影响 (03:27)

2-8 操作系统对性能的影响-MySQL适合的操作系统 (03:50)

2-9 CentOS系统参数优化 (11:43)

2-10 文件系统对性能的影响 (03:29)

2-11 MySQL体系结构 (05:29)

2-12 MySQL常用存储引擎之MyISAM (13:23)

2-13 MySQL常用存储引擎之Innodb (10:44)

2-14 Innodb存储引擎的特性(1) (15:24)

2-15 Innodb存储引擎的特性(2) (08:44)

2-16 MySQL常用存储引擎之CSV (09:19)

2-17 MySQL常用存储引擎之Archive (06:08)

2-18 MySQL常用存储引擎之Memory (10:40)

2-19 MySQL常用存储引擎之Federated (11:21)

2-20 如何选择存储引擎 (04:33)

2-21 MySQL服务器参数介绍 (08:04)

2-22 内存配置相关参数 (09:24)

2-23 IO相关配置参数 (10:01)

2-24 安全相关配置参数 (06:13)

2-25 其它常用配置参数 (03:41)

2-26 数据库设计对性能的影响 (04:36)

2-27 总结 (01:32)

2-28 【讨论题】你会如何配置公司的数据库服务器硬件？

2-29 【讨论题】你认为对数据库性能影响最大的因素是什么

2-30 【讨论题】做为电商的DBA，建议开发选哪种MySQL存储引擎


### 第3章 MySQL基准测试

#### 了解基准测试,MySQL基准测试工具介绍及实例演示。
3-1 什么是基准测试 (02:20)

3-2 如何进行基准测试 (09:00)

3-3 基准测试演示实例 (11:18)

3-4 Mysql基准测试工具之mysqlslap (13:30)

3-5 Mysql基准测试工具之sysbench (11:07)

3-6 sysbench基准测试演示实例 (17:11)

3-7 【讨论题】MySQL基准测试是否可以体现出业务系统的真实性能

3-8 【实操题】参数不同取值对性能的影响


### 第4章 MySQL数据库结构优化

#### 详细介绍数据库结构设计、范式和反范式设计、物理设计等等。
4-1 数据库结构优化介绍 (06:52)

4-2 数据库结构设计 (14:49)

4-3 需求分析及逻辑设计 (11:00)

4-4 需求分析及逻辑设计-反范式化设计 (06:44)

4-5 范式化设计和反范式化设计优缺点 (04:06)

4-6 物理设计介绍 (05:17)

4-7 物理设计-数据类型的选择 (18:59)

4-8 物理设计-如何存储日期类型 (13:37)

4-9 物理设计-总结 (02:37)

4-10 说明MyISAM和Innodb存储引擎的5点不同

4-11 【讨论题】判断表结构是否符合第三范式要求?如不满足要如何修改

4-12 【实操题】请设计一个电商订单系统的数据库结构

4-13 【讨论题】以下那个字段适合作为Innodb表的主建使用

4-14 【讨论题】请为下表中的字段选择合适的数据类型


### 第5章 MySQL高可用架构设计 

#### 详细介绍二进制日志及其对复制的影响、GTID的复制、MMM、MHA等等。
5-1 mysql复制功能介绍 (04:58)

5-2 mysql二进制日志 (22:05)

5-3 mysql二进制日志格式对复制的影响 (09:37)

5-4 mysql复制工作方式 (03:08)

5-5 基于日志点的复制 (20:06)

5-6 基于GTID的复制 (22:32)

5-7 MySQL复制拓扑 (13:58)

5-8 MySQL复制性能优化 (09:23)

5-9 MySQL复制常见问题处理 (08:31)

5-10 什么是高可用架构 (14:09)

5-11 MMM架构介绍 (08:09)

5-12 MMM架构实例演示（上） (09:16)

5-13 MMM架构实例演示（下） (18:55)

5-14 MMM架构的优缺点 (08:01)

5-15 MHA架构介绍 (10:02)

5-16 MHA架构实例演示(1) (13:11)

5-17 MHA架构实例演示(2) (16:54)

5-18 MHA架构优缺点 (05:14)

5-19 读写分离和负载均衡介绍 (11:42)

5-20 MaxScale实例演示 (18:25)

5-21 【讨论题】MySQL主从复制为什么会有延迟，延迟又是如何产生

5-22 【实操题】请为某互联网项目设计99.99%MySQL架构

5-23 【讨论题】如何给一个已经存在的主从复制集群新增一个从节点

5-24 【讨论题】给你三台数据库服务器，你如何设计它的高可用架构


### 第6章 数据库索引优化

#### 介绍BTree索引和Hash索引，详细介绍索引的优化策略等等。
6-1 Btree索引和Hash索引 (20:09)

6-2 安装演示数据库 (01:19)

6-3 索引优化策略（上） (17:33)

6-4 索引优化策略（中） (13:02)

6-5 索引优化策略（下） (12:30)

6-6 【讨论题】一列上建立了索引，查询时就一定会用到这个索引吗

6-7 【讨论题】在定义联合索引时为什么需要注意联合索引中的顺序

6-8 【实操题】SQL建立索引，你会考虑那些因素


### 第7章 SQL查询优化

#### 详细介绍慢查询日志及示例演示,MySQL查询优化器介绍及特定SQL的查询优化等。
7-1 获取有性能问题SQL的三种方法 (05:14)

7-2 慢查询日志介绍 (08:57)

7-3 慢查询日志实例 (08:27)

7-4 实时获取性能问题SQL (02:21)

7-5 SQL的解析预处理及生成执行计划 (16:02)

7-6 如何确定查询处理各个阶段所消耗的时间 (09:35)

7-7 特定SQL的查询优化 (10:34)

7-8 【讨论题】如何跟据需要对一个大表中的数据进行删除或更新

7-9 【讨论题】如何获取需要优化的SQL查询


### 第8章 数据库的分库分表

#### 详细介绍数据库分库分表的实现原理及演示案例等。
8-1 数据库分库分表的几种方式 (04:34)

8-2 数据库分片前的准备 (13:53)

8-3 数据库分片演示(上) (11:40)

8-4 数据库分片演示(下) (17:02)

8-5 【讨论题】对于大表来说我们一定要进行分库分表吗


### 第9章 数据库监控

#### 介绍数据库可用性监控、性能监控、MySQL主从复制监控等
9-1 数据库监控介绍 (04:46)

9-2 数据库可用性监控 (07:20)

9-3 数据库性能监控 (09:39)

9-4 MySQL主从复制监控 (06:16)

9-5 【讨论题】QPS是否可以真实的反映出数据库的负载情况

9-6 【讨论题】如何正确评估数据库的当前负载状况

9-7 【实操题】开发一个简单监控脚本，监控mySQL数据库阻塞情况


[下载地址](http://www.36tz.cn "下载地址")
