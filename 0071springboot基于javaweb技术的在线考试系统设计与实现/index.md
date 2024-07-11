# 0071springboot基于JavaWeb技术的在线考试系统设计与实现


# 0071springboot基于JavaWeb技术的在线考试系统设计与实现

### 微信： chen_q123456  qq:462201886
### github:chenqi199 gitee :chen_q_i

### [所有项目](https://github.com/GraduationProject-springboot/allSpringbootProjects) 包安装运行

### [所有项目列表excel 腾讯文档 项目清单](https://docs.qq.com/sheet/DSHRFSVZ5aEVYT3N3?tab=BB08J2) 包安装运行

### [github](https://chenqi199.github.io)

### [gitee](https://gitee.com/chen_q_i)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://player.bilibili.com/player.html?isOutside=true&aid=BV16ia6epENY&bvid=BV16ia6epENY&cid=500001610576285&p=72)



### 0071springboot基于JavaWeb技术的在线考试系统设计与实现 部分论文
```

﻿基于JavaWeb技术的在线考试系统设计与实现
摘要
随着信息技术在管理上越来越深入而广泛的应用，管理信息系统的实施在技术上已逐步成熟。本文介绍了基于JavaWeb技术的在线考试系统设计与实现的开发全过程。通过分析基于Java Web技术的在线考试系统设计与实现管理的不足，创建了一个计算机管理基于Java Web技术的在线考试系统设计与实现的方案。文章介绍了基于JavaWeb技术的在线考试系统设计与实现的系统分析部分，包括可行性分析等，系统设计部分主要介绍了系统功能设计和数据库设计。
本基于Java Web技术的在线考试系统设计与实现有管理员和用户两个角色。管理员功能有个人中心，用户管理，考试统计管理，专业列表管理，专业类型管理，考试规则管理，忘记密码人员登记管理，考试评分管理，试卷管理，试题管理，系统管理，考试管理等。用户功能有，查看考试规则，试卷列表，考试资讯，参加考试，考试记录，错题本，考试评分等因而具有一定的实用性。
本站是一个B/S模式系统，采用SSM框架，MYSQL数据库设计开发，充分保证系统的稳定性。系统具有界面清晰、操作简单，功能齐全的特点，使得基于Java Web技术的在线考试系统设计与实现管理工作系统化、规范化。本系统的使用使管理人员从繁重的工作中解脱出来，实现无纸化办公，能够有效的提高基于Java Web技术的在线考试系统设计与实现管理效率。

关键词：基于Java Web技术的在线考试系统设计与实现；Spring Boot；MYSQL数据库
Abstract
With the deepening and extensive application of information technology in management, the implementation of management information systems has gradually matured in technology. This article introduces the whole process of the design and implementation of the online examination system based on JavaWeb technology. By analyzing the deficiencies in the design and implementation of the online examination system based on Java Web technology, a computer management scheme for the design and implementation of the online examination system based on Java Web technology is created. The article introduces the system analysis part of the online examination system design and implementation based on JavaWeb technology, including feasibility analysis, etc. The system design part mainly introduces the system function design and database design.
The design and implementation of the online examination system based on Java Web technology has two roles: administrator and user. The administrator functions include personal center, user management, examination statistics management, professional list management, professional type management, examination rule management, registration management of forgotten password personnel, examination scoring management, examination paper management, examination question management, system management, examination management, etc. User functions include viewing exam rules, list of exam papers, exam information, taking exams, exam records, wrong question books, exam scoring, etc. Therefore, it has a certain degree of practicability.
This site is a B/S mode system, using SSM framework, MYSQL database design and development, fully guarantee the stability of the system. The system has the characteristics of clear interface, simple operation and complete functions, which makes the design and implementation of the online examination system based on Java Web technology systematized and standardized. The use of this system frees managers from heavy work, realizes a paperless office, and can effectively improve the design and implementation management efficiency of an online examination system based on Java Web technology.
Keywords: Design and implementation of online examination system based on Java Web technology; Spring Boot; MYSQL database
目录
1系统概述	1
1.1 研究背景	1
1.2研究目的	1
1.3系统设计思想	1
2相关技术	2
2.1 MYSQL数据库	3
2.2 B/S结构	3
2.3 Spring Boot框架简介	4
3系统分析	4
3.1可行性分析	4
3.1.1技术可行性	5
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
5系统详细实现	15
5.1 管理员模块的实现	15
5.1.1 用户信息管理	15
5.1.2 考试统计管理	16
5.2.1 专业列表管理	16
5.2.1 忘记密码人员登记管理	17
5.2 用户模块的实现	18
5.2.2 修改密码	18
5.2.3 试卷信息	18
5.2.3 考试信息管理	19
6系统测试	19
6.1概念和意义	19
6.2特性	20
6.3重要性	20
6.4测试方法	20
6.5 功能测试	21
6.6可用性测试	21
6.7性能测试	22
6.8测试分析	22
6.9测试结果分析	23
结论	23
致谢语	23
参考文献	24

1系统概述
1.1 研究背景
随着计算机技术的发展以及计算机网络的逐渐普及，互联网成为人们查找信息的重要场所，二十一世纪是信息的时代，所以信息的管理显得特别重要。因此，使用计算机来管理基于JavaWeb技术的在线考试系统设计与实现的相关信息成为必然。开发合适的基于JavaWeb技术的在线考试系统设计与实现，可以方便管理人员对基于JavaWeb技术的在线考试系统设计与实现的管理，提高信息管理工作效率及查询效率，有利于更好的为人们服务。
1.2研究目的
随着互联网技术的快速发展，网络时代的到来，网络信息也将会改变当今社会。各行各业在日常企业经营管理等方面也在慢慢的向规范化和网络化趋势汇合。基于JavaWeb技术的在线考试系统设计与实现的信息化程度体现在将互联网与信息技术应用于经营与管理，以现代化工具代替传统手工作业。无疑，使用网络信息化管理使信息管理更先进、更高效、更科学，信息交流更迅速。
对于之前基于JavaWeb技术的在线考试系统设计与实现的管理，大部分都是使用传统的人工方式去管理，这样导致了管理效率低下、出错频率高。而且，时间一长的话，积累下来的数据信息不容易保存，对于查询、更新还有维护会带来不少问题。对于数据交接也存在很大的隐患。如果采用电子化的存储方式就会带来很大的改善，而且给用户的查询带来了很大便利，因此设计一个基于JavaWeb技术的在线考试系统设计与实现刻不容缓，能够提高信息的管理水平。
1.3系统设计思想
一个成功的网站应明确建设网站的目的，确定网站的功能，确定网站规模、投入费用，进行必要的市场分析等。只有详细的策划，才能避免在网站建设中出现的很多问题，使网站建设能顺利进行。同时，一个大型的计算机网站系统，必须有一个正确的设计指导思想，通过合理选择数据结构、网络结构、操作系统以及开发环境，构成一个完善的网络体系结构，才能充分发挥计算机信息管理的优势。根据现实生活中网民的实际需求，本系统的设计按照下述原则进行。
    1. 有效性：实际上这里的有效性包括两个方面的意思：有用性和可用性。有用性是指站点潜在的能满足用户需求的功能，而可用性是指能够通过站点的操作实现特定的目标。可以看出一个站点如果不能恰当运行或设计得非常槽糕就不是一个好站点。可用站点的效益应该非常高，并易于学习，在实现用户目标时令人满意而不出错。
    2. 高可靠性：一个实用的网站同时必须是可靠的，本设计通过合理而先进的网络设计以及软、硬件的优化选型，可保证网站的可靠性与容错性。
    3. 高安全性：在设计中，将充分利用网络软、硬件提供的各种安全措施，既可以保证用户共享资源，充分考虑系统及数据资源的容灾、备份、恢复的要求。为系统提供强大的数据库备份工具。可以保证关键数据的安全性。操作权限级，设置不同的角色确保每一步的操作权限，可以由管理员进行设置。
    4. 先进性：采用目前国际上最先进的开发技术，使用JSP开发技术，MYSQL作为网站后台数据库。采用这些技术降低了以后的系统运营成本，提高了系统的稳定性和易维护性。
    5. 采用标准技术：本网站的所有设计遵循国际上现行的标准进行，以提高系统的开放性。
    6. 外观和技术平衡：系统采用Web风格的界面设计，界面友好、美观，使用方便，易学易用。网站设计的关键问题是外观和技术的平衡。外现不好的网站令人厌烦，站点可以运行很好，但却不能带动用户积极性，相反，如果外观非常有表现力，但技术有限，用户则会感到非常失望。在外观与技术之间需要确定一个清晰而连续的关系，

```
### 0071springboot基于JavaWeb技术的在线考试系统设计与实现 项目图片
![图片](/images/0071springbootimg_001.jpg)
![图片](/images/0071springbootimg_003.jpg)
![图片](/images/0071springbootimg_002.jpg)
![图片](/images/0071springbootimg_012.jpg)
![图片](/images/0071springbootimg_006.jpg)
![图片](/images/0071springbootimg_007.jpg)
![图片](/images/0071springbootimg_013.jpg)
![图片](/images/0071springbootimg_005.jpg)
![图片](/images/0071springbootimg_011.jpg)
![图片](/images/0071springbootimg_010.jpg)
![图片](/images/0071springbootimg_004.jpg)
![图片](/images/0071springbootimg_009.jpg)
![图片](/images/0071springbootimg_008.jpg)








