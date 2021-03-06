## 个人信息
- 陈嘉伟/男/1997
- 毕业院校：广东工业大学/电子科学与技术（2015-2020）
- 手机: 18588557892 / Email: jerrychaox8406@gmail.com
- 求职意向：Java开发工程师/服务端工程师/后端开发工程师

## 专业技能
- 具备良好的**算法/数据结构**基础、熟悉**网络(TCP/IP)协议**、**Linux操作系统**
- 精通**Java**(Core/NIO/JUC/JVM)
- 掌握**存储系统Redis、Mysql原理及应用**、消息队列RocketMQ的技术架构与应用
- 掌握**Docker、Kubernetes**在部署方面的应用
- 了解Javascript(es6+)、Vue全家桶

## 创业经历：广州市墨锋信息科技有限公司（2017.6 - 2020.1）
- 担任公司后端核心开发人员
- 负责核心系统的设计，开发，性能优化，维护
- 解决技术部内疑难问题、主导基础设施技术方案的决策。

## 项目经历

### 小型聚合支付系统——通用支付服务下沉 (2017.9 ‒ 2020.1)

本系统主要为公司内部软件系统提供**支付解决方案**，聚合了多个提供微信支付、银联支付服务的第三方支付公司，提供交易、分账、资金清算服务。目前约有日交易流水约**15W+**。

> 担任后端开发，独立完成数据库设计、API设计、订单状态机设计、核心功能编码

- 利用**适配器、策略、模版方法的设计模式**处理不同上游支付接口的异构性问题
- 利用了**RocketMQ**优化下单**QPS**，**解藕**服务层与渠道层，配合RockerMQ的**事务消息**保证数据一致性
- 对后端Java服务进行容器化，利用阿里云Kubernetes平台快速实现负载均衡、滚动更新、自动伸缩

### 校园外卖购——校园点餐平台 (2019.02 ‒ 2020.1)

本系统为校园外卖提供线上运营的解决方案，支持多所学校和饭堂的入驻。业务上分为点餐、学生跑腿、营销三大板块，包含一元券、秒杀、抽奖等营销功能。目前日均交易流水达10W+，已入驻8所学校，几十余饭堂。

> 担任服务端优化，主要负责线上高负载问题排查、性能优化，保障**高峰时段的可用性与整体性能优化**

- 从平均负载/CPU使用率/上下文切换，定位应用业务高峰期性能问题
- 优化WebServer **IO模型**及**nginx+php-fpm**配置，最大化利用核心与内存资源
- 分析MySQL**慢SQL**日志，优化部分SQL**索引命中**问题
- 分析高峰时段无法新增订单的INNODB RR **Gap Lock**问题
- 容器化PHP应用，提供标准单实例运行镜像
