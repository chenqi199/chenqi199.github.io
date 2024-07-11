# 0051springboot旅游管理系统的设计与实现


# 0051springboot旅游管理系统的设计与实现

### 微信： chen_q123456  qq:462201886
### github:chenqi199 gitee :chen_q_i

### [所有项目](https://github.com/GraduationProject-springboot/allSpringbootProjects) 包安装运行

### [所有项目列表excel 腾讯文档 项目清单](https://docs.qq.com/sheet/DSHRFSVZ5aEVYT3N3?tab=BB08J2) 包安装运行

### [github](https://chenqi199.github.io)

### [gitee](https://gitee.com/chen_q_i)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://player.bilibili.com/player.html?isOutside=true&aid=BV16ia6epENY&bvid=BV16ia6epENY&cid=500001610574012&p=52)



### 0051springboot旅游管理系统的设计与实现 部分论文
```


                              毕业设计（论文）
　
               基于Bootstrap的常州地方旅游管理系统的设计与实现
          姓　　名　　　　　　　　　       　　　 　
          学　　号　　　　　　　　　　　         　
          院  　系　　　　　　　　　　　       　 　
          专　　业　　　　　　　　　　       　 　　
          指导老师　      　　　　　　　       　　
                       2021 年    月
                      教务处制
                                  目    录
目  录 I
摘  要 III
Abstract  IV
第一章 绪论   1

  1.1 研究现状   1
  1.2 设计原则   1
  1.3 研究内容   2

第二章 相关技术简介 1

  2.1 JAVA技术   1
  2.2 MYSQL数据库    1
  2.3 B/S结构 2
  2.4 Spring Boot框架   2

第三章 系统分析  4

  3.1可行性分析  4
   3.1.1技术可行性  4
   3.1.2 操作可行性 4
   3.1.3 经济可行性 4
   3.1.4 法律可行性 4
  3.2系统性能分析    5
  3.3系统功能分析    5
  3.4系统流程分析    6
   3.4.1注册流程 6
   3.4.2 登录流程   7
  3.5系统架构分析    7

第四章 系统设计  9

  4.1系统结构设计    9
  4.2系统顺序图设计  9
  4.3数据库设计  10
   4.3.1 数据库实体（E-R图）  10
   4.3.2 数据库表设计  12

第五章 系统实现  15

  5.1登录模块的实现  15
  5.2管理员功能模块的实现  15
   5.2.1景点信息管理界面  15
   5.2.2订票信息管理界面  16
   5.2.3用户评价管理界面  17
   5.2.4用户管理界面   17
   5.2.5景点资讯界面   18
  5.3用户功能模块的实现 18
   5.3.1系统主界面  18
   5.3.2用户注册界面   19
   5.3.3景点信息详情界面  19
   5.3.4订票信息界面   20

第六章 系统测试  22

  6.1测试环境 22
  6.2测试方法 22
  6.3测试计划 23
  6.4测试结论 23

第七章 结论   24
参考文献  25
致  谢 26
                                   摘  要

    随着旅游业的迅速发展，传统的旅游信息查询方式，已经无法满足用户需求，因此，
结合计算机技术的优势和普及，针对常州旅游，特开发了本基于Bootstrap的常州地方旅
游管理系统。
    本论文首先对常州地方旅游管理系统进行需求分析，从系统开发环境、系统目标、设
计流程、功能设计等几个方面进行系统的总体设计，开发出本基于Bootstrap的常州地方
旅游管理系统，主要实现了用户功能模块和管理员功能模块两大部分，用户可查看景点
信息、景点资讯等，注册登录后可进行景点订票操作，同时管理员可进入系统后台对系
统进行全面管理操作。通过对系统的功能进行测试，测试结果证明该系统界面友好、功
能完善，有着较高的使用价值，具有庞大的潜在用户群体和较广阔的应用前景。
    本常州地方旅游管理系统基于Springboot+Bootstrap框架、JAVA编程语言、MYSQL数
据库开发完成，“操作简单，功能实用”这是本软件设计的核心理念，本系统力求创造最
好的用户体验。
    关键词：常州地方旅游；Bootstrap框架；MYSQL数据库；JAVA编程语言
                                  Abstract

   With the rapid development of the tourism industry, traditional  tourism
information query methods can no longer meet the needs of users.  Therefore,
combined with the advantages and popularization of computer technology,  for
Changzhou tourism, a Bootstrap-based  local  tourism  management  system  in
Changzhou has been specially developed.
   This thesis first analyzes the needs  of  the  Changzhou  local  tourism
management system, and conducts the overall design of the  system  from  the
system  development  environment,   system   objectives,   design   process,
functional  design,  etc.,  and  develops  the   Changzhou   local   tourism
management system based on Bootstrap, which  is  mainly  realized  The  user
function module and the administrator function module  are  two  parts.  The
user can view the scenic spot information, scenic  spot  information,  etc.,
after registering and logging in, the scenic spot booking operation  can  be
carried out, and the  administrator  can  enter  the  system  background  to
perform comprehensive management operations on the system.  By  testing  the
functions of the system, the test  results  prove  that  the  system  has  a
friendly interface, complete functions, high use  value,  a  huge  potential
user group and a broader application prospect.
   This Changzhou local tourism management system  is  developed  based  on
Springboot+Bootstrap  framework,  JAVA  programming  language,   and   MYSQL
database. "Simple operation and practical functions" is the core concept  of
this  software  design.  This  system  strives  to  create  the  best   user
experience.
    Key Words：Changzhou local tourism; Bootstrap framework; MYSQL database;
JAVA programming language
                                 第一章 绪论
1.1 研究现状

    时代的发展，我们迎来了数字化信息时代，它正在渐渐的改变着人们的工作、学习以
及娱乐方式。计算机网络，Internet扮演着越来越重要的角色，人们已经离不开网络了
，大量的图片、文字、视频冲击着我们的视觉。
    随着社会生产力的发展，人们的生活水平越来越高。旅游，越来越成为人们一种休闲
娱乐的方式。喧嚣的都市，高强度的工作与生活，让很多人身心疲惫。而旅游，则可以
调节身心、恢复疲惫和增加人们的阅历。在旅游度假区，既可以了解当地的人文情怀，
又可以在碧水蓝天间忘却烦恼。所以，旅游越来越受人民的欢迎。根据联合国世界旅游
组织最新发布的《世界旅游晴雨表》，2015年国际游客人数相比2014年增长了4.4％，达到
11.84亿人次。随着社会和经济的发展，旅游业已成长为世界经济中发展势头最强劲和规
模最大的产业之一。
    因此，为了给用户提供一个便利的查看常州旅游信息、景点订票的平台，开发了本基
于Bootstrap的常州地方旅游管理系统。

1.2 设计原则

    在开始开发项目之前，必须要先考虑项目的实用性、科学性，以及该项目是否能够真
正让用户受益并尽可能的发挥项目的作用。因此，在开发前，通过以下几条原则对项目
进行判断：
    （1）可行性原则。项目需要保证经济可行性和技术可行性，这包括了项目在浏览端
、服务端等方面上的经济和技术上是可以达成的。
    （2）适应性原则。项目要保证可维护性和可扩展性，这是每个非短期项目都需要考
虑的，并且不论是维护还是扩展，都必须要建立在适应用户的正常需求的基础上。
    （3）安全性及保密性原则。要充分保证用户信息的安全性和保密性，不能因为开发
上的疏忽，导致用户的信息泄露。
    （4）系统工程原则。为了确保项目的整体性，在项目调查、项目分析、项目设计、
项目开发的过程中，都需遵从项目工程的方法和步骤逐步进行。
    （5）统一规划、分期实施、逐步完善原则。项目开发的过程中，要按照规划、分期
实施，特别是要注意在项目开发过程中要有条理，从点到面，一步步完善，不要贪图进
度，要循环渐进的对项目进行开发。

1.3 研究内容

    根据基于Bootstrap的常州地方旅游管理系统编写的论文主要阐述了基于Bootstrap的
常州地方旅游管理系统的开发过程中使用的技术，首先进行系统需求分析，进而进行系
统设计，最后才是系统功能实现以及测试几个部分，在开始编写论文之前亲自到图书馆
借阅Java书籍，MYSQL数据库书籍等编程书籍，然后针对开发的基于Bootstrap的常州地
方旅游管理系统，去网上查找了很多别人做好的系统，根据他们的功能设计进行自己的
系统的系统功能结构设计，出具需求报告，最后才是进行程序编码，系统完成后才能进
行测试和最后的验收工作，程序开发流程大致如此。
    这次编写的论文包含了6个部分的内容，具体内容如下：
    第一部分绪论：文章主要从课题背景以及设计原则综合阐述了开发此系统的必要性。

    第二部分相关技术：系统开发用到的各种技术都大致做出了简介
    第三部分系统分析：从可行性分析和功能需求分析等角度综合研究了此次开发的系统

    第四部分系统设计：功能模块设计和数据库设计这两部分内容都有专门的表格和图片
表示
    第五部分系统实现：进行系统主要功能模块的界面展示
    

```
### 0051springboot旅游管理系统的设计与实现 项目图片
![图片](/images/0051springbootimg_001.jpg)
![图片](/images/0051springbootimg_003.jpg)
![图片](/images/0051springbootimg_002.jpg)
![图片](/images/0051springbootimg_012.jpg)
![图片](/images/0051springbootimg_006.jpg)
![图片](/images/0051springbootimg_007.jpg)
![图片](/images/0051springbootimg_013.jpg)
![图片](/images/0051springbootimg_005.jpg)
![图片](/images/0051springbootimg_011.jpg)
![图片](/images/0051springbootimg_010.jpg)
![图片](/images/0051springbootimg_004.jpg)
![图片](/images/0051springbootimg_009.jpg)
![图片](/images/0051springbootimg_008.jpg)








