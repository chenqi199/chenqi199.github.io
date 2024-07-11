# 0059springboot师生共评的作业管理系统设计与实现


# 0059springboot师生共评的作业管理系统设计与实现

### 微信： chen_q123456  qq:462201886
### github:chenqi199 gitee :chen_q_i

### [所有项目](https://github.com/GraduationProject-springboot/allSpringbootProjects) 包安装运行

### [所有项目列表excel 腾讯文档 项目清单](https://docs.qq.com/sheet/DSHRFSVZ5aEVYT3N3?tab=BB08J2) 包安装运行

### [github](https://chenqi199.github.io)

### [gitee](https://gitee.com/chen_q_i)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://player.bilibili.com/player.html?isOutside=true&aid=BV16ia6epENY&bvid=BV16ia6epENY&cid=500001610574931&p=60)



### 0059springboot师生共评的作业管理系统设计与实现 部分论文
```

﻿师生共评的作业管理系统设计与实现
摘要
随着信息互联网信息的飞速发展，无纸化作业变成了一种趋势，针对这个问题开发一个专门适应师生作业交流形式的网站。本文介绍了师生共评的作业管理系统的开发全过程。通过分析企业对于师生共评的作业管理系统的需求，创建了一个计算机管理师生共评的作业管理系统的方案。文章介绍了师生共评的作业管理系统的系统分析部分，包括可行性分析等，系统设计部分主要介绍了系统功能设计和数据库设计。
本师生共评的作业管理系统管理员，学生，教师，组长共四个权限。
管理员有管理所有基本信息的功能。教师功能：个人中心，小组信息管理，课程管理，作业管理，作业互评管理，作业评分管理。组长是教师进行设定的，主要协助教师管理作业相关事宜。学生功能：个人中心，课程管理，作业管理，作业互评管理，作业评分管理，作业提交管理。因而具有一定的实用性。
本站是一个B/S模式系统，采用Spring Boot框架作为后台开发技术，前端框架是VUE，MYSQL数据库设计开发，充分保证系统的稳定性。系统具有界面清晰、操作简单，功能齐全的特点，使得师生共评的作业管理系统管理工作系统化、规范化。

关键词：师生共评的作业管理系统；Spring Boot框架；MYSQL数据库；VUE框架
Abstract
With the rapid development of information on the Internet, paperless homework has become a trend. In response to this problem, a website specially adapted to the form of communication between teachers and students has been developed. This article introduces the whole process of the development of the homework management system for teachers and students. By analyzing the needs of the enterprise for the homework management system for teachers and students, a computer-based homework management system for teachers and students was created. The article introduces the system analysis part of the homework management system evaluated by teachers and students, including feasibility analysis, etc. The system design part mainly introduces the system function design and database design.
The homework management system administrator, student, teacher, and group leader for this teacher and student evaluation have four permissions.
The administrator has the function of managing all basic information. Teacher functions: personal center, group information management, course management, homework management, homework evaluation management, homework grading management. The group leader is set by the teacher and mainly assists the teacher in managing homework-related matters. Student functions: personal center, course management, homework management, homework mutual evaluation management, homework grading management, homework submission management. So it has a certain practicability.
This site is a B/S model system, using Spring Boot framework as the back-end development technology, front-end framework is VUE, MYSQL database design and development, fully guarantee the stability of the system. The system has the characteristics of clear interface, simple operation and complete functions, which makes the management of the homework management system for teachers and students systematic and standardized.
Keywords:Homework management system evaluated by teachers and students; Spring Boot framework; MYSQL database; VUE framework
目录
1系统概述	1
1.1 研究背景	1
1.2研究目的	1
1.3系统设计思想	1
2相关技术	3
2.1 MYSQL数据库	3
2.2 B/S结构	3
2.3 Spring Boot框架简介	4
2.4 VUE框架	4
3系统分析	5
3.1可行性分析	5
3.1.1技术可行性	5
3.1.2经济可行性	5
3.1.3操作可行性	5
3.2系统性能分析	6
3.2.1 系统安全性	6
3.2.2 数据完整性	6
3.3系统界面分析	6
3.4系统流程和逻辑	8
4系统概要设计	9
4.1概述	9
4.2系统结构	10
4.3.数据库设计	11
4.3.1数据库实体	11
4.3.2数据库设计表	13
5系统详细实现	17
5.1 学生模块的实现	17
5.1.1 课程管理	17
5.1.2 作业管理	18
5.2.1 作业互评	18
5.3 教师模块的实现	19
5.2.2 小组管理	19
5.3.1 作业管理	19
5.3.2 作业评分	20
6系统测试	20
6.1概念和意义	20
6.2特性	21
6.3重要性	21
6.4测试方法	21
6.5 功能测试	22
6.6可用性测试	22
6.7性能测试	23
6.8测试分析	23
6.9测试结果分析	24
结论	24
致谢语	24
参考文献	25

1系统概述
1.1 研究背景
如今互联网高速发展，网络遍布全球，通过互联网发布的消息能快而方便的传播到世界每个角落，并且互联网上能传播的信息也很广，比如文字、图片、声音、视频等。从而，这种种好处使得互联网成了信息传播的主要途径，社会上各种各样的信息都想尽办法通过互联网进行传播，互联网对社会产生的影响越来越大。
随着计算机技术的发展以及计算机网络的逐渐普及，互联网成为人们查找信息的重要场所，二十一世纪是信息的时代，所以信息的交换和信息流通显得特别重要。因此，开发合适的师生共评的作业管理系统成为企业必然要走的一步棋。开发合适的师生共评的作业管理系统，可以方便管理人员对师生共评的作业管理系统的管理，提高信息管理工作效率及查询效率，有利于更好的为用户提供服务。
1.2研究目的
随着互联网技术的快速发展，网络时代的到来，网络信息也将会改变当今社会。各行各业在日常企业经营管理等方面也在慢慢的向规范化和网络化趋势汇合。师生共评的作业管理系统的信息化程度体现在将互联网与信息技术应用于经营与管理，以现代化工具代替传统手工作业。无疑，使用网络信息化管理使信息管理更先进、更高效、更科学，信息交流更迅速。
医院如何还用直接只用纸质票据来进行开方子，取药，以及其他业务操作，已经很落伍了，这样会导致了效率低下。而且，时间一长的话，积累下来的数据信息不容易保存，对于查询、更新还有维护会带来不少问题。对于数据交接也存在很大的隐患。如果采用电子化的存储方式就会带来很大的改善，而且给用户的查询带来了很大便利，因此设计一个师生共评的作业管理系统刻不容缓，能够提高企业在信息技术方面的展示水平。
1.3系统设计思想
一个成功的网站应明确建设网站的目的，确定网站的功能，确定网站规模、投入费用，进行必要的市场分析等。只有详细的策划，才能避免在网站建设中出现的很多问题，使网站建设能顺利进行。同时，一个大型的计算机网站系统，必须有一个正确的设计指导思想，通过合理选择数据结构、网络结构、操作系统以及开发环境，构成一个完善的网络体系结构，才能充分发挥计算机信息管理的优势。根据现实生活中网民的实际需求，本系统的设计按照下述原则进行。
    1. 有效性：实际上这里的有效性包括两个方面的意思：有用性和可用性。有用性是指站点潜在的能满足用户需求的功能，而可用性是指能够通过站点的操作实现特定的目标。可以看出一个站点如果不能恰当运行或设计得非常槽糕就不是一个好站点。可用站点的效益应该非常高，并易于学习，在实现用户目标时令人满意而不出错。
    2. 高可靠性：一个实用的网站同时必须是可靠的，本设计通过合理而先进的网络设计以及软、硬件的优化选型，可保证网站的可靠性与容错性。
    3. 高安全性：在设计中，将充分利用网络软、硬件提供的各种安全措施，既可以保证用户共享资源，充分考虑系统及数据资源的容灾、备份、恢复的要求。为系统提供强大的数据库备份工具。可以保证关键数据的安全性。操作权限级，设置不同的角色确保每一步的操作权限，可以由管理员进行设置。
    4. 先进性：采用目前国际上最先进的开发技术，使用JSP开发技术，MYSQL作为网站后台数据库。采用这些技术降低了以后的系统运营成本，提高了系统的稳定性和易维护性。
    5. 采用标准技术：本网站的所有设计遵循国际上现行的标准进行，以提高系统的开放性。
    6. 外观和技术平衡：系统采用Web风格的界面设计，界面友好、美观，使用方便，易学易用。网站设计的关键问题是外观和技术的平衡。外现不好的网站令人厌烦，站点可以运行很好，但却不能带动用户积极性，相反，如果外观非常有表现力，但技术有限，用户则会感到非常失望。在外观与技术之间需要确定一个清晰而连续的关系，即外观与站点的意图相关，对不同类型的网站处理方法不同。
2相关技术
2.1 MYSQL数据库
MySQL是一个真正的多用户、多线程SQL数据库服务器。 是基于SQL的客户/服务器模式的关系数据库管理系统，它的有点有有功能强大、使用简单、管理方便、安全可靠性高、运行速度快、多线程、跨平台性、完全网络化、稳定性等，非常适用于Web站点或者其他应用软件的数据库后端的开发工作。此外，用户可利用许多语言编写访问MySQL数据库的程序。作为开放源代码运动的产物之一，MySQL关系数据库管理系统越来越受到人们的青睐，应用范围也越来越广。速度和易用性使MySQL特别适用于Web站点或应用软件

```
### 0059springboot师生共评的作业管理系统设计与实现 项目图片
![图片](/images/0059springbootimg_001.jpg)
![图片](/images/0059springbootimg_003.jpg)
![图片](/images/0059springbootimg_002.jpg)
![图片](/images/0059springbootimg_012.jpg)
![图片](/images/0059springbootimg_006.jpg)
![图片](/images/0059springbootimg_007.jpg)
![图片](/images/0059springbootimg_013.jpg)
![图片](/images/0059springbootimg_005.jpg)
![图片](/images/0059springbootimg_011.jpg)
![图片](/images/0059springbootimg_010.jpg)
![图片](/images/0059springbootimg_004.jpg)
![图片](/images/0059springbootimg_009.jpg)
![图片](/images/0059springbootimg_008.jpg)








