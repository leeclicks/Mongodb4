# Mongodb4 
Mongodb4  集群  

Replica Set Deployment Tutorials  副本集部署

特点：

1. 最小构成是：primary，secondary，arbiter，一般部署是：primary，2 secondary。

2. 成员数应该为奇数，如果为偶数的情况下添加arbiter，arbiter不保存数据，只投票。

3. 最大50 members，但是只能有 7 voting members，其他是non-voting members。

一、Download and installation 环境准备及安装包下载

1、配置三台linux，并相互ping通，且联网

2、下载MongoDB安装包

3、在三台服务器上创建文件夹并上传安装包

      创建/usr/local/web/mongodb文件夹：
      mkdir  /usr/local/web/mongodb

      解压MongoDB到/usr/local/web/mongodb目录

      创建/usr/local/web/mongodb/logs文件夹：
      mkdir  /usr/local/web/mongodb/logs

      创建/usr/local/web/mongodb/data文件夹：
      mkdir  /usr/local/web/mongodb/data 


