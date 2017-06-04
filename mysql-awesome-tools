# MySQL 优秀工具推荐

我想很多程序员应该记得 GitHub 上有一个 Awesome - XXX 系列的资源整理。[awesome-mysql](http://shlomi-noach.github.io/awesome-mysql/)就是 shlomi-noach 发起维护的 MySQL 资源列表，内容包括：分析工具、备份、性能测试、配置、部署、GUI 等。

Awesome 系列虽然挺全，但基本只对收录的资源做了极为简要的介绍，有两点可以改善：
1. 没有中国本地的一些工具，另外一些工具在国内市场没有得到认可。
2. 没有中文化，如果中文化，会有更多的朋友会进行关注。
3. 中国的社区并没有补进来
* * *


### 做这个的目的

[知数堂](http://zhishuedu.com)从事MySQL，Python相关教学工作， 有责任给学生做好职业辅垫，同时需要回馈给社区。以前想以公众号的形式推荐这些工具。后来觉的，不如以github的形式整理，这样方便更多的朋友参与。 也利于圈子的交流。

### 如何参与本项目？

从下面的目录来看，本项目的工作量不小，所以非常期待能有更多社区成员一起参与进来。

不过加入前，要求：

* 爱好开源，能读懂英文文档
* 有 MySQL 相关实践经验；

如有兴趣，请加 QQ群： 480110023。加 群时 时请注明「awesome-mysql」

* * *

### 本项目的参与者

- 维护者：[知数堂](https://zhishuedu.com)
- [吴炳锡](https://github.com/wubx) [blog](http://wubx.net) 
- [叶金荣](http://imysql.com) 
- 根据原文进行翻译添加本土工具。

注：名单不分排名，不定期补充更新

* * *


### 目录

*   分析工具
*   备份
*   性能测试
*   聊天应用
*   配置
*   连接器
*   部署
*   开发
*   GUI
*   HA
*   代理
*   复制
*   模式
*   服务器
*   分片
*   工具包

资源

*   文档
*   电子书
*   媒体
*   简讯
*   技术站点

## 分析工具

性能，结构和数据分析工具

*   [Box Anemometer](https://github.com/box/Anemometer) - 一个 SQL 慢查询监控器。 可以在上面做二次开发，实现慢日志收集平台。
*   [innodb-ruby](https://github.com/jeremycole/innodb_ruby) - 一个对 InooDB 格式文件的解析器，用于 Ruby 语言。特别提示： wubx 备注，这个工具非常强大，从2016年开始，用这个工具分析Innodb底层的一些问题，表示很受溢。
*   [innotop](https://github.com/innotop/innotop) - 一个具备多种特性和可扩展性的 MySQL 版 'top' 工具。
*   [pstop](https://github.com/sjmudd/ps-top) - 一个针对 MySQL 的类 top 程序，用于收集，汇总以及展示来自 performance_schema 的信息。
*   [mysql-statsd](https://github.com/db-art/mysql-statsd) - 一个收集 MySQL 信息的 Python 守护进程，并通过 StatsD 发送到 Graphite。
*   [dstat](https://github.com/dagwieers/dstat) - 一个Python实现的性能收集的工具，系统性能分析时，这个工具也比较有用。（20170315 推荐原因，指标比较全面）

## 备份

备份/存储/恢复 工具

*   [MyDumper](https://launchpad.net/mydumper) - 逻辑的，并行的 MySQL 备份/转储工具。
*   [MySQLDumper](http://www.mysqldumper.net/) - 基于 web 的开源备份工具-对于共享虚拟主机非常有用。
*   [mysqldump-secure](https://github.com/cytopia/mysqldump-secure) - 将加密，压缩，日志，黑名单和 Nagios 监控一体化的 mysqldump 安全脚本。
*   [Percona Xtrabackup](https://www.percona.com/doc/percona-xtrabackup) - 针对 MySQL 的一个开源热备份实用程序——在服务器的备份期间不会锁定你的数据库。

## 性能测试

_给你的服务器进行压测的工具_
 在做压力测试时，建议把压力工具和MySQL服务器分开，避免压力工具占用太多的资源。
 *   [iibench-mysql](https://github.com/tmcallaghan/iibench-mysql) -基于 Java 的 MySQL/Percona/MariaDB 索引进行插入性能测试工具。备注： **建议不用关注了。**
 *   [Sysbench](https://github.com/akopytov/sysbench) - 一个模块化，跨平台以及多线程的性能测试工具。 
 *   [tpcc-mysql](https://github.com/Percona-Lab/tpcc-mysql) 基于tpcc模型对MySQL进行压测力测试。 --add wubx
 *   [YSCB](https://github.com/brianfrankcooper/YCSB) - Yahoo基于Java开发的一个压测工具，支持压测的种类比较多，优秀之处在于：可以调整读写比例进行压测，以便方好的观查不同模型的压力情况。
 *   [fio](https://github.com/axboe/fio)  - 一款IO测试的工具，做MySQL DBA必须懂得IO压力测试. 

## 聊天应用

_集成进聊天室的脚本_

*   [Hubot MySQL ChatOps](https://github.com/samlambert/hubot-mysql-chatops)

## 配置

_MySQL 配置实例及指导_

*   [mysql-compatibility-config](https://github.com/morgo/mysql-compatibility-config) - 使 MySQL 配置起来更像新的（或先前）的 MySQL 版本。
*   [my.cnf生成工具](http://zhishutech.net/my-cnf-wizard.html) - 叶金荣开发的一个MySQL配置生成工具

## 连接器

_多种编程语言的 MySQL 连接器_

*   [Connector/Python](https://dev.mysql.com/downloads/connector/python/) - 一个对于 Python 平台和开发的标准化数据库驱动程序。
*   [go-sql-driver](https://github.com/go-sql-driver/mysql) - 一个 Go 语言的轻量级、极速的 MySQL 驱动程序。
*   [libAttachSQL](http://libattachsql.org/) - libAttachSQL 是 MySQL 服务器的一个轻量级，非阻塞的 C 语言 API。
*   [MariaDB Java Client](https://mariadb.com/kb/en/mariadb/mariadb-connector-j/) - 针对 Java 应用且经过 LGPL 许可的 MariaDB 客户端库。
*   [MySQL-Python](https://sourceforge.net/projects/mysql-python/) - 一个 Python 语言的 MySQL 数据库连接器。
*   [PHP mysqlnd](https://dev.mysql.com/downloads/connector/php-mysqlnd/) - 针对 MySQL 的 MySQL 本地驱动，弃用过时的 libmysql 基础驱动。

## 开发

_支持 MySQL 相关开发的工具_

*   [Flywaydb](https://flywaydb.org/getstarted/) - 数据库迁移;任意情况下轻松可靠地演变你的数据库版本。
*   [Liquibase](http://www.liquibase.org/) - 对你的数据库进行源代码控制。
*   [Propagator](https://github.com/outbrain/propagator) - 集中模式和数据部署在一个多维拓扑上。

## GUI

_前端和应用的 GUI_

*   [Adminer](https://www.adminer.org/) - 一个 PHP 编写的数据库管理工具。
*   [HeidiSQL](http://www.heidisql.com/) - Windows 下的 MySQL 图形化管理工具。
*   [MySQL Workbench](http://dev.mysql.com/downloads/workbench/) - 提供给数据库管理员和开发人员进行数据库设计和建模的集成工具环境;SQL 开发;数据库管理。
*   [phpMyAdmin](https://www.phpmyadmin.net/) - 一个 PHP 写成的开源软件，意图对 web 上的 MySQL 进行管理。
*   [SequelPro](https://github.com/sequelpro/sequelpro) - 一个 mac 下运行 MySQL 的数据库管理应用程序。
*   [mycli](http://hao.jobbole.com/mycli-mysql/) - 一个带自动补全和语法高亮的终端版 MySQL 客户端

## HA

_高可用解决方案_

*   [Galera Cluster](http://galeracluster.com/products/) - 一个基于同步复制的多主机集群方案。
*   [MHA](http://code.google.com/p/mysql-master-ha/) - 针对 MySQL 的优秀高可用管理器及工具
*   [MySQL Fabric](https://www.mysql.com/products/enterprise/fabric.html) - 一个用于管理 MySQL 服务器场（Server Farms）的可扩展框架。
*   [Percona Replication Manager](https://github.com/percona/percona-pacemaker-agents/) - 针对 MySQL 的异步复制管理代理。支持以文件和 GTID 为基础的复制，使用 booth 实现的地理分布式集群。
*   [keepalived](http://www.keepalived.org/) - 一个很古老的HA工具，但还是很实用，里面的切换接口比较完善，只需要细心定制一下就可以实现MySQL的高可用。 

## 代理

_MySQL 代理_

* [MaxScale](https://github.com/mariadb-corporation/MaxScale) - 开源，以数据库为中心的代理。
* [Mixer](https://github.com/siddontang/mixer) - Go 实现的一个 MySQL 代理，目的为 MySQL 分片提供一个简单的解决方案。
* [MySQL Proxy](https://launchpad.net/mysql-proxy) - 一个处于你的客户端和 MySQL 服务端之间的简单程序，它可以检测、分析或者改变它们的通信。
* [ProxySQL](https://github.com/renecannao/proxysql) - 高性能的 MySQL 代理。
* [Atlas](https://github.com/Qihoo360/Atlas) - Qihoo 360开源的MySQL Proxy。
* [OneProxy](http://www.onexsoft.com/proxy.html) - 业界专家楼方鑫开发的商业Proxy产品。


## 复制

_复制相关的软件_

*   [orchestrator](https://github.com/outbrain/orchestrator) - 对 MySQL 复制拓扑管理并可视化的工具。
*   [Tungsten Replicator](https://code.google.com/archive/p/tungsten-replicator) - MySQL 的一个高性能、开源、数据复制引擎。
*   [otter](https://github.com/alibaba/otter) - 阿里巴巴分布式数据库同步系统(解决中美异地机房)

## 模式

_附加模式_

*   [common_schema](https://code.google.com/archive/p/common-schema) - MySQL DBA 的框架， 提供一个具有函数库、视图库和查询脚本的解释器。
* [sys](https://github.com/mysql/mysql-sys) - 一个视图、函数和过程的集合，以帮助 MySQL 管理人员更加深入理解 MySQL 数据库的使用。（备注：MySQL 5.7已经集成了sys schema功能，可以不再关注该项目了）
## 服务器

_MySQL server分支_

*   [MariaDB](https://github.com/MariaDB/server) - MySQL server 的一个由社区开发的分支。
*   [MySQL Server & MySQL Cluster](https://github.com/mysql/mysql-server) - Oracle 官方的 MySQL server 和 MySQL 集群分布。
*   [Percona Server](https://launchpad.net/percona-server) - 一个加强版的 MySQL 替代品，内部含用TokuDB引擎
*   [WebScaleSQL](https://github.com/webscalesql/webscalesql-5.6) - WebScaleSQL，5.6 版本，基于 MySQL 5.6 社区版本。
*   [AliSQL](https://github.com/alibaba/AliSQL) - 阿里云开源出来的一个MySQL分支
*   [Xenon TokuDB](https://github.com/XeLabs/tokudb) - 基于percona的tokudb进行优化，引入MyRoks的一些特性。
*   [MyRocks](https://github.com/facebook/mysql-5.6) - Facebook开源一个MySQL分支，内含MyRocks引擎

## 分片

_分片解决方案/框架_

*   [vitess](https://github.com/youtube/vitess) - 对于大规模的 web 服务，vitess 提供服务和工具以便于 MySQL 数据库的缩放。
*   [jetpants](https://github.com/tumblr/jetpants) - 一个自动化套件，用于管理大规模分片集群，由 Tumblr 开发。
*   [DBproxy](https://github.com/Meituan-Dianping/DBProxy) - 美团开源出来的一个DBproxy 目前比较活跃
*   [MyCAT](https://github.com/MyCATApache/Mycat-Server) - 基于Java开发的一款Proxy功能方面比较强大。
* [Atlas](https://github.com/Qihoo360/Atlas) - Qihoo 360开源的MySQL Proxy。
* [KingShard](https://github.com/flike/kingshard) - 基于Golang实现的一个MySQL Proxy。

## 工具包

_工具包，通用脚本_

*   [go-mysql](https://github.com/siddontang/go-mysql) - 一个纯 go 的库，用于处理 MySQL 的网络协议和复制。
*   [MySQL Utilities](https://dev.mysql.com/downloads/utilities/) - 一个命令行实用程序的集合，Python 语言编写，用于维护和管理单一或多层的 MySQL。
*   [Percona Toolkit](https://www.percona.com/software/percona-toolkit) - 一个先进的命令行工具集，用于执行对于 MySQL 服务器和系统过于困难或复杂的任务。
*   [openark kit](http://code.openark.org/forge/openark-kit) - 一组实用的工具，解决日常的维护工作，包括一些复杂的或需徒手操作的，用 Python 语言编写。
*   [UnDROP](https://twindb.com/undrop-tool-for-innodb/) - 一个用来恢复删除或损坏的 InnoDB 表中数据的工具。
*   [binlog2sql](https://github.com/danfengcao/binlog2sql) - 基于Binlog对误操作一个恢复工具

# SQL审核
 [mysql inception](https://github.com/mysql-inception/inception) - 一个集审核、执行、备份及生成回滚语句于一身的MySQL自动化运维工具
 [Themis](https://github.com/CreditEaseDBA/Themis) - Themis，是宜信公司DBA团队开发的一款数据库审核产品。可帮助DBA、开发人员快速发现数据库质量问题，提升工作效率。

# 社会资源

_目前主要整理开源出来或是WEB页面提供的工具。在这个阶段，“资源”不包括网站，博客，幻灯片，演示视频等。这些资源列表的大小令人恐惧。_

## 会议

_围绕 MySQL 进行公开，经常性的大会。_
**国外的大会**
*   [FOSDEM](https://fosdem.org/) - 一个软件开发人员见面、交流思想与协作的活动。每年在 Brussels 举行。提供 “MySQL & friends” 开发工作室。
*   [MySQL Central](https://www.oracle.com/openworld/mysql/index.html) - Oracle 年度 MySQL 大会，是 Oracle Open World 的一部分。
*   [Percona Live](https://www.percona.com/live/conferences) - MySQL 和 OpenStack 的重要会议。
*   [SCALE](https://www.socallinuxexpo.org/) - 一个每年在南加州举办，由社区组织的 Linux 和 开源软件大会。由当地 MySQL社区组织并以MySQL社区日的名义举办。

**国内优秀MySQL大会组织**
* [ACMUG](http://acmug.com) - 专注MySQL社区交流，注重实体交流 
* [DTCC](http://dtcc.it168.com/) - IT168数据库架构师大会，综合性数据库大会
* [Oracle技术嘉年华]() -  以Oracle为主含MySQL的技术交流大会


## 电子书

_MySQL 电子书以及相关材料。_

*   [SQL-exercise](https://github.com/XD-DENG/SQL-exercise) - 包含几个 SQL 练习，包括模式描述，用 SQL 语句去建立模式，SQL 的问题及解决方案。以 wikibook SQL 练习为基础。

## 媒体

_公开，持续的视频和音频转播。这不包括会议演讲那令人恐惧的资源列表大小。_

*   [DBHangOps](http://dbhangops.github.io/) - 两周一次由各种各样的 MySQL 社区人员参加的 google 聚集大会，大会的日常就是谈论一切关于 MySQL 的东西。
*   [OurSQL Podcast](http://www.oursql.com/) - MySQL 数据库社区播客。

## 新闻周刊

__顾名思义，新闻周刊_需要一个 email 地址。下面列出周刊只需要一个 email 地址。_

*   [Weekly MySQL News](http://mysqlnewsletter.com/) - 非官方的 MySQL新闻摘要，包含关于MySQL的各类信息。

## 技术站点
MySQL相关中文技术站点，博客，聚合等资源

*   [MySQL Planet(中文)](http://planet.mysql.com/zh/) - MySQL 官方的博客聚合站。


# 工具整理交流

<h3 id="QQ">有任何建议或意见请加入QQ群：480110023 </h3>
