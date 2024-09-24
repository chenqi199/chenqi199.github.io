# 0731springboot致远汽车租赁系统--论文


# [项目清单 包安装运行](http://chenqi1990.site) 官网地址 http://chenqi1990.site

# [0731springboot致远汽车租赁系统--论文](https://github.com/GraduationProject-springboot/0731springboot)

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### [github 项目仓库](https://github.com/GraduationProject-springboot/allSpringbootProjects) 开源仅有后端代码

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV14HerezEwW?p=82)

# 绪论
## 1.1项目研究的背景
困扰公司的许多问题当中,致远汽车租赁管理一定是公司不敢忽视的一块。但是管理好致远汽车租赁又面临很多麻烦需要解决,例如有几个方面:第一,公司往往汽车数量都比较多,如何保证能够管理到每一汽车;第二,如何在工作琐碎,记录繁多的情况下将致远汽车租赁的当前情况反应给公司领导相关部门决策,等等。在此情况下开发一款致远汽车租赁系统，于是乎变得非常合乎时宜。

经过网上调查和搜集数据,我们可以发现致远汽车租赁管理方面的系统在公司中并不是相当普及,公司在致远汽车租赁管理方面的可以有许多改进。实际上如今信息化成为一个未来的趋势或者可以说在当前现代化的城市典范中,信息化已经成为主流,开发一个致远汽车租赁系统一方面的可能会更合乎时宜,另一方面来说也可以提高公司在致远汽车租赁管理方面的效率给相关部门人的工作带来一定的便利。
## 1.2开发意义
人类的进步带动信息化的发展，使人们生活节奏越来越快，所以人们越来越重视信息的时效性。以往的管理方式已经满足不了人们对获得信息的方式、方便快捷的需求。即致远汽车租赁系统慢慢的被人们关注。首先，网上获取信息十分的实时、便捷，只要系统在线状态，无论在哪里都能第一时间查找到理想的信息。

计算机技术在管理中成为人们的重要工具。可以有效快捷的解决想要获取的信息，提高工作效率。
## 1.3项目研究内容
致远汽车租赁管理方面的任务繁琐,以至于公司每年都在致远汽车租赁管理这方面投入较多的精力却效果甚微,致远汽车租赁系统的目标就是为了能够缓解致远汽车租赁管理工作方面面临的压力,让致远汽车租赁管理方面的工作变得更加高效准确。

本项目在开发和设计过程中涉及到原理和技术有: B/S、java技术和MySQL数据库等等；
## 1.4论文结构
1. 绪论；剖析项目背景,说明研究的内容。
1. 开发技术；系统主要使用了java技术， b/s模式和myspl数据库，并对此做了介绍。
1. 系统分析；包括了系统总体结构、对系统的性能、功能、流程图进行了分析。
1. 系统设计；对软件功能模块和数据库进行详细设计。
1. 系统总体设计；对系统管理员，用户和业务员的功能进行描述。
1. 对系统进行测试。
1. 总结心得；在论文最后结束章节总结了开发这个系统和撰写论文时候自己的总结、感想,包括致谢。


# 2开发技术介绍
## 2.1 B/S架构
B/S结构是目前使用最多的结构模式，它可以使得系统的开发更加的简单，好操作，而且还可以对其进行维护。使用该结构时只需要在计算机中安装数据库，和一些很常用的浏览器就可以了。浏览器就会与数据库进行信息的连接，可以实现很多的功能，B/S结构是可以直接进行使用的，而且B/S结构在使用中极大的减少了工作的维护。基于B/S的软件，所有的数据库之间都是相互独立的，因此是非常安全的。因为基于B/S结构可以清楚的看到系统正在处理的业务，并且能够及时的让管理人员做出决策，这样就可以避免企业的损失。B/S结构的基本特点是集中式的管理模式，用户使用系统生成数据后，这些数据就可以存储到系统的数据库中，方便日后能够用到，这样就可以满足人们的所有的需求。

![](/images/0700stringboot/0731springboot/blog.002.png)

图2-1  B/S模式三层结构图
## 2.2Java技术
Java是由Sun公司推出的一门跨平台的面向对象的程序设计语言。因为Java 技术具有卓越的通用性、高效性、健壮的安全性和平台移植性的特点，而且Java是开源的，拥有全世界最大的开发者专业社群，所以Java的发展迅速。
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
在开发系统之前要进行系统可行性分析，目的是在用最简单的方法去解决最大的问题，程序一旦开发出来满足了用户的需要，所带来的利益也很多。下面我们将从技术、操作、经济等方面来选择这个系统最终是否开发。
### 3.1.1技术可行性
本系统开发选择java技术，java技术是一个完全面向对象的语言，为开发者提供了丰富的类库，大大减少了使用windows编程的难度,减少开发人员在设计算法上的难度，作为java技术开发 Visual Studio更是一个必不可少的角色，它友好的界面，以及强大的功能，给程序开发人员带来了很多方便，加上环境简单，转移方便，无疑使此系统最佳的选择。所以后台设计选择使用MySQL数据库主要用来的建立和维护信息。对于前台开发要求应具备功能完善、易于操作等优点，后台数据库的要求则是能够建立和维护数据信息的统一性和完整性。

依据上述目标来分析本系统的硬件如下：

奔腾3的处理器；

内存是 2G；

硬盘是50G；

操作系统是Window 10；

在软件方面的话，安装了Visul Studio和MySQL数据库开发工具。根据以上的软件与硬件要求，得到这个系统的技术是可行的。
### 3.1.2经济可行性
基于springboot的致远汽车租赁系统，该系统软件开发仅需要一台普通的计算机便可完成实现开发，其成本很低。另外，作为毕业设计作品来讲，开发成本基本上可以忽略不计，且该系统软件的投入使用，可以实现更加快速高效的致远汽车租赁功能，同时还能实现对人力资源和管理资源的有效节约，该致远汽车租赁系统在经济上完全可行。
### 3.1.3操作可行性
现在随着科技的飞速发展，计算机早已经进入了人们的日常生活中，人们的工作环境也不像以前有那么多的要求，需要员工一定要到公司办公，有的工作在家也可以完成。这使得人们的工作效益有了很大的提高。操作的多样性也变高了。因此，管理的计算机化，智能化是社会发展而带来的必然趋势，各种智能的软件层出不穷，不同的软件能完成用户不同的需求，这不仅提高了工作效率还能完成一些客户特定的一些需求。本系统不仅界面简洁明了，用户只要用鼠标和键盘就可以完成对相关信息的修改，删除，添加等操作。因为这个系统的操作十分简单，方便上手，对于第一次使用系统的人，只需要很少的时间就可以上手操作。由此可见，本系统在操作上是可行的。
## 3.2系统性能需求分析
对系统性能进行分析，可对系统反应度、界面简洁清晰度、储存能性、易学性和稳定性进行分析；

系统反应度：同时上万人在线时反应时间应该在两三秒以内，。

界面简洁清晰：系统界面要求简单明了，操作简单，用户操作容易上手。

储存性能高：致远汽车租赁系统中需要存储的信息有很多，所以对系统的存储量要求很高，因此数据库就应该很强大，才能保证信息能安全稳定的进行存储；

易学性：该系统在操作上必须简单好上手，没有很多复杂的操作，只需要简单的进行学习就能操作该系统。

稳定性：要求致远汽车租赁系统运行要稳定，界面清楚、字体清晰等。
## 3.3系统功能分析
考虑到实际生活中在致远汽车租赁方面的需要以及对该系统认真的分析,将系统权限按管理员，用户和业务员这三类涉及用户划分。

(a) 管理员；管理员使用本系统涉到的功能主要有：首页，个人中心，用户管理，业务员管理，汽车类型管理，租赁汽车管理，汽车租赁管理，汽车归还管理，租赁订单管理，检查信息管理，系统管理等功能。管理员用例图如图3-1所示。

![](/images/0700stringboot/0731springboot/blog.003.png)图3-1　管理员用例图

` `(b)用户；用户使用本系统涉到的功能主要有：首页，个人中心，汽车租赁管理，汽车归还管理，租赁订单管理，检查信息管理，我的收藏管理等功能。用户用例图如图3-2所示。

![](/images/0700stringboot/0731springboot/blog.004.png)

图3-2用户用例图

(c)业务员，业务员使用本系统主要包括首页，个人中心，汽车租赁管理，汽车归还管理，租赁订单管理，检查信息管理等功能。业务员用例图如图3-3所示。

![](/images/0700stringboot/0731springboot/blog.005.png)

图3-3业务员用例图
## 3.4系统流程的分析
由于不同的系统实际使用用户角色的不同,他们的业务分析也会变得有所不一样,为了论述方便接下来都将以用户功能权限下的系统业务流程来分析,如下图所展示:
### 3.4.1 用户管理的流程

![](/images/0700stringboot/0731springboot/blog.006.png)

图3-4 用户管理流程
### 3.4.2个人中心管理流程

![](/images/0700stringboot/0731springboot/blog.007.png)

图3-5 个人中心管理流程
### 3.4.3登录流程
![](/images/0700stringboot/0731springboot/blog.008.png)

图3-6 登录流程







# 4系统设计
## 4.1 软件功能模块设计
网站整体功能如下图所示：

![](/images/0700stringboot/0731springboot/blog.009.png)

图 4-1 致远汽车租赁系统总体功能模块图
## 4.2数据库设计
### 4.2.1概念模型设计
概念模型是对现实中的问题出现的事物的进行描述，ER图是由实体及其关系构成的图，通过E-R图可以清楚地描述系统涉及到的实体之间的相互关系。

用户注册实体图如图4-2所示：

![](/images/0700stringboot/0731springboot/blog.010.png)

图4-2用户注册实体图

汽车租赁实体图如图4-3所示：

![](/images/0700stringboot/0731springboot/blog.011.png)

图4-3汽车租赁实体图

用户管理实体图如图4-4所示：

![](/images/0700stringboot/0731springboot/blog.012.png)

图4-4用户管理实体图

### 4.2.2物理模型设计
根据上诉的逻辑模型设计,下面给出物理模型的设计,如下表:

表4-1：收藏表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|userid|bigint||用户id|||
|refid|bigint||收藏id|||
|tablename|varchar|200|表名|||
|name|varchar|200|收藏名称|||
|picture|varchar|200|收藏图片|||
|type|varchar|200|类型(1:收藏,21:赞,22:踩)||1|
|inteltype|varchar|200|推荐类型|||

表4-2：汽车租赁

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|dingdanbianhao|varchar|200|订单编号|||
|qichebianhao|varchar|200|汽车编号|||
|qichepinpai|varchar|200|汽车品牌|||
|qichexinghao|varchar|200|汽车型号|||
|chepaihao|varchar|200|车牌号|||
|yanse|varchar|200|颜色|||
|qicheleixing|varchar|200|汽车类型|||
|yajin|int||押金|||
|rizujiage|int||日租价格|||
|zulinshijian|datetime||租赁时间|||
|qichezhuangtai|varchar|200|汽车状态|||
|yonghuzhanghao|varchar|200|用户账号|||
|xingming|varchar|200|姓名|||
|shoujihaoma|varchar|200|手机号码|||
|shenfenzhenghao|varchar|200|身份证号|||
|sfsh|varchar|200|是否审核||否|
|shhf|longtext|4294967295|审核回复|||

表4-3：汽车类型

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|qicheleixing|varchar|200|汽车类型|||

表4-4：汽车归还

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|dingdanbianhao|varchar|200|订单编号|||
|qichebianhao|varchar|200|汽车编号|||
|qichepinpai|varchar|200|汽车品牌|||
|qichexinghao|varchar|200|汽车型号|||
|chepaihao|varchar|200|车牌号|||
|yanse|varchar|200|颜色|||
|qicheleixing|varchar|200|汽车类型|||
|yajin|int||押金|||
|rizujiage|int||日租价格|||
|zulinshijian|varchar|200|租赁时间|||
|guihaishijian|datetime||归还时间|||
|yonghuzhanghao|varchar|200|用户账号|||
|xingming|varchar|200|姓名|||
|shoujihaoma|varchar|200|手机号码|||
|shenfenzhenghao|varchar|200|身份证号|||

表4-5：公告信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|title|varchar|200|标题|||
|introduction|longtext|4294967295|简介|||
|picture|varchar|200|图片|||
|content|longtext|4294967295|内容|||

表4-6：租赁订单

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|dingdanbianhao|varchar|200|订单编号|||
|qichebianhao|varchar|200|汽车编号|||
|qichepinpai|varchar|200|汽车品牌|||
|qichexinghao|varchar|200|汽车型号|||
|chepaihao|varchar|200|车牌号|||
|yanse|varchar|200|颜色|||
|qicheleixing|varchar|200|汽车类型|||
|yajin|int||押金|||
|zulinshijian|varchar|200|租赁时间|||
|rizujiage|int||日租价格|||
|guihaishijian|varchar|200|归还时间|||
|zulintianshu|int||租赁天数|||
|zongjine|int||总金额|||
|yonghuzhanghao|varchar|200|用户账号|||
|xingming|varchar|200|姓名|||
|shoujihaoma|varchar|200|手机号码|||
|shenfenzhenghao|varchar|200|身份证号|||
|yewuyuanzhanghao|varchar|200|业务员账号|||
|yewuyuanxingming|varchar|200|业务员姓名|||
|ispay|varchar|200|是否支付||未支付|

表4-7：检查信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|dingdanbianhao|varchar|200|订单编号|||
|qichebianhao|varchar|200|汽车编号|||
|qichepinpai|varchar|200|汽车品牌|||
|qichexinghao|varchar|200|汽车型号|||
|chepaihao|varchar|200|车牌号|||
|yanse|varchar|200|颜色|||
|qicheleixing|varchar|200|汽车类型|||
|zulinshijian|varchar|200|租赁时间|||
|guihaishijian|varchar|200|归还时间|||
|yonghuzhanghao|varchar|200|用户账号|||
|xingming|varchar|200|姓名|||
|shoujihaoma|varchar|200|手机号码|||
|shenfenzhenghao|varchar|200|身份证号|||
|jianchajieguo|longtext|4294967295|检查结果|||
|cunzaiwenti|longtext|4294967295|存在问题|||
|peifujine|int||赔付金额|||
|jianchashijian|datetime||检查时间|||
|yewuyuanzhanghao|varchar|200|业务员账号|||
|yewuyuanxingming|varchar|200|业务员姓名|||
|ispay|varchar|200|是否支付||未支付|

表4-8：用户

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yonghuzhanghao|varchar|200|用户账号|||
|mima|varchar|200|密码|||
|xingming|varchar|200|姓名|||
|touxiang|varchar|200|头像|||
|xingbie|varchar|200|性别|||
|shoujihaoma|varchar|200|手机号码|||
|youxiang|varchar|200|邮箱|||
|shenfenzhenghao|varchar|200|身份证号|||

表4-9：租赁汽车评论表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|refid|bigint||关联表id|||
|userid|bigint||用户id|||
|nickname|varchar|200|用户名|||
|content|longtext|4294967295|评论内容|||
|reply|longtext|4294967295|回复内容|||

表4-10：业务员

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yewuyuanzhanghao|varchar|200|业务员账号|||
|mima|varchar|200|密码|||
|yewuyuanxingming|varchar|200|业务员姓名|||
|touxiang|varchar|200|头像|||
|xingbie|varchar|200|性别|||
|lianxidianhua|varchar|200|联系电话|||
|shenfenzhenghao|varchar|200|身份证号|||

表4-11：配置文件

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|name|varchar|100|配置参数名称|||
|value|varchar|100|配置参数值|||

表4-12：押金支付

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|dingdanbianhao|varchar|200|订单编号|||
|qichebianhao|varchar|200|汽车编号|||
|qichepinpai|varchar|200|汽车品牌|||
|qichexinghao|varchar|200|汽车型号|||
|chepaihao|varchar|200|车牌号|||
|yanse|varchar|200|颜色|||
|qicheleixing|varchar|200|汽车类型|||
|yajin|int||押金|||
|zulinshijian|varchar|200|租赁时间|||
|yonghuzhanghao|varchar|200|用户账号|||
|xingming|varchar|200|姓名|||
|shoujihaoma|varchar|200|手机号码|||
|shenfenzhenghao|varchar|200|身份证号|||
|ispay|varchar|200|是否支付||未支付|

表4-13：租赁汽车

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|qichebianhao|varchar|200|汽车编号|||
|qichepinpai|varchar|200|汽车品牌|||
|qichexinghao|varchar|200|汽车型号|||
|tupian|varchar|200|图片|||
|qicheleixing|varchar|200|汽车类型|||
|chepaihao|varchar|200|车牌号|||
|yanse|varchar|200|颜色|||
|yajin|int||押金|||
|rizujiage|int||日租价格|||
|zulinzhuangtai|varchar|200|租赁状态|||
|qichexiangqing|longtext|4294967295|汽车详情|||
|tichedidian|varchar|200|提车地点|||

表4-14：用户表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|username|varchar|100|用户名|||
|password|varchar|100|密码|||
|role|varchar|100|角色||管理员|
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|

表4-15：token表

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


# 5系统详细设计
## 5.1系统功能模块
致远汽车租赁系统，在系统首页可以查看首页，汽车租赁，公告信息，个人中心，后台管理等内容，并进行详细操作，如图5-1所示。

![](/images/0700stringboot/0731springboot/blog.013.jpeg)

图5-1系统首页界面图

用户注册，在用户注册页面通过填写用户账号，密码，确认密码，姓名，手机号码，邮箱，身份证号等信息进行注册操作，如图5-2所示。

![](/images/0700stringboot/0731springboot/blog.014.jpeg)

图5-2用户注册界面图

汽车租赁，在汽车租赁页面可以查看汽车型号，汽车编号，汽车类型，汽车品牌，车牌号，颜色，押金，目前价格，租赁状态，提车地点等内容，如图5-3所示。

![](/images/0700stringboot/0731springboot/blog.015.png)

图5-3汽车租赁界面图

个人中心，在个人中心页面通过填写用户信息进行更新信息，还可以根据需要对我的收藏进行详细操作，如图5-4所示。

![](/images/0700stringboot/0731springboot/blog.016.png)

图5-4个人中心界面图

## 5.2管理员功能模块
管理员进行登录，进入系统前在登录页面根据要求填写用户名和密码，选择角色等信息，点击登录进行登录操作，如图5-5所示。

![](/images/0700stringboot/0731springboot/blog.017.jpeg)

图5-5管理员登录界面图

管理员登录系统后，可以对首页，个人中心，用户管理，业务员管理，汽车类型管理，租赁汽车管理，汽车租赁管理，汽车归还管理，租赁订单管理，检查信息管理，系统管理等进行相应的操作管理，如图5-6所示。

![](/images/0700stringboot/0731springboot/blog.018.png)

图5-6管理员功能界面图

用户管理，在用户管理页面可以对用户账号，姓名，头像，性别，手机号码，邮箱，身份证号等内容进行详情，修改和删除等操作，如图5-7所示。

![](/images/0700stringboot/0731springboot/blog.019.png)

图5-7用户管理界面图

业务员管理，在业务员管理页面可以对索引、业务员账号，业务员姓名，头像，性别，联系电话，身份证号等内容进行详情，修改和删除等操作，如图5-8所示。

![](/images/0700stringboot/0731springboot/blog.020.png)

图5-8业务员管理界面图

汽车类型管理，在汽车类型管理页面可以对索引、汽车类型等内容进行详情，修改和删除等操作，如图5-9所示。

![](/images/0700stringboot/0731springboot/blog.021.png)

图5-9汽车类型管理界面图

租赁汽车管理，在租赁汽车管理页面可以对索引、汽车编号，汽车品牌，汽车型号，图片，汽车类型，车牌号，颜色，押金，日租价格，租赁状态，提车地点等内容进行详情，修改，查看评论和删除等操作，如图5-10所示。

![](/images/0700stringboot/0731springboot/blog.022.png)

图5-10租赁汽车管理界面图

汽车租赁管理，在汽车租赁管理页面可以对索引、订单编号，汽车编号，汽车品牌，汽车型号，车牌号，颜色，汽车类型，押金，日租价格，租赁时间，汽车状态，用户账号，姓名，手机号码，身份证号，是否支付等内容进行详情和删除等操作，如图5-11所示。

![](/images/0700stringboot/0731springboot/blog.023.png)

图5-11汽车租赁管理界面图

## 5.3业务员功能模块
业务员登录进入致远汽车租赁系统可以对首页，个人中心，汽车租赁管理，汽车归还管理，租赁订单管理，检查信息管理等进行相应操作，如图5-12所示。

![](/images/0700stringboot/0731springboot/blog.024.png)

图5-124业务员功能界面图

汽车归还管理，在汽车归还页面通过填写索引，订单编号，汽车编号，汽车品牌，汽车型号，车牌号，颜色，汽车类型，押金，日租价格，租赁时间，归还时间，用户账号，姓名，手机号码，身份证号等内容进行详情，租赁订单，检查信息等操作，如图5-13所示。

![](/images/0700stringboot/0731springboot/blog.025.png)

图5-13汽车归还界面图
## 5.3用户功能模块
用户登录进入致远汽车租赁系统可以对首页，个人中心，汽车租赁管理，汽车归还管理，租赁订单管理，检查信息管理，我的收藏管理等进行相应操作，如图5-14所示。

![](/images/0700stringboot/0731springboot/blog.026.png)

图5-14汽车功能界面图

个人中心，在个人信息页面通过填写用户账号，姓名，头像，性别，手机号码，邮箱，身份证号等内容对个人信息进行修改操作，如图5-15所示。

![](/images/0700stringboot/0731springboot/blog.027.png)

图5-15个人中心界面图

检查信息管理，在检查信息页面通过填写索引，订单编号，汽车编号，汽车品牌，汽车型号，车牌号，颜色，汽车类型，租赁时间，归还时间，用户编号，姓名，手机号码，身份照，赔付金额，检查时间，业务员账号，业务员姓名，是否支付等内容进行详情操作，如图5-16所示。

![](/images/0700stringboot/0731springboot/blog.028.png)

图5-16检查信息界面图

我的收藏管理，在我的收藏管理页面可以对索引、收藏名称、收藏图片等内容进行详情和删除等操作，如图5-17所示。

![](/images/0700stringboot/0731springboot/blog.029.png)

图5-17 我的收藏管理界面图


#










