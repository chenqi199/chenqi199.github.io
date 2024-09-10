# 0628springboot智慧党建系统设计与实现_1i659--论文


# [0628springboot智慧党建系统设计与实现_1i659--论文](https://github.com/GraduationProject-springboot/0628springboot)

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

# [项目清单](https://chenqi1990.site) 包安装运行

### [github 项目仓库](https://github.com/GraduationProject-springboot/allSpringbootProjects) 开源仅有后端代码

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1eMbYemE1U?p=124)


# 研究背景
近年来，由于计算机技术和互联网技术的快速发展，使得所有企事业单位内部都是数字化、信息化、无纸化的发展趋势，随着趋势的发展，各种决策系统、辅助系统也应运而生，其中，智慧党建系统就是其中的重要组成部分[1]。

智慧党建管理工作向来都是在党建管理中不可或缺的一部分，然而多年以来人们大都习惯使用传统方法，即人工来完成党建的管理，但是这种方法存在着工作效率低以及保密性差的问题，同时还会生成大量的文本和数据，在检索数据时极大不便。随着科技发展进步，我们已进入了信息化社会，仅仅依靠传统的表格管理方式已不能适应时代的要求。因此使用计算机来进行接手传统方式的党建管理已经势在必行。

而通过计算机技术来实现的智慧党建系统拥有对信息的快速检索、保存了大量的党建信息、信息系统保存的稳定性高和维护成本低等优点，对智慧党建管理的工作效率也能提高。如今，传统的人工管理方法、文件和图表打印等信息传输方法已经不能满足当下公司的发展需求，计算机科学与互联网技术的蓬勃发展，颠覆了人们的生活以及思维方式。智慧党建系统的出现，利用信息技术将智慧党建管理融于办公平台中，提高管理水平的有利手段，将会成为未来智慧党建管理的新模式。
## 1.2 课题研究意义
在当下，办公自动化以一种迅速并不可阻挡的速度在慢慢遍布到社会的每一个角落中，而智慧党建系统正是办公自动化的一个小小分支，解决了传统党建管理中繁杂且重复的操作，提高了工作的效率。

对于大部分的企事业单位来说，智慧党建系统对于管理人员进行管理来说是非常重要的，站在管理者的角度也一样。智慧党建系统应该做到让管理人员进行快捷的信息查询以及对信息的处理功能。然而，大多数的还没有使用电子化管理来进行智慧党建管理工作的意识，还是使用传统的人工管理方法。如今，伴随着计算机科学的不断发展，互联网科技的日渐成熟，计算机所带来的种种优势已经逐渐为人们所认识，它已经应用在社会中的各个领域中并且越来越重要，利用计算机将智慧党建信息进行电子化、系统化的管理能将智慧党建管理的效率提上一个台阶。所以，开发一套智慧党建系统，将党建信息进行电子化、系统化的管理，代替了传统的人工管理方式，提升了工作效率。

1) 无纸化办公，节省了时间，减少了纸张的浪费同时节约了成本。
1) 加快了信息传输的过程，使智慧党建管理更规范和科学。
1) 利用计算机处理速度快、信息存储量大的特点，将党建管理工作信息化，可以积累和管理大量的数据。
1) 对数据进行有效并且集中的管理，实现了用户信息的共享，使党建管理工作可以从传统的人工管理中解放出来，提升了工作的效率，使其有更多的时间去完成更多的工作，来提高自身的业务素质。
## 1.3 课题研究内容
本系统结合现今智慧党建系统的功能模块以及设计方式进行分析，使用Java语言和Springboot框架进行开发设计，具体研究内容如下：

1) 系统管理员主要对个人中心、党员管理、党支部管理、党建要闻管理、党建地图管理、党建学习管理、学习心得管理、党费缴纳管理、党建活动管理、活动报名管理、问卷调查管理、问卷回答管理、民主投票管理、投票信息管理、试题管理、学习测试管理、系统管理、考试管理等功能进行管理。
1) 党支部主要对个人中心、党员管理、党费缴纳管理、党建活动管理、活动报名管理等功能进行管理。
1) 党员主要对个人中心、学习心得管理、党费缴纳管理、活动报名管理、问卷回答管理、投票信息管理等功能进行管理。

#
# 2  系统开发环境及相关技术
## 2.1 系统开发环境
本管理系统采用的集成开发环境为IntelliJ IDEA，使用Java等语言及Springboot框架进行开发，其中硬件环境和软件环境如下：

1) 硬件环境

处理器：Intel(R) Core(TM) i5-7400 CPU @ 3.00GHz  3.00GHz

内存：8GB

1) 软件环境

操作系统：windows 10 64位操作系统

开发工具：IntelliJ IDEA 2019.1
## 2.2 系统开发技术
智慧党建系统采用B/S(Browser/Server)架构和MVC模型进行设计开发。在B/S架构下，用户在浏览器端进行使用，主要工作通过服务器端进行实现，用户通过网站进行访问大大节约了成本。本系统使用Java等语言同时运用了Springboot框架进行开发，使用MySQL进行数据存储。
### 2.2.1 Java技术
Java是一种在Web应用开发中得到广泛使用的脚本语言，经常被用来对用户的相关行为做出反应。它还具有面向对象的设计能力，使设计开发过程更加直观和模块化，并在HTML基础上进行交互Web页面的开发[9]。这种脚本语言的问世，使用户与页面之间的实时、动态交互成为现实，丰富了页面的内容，增强了页面的活力。另外，Java技术也被广泛地运用于该系统，比如对用户输入的数据进行检测，以保证其有效性。Java技术[10]可以在不依赖Web服务程序的基础上在本地客户机上运行。从而有效地解决了因网络速度所带来的迟缓问题，使用户能够更加顺畅、快捷地进行访问。一些功能，比如用户的数据输入，可以通过JavaScript这样的客户语言来完成。该系统采用Java客户机进行用户身份认证，确保了系统的安全性和可靠性。
### 2.2.2 SpringBoot框架
Spring Boot是由Pivotal的开发团队在2013年开发的一个免费、轻量级、开源的系统框架。SpringBoot的主要设计思想是约定大于配置，因此SpringBoot在设计时几乎达到零配置。SpringBoot集成了业界的开源框架。

SpringBoot是一个非常强大的后台框架，因为SpringBoot的开发基本上不需要写配置文件，所以利用SpringBoot来构建网站的后台环境，在SpringBoot的YML配置文件中写项目启动端口，项目就可以启动了。项目的Java和静态文件由SpringBoot管理。
### 2.2.3 MySQL数据库
MySql做为瑞典公司MySql AB开发的中小型开源数据库智能管理系统，具备配备低、低成本、运作速度更快的优势。与此同时，因为社区版的开源系统性，变成了许多网址减少开发成本费的最佳选择。被甲骨文回收后，MySQL也发布了商业版。另外Mysql具有以下特性：

（1）使用C和C++编写，并使用了多种编译器进行测试，保证源代码的可移植性。

（2）为C、C++、Eiffel、Java、Perl、PHP、Python、Ruby和Tcl等多种编程语言提供了API。

（3）采用多线程并行的方法提高了CPU的利用率。

（4）改善算法，有效地提高查询速度。
### 2.2.4 B/S结构
B/S结构就是指系统客户端与服务器分离，客户端通过浏览器访问服务端进行操作[10]。

B/S结构目前广泛应用于绝大部分系统搭建中，这种结构摒弃C/S结构客户端服务端不分离的缺点，具有更多的优势：

（1）跨平台性：B/S的标准由标准化组织确立，适用于绝大多数的系统搭建，通用于应用之间。

（2）低维护成本：客户端和服务器端分离，减轻了两端的压力，尤其是客户端，对客户端设备，硬件、软件要求都比较低，并且系统需要升级或维护时，只需要在服务器端升级或维护就可以，使相应的费用减少。



# 3  系统需求分析
在当今的社会生活中，互联网已经变得非常普遍和重要。充分利用互联网大数据等技术可以解决很多问题。目前，智慧党建管理也面临着自身的问题。根据这一普遍现象，党建管理制度的出现需求巨大。该系统可以很好地解决这些问题。系统中这三类用户的数据在系统中非常关键，因此系统数据应该被组织起来，因为数据是以某种格式存储的，而不是无序的。其概念是，它可以根据长期稳定的格式在计算机内存中共享。数据库管理系统主要用于保存、修改和添加索引数据以及设置数据库。为了确保系统数据管理的顺利进行，一些有能力的处理器可以在不需要专业人员处理的情况下管理数据。创建数据表时，可以调整、重新组织和重建数据表中的数据，以确保数据可靠性。在数据库系统设计中，MySQL主要用于实现数据的集中管理。各方面表现良好。
## 2.1 可行性分析
根据智慧党建系统的功能，通过对经济效益、技术难点和管理方法进行全面的可行性分析，提供准确的可行性依据。以下是本系统的可行性分析:

1) 经济可行性

使用了免费版的IntelliJ IDEA节省了开发成本，在购买服务器后部署项目便能通过浏览器进行访问。

1) 技术可行性

本管理系统采用B/S架构进行设计，通过分层分包的方法，有利于日常的维护，同时降低了代码之间的耦合。

1) 管理可行性

本管理系统要求管理难度低，只需要有管理员就能够对个人中心、党员管理、党支部管理、党建要闻管理、党建地图管理、党建学习管理、学习心得管理、党费缴纳管理、党建活动管理、活动报名管理、问卷调查管理、问卷回答管理、民主投票管理、投票信息管理、试题管理、学习测试管理、系统管理、考试管理等进行删除、修改和新增等操作。
## 3.2 功能需求分析 
智慧党建系统综合网络空间开发设计要求。目的是将智慧党建通过网络平台将传统管理方式转换为在网上管理，完成智慧党建的方便快捷、安全性高、交易规范做了保障，目标明确。智慧党建系统可以将功能划分为管理员的使用功能，党支部的使用功能和党员功能。

（1）、管理员的功能是最高的，可以对系统所在功能进行查询、新增、修改和删除，包括党支部功能和党员功能。管理员用例如下：

![](/images/0600stringboot/0628springboot/blog.001.png)

图3-1管理员用例图

（2）、党员关键功能包含个人中心、学习心得管理、党费缴纳管理、活动报名管理、问卷回答管理、投票信息管理等有关功能进行管理。党员用例如下：

![](/images/0600stringboot/0628springboot/blog.002.png)

图3-2党员用例图

（3）、党支部关键功能包含个人中心、党员管理、党费缴纳管理、党建活动管理、活动报名管理等有关功能进行管理。党支部用例如下：

![](/images/0600stringboot/0628springboot/blog.003.png)

图3-3党支部用例图
## 3.3 系统流程分析
### 3.3.1 登录流程
每个用户都有专属的密码和账号，在输入合法的账号和密码之后即可进入系统。登录流程如图3-4所示：

![登录流程图](/images/0600stringboot/0628springboot/blog.004.png)

图3-4 登录流程图
### 3.3.2 添加信息流程
管理层人员有添加角色、党支部和党员等信息功能。添加信息流程如图3-5所示：

![C:\Users\lenovo\AppData\Local\Temp\WeChat Files\da8dfc62fa46238fbebe4d324ba8419.jpg](/images/0600stringboot/0628springboot/blog.005.jpeg)

图3-5 添加信息流程图
### 3.3.3 修改信息流程
管理层人员有修改信息功能。修改信息流程如图3-6所示：

![](/images/0600stringboot/0628springboot/blog.006.png)

图3-6 修改信息流程图



# 4  系统设计
## 4.1 功能模块设计
智慧党建系统按照权限的类型进行划分，分为管理员、党支部和党员三个模块。系统用户实现注册登录、个人信息修改，同时对党员管理、党支部管理、党建要闻管理、党建地图管理、党建学习管理、学习心得管理、党费缴纳管理、党建活动管理、活动报名管理、问卷调查管理、问卷回答管理、民主投票管理、投票信息管理、试题管理、学习测试管理、系统管理、考试管理等功能进行操作，增强了系统用户的操作体验。管理员模块主要针对整个系统的管理进行设计，提高了管理的效率和标准。系统的总体模块设计如下图所示:

![](/images/0600stringboot/0628springboot/blog.007.png)

图4-1 系统总体模块设计
## 4.2 系统数据库设计
### 4.2.1 数据库系统
本系统采用MySQL来进行数据库的管理。MySQL数据库具有体积小、速度快、成本低等优点。具备同时处理数千万条记录，实现大型数据库的高并发读写和高效读写需求。
### 4.2.2 数据库概念设计
概念模型用于对信息世界建模，并与指定的数据库管理系统分离。它有助于将真实世界的事物抽象为适合于数据库管理系统的数据库模型。人们倾向于将现实世界抽象为信息世界，再把信息世界变成机器世界。也就是说，将现实世界的目标抽象成独立于专用计算机软件和专用数据库管理系统的信息结构的数据模型，然后将物理模型转化为适合电子计算机的数据库管理系统。事实上，数据模型是从真实世界到机器世界的中间层。

信息世界的基本要素包括实体和关联。现实存在且彼此可区别的事物称为实体。实体可以是实际的人、事或物，还可以是抽象化的概念或联络。以下是对部分主要的关键实体如下：

党建学习实体属性图如下图4-2所示。

![](/images/0600stringboot/0628springboot/blog.008.png)

图4-2党建学习实体属性图

党建活动实体属性图如下图4-3所示。

![](/images/0600stringboot/0628springboot/blog.009.png)

图4-3党建活动实体属性图

民主投票实体属性图如下图4-4所示。

![](/images/0600stringboot/0628springboot/blog.010.png)

图4-4民主投票实体属性图

活动报名实体属性图如下图4-5所示。

![](/images/0600stringboot/0628springboot/blog.011.png)

图4-5活动报名实体属性图
### 4.2.3 数据表设计
本设计根据数据表管理系统的具体流程进行管理，方便管理员、计划员和工艺员对数据的添加、删除、修改和查询等操作。
### 4.2.4 数据表的建立
系统采用Navicat Premium对数据库进行操作，数据库管理操作简单，数据处理能力强。数据表建立如下:

表4-1：配置文件

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|name|varchar|100|配置参数名称|||
|value|varchar|100|配置参数值|||

表4-2：党建要闻评论表

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

表4-3：党建学习评论表

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

表4-4：党建地图评论表

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

表4-5：用户表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|username|varchar|100|用户名|||
|password|varchar|100|密码|||
|role|varchar|100|角色||管理员|
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|

表4-6：token表

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

表4-7：收藏表

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

表4-8：考试记录表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|userid|bigint||用户id|||
|username|varchar|200|用户名|||
|paperid|bigint||学习测试id（外键）|||
|papername|varchar|200|学习测试名称|||
|questionid|bigint||试题id（外键）|||
|questionname|varchar|200|试题名称|||
|options|longtext|4294967295|选项，json字符串|||
|score|bigint||分值||0|
|answer|varchar|200|正确答案|||
|analysis|longtext|4294967295|答案解析|||
|myscore|bigint||试题得分||0|
|myanswer|varchar|200|考生答案|||

表4-9：试题表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|paperid|bigint||所属学习测试id（外键）|||
|papername|varchar|200|学习测试名称|||
|questionname|varchar|200|试题名称|||
|options|longtext|4294967295|选项，json字符串|||
|score|bigint||分值||0|
|answer|varchar|200|正确答案|||
|analysis|longtext|4294967295|答案解析|||
|type|bigint||试题类型，0：单选题 1：多选题 2：判断题 3：填空题（暂不考虑多项填空）||0|
|sequence|bigint||试题排序，值越大排越前面||100|

表4-10：学习测试表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|name|varchar|200|学习测试名称|||
|time|int||考试时长(分钟)|||
|status|int||学习测试状态||0|

表4-11：学习心得

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|ziliaobianhao|varchar|200|资料编号|||
|ziliaomingcheng|varchar|200|资料名称|||
|xuexixinde|longtext|4294967295|学习心得|||
|xuexishijian|datetime||学习时间|||
|dangyuanzhanghao|varchar|200|党员账号|||
|dangyuanxingming|varchar|200|党员姓名|||
|crossuserid|bigint||跨表用户id|||
|crossrefid|bigint||跨表主键id|||

表4-12：问卷回答

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|wenjuanbiaoti|varchar|200|问卷标题|||
|wenjuanhuida|varchar|200|问卷回答|||
|diaochashijian|datetime||调查时间|||
|dangyuanzhanghao|varchar|200|党员账号|||
|dangyuanxingming|varchar|200|党员姓名|||
|crossuserid|bigint||跨表用户id|||
|crossrefid|bigint||跨表主键id|||

表4-13：问卷调查

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|wenjuanbiaoti|varchar|200|问卷标题|||
|tupian|longtext|4294967295|图片|||
|wenjuanneirong|longtext|4294967295|问卷内容|||
|daanyi|varchar|200|答案一|||
|daaner|varchar|200|答案二|||
|daansan|varchar|200|答案三|||
|daansi|varchar|200|答案四|||
|fabushijian|datetime||发布时间|||

表4-14：党支部

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|zhibuzhanghao|varchar|200|支部账号|||
|mima|varchar|200|密码|||
|zhibumingcheng|varchar|200|支部名称|||
|fuzeren|varchar|200|负责人|||
|lianxidianhua|varchar|200|联系电话|||
|zhibudizhi|varchar|200|支部地址|||

表4-15：党员

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|dangyuanzhanghao|varchar|200|党员账号|||
|mima|varchar|200|密码|||
|dangyuanxingming|varchar|200|党员姓名|||
|touxiang|longtext|4294967295|头像|||
|lianxifangshi|varchar|200|联系方式|||
|nianling|int||年龄|||
|xingbie|varchar|200|性别|||
|xueli|varchar|200|学历|||
|shenfenzhenghao|varchar|200|身份证号|||
|rudangshijian|date||入党时间|||
|zhibuzhanghao|varchar|200|支部账号|||
|zhibumingcheng|varchar|200|支部名称|||

表4-16：投票信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|dangyuanzhanghao|varchar|200|党员账号|||
|dangyuanxingming|varchar|200|党员姓名|||
|toupiaozhuti|varchar|200|投票主题|||
|xuanxianga|int||选项a|||
|xuanxiangb|int||选项b|||
|xuanxiangc|int||选项c|||
|xuanxiangd|int||选项d|||
|toupiaoshijian|datetime||投票时间|||
|crossuserid|bigint||跨表用户id|||
|crossrefid|bigint||跨表主键id|||

表4-17：党建要闻

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|dangjianbiaoti|varchar|200|党建标题|||
|fengmian|longtext|4294967295|封面|||
|jianjie|longtext|4294967295|简介|||
|shipin|longtext|4294967295|视频|||
|xiangqingneirong|longtext|4294967295|详情内容|||
|fabushijian|date||发布时间|||
|thumbsupnum|int||赞||0|
|crazilynum|int||踩||0|

表4-18：党建学习

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|ziliaobianhao|varchar|200|资料编号|||
|ziliaomingcheng|varchar|200|资料名称|||
|tupian|longtext|4294967295|图片|||
|ziliaojianjie|longtext|4294967295|资料简介|||
|shipin|longtext|4294967295|视频|||
|fujianxiazai|longtext|4294967295|附件下载|||
|fabushijian|datetime||发布时间|||

表4-19：党建活动

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|huodongmingcheng|varchar|200|活动名称|||
|huodongtupian|longtext|4294967295|活动图片|||
|huodongdidian|varchar|200|活动地点|||
|huodongshijian|datetime||活动时间|||
|huodongrenshu|varchar|200|活动人数|||
|huodongneirong|longtext|4294967295|活动内容|||
|fabushijian|datetime||发布时间|||
|zhibuzhanghao|varchar|200|支部账号|||
|zhibumingcheng|varchar|200|支部名称|||

表4-20：民主投票

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|toupiaozhuti|varchar|200|投票主题|||
|fengmian|longtext|4294967295|封面|||
|xuanxianga|int||选项a|||
|xuanxiangb|int||选项b|||
|xuanxiangc|int||选项c|||
|xuanxiangd|int||选项d|||
|toupiaoneirong|longtext|4294967295|投票内容|||
|fabushijian|datetime||发布时间|||
|reversetime|datetime||倒计结束时间|||

表4-21：党建地图

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|ditumingcheng|varchar|200|地图名称|||
|fengmian|longtext|4294967295|封面|||
|dituxiangqing|longtext|4294967295|地图详情|||
|fabushijian|datetime||发布时间|||

表4-22：活动报名

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|huodongmingcheng|varchar|200|活动名称|||
|huodongdidian|varchar|200|活动地点|||
|huodongshijian|varchar|200|活动时间|||
|baomingshijian|datetime||报名时间|||
|beizhu|varchar|200|备注|||
|dangyuanzhanghao|varchar|200|党员账号|||
|dangyuanxingming|varchar|200|党员姓名|||
|lianxifangshi|varchar|200|联系方式|||
|zhibuzhanghao|varchar|200|支部账号|||
|zhibumingcheng|varchar|200|支部名称|||
|crossuserid|bigint||跨表用户id|||
|crossrefid|bigint||跨表主键id|||
|sfsh|varchar|200|是否审核||待审核|
|shhf|longtext|4294967295|审核回复|||

表4-23：党费缴纳

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|dangyuanzhanghao|varchar|200|党员账号|||
|dangyuanxingming|varchar|200|党员姓名|||
|xingbie|varchar|200|性别|||
|lianxifangshi|varchar|200|联系方式|||
|zhibuzhanghao|varchar|200|支部账号|||
|zhibumingcheng|varchar|200|支部名称|||
|dangfei|float||党费|||
|yuefen|varchar|200|月份|||
|ispay|varchar|200|是否支付||未支付|














# 5  系统实现
## 5.1系统功能实现
当人们打开系统的网址后，首先看到的就是首页界面。在这里，人们能够看到系统的导航条，通过导航条导航进入各功能展示页面进行操作。系统首页界面如图5-1所示：

![](/images/0600stringboot/0628springboot/blog.012.png)

图5-1 系统首页界面

党建要闻：在党建要闻页面的输入栏中输入党建标题、简介进行查询，可以查看到党建要闻详细信息，并根据需要进行评论或收藏操作；党建要闻页面如图5-2所示：

![](/images/0600stringboot/0628springboot/blog.013.png)

图5-2党建要闻详细页面

党建学习：在党建学习页面的输入栏中输入资料名称进行查询，可以查看到党建学习详细信息，党建学习页面如图5-3所示：

![](/images/0600stringboot/0628springboot/blog.014.png)

图5-3党建学习详细页面

党建活动：在党建活动页面的输入栏中输入活动名称进行查询，可以查看到党建活动详细信息，并根据需要进行报名操作；党建活动页面如图5-4所示：

![](/images/0600stringboot/0628springboot/blog.015.png)

图5-4党建活动详细页面

问卷调查：在问卷调查页面的输入栏中输入问卷标题进行查询，可以查看到问卷调查详细信息，并进行问卷回答操作；问卷调查页面如图5-5所示：

![](/images/0600stringboot/0628springboot/blog.016.png)

图5-5问卷调查详细页面

民主投票：在民主投票页面的输入栏中输入投票主题进行查询，可以查看到民主投票详细信息，并进行投票操作；民主投票页面如图5-6所示：

![](/images/0600stringboot/0628springboot/blog.017.png)

图5-6民主投票详细页面

学习测试：在学习测试页面可以查看学习测试名称、考试时长、创建时间等信息，并进行考试操作；党建要闻页面如图5-7所示：

![](/images/0600stringboot/0628springboot/blog.018.png)

图5-7学习测试详细页面

个人中心：在个人中心页面通过填写个人详细信息进行信息更新操作，还可以对考试管理、错题本、我的收藏进行详细操作；如图5-8所示：

![](/images/0600stringboot/0628springboot/blog.019.png)

图5-8个人中心界面
## 5.2后台模块实现
后台用户登录，在登录页面选择需要登录的角色，在正确输入用户名和密码后，进入操作系统进行操作；如图5-9所示。                               

![](/images/0600stringboot/0628springboot/blog.020.png)

图5-9 后台登录界面
### 5.2.1管理员模块实现
管理员进入主页面，主要功能包括对个人中心、党员管理、党支部管理、党建要闻管理、党建地图管理、党建学习管理、学习心得管理、党费缴纳管理、党建活动管理、活动报名管理、问卷调查管理、问卷回答管理、民主投票管理、投票信息管理、试题管理、学习测试管理、系统管理、考试管理等进行操作。管理员主页面如图5-10所示：

![](/images/0600stringboot/0628springboot/blog.021.png)

图5-10管理员主界面

管理员点击党员管理。在党员页面输入党员账号和选择性别进查询、新增、删除、年龄分析或学历统计党员列表，并根据需要对党员详情信息进行详情操作；如图5-11所示：

![](/images/0600stringboot/0628springboot/blog.022.png)

图5-11党员管理界面

管理员点击党支部管理。在党支部页面输入支部账号进行查询、新增或删除党支部列表，并根据需要对党支部详情信息进行详情、修改或删除操作；如图5-12所示：

![](/images/0600stringboot/0628springboot/blog.023.png)

图5-12党支部管理界面

管理员点击党建要闻管理。在党建要闻页面输入党建标题、简介进行查询、新增或删除党建要闻列表，并根据需要对党建要闻详情信息进行详情、查看评论、修改或删除操作；如图5-13所示：

![](/images/0600stringboot/0628springboot/blog.024.png)

图5-13党建要闻管理界面

管理员点击党建地图管理。在党建地图页面输入地图名称进行查询、新增或删除党建地图列表，并根据需要对党建地图详情信息进行详情、查看评论、修改或删除操作；如图5-14所示：

![](/images/0600stringboot/0628springboot/blog.025.png)

图5-14党建地图管理界面

管理员点击学习心得管理。在学习心得页面输入资料编号、资料名称进行查询或删除学习心得列表，并根据需要对学习心得详情信息进行详情、修改或删除操作；如图5-15所示：

![](/images/0600stringboot/0628springboot/blog.026.png)

图5-15学习心得管理界面

管理员点击活动报名管理。在活动报名页面输入活动名称、党员姓名、支部名称、是否通过进行查询或删除活动报名列表，并根据需要对活动报名详情信息进行详情操作；如图5-16所示：

![](/images/0600stringboot/0628springboot/blog.027.png)

图5-16活动报名管理界面

管理员点击问卷调查管理。在问卷调查页面输入问卷标题进查询、新增、删除、年龄分析或学历统计问卷调查列表，并根据需要对问卷调查详情信息进行详情操作；如图5-17所示：

![](/images/0600stringboot/0628springboot/blog.028.png)

图5-17问卷调查管理界面

管理员点击问卷回答管理。在问卷回答页面输入问卷标题进查询、删除或问卷回答统计问卷回答列表，并根据需要对问卷回答详情信息进行详情、修改或删除操作；如图5-18所示：

![](/images/0600stringboot/0628springboot/blog.029.png)

图5-18问卷回答管理界面

管理员点击党建活动管理。在党建活动页面输入活动名称进查询、新增或删除党建活动列表，并根据需要对党建活动详情信息进行详情操作；如图5-19所示：

![](/images/0600stringboot/0628springboot/blog.030.png)

图5-19党建活动管理界面

管理员点击民主投票管理。在民主投票页面输入投票主题进查询、新增或删除民主投票列表，并根据需要对民主投票详情信息进行详情、修改或删除操作；如图5-20所示：

![](/images/0600stringboot/0628springboot/blog.031.png)

图5-20民主投票管理界面

### 5.2.2党员模块实现
党员进入系统可以对个人中心、学习心得管理、党费缴纳管理、活动报名管理、问卷回答管理、投票信息管理等功能进行操作。党员主页面如图5-21所示：

![](/images/0600stringboot/0628springboot/blog.032.png)

图5-21党员主界面

### 5.2.3党支部模块实现
党支部进入系统可以对个人中心、党员管理、党费缴纳管理、党建活动管理、活动报名管理等功能进行操作。党支部主页面如图5-22所示：

![](/images/0600stringboot/0628springboot/blog.033.png)

图5-22党支部主界面


# 系统测试










