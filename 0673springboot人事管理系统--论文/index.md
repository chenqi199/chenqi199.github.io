# 0673springboot人事管理系统--论文


# [0673springboot人事管理系统--论文](https://github.com/GraduationProject-springboot/0673springboot)

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

# [项目清单](https://chenqi1990.site) 包安装运行

### [github 项目仓库](https://github.com/GraduationProject-springboot/allSpringbootProjects) 开源仅有后端代码

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV14HerezEwW?p=28)


# 绪论
## 1.1 项目研究的背景
困扰管理层的许多问题当中,人事管理是一定不敢忽视的一块。但是管理好人事又面临很多麻烦需要解决,例如有几个方面:第一,公司往往员工人数都比较多,如何保证能够管理到每一员工;第二,如何在工作琐碎,记录繁多的情况下将人事变动的情况反应给公司领导相关部门决策,等等。在此情况下开发一款人事管理系统，于是乎变得非常合乎时宜。

经过网上调查和搜集数据,我们可以发现人事管理方面的系统在公司中并不是相当普及,公司在人事管理方面的可以有许多改进。实际上如今信息化成为一个未来的趋势或者可以说在当前现代化的城市典范中,信息化已经成为主流,开发一个人事管理系统一方面可能会更合乎时宜,另一方面来说也可以提高公司在人事管理方面的效率给相关部门人的工作带来一定的便利。
## 1.2开发意义
人类的进步带动信息化的发展，使人们生活节奏越来越快，所以人们越来越重视信息的时效性。以往的管理方式已经满足不了人们对获得信息的方式、方便快捷的需求。即人事管理系统慢慢的被人们关注。首先，网上获取信息十分的实时、便捷，只要系统在线状态，无论在哪里都能第一时间查找到理想的信息。

计算机技术在管理中成为人们的重要工具。可以有效快捷的解决想要获取的信息，提高工作效率。
## 1.3项目研究内容与结构
人事管理管理方面的任务繁琐,以至于公司每年都在人事管理这方面投入较多的精力却效果甚微,人事管理系统的目标就是为了能够缓解人事管理工作方面面临的压力,让人事管理方面的工作变得更加高效准确。

本项目在开发和设计过程中涉及到原理和技术有: B/S、java技术和MySQL数据库等等；将按以下章节进行开发设计；

1. 绪论；剖析项目背景,说明研究的内容。
1. 开发技术；系统主要使用了java技术，b/s模式和myspl数据库，并对此做了介绍。
1. 系统分析；包罗了系统总体结构、对系统的性能、功能、流程图进行了分析。
1. 系统设计；对软件功能模块和数据库进行详细设计。
1. 系统总体设计；对系统管理员，教师和学生的功能进行描述。
1. 对系统进行测试。
1. 总结心得；在论文最后结束章节总结了开发这个系统和撰写论文时候自己的总结、感想,包括致谢。
# 2开发技术介绍
## 2.1 B/S架构
B/S结构是目前使用最多的结构模式，它可以使得系统的开发更加的简单，好操作，而且还可以对其进行维护。使用该结构时只需要在计算机中安装数据库，和一些很常用的浏览器就可以了。浏览器就会与数据库进行信息的连接，可以实现很多的功能，B/S结构是可以直接进行使用的，而且B/S结构在使用中极大的减少了工作的维护。基于B/S的软件，所有的数据库之间都是相互独立的，因此是非常安全的。因为基于B/S结构可以清楚的看到系统正在处理的业务，并且能够及时的让管理人员做出决策，这样就可以避免企业的损失。B/S结构的基本特点是集中式的管理模式，用户使用系统生成数据后，这些数据就可以存储到系统的数据库中，方便日后能够用到，这样就可以满足人们的所有的需求。

![](/images/0600stringboot/0673springboot/blog.002.png)

图2-1  B/S模式三层结构图
## 2.2Java语言简介
Java是由SUN公司推出，该公司于2010年被oracle公司收购。Java本是印度尼西亚的一个叫做爪洼岛的英文名称，也因此得来java是一杯正冒着热气咖啡的标识。Java语言在移动互联网的大背景下具备了显著的优势和广阔的前景，它是面向对象的，分布式的，动态的，具有平台无关性、安全性、健壮性。Java语言的基本语句语法和C++一样，但是它面向对象的技术更加彻底，因为Java要求将所有的内容都必须封装成类，把类作为程序的基本单位。由于不允许类外有变量、方法。 Java语言的分布式体现在数据分布和操作分布，它是面向网络的语言，可以处理TCP/IP协议，它也支持客户机/服务器的计算模式。Java语言的动态性是指类在运行时是动态安装的，使得Java可以动态的维护程序。Java不支持指针，对内存访问的所有操作都是通过对象实例化实现的，这样就避免了指针操作中易产生的错误，同时也预防了病毒对系统的破坏和威胁。

Java语言的编程风格与C语言非常接近，它继承了C++面向对象技术的核心，它面世之后发展迅速，非常流行，对高级C语言形成了很大的冲击。业内人士称之为“一次编译、到处执行”。当然java也有缺点，在每次执行编译后，字节码都需要消耗一定的时间，在某些程度上降低了性能。但是这并不影响java成为此次设计语言的选择。Java语言简单易学，使用它的编程时间短，功能性强，开发者学习起来更简便、更快。Java的主要特性有以下几个：

1.面向对象

面向对象有四个特点：封装、继承、多态、抽象。抽象是指忽略一个问题中的次要部分，关注主要部分。多态是指对同一种消息做出的不同反应。继承是指在原有的父类方法基础上增加自己独有的方法，而不改变原来父类。

2.平台无关性、

Java编译出来的是字节码，直接由虚拟机执行。在任何平台上，只要有Java虚拟机，Java代码都能运行。

3.可靠性和安全性

Java对内存的访问都必须通过对象的实例变量来实现，避免了指针中出现的错误。

\4. 多线程	

Java提供了多线程功能，利用编程实现同一时间同时工作的功能。
## 2.3MySQL 介绍
在软件项目，通过经营性数据的数据库，可以保证其安全，独立和数据一致，访问数据的系统来提供，所以有效减少时间程序员开发应用程序。

MySQL可以支持多线程，可以方便使用系统的资源，提高运行的速度。并提供odbc、jdbc和tcp/ ip，以各种形式连接到MySQL; 功能方面表现欠缺，规模小，但对于这个系统就足够了。

因为MySQL是源代码对外开放的，所以任何人都可以通过相应的方法下载，并根据个性化需求进行修改。 由于MySQL的速度，可靠性和适应性，MySQL受到重视。

MySQL虽然功能可能不是很强大，但由于其开源，广泛传播，导致很多人都意识到这个数据库。
## 2.4MySQL环境配置
本系统的数据使用的是MySQL,所以要将MySQL安装到指定目录，如果下载的是非安装的MySQL压缩包，直接解压到指定目录就可以了。然后点击C:\Program Files\MySQL\bin\winMySQLadmin.exe这个文件其中C:\Program Files\MySQL是MySQL安装目录。输入winMySQLadmin的初始用户、密码（注：这不是MySQL里的用户、密码）随便填不必在意，确定之后右下角任务的启动栏会出现一个红绿灯的图标，红灯亮代表服务停止，绿灯亮代表服务正常，左击这个图标->winnt->install the service 安装此服务，再左击这个图标->winnt->start the service 启动MySQL服务。

修改MySQL数据库的root密码。用cmd进入命令行模式输入如下命令:

cd C:\Program Files\MySQL\bin

MySQLadmin -u root -p password 123

回车出现Enter password: ，这是要输入原密码. 刚安装时密码为空,所以直接回车，此时MySQL 中账号 root 的密码被改为 123 安装完毕。
## 2.5SpringBoot技术
本技术是Java平台的开源应用框架，其目的地简单化Spring的初始搭建和开发的过程。默认配置了很多框架的使用方式，自动加载Jar包，为了让用户尽可能快的跑起来spring应用程序。

SpringBoot的主要优点有：1.为所有Spring开发提供了一个更快、更广泛的入门体验；2.零配置；3.集成了大量常用的第三方库的配置；4.提供准备好的特性。当今，Java领域开发者几乎都在使用SpringBoot，在开发领域逐渐成为领导者。

# 3系统分析
## 3.1可行性分析
在开发系统之前要进行系统可行性分析，目的是在用最简单的方法去解决最大的问题，程序一旦开发出来满足了员工的需要，所带来的利益也很多。下面我们将从技术、操作、经济等方面来选择这个系统最终是否开发。
### 3.1.1技术可行性
本系统开发选择java技术，java技术是一个完全面向对象的语言，为开发者提供了丰富的类库，大大减少了使用windows编程的难度,减少开发人员在设计算法上的难度，作为java技术开发 Visual Studio更是一个必不可少的角色，它友好的界面，以及强大的功能，给程序开发人员带来了很多方便，加上环境简单，转移方便，无疑使此系统最佳的选择。所以后台设计选择使用MySQL数据库主要用来的建立和维护信息。对于系统开发要求应具备功能完善、易于操作等优点，后台数据库的要求则是能够建立和维护数据信息的统一性和完整性。

依据上述目标来分析本系统的硬件如下：

奔腾3的处理器；

内存是 2G；

硬盘是50G；

操作系统是Window 10；

在软件方面的话，安装了Visul Studio和MySQL数据库开发工具。根据以上的软件与硬件要求，得到这个系统的技术是可行的。
### 3.1.2经济可行性
基于springboot的人事管理系统，该系统软件开发仅需要一台普通的计算机便可完成实现开发，其成本很低。另外，作为毕业设计作品来讲，开发成本基本上可以忽略不计，且该系统软件的投入使用，可以实现更加快速高效的人事管理，同时还能实现对人力资源和管理资源的有效节约，该人事管理系统在经济上完全可行。
### 3.1.3操作可行性
现在随着科技的飞速发展，计算机早已经进入了人们的日常生活中，人们的工作环境也不像以前有那么多的要求，需要员工一定要到公司办公，有的工作在家也可以完成。这使得人们的工作效益有了很大的提高。操作的多样性也变高了。因此，管理的计算机化，智能化是社会发展而带来的必然趋势，各种智能的软件层出不穷，不同的软件能完成员工不同的需求，这不仅提高了工作效率还能完成一些特定的一些需求。本系统不仅界面简洁明了还采用可视化界面，员工只要用鼠标和键盘就可以完成对相关信息的修改，删除，添加等操作。因为这个系统的操作十分简单，方便上手，对于第一次使用系统的人，只需要很少的时间就可以上手操作。由此可见，本系统在操作上是可行的。
## 3.2系统性能需求分析
对系统性能进行分析，可对系统反应度、界面简洁清晰度、储存能性、易学性和稳定性进行分析；

系统反应度：同时上万人在线时反应时间应该在两三秒以内。

界面简洁清晰：系统界面要求简单明了，操作简单，员工操作容易上手。

储存性能高：人事管理系统中需要存储的信息有很多，所以对系统的存储量要求很高，因此数据库就应该很强大，才能保证信息能安全稳定的进行存储；

易学性：该系统在操作上必须简单好上手，没有很多复杂的操作，只需要简单的进行学习就能操作该系统。

稳定性：要求人事管理系统运行要稳定，界面清楚、字体清晰等。
## 3.3系统功能分析
考虑到实际生活中在人事管理方面的需要以及对该系统认真的分析,将系统权限按管理员和员工这两类涉及用户划分。

(a)管理员；管理员使用本系统涉到的功能主要有：首页，个人中心，员工管理，部门管理，员工考勤管理，请假申请管理，加班申请管理，员工工资管理，招聘计划管理，员工培训管理，部门培训管理，员工详细管理等功能。管理员用例图如图3-1所示。

![](/images/0600stringboot/0673springboot/blog.003.png)

图3-1管理员用例图

` `(b)员工；员工使用本系统涉到的功能主要有：首页，个人中心，员工考勤管理，请假申请管理，加班申请管理，员工工资管理，招聘计划管理，员工培训管理，部门培训管理，员工详细管理等功能。员工用例图如图3-2所示。

![](/images/0600stringboot/0673springboot/blog.004.png)

图3-2员工用例图
## 3.4系统流程的分析
由于不同的系统实际使用用户角色的不同,他们的业务分析也会变得有所不一样,为了论述方便接下来都将以用户功能权限下的系统业务流程来分析,如下图所展示:
### 3.4.1 用户管理的流程

![](/images/0600stringboot/0673springboot/blog.005.png)

图3-3 用户管理流程
### 3.4.2个人中心管理流程

![](/images/0600stringboot/0673springboot/blog.006.png)

图3-4 个人中心管理流程
### 3.4.3登录流程
![](/images/0600stringboot/0673springboot/blog.007.png)

图3-5登录流程


# 4系统设计
## 4.1 系统功能模块设计
系统整体功能如下图所示：

![](/images/0600stringboot/0673springboot/blog.008.png)

图 4-1系统总体功能模块图
## 4.2数据库设计
### 4.2.1概念模型设计
概念模型是对现实中的问题出现的事物的进行描述，ER图是由实体及其关系构成的图，通过E-R图可以清楚地描述系统涉及到的实体之间的相互关系。

员工管理实体图如图4-2所示：

![](/images/0600stringboot/0673springboot/blog.009.png)

图4-2员工管理实体图

部门管理实体图如图4-3所示：

![](/images/0600stringboot/0673springboot/blog.010.png)

图4-3部门管理实体图

员工考勤实体图如图4-4所示：

![](/images/0600stringboot/0673springboot/blog.011.png)

图4-4员工考勤实体图

### 4.2.2物理模型设计
根据上诉的逻辑模型设计,下面给出物理模型的设计,如下表:

表4-1：用户表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|username|varchar|100|用户名|||
|password|varchar|100|密码|||
|role|varchar|100|角色||管理员|
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|

表4-2：token表

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

表4-3：招聘计划

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yuangonggonghao|varchar|200|员工工号|||
|yuangongxingming|varchar|200|员工姓名|||
|zhiwei|varchar|200|职位|||
|bumen|varchar|200|部门|||
|zhaopingangwei|varchar|200|招聘岗位|||
|zhaopinyaoqiu|varchar|200|招聘要求|||
|zhaopinrenshu|varchar|200|招聘人数|||
|zhaopinliucheng|longtext|4294967295|招聘流程|||
|shenqingshijian|datetime||申请时间|||
|sfsh|varchar|200|是否审核||否|
|shhf|longtext|4294967295|审核回复|||

表4-4：员工详细

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yuangonggonghao|varchar|200|员工工号|||
|yuangongxingming|varchar|200|员工姓名|||
|bumen|varchar|200|部门|||
|zhiwei|varchar|200|职位|||
|xingbie|varchar|200|性别|||
|nianling|varchar|200|年龄|||
|yuangongshouji|varchar|200|员工手机|||
|zhaopian|varchar|200|照片|||
|yuangongdizhi|varchar|200|员工地址|||
|minzu|varchar|200|民族|||
|xueli|varchar|200|学历|||
|hunfou|varchar|200|婚否|||
|zhengzhimianmao|varchar|200|政治面貌|||
|biyeyuanxiao|varchar|200|毕业院校|||
|zhuanye|varchar|200|专业|||
|shenfenzhenghao|varchar|200|身份证号|||
|crossuserid|bigint||跨表用户id|||
|crossrefid|bigint||跨表主键id|||

表4-5：员工培训

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yuangonggonghao|varchar|200|员工工号|||
|yuangongxingming|varchar|200|员工姓名|||
|zhiwei|varchar|200|职位|||
|xingbie|varchar|200|性别|||
|nianling|varchar|200|年龄|||
|bumen|varchar|200|部门|||
|peixunshijian|datetime||培训时间|||
|peixunneirong|longtext|4294967295|培训内容|||
|peixundidian|varchar|200|培训地点|||
|jieshushijian|datetime||结束时间|||
|beizhu|varchar|200|备注|||

表4-6：员工考勤

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yuangonggonghao|varchar|200|员工工号|||
|yuangongxingming|varchar|200|员工姓名|||
|zhiwei|varchar|200|职位|||
|bumen|varchar|200|部门|||
|dakaleixing|varchar|200|打卡类型|||
|dakashijian|datetime||打卡时间|||
|beizhu|varchar|200|备注|||

表4-7：员工工资

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|fafangshijian|date||发放时间|||
|yuangonggonghao|varchar|200|员工工号|||
|yuangongxingming|varchar|200|员工姓名|||
|zhiwei|varchar|200|职位|||
|bumen|varchar|200|部门|||
|jibengongzi|float||基本工资|||
|jixiao|float||绩效|||
|chebu|float||车补|||
|canbu|float||餐补|||
|fangbu|float||房补|||
|quanqinjiang|float||全勤奖|||
|jiabanfei|float||加班费|||
|wuxianyijin|float||五险一金|||
|koujixiao|float||扣绩效|||
|kuanggongfei|float||旷工费|||
|qitakoukuan|float||其它扣款|||
|shifagongzi|float||实发工资|||
|gongzibeizhu|longtext|4294967295|工资备注|||

表4-8：员工

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yuangonggonghao|varchar|200|员工工号|||
|mima|varchar|200|密码|||
|yuangongxingming|varchar|200|员工姓名|||
|bumen|varchar|200|部门|||
|zhiwei|varchar|200|职位|||
|xingbie|varchar|200|性别|||
|nianling|varchar|200|年龄|||
|yuangongshouji|varchar|200|员工手机|||
|zhaopian|varchar|200|照片|||
|jibengongzi|float||基本工资|||

表4-9：请假申请

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yuangonggonghao|varchar|200|员工工号|||
|yuangongxingming|varchar|200|员工姓名|||
|bumen|varchar|200|部门|||
|zhiwei|varchar|200|职位|||
|qingjialeixing|varchar|200|请假类型|||
|qingjiashijian|date||请假时间|||
|qingjiatianshu|int||请假天数|||
|qingjialiyou|longtext|4294967295|请假理由|||
|sfsh|varchar|200|是否审核||否|
|shhf|longtext|4294967295|审核回复|||

表4-10：加班申请

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yuangonggonghao|varchar|200|员工工号|||
|yuangongxingming|varchar|200|员工姓名|||
|bumen|varchar|200|部门|||
|zhiwei|varchar|200|职位|||
|jiabanshijian|date||加班时间|||
|jiabanshizhang|varchar|200|加班时长|||
|jiabanshiyou|longtext|4294967295|加班事由|||
|sfsh|varchar|200|是否审核||否|
|shhf|longtext|4294967295|审核回复|||

表4-11：配置文件

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|name|varchar|100|配置参数名称|||
|value|varchar|100|配置参数值|||

表4-12：部门培训

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|bumen|varchar|200|部门|||
|peixunshijian|datetime||培训时间|||
|peixunneirong|longtext|4294967295|培训内容|||
|peixundidian|varchar|200|培训地点|||
|jieshushijian|datetime||结束时间|||
|beizhu|varchar|200|备注|||

表4-13：部门

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|bumen|varchar|200|部门|||
|zhiwei|varchar|200|职位|||
#

# 5系统详细设计
## 5.1 管理员功能模块
管理员进行登录，进入系统前在登录页面根据要求填写用户名和密码，选择角色等信息，点击登录进行登录操作，如图5-1所示。

![](/images/0600stringboot/0673springboot/blog.012.png)

图5-1管理员登录界面图

管理员登录系统后，可以对首页，个人中心，员工管理，部门管理，员工考勤管理，请假申请管理，加班申请管理，员工工资管理，招聘计划管理，员工培训管理，部门培训管理，员工详细管理等进行相应的操作管理，如图5-2所示。

![](/images/0600stringboot/0673springboot/blog.013.png)

图5-2管理员功能界面图

学生管理，在学生管理页面可以对索引，员工工号，员工姓名，部门，职位，性别，年龄，员工手机，照片，基本工资等内容进行详情，员工培训，发放工资，详细信息，修改和删除等操作，如图5-3所示。

![](/images/0600stringboot/0673springboot/blog.014.png)

图5-3学生管理界面图

部门管理，在部门管理页面可以对索引，部门，职位等内容进行详情，修改和删除等操作，如图5-4所示。

![](/images/0600stringboot/0673springboot/blog.015.png)

图5-4部门管理界面图

员工考勤管理，在员工考勤管理页面可以对索引，员工工号，员工姓名，职位，部门，打卡类型，打卡时间，备注等内容进行详情，修改和删除等操作，如图5-5所示。

![](/images/0600stringboot/0673springboot/blog.016.png)

图5-5员工考勤管理界面图

请假申请管理，在请假申请管理页面可以对索引，员工工号，员工姓名，部门，职位，请假类型，请假时间，请假天数，审核回复，审核状态，审核等内容进行详情，修改和删除等操作，如图5-6所示。

![](/images/0600stringboot/0673springboot/blog.017.png)

图5-6请假申请管理界面图

员工工资管理，在员工工资管理页面可以对索引，发放时间，员工工号，员工姓名，职位，部门，基本工资，绩效，车补，餐补，房补，全勤奖，加班费，五险一金，扣绩效，旷工费，其它扣款，实发工资等内容进行详情，修改和删除等操作，如图5-7所示。

![](/images/0600stringboot/0673springboot/blog.018.png)

图5-7员工工资管理界面图

招聘计划管理，在招聘计划管理页面可以对索引，员工工号，员工姓名，职位，部门，招聘岗位，招聘要求，招聘人数，申请时间，审核回复，审核状态，审核等内容进行详情，修改和删除等操作，如图5-8所示。

![](/images/0600stringboot/0673springboot/blog.019.png)

图5-8招聘计划管理界面图

部门培训管理，在部门培训管理页面可以对索引，部门，培训时间，培训地点，结束时间，备注等内容进行详情，修改和删除等操作，如图5-9所示。

![](/images/0600stringboot/0673springboot/blog.020.png)

图5-9部门培训管理界面图

员工详细管理，在员工详细管理页面可以对索引，员工工号，员工姓名，部门，职位，性别，年龄，员工手机，照片，员工地址，名族，学历，婚否，政治面貌，毕业院校，专业，身份证号等内容进行详情，修改和删除等操作，如图5-10所示。

![](/images/0600stringboot/0673springboot/blog.021.png)

图5-10员工详细管理界面图

## 5.2 员工功能模块
员工登录进入人事管理系统可以对首页，个人中心，员工考勤管理，请假申请管理，加班申请管理，员工工资管理，招聘计划管理，员工培训管理，部门培训管理，员工详细管理等进行相应操作，如图5-11所示。

![](/images/0600stringboot/0673springboot/blog.022.png)

图5-11员工功能界面图

个人中心，在个人信息页面通过填写员工工号，员工姓名，部门，职位，性别，年龄，员工手机，照片，基本工资等内容对个人信息进行修改操作，如图5-12所示。

![](/images/0600stringboot/0673springboot/blog.023.png)

图5-12个人中心界面图

请假申请管理，在请假申请管理页面可以对索引，员工工号，员工姓名，部门，职位，请假类型，请假时间，请假天数，审核回复，审核状态等内容进行详情和删除等操作，如图5-13所示。

![](/images/0600stringboot/0673springboot/blog.024.png)

图5-13请假申请管理界面图

加班申请管理，在加班申请管理页面可以对索引，员工工号，员工姓名，部门，职位，加班时间，加班时长，审核回复，审核状态等内容进行详情和删除等操作，如图5-14所示。

![](/images/0600stringboot/0673springboot/blog.025.png)

图5-14加班申请管理界面图

员工培训管理，在员工培训管理页面可以对索引，员工工号，员工姓名，职位，性别，年龄，部门，培训时间，培训地点，结束时间，备注等内容进行详情等操作，如图5-15所示。

![](/images/0600stringboot/0673springboot/blog.026.png)

图5-15员工培训管理界面图


#










