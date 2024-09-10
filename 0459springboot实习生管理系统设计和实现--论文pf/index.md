# 0459springboot实习生管理系统设计和实现--论文pf


# [0459springboot实习生管理系统设计和实现--论文pf](https://github.com/GraduationProject-springboot/0459springboot)

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

# [项目清单](https://chenqi1990.site) 包安装运行

### [github 项目仓库](https://github.com/GraduationProject-springboot/allSpringbootProjects) 开源仅有后端代码

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1ULbQeREgz?p=59)


# 绪论
## 1.1 研究背景
当前社会各行业领域竞争压力非常大，随着当前时代的信息化，科学化发展，让社会各行业领域都争相使用新的信息技术，对行业内的各种相关数据进行科学化，规范化管理。这样的大环境让那些止步不前，不接受信息改革带来的信息技术的企业随时面临被淘汰，被取代的风险。所以当今，各个行业领域，不管是传统的教育行业，餐饮行业，还是旅游行业，医疗行业等领域都将使用新的信息技术进行信息革命，改变传统的纸质化，需要人手工处理工作事务的办公环境。软件信息技术能够覆盖社会各行业领域是时代的发展要求，各种数据以及文件真正实现电子化是信息社会发展的不可逆转的必然趋势。本实习生管理系统也是紧跟科学技术的发展，运用当今一流的软件技术实现软件系统的开发，让实习生管理系统完全通过管理系统实现科学化，规范化，程序化管理。从而帮助信息管理者节省事务处理的时间，降低数据处理的错误率，对于基础数据的管理水平可以起到促进作用，也从一定程度上对随意的业务管理工作进行了避免，同时，实习生管理系统的数据库里面存储的各种动态信息，也为上层管理人员作出重大决策提供了大量的事实依据。总之，实习生管理系统是一款可以真正提升管理者的办公效率的软件系统。
## 1.2 目的和意义
信息数据的处理完全依赖人工进行操作，会耗费大量的人工成本，特别是面对大量的数据信息时，传统人工操作不仅不能对数据的出错率进行保证，还容易出现各种信息资源的低利用率与低安全性问题。更有甚者，耽误大量的宝贵时间，尤其是对信息的更新，归纳与统计更是耗财耗力的过程。所以电子化信息管理的出现就能缓解以及改变传统人工方式面临的处境，一方面可以确保信息数据在短时间被高效处理，还能节省人力成本，另一方面可以确保信息数据的安全性，可靠性，并可以实现信息数据的快速检索与修改操作，这些优点是之前的旧操作模式无法比拟的。因此实习生管理系统为数据信息的管理模式的升级与改革提供了重要的窗口。
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

MySQL是一种具有安全系数、安全系数、混合开发性、高效化等特征的轻量关联数据库智能管理系统。MySQL由C语言和C语言构成  由C语言和C语言撰写成的，由于C语言和C语言  这是混合开发的，因此MySQL源码是生命期的。MySQL提供多种多样数据种类，常见的数据种类包含[34]。伴随着数据库技术发展，MySQL逐步形成数据库管理方法的重要工具之一。它不仅能提供简单实用的操作作用，还能实现复杂多变的数据检索方法和查询记录导出方式。因为MySQL具有较好的兼容模式和扩展性，因而广泛应用于各行各业。

MySQL在WEB行业越来越受单位和个人开发者的亲睐。大部分大中小型网址都采用MySQL数据库，它不仅可以提供简单高效的数据浏览作用，还会对数据进行相应的剖析解决。因为Linux电脑操作系统和MySQL数据库全是开源系统免费体验，能够为公司节约许多费用，让很多企业使用Linux   MySQL做为网址数据库，体型小，启动速度快，也不会影响网址性能，导致用户体验感极差。

MySQL数据库能够支持各种各样操作系统的运作，包含AIX、HP-UX、OS/2 Wrap、Solaris、Mac OS、Linux和Windows等。性能好，使用便捷。因而，MySQL数据库已成为当下数据库行业最流行产品之一。MySQL数据库系统使用面向对象设计方式，客户至上开展编程设计。是利用面向对象观念来达到各项功能。它不仅能管理方法大中型数据表或关系数据库，还可以把这种复杂且庞大信息系统集成到一个简单的中小型数据库系统内。现阶段，中国很多公司早已运用了这一尖端技术。但是由于该操作系统是根据远程服务器/服务器结构的（C/S），因而，存在一些缺陷：最先，系统软件不可以提供完备的数据访问接口，客户只能依靠浏览器浏览所需要的数据；次之，系统软件并没有统一的标准，不同类型的客户端难以实现数据分享；第三，系统软件没有很好的权限管理体制。
## 2.2 Java语言技术
Java语言已经存在了25年有余。通过这些年的发展趋势，it行业在市场占有率上仍然占据一半，仍然受到了很多程序员的工作钟爱。许多从业者都是在学习培训。近年来随着从业者的提高，Java语言的位置并没减少，算得上是常青藤。Java语言学习培训比较简单，自然，它是对于C前辈们的  而言的，C  语言非常强劲。Java取消了许多特点，如go这种阐述，也取消了主文件，让所有文件夹全是类，类是二维数组以及各种对象，也使Java处理一些对象的引入和回收利用，让开发者只需建立对象，应用对象，编写代码逻辑，不需要留意性能，让各种各样文件存储给Java自己解决，你能花很多时间科学研究应用软件相互关系，使研发更为集中化，如同跑车驾驶员一样，只要了解各种汽车的性能，实际操作，不需要科学研究如何生产车轮子，使软件开发更为详尽。
## 2.3 SpringBoot框架
	在过去的两三年的Spring生态系统中，最令人兴奋的是Spring Boot框架。或许从取名上能够得知这一框架设计初心：快速开启Spring运用。因此Spring 实质上，Boot应用程序是一个根据Spring框架的应用程序。这是Spring“协议书先于配置”理论的良好实践物质。可以帮助开发者迅速、更有效地搭建根据Spring生态系统的应用程序。

Spring Boot有什么魔法？全自动配置、发展依靠、Actuator、命令行界面（CLI） 是Spring Boot最主要的四个核心特点，在其中CLI是Spring Boot的能选特点尽管功能齐全，却也引入了一套非传统的开发模型，因此本系列文章只注重别的三个特点。如标题，文中是本系列的第一部分，将为您开启Spring Boot大门口，关键为您进一步分析启动过程及全自动配置完成基本原理。把握这一部分主要内容，了解一些Spring框架的基本知识，也会让你游刃有余。
## 2.4 B/S模式框架
B/S架构是互联网行业区别C/S架构，用以叙述浏览器与服务器之间的架构方式。一般来说，挑选B/S架构的主要原因是维修方便。当软件开发时，能够在本地进行检测。一般综合开发工具都有各自的开发与一键部署。当地浏览器能够及时出效果。测试工程师有专业的网络服务器，仅需布署就可以。假如正中间有什么问题，能够整顿。应用软件更新，只需后台维护编码，顾客依然应用以前的浏览器开展访问，因此用户端十分方便。现在市面上大部分每一个电脑操作系统服务平台只要是有窗口模式，除开命令行操作页面对话框，窗口模式可以放置浏览器，因此一切带窗口模式的计算机操作系统自已的浏览器或其它生产商的浏览器，或挪动浏览器，都能够访问网络服务器。访问网络服务器占用用户端网络资源非常少，不易出差错。即便用户端有问题，也仅需重新装系统，随后组装浏览器就可以。在程序流程性能和用户体验层面，挑选B/S架构开发设计应用软件特别适合如今的社会的主力发展趋向。



# 3 系统分析
## 3.1 系统可行性分析




### 3.1.1技术可行性分析
研发设计程序流程挑选面向对象设计、功能齐全、简单实用的Java编程设计核心理念。MySQL数据库存储数据。IDEA工具作为编程软件，Windows 10计算机操作系统作为应用系统，以及数据库可视化工具等技术职称。一般来说，该程序流程的开发能够从技术上开展是可行的。
### 3.1.2经济可行性分析
开发的程序并不是向着商业程序方向设计与开发的，反而是做为一个新的毕业论文新项目开发的。它主要运用于检测小朋友们在院校所学的知识，并锻练客户使用网络、书籍和其他方式自学能力。因而，程序软件的开发不容易涉及到边际收益，也不会为软件的挑选付钱。你可以在开发软件的官网上下载所需要的软件，并依据所需要的安装方法将应用安装到你的电脑里。一般来说，开发这一程序并没有社会经济发展花费。
### 3.1.3运行可行性分析
由于程序软件就是针对大部分一般操作用户，考虑到他的知识与文化水准，尤其开发了一个可操作度高的程序软件，能够轻而易举地让用户应用，数据可视化操作页面。一般来说，从用户操作程序的角度看，这一程序其实并不难操作。只需用户开启程序，就能避免专职人员学习培训开展程序作用操作。

3.2 系统流程
### 3.2.1 操作信息流程
具体操作流程见下图

![](/images/0400stringboot/0459springboot/blog.001.png)

图3.1 操作流程图

3.2.2 登录信息流程

登录模块流程见下图

![](/images/0400stringboot/0459springboot/blog.002.png)

图3.2 登录流程图

3.2.3 删除信息流程

删除流程见下图。

![](/images/0400stringboot/0459springboot/blog.003.png)

图3.3 删除信息流程图

## 3.3系统功能分析
程序功能需要花费一定时间进行分析与设计，需要从大量的参考资料或者是社会上同种类型的程序中吸收对此程序开发有用的知识，可以将其它同类型程序中的合理功能部分规划到此程序里面，另外程序功能也需要针对用户的需求进行分析与设计。
# 4 系统设计
## 4.1 总体功能
实习生管理系统是根据需求定制开发，开发软件选用idea平台配合MySQL数据库进行开发环境的搭建操作，网站采用为微信小程序结构进行开发，用户通过小程序访问项目,管理人员通过访问系统数据仅仅需要在客户端安装谷歌浏览器或者是当下常用浏览器就可以访问网站后台管理内容。
## 4.2 系统概要设计
本次拟开发的系统为了节约开发成本，也为了后期在维护和升级上的便利性，打算通过浏览器来实现系统功能界面的展示，让程序软件的主要事务集中在后台的服务器端处理，前端部分只用处理少量的事务逻辑。下面使用一张图（如图4.2所示）来说明程序的工作原理。

![](/images/0400stringboot/0459springboot/blog.004.png)

图4.2 程序工作的原理图
## 4.3 系统功能结构设计
在分析并得出使用者对程序的功能要求时，就可以进行程序设计了。如图4.3展示的就是管理员功能结构图，管理员在后台主要管理字典表管理、辅导员管理、公告管理、简历管理、企业管理、实习生培养记录管理、实习作业管理、用户管理、职位招聘管理、职位收藏管理、职位留言管理、简历投递管理、管理员管理等。

![结构设计图](/images/0400stringboot/0459springboot/blog.005.jpeg "结构设计图")


图4.3 管理员功能结构图
## 4.4 数据库设计
程序功能操作不管是添加，修改，还是删除等功能产生的数据都是经由数据库进行数据保存和更新的，所以一个数据库设计的好坏也是程序是否好坏的判定标准，因为程序的成功，有一半的功劳都是靠数据库的优秀设计。数据库一旦设计得良好是可以减轻开发人员的开发负担的。
### 4.4.1 数据库E-R图设计
这个部分的设计需要使用到E-R图绘制工具，常用的工具就是Visio工具来绘制E-R模型图，这款工具不仅可以快速创建需要的E-R模型图，而且该工具提供的操作界面很简单，可以短时间内修改绘图界面的图形或者是文字的属性。在绘制E-R模型图时，要分清楚各个图形代表的含义，以免绘制出错，E-R模型图由长方形（实体），椭圆形（属性），菱形（关系）这三部分图形符号组成，绘制期间要区分开来，用准确的图形符号代表相应的数据元素。

（1）下图是用户实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\9.1\\_\_\_\_img\用户.jpg](/images/0400stringboot/0459springboot/blog.006.jpeg "C:/Users/Administrator/Desktop/temp111\9.1\\_\_\_\_img\用户.jpg")

用户实体属性图

（2）下图是职位留言实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\9.1\\_\_\_\_img\职位留言.jpg](/images/0400stringboot/0459springboot/blog.007.jpeg "C:/Users/Administrator/Desktop/temp111\9.1\\_\_\_\_img\职位留言.jpg")

职位留言实体属性图

（3）下图是字典表实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\9.1\\_\_\_\_img\字典表.jpg](/images/0400stringboot/0459springboot/blog.008.jpeg "C:/Users/Administrator/Desktop/temp111\9.1\\_\_\_\_img\字典表.jpg")

字典表实体属性图

（4）下图是辅导员实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\9.1\\_\_\_\_img\辅导员.jpg](/images/0400stringboot/0459springboot/blog.009.jpeg "C:/Users/Administrator/Desktop/temp111\9.1\\_\_\_\_img\辅导员.jpg")

辅导员实体属性图

（5）下图是简历实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\9.1\\_\_\_\_img\简历.jpg](/images/0400stringboot/0459springboot/blog.010.jpeg "C:/Users/Administrator/Desktop/temp111\9.1\\_\_\_\_img\简历.jpg")

简历实体属性图

（6）下图是实习生培养记录实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\9.1\\_\_\_\_img\实习生培养记录.jpg](/images/0400stringboot/0459springboot/blog.011.jpeg "C:/Users/Administrator/Desktop/temp111\9.1\\_\_\_\_img\实习生培养记录.jpg")

实习生培养记录实体属性图

（7）下图是简历投递实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\9.1\\_\_\_\_img\简历投递.jpg](/images/0400stringboot/0459springboot/blog.012.jpeg "C:/Users/Administrator/Desktop/temp111\9.1\\_\_\_\_img\简历投递.jpg")

简历投递实体属性图

（8）下图是企业实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\9.1\\_\_\_\_img\企业.jpg](/images/0400stringboot/0459springboot/blog.013.jpeg "C:/Users/Administrator/Desktop/temp111\9.1\\_\_\_\_img\企业.jpg")

企业实体属性图

（9）下图是职位收藏实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\9.1\\_\_\_\_img\职位收藏.jpg](/images/0400stringboot/0459springboot/blog.014.jpeg "C:/Users/Administrator/Desktop/temp111\9.1\\_\_\_\_img\职位收藏.jpg")

职位收藏实体属性图

（10）下图是公告实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\9.1\\_\_\_\_img\公告.jpg](/images/0400stringboot/0459springboot/blog.015.jpeg "C:/Users/Administrator/Desktop/temp111\9.1\\_\_\_\_img\公告.jpg")

公告实体属性图

（11）下图是实习作业实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\9.1\\_\_\_\_img\实习作业.jpg](/images/0400stringboot/0459springboot/blog.016.jpeg "C:/Users/Administrator/Desktop/temp111\9.1\\_\_\_\_img\实习作业.jpg")

实习作业实体属性图

（12）下图是职位招聘实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\9.1\\_\_\_\_img\职位招聘.jpg](/images/0400stringboot/0459springboot/blog.017.jpeg "C:/Users/Administrator/Desktop/temp111\9.1\\_\_\_\_img\职位招聘.jpg")

职位招聘实体属性图

### 4.4.2 数据库表结构设计
数据库系统一旦选定之后，需要根据程序要求在数据库中建立数据库文件，并在已经完成创建的数据库文件里面，为程序运行中产生的数据建立对应的数据表格，数据表结构设计就是对创建的数据表格进行字段设计，字段长度设计，字段类型设计等，当数据表格合理设计完成之后，才能正常存储相关程序运行产生的数据信息。 

表4.1字典表表

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
表4.2辅导员表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|fudaoyuan\_name|String|辅导员姓名|是|
|3|fudaoyuan\_photo|String|头像|是|
|4|fudaoyuan\_phone|String|辅导员手机号|是|
|5|fudaoyuan\_id\_number|String|辅导员身份证号|是|
|6|fudaoyuan\_email|String|邮箱|是|
|7|fudaoyuan\_delete|Integer|假删|是|
|8|create\_time|Date|创建时间|是|
表4.3公告表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|gonggao\_name|String|公告名称|是|
|3|gonggao\_photo|String|公告图片|是|
|4|gonggao\_types|Integer|公告类型|是|
|5|insert\_time|Date|公告发布时间|是|
|6|gonggao\_content|String|公告详情|是|
|7|create\_time|Date|创建时间|是|
表4.4简历表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_id|Integer|用户|是|
|3|jianli\_uuid\_number|String|简历唯一编号|是|
|4|jianli\_name|String|简历标题|是|
|5|jianli\_xingming|String|姓名|是|
|6|jianli\_types|Integer|求职意向|是|
|7|jianli\_xinzi|String|期望工资|是|
|8|jianli\_xueli|String|学历|是|
|9|jianli\_jingli|String|工作经历|是|
|10|sex\_types|Integer|性别|是|
|11|jianli\_file|String|简历文件|是|
|12|jianli\_phone|String|手机号|是|
|13|jianli\_photo|String|照片|是|
|14|jianli\_address|String|现在位置|是|
|15|jiaoyu\_text|String|教育经历|是|
|16|shixi\_text|String|实习或工作经历|是|
|17|geren\_text|String|个人介绍|是|
|18|create\_time|Date|创建时间|是|
表4.5企业表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|qiye\_name|String|企业名称|是|
|3|qiye\_types|Integer|企业类型|是|
|4|qiye\_phone|String|联系方式|是|
|5|qiye\_email|String|邮箱|是|
|6|qiye\_photo|String|企业logo|是|
|7|qiye\_chenglishijian\_time|Date|企业成立时间|是|
|8|qiye\_content|String|企业介绍|是|
|9|qiye\_delete|Integer|逻辑删除|是|
|10|create\_time|Date|创建时间|是|
表4.6实习生培养记录表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_id|Integer|用户|是|
|3|shixishengpeiyang\_uuid\_number|String|实习生培养记录编号|是|
|4|shixishengpeiyang\_name|String|实习生培养标题|是|
|5|shixishengpeiyang\_address|String|培养地点|是|
|6|shixishengpeiyang\_types|Integer|培养类型|是|
|7|shixishengpeiyang\_time|Date|培养时间|是|
|8|shixishengpeiyang\_content|String|培养内容|是|
|9|shixishengpeiyang\_dafen|BigDecimal|打分|是|
|10|shixishengpeiyang\_jieguo\_types|Integer|培养结果|是|
|11|shixishengpeiyang\_pingyu\_content|String|培养评语|是|
|12|insert\_time|Date|上传时间|是|
|13|create\_time|Date|创建时间|是|
表4.7实习作业表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_id|Integer|用户|是|
|3|shixizuoye\_uuid\_number|String|实习作业编号|是|
|4|shixizuoye\_name|String|实习作业标题|是|
|5|shixizuoye\_content|String|作业描述|是|
|6|shixizuoye\_file|String|作业文件|是|
|7|insert\_time|Date|上传时间|是|
|8|shixizuoye\_old\_money|BigDecimal|作业打分|是|
|9|shixizuoye\_pingyu\_content|String|作业评语|是|
|10|update\_time|Date|评论时间|是|
|11|create\_time|Date|创建时间|是|
表4.8用户表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_name|String|用户姓名|是|
|3|yonghu\_photo|String|头像|是|
|4|yonghu\_phone|String|用户手机号|是|
|5|yonghu\_id\_number|String|用户身份证号|是|
|6|yonghu\_email|String|邮箱|是|
|7|yonghu\_delete|Integer|假删|是|
|8|create\_time|Date|创建时间|是|
表4.9职位招聘表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|qiye\_id|Integer|企业|是|
|3|zhaopin\_name|String|招聘信息名称|是|
|4|zhaopin\_photo|String|招聘信息照片|是|
|5|zhaopin\_daiyu|String|薪资待遇|是|
|6|zhaopin\_address|String|上班地点|是|
|7|lianxiren\_name|String|联系人|是|
|8|zan\_number|Integer|赞|是|
|9|cai\_number|Integer|踩|是|
|10|zhaopin\_phone|String|招聘电话|是|
|11|zhaopin\_types|Integer|招聘岗位|是|
|12|zhaopin\_renshu\_number|Integer|招聘人数|是|
|13|shangxia\_types|Integer|是否上架|是|
|14|zhaopin\_content|String|招聘信息详情|是|
|15|create\_time|Date|创建时间|是|
表4.10职位收藏表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|zhaopin\_id|Integer|职位|是|
|3|yonghu\_id|Integer|用户|是|
|4|zhaopin\_collection\_types|Integer|类型|是|
|5|insert\_time|Date|收藏时间|是|
|6|create\_time|Date|创建时间|是|
表4.11职位留言表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|zhaopin\_id|Integer|职位|是|
|3|yonghu\_id|Integer|用户|是|
|4|zhaopin\_liuyan\_text|String|留言内容|是|
|5|reply\_text|String|回复内容|是|
|6|insert\_time|Date|留言时间|是|
|7|update\_time|Date|回复时间|是|
|8|create\_time|Date|创建时间|是|
表4.12简历投递表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|jianli\_id|Integer|简历|是|
|3|zhaopin\_id|Integer|招聘|是|
|4|insert\_time|Date|投递时间|是|
|5|zhaopin\_toudi\_yesno\_types|Integer|审核状态|是|
|6|zhaopin\_toudi\_yesno\_text|String|投递回复|是|
|7|zhaopin\_toudi\_shenhe\_time|Date|回复时间|是|
|8|create\_time|Date|创建时间|是|
表4.13管理员表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|username|String|学生名|是|
|3|password|String|密码|是|
|4|role|String|角色|是|
|5|addtime|Date|新增时间|是|

# 5 系统实现
系统实现部分就是将系统分析，系统设计部分的内容通过编码进行功能实现，以一个实际应用系统的形式展示系统分析与系统设计的结果。前面提到的系统分析，系统设计最主要还是进行功能，系统操作逻辑的设计，也包括了存储数据的数据库方面的设计等内容，系统实现就是一个最终的实施阶段，将前面的设计成果进行物理转化，最终出具可以运用于实际的软件系统。
## 5.1 管理员功能介绍
### 5.1.1 职位招聘列表
如图5.1显示的就是职位招聘列表页面，此页面提供给管理员的功能有：查看职位招聘、新增职位招聘、修改职位招聘、删除职位招聘等。

![](/images/0400stringboot/0459springboot/blog.018.png)

图5.1 职位招聘列表页面
### 5.1.2 公告信息管理
公告信息管理页面提供的功能操作有：新增公告，修改公告，删除公告操作。下图就是公告信息管理页面。

![](/images/0400stringboot/0459springboot/blog.019.png)

图5.3 公告信息管理页面
### 5.1.3公告类型管理
公告类型管理页面显示所有公告类型，在此页面既可以让管理员添加新的公告信息类型，也能对已有的公告类型信息执行编辑更新，失效的公告类型信息也能让管理员快速删除。下图就是公告类型管理页面。

![](/images/0400stringboot/0459springboot/blog.020.png)

图5.3 公告类型列表页面
### 5.1.4 企业管理
如图5.4显示的就是企业管理页面，此页面提供给管理员的功能有：新增企业,修改企业,删除企业。

![](/images/0400stringboot/0459springboot/blog.021.png)

图5.4企业管理页面
### 5.1.5 企业类型管理
如图5.5显示的就是企业类型管理页面，此页面提供给管理员的功能有：新增企业类型,修改企业类型,删除企业类型。

![](/images/0400stringboot/0459springboot/blog.022.png)

图5.5 企业类型管理页面
# 系统










