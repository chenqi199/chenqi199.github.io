# 0066springboot中小型医院网站


# 0066springboot中小型医院网站

### 微信： chen_q123456  qq:462201886
### github:chenqi199 gitee :chen_q_i

### [所有项目](https://github.com/GraduationProject-springboot/allSpringbootProjects) 包安装运行

### [所有项目列表excel 腾讯文档 项目清单](https://docs.qq.com/sheet/DSHRFSVZ5aEVYT3N3?tab=BB08J2) 包安装运行

### [github](https://chenqi199.github.io)

### [gitee](https://gitee.com/chen_q_i)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://player.bilibili.com/player.html?isOutside=true&aid=BV16ia6epENY&bvid=BV16ia6epENY&cid=500001610575664&p=67)



### 0066springboot中小型医院网站 部分论文
```

毕业论文（设计）
基于Spring Boot的中小型医院网站

的设计与实现
院    系                       

专    业                       

学生姓名                       

学    号                       

指导教师                       

职    称                        
2021 年    月     日
摘  要

本基于Spring Boot的中小型医院网站设计目标是实现用户网络预约挂号的功能，同时提高医院管理效率，更好的为广大用户服务。

本文重点阐述了中小型医院网站的开发过程，以实际运用为开发背景，基于Spring Boot框架，运用了Java技术和MYSQL数据库进行开发设计，充分保证系统的安全性和稳定性。本系统界面良好，操作简单方便，通过系统概述、系统分析、系统设计、数据库设计、系统测试这几个部分，详细的说明了系统的开发过程，最后并对整个开发过程进行了总结，实现了预约挂号管理、医师开药管理、药库信息管理、用户取药管理以及缴费清单管理等重要功能。

本基于Spring Boot的中小型医院网站运行效果稳定，操作方便、快捷，界面友好，是一个功能全面、实用性好、安全性高，并具有良好的可扩展性、可维护性的医院网站。
关键字：医院网站；Java技术；MYSQL 数据库；Spring Boot框架
Abstract

The design goal of this Spring Boot-based small and medium-sized hospital website is to realize the function of users' online appointment registration, and at the same time improve the efficiency of hospital management, and better serve the majority of users.

This article focuses on the development process of small and medium-sized hospital websites. It takes practical application as the development background, based on the Spring Boot framework, and uses Java technology and MYSQL database to develop and design to fully ensure the security and stability of the system. The system has a good interface, simple and convenient operation. Through the system overview, system analysis, system design, database design, and system testing, the development process of the system is explained in detail. Finally, the whole development process is summarized and realized Important functions such as appointment registration management, physician prescription management, drug library information management, user withdrawal management, and payment list management.

The Spring Boot-based small and medium-sized hospital website has stable operation effect, convenient and fast operation, and friendly interface. It is a hospital website with comprehensive functions, good practicability, high security, and good scalability and maintainability.
Key words：Hospital website; Java technology; MYSQL database; Spring Boot framework 
目  录

	摘  要	I

	Abstract	II

	1 绪论	1

	1.1研究背景	1

	1.2设计原则	1

	1.3研究内容	2

	2 相关技术简介	3

	2.1 Java技术	3

	2.2 B/S结构	3

	2.3 MYSQL数据库	4

	2.4 Spring Boot框架	4

	3 系统分析	6

	3.1 可行性分析	6

	3.1.1 技术可行性	6

	3.1.2 操作可行性	6

	3.1.3 经济可行性	6

	3.1.4 法律可行性	6

	3.2 系统性能分析	7

	3.3 角色功能分析	7

	3.4 系统结构分析	9

	3.4.1逻辑结构	9

	3.4.2物理结构	9

	3.5 系统流程分析	10

	3.5.1注册流程	10

	3.5.2登录流程	10

	4 系统设计	12

	4.1 系统概要设计	12

	4.2 系统结构设计	12

	4.3 数据库设计	13

	4.3.1数据库实体（E-R图）	13

	4.3.2数据库表设计	16

	5 系统实现	20

	5.1 用户功能模块的实现	20

	5.1.1用户登录界面	20

	5.1.2用户注册界面	21

	5.1.3门诊信息详情界面	22

	5.1.4预约挂号界面	22

	5.1.5药品详情界面	23

	5.1.6体检报告界面	24

	5.2 管理员功能模块的实现	24

	5.2.1管理员登录界面	24

	5.2.2用户管理界面	25

	5.2.3医师管理界面	25

	5.2.4科室类型管理界面	26

	5.2.5门诊信息管理界面	26

	5.2.6药库信息管理界面	26

	5.3 医师功能模块的实现	27

	5.3.1预约挂号管理界面	27

	5.3.2体检报告管理界面	28

	6 系统测试	29

	6.1 测试定义	29

	6.2 测试方式	29

	6.3 测试方案	30

	6.4 测试分析	31

	总结	32

	参考文献	33

	致  谢	34
1 绪论

1.1研究背景

随着计算机技术的成熟、普及，现代信息技术革命的迅猛发展,正冲击并进而改变着经济和社会结构。信息化的程度已经成为一个国家，一个企业，一个组织仍至一个人发展的基础和竞争成败的关键。

在实际的生活中，用户都是去医院进行就诊预约挂号，费事费力，效率低下，因此，针对用户对网上预约挂号的高需求，特开发了本基于Spring Boot的中小型医院网站。在互联网的迅速发展下，局域网的普及，为建立中小型医院网站的设计与实现提供了基础条件。中小型医院网站有着无法比拟的优点，网络共享、传播速度快的特点，用户可以随时随地进行预约挂号，取药等，同时医师可及时查看用户挂号预约信息，并可进行开药等，管理员通过计算机后台可对系统相关信息进行管理，大大提高管理的效率，更好的为广大用户服务。

1.2设计原则

在开始开发项目之前，必须要先考虑项目的实用性、科学性，以及该项目是否能够真正让用户受益并尽可能的发挥项目的作用。因此，在开发前，通过以下几条原则对项目进行判断：

（1）可行性原则。项目需要保证经济可行性和技术可行性，这包括了项目在浏览端、服务端等方面上的经济和技术上是可以达成的。

（2）适应性原则。项目要保证可维护性和可扩展性，这是每个非短期项目都需要考虑的，并且不论是维护还是扩展，都必须要建立在适应用户的正常需求的基础上。

（3）安全性及保密性原则。要充分保证用户信息的安全性和保密性，不能因为开发上的疏忽，导致用户的信息泄露。

（4）系统工程原则。为了确保项目的整体性，在项目调查、项目分析、项目设计、项目开发的过程中，都需遵从项目工程的方法和步骤逐步进行。

（5）统一规划、分期实施、逐步完善原则。项目开发的过程中，要按照规划、分期实施，特别是要注意在项目开发过程中要有条理，从点到面，一步步完善，不要贪图进度，要循环渐进的对项目进行开发。

1.3研究内容

根据基于Spring Boot的中小型医院网站编写的论文主要阐述了基于Spring Boot的中小型医院网站的开发过程中使用的技术，系统开发前进行的需求分析，根据需求文档进行系统设计，最后才是系统功能实现以及测试几个部分，在开始编写论文之前亲自到图书馆借阅Java书籍，MYSQL数据库书籍等编程书籍，然后针对开发的基于Spring Boot的中小型医院网站，去网上查找了很多别人做好的系统，根据他们的功能设计进行自己的系统的系统功能结构设计，出具需求报告，根据形成的需求报告完成系统各个功能模块设计，最后才是进行程序编码，系统完成后才能进行测试和最后的验收工作，程序开发流程大致如此。

这次编写的论文包含了6个部分的内容，具体内容如下：

第一部分绪论：文章主要从课题背景以及设计原则综合阐述了开发此系统的必要性。

第二部分相关技术：系统开发用到的各种技术都大致做出了简介

第三部分系统分析：从可行性分析和功能需求分析等角度综合研究了此次开发的系统

第四部分系统设计：功能模块设计和数据库设计这两部分内容都有专门的表格和图片表示

第五部分系统实现：进行系统主要功能模块的界面展示

第六部分系统测试：检验程序是否达到预期目标
2 相关技术简介

2.1 Java技术

Java是一种非常常用的编程语言，在全球编程语言排行版上总是前三。在方兴未艾的计算机技术发展历程中，Java的身影无处不在，并且拥有旺盛的生命力。Java的跨平台能力十分强大，只需一次编译，任何地方都可以运行。除此之外，它还拥有简单的语法和实用的类库，让编程人员可以尽可能将精力集中在问题的求解上，并且许多开源项目和科研成果都是采用它实现的。

在1995年这一年的5月份，著名的Sun Microsystems公司在程序开发设计上面郑重推出一种面向对象开发的程序设计语言——Java，最开始的时候Java是由詹姆斯.高斯林这位伟大的JAVA之父来进行主导，但是在后来由于各种原因，让甲骨文公司这个针对商业程序创建了oracle大型数据库的公司收购了Java。Java的平台总共算下来有3个，分别为javaME和javaSE以及javaEE这3个java平台。下面将对其进行分别介绍。

（1）在电脑桌面程序的开发上面需要选择JavaME，这个用得也比较多。

（2）企业也会根据工作以及业务需要开发各种软件，那么就会选用JavcEE这个支持企业版软件的开发的Java平台，JavcEE主攻运用在企业领域上面的web应用，JavcEE也在javaSE的基础上获得了比如jsp技术 ，Servlet技术等程序开发技术的支持。

（3）现在生活中手机的普及化，也使得手机端这样的移动设备的软件的兴起，JavaME这个迷你版java平台就能运用于移动端的软件开发操作。

2.2 B/S结构

此次设计的网络结构模式B/S结

```
### 0066springboot中小型医院网站 项目图片
![图片](/images/0066springbootimg_001.jpg)
![图片](/images/0066springbootimg_003.jpg)
![图片](/images/0066springbootimg_002.jpg)
![图片](/images/0066springbootimg_012.jpg)
![图片](/images/0066springbootimg_006.jpg)
![图片](/images/0066springbootimg_007.jpg)
![图片](/images/0066springbootimg_013.jpg)
![图片](/images/0066springbootimg_005.jpg)
![图片](/images/0066springbootimg_011.jpg)
![图片](/images/0066springbootimg_010.jpg)
![图片](/images/0066springbootimg_004.jpg)
![图片](/images/0066springbootimg_009.jpg)
![图片](/images/0066springbootimg_008.jpg)








