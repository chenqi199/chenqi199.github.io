# 0069springboot大创管理系统


# 0069springboot大创管理系统

### 微信： chen_q123456  qq:462201886
### github:chenqi199 gitee :chen_q_i

### [所有项目](https://github.com/GraduationProject-springboot/allSpringbootProjects) 包安装运行

### [所有项目列表excel 腾讯文档 项目清单](https://docs.qq.com/sheet/DSHRFSVZ5aEVYT3N3?tab=BB08J2) 包安装运行

### [github](https://chenqi199.github.io)

### [gitee](https://gitee.com/chen_q_i)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://player.bilibili.com/player.html?isOutside=true&aid=BV16ia6epENY&bvid=BV16ia6epENY&cid=500001610575977&p=70)



### 0069springboot大创管理系统 部分论文
```

﻿基于springboot的大创管理系统
摘要
随着信息技术在管理上越来越深入而广泛的应用，管理信息系统的实施在技术上已逐步成熟。本文介绍了大创管理系统的开发全过程。通过分析大创管理系统管理的不足，创建了一个计算机管理大创管理系统的方案。文章介绍了大创管理系统的系统分析部分，包括可行性分析等，系统设计部分主要介绍了系统功能设计和数据库设计。
本大创管理系统有院系管理员，指导老师以及学生三个角色。学生功能有优秀项目，项目信息，评审方案，大创资讯，项目申报管理，项目中检管理，项目结项管理，项目评审管理，专家评审管理。指导老师功能有个人中心，优秀项目管理，项目类型管理，项目信息管理，项目申报管理，项目中检管理，项目结项管理，项目评审管理，专家评审管理，评审方案管理。院系管理员功能有个人中心，优秀项目管理，项目类型管理，项目信息管理，项目申报管理，项目中检管理，项目结项管理，项目评审管理，专家评审管理，评审方案管理。因而具有一定的实用性。
本站是一个B/S模式系统，采用SSM框架，MYSQL数据库设计开发，充分保证系统的稳定性。系统具有界面清晰、操作简单，功能齐全的特点，使得大创管理系统管理工作系统化、规范化。本系统的使用使管理人员从繁重的工作中解脱出来，实现无纸化办公，能够有效的提高大创管理系统管理效率。

关键词：大创管理系统；SSM框架；MYSQL数据库；Spring Boot
Abstract
With the deepening and extensive application of information technology in management, the implementation of management information systems has gradually matured in technology. This article introduces the entire development process of Daiso's management system. By analyzing the deficiencies of Daiso’s management system, a computer-based solution for Daiso’s management system was created. The article introduces the system analysis part of Daiso management system, including feasibility analysis, etc. The system design part mainly introduces the system function design and database design.
The Daiso management system has three roles: department administrator, instructor and student. Student functions include excellent projects, project information, review plans, Daiso information, project application management, project in-process inspection management, project closure management, project review management, and expert review management. The functions of the instructor include personal center, excellent project management, project type management, project information management, project declaration management, project inspection management, project completion management, project review management, expert review management, and review plan management. Department administrator functions include personal center, excellent project management, project type management, project information management, project declaration management, project inspection management, project completion management, project review management, expert review management, and review plan management. So it has a certain practicability.
This site is a B/S mode system, using SSM framework, MYSQL database design and development, fully guarantee the stability of the system. The system has the characteristics of clear interface, simple operation, and complete functions, which makes Daiso's management system systematized and standardized. The use of this system frees managers from heavy work, realizes a paperless office, and can effectively improve the management efficiency of Daiso's management system.
Keywords: Daiso Management System; SSM framework; MYSQL database; Spring Boot
目录
1系统概述	1
1.1 研究背景	1
1.2研究目的	1
1.3系统设计思想	1
2相关技术	2
2.1 MYSQL数据库	2
2.2 B/S结构	3
2.3 Spring Boot框架简介	4
3系统分析	4
3.1可行性分析	4
3.1.1技术可行性	4
3.1.2经济可行性	5
3.1.3操作可行性	5
3.2系统性能分析	5
3.2.1 系统安全性	5
3.2.2 数据完整性	6
3.3系统界面分析	6
3.4系统流程和逻辑	7
4系统概要设计	8
4.1概述	8
4.2系统结构	9
4.3.数据库设计	10
4.3.1数据库实体	10
4.3.2数据库设计表	12
5系统详细实现	18
5.1 管理员模块的实现	18
5.1.1 项目中检管理	18
5.1.2 专家评审管理	18
5.2 指导老师模块的实现	19
5.2.1 项目申报管理	19
5.2.1 项目结项管理	19
5.2 学生模块的实现	20
5.2.2 学生注册管理	20
5.2.3 优秀项目信息	21
5.2.3 项目信息申报	22
6系统测试	23
6.1概念和意义	23
6.2特性	23
6.3重要性	24
6.4测试方法	24
6.5 功能测试	24
6.6可用性测试	25
6.7性能测试	25
6.8测试分析	26
6.9测试结果分析	26
结论	26
致谢语	27
参考文献	27

1系统概述
1.1 研究背景
随着计算机技术的发展以及计算机网络的逐渐普及，互联网成为人们查找信息的重要场所，二十一世纪是信息的时代，所以信息的管理显得特别重要。因此，使用计算机来管理大创管理系统的相关信息成为必然。开发合适的大创管理系统，可以方便管理人员对大创管理系统的管理，提高信息管理工作效率及查询效率，有利于更好的为人们服务。
1.2研究目的
随着互联网技术的快速发展，网络时代的到来，网络信息也将会改变当今社会。各行各业在日常企业经营管理等方面也在慢慢的向规范化和网络化趋势汇合。大创管理系统的信息化程度体现在将互联网与信息技术应用于经营与管理，以现代化工具代替传统手工作业。无疑，使用网络信息化管理使信息管理更先进、更高效、更科学，信息交流更迅速。
对于之前大创管理系统的管理，大部分都是使用传统的人工方式去管理，这样导致了管理效率低下、出错频率高。而且，时间一长的话，积累下来的数据信息不容易保存，对于查询、更新还有维护会带来不少问题。对于数据交接也存在很大的隐患。如果采用电子化的存储方式就会带来很大的改善，而且给用户的查询带来了很大便利，因此设计一个大创管理系统刻不容缓，能够提高信息的管理水平。
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
MySQL是一个真正的多用户、多线程SQL数据库服务器。 是基于SQL的客户/服务器模式的关系数据库管理系统，它的有点有有功能强大、使用简单、管理方便、安全可靠性高、运行速度快、多线程、跨平台性、完全网络化、稳定性等，非常适用于Web站点或者其他应用软件的数据库后端的开发工作。此外，用户可利用许多语言编写访问MySQL数据库的程序。作为开放源代码运动的产物之一，MySQL关系数据库管

```
### 0069springboot大创管理系统 项目图片
![图片](/images/0069springbootimg_001.jpg)
![图片](/images/0069springbootimg_003.jpg)
![图片](/images/0069springbootimg_002.jpg)
![图片](/images/0069springbootimg_012.jpg)
![图片](/images/0069springbootimg_006.jpg)
![图片](/images/0069springbootimg_007.jpg)
![图片](/images/0069springbootimg_013.jpg)
![图片](/images/0069springbootimg_005.jpg)
![图片](/images/0069springbootimg_011.jpg)
![图片](/images/0069springbootimg_010.jpg)
![图片](/images/0069springbootimg_004.jpg)
![图片](/images/0069springbootimg_009.jpg)
![图片](/images/0069springbootimg_008.jpg)








