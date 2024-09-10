# 0403springboot考勤管理系统代码


# [0403springboot考勤管理系统代码](https://github.com/GraduationProject-springboot/0403springboot)

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

# [项目清单](https://chenqi1990.site) 包安装运行

### [github 项目仓库](https://github.com/GraduationProject-springboot/allSpringbootProjects) 开源仅有后端代码

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1ULbQeREgz?p=4)


# 绪论
## 1.1 研究背景
当前社会各行业领域竞争压力非常大，随着当前时代的信息化，科学化发展，让社会各行业领域都争相使用新的信息技术，对行业内的各种相关数据进行科学化，规范化管理。这样的大环境让那些止步不前，不接受信息改革带来的信息技术的企业随时面临被淘汰，被取代的风险。所以当今，各个行业领域，不管是传统的教育行业，餐饮行业，还是旅游行业，医疗行业等领域都将使用新的信息技术进行信息革命，改变传统的纸质化，需要人手工处理工作事务的办公环境。软件信息技术能够覆盖社会各行业领域是时代的发展要求，各种数据以及文件真正实现电子化是信息社会发展的不可逆转的必然趋势。本考勤管理系统也是紧跟科学技术的发展，运用当今一流的软件技术实现软件系统的开发，让考勤管理系统完全通过管理系统实现科学化，规范化，程序化管理。从而帮助信息管理者节省事务处理的时间，降低数据处理的错误率，对于基础数据的管理水平可以起到促进作用，也从一定程度上对随意的业务管理工作进行了避免，同时，考勤管理系统的数据库里面存储的各种动态信息，也为上层管理人员作出重大决策提供了大量的事实依据。总之，考勤管理系统是一款可以真正提升管理者的办公效率的软件系统。
## 1.2 目的和意义
信息数据的处理完全依赖人工进行操作，会耗费大量的人工成本，特别是面对大量的数据信息时，传统人工操作不仅不能对数据的出错率进行保证，还容易出现各种信息资源的低利用率与低安全性问题。更有甚者，耽误大量的宝贵时间，尤其是对信息的更新，归纳与统计更是耗财耗力的过程。所以电子化信息管理的出现就能缓解以及改变传统人工方式面临的处境，一方面可以确保信息数据在短时间被高效处理，还能节省人力成本，另一方面可以确保信息数据的安全性，可靠性，并可以实现信息数据的快速检索与修改操作，这些优点是之前的旧操作模式无法比拟的。因此考勤管理系统为数据信息的管理模式的升级与改革提供了重要的窗口。
## 1.3 论文结构安排
为了帮助用户更好的了解和理解程序的开发流程与相关内容，本文将通过六个章节进行内容阐述。

第一章：描述了程序的开发背景，程序运用于现实生活的目的与意义，以及程序文档的结构安排信息；

第二章：描述了程序的开发环境，包括程序开发涉及到的技术，程序开发使用的数据存储工具等信息；

第三章：描述了程序着手进行开发时，会面临的可行性问题，并对程序功能以及性能要求进行描述；

第四章：描述了程序大功能模块下的功能细分信息，以及存储程序数据的数据库表文件结构的设计信息等；

第五章：描述了程序的功能实现界面的内容，也对程序操作人员操作的部分功能进行了描述；

第六章：描述了程序功能的测试内容，并介绍了系统测试的概念与方法。
# 2 相关技术
2.1 MySQL数据库

`	`该研究和开发的应用程序在数据操作中难以预料，有时候甚至发生改变。没办法直接从Word中写数据和信息，这不但不安全的，并且难以实现应用程序的功效。要实现所需要的文档存储作用，请尽快选择专业数据存储软件。在很多情况下，应用程序的功效并不是很繁杂，市场中的每一个有关数据库系统软件都能实现。但MySQL数据库，安装包小，拼装速度更快，使用便捷，即便拼装难题改善，不用再度安装操作系统，也不影响电子计算机第三方软件的运转，互联网资源损害少，最主要的是功能充分满足设计定位，最终选择了MySQL数据库做为应用软件开发所需要的数据库。
## 2.2 Java语言技术
Java语言已经出现了25年有余。根据近些年的发展方向，it行业仍占有一半市场占比，仍遭受很多程序员的工作钟爱。很多从业者都是在学习与练习。近些年，伴随着从业者的提升，Java语言位置并没降低，算得上是常青藤。Java语言学习较为简单，当然，这是对于C前辈们的  来说的，C  语言较强。Java取消了很多特点，如go，也取消了主文件，让所有文件夹全是类，类是二维数组以及各种对象，也使Java处理一些对象的引进和回收利用，让开发人员只可以建立对象，运用对象，编写代码逻辑性，不应注意性能，让各种各样文档存储给Java自行解决，你能花时间科学研究系统软件相互关系，使开发更为集中化，如同超级跑车驾驶员一样，只需掌握各种车辆的性能和操作过程，就可以不用科学研究如何生产车轱辘，使程序开发更为详尽。
## 2.3 SpringBoot框架

在过去的两三年的Spring生态系统中，最令人兴奋的是Spring Boot框架。或许从取名上能够了解这个框架设计方案的初心：迅速打开Spring运用。因此Spring 实质上，Boot应用程序是一个根据Spring框架的应用程序。这也是Spring“协议书在于配置”现代逻辑良好实践原材料。可以帮助开发者依据Spring生态系统迅速、更有效的搭建应用程序。

Spring Boot有什么魔法？自动式配置、开发依靠、Actuator、命令行界面(CLI) 是Spring Boot的四大核心特质，在其中CLI是Spring Boot的能选特点尽管功能完善，却也引入了一套非常规的开发实体模型，因此本系列文章只关注别的三个特点。如文章标题，文中是本系列的第一部分，将为您开启Spring Boot大门口，关键在于进一步分析启动过程和自动配置进行基本概念。把握这一部分主要内容，了解一些Spring框架基本知识，会让你悠闲自在。
## 2.4 Vue框架
Vue是最流行JavaScript前端框架之一，它是由Evannn构成 You研发设计。Vue具备重量较轻、易学易用的特征，其核心库只关注视图层，有利于与其它库或现阶段项目集成。Vue带来啦相近Angular的双向数据绑定和React的组件开发方式，还提供虚似DOMM、模板汇编程序等先进特性，使开发者能够迅速搭建可赏识、可维修的当今Web系统软件。

Vue生态体系丰富多彩，包含Vue Router、Vuex等官网手机软件，及其很多第三方插件和图书馆。Vue的模板词很好理解，那样开发者就可以快速开始。除此之外，Vue的回应数据绑定和动态组件系统还能提高应用软件手机软件性能和用户体验。

简单的说，Vue是一个迅速、灵便、易学易用的前端框架，主要应用于Web应用软件的研发

# 3 系统分析
## 3.1 系统可行性分析
### 3.1.1技术可行性分析
本系统所需要的软件包括IDEA，Tomcat，MySQL等，这个工具早已触碰并用过，对于JAVA，B/S，Vue，HTML和其它技术，公共图书馆有明确的书可以参照学习培训，再加上一般在课堂上学习培训编程项目来描述这种技术，除此之外，我就从课题设计运行中能锻炼程序编写能力。因而，在技术上，能完成扶贫助农系统的编程开发。

通过上述剖析，明确了这一系统经济可行性、技术可行性及使用可行性。因而，能够得出结果，在目前环境下，扶贫系统设计和完成能够进行。
### 3.1.2经济可行性分析
开发的程序并不是向着商业服务程序方向设计与开发的，反而是做为一个新的论文新项目开发的。主要运用于检测学生们在学校所学的知识，塑造顾客使用互联网、书本等形式自学能力。因而，程序软件的开发不容易涉及到边际收入，也不会为软件的挑选付钱。你可以在开发软件的官网上下载所需要的app，并依据所需要的安装步骤将运用程序安装在你的电脑里。一般来说，这一程序的开发并没有社会经济发展成本。
### 3.1.3运行可行性分析
由于程序软件就是针对大部分一般操作用户，考虑到他的知识与文化水准，尤其开发了一个可操作度高的程序软件，能够轻而易举地让用户应用，数据可视化操作页面。一般来说，从用户操作程序的角度看，这一程序其实并不难操作。只需用户开启程序，就能避免专职人员学习培训开展程序作用操作，可以得出程序软件能够开发和操作。

3.2 系统流程分析

3.2.1 操作信息流程

具体操作流程见下图

![](/images/0400stringboot/0403springboot/blog.001.png)

图3.1 操作流程图

3.2.2 登录信息流程

登录模块流程见下图

![](/images/0400stringboot/0403springboot/blog.002.png)

图3.2 登录流程图

3.2.3 删除信息流程

删除流程见下图。

![](/images/0400stringboot/0403springboot/blog.003.png)

图3.3 删除信息流程图

3.3 性能需求分析

数据分析报告包含根据用户实际需要制订性能和订制系统的性能数据分析报告。因而，在一般用户数据分析系统中，一方面要知道数据统计分析系统的功效，另一方面要知道综合性性能。终究，更强综合性能设计设计和开发可以确保系统质量以及稳定性。

下边，从简单易用性、系统时间特性、系统可靠性等多个方面系统性能展开了深入分析。

（1）系统容量要求：确立系统数据分析方法容量。也就是说，假如系统创建模型容积零界点超出该零界点，则系统很有可能设备异常。

（2）系统精度要求：确立传送数据所需要的精度值，包含数值计算方法的精度值、数据和信息精度系数设定等。

（3）时长特点要求：系统构建模型有时间期限，那也是系统的时间也特点。一般来说，数据分析方法的解读时间需提前剖析，设置客户标准化的响应时间，及其系统在负载运行时能够偏位的范围值。

（4）适应能力要求：当系统解决系统环境破坏时，也应依据参数信息体现其融合这种变化能力。比如，为应对转变，系统需要通过注重务必设计的一个过程或系统来适应来反映系统的适应能力。
## 3.4 系统功能分析
程序功能需要花费一定时间进行分析与设计，需要从大量的参考资料或者是社会上同种类型的程序中吸收对此程序开发有用的知识，可以将其它同类型程序中的合理功能部分规划到此程序里面，另外程序功能也需要针对用户的需求进行分析与设计。
# 4 系统设计
# 4.1 总体功能
考勤管理系统是根据需求定制开发，开发软件选用idea平台配合MySQL数据库进行开发环境的搭建操作，网站采用为微信小程序结构进行开发，用户通过小程序访问项目,管理人员通过访问系统数据仅仅需要在客户端安装谷歌浏览器或者是当下常用浏览器就可以访问网站后台管理内容。
## 4.2 系统概要设计
考勤管理系统选用B/S架构设计，即网页页面和网站架构模式的开发方式。这类系统构造可以理解为正确 C/S 系统构造的改变与推广能够分布式系统信息，减少资源成本，提升订制系统的性能。在这样的设计下，极少有事务管理在前，大部分关键事务管理模式必须在服务器上进行。

系统的性能层表明给用户网页页面，表明与理解用户数据，回到用户所提供的数据，递交给系统解决方法，给予用户与系统间的通讯操作面板；系统通讯层为性能层提供以下数据，联接性能层和系统后台管理系统间的通讯。HTTP/HTTPS协议书选用，系统控制层首先从HTTP要求中获得信息，获得主要参数。并把它发放给不一样的处理方式服务项目(service层)，并把service层处理过的数据回到前边(本系统应用JSON数据)；系统业务逻辑层的主要作用是挑选用户键入信息开展特定业务逻辑和数据浏览；系统数据浏览层主要面向操作流程数据，为业务逻辑层或控制层给予数据服务项目；系统数据库是系统存放数据的地区。与众不同的业务需要数据可以用，务必纪录信息才能达到工作内容
## 4.3 系统功能结构设计
在分析并得出使用者对程序的功能要求时，就可以进行程序设计了。如图4.3展示的就是管理员功能结构图，管理员在后台主要管理档案管理、字典管理、公告管理、菜单管理、员工签到管理、薪资管理、员工管理、员工出差管理、员工请假管理、管理员管理等。

![结构设计图](/images/0400stringboot/0403springboot/blog.004.jpeg "结构设计图")


图4.3 管理员功能结构图
## 4.4 数据库设计
程序功能操作不管是添加，修改，还是删除等功能产生的数据都是经由数据库进行数据保存和更新的，所以一个数据库设计的好坏也是程序是否好坏的判定标准，因为程序的成功，有一半的功劳都是靠数据库的优秀设计。数据库一旦设计得良好是可以减轻开发人员的开发负担的。
### 4.4.1 数据库E-R图设计
本系统的数据库采用的是MySQL数据库，其中订单表、宠物商品表，订单表、宠物领养等是构成系统的关键组成部分。

以下是系统主要数据库的E-R图。

（1）下图是员工出差实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\2.2\\_\_\_\_img\员工出差.jpg](/images/0400stringboot/0403springboot/blog.005.jpeg "C:/Users/Administrator/Desktop/temp111\2.2\\_\_\_\_img\员工出差.jpg")
员工出差实体属性图

（2）下图是公告实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\2.2\\_\_\_\_img\公告.jpg](/images/0400stringboot/0403springboot/blog.006.jpeg "C:/Users/Administrator/Desktop/temp111\2.2\\_\_\_\_img\公告.jpg")
公告实体属性图

（3）下图是员工请假实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\2.2\\_\_\_\_img\员工请假.jpg](/images/0400stringboot/0403springboot/blog.007.jpeg "C:/Users/Administrator/Desktop/temp111\2.2\\_\_\_\_img\员工请假.jpg")
员工请假实体属性图

（4）下图是员工实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\2.2\\_\_\_\_img\员工.jpg](/images/0400stringboot/0403springboot/blog.008.jpeg "C:/Users/Administrator/Desktop/temp111\2.2\\_\_\_\_img\员工.jpg")
员工实体属性图

（5）下图是档案实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\2.2\\_\_\_\_img\档案.jpg](/images/0400stringboot/0403springboot/blog.009.jpeg "C:/Users/Administrator/Desktop/temp111\2.2\\_\_\_\_img\档案.jpg")
档案实体属性图

（6）下图是菜单实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\2.2\\_\_\_\_img\菜单.jpg](/images/0400stringboot/0403springboot/blog.010.jpeg "C:/Users/Administrator/Desktop/temp111\2.2\\_\_\_\_img\菜单.jpg")
菜单实体属性图

（7）下图是员工签到实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\2.2\\_\_\_\_img\员工签到.jpg](/images/0400stringboot/0403springboot/blog.011.jpeg "C:/Users/Administrator/Desktop/temp111\2.2\\_\_\_\_img\员工签到.jpg")
员工签到实体属性图

（8）下图是薪资实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\2.2\\_\_\_\_img\薪资.jpg](/images/0400stringboot/0403springboot/blog.012.jpeg "C:/Users/Administrator/Desktop/temp111\2.2\\_\_\_\_img\薪资.jpg")
薪资实体属性图

### 4.4.2 数据库表结构设计
该研究数据库是一个关系型数据库，因而二维表的结构设计尤为重要。终究，二维表格数字模型是关系型数据库里的关系模型。在设计关系模型以前，大家还应当把握一些常见的关系模型界定。在全面了解了表构造设计最常见的界定后，大家必须采用以前绘制的E-R数字模型去完成表结构的设计，并且在公共图书馆中建立数据报表，并取名每一个数据报表。下列设计结论以表格方法表明。 

表4.1档案表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|dangan\_uuid\_number|String|档案编号|是|
|3|dangan\_name|String|员工姓名|是|
|4|dangan\_phone|String|员工手机号|是|
|5|dangan\_id\_number|String|员工身份证号|是|
|6|dangan\_photo|String|员工照片|是|
|7|dangan\_chusheng|String|出生年月|是|
|8|dangan\_file|String|附件|是|
|9|sex\_types|Integer|性别|是|
|10|dangan\_email|String|邮箱|是|
|11|ruzhi\_time|Date|入职时间|是|
|12|dangan\_xueli\_content|String|学历情况|是|
|13|dangan\_shixi\_content|String|实习情况|是|
|14|dangan\_gongzuo\_content|String|工作情况|是|
|15|dangan\_beizhu\_content|String|备注|是|
|16|insert\_time|Date|上传时间|是|
|17|update\_time|Date|最后更新时间|是|
|18|create\_time|Date|创建时间|是|
表4.2字典表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|dic\_code|String|字段|是|
|3|dic\_name|String|字段名|是|
|4|code\_index|Integer|编码|是|
|5|index\_name|String|编码名字|是|
|6|super\_id|Integer|父字段id|是|
|7|beizhu|String|备注|是|
|8|create\_time|Date|创建时间|是|
表4.3公告表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|gonggao\_name|String|公告名称|是|
|3|gonggao\_photo|String|公告图片|是|
|4|gonggao\_types|Integer|公告类型|是|
|5|insert\_time|Date|发布时间|是|
|6|gonggao\_content|String|公告详情|是|
|7|create\_time|Date|创建时间|是|
表4.4菜单表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|role\_zh\_name|String|角色汉字|是|
|3|role\_en\_name|String|角色表名|是|
|4|direction|String|使用方向|是|
|5|yiji\_menu\_name|String|一级菜单名称|是|
|6|yiji\_menu\_icon|String|一级菜单图标|是|
|7|erji\_menu|String|二级菜单|是|
|8|beizhu|String|备注|是|
|9|insert\_time|Date|添加时间|是|
|10|update\_time|Date|更新时间|是|
|11|create\_time|Date|创建时间|是|
表4.5员工签到表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yuangong\_id|Integer|员工|是|
|3|qiandao\_shangban\_time|Date|上班签到时间|是|
|4|qiandao\_shangban\_types|Integer|上班签到状态|是|
|5|qiandao\_xiaban\_time|Date|下班签退时间|是|
|6|qiandao\_xiaban\_types|Integer|下班签退状态|是|
|7|insert\_time|Date|所属日期|是|
|8|create\_time|Date|创建时间|是|
表4.6薪资表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yuangong\_id|Integer|员工|是|
|3|xinzi\_uuid\_number|String|薪资编号|是|
|4|xinzi\_month|String|月份|是|
|5|jiben\_jine|BigDecimal|基本工资|是|
|6|jiangjin\_jine|BigDecimal|奖金|是|
|7|jixiao\_jine|BigDecimal|绩效|是|
|8|butie\_jine|BigDecimal|补贴|是|
|9|shifa\_jine|BigDecimal|实发|是|
|10|xinzi\_content|String|备注|是|
|11|insert\_time|Date|添加时间|是|
|12|create\_time|Date|创建时间|是|
表4.7员工表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yuangong\_uuid\_number|String|工号|是|
|3|yuangong\_name|String|员工姓名|是|
|4|yuangong\_phone|String|员工手机号|是|
|5|yuangong\_id\_number|String|员工身份证号|是|
|6|yuangong\_photo|String|员工头像|是|
|7|yuangong\_email|String|员工邮箱|是|
|8|bumen\_types|Integer|部门|是|
|9|zhiwei\_types|Integer|职位|是|
|10|jinyong\_types|Integer|账户状态|是|
|11|create\_time|Date|创建时间|是|
表4.8员工出差表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yuangong\_id|Integer|员工|是|
|3|yuangongchuchai\_name|String|出差标题|是|
|4|yuangongchuchai\_text|String|出差缘由|是|
|5|yuangongchuchai\_address|String|出差地点|是|
|6|yuangongchuchai\_types|Integer|出差类型|是|
|7|yuangongchuchai\_kaishi\_time|Date|出差开始时间|是|
|8|yuangongchuchai\_jieshu\_time|Date|出差结束时间|是|
|9|yuangongchuchai\_jiaotonggongju\_types|Integer|交通工具|是|
|10|yuzhi\_feiyong|BigDecimal|预支费用|是|
|11|insert\_time|Date|申请时间|是|
|12|yuangongchuchai\_yesno\_types|Integer|申请状态|是|
|13|yuangongchuchai\_yesno\_text|String|处理意见|是|
|14|yuangongchuchai\_shenhe\_time|Date|审核时间|是|
|15|create\_time|Date|创建时间|是|
表4.9员工请假表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yuangong\_id|Integer|员工|是|
|3|yuangongqingjia\_text|String|请假缘由|是|
|4|yuangongqingjia\_types|Integer|请假类型|是|
|5|insert\_time|Date|申请时间|是|
|6|yuangongqingjia\_time|Date|请假时间|是|
|7|yuangongqingjia\_number|Integer|请假天数|是|
|8|yuangongqingjia\_yesno\_types|Integer|申请状态|是|
|9|yuangongqingjia\_yesno\_text|String|处理意见|是|
|10|yuangongqingjia\_shenhe\_time|Date|审核时间|是|
|11|create\_time|Date|创建时间|是|
表4.10管理员表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|username|String|员工名|是|
|3|password|String|密码|是|
|4|role|String|角色|是|
|5|addtime|Date|新增时间|是|

# 5 系统实现
系统实现部分就是将系统分析，系统设计部分的内容通过编码进行功能实现，以一个实际应用系统的形式展示系统分析与系统设计的结果。前面提到的系统分析，系统设计最主要还是进行功能，系统操作逻辑的设计，也包括了存储数据的数据库方面的设计等内容，系统实现就是一个最终的实施阶段，将前面的设计成果进行物理转化，最终出具可以运用于实际的软件系统。
## 5.1 管理员功能介绍
### 5.1.1 员工列表
如图5.1显示的就是员工列表页面，此页面提供给管理员的功能有：查看员工、新增员工、修改员工、删除员工等。

![](/images/0400stringboot/0403springboot/blog.013.png)

图5.1 员工列表页面
### 5.1.2 公告信息管理
公告信息管理页面提供的功能操作有：新增公告，修改公告，删除公告操作。下图就是公告信息管理页面。

![](/images/0400stringboot/0403springboot/blog.014.png)

图5.3 公告信息管理页面
### 5.1.3公告类型管理
公告类型管理页面显示所有公告类型，在此页面既可以让管理员添加新的公告信息类型，也能对已有的公告类型信息执行编辑更新，失效的公告类型信息也能让管理员快速删除。下图就是公告类型管理页面。

![](/images/0400stringboot/0403springboot/blog.015.png)

图5.3 公告类型列表页面
### 5.1.4 薪资管理
如图5.4显示的就是薪资管理页面，此页面提供给管理员的功能有：新增薪资,修改薪资,删除薪资。

![](/images/0400stringboot/0403springboot/blog.016.png)

图5.4薪资管理页面
### 5.1.5 部门管理
如图5.5显示的就是部门管理页面，此页面提供给管理员的功能有：新增部门,修改部门,删除部门。

![](/images/0400stringboot/0403springboot/blog.017.png)

图5.5 部门管理页面
# 系统










