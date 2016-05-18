# 介绍

	何敢自矜医国手，药方只贩古时丹。——[清]龚自珍

我是一个老程序员了。多年来，见证无数的公司和开发人员在在项目中死死挣扎，不成系统，没有章法，在消耗大量的人力、时间和金钱之后，得出的往往只是一个差强人意的产品，僵化、脆弱、漏洞百出。客户不满意，管理层不满意，我们自己更是身心俱疲，缺乏成就感，甚至怀疑自己入错了行。

我们自诩为软件工程师、架构师，但是在内心深处，你我都知道，我们离这些称号所代表的专业性之间相差着十万八千里。工程师造的桥梁和楼房至少不会每两三个月倒塌一次吧，我们的软件呢？

本书试图总结和运用当前业界先进的软件开发思想、方法和工具，启发和引导开发人员进行“准”专业的软件开发，希望能够将我们和“专业性”之间的距离缩短到一万八百里甚至一千零八十里。（为什么我们不敢以真正的专业性为目标？因为计算机软件行业只出现了几十年的时间，它至少还要几十年的实践、试错和思考淬炼，才有可能达到真正的专业性）


编写本书的目的之一，是试图纠正国内业界几个根深蒂固的落后甚至错误的开发范式，主要包括：

* **瀑布式开发**

需求阶段、设计阶段、实现阶段、测试阶段……只要你思想里面还有这些概念，你就属于传统的瀑布式开发范式的一员。1996年Kent Beck就开创了极限编程（XP）敏捷开发范式，2001年敏捷宣言的发表至今也有15个年头了，而国内真正实施敏捷的公司、团队和个人却仍然少的可怜。这是导致软件质量低劣和程序员缺乏幸福感的最重要原因之一。

* **以数据模型为中心**

绝大多数的公司和开发人员仍然是采用“以数据库表为中心的增删改查”的面向过程的思维开发应用软件。从1960年在simula 67语言中引入面向对象（OO）的思想开始，到上世纪八、九十年代C++和Java的出现，OO语言达到极盛，今天绝大多数的编程语言都是OO的。但是我们今天仍然是用着面向对象的语言写面向过程的代码。就如同拿着先进的链锯去*砍*（不是*锯*）树——树没倒，链锯断了，还顺带截断了几节手指头。

* **没有自动化测试/测试后行**

我认为有没有采用测试先行开发范式，是专业和非专业软件开发的分水岭。当我们在编写产品代码之前先编写测试代码的时候，这些测试本质上不再是质量保证工具，而是一种设计工具了。我们可以在单元测试和验收测试的层面都采用测试先行的开发范式，用测试表达需求、驱动设计。但是国内的软件开发基本上没有编写自动化测试代码，遑论测试先行。

* **手工构建和部署软件**

“卖花姑娘插竹叶”是我们行业的普遍现状。我们为客户开发自动化的解决方案，可我们构建软件解决方案的过程却充满了手工的环节，每次构建、打包、部署和测试的过程都非常繁琐、复杂、不可重复、易于出错。本书试图展示自动化构建、持续集成、持续交付和持续软件质量检测与改进等等现代先进软件生产流水线。


本项目涵盖下面这些思想、材料、服务和工具：

* 思想和方法论
   * 敏捷开发
   * 领域驱动设计
   * 测试驱动开发
   * 行为驱动开发
* 类库、框架、服务和规范
   * 持久化：JPA和Hibernate
   * 依赖注入：SpringIoC
   * 表示层：SpringMVC、ReactJS
   * 认证授权：OAuth2，Shiro
   * REST服务：Dropwizard
   * REST客户端：Retrofit
   * 日志：SLF4J
* 移动App
   * React Native
* 虚拟机和容器
   * 虚拟机：VirtualBox
   * 容器：Docker
* 工具
   * 单元测试：JUnit
   * 集成测试：Arquillian
   * 验收测试：Cucumber
   * JS测试：Jasmine
   * 测试断言库：AssertJ
   * 测试替身：Mockito
   * 测试数据准备：DBUnit
   * 参数化测试：Feed4JUnit
   * 性能测试：JMeter
   * 版本控制：GIT
   * 自动化构建：Maven, Nexus
   * 持续集成：Jenkins
   * 质量分析：Sonarqube
   * 代码剖析：VisualVM
   * IT自动化：Ansible、Vagrant
   * 项目管理与Bug跟踪：Redmine, 看板
   * UML建模：Visual Paradigm
   * 原型建模：Azure RP
   * IDE：IntelliJ IDEA
   * 日志分析展示：ELK（ElasticSearch、Logstash、Kibana）
   * API文档生成：Doxmate、Doxygen
