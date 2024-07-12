# 0127springboot中小企业人事管理系统代码


# [0127springboot中小企业人事管理系统代码](https://github.com/GraduationProject-springboot/0127springboot)

### 微信： chen_q123456  qq:462201886
### github:chenqi199

### [所有项目](https://github.com/GraduationProject-springboot/allSpringbootProjects) 包安装运行

### [所有项目列表excel 腾讯文档 项目清单](https://docs.qq.com/sheet/DSHRFSVZ5aEVYT3N3?tab=BB08J2) 包安装运行

### [github](https://chenqi199.github.io)








# 0127springboot中小企业人事管理系统代码

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://player.bilibili.com/player.html?isOutside=true&aid=BV1jqaLe1ECs&bvid=BV1jqaLe1ECs&cid=500001610724183&p=27)

### [所有项目](https://github.com/GraduationProject-springboot/allSpringbootProjects) 包安装运行












# 摘 要

随着科学技术的飞速发展，社会的方方面面、各行各业都在努力与现代的先进技术接轨，通过科技手段来提高自身的优势，中小企业人事管理系统当然也不能排除在外。中小企业人事管理系统是以实际运用为开发背景，运用软件工程原理和开发方法，采用springboot框架构建的一个管理系统。整个开发过程首先对软件系统进行需求分析，得出系统的主要功能。接着对系统进行总体设计和详细设计。总体设计主要包括系统功能设计、系统总体结构设计、系统数据结构设计和系统安全设计等；详细设计主要包括系统数据库访问的实现，主要功能模块的具体实现，模块实现关键代码等。最后对系统进行功能测试，并对测试结果进行分析总结，得出系统中存在的不足及需要改进的地方，为以后的系统维护提供了方便，同时也为今后开发类似系统提供了借鉴和帮助。这种个性化的网上管理系统特别注重交互协调与管理的相互配合，激发了管理人员的创造性与主动性，对中小企业人事管理系统而言非常有利。

本中小企业人事管理系统采用的数据库是Mysql，使用springboot框架开发。在设计过程中，充分保证了系统代码的良好可读性、实用性、易扩展性、通用性、便于后期维护、操作方便以及页面简洁等特点。

关键词：中小企业人事管理系统，springboot框架 Mysql数据库 Java技术

# ABSTRACT

# With the rapid development of science and technology, all aspects of society and all walks of life are trying to integrate with modern advanced technology, and improve their own advantages through scientific and technological means. Of course, the personnel management system of small and medium-sized enterprises can not be excluded. The personnel management system of small and medium-sized enterprises is a management system based on the practical application, using software engineering principles and development methods, and using springboot framework. In the whole development process, we first analyze the requirements of the software system and get the main functions of the system. Then the overall design and detailed design of the system. The overall design mainly includes system function design, system overall structure design, system data structure design and system security design; The detailed design mainly includes the realization of the system database access, the concrete realization of the main function module, the key code of the module implementation and so on. Finally, the function of the system is tested, and the test results are analyzed and summarized. The deficiencies and the need for improvement in the system are obtained, which provides convenience for the future system maintenance, and also provides reference and help for the future development of similar systems. This personalized online management system pays special attention to the interaction and coordination of management, stimulates the creativity and initiative of managers, and is very beneficial to the personnel management system of small and medium-sized enterprises.

# The personnel management system of small and medium-sized enterprises uses MySQL as the database, which is developed with springboot framework. In the design process, it fully ensures the good readability, practicability, expansibility, universality, easy to maintain, easy to operate and concise page of the system code.

# Key words: SME personnel management system, springboot framework, MySQL database, Java technology

# 目 录

[摘 要 I](#摘-要)

[ABSTRACT II](#abstract)

[目 录
II](#with-the-rapid-development-of-science-and-technology-all-aspects-of-society-and-all-walks-of-life-are-trying-to-integrate-with-modern-advanced-technology-and-improve-their-own-advantages-through-scientific-and-technological-means.-of-course-the-personnel-management-system-of-small-and-medium-sized-enterprises-can-not-be-excluded.-the-personnel-management-system-of-small-and-medium-sized-enterprises-is-a-management-system-based-on-the-practical-application-using-software-engineering-principles-and-development-methods-and-using-springboot-framework.-in-the-whole-development-process-we-first-analyze-the-requirements-of-the-software-system-and-get-the-main-functions-of-the-system.-then-the-overall-design-and-detailed-design-of-the-system.-the-overall-design-mainly-includes-system-function-design-system-overall-structure-design-system-data-structure-design-and-system-security-design-the-detailed-design-mainly-includes-the-realization-of-the-system-database-access-the-concrete-realization-of-the-main-function-module-the-key-code-of-the-module-implementation-and-so-on.-finally-the-function-of-the-system-is-tested-and-the-test-results-are-analyzed-and-summarized.-the-deficiencies-and-the-need-for-improvement-in-the-system-are-obtained-which-provides-convenience-for-the-future-system-maintenance-and-also-provides-reference-and-help-for-the-future-development-of-similar-systems.-this-personalized-online-management-system-pays-special-attention-to-the-interaction-and-coordination-of-management-stimulates-the-creativity-and-initiative-of-managers-and-is-very-beneficial-to-the-personnel-management-system-of-small-and-medium-sized-enterprises.)

[第1章 绪论 1](#第1章-绪论)

> [1.1背景及意义 1](#背景及意义)
>
> [1.2 国内外研究概况 1](#国内外研究概况)
>
> [1.3 研究的内容 1](#研究的内容)

[第2章 相关技术 2](#相关技术)

> [2.1 Tomcat服务器 2](#__RefHeading___Toc30171)
>
> [2.2 Java技术介绍 3](#__RefHeading___Toc20072)
>
> [2.3 mysql数据库介绍 3](#__RefHeading___Toc20072)
>
> [2.4 springboot框架 4](#__RefHeading___Toc25808)

[第3章 系统分析 5](#第3章-系统分析)

> [3.1 需求分析 5](#需求分析)
>
> [3.2 系统可行性分析 5](#系统可行性分析)

[3.2.1技术可行性：技术背景 5](#技术可行性技术背景)

[3.2.2经济可行性 6](#经济可行性)

[3.2.3操作可行性： 6](#操作可行性)

> [3.3 项目设计目标与原则 6](#项目设计目标与原则)
>
> [3.4系统流程分析 7](#系统流程分析)

[3.4.1操作流程 7](#操作流程)

[3.4.2添加信息流程 8](#添加信息流程)

[3.4.3删除信息流程 9](#删除信息流程)

[第4章 系统设计 11](#第4章-系统设计)

> [4.1 系统体系结构 11](#系统体系结构)
>
> [4.2开发流程设计系统 12](#开发流程设计)
>
> [4.3 数据库设计原则 13](#数据库设计原则)
>
> [4.4 数据表 15](#数据表)

[第5章 系统详细设计 19](#第5章-系统详细设计)

> [5.1管理员功能模块 20](#管理员功能模块)
>
> [5.2员工功能模块 23](#员工功能模块)

[第6章 系统测试 25](#第6章-系统测试)

> [6.1系统测试的目的 25](#系统测试的目的)
>
> [6.2系统测试方法 25](#系统测试方法)
>
> [6.3功能测试 26](#功能测试)

[结 论 28](#__RefHeading___Toc1953)

[致 谢 29](#__RefHeading___Toc1495)

[参考文献 30](#参考文献)

# **第1章 绪论**

## 1.1背景及意义

随着社会的快速发展，计算机的影响是全面且深入的。人们生活水平的不断提高，日常生活中人们对中小企业人事管理系统方面的要求也在不断提高，随着中小企业人事受到广大员工的关注，使得中小企业人事管理系统的开发成为必需而且紧迫的事情。中小企业人事管理系统主要是借助计算机，通过对中小企业人事管理系统所需的信息管理，增加员工的选择，同时也方便对广大中小企业人事管理系统的及时查询、修改以及对中小企业人事管理系统的及时了解。中小企业人事管理系统对员工带来了更多的便利，该系统通过和数据库管理系统软件协作来满足员工的需求。计算机技术在现代管理中的应用，使计算机成为人们应用现代技术的重要工具。能够有效的解决获取信息便捷化、全面化的问题，提高效率。

本中小企业人事管理系统主要牵扯到程序，数据库与计算机技术等。覆盖知识面大，可以大大的提高系统人员工作效率。

## 1.2 国内外研究概况

随着国内经济形势的不断发展，中国互联网进入了一个难得的高峰发展时期，这使得中外资本家纷纷转向互联网市场。然而，许多管理领域的不合理结构，人员不足以及管理需求的增加使得更多的人具备了互联网管理的意识。

在当今高度发达的信息中，信息管理改革已成为一种更加广泛和全面的趋势。"中小企业人事管理系统"是基于Mysql数据库，在springboot框架程序设计的基础上实现的。为确保中国经济的持续发展，信息时代日益更新，中小企业人事管理系统更是蓬勃发展。同时，随着信息社会的快速发展，中小企业人事管理系统面临着越来越多的信息，因此很难获得他们对高效信息的需求，如何使用方便快捷的方式使查询者在广阔的中小企业人事管理系统信息中查询，存储，管理和共享信息方面有效，对我们的学习，工作和生活具有重要的现实意义。因此，国内外学术界对此进行了深入而广泛的研究，一个新的研究领域------中小企业人事管理系统诞生了。

## 1.3 研究的内容

目前许多人仍将传统的纸质工具作为信息管理的主要工具，而网络技术的应用只是起到辅助作用。在对网络工具的认知程度上，较为传统的office软件等仍是人们使用的主要工具，而相对全面且专业的中小企业人事管理系统的信息管理软件仍没有得到大多数人的了解或认可。本选题则旨在通过标签分类管理等方式，实现管理员：首页、个人中心、员工管理、部门信息管理、职位信息管理、福利信息管理、培训信息管理、任务信息管理、工资信息管理、考勤信息管理、招聘信息管理，员工；首页、个人中心、部门信息管理、福利信息管理、培训信息管理、任务信息管理、工资信息管理、考勤信息管理功能。从而达到对中小企业人事管理系统信息的高效管理。

# **相关技术**

## 2.1 Tomcat服务器

Tomcat属于一种轻型的服务器，所以说在中小企业中并不具有普适性。但是当程序员需要开发或调试JSP
程序时，则通常会将该服务器作为首选。对于一个仅具有计算机基础知识的人来说，计算机系统具有一个好的Apache服务器，可以很好的对HTML
页面进行访问。Tomcat
虽然是Apache的扩展，但是它们都是可以独立运行的，二者是不互相干扰的。当配置正确的时候，Apache服务器为HTML
页面的运行提供技术支持，Tomcat 的任务则是运行Servle和JSP
页面。Tomca也具有一定的HTML页面处理功能。

### **2.2 Java技术介绍** 

Java语言擅长开发互联网类应用和企业级应用，现在已经相当的成熟，而且也是目前使用最多的编程语言之一。Java语言具有很好的面向对象性，可以符合人的思维模式进行设计，封装是将对象的属性和方法尽可能地隐藏起来，使得外界并不知道是如何实现的，外界能通过接口进行访问，继承是指每个类都会有一个父类，所有的子类都有父类的方法，可以进行继承，但是只有final修饰的类不能被继承，通过继承可以使得代码得到重新利用，能够提高软件的开发效率，也是多态的前提。

Java就像C语言、C#语言等，也是一种程序开发语言，而它的特点就是面向对象。作为一种程序开发与设计的语言，它有很多特性，主要特性就是面向对象、夸平台以及可以分布式运行。Java语言项目不但安全性高、稳定性强，而且可以并发运行。

为了提高开发的速度及效率，必须做到代码的重复使用和简化程序的复杂度，要达到上述的要求java语言通过封装、继承与多态等方式实现，这样可以很大程度上达到信息的封装，提高代码复用率，减少冗余度，提高效率。它使得以往程序中大量存在的内存泄漏的问题得到了较好的缓解。所谓的内存泄漏就是程序向操作系统申请了一块存储空间，比如定义了一个变量，但是由于某种原因，这个变量一直没有使用，但是仍然占用着系统的内存空间，可能一两个这样的变量对程序和操作系统造不成什么大的影响，但是试想如果这样的变量定义的多了系统的内存空间就会一步步减少，从而造成机器的性能降低甚至宕机。但是在Java中有垃圾回收机制的存在，这种机制极大地避免了内存泄漏的出现，在Java虚拟机中，垃圾回收机制会对长时间没有引用变量指向的对象实施垃圾回收，简单的说就是将这个对象销毁，以避免内存泄漏的情况出现。

###  **2.3 mysql数据库介绍** 

MySQL是一款Relational Database Management
System，直译过来的意思就是关系型数据库管理系统，MySQL有着它独特的特点，这些特点使他成为目前最流行的RDBMS之一，MySQL想比与其他数据库如ORACLE、DB2等，它属于一款体积小、速度快的数据库，重点是它符合本次毕业设计的真实租赁环境，拥有成本低，开发源码这些特点，这也是选择它的主要原因。

本系统使用了MySQL数据库，建立了多张数据库表来存储租赁以及汽车租赁平台相关数据。系统中主要应用查询（select），修改（update），删除（delete）以及增加（insert）等语句来实现系统功能。

## **2.4 Spring Boot框架**

Spring Boot是Pivotal团队的一个新框架，旨在简化新Spring应用程序的初始设置和开发。该框架使用特定的配置方法，无需开发人员定义样板配置。通过这种方式，Spring Boot旨在成为蓬勃发展的快速应用程序开发领域的领导者。\
Spring Boot特点：\
1、创建一个单独的Spring应用程序；\
2、嵌入式Tomcat，无需部署WAR文件；\
3、简化Maven配置；\
4、自动配置Spring；\
5、提供生产就绪功能，如指标，健康检查和外部配置；\
6、绝对没有代码生成和XML的配置要求；\
安装步骤：\
最基本的是，Spring Boot是一个可以被任何项目的构建系统使用的库集合。 为简单起见，该框架还提供了一个命令行界面，可用于运行和测试Boot应用程序。 可以从Spring存储库手动下载和安装框架的已发布版本，包括集成的CLI（命令行界面）。 更简单的方法是使用Groovy enVironment Manager（GVM），它负责处理Boot版本的安装和管理。 可以从GVM命令行GVM install springboot安装Boot及其CLI。 在OS X上安装Boot时可以使用Homebrew包管理器。要完成安装，首先使用brew tap pivotal / tap切换到pivotal存储库，然后执行brew install springboot命令。

# **第3章 系统分析**

## 3.1 需求分析

中小企业人事管理系统主要是为了提高工作人员的工作效率和更方便快捷的满足员工，更好存储所有数据信息及快速方便的检索功能，对系统的各个模块是通过许多今天的发达系统做出合理的分析来确定考虑员工的可操作性，遵循开发的系统优化的原则，经过全面的调查和研究。

系统所要实现的功能分析，对于现在网络方便的管理，系统要实现员工可以直接在平台上进行查看所有数据信息，根据需求可以进行在线添加，删除或修改中小企业人事管理系统信息，这样既能节省时间，不用再像传统的方式耽误时间，真的很难去满足员工的各种需求。所以中小企业人事管理系统的开发不仅仅是能满足员工的需求，还能提高管理员的工作效率，减少原有不必要的工作量。

## 3.2 系统可行性分析

### 3.2.1技术可行性：技术背景

本企业网站在Windows操作系统中进行开发，并且目前PC机的性能已经可以胜任普通网站的web服务器。系统开发所使用的技术也都是自身所具有的，也是当下广泛应用的技术之一。

系统的开发环境和配置都是可以自行安装的，系统使用springboot框架开发工具，使用比较成熟的Mysql数据库进行对系统后台的数据交互，根据技术语言对数据库，结合需求进行修改维护，可以使得网站运行更具有稳定性和安全性，从而完成实现网站的开发。

（1）硬件可行性分析

系统管理及信息分析的设计对于所使用的计算机没有什么硬性的要求，计算机只要可以正常的使用进行代码的编写及页面设计就可行，主要是对于服务器有些要求，对于平台搭建完成要上传的服务器是有一定的要求的，服务器必须选择安全性比较高的，然后就是在打开网站必须顺畅，不能停顿太长时间；性价比高；安全性高。

（2）软件可行性分析

提供一个共同的机制类似的借口动态模型，设计更集中。此外，代码复用，也可以很好的体现。因此，考虑到系统的实际情况，选择Java作为本系统开发技术。通过上述分析，该系统的设计实现在软件方面是可行的。

因此，我们进行了两个方面的可行性研究，可以看出，该系统的开发是没有问题的。

### 3.2.2经济可行性

在中小企业人事管理系统开发之前所做的市场调研及其他的相关的管理系统，都是没有任何费用的，都是通过开发者自己的努力，所有的工作的都是自己亲力亲为，在碰到自己比较难以解决的问题，大多是通过同学和指导老师的帮助进行相关信息的解决，所以对于中小企业人事管理系统的开发在经济上是完全可行的，没有任何费用支出的。

使用比较成熟的技术，系统是基于Java技术的开发，采用Mysql数据库。所以系统在开发人力、财力要求不高，具有经济可行性。

### 3.2.3操作可行性： 

可操作性主要是对中小企业人事管理系统设计完成后，员工的使用体验度，以及管理员可以通过系统随时管理相关的数据信息，并且对于管理员、员工二个权限角色，都可以简单明了的进入到自己的系统界面，通过界面导航菜单可以简单明了地操作功能模块，方便中小企业人事管理系统的操作需求和管理员管理数据信息，对于系统的操作，不需要专业人员都可以直接进行功能模块的操作管理，所以在系统的可操作性是完全可以的。本系统的操作使用的也是界面窗口进行登录，所以操作人员只要会简单的电脑操作就完全可以的。

## 3.3 项目设计目标与原则

1、关于中小企业人事管理系统的基本要求

（1）功能要求：可以管理首页、个人中心、员工管理、部门信息管理、职位信息管理、福利信息管理、培训信息管理、任务信息管理、工资信息管理、考勤信息管理、招聘信息管理等功能模块。

（2）性能：在不同操作系统上均能无差错实现在不同类型的员工登入相应界面后能不出差错、方便地进行预期操作。

（3）安全与保密要求：员工都必须通过注册、登录才能进入系统，并且员工的权限也需要根据员工的类型进行限定。

（4）环境要求：支持多种平台，可在Windows系列、Vista系统等多种操作系统下使用。

2、开发目标

中小企业人事管理系统的主要开发目标如下：

（1）实现管理系统信息关系的系统化、规范化和自动化；

（2）减少维护人员的工作量以及实现员工对信息的控制和管理。

（3）方便查询信息及管理信息等；

（4）通过网络操作，改善处理问题的效率，提高操作人员利用率；

（5）考虑到员工多样性特点，要求界面简单，操作简便。

3、设计原则

本中小企业人事管理系统采用Java技术，Mysql数据库开发，充分保证了系统稳定性、完整性。

中小企业人事管理系统的设计与实现的设计思想如下：

1.  操作简单方便、系统界面安全良好、简单明了的页面布局、方便查询相关信息。

2、即时可见：对中小企业人事管理系统信息的处理将立马在对应地点可以查询到，从而实现"即时发布、即时见效"的系统功能。

## 3.4系统流程分析

### 3.4.1操作流程

系统登录流程图，如图所示：![](media/image1.wmf)

图3-1登录流程图

### 3.4.2添加信息流程

添加信息流程图，如图所示：

![](media/image2.wmf)

图3-2添加信息流程图

### 3.4.3删除信息流程

删除信息流程图，如图所示：

![](media/image3.wmf)

图3-3删除信息流程图

# **第4章 系统设计**

## 4.1 系统体系结构

中小企业人事管理系统的结构图4-1所示：

管理员

服务器和程序

员工

图4-1 系统结构

登录系统结构图，如图4-2所示：

中小企业人事管理系统登录界面

用户登录

密码正确

管理员界面

员工界面

图4-2 登录结构图

中小企业人事管理系统结构图，如图4-3所示。

![](media/image4.wmf)

图4-3 中小企业人事管理系统结构图

## 4.2开发流程设计

系统流程的分析是通过调查系统所涉及问题的识别、可行性、可操作性、系统分析处理能力等具体环节来调节、整理系统的设计方案以确保系统能达到理想的状态。这些操作都要从注册、登录处着眼进行一系列的流程测试保证数据库的完整，从而把控系统所涉及信息管理的安全、保证信息输入、输出正常转换。然后，通过实际操作完成流程图的绘制工作。

中小企业人事管理系统的开发对管理模块和系统使用的数据库进行分析，编写代码，系统测试，如图4-4所示。

![](media/image5.wmf)

图4-4开发系统流程图

## 4.3 数据库设计原则

学习编程，我们都知道数据库设计是基于需要设计的系统功能，我们需要建立一个数据库关系模型，用于存储数据信息，这样当我们在程序中时，就没有必要为程序页面添加数据，从而提高系统的效率。数据库存储了很多信息，可以说是信息管理系统的核心和基础，数据库还提供了添加、删除、修改和检查，使系统能够快速找到自己想要的信息，而不是在程序代码中找到。数据库中信息表的每个部分根据一定的关系精确地组合，排列和组合成数据表。

通过中小企业人事管理系统的功能进行规划分成几个实体信息，实体信息将通过ER图进行说明，本系统的主要实体图如下：

管理员信息属性图如图4-5所示。

![](media/image6.wmf)

图4-5 管理员信息实体属性图

员工信息实体属性图如图4-6所示。

![](media/image7.wmf)

图4-6员工信息属性图

培训信息实体属性图如图4-7所示。

![](media/image8.wmf)

图4-7培训信息实体属性图

考勤信息实体属性图如图4-8所示。

![](media/image9.wmf)

图4-8考勤信息实体属性图

## 4.4 数据表

将数据库概念设计的E-R图转换为关系数据库。在关系数据库中，数据关系由数据表组成，但是表的结构表现在表的字段上。

表4-1 allusers表

  ------------------- --------------------- ------- ----------------------
         列名               数据类型         长度            约束

          id                   int            11           NOT NULL

       username              varchar          50         default NULL

          pwd                varchar          50         default NULL

          cx                 varchar          50         default NULL
  ------------------- --------------------- ------- ----------------------

表4-2 gongzixinxi表

  ------------------- --------------------- ------- ----------------------
         列名               数据类型         长度            约束

          id                   int            11           NOT NULL

        addtime              varchar          50         default NULL

       mingcheng             varchar          50         default NULL

        gonghao              varchar          50         default NULL

       xingming              varchar          50         default NULL

         bumen               varchar          50         default NULL

        zhiwei               varchar          50         default NULL

      jibengongzi            varchar          50         default NULL

     jiabangongzi            varchar          50         default NULL

         fuli                varchar          50         default NULL

        shebao               varchar          50         default NULL

        koufei               varchar          50         default NULL

      shifagongzi            varchar          50         default NULL

         riqi                varchar          50         default NULL
  ------------------- --------------------- ------- ----------------------

表4-3：kaoqinxinxi表

  ----------------------- ------------ ------------ -----------------------
           列名             数据类型       长度              约束

            id                int           11             NOT NULL

          addtime           varchar         50           default NULL

         mingcheng          varchar         50           default NULL

        kaoqinriqi          varchar         50           default NULL

          gonghao           varchar         50           default NULL

         xingming           varchar         50           default NULL

           bumen            varchar         50           default NULL

          zhiwei            varchar         50           default NULL

     kaoqinzhuangkuang      varchar         50           default NULL

       kaoqinneirong        varchar         50           default NULL
  ----------------------- ------------ ------------ -----------------------

表4-4：peixunxinxi表

  ----------------------- ------------ ------------ -----------------------
           列名             数据类型       长度              约束

            id                int           11             NOT NULL

          addtime           varchar         50           default NULL

       peixunxiangmu        varchar         50           default NULL

          gonghao           varchar         50           default NULL

         xingming           varchar         50           default NULL

           bumen            varchar         50           default NULL

       peixunshijian        varchar         50           default NULL

       peixundidian         varchar         50           default NULL

       peixunneirong        varchar         50           default NULL

         faburiqi           varchar         50           default NULL
  ----------------------- ------------ ------------ -----------------------

表4-5：renwuxinxi表

  ----------------------- ------------ ------------ -----------------------
           列名             数据类型       长度              约束

            id                int           11             NOT NULL

          addtime           varchar         50           default NULL

          biaoti            varchar         50           default NULL

          gonghao           varchar         50           default NULL

         xingming           varchar         50           default NULL

           bumen            varchar         50           default NULL

        renwuyaoqiu         varchar         50           default NULL

       renwuneirong         varchar         50           default NULL

         faburiqi           varchar         50           default NULL
  ----------------------- ------------ ------------ -----------------------

# **第5章 系统详细设计**

## 5.1管理员功能模块

管理员登录，通过登录页面填写用户名、密码、角色进行登录，如图5-1所示。

![](media/image10.png){width="5.897222222222222in"
height="2.5840277777777776in"}

图5-1管理员登录界面图

管理员登录进入中小企业人事管理系统可以查看首页、个人中心、员工管理、部门信息管理、职位信息管理、福利信息管理、培训信息管理、任务信息管理、工资信息管理、考勤信息管理、招聘信息管理等信息。

员工管理，在员工管理页面中可以通过查看工号、姓名、性别、头像、部门、职位、电话等信息进行详情、修改，如图5-2所示。还可以根据需要对部门信息管理进行详情，修改或删除等详细操作，如图5-3所示。

![](media/image11.png){width="5.896527777777778in"
height="2.798611111111111in"}

图5-2员工管理界面图

![](media/image12.png){width="5.895833333333333in"
height="2.7152777777777777in"}

图5-3部门信息管理界面图

职位信息管理，在职位信息管理页面中可以查看职位等信息，并可根据需要对职位信息管理进行修改或删除等操作，如图5-4所示。

![](media/image13.png){width="5.9in" height="2.776388888888889in"}

图5-4职位信息管理界面图

福利信息管理，在福利信息管理页面中可以查看名称、发布日期等信息，并可根据需要对福利信息管理进行详情、修改或删除等详细操作，如图5-5所示。

![](media/image14.png){width="5.905555555555556in"
height="2.776388888888889in"}

图5-5福利信息管理界面图

培训信息管理，在培训信息管理页面中可以查看培训项目、工号、姓名、部门、培训时间、培训地点、发布日期等信息，并可根据需要对培训信息管理进行详情、修改或删除等详细操作，如图5-6所示。

![](media/image15.png){width="5.895833333333333in" height="2.725in"}

图5-6培训信息管理界面图

任务信息管理，在任务信息管理页面中可以查看标题、工号、姓名、部门、发布日期等信息，并可根据需要对任务信息管理进行详情、修改或删除等详细操作，如图5-7所示。

![](media/image16.png){width="5.905555555555556in"
height="2.786111111111111in"}

图5-7任务信息管理界面图

工资信息管理，在工资信息管理页面中可以查看名称、工号、姓名、部门、职位、基本工资、加班工资、福利、社保、扣费、实发工资、日期等信息，并可根据需要对工资信息管理进行详情、修改或删除等详细操作，如图5-8所示。

![](media/image17.png){width="5.895138888888889in"
height="2.533333333333333in"}

图5-8工资信息管理界面图

考勤信息管理，在考勤信息管理页面中可以查看名称、考勤日期、工号、姓名、部门、职位、考勤状况等信息，并可根据需要对考勤信息管理进行详情、修改或删除等详细操作，如图5-9所示。

![](media/image18.png){width="5.905555555555556in"
height="2.795138888888889in"}

图5-9考勤信息管理界面图

## 5.2员工功能模块

员工登录进入中小企业人事管理系统可以查看首页、个人中心、部门信息管理、福利信息管理、培训信息管理、任务信息管理、工资信息管理、考勤信息管理等内容。

个人信息，在个人信息页面中通过查看工号、姓名、性别、头像、部门、职位、电话等信息还可以根据需要对个人信息进行查看修改，如图5-10所示。

![](media/image19.png){width="5.904166666666667in"
height="2.6840277777777777in"}

图5-10个人信息界面图

福利信息管理，在福利信息管理页面中可以查看名称、发布日期等信息内容，并且根据需要对福利信息管理进行查看详情操作，如图5-11所示。

![](media/image20.png){width="5.904166666666667in"
height="2.7534722222222223in"}

图5-11福利信息管理界面图

培训信息管理，在培训信息管理页面中可以查看培训项目、工号、姓名、部门、培训时间、培训地点、发布日期等信息内容，并且根据需要对培训信息管理进行查看详情操作，如图5-12所示。

![](media/image21.png){width="5.898611111111111in"
height="2.6083333333333334in"}

图5-12培训信息管理界面图

任务信息管理，在任务信息管理页面中可以查看标题、工号、姓名、部门、发布日期等信息内容，并且根据需要对任务信息管理进行查看详情操作，如图5-13所示。

![](media/image22.png){width="5.9in" height="2.6395833333333334in"}

图5-13任务信息管理界面图

工资信息管理，在工资信息管理页面中可以查看名称、工号、姓名、部门、职位、基本工资、加班工资、福利、社保、扣费、实发工资、日期等信息内容，并且根据需要对工资信息管理进行查看详情操作，如图5-14所示。

![](media/image23.png){width="5.898611111111111in"
height="2.7958333333333334in"}

图5-14工资信息管理界面图

考勤信息管理，在考勤信息管理页面中可以查看名称、考勤日期、工号、姓名、部门、职位、考勤状况等信息内容，并且根据需要对考勤信息管理进行查看详情操作，如图5-15所示。

![](media/image24.png){width="5.902777777777778in"
height="2.8333333333333335in"}

图5-15考勤信息管理界面图

# **第6章 系统测试**

## 6.1系统测试的目的

程序设计不能保证没有错误，这是一个开发过程，在错误或错误的过程中都是难以避免的。虽然这是不可避免的，但我们不能使这些错误始终存在于系统中，错误可能会造成无法估量的后果，如系统崩溃，安全信息泄露，系统无法正常启动等，为了避免这些问题，我们需要测试程序，再测试过程中发现问题，并纠正它们，从而使系统更长时间稳定成熟。本章的作用是发现这些问题，并对其进行修改，虽然耗时费力，但对于长期使用而言是非常重要和必要系统的开发。

软件在设计后必须进行测试，调试过程中使用的方法是软件测试方法。在开发新软件时，系统测试是检查软件是否合格的关键步骤，以及是否符合设计目标的参考。测试主要是查看软件中数据的准确性，正确的操作与否，以及操作的结果，还有哪些方面需要改进。

中小企业人事管理系统的实现，对于系统中功能模块的实现及操作都必须通过测试进行来评判系统是否可以准确的实现。在中小企业人事管理系统正式上传使用之前必须做的一步就是系统测试，对于测试发现的错误及时修改处理，保证系统准确无误的供给员工使用。

## 6.2系统测试方法

在对中小企业人事管理系统进行测试的时候在找到问题的情况下必须在第一时间找到解决问题的办法，不要存在侥幸的心理，这样才能让中小企业人事管理系统开发的质量可以过关，并且开发的周期会大大缩短，还有就是在测试时，不要出现重复性的错误，遇到一个错误问题，要将整个中小企业人事管理系统开发所牵扯的该问题都必须一一解决，提高中小企业人事管理系统平台的安全性、稳定性。

白盒测试与黑盒测试是测试中比较常用的两种方法。

①结构测试俗称白盒测试：这种测试是在对程序的处理过程与结构都有详尽谅解的前提下，顺从程序内部的逻辑而完成的系统测试，以确定系统中所有的通路都能够遵照设计要求正常工作，不出现任何偏差。

②功能测试又成黑盒测试：主要是针对程序功能能够按照设计正常实现的一种检测，在程序接口处进行，检测程序手法数据是否正常，与外部信息的交换是否完整。

## 6.3功能测试

> 员工登录测试：

+:-----------:+-------------+-------------+-------------+-------------+
| 模块名称    | 测试用例    | 预期结果    | 实际结果    | 是否通过    |
+-------------+-------------+-------------+-------------+-------------+
| 登录模块    | 用户名：001 | 弹出错      | 弹出错      | 通过        |
|             | 密码：123   | 误提示，提  | 误提示，提  |             |
|             |             | 示密码错误  | 示密码错误  |             |
+-------------+-------------+-------------+-------------+-------------+
| 登录模块    | 用户名：123 | 弹出错误    | 弹出错误    | 通过        |
|             |             | 提示，提示  | 提示，提示  |             |
|             | 密码：001   | 用户名错误  | 用户名错误  |             |
+-------------+-------------+-------------+-------------+-------------+
| 登录模块    | 用户名：001 | 管理        | 管理        | 通过        |
|             |             | 员登录成功  | 员登录成功  |             |
|             | 密码：001   |             |             |             |
+-------------+-------------+-------------+-------------+-------------+

> 删除分类测试：

  -------------- ------------------ ------------------------ ------------------------ --------------
     模块名称    测试用例           预期结果                 实际结果                 是否通过

   删除分类模块  分类名：最新通知   删除成功、页面自动跳转   删除成功、页面自动跳转   通过
  -------------- ------------------ ------------------------ ------------------------ --------------

> 修改密码测试：

+-------------+-------------+-------------+-------------+-------------+
| 模块名称    | 测试用例    | 预期结果    | 实际结果    | 是否通过    |
+-------------+-------------+-------------+-------------+-------------+
| 修          | 原密码：666 | 弹出错误    | 弹出错误    | 通过        |
| 改密码模块  |             | 提示，提示  | 提示，提示  |             |
|             | 新密码：123 | 原密码错误  | 原密码错误  |             |
|             |             |             |             |             |
|             | 确          |             |             |             |
|             | 认密码：123 |             |             |             |
+-------------+-------------+-------------+-------------+-------------+
| 修          | 原密码：002 | 弹          | 弹          | 通过        |
| 改密码模块  | 新密码：123 | 出错误提示  | 出错误提示  |             |
|             |             | ，提示确认  | ，提示确认  |             |
|             | 确          | 密码不一致  | 密码不一致  |             |
|             | 认密码：333 |             |             |             |
+-------------+-------------+-------------+-------------+-------------+
| 修          | 原密码：002 | 密          | 密          | 通过        |
| 改密码模块  | 新密码：123 | 码修改成功  | 码修改成功  |             |
|             |             |             |             |             |
|             | 确          |             |             |             |
|             | 认密码：123 |             |             |             |
+-------------+-------------+-------------+-------------+-------------+

通过对功能的测试，中小企业人事管理系统的基本功能都是可行的，不管是系统里面的功能，还是界面的设计都是可值得推广宣传的。

[]{#__RefHeading___Toc1953 .anchor}结 论

此时项目已经完成，即使实施的时间不是很长，但是这个过程中需要准备很长的一段时间去对系统设计开发所实际到的技术进行学习。在学习的过程中，我逐渐认识得到了我自身存在的一些不足。对于一些控制是必要的应用技能，能够理解，整个过程中仅仅是一个掌握了常用的性能和控制方法，我觉得挺容易的。从该系统中，系统的分析和设计的调查数据，并且已经经历了几个月，并努力几个月，该系统已经完成。很显然，该系统仍有很多不成熟，在系统设计过程中有许多技术缺陷存在。在设计的过程中也涉及到了很多自己无法解决的问题，主要通过找专业的网站和论坛来解决这些问题，对于圆满完成我的毕业设计，他们也贡献了很大一部分力量。系统的开发环境和配置都是可以自行安装的，使用比较成熟的Mysql数据库进行对系统后台的数据交互，根据技术语言对数据库，结合需求进行修改维护，可以使得系统运行更具有稳定性和安全性，从而完成实现系统的开发。

回顾毕业设计的整个过程，既付出汗水也收获了很多。虽然经历了各种各样的困难，自己的不断研究探索，系统的实现仍有不足之处。

在以后的学习及工作中，我仍然继续学习计算机方面的技术，让我在后期的平台开发中可以更好更快的实现需求功能。

[]{#__RefHeading___Toc1495 .anchor}致 谢

中小企业人事管理系统的完成，如何实现的更好，其中付出的努力是很大的，这段时光将会终身难忘。

首先要感谢我的指导老师，谢谢您在设计和论文中给我的指导。在您的细心指导下我才能快速的掌握系统的相关功能，在您的大力帮助下我才能将课本上的知识与自己的项目结合，真正的做到学以致用。感谢您经常牺牲自己的休息时间，利用其丰富的教学和项目经验对我进行指导。

感谢所有教过我的老师，为我倾注了大量的心血，正是你们的谆谆教诲、严谨教学才使我能顺利的完成学业，再此向你们表示深深的感谢。

感谢我的同学们，对我的大力支持及帮助，正是你们不断的帮助、鼓励，给我带来了极大的动力，最终系统可以顺利的运行。我们在交流、谈论的这段时间,将是我未来的财富，我要深深地感谢你们!

毕业在即，在今后的工作和生活中，我会铭记师长们的教诲、同学们的帮助，继续不懈努力和追求，来报答所有支持和帮助过我的人!。

# 参考文献

1.  范立峰，乔世全，程文彬 springboot框架程序设计 人民邮电大学出版社
    2019。

2.  西尔伯沙茨(Silberschatz.A.) .
    计算机科学丛书：数据库系统概念(原书第6版)\[M\].
    机械工业出版社,2018,03．。

3.  陈雄华 企业应用开发详解 电子大学出版社，2017。

4.  李宁springboot框架
    Web开发技术大全\--springboot框架+Servlet清华大学出版社，2018。

5.  聂哲 springboot框架动态WEB技术实例教程。

6.  李绪成，闫海珍 springboot框架
    Web开发教程---入门与提高篇(springboot框架+Servlet) 清华大学出版社
    2017。

7.  史胜辉，王春明，沈学华 springboot框架EE基础教程 清华大学出版社 2019
    。

8.  \[8\] Symfon,Cakespringboot框架,Zend Bartosz Porebski,Karol
    Przystalski,Leszek Nowak, 付勇. springboot框架高级编程:应用\[M\].
    清华大学出版社,2017,02.

9.  \[9\] 波诺赛克 (Boroncxyk.T.),Elizabeth Naramore,薛焱.
    Web开发入门经典:使用springboot框架6、Apache和MySQL\[M\].
    清华大学出版社 ,2019,06

10. Robert
    W.Sebesta著，刘伟琴等译．Web程序设计\[M\]．(第4版)．北京：清华大学出版社，2018：9-450．

11. 赵强
    编著．精通springboot框架编程\[M\]．北京：电子工业出版社,2019：34-56．

12. 萨师煊，王珊．数据库系统概论\[M\]．北京:高等教育出版社，2018：10-180．

13. 陈刚．Eclipse从入门到精通\[M\]．(第2版)．北京:清华大学出版社，2017：17-380．

14. 孙卫琴．精通Struts:基于MVC的springboot框架
    Web设计与开发\[M\]．北京:电子工业出版社，2018：19-421．


### 0127springboot中小企业人事管理系统代码 项目图片









