# 为什么需要分布式存储

- 数据量太大,单机存储能力有上限,需要靠数量来解决问题

- 数量的提升带来的是网络传输、磁盘读写、CPU、内存等各方面的综合提升。分布式组合在一起可以达到1+1>2的效果

# 分布式的基础架构分析

## 1、分布式系统常见的组织形式

- 去中心化模式：没有明确中心，大家协调工作
- 中心化模式：有明确的中心，基于中心节点分工作

## 2、什么是主从模式

- 主从模式(Master-Slaves)就是中心化模式，表示有一个主节点来作为管理者，管理协调下属一批从节点工作

## 3、Hadoop是哪种模式？

主从模式(中心化模式)

# HDFS 的基础架构

## 1、什么是HDFS?

- HDFS全称：Hadoop Distributed File System
- 是Hadoop三大组件(HDFS、MapReduce、YARN)之一
- 可在多台服务器上构建集群，提供分布式数据存储能力

## 2、HDFS中架构角色有哪些？

- NameNode：主角色，管理HDFS集群和DataNode角色
- DataNode：从角色，负责数据的存储
- SecondaryNameNode：辅助角色，协助NameNode整理元数据

## 3、HDFS的基础架构

![image-20230921193626860](assets/image-20230921193626860.png)

# HDFS集 群环境部署



# HDFS的存储 原理
# HDFS的Shell操作