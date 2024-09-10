# 0575springboot校园一卡通_q7e7o--论文


# [0575springboot校园一卡通_q7e7o--论文](https://github.com/GraduationProject-springboot/0575springboot)

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

# [项目清单](https://chenqi1990.site) 包安装运行

### [github 项目仓库](https://github.com/GraduationProject-springboot/allSpringbootProjects) 开源仅有后端代码

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1eMbYemE1U?p=73)


# 第一章 概述
## 1.1 研究背景
近些年，随着中国经济发展，人民的生活质量逐渐提高，对网络的依赖性越来越高，通过网络处理的事务越来越多。随着校园一卡通的常态化，如果依然采用传统的管理方式，将会为工作人员带来庞大的工作量，这将是一个巨大考验，需要投入大量人力开展对校园一卡通等相关工作进行管理，单一且反复的操作容易出错且不易被察觉，工作人员对此风险并不能完全归避。利用现代信息技术，设计开发一款管理系统，能够极大的节省人力物力、提高工作效率、降低工作成本。
## 1.2研究目的及意义
本论文拟采用计算机技术设计并开发的校园一卡通，主要是为校园一卡通提供服务。使得用户可依据、时间、地点或者其他特定条件，筛选出符合的信息，给用户提供更符合实际的合理化建议，再为用户提供服务。本课题的意义在于，用户能通过使用校园一卡通，提高工作效率和服务质量，进而提高体验感。
## 1.3国内外发展现状
相比于国内，国外的线上管理系统建设比较早，在上世纪就已经很先进，但受七十年代的经济危机影响，导致部分国家发展缓慢，但也有些发达国家走群众路线，全面发展网络技术。

在国内，线下管理系统已经特别完善，它基于计算机技术，让系统具有信息化、科学化、自动化等特性。在计算机的辅助下，国内该类系统可使管理者提高信息的复用率，对数据的处理、备份等方面也有了显著的效率提升，这种有效的工作可使管理者能更快的做好决定，也实现了“无纸化”的信息管理方式。由于其功能特别完善，也导致系统比较庞大，所以在了解该类系统的功能、操作后，决定开发一款校园一卡通，它的功能小，但是操作简单、快速、准确的特点，也体现了设计它的意义。
## 1.4 研究内容
1. 调研：通过网络、图书馆等渠道调查该课题的参考资料。
1. 系统需求分析：对参考资料分类整理，设想需求与功能，再研究实现功能所需的开发工具、技术、数据库等。
1. 系统概要设计：设计功能模块、流程、数据库模型、表与字段间的关系等。
1. 系统实现：对系统用户以文字加截图的形式进行精细化分解。
1. 系统测试：测试的作用和好处，测试的具体操作步骤，分析需求与测试结果是否一致。
## 1.5本文的结构
本论文分为六个章节。

第一章，绪论，其包含课题背景及意义，现国内外的发展现状，本课题要研究的内容，所使用开发工具的描述等信息。

第二章，主要介绍了系统的开发技术。

第三章，先讲述功能需求分析，再讲述系统可行性分析和流程图的设计。

第四章，是系统设计原理，功能模块设计和数据库设计。

第五章，详细讲述每个界面的正确操作步骤。

第六章，该章讲述了测试的目的以及测试过程及用例。

最后对论文进行总结，包括致谢和参考文献等内容。


# `	`第二章 开发工具及技术介绍
此次管理系统的关键技术和架构由B/S结构、java技术和MySQL数据库，是本系统的关键开发技术，对系统的整体、数据库、功能模块、系统页面以及系统程序等设计进行了详细的研究与规划。
## 2.1 Java编程语言
Java语言的发展距今己有二十多年的历史，Java在众多编程开发语言中依然稳居排名前三，这离不开Java技术体系的众多开发优势，相对比于其他编程开发语言而言，Java语言[}so]的入门使用非常简单，Java集成了丰富的类库和封装类，能够使开发者非常方便调用，拥有强大的技术基础作为支撑，非常适合大型软件的开发。由于Java语言是一门面向对象的编程语言，因此程序员只需要掌握基本的语法规则和清晰的编程思路便可以较好地开发应用程序。除此之外，由于Java语言具有跨平台和可移植性强的开发优点，因此可以在Android的应用程序开发中发挥其重要作用。在大型的软件项目开发中应用Java技术较为广泛，能够为企业项目需求提供成熟的解决方案。

常用的计算机程序编程语言有Java语言、Python语言、C语言以及C++语言。由于Java语言具有成熟的技术架构以及较为广泛的应用范围，因此深得编程人员的喜爱。

Java语言提供了try-catch异常处理、垃圾自动回收、内存动态分配等强大功能机制，Java语言具备简单性、健壮性、可移植性、多线程等优点，Java语言的强大特性能够降低软件后期的维护成本以及有效缩短软件研发周期，节省了企业的软件开发成本。本研究的校园一卡通管理案例项目正是以成熟的Java编程语言为基础的校园一卡通项目开发语言。
## 2.2 MySQL数据库
MySQL是Oracle公司旗下的一个开源的关系型数据库管理系统(Relational Database Management System, RDBMS)}44} o MySQL支持使用多线程，充分利用了CPU的计算资源，可以选择InnoDB, MyISAM和MEMORY等作为存储引擎，提供了丰富的数据库管理工具。在索引功能的加持下，其具有非常高的查询效率，并支持主从、多节点集群等高可用部署模式。MySQL凭借其低廉的成本、可靠的数据库服务和出色的性能，目前己经成为绝大多数企业在进行项目开发时的首选关系型数据库。MySQL的体系结构如图2.1所示，具体可分为网络连接层、服务层、存储引擎层和系统文件层，分别完成建立连接、SQL解析与执行、数据存储与提取和数据交互等功能。

![](/images/0500stringboot/0575springboot/blog.002.png)

图2.1 MySQL体系结构图
## 2.3 SPRINGBOOT 框架
Spring Boot是由Pivotal的开发团队在2013年开发的一个免费、轻量级、开源的系统框架。SpringBoot的主要设计思想是约定大于配置，因此SpringBoot在设计时几乎达到零配置。SpringBoot集成了业界的开源框架。

SpringBoot是一个非常强大的后台框架，因为SpringBoot的开发基本上不需要写配置文件，所以利用SpringBoot来构建网站的后台环境，在SpringBoot的YML配置文件中写项目启动端口，项目就可以启动了。项目的Java和静态文件由SpringBoot管理。
## 2.4 B/S架构
B/S结构就是指系统客户端与服务器分离，客户端通过浏览器访问服务端进行操作[10]。

B/S结构目前广泛应用于绝大部分系统搭建中，这种结构摒弃C/S结构客户端服务端不分离的缺点，具有更多的优势：

（1）跨平台性：B/S的标准由标准化组织确立，适用于绝大多数的系统搭建，通用于应用之间。

（2）低维护成本：客户端和服务器端分离，减轻了两端的压力，尤其是客户端，对客户端设备，硬件、软件要求都比较低，并且系统需要升级或维护时，只需要在服务器端升级或维护就可以，使相应的费用减少。
# 第三章 系统分析
## 3.1功能需求分析
需求分析的首要任务是要分析用户的需求，知道用户存在的一些情况，并且要明确用户的使用状况，然后设计规划解决的问题。其中在使用定性的分析以及定量的分析，从这两个方面获取用户的需求。一方面定性的分析获得的应该是用户的基本需求，能够发现现在人们的习惯要求。所以定性的需要主要是为了多与用户交流，从而更为深刻的了解一些存在的需求问题；定量的分析则是发现一些潜在的用户，并且获得不一样的反馈内容。所以定量的需求要让用户来阐述一些情况，一定让使用者清晰的进行客观的描述，这样才能够比较全面的获得用户的需求所在。

其中获得用户需求以后，就要可以将用户需求设计为系统的功能模块。在能及时的分析和发现有关需求的情况下，需要系统同时的跟进需求设计。在校园一卡通管理过程中还需要创建需求工作的数据分析，以便于后面的分析做总结。写入一个需求的报告内容，其中需要包含完整的描述需求、以及功能需求、模型等后续开发过程中还需要用到的部分资料。

需求的分析中用户需求就是比较的重要，而且可以通过各种的路径，以及各用户对于系统的功能需求，你需要对这些内容做出整理以及分类，然后分析这些需求的现实情况下的可能原因，还需要有认真的分析过程，结合现实的情况下最终做出一系列的需求资料。在有关用户的期望分析中能够明确一些可能实现的情况，校园一卡通管理功能是许多个可以测试的功能相结合的，正是由于这些功可以使得用户能够更加积极的提供出需求，让系统功能可以变得更加的完善。这样就可以保证所有设计的功能模块都是可以用到的，而且也是可测试的，对于后续系统的开发能够有比较关键的作用，也能快速完成用户所提供的需求。 
## 3.2系统可行性分析
### 3.2.1技术可行性
该系统使用java技术开发，MySQL数据库同Springboot框架联合开发并实现。对于以上描述的技术，在当代都是较为成熟的技术和平台，虽然它们都有自已的体系，但在程序员的眼里，它们的配合度是很高的，网上的相关博客中每个创建项目的帖子，它们都会出现，数据库负责管理数据，开发工具负责管理项目，技术负责代码的框架，既相互独立，又相互依赖。以上描述的工具、技术都已转化为自身的技能，所以从技术角色考虑是可行的，工作人员对于技术的关注度并不高，只要程序可用即可。
### 3.2.2 经济可行性
经济可行性，可分为两种，支出和收入，该系统属于研究型毕业设计，所以收入部分暂不考虑。支出可分为，设备、场地、开发环境、人力、时间等一切需考虑的因素，所有信息都是影响形成系统的一部分。设备：只需一台笔记本电脑，配套的输入设备；场地：暂定为图书馆与校内的自习室；开发环境：良好；人力：自身、指导老师、同学；时间：从选题到毕业为止，大约8个月。从以上描述可知，大部分条件已经满足，所以该系统不会存在经济方面的问题，所以是可行的。
### 3.2.3社会可行性
社会可行性，广义而讲可涉及到道德方面、法律方面、社会方面，每个方面都会影响系统的形成[12]。本系统的是独立且没有任何传播性质的信息，更涉及不到道德层面，法律层面；本系统也没有触发法律，没有赌博、黄色等类型信息，同时也是遵从国家法律，不会显示任何触发法律层面的信息；社会方面，该系统是为方便客户提供更好的服务，是轻量级的校园一卡通，会为人们带来快速并有效查询的功能，也是具有贡献意义的。总体而言，该系统也是具有社会可行性的。
## 3.3 系统用例分析
校园一卡通综合网络空间开发设计要求。目的是将传统管理方式转换为在网上管理，完成校园一卡通管理的方便快捷、安全性高、交易规范做了保障，目标明确。校园一卡通可以将功能划分为管理员功能，学生功能。

（1）管理员关键功能包含系统首页，个人中心，学生管理，一卡通管理，充值信息管理，扣费信息管理，挂失申请管理，商品类型管理，商品信息管理，订单信息管理，图书类型管理，图书信息管理，图书借阅管理，图书归还管理，通知信息管理，美食信息管理，食堂就餐管理，体育器材管理，器材借用管理，器材归还管理，会议签到管理，缴费信息管理，上机记录管理，论坛管理，系统管理等进行管理。管理员用例如下：

![](/images/0500stringboot/0575springboot/blog.003.png)

图3-1 管理员用例图

（2）学生关键功能包含首页，商品信息，图书信息，美食信息，体育器材，论坛，校园资讯，后台管理，个人中心等进行管理。学生用例如下：

![](/images/0500stringboot/0575springboot/blog.004.png)

图3-2 学生用例图

## 3.4系统流程图设计
流程图是用具体的图形符号和相应的线条来表示系统执行的整个过程。因为这种图可以很容易地描述系统的一系列过程，所以它的所有图形符号都是比较关键的，基本上一个图形符号可以表示一个过程的一个步骤。流程图不仅提供了一个比较完整、全面的实施过程，而且可以发现整个团队协同设计过程中可能存在的缺陷和不足，便于在后续过程中及时对系统进行修正和改进。

通过流程图可以对系统的需求和相关流程进行分析，可以详细细分为各个部分的设计。对于设计人员来说在开发过程中要能够以流程图为基础，能够快速的提高自己的逻辑思维，并且也能够指导后续的操作在系统设计中最重要的部分就是程序的设计，然后具体的编写程序，流程图是设计过程中的重要工具，下面是流程图的部分设计。
### 3.4.1 登录流程图
登录流程是该系统的第一个流程，登录的第一步是输入账号、密码登录，系统会验证账号与密码是否正确，正确时系统会判断账号类型再进入不同的后台；不正确时，会返回到登录的第一步，输入用户重新执行登录流程。该流程如图3-3所示。

![](/images/0500stringboot/0575springboot/blog.005.png)

图3-3登录流程图

### 3.4.2 添加新用户流程图
添加新用户的流程是先查询新用户名是否已存在，如已有该用户名，需重拟用户名并同时输入新用户的其它信息，添加新用户到数据库时会先验证数据是否完整，信息都正确且完整时，返回并刷新用户列表；信息不正确时，会返回输入信息的那一步。该流程如图3-4所示。

![](/images/0500stringboot/0575springboot/blog.006.png)

图3-4添加新用户流程图



# 第四章 系统设计
## 4.1系统设计原理
设计原理，是指一个系统的设计由来，其将需求合理拆解成功能，抽象的描述系统的模块，以模块下的功能。功能模块化后，变成可组合、可拆解的单元，在设计时，会将所有信息分解存储在各个表中，界面不会显示所有定义的字段。在设计时，会有几大要求，抽象、模块化、信息隐藏、耦合低、内聚等特性，本系统的设计也符合以上几大特性。制作和显示流程都属于程序员需要分析研究的一部分[13]。每个模块都是相对独立的，系统前台不显示账号操作权限范围外的信息。
## 4.2功能模块设计
该章节的功能模块设计，只是大概描述了系统的所有功能模块，将功能按权限来讲解。系统总体功能如图4-1所示。

![](/images/0500stringboot/0575springboot/blog.007.png)

图4-1 系统总体结构图

## 4.3 数据库设计
### 4.3.1数据库设计原则
学习程序设计，如果想要了解数据库管理系统或者是按照系统接口的要求制作的，就必须创建一个数据库管理系统模型，用来存储数据，这样在进行应用程序编程的过程中，就不需要加载操作系统页面的信息，从而提高整个系统的工作效率。在数据库管理系统中承载着众多的数据，应该说，一个管理信息系统的建设中心和基地，也为建设管理信息系统和信息管理系统提出了新的查询、删除、修改和操作功能，使管理信息系统建设可以快速查询需要的数据，而不是直接从代码中查找。信息库管理系统由各个组成部分的信息表按照具体的方法进行准确的归并、排序和组成信息库管理系统。
### ` `4.3.2数据库E-R图设计
E-R图即实体-联系图，主要作用是提供了解显示数据类型存在的联系的途径，是藐视现实世界的概念模型，其关键要素是实体型、属性、联系。以下是本系统主要的实体属性图如下所示。

商品信息实体如图4-2所示。

![](/images/0500stringboot/0575springboot/blog.008.png)

图4-2商品信息实体属性图

美食信息评论实体如图4-3所示。

=![](/images/0500stringboot/0575springboot/blog.009.png)

图4-3美食信息评论实体属性图

器材借用实体如图4-4所示。

![](/images/0500stringboot/0575springboot/blog.010.png)

图4-4器材借用实体属性图

图书信息实体如图4-5所示。

![](/images/0500stringboot/0575springboot/blog.011.png)

图4-5图书信息实体属性图

上机记录实体如图4-6所示。

![](/images/0500stringboot/0575springboot/blog.012.png)

图4-6上机记录实体属性图

### 4.3.3数据库表结构设计
该系统采用的数据库是MySQL，根据该系统的数据存储特点进行数据库关系表的设计。下面是该系统中关键部分关系表的详细信息。

表4-1：商品信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|shangpinbianhao|varchar|200|商品编号|||
|shangpinmingcheng|varchar|200|商品名称|||
|shangpinleixing|varchar|200|商品类型|||
|tupian|longtext|4294967295|图片|||
|jiage|float||价格|||
|shuliang|int||数量|||
|fabushijian|datetime||发布时间|||
|shangpinxiangqing|longtext|4294967295|商品详情|||

表4-2：美食信息评论表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|refid|bigint||关联表id|||
|userid|bigint||用户id|||
|avatarurl|longtext|4294967295|头像|||
|nickname|varchar|200|用户名|||
|content|longtext|4294967295|评论内容|||
|reply|longtext|4294967295|回复内容|||

表4-3：用户表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|username|varchar|100|用户名|||
|password|varchar|100|密码|||
|role|varchar|100|角色||管理员|
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|

表4-4：一卡通

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yikatonghao|varchar|200|一卡通号|||
|mima|varchar|200|密码|||
|xuehao|varchar|200|学号|||
|xingming|varchar|200|姓名|||
|jine|float||金额|||
|banlishijian|datetime||办理时间|||
|crossuserid|bigint||跨表用户id|||
|crossrefid|bigint||跨表主键id|||
|sfsh|varchar|200|是否审核||待审核|
|shhf|longtext|4294967295|审核回复|||

表4-5：器材借用

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|qicaimingcheng|varchar|200|器材名称|||
|qicaileixing|varchar|200|器材类型|||
|shuliang|int||数量|||
|jieyongshizhang|varchar|200|借用时长|||
|jieyongshijian|datetime||借用时间|||
|jieyongshuoming|varchar|200|借用说明|||
|xuehao|varchar|200|学号|||
|xingming|varchar|200|姓名|||
|shouji|varchar|200|手机|||
|sfsh|varchar|200|是否审核||待审核|
|shhf|longtext|4294967295|审核回复|||

表4-6：商品类型

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|shangpinleixing|varchar|200|商品类型|||

表4-7：订单信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|dingdanbianhao|varchar|200|订单编号|||
|shangpinmingcheng|varchar|200|商品名称|||
|shangpinleixing|varchar|200|商品类型|||
|jiage|varchar|200|价格|||
|shuliang|int||数量|||
|zongjiage|varchar|200|总价格|||
|goumaishijian|datetime||购买时间|||
|xuehao|varchar|200|学号|||
|xingming|varchar|200|姓名|||
|shouji|varchar|200|手机|||

表4-8：图书信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|tushubianhao|varchar|200|图书编号|||
|tushumingcheng|varchar|200|图书名称|||
|tushuleixing|varchar|200|图书类型|||
|tupian|longtext|4294967295|图片|||
|shuliang|int||数量|||
|kejieshuliang|int||可借数量|||
|zuozhe|varchar|200|作者|||
|chubanshe|varchar|200|出版社|||
|jieyuexuzhi|longtext|4294967295|借阅须知|||
|tushujieshao|longtext|4294967295|图书介绍|||

表4-9：器材归还

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|qicaimingcheng|varchar|200|器材名称|||
|qicaileixing|varchar|200|器材类型|||
|guihaishuliang|int||归还数量|||
|guihaishuoming|varchar|200|归还说明|||
|guihaishijian|datetime||归还时间|||
|xuehao|varchar|200|学号|||
|xingming|varchar|200|姓名|||
|shouji|varchar|200|手机|||
|sfsh|varchar|200|是否审核||待审核|
|shhf|longtext|4294967295|审核回复|||

表4-10：上机记录

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|mingcheng|varchar|200|名称|||
|shangjiriqi|date||上机日期|||
|xuehao|varchar|200|学号|||
|xingming|varchar|200|姓名|||
|shangjishizhang|varchar|200|上机时长|||
|shangjifeiyong|float||上机费用|||
|shangjishuoming|longtext|4294967295|上机说明|||

表4-11：配置文件

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|name|varchar|100|配置参数名称|||
|value|varchar|100|配置参数值|||

表4-12：图书类型

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|tushuleixing|varchar|200|图书类型|||

表4-13：校园资讯

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|title|varchar|200|标题|||
|introduction|longtext|4294967295|简介|||
|picture|longtext|4294967295|图片|||
|content|longtext|4294967295|内容|||

表4-14：充值信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yikatonghao|varchar|200|一卡通号|||
|xuehao|varchar|200|学号|||
|xingming|varchar|200|姓名|||
|jine|int||金额|||
|chongzhishijian|datetime||充值时间|||
|ispay|varchar|200|是否支付||未支付|

表4-15：图书借阅

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|tushumingcheng|varchar|200|图书名称|||
|tushuleixing|varchar|200|图书类型|||
|kejieshuliang|int||可借数量|||
|shuliang|int||数量|||
|jieyueriqi|date||借阅日期|||
|guihairiqi|date||归还日期|||
|jieyueshuoming|longtext|4294967295|借阅说明|||
|xuehao|varchar|200|学号|||
|xingming|varchar|200|姓名|||
|shouji|varchar|200|手机|||
|sfsh|varchar|200|是否审核||待审核|
|shhf|longtext|4294967295|审核回复|||

表4-16：美食信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|shitangmingcheng|varchar|200|食堂名称|||
|caipinmingcheng|varchar|200|菜品名称|||
|caipinleixing|varchar|200|菜品类型|||
|tupian|longtext|4294967295|图片|||
|kouwei|varchar|200|口味|||
|jiage|float||价格|||
|shuliang|int||数量|||
|caipinjieshao|longtext|4294967295|菜品介绍|||

表4-17：图书归还

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|tushumingcheng|varchar|200|图书名称|||
|tushuleixing|varchar|200|图书类型|||
|shuliang|int||数量|||
|guihaishijian|date||归还时间|||
|guihaishuoming|longtext|4294967295|归还说明|||
|xuehao|varchar|200|学号|||
|xingming|varchar|200|姓名|||
|shouji|varchar|200|手机|||
|crossuserid|bigint||跨表用户id|||
|crossrefid|bigint||跨表主键id|||
|sfsh|varchar|200|是否审核||待审核|
|shhf|longtext|4294967295|审核回复|||

表4-18：扣费信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yikatonghao|varchar|200|一卡通号|||
|xuehao|varchar|200|学号|||
|xingming|varchar|200|姓名|||
|jine|int||金额|||
|koufeishuoming|longtext|4294967295|扣费说明|||
|koufeishijian|datetime||扣费时间|||

表4-19：通知信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|biaoti|varchar|200|标题|||
|xuehao|varchar|200|学号|||
|xingming|varchar|200|姓名|||
|tongzhineirong|longtext|4294967295|通知内容|||
|tongzhishijian|datetime||通知时间|||

表4-20：缴费信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|dingdanbianhao|varchar|200|订单编号|||
|jiaofeixiangmu|varchar|200|缴费项目|||
|xuehao|varchar|200|学号|||
|xingming|varchar|200|姓名|||
|jiaofeijine|float||缴费金额|||
|fabushijian|datetime||发布时间|||
|jiaofeishuoming|varchar|200|缴费说明|||

表4-21：token表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|userid|bigint||用户id|||
|username|varchar|100|用户名|||
|tablename|varchar|100|表名|||
|role|varchar|100|角色|||
|token|varchar|200|密码|||
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|
|expiratedtime|timestamp||过期时间||CURRENT\_TIMESTAMP|

表4-22：会议签到

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|huiyimingcheng|varchar|200|会议名称|||
|xuehao|varchar|200|学号|||
|xingming|varchar|200|姓名|||
|qiandaoshuoming|varchar|200|签到说明|||
|qiandaoshijian|datetime||签到时间|||
|longitude|float||经度|||
|latitude|float||纬度|||
|fulladdress|varchar|200|地址|||

表4-23：体育器材

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|qicaimingcheng|varchar|200|器材名称|||
|qicaileixing|varchar|200|器材类型|||
|tupian|longtext|4294967295|图片|||
|shuliang|int||数量|||
|qicaijieshao|longtext|4294967295|器材介绍|||

表4-24：挂失申请

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yikatonghao|varchar|200|一卡通号|||
|xuehao|varchar|200|学号|||
|xingming|varchar|200|姓名|||
|guashineirong|longtext|4294967295|挂失内容|||
|guashishijian|datetime||挂失时间|||
|sfsh|varchar|200|是否审核||待审核|
|shhf|longtext|4294967295|审核回复|||

表4-25：收藏表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|userid|bigint||用户id|||
|refid|bigint||商品id|||
|tablename|varchar|200|表名|||
|name|varchar|200|名称|||
|picture|longtext|4294967295|图片|||
|type|varchar|200|类型(1:收藏,21:赞,22:踩,31:竞拍参与,41:关注)||1|
|inteltype|varchar|200|推荐类型|||
|remark|varchar|200|备注|||

表4-26：论坛表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|title|varchar|200|帖子标题|||
|content|longtext|4294967295|帖子内容|||
|parentid|bigint||父节点id|||
|userid|bigint||用户id|||
|username|varchar|200|用户名|||
|avatarurl|longtext|4294967295|头像|||
|isdone|varchar|200|状态|||

表4-27：食堂就餐

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|dingdanbianhao|varchar|200|订单编号|||
|caipinmingcheng|varchar|200|菜品名称|||
|caipinleixing|varchar|200|菜品类型|||
|jiage|float||价格|||
|shuliang|int||数量|||
|zongjiage|float||总价格|||
|beizhu|varchar|200|备注|||
|xiadanshijian|date||下单时间|||
|xuehao|varchar|200|学号|||
|xingming|varchar|200|姓名|||
|shouji|varchar|200|手机|||

表4-28：体育器材评论表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|refid|bigint||关联表id|||
|userid|bigint||用户id|||
|avatarurl|longtext|4294967295|头像|||
|nickname|varchar|200|用户名|||
|content|longtext|4294967295|评论内容|||
|reply|longtext|4294967295|回复内容|||

表4-29：学生

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|xuehao|varchar|200|学号|||
|mima|varchar|200|密码|||
|xingming|varchar|200|姓名|||
|xingbie|varchar|200|性别|||
|xuexiao|varchar|200|学校|||
|banji|varchar|200|班级|||
|shouji|varchar|200|手机|||
|sfsh|varchar|200|是否审核||待审核|
|shhf|longtext|4294967295|审核回复|||


# 第五章 系统功能实现
## 5.1系统功能实现
当人们打开系统的网址后，首先看到的就是首页界面。在这里，人们能够看到校园一卡通的导航条，通过导航条进入各信息展示页面进行操作。系统首页界面如图5-1所示：

![](/images/0500stringboot/0575springboot/blog.013.png)

图5-1 系统首页界面

系统注册：在系统注册页面的输入用户注册信息进行注册操作，系统注册界面如图5-2所示：

![](/images/0500stringboot/0575springboot/blog.013.png)

图5-2 系统注册界面

商品信息：在商品信页面输入商品名称和选择商品类型进行查询，可以查看到商品详细信息，并根据需要进行购买操作；商品信息详细页面如图5-3所示：

![](/images/0500stringboot/0575springboot/blog.013.png)

图5-3商品信息详细页面

图书信息：在图书信息页面输入图书名称，选择图书类型和作者进行查询，可以查看到图书详细信息，并根据需要进行借阅操作；图书信息详细页面如图5-4所示：

![](/images/0500stringboot/0575springboot/blog.013.png)

图5-4图书信息详细页面

## 5.2后台模块实现
后台登录，在登录页面正确输入账号、密码和验证后，进入操作系统进行操作；如图5-5所示。

![](/images/0500stringboot/0575springboot/blog.013.png)

图5-5 后台登录界面
### 5.2.1管理员功能实现
管理员进入主页面，主要功能包括对系统首页，个人中心，学生管理，一卡通管理，充值信息管理，扣费信息管理，挂失申请管理，商品类型管理，商品信息管理，订单信息管理，图书类型管理，图书信息管理，图书借阅管理，图书归还管理，通知信息管理，美食信息管理，食堂就餐管理，体育器材管理，器材借用管理，器材归还管理，会议签到管理，缴费信息管理，上机记录管理，论坛管理，系统管理等进行操作。管理员主页面如图5-6所示：

![](/images/0500stringboot/0575springboot/blog.013.png)

图5-6 管理员主界面

管理员点击学生管理。进入学生管理页面输入学号，姓名，性别和选择是否通过进行查询、新增、删除和批量审核学生列表，并根据需要对学生详细信息进行详情，办理，通知，修改和删除操作；如图5-7所示：

![](/images/0500stringboot/0575springboot/blog.013.png)

图5-7学生管理界面

管理员点击一卡通管理。进入一卡通页面输入一卡通号和选择是否通过进行查询、删除和批量审核一卡通列表，并根据需要对一卡通详细信息进行详情，修改和删除操作；如图5-8所示：

![](/images/0500stringboot/0575springboot/blog.013.png)

图5-8一卡通管理界面

管理员点击扣费信息管理。进入扣费信息页面输入一卡通号和姓名进行查询或删除扣费信息列表，并根据需要对扣费详细信息进行详情，修改或删除操作；如图5-9所示：

![](/images/0500stringboot/0575springboot/blog.013.png)

图5-9扣费信息管理界面

管理员点击商品类型管理。进入商品类型页面输入商品类型进行查询、新增或删除商品类型列表，并根据需要对商品类型详细信息进行修改或删除操作；如图5-10所示：

![](/images/0500stringboot/0575springboot/blog.013.png)

图5-10商品类型管理界面

### 5.2.2学生功能实现
学生登录进入系统可以对系统首页，个人中心，充值信息管理，扣费信息管理，挂失申请管理，订单信息管理，图书借阅管理，图书归还管理，通知信息管理，食堂就餐管理，器材借用管理，器材归还管理，会议签到管理，缴费信息管理，上机记录管理等功能进行操作。学生主页面如图5-11所示：

![](/images/0500stringboot/0575springboot/blog.013.png)

图5-11 学生主界面













