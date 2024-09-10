# 0741springboot毕业生信息招聘平台


# [0741springboot毕业生信息招聘平台](https://github.com/GraduationProject-springboot/0741springboot)

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

# [项目清单](https://chenqi1990.site) 包安装运行

### [github 项目仓库](https://github.com/GraduationProject-springboot/allSpringbootProjects) 开源仅有后端代码

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV14HerezEwW?p=97)


# 系统概述
## 1.1 概述
`　`随着社会的快速发展，计算机的影响是全面且深入的。人们的生活水平不断提高，日常生活中毕业生对招聘平台方面的要求也在不断提高，需要招聘平台的人数更是不断增加，使得毕业生信息招聘平台的开发成为必需而且紧迫的事情。毕业生信息招聘平台主要是借助计算机，通过对毕业生信息招聘平台所需的信息管理，增加毕业生选择，同时也方便对广大招聘平台的及时查询、修改以及对毕业生信息的及时了解。毕业生信息招聘平台对毕业生带来了更多的便利, 该系统通过和数据库管理系统软件协作来满足毕业生的需求。
## 1.2课题意义
随着全球信息化的发展，人们的生活节奏越来越快，对信息的时效性越来越重视。以传统的宣传方式为载体的传统媒介早已不能满足毕业生对获取信息的方式、便捷性的需求。所以毕业生信息招聘平台渐渐成为毕业生关注的焦点。首先，毕业生信息招聘平台，网上获取信息的实时性、便捷性要远远高于传统媒介。系统一经上线，无论毕业生在世界的哪个角落，只要能够连接互联网，就能在第一时间获得想要的信息。

以往的毕业生信息招聘平台相关信息管理，都是工作人员手工统计。这种方式不但时效性低，而且需要查找和变更的时候很不方便。随着科学的进步，技术的成熟，计算机信息化也日新月异的发展，社会也已经深刻的认识，计算机功能非常的强大，计算机已经进入了人类社会发展的各个领域，并且发挥着十分重要的作用。

计算机技术在现代管理中的应用，使计算机成为毕业生应用现代技术的重要工具。能够有效的解决获取信息便捷化、全面化的问题，提高效率。
## 1.3 主要内容
毕业生信息招聘平台从功能、数据流程、可行性、运行环境等方面进行需求分析。对招聘平台的数据库、功能进行了详细设计。分析了主要界面设计和相关组件设计，对招聘平台的具体实现进行了介绍，从而达到对毕业生信息招聘平台的管理。

详细内容介绍，将在以下六章中详细阐述：

第一章、绪论，介绍了研究课题选择的背景及意义、研究现状，简要介绍了本文的章节内容。

第二章、引入技术知识，通过引入关键技术进行开发，向系统中涉及直观表达的技术知识。

第三章、重点分析了系统的分析，从系统强大的供需市场出发，对系统开发的可行性，系统流程以及系统性能和功能进行了探讨。

第四章、介绍了系统的详细设计方案，包括系统结构设计和数据库设计。

第五章、系统设计的实现，通过对系统功能设计的详细说明，论证了系统的结构。

第六章、系统的整体测试，评判系统是否可以上线运行。

采用Java技术，从数据库中获取数据、向数据库中写入数据，实现系统直接对数据库进行各种操作，在网页中加入动态内容，从而实现毕业生信息招聘平台所需要的各种基本功能。


# 2 系统开发环境
## 2.1 Spring Boot框架
Spring Boot是Pivotal团队的一个新框架，旨在简化新Spring应用程序的初始设置和开发。该框架使用特定的配置方法，无需开发人员定义样板配置。通过这种方式，Spring Boot旨在成为蓬勃发展的快速应用程序开发领域的领导者。
Spring Boot特点：
1、创建一个单独的Spring应用程序；
2、嵌入式Tomcat，无需部署WAR文件；
3、简化Maven配置；
4、自动配置Spring；
5、提供生产就绪功能，如指标，健康检查和外部配置；
6、绝对没有代码生成和XML的配置要求；
`  `安装步骤：
`   `最基本的是，Spring Boot是一个可以被任何项目的构建系统使用的库集合。 为简单起见，该框架还提供了一个命令行界面，可用于运行和测试Boot应用程序。 可以从Spring存储库手动下载和安装框架的已发布版本，包括集成的CLI（命令行界面）。 更简单的方法是使用Groovy enVironment Manager（GVM），它负责处理Boot版本的安装和管理。 可以从GVM命令行GVM install springboot安装Boot及其CLI。 在OS X上安装Boot时可以使用Homebrew包管理器。要完成安装，首先使用brew tap pivotal / tap切换到pivotal存储库，然后执行brew install springboot命令。



## 2.2 JAVA简介
Java主要采用CORBA技术和安全模型，可以在互联网应用的数据保护。它还提供了对EJB（Enterprise JavaBeans）的全面支持，java servlet API，JSP（java server pages），和XML技术。Java是一种计算机编程语言，具有封装、继承和多态性三个主要特性，广泛应用于企业Web应用程序开发和移动应用程序开发。Java语言和一般编译器以及直译的区别在于，Java首先将源代码转换为字节码，然后将其转换为JVM的可执行文件，JVM可以在各种不同的JVM上运行。因此，实现了它的跨平台特性。虽然这使得Java在早期非常缓慢，但是随着Java的开发，它已经得到了改进。
## 2.3访问数据库实现方法
（1）首先介绍一下web数据库搜索网络上的基本步骤：

第一步：检查消费者的数据，

第二步：你必须建立与数据库的连接;

第三步：搜索数据库;

第四步：数据的结构;

第五步：该毕业生 的结果被示出。

（2）系统，直到我MYSQL5.0 PHP集成开发环境，如使用WAMP服务器处于开机状态，并且更容易访问数据库的报告开发环境：

一个连接到MySQL数据库服务器Mysql\_connect-;

语法：资源的mysql\_connect（主机，毕业生 名，密码）;

请选择数据库：mysql\_select\_db（数据库链接标识的名称）;

关闭数据库：则mysql\_close（）;
## 2.4系统对MySQL数据库的两种连接方式
活动的MySQL/ MySQL库，或使用ODBC接口，MySQL数据库是一个双向链接。永久及非永久连接。

（1）永久连接：一个更永久的连接请求的最大优点是可以非常有效的客户站在密切的联系，当连接到MySQL服务器，就更好了。在起草该页面每一个孩子在这个过程中，而不是仅仅在任何时候，只有在到MySQL服务器请求连接的生命周期，一旦连接。此子过程是建立到服务器的单独连接可以是永久性的。

（2）非永久连接：他是短路。提交顺路到Web服务器，服务器处理请求并请求的页面，你要发送的浏览器客户端，然后连接断开。对于大多数网站，它经常通过有效高效率有关，但在大多数情况下，所使用的连接，但它是一个完整的时间，以避免出现任何问题，并可以增加的容量服务器承载。
## 2.5 MySql数据库
Mysql的语言是非结构化的，毕业生 可以在数据上进行工作。因为Mysql的语言和结构比较简单，但是功能和存储信息量很强大，其速度、可靠性和适应性而备受关注并得到了普遍的应用。Mysql数据库在编程过程中的作用是很广泛的，为毕业生 进行数据查询带来了方便。Mysql数据库的应用特点：灵活性强，功能强大，语言相对要简洁很多。 

数据流程分析主要就是数据存储的储藏室，它是在计算机上进行的，而不是现实中的储藏室。数据库管理主要是数据存储、修改和增加以及数据表的建立。数据表的建立，可以对数据表中的数据进行调整，数据的重新组合及重新构造，保证数据的安全性。介于数据库的功能强大等特点，本系统的开发主要应用了Mysql进行对数据的管理。
# 3 需求分析
## 3.1技术可行性：技术背景     
毕业生信息招聘平台是在Windows操作系统中进行开发运用的，而且目前PC机的各项性能已经可以胜任普通网站的web服务器。系统开发所使用的技术也都是自身所具有的，也是当下广泛应用的技术之一。

系统的开发环境和配置都是可以自行安装的，系统使用Java开发工具，使用比较成熟的Mysql数据库进行对系统前台及后台的数据交互，根据技术语言对数据库，结合需求进行修改维护，可以使得网站运行更具有稳定性和安全性，从而完成实现网站的开发。

（1）硬件可行性分析

系统管理及信息分析的设计对于所使用的计算机没有什么硬性的要求，计算机只要可以正常的使用进行代码的编写及页面设计就可行，主要是对于服务器有些要求，对于平台搭建完成要上传的服务器是有一定的要求的，服务器必须选择安全性比较高的，然后就是在打开网站必须顺畅，不能停顿太长时间；性价比高；安全性高。

（2）软件可行性分析

开发整个系统使用的是云计算，流量的可扩展性和基于流量的智能调整云计算的优点就是流量的可扩展性和基于流量的智能调整，保障了数据信息能够得到及时的备份，整个系统可以安全有效的运行。 

因此，我们从两个方面进行了可行性研究，可以看出系统的开发没有问题。
## 3.2经济可行性
在毕业生信息招聘平台开发之前所做的市场调研及与其相关的其他管理系统，都是没有任何费用的。所有的调查研究都是通过开发者自己的努力，所有的工作也都是自己亲力亲为的。在碰到自己比较难以解决的问题时，大多数是通过指导老师和同学的帮助进行相关问题的解决。所以对于毕业生信息招聘平台的开发在经济上是完全可行的，没有任何费用支出的。 

使用比较成熟的技术，系统是基于Java的开发，采用Mysql数据库。所以系统在开发人力、财力方面的要求不高，具有经济可行性。

## 3.3操作可行性： 
可操作性主要是对在毕业生信息招聘平台设计完成后，毕业生的使用体验度，以及管理员可以通过系统随时管理相关的数据信息，并且对于管理员、企业、毕业生三个角色，都可以简单明了的进入到自己的系统界面，通过界面可以简单明了地操作功能模块，方便毕业生信息的操作需求和管理员管理数据信息。对于系统的操作，不需要专业人员都可以直接进行功能模块的操作管理，所以毕业生信息招聘平台的可操作性是完全可以的。本系统的操作使用的也是界面窗口进行登录，所以操作人员只要会简单的电脑操作就完全可以的。
## 3.4系统设计规则
本毕业生信息招聘平台采用Java技术，Mysql数据库开发，充分保证了系统稳定性、完整性。 

毕业生信息招聘平台的设计与实现的设计思想如下： 

1. 操作简单方便、系统界面安全良好：简单明了的页面布局，方便查询管理的相关信息。

2、即时可见：对毕业生信息招聘平台信息的处理将立马在对应地点可以查询到，从而实现“即时发布、即时见效”的系统功能。 

3、功能的完善性：可以管理管理员；首页、个人中心、企业管理、空中宣讲会管理、招聘岗位管理、毕业生管理、个人简历管理、求职信息管理、信息咨询管理、岗位应聘管理、线上面试管理、面试回复管理、试卷管理、试题管理、管理员管理、论坛管理、系统管理、考试管理，

企业；首页、个人中心、空中宣讲会管理、招聘岗位管理、信息咨询管理、岗位应聘管理、线上面试管理、面试回复管理、试卷管理、试题管理、考试管理，

毕业生；首页、个人中心、个人简历管理、求职信息管理、信息咨询管理、岗位应聘管理、线上面试管理、面试回复管理、我的收藏管理、考试管理，

前台首页；首页、空中宣讲会、招聘岗位、求职信息、论坛信息、试卷列表、招聘资讯、个人中心、后台管理模块的修改和维护操作。

## 3.5系统流程和逻辑
系统业务流程图，如图所示：

![](/images/0700stringboot/0741springboot/blog.001.png)

图3-1登录流程图

![](/images/0700stringboot/0741springboot/blog.002.png) 

图3-2添加信息流程图

![](/images/0700stringboot/0741springboot/blog.003.png) 

图3-3注册信息流程图


# 4系统概要设计
## 4.1 概述
毕业生信息招聘平台基于Web服务模式，是一个适用于Internet环境下的模型结构。只要毕业生能连上Internet,便可以在不受时间、地点的限制来使用这个系统。毕业生信息招聘平台工作原理图，如图4-1所示：

![](/images/0700stringboot/0741springboot/blog.004.png)

图4-1  系统工作原理图
## 4.2 系统结构
本系统架构网站系统，本系统的具体功能如下：

毕业生信息招聘平台登陆界面

用户登录

密码正确

管理员界面

毕业生界面

企业界面

![](/images/0700stringboot/0741springboot/blog.005.png)

图4-2系统功能结构图

管理员功能结构图，如图4-3所示：

![](/images/0700stringboot/0741springboot/blog.006.png)

图4-3 管理员功能结构图

毕业生功能结构图，如图4-4所示：

![](/images/0700stringboot/0741springboot/blog.007.png)

图4-4 毕业生功能结构图

企业功能结构图，如图4-5所示：

![](/images/0700stringboot/0741springboot/blog.008.png)

图4-5企业功能结构图

## 4.3. 数据库设计
### 4.3.1 数据库实体
管理员信息图，如图4-6所示：

![](/images/0700stringboot/0741springboot/blog.009.png)

` `图4-6 管理员信息图

个人简历实体属性图，如图4-7所示：

![](/images/0700stringboot/0741springboot/blog.010.png)

图4-7个人简历实体属性图

企业管理实体属性图如图4-8所示。

![](/images/0700stringboot/0741springboot/blog.011.png)

图4-8企业管理实体属性图

招聘岗位信息实体属性图如图4-9所示。

![](/images/0700stringboot/0741springboot/blog.012.png)

`      `图4-9招聘岗位信息实体属性图

### 4.3.2 数据库设计表
## 4.4 数据表
将数据库概念设计的E-R图转换为关系数据库。在关系数据库中，数据关系由数据表组成，但是表的结构表现在表的字段上。

表4-1 allusers表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|int|11|NOT NULL|
|username|varchar|50|default NULL|
|pwd|varchar|50|default NULL|
|cx|varchar|50|default NULL|
表4-2：biyesheng表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|` `int|11|NOT NULL |
|addtime|varchar|50|default NULL|
|yonghuming|varchar|50|default NULL|
|mima|varchar|50|default NULL|
|xingming|varchar|50|default NULL|
|xingbie|varchar|50|default NULL|
|touxiang|varchar|50|default NULL|
|zhuanye|varchar|50|default NULL|
|shouji|varchar|50|default NULL|
|youxiang|varchar|50|default NULL|
表4-3：gangweiyingpin表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|int|11|NOT NULL|
|addtime|varchar|50|default NULL|
|gangweimingcheng|varchar|50|default NULL|
|xingye|varchar|50|default NULL|
|qiyebianhao|varchar|50|default NULL|
|qiyemingcheng|varchar|50|default NULL|
|chengshi|varchar|50|default NULL|
|yingpinneirong|varchar|50|default NULL|
|qiuzhijianli|varchar|50|default NULL|
|beizhu|varchar|50|default NULL|
|yonghuming|varchar|500|default NULL|
|xingming|varchar|500|default NULL|
|zhuanye|varchar|500|default NULL|
|shouji|varchar|500|default NULL|
|sfsh|varchar|500|default NULL|
|shhf|varchar|500|default NULL|

表4-4：gerenjianli表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|` `int|11|NOT NULL|
|addtime|varchar|50|` `default NULL|
|yonghuming|varchar|50|` `default NULL|
|xingming|varchar|50|` `default NULL|
|xingbie|varchar|50|` `default NULL|
|touxiang|varchar|50|` `default NULL|
|juzhushengfen|varchar|50|` `default NULL|
|juzhuchengshi|varchar|50|` `default NULL|
|chushengnianyue|varchar|50|` `default NULL|
|gongzuoshijian|varchar|50|` `default NULL|
|dangqianzhuangtai|varchar|10|` `default '否'|
|shouji|varchar|50|` `default NULL|
|zhuanye|varchar|50|` `default NULL|
|zuigaoxueli|varchar|50|` `default NULL|
|jianlifujian|varchar|50|` `default NULL|

表4-5：kongzhongxuanjianghui表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|ID|int|11|NOT NULL|
|addtime|varchar|50|default NULL|
|qiyebianhao|varchar|50|default NULL|
|qiyemingcheng|varchar|50|default NULL|
|guimo|varchar|50|default NULL|
|xingzhi|varchar|50|default NULL|
|tupian|varchar|50|default NULL|
|lianxiren|varchar|500|default NULL|
|lianxidianhua|varchar|500|default NULL|
|xuanchuanshipin|varchar|500|default NULL|
|bangongdizhi|varchar|500|default NULL|
|xuanjiangneirong|varchar|500|default NULL|


表4-6：mianshihuifu表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|int|11|NOT NULL|
|addtime|varchar|50|default NULL|
|mianshibiaoti|varchar|50|default NULL|
|mianshihuifu|varchar|50|default NULL|
|huifufujian|varchar|50|default NULL|
|huifushijian|varchar|50|default NULL|
|beizhu|varchar|50|default NULL|
|qiyebianhao|varchar|50|default NULL|
|qiyemingcheng|varchar|50|default NULL|
|yonghuming|varchar|500|default NULL|
|xingming|varchar|10|default '否'|
|shouji|varchar|500|default NULL|
|sfsh|varchar|500|default '否'|
|shhf|varchar|500|default '是'|

#########

# 第5章 系统详细设计
## 5.1管理员功能模块
管理员登录，管理员通过输入用户名、密码、角色等信息进行系统登录，如图5-1所示。

![](/images/0700stringboot/0741springboot/blog.013.png)

图5-1管理员登录界面图

管理员登录进入毕业生信息招聘平台可以查看首页、个人中心、企业管理、空中宣讲会管理、招聘岗位管理、毕业生管理、个人简历管理、求职信息管理、信息咨询管理、岗位应聘管理、线上面试管理、面试回复管理、试卷管理、试题管理、管理员管理、论坛管理、系统管理、考试管理等内容，如图5-2所示。

![](/images/0700stringboot/0741springboot/blog.014.png)

图5-2管理员功能界面图

空中宣讲会管理，在空中宣讲会管理页面可以填写企业编号、企业名称、规模、性质、图片、联系人、联系电话、宣传视频、办公地址等内容，并可根据需要对空中宣讲会管理进行添加，修改或删除等操作，如图5-3所示。

![](/images/0700stringboot/0741springboot/blog.015.png)

图5-3空中宣讲会管理界面图

招聘岗位管理，在招聘岗位管理页面可以填写岗位名称、行业、岗位要求、专业要求、岗位性质、图片、薪资待遇、工作时间、城市、企业编号、企业名称、联系人、联系电话等内容，并可根据需要对招聘岗位管理进行添加，修改或删除等操作，如图5-4所示。

![](/images/0700stringboot/0741springboot/blog.016.png)

图5-4招聘岗位管理界面图



毕业生管理，在毕业生管理页面可以填写用户名、密码、姓名、性别、头像、专业、手机、邮箱等进行添加，修改，删除或查看详细内容等操作，如图5-5所示。

![](/images/0700stringboot/0741springboot/blog.017.png)

图5-5毕业生管理界面图

个人简历管理，在个人简历管理页面可以查看用户名、密码、姓名、性别、头像、居住省份、居住城市、出生年月、工作时间、当前状态、手机、专业、最高学历、简历附件等内容，并可根据需要对个人简历管理信息进行添加，修改，删除或详细内容等操作，如图5-6所示。 ![](/images/0700stringboot/0741springboot/blog.018.png)

图5-6个人简历管理界面图

信息咨询管理 ，在信息咨询管理页面可以查看咨询标题、企业编号、企业名称、咨询日期、备注、用户名、姓名、手机、审核回复等内容，并可根据需要对信息咨询管理进行添加，修改，删除或详细内容等操作，如图5-7所示。

![](/images/0700stringboot/0741springboot/blog.019.png)

图5-7信息咨询管理界面图

线上面试管理 ，在线上面试管理页面可以查看面试标题、面试附件、企业编号、企业名称、联系电话、日期、用户名、姓名、手机、专业等内容，并可根据需要对线上面试管理进行添加，修改，删除或详细内容等操作，如图5-8所示。

![](/images/0700stringboot/0741springboot/blog.020.png)

图5-8线上面试管理界面图

面试回复管理 ，在面试回复管理页面可以查看面试标题、回复附件、回复时间、备注、企业名称、用户名、姓名、手机、审核回复等内容，并可根据需要对面试回复管理进行添加，修改，删除或详细内容等操作，如图5-9所示。

![](/images/0700stringboot/0741springboot/blog.021.png)

图5-9面试回复管理界面图

论坛管理 ，在论坛管理页面可以查看帖子标题、用户名、状态等内容，并可根据需要对论坛管理进行添加，修改，删除或详细内容等操作，如图5-10所示。

![](/images/0700stringboot/0741springboot/blog.022.png)

图5-10论坛管理界面图






## 5.2企业功能模块
企业登录进入毕业生信息招聘平台可以查看首页、个人中心、空中宣讲会管理、招聘岗位管理、信息咨询管理、岗位应聘管理、线上面试管理、面试回复管理、试卷管理、试题管理、考试管理等内容，如图5-11所示。

![](/images/0700stringboot/0741springboot/blog.023.png)图5-11企业功能界面图

个人信息，在个人信息页面通过填写企业编号、密码、企业名称、图片、规模、性质、联系人、联系电话等内容并可根据需要对个人信息进行查看、修改，如图5-12所示。

![](/images/0700stringboot/0741springboot/blog.024.png)

图5-12个人信息界面图

空中宣讲会管理，在空中宣讲会管理页面可以填写企业编号、企业名称、规模、性质、图片、联系人、联系电话、宣传视频、办公地址等内容，并可根据需要对空中宣讲会管理详细内容进行详情、修改、删除操作，如图5-13所示。

![](/images/0700stringboot/0741springboot/blog.025.png)

图5-13空中宣讲会管理界面图

招聘岗位管理，在招聘岗位管理页面可以查看岗位名称、行业、岗位要求、专业要求、岗位性质、图片、薪资待遇、工作时间、城市、企业编号、企业名称、联系人、联系电话等内容，并可根据需要对招聘岗位管理进行详情、修改、删除等操作，如图5-14所示。

![](/images/0700stringboot/0741springboot/blog.026.png)

图5-14招聘岗位管理界面图

信息咨询管理，在信息咨询管理页面可以查看咨询标题、企业编号、企业名称、咨询日期、备注、用户名、姓名、手机、审核回复等内容，并可根据需要对信息咨询管理进行详情等操作，如图5-15所示。

![](/images/0700stringboot/0741springboot/blog.027.png)

图5-15信息咨询管理界面图

线上面试管理，在线上面试管理页面可以查看面试标题、面试附件、企业编号、企业名称、联系电话、日期、用户名、姓名、手机、专业等内容，并可根据需要对线上面试管理进行详情等操作，如图5-16所示。

![](/images/0700stringboot/0741springboot/blog.028.png)

图5-16线上面试管理界面图

试卷管理，在试卷管理页面可以查看试卷名称、考试时长、试卷状态等内容，并可根据需要对试卷管理进行详情、修改、删除等操作，如图5-17所示。

![](/images/0700stringboot/0741springboot/blog.029.png)

图5-17试卷管理界面图


考试记录，在考试记录页面可以查看用户ID、试卷、考试得分等内容，并可根据需要对考试记录进行查看详情等操作，如图5-18所示。

![](/images/0700stringboot/0741springboot/blog.030.png)

图5-18考试记录界面图






## 5.3毕业生功能模块
毕业生登录进入毕业生信息招聘平台可以查看首页、个人中心、个人简历管理、求职信息管理、信息咨询管理、岗位应聘管理、线上面试管理、面试回复管理、我的收藏管理、考试管理等内容，如图5-19所示。

![](/images/0700stringboot/0741springboot/blog.031.png)图5-19毕业生功能界面图

线上面试管理，在线上面试管理页面通过填写面试标题、面试附件、企业编号、企业名称、联系电话、日期、用户名、姓名、手机、专业等内容并可根据需要对线上面试管理进行详情、面试回复，如图5-20所示。

![](/images/0700stringboot/0741springboot/blog.032.png)

图5-20线上面试管理界面图

面试回复管理，在面试回复管理页面可以填写面试标题、回复附件、回复时间、备注、企业名称、用户名、姓名、手机、审核回复等内容，并可根据需要对面试回复管理详细内容操作，如图5-21所示。

![](/images/0700stringboot/0741springboot/blog.033.png)

图5-21面试回复管理界面图

我的收藏管理，在我的收藏管理页面可以查看收藏ID、表名、收藏名称、收藏图片等内容，并可根据需要对我的收藏管理进行详情、删除等操作，如图5-22所示。

![](/images/0700stringboot/0741springboot/blog.034.png)

图5-22我的收藏管理界面图
#########
考试管理，在考试管理页面可以查看用户ID、试卷、考试得分等内容，并可根据需要对考试管理查看详情等操作，如图5-23所示。

![](/images/0700stringboot/0741springboot/blog.030.png)

图5-23考试管理界面图
## 5.4 前台首页功能模块
毕业生信息招聘平台首页、空中宣讲会、招聘岗位、求职信息、论坛信息、试卷列表、招聘资讯、个人中心、后台管理功能。网站首页效果图如图5-24所示：

![](/images/0700stringboot/0741springboot/blog.035.png)

图5-24首页界面

`   `登录、毕业生注册，在毕业生注册页面通过填写用户名、密码、姓名、专业、手机、邮箱等信息进行登录、毕业生注册，如图5-25所示。

![](/images/0700stringboot/0741springboot/blog.036.png)
######### ![](/images/0700stringboot/0741springboot/blog.037.png)
图5-25登录、毕业生注册界面图

招聘岗位，在招聘岗位页面通过填写专业、岗位要求、专业要求、岗位性质等内容进行咨询、应聘，如图5-26所示。

![](/images/0700stringboot/0741springboot/blog.038.png)

图5-26招聘岗位界面图
#########
#########
#########
空中宣讲会，在空中宣讲会页面通过填写企业编号、规模、性质、联系人、联系电话、办公地址等信息进行点我收藏，如图5-27所示。

![](/images/0700stringboot/0741springboot/blog.039.png)

图5-27空中宣讲会界面图

求职信息，在求职信息页面可以查看求职标题、图片、期望职位、期望行业、工作城市、薪资要求等信息并可以进行提交，如图5-28所示：

![](/images/0700stringboot/0741springboot/blog.040.png)

图5-28求职信息界面图











