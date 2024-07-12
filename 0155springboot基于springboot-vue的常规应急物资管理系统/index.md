# 0155springboot基于SpringBoot+Vue的常规应急物资管理系统


# [0155springboot基于SpringBoot+Vue的常规应急物资管理系统](https://github.com/GraduationProject-springboot/0155springboot)

### 微信： chen_q123456  qq:462201886
### github:chenqi199

### [所有项目](https://github.com/GraduationProject-springboot/allSpringbootProjects) 包安装运行

### [所有项目列表excel 腾讯文档 项目清单](https://docs.qq.com/sheet/DSHRFSVZ5aEVYT3N3?tab=BB08J2) 包安装运行

### [github](https://chenqi199.github.io)








# 0155springboot基于SpringBoot+Vue的常规应急物资管理系统

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://player.bilibili.com/player.html?isOutside=true&aid=BV1jqaLe1ECs&bvid=BV1jqaLe1ECs&cid=500001610829318&p=54)

### [所有项目](https://github.com/GraduationProject-springboot/allSpringbootProjects) 包安装运行












**基于SpringBoot+Vue的常规应急物资管理系统的设计与实现**

**学 院 名 称**

**专 业 班 级**

**学 生 姓 名**

**学 号**

**导 师 姓 名**

**专业技术职务**

**目 录**

[摘 要 [1](#摘-要)](#摘-要)

[ABSTRACT [2](#abstract)](#abstract)

[第一章 绪论 [3](#第一章-绪论)](#第一章-绪论)

[1.1研究背景 [3](#研究背景)](#研究背景)

[1.2研究意义 [3](#研究意义)](#研究意义)

[1.3国内外研究现状 [4](#国内外研究现状)](#国内外研究现状)

[1.3.1国外研究现状 [4](#国外研究现状)](#国外研究现状)

[1.3.2国内研究现状 [4](#国内研究现状)](#国内研究现状)

[1.4研究内容与方法 [5](#研究内容与方法)](#研究内容与方法)

[1.4.1研究内容 [5](#研究内容)](#研究内容)

[1.4.2研究方法 [5](#研究方法)](#研究方法)

[1.5论文的组织结构 [5](#论文的组织结构)](#论文的组织结构)

[第二章 开发技术介绍 [7](#第二章-开发技术介绍)](#第二章-开发技术介绍)

[2.1 B/S架构 [7](#bs架构)](#bs架构)

[2.2 Java语言 [7](#java语言)](#java语言)

[2.3 SSM框架 [7](#ssm框架)](#ssm框架)

[2.4 vue框架 [8](#vue框架)](#vue框架)

[2.5 MySQL数据库 [8](#mysql数据库)](#mysql数据库)

[第三章 系统分析 [10](#第三章-系统分析)](#第三章-系统分析)

[3.1系统的需求分析 [10](#系统的需求分析)](#系统的需求分析)

[3.2系统的可行性分析 [10](#系统的可行性分析)](#系统的可行性分析)

[3.2.1经济可行性 [10](#经济可行性)](#经济可行性)

[3.2.2技术可行性 [10](#技术可行性)](#技术可行性)

[3.2.3操作可行性 [11](#操作可行性)](#操作可行性)

[第四章 系统设计 [12](#第四章-系统设计)](#第四章-系统设计)

[4.1系统的总体功能设计 [12](#系统的总体功能设计)](#系统的总体功能设计)

[4.2数据库设计 [13](#数据库设计)](#数据库设计)

[4.2.1概念设计 [13](#概念设计)](#概念设计)

[4.2.2逻辑设计 [16](#逻辑设计)](#逻辑设计)

[第五章 系统实现 [19](#第五章-系统实现)](#第五章-系统实现)

[5.1管理员角色功能设计 [19](#管理员角色功能设计)](#管理员角色功能设计)

[5.1.1管理员首页 [19](#管理员首页)](#管理员首页)

[5.1.2个人中心 [20](#个人中心)](#个人中心)

[5.1.3健康打卡管理 [21](#健康打卡管理)](#健康打卡管理)

[5.1.4基础数据管理 [22](#基础数据管理)](#基础数据管理)

[5.1.5物资管理 [23](#物资管理)](#物资管理)

[5.1.6物资申请管理 [25](#物资申请管理)](#物资申请管理)

[5.1.7物资运输管理 [26](#物资运输管理)](#物资运输管理)

[5.1.8用户管理 [27](#用户管理)](#用户管理)

[5.1.9部门管理 [29](#部门管理)](#部门管理)

[5.2用户功能设计 [30](#用户功能设计)](#用户功能设计)

[5.2.1用户首页 [30](#用户首页)](#用户首页)

[5.2.2个人中心 [31](#个人中心-1)](#个人中心-1)

[5.2.3健康打卡管理 [33](#健康打卡管理-1)](#健康打卡管理-1)

[5.2.4物资管理 [34](#物资管理-1)](#物资管理-1)

[5.2.5物资申请管理 [35](#物资申请管理-1)](#物资申请管理-1)

[5.2.6物资运输管理 [36](#物资运输管理-1)](#物资运输管理-1)

[第六章 系统测试 [38](#第六章-系统测试)](#第六章-系统测试)

[6.1 测试概述 [38](#测试概述)](#测试概述)

[6.2 测试结果 [38](#测试结果)](#测试结果)

[结 论 [41](#结-论)](#结-论)

[参考文献 [42](#参考文献)](#参考文献)

[致 谢 [44](#致-谢)](#致-谢)

# 

# 摘 要

当下，正处于信息化的时代，许多行业顺应时代的变化，结合使用计算机技术向数字化、信息化建设迈进。以前相关行业对于常规应急物资信息的管理和控制，采用人工登记的方式保存相关数据，这种以人力为主的管理模式已然落后。本人结合使用主流的程序开发技术，设计了一款基于SpringBoot+Vue的常规应急物资管理系统，可以较大地减少人力、财力的损耗，方便相关人员及时更新和保存信息。本常规应急物资管理系统是建立在B/S模式的基础之上，通过使用idea平台上编写相关的Java代码，实现对系统的功能模块的设计，使用MySQL数据库设计相关的数据表，实现对系统数据资源的管理和控制，使用SSM框架创建相关的项目主流架构，实现系统的基本框架搭建，最后再通过使用Tomcat浏览器将所研发的系统发布到网上，便于相关的用户运行和使用本系统。本文对系统进行实现的可行性分析，设计的功能及数据库规划，以及设计的主要功能模块测试等内容做了较为详细的介绍，并且在本文中也展示了系统主要的功能模块设计界面和操作界面，并对其做出了必要的解释说明，方便用户对系统进行操作和使用，以及后期的相关人员对系统进行更新和维护。本系统的实现可以极大地提高相关行业的工作效率，提升用户的使用体验，因此在现实生活中运用本系统具有很大的使用价值。

**关键词：**常规应急物资管理 Java语言 B/S架构 MySQL数据库

# **ABSTRACT**

At present, we are in the era of informationization. Many industries
conform to the changes of the times and use computer technology to move
towards digitalization and informationization. In the past, related
industries used manual registration to save relevant data for the
management and control of conventional emergency material information.
This manpower-based management model has fallen behind. Combining the
use of mainstream program development technology, I designed a
conventional emergency material management system based on
SpringBoot+Vue, which can greatly reduce the loss of human and financial
resources and facilitate relevant personnel to update and save
information in a timely manner. This conventional emergency material
management system is based on the B/S model. By using the idea platform
to write the relevant Java code, the design of the function modules of
the system is realized, and the MySQL database is used to design the
relevant data tables to realize the system control. For the management
and control of data resources, the SSM framework is used to create the
relevant project mainstream architecture, and the basic framework of the
system is realized. Finally, the developed system is published on the
Internet by using the Tomcat browser, which is convenient for the
relevant users to run and use the system. In this paper, the feasibility
analysis of the system implementation, the design function and database
planning, as well as the main function module testing of the design are
introduced in detail, and the main function module design interface and
operation interface of the system are also shown in this paper. , and
make necessary explanations for it, which is convenient for users to
operate and use the system, and the relevant personnel to update and
maintain the system later. The implementation of this system can greatly
improve the work efficiency of related industries and enhance the user
experience, so the application of this system in real life has great use
value.

**Key words:** Conventional emergency material management; Java
language; B/S architecture; MySQL database

# **第一章 绪论**

## 1.1研究背景

近年来，第三产业发展非常迅速，诸如计算机服务、旅游、娱乐、体育等服务行业，对整个社会的经济建设起到了极大地促进作用，这一点是毋庸置疑的。现下，国家也出台了一系列的政策来支持和鼓励第三服务产业的发展与完善，用以带动社会经济的发展^\[1\]^。所以，整体来说，国家是比较提倡发展第三方服务行业的。纵观计算机领域的整个发展历程，从计算机的诞生到现在，已经有几百年的历史了，计算机应用技术也逐步趋于成熟，并且相关的设计人员也在不断地对其进行改进和完善。再到如今，计算机已经发展成为一个比较热门的行业了。在高校中，计算机、人工智能等专业热度非常高，许多学生在选择专业的时候，大都优先考虑计算机专业。在社会上，计算机类行业也成为了比较受欢迎的行业，从在浏览器中访问的网址，到手机上的各种应用程序，再到大型的软件服务设备，基本上都离不开计算机技术支持，以及硬件的支撑。

如今，互联网几乎遍布于世界的各个角落，人工智能、大数据占据越来越重要的地位，比如疫情期间，通过大数据技术进行筛查，确定哪些人员无接触史，哪些人员需要重点观察，由此可以在极短的时间内，以最快的速度对疫情进行防控。在这个大背景环境的推动下，本人通过学习Java语言、MySQL数据库、SSM框架等相关的计算机技术，打好坚实的技术基础，方便后期对系统进行研发。而后再通过对系统进行分析，确定系统的总体功能需求，以及实现的可能性，方便接下来详细地设计相关的功能模块，最后成功的研发了一款基于SpringBoot+Vue的常规应急物资管理系统。本系统改善了传统的管理模式，将原先的手工记录和管理信息，改进为使用计算机存储和管理信息记录，极大地方便了工作人员对相关数据进行处理，为相关行业节约了不少的员工费用和管理开销，并且能够在较短的时间内响应用户的需求，这种便捷的操作，对于用户来说可以节省不少时间和精力，也省去了不少的麻烦，极大地方便了用户。

## 1.2研究意义

传统的信息管理模式，主要是以人力为主进行管理和控制，由工作人员负责登记用户信息，再通过对照之前的信息记录，确定是否给用户提供相关的使用需求，以及如何提供能让用户满意的使用需求。这种管理模式已经适应不了时代的变化了，正在不断地走下坡路，并且逐步被信息化管理模式所取代。所谓的信息化管理模式，是现在主流的一种管理模式，其通过与计算机技术相结合的方式，对行业的整个工作模式和服务流程进行改进和完善。其主要通过使用计算机等设备，将工作服务流程电子化，并且进行存储记录，用以提高行业整体的服务水平。结合计算机技术，本人研发出一款基于SpringBoot+Vue的常规应急物资管理系统，采用电子化的方式对数据信息进行存储，便于工作人员对相关信息进行记录和管理，有利于提高相关行业的工作运营效率以及工作人员的管理速度，以此更好的满足用户的相关需求，最终达到提升用户的使用感受的目的，由此可见设计和实现本系统具有重要的意义和价值。

## 1.3国内外研究现状

### 1.3.1国外研究现状

美国是最先发展计算机技术的众多国家之一，早在上个世纪，美国的计算机技术就快速地发展起来，并且运用在军事、医院、学校、社会服务等场所。日本、德国等国家紧随其后，不断地发展和完善计算机技术，侧重将医疗、社会服务等领域与计算机技术相结合^\[2\]^。而后随着社会的发展与进步，计算机技术逐渐趋于成熟。许多发达国家在探索将计算机技术应用于各行各业中时，从另一个角度来看，也在不断地推进相关行业的信息化管理进程，使得相关行业管理也变得更加网络化、信息化。有许多专家表示，可以结合使用图像处理软件、人工智能技术等相关工具，深度地分析常规应急物资管理系统，主要从简化运行操作，加设功能模块，美化系统界面，保障数据安全等方面，更深层次地提升和优化系统，并且尽可能地在理想状态下做到实时的信息共享。

### 1.3.2国内研究现状

国内的计算机技术的发展虽然晚于国外，尤其是美国、英国、德国等发达国家。但是我国的计算机技术发展势头非常迅猛，近些年，也逐渐走向成熟和完善的阶段。现在，选择网上购物已经成为人们日常生活的一种常态趋势，当然这也离不开对于天猫、支付宝、微信等应用软件的使用^\[3\]^。许多企业结合使用了云计算、人工智能等先进的计算机技术，自主研发了行业相关的信息管理系统，计算机技术逐渐趋于成熟，使用设计的功能逐渐趋于完备。结合计算机技术，采用主流的B/S开发结构模式开发一款基于SpringBoot+Vue的常规应急物资管理系统。由此，本系统能够支持工作人员随时随地的通过使用浏览器进行访问操作，支持随时随地对相关的常规应急物资信息进行管理，便于及时为用户提供一定的功能服务。并且所设计的系统基本上能够符合用户的客观使用需求，有利于充分协调相关行业的人力、财力、物力等资源，不断提高相关工作人员的管理质量和水平^\[4\]^。

## 1.4研究内容与方法

### 1.4.1研究内容

本文首先介绍了常规应急物资管理系统的研究背景与意义，其次介绍了系统的总体功能设计，接着将对系统规划好的总体功能拆分成了各个功能子模块，然后详细地对每一个小的功能子模块进行设计，最后介绍了展示设计好的功能模块以及测试结果。系统主要分为管理员角色和用户角色，具体的功能设计包括注册登录管理、用户信息管理、物资信息管理、物资运输管理等模块。注册登录管理功能是新用户在使用系统前，需要通过注册步骤，登记详细的信息资料，而后再通过输入正确的账号和密码，成功登录系统后，即可通过一系列的操作来满足自己的相关需求。用户信息管理功能是管理相关的用户信息资料，管理人员根据现实情况的需要，选择性的对用户信息记录进行更新处理。物资信息管理是管理相关的物资信息记录，保存详情的物资信息情况，方便及时响应用户的服务请求。物资运输管理是管理相关的物资运输信息记录，方便相关人员及时查看物资运输信息，如果遇到异常的物资运输信息，可以及时对其进行处理，在较短的时间内解决问题，提高用户的使用体验。

### 1.4.2研究方法

本系统以B/S架构进行实现，通过使用idea工具编写相关的java代码，设计系统功能模块，再通过MySQL数据库管控数据资源，由此有利于对系统相关数据进行必要的管理和控制。系统设计的最关键的环节，则是需要通过SSM框架设计系统功能架构，再通过Tomcat服务器将系统发布到浏览器上，以便相关用户的操作和使用。本系统的设计和实现促进了相关行业的信息化建设，有利于简化相关人员工作流程，提高工作效率，提升工作幸福感。

## 1.5论文的组织结构

基于SpringBoot+Vue的常规应急物资管理系统的设计与实现的论文组织结构，大致可以分为七个章节，具体的内容如下：

第一章为绪论，本章主要介绍了系统的背景、现状、方法等内容。根据研究背景与意义，介绍所要设计的系统的研究背景和理论依据，再通过国内外研究现状，了解当前相关的系统软件产品的实际研究情况，最后通过研究内容与方法，总体概括系统的整个开发流程和实现步骤，为系统提供可靠的理论依据和技术支持。

第二章为相关技术介绍，本章主要介绍了开发所使用的相关技术。本系统主要使用的开发技术包括Java语言、SSM框架、MySQL数据库等，并且所使用的开发模式为B/S架构。其中，Java语言具有跨平台性，可移植性高，可以支持在不同的浏览器上运行本系统，MySQL数据库占用内存少，执行速度快，对于中小型系统的数据管理是非常好的选择。

第三章为系统分析，系统分析阶段主要是对系统进行需求和可行性分析，规划系统的功能设计，判断系统实现的可能性。根据需求分析，确认使用者对系统的基本功能需求，再通过在经济、操作、法律上进行可行性分析，分析系统研发的实际意义和使用价值，系统性能的稳定性和功能操作的便捷性，以及成功投入市场的可能性。

第四章为系统设计，本章主要介绍了系统的总体功能设计、数据库设计等内容。通过介绍系统的总体功能设计，规划设计出系统实际需要设计的功能模块，便于相关的技术人员后期设计系统的功能模块做好准备工作。再通过介绍数据库设计，便于设计出数据库能够存放和管控的数据表，有利于相关的设计人员管理必要的数据资源，维护和更新数据信息的安全。

第五章为系统实现，系统实现阶段主要是对物资信息管理、物资运输管理等功能模块进行阐述。通过前面介绍的系统分析，功能及数据库设计等相关内容，详细地实现系统功能模块。这一过程就是系统的具体实现阶段，站在系统的整体设计角度出发，对系统的实现进行必要分析可知，这一阶段是极为重要，直接关系到用户对系统的使用感受。

第六章为系统测试，本章主要是对测试相关的内容进行叙述。本系统主要使用功能测试的方法，检查测验系统主要功能，测试所设计的系统功能能否正常使用，并且用户能够正常操作和使用，在系统运行过程中是否发生异常，如运行异常、数据异常、结果异常等，并且根据测试结果，给出相应的测试总结，由此得出相关结论，说明系统是否达到预期要求、设计目的。

# **第二章 开发技术介绍**

## 2.1 B/S架构

就软件开发的现状而言，目前主要使用的系统开发结构模式大致可以分为C/S模式和B/S模式^\[5\]^。用户在使用基于C/S模式开发的系统时，必须下载相应的客户端，即应用程序，才能操作和使用软件系统的相关功能模块。从使用者的角度来看，由于下载和安装客户端的步骤比较繁琐，期间还需要确保下载网速的稳定性，以及安装步骤的正确性，进而增加了用户放弃使用该系统的可能性，由此可见C/S模式具有很大的局限性。

由于C/S模式适用于小范围的局域网，并且具有较好的通信效率，所以在以前系统规模很小的时代，主要使用C/S模式开发系统。随着时代的发展以及社会的进步，C/S模式也越来越满足不了开发者的设计需要，以及使用者的使用需求。当下，C/S模式已经满足不了实际的系统程序设计要求，由此，B/S模式以C/S模式为基础而被提出，并且在近些年逐渐发展成为主流的开发结构模式。在B/S模式下开发的系统，不再需要用户下载和安装相应的应用程序，直接通过使用浏览器，输入正确的网站地址，以访问网站的形式实现系统的相关功能操作。这一特点对C/S模式下的开发设计做出了极大的改进，当然，使用本系统的前提是确保账号和密码是合法的。

## 2.2 Java语言

Java语言是一种将数据和操作方法封装成对象整体的程序设计语言，它拥有着优秀的技术体系结构。目前在市场上，很大一部分的应用系统主要使用Java语言进行开发^\[6\]^。Java语言具有简单易懂，操作方便，健壮性强等优点，开发人员能够在短时间内理解和掌握Java语言，并将其运用到具体的系统开发过程中。针对于系统内存管理问题，Java语言为解决这类问题，内部提供了垃圾回收机制。为了极大地简化了开发编程的难易程度，Java语言还将C语言中的指针，改进成了引用，所以受到了很多开发人员的喜爱。Java语言还具有跨平台性的特点，意味着它的可移植性非常高，这一特点有利于开发人员更新和维护相关代码，由它所开发的系统可以支持在不同的浏览器中打开。因为使用Java开发的系统兼容性较强，代码通用性较高，为了后期方便对系统进行完善和维护，所以本人最终选择使用Java语言开发本系统。

## 2.3 SSM框架

SSM框架主要由Spring、SpringMVC、MyBatis这三个框架所集成的，是现在比较流行的一种Java开发框架，能够适用于大中型的应用程序的设计和搭建。Spring是前几十年前兴起的一种轻量级的、开源的Java开发框架，使用它可以解决相关的系统对象创建和对象依赖问题，并且也可以将高耦合的系统分解为低耦合的多个功能模块，方便对系统模块进行明确的分工，对功能代码进行理解和修改，这就极大地减轻了设计人员的开发压力^\[7\]^。SpringMVC框架是基于Spring框架而被提出的，它以MVC三层架构为核心，对Spring的相关技术进行了整合，主要针对于Web端进行技术架构，通过对相关请求消息进行细化处理，对相关的用户请求做出一定的响应处理。MyBatis框架是一种开源的Java持久层框架，它主要是通过改进手动设置参数和获取结果记录的方式，通过支持对数据库进行存储过程、高级映射等处理，使得数据库的操作更加定制化、透明化，因此降低了数据库访问的复杂性，提高了开发的工作效率。

## 2.4 vue框架

vue框架是一种用于构建相关的用户使用界面的渐进式框架，由此便可以控制某个系统页面的标签，或者控制整个页面的不同标签，又或者控制整个前端项目的不同标签^\[8\]^。使用vue框架编写的代码，不再需要手动更新相关的控件的变量值，当与其绑定的变量值发生改变时，相关的组件会自动地进行更新。vue框架主要通过自底向上的方式对系统的用户界面进行设计和创建，而且vue框架只关注图层内容，如此一来，其不仅能够为各种支持的类库的比较复杂繁琐的单页提供相应的驱动，还能够整合第三方库或者相关的项目。因为vue框架的语法定义简单，比较容易学习和掌握，所以相关的开发技术人员大多选择使用vue框架编写相关的前端页面显示代码，创建相应的系统网站页面。这样的页面设计便于用户查询相关的数据信息，理解系统的操作和使用。

## 2.5 MySQL数据库

MySQL数据库是一种使用频繁的关系型数据库。因为其具有开源免费、占用内存少、安装简单、操作便捷、使用灵活等优点，所以经常被运用于中小型的系统开发中^\[9\]^。MySQL数据库可以支持多线程，在同一个时间内，能够同时响应多个用户的使用需求。MySQL数据库还自带了优化器，方便设计人员在
使用过程中，快速的查询相关的数据信息。除此之外，SQLServer数据库在当下也是使用比较频繁的，它在数据安全、系统稳定等方面还是比较不错的，但是由于其收费使用、占用内存大、操作复杂、维护成本高，
一般适用于中型及以上的系统开发中。MySQL数据库也有着许多的应用程序接口，以供相关的编程语言使用，编写的代码具有极高的通用性和可维护性，并且MySQL数据库能够迅速的处理上千条数据记录，在系统发生故障时，能通过日志文件快速恢复。MySQL数据库与SQLServer数据库相比较，综合考虑成本开销、占用内存大小、代码通用、数据维护、操作难易程度等方面，MySQL数据库占有很大的优势，在数据库设计人员的眼中，MySQL数据库的实际运用价值极高。

# **第三章 系统分析**

## 3.1系统的需求分析

需求分析阶段是设计系统功能模块的总方向，可以这样来说，系统的整个的开发流程以及设计进度，基本上都是以需求分析为基本依据的^\[10\]^。需求分析阶段可以确定系统的基本功能设计，以及在最后的系统验收阶段，再通过对需求分析报告进行对比，验证系统的功能设计是否合理，能否满足用户的基本需要，最终判断总结系统是否成功现实。本文主要通过问卷调查的方式，来分析常规应急物资管理系统所需要的相关功能^\[11\]^。根据调查结果显示，系统用户主要有两种类型，一种是以使用为主要目的的用户角色类型，另一种是以管理为主要目的的管理员角色类型。本系统主要功能需求包括物资信息管理、物资运输管理等模块。其中，密码信息、用户信息、物资信息、物资运输信息等都是非常重要的数据记录，在系统设计的过程中，需要进行一定的加密处理，确保数据安全性，切实的保护好用户的重要信息。

## 3.2系统的可行性分析

### 3.2.1经济可行性

对系统进行经济可行性分析，也可以被称为对系统进行经济可行性研究，它是从社会的经济发展出发，通过研究整个的系统可行性，对成本收益情况进行全面地、具体地分析，并且根据所分析的可行性报告，为相关的投资者提供最科学的决策理论和最优的投资方案。本系统的开发促进了相关行业的信息化管理，管理人员可以直接通过在浏览器上发布常规应急物资管理系统的网站地址，用户即可根据一定的需要，有选择的对系统相关功能进行操作。这种方式打破了时间和空间的限制，可以使得相关行业在较短的时间内最大化地管理常规应急物资的相关信息。并且本系统所使用的开发技术和相关工具，大部分是开源的、免费的，所以可以节约很大一笔开发成本。综合上述内容分析可知，本系统的实现在经济层面上是具备可行性的。

### 3.2.2技术可行性

本系统是基于Java语言而进行开发的，因为Java语言简单易学、稳定性强、代码利用率高等特点，所以许多的开发技术人员均喜欢使用Java语言进行系统设计。现今很多程序系统的研究和开发，是通过使用Java语言进行编码设计的。此外，Java语言还具有跨平台的优点，这意味着所设计的系统是与平台无关的，也就说明由Java语言开发的系统可以支持在不同的浏览器上运行和使用。在条件大致相同的情况下，对比其他数据库，本系统使用的是MySQL数据库的相关语法简单易懂，数据库设计人员可以尽可能快的对其掌握和使用。MySQL数据库还具有占用系统内存少、功能齐全、响应速度快、使用不收费等特点，能够在极短时间内处理上千条信息记录，所以能够保证系统可以高效地运行和工作。综合上述内容分析可知，系统的实现在技术层面上是具备可行性的。

### 3.2.3操作可行性

如今，人们的日常生活已经离不开互联网的使用，在一定程度上，相关行业的信息化建设促进着社会的发展。人们通过使用手机上的应用程序，比如，通过使用电子商务系统，可以实现网上购物、在线支付等功能；通过使用国家官方网站，可以查看最新消息，申报个人业务；通过使用医院管理系统，可以进行网上预约挂号，在线查看体检报告等操作。在这些应用的背景下，本系统使用的是B/S开发结构模式，网站界面以人性化的设计为主，具有美观友好、交互性好等优点，用户不需要掌握一定的编程技术，直接通过对系统进行简单的功能操作，即可满足自己的使用需求。本系统还设计了一些提示信息，便于用户更好的理解系统相关功能，较快的以正确的操作方式来使用系统。综合上述内容分析可知，系统的实现在操作层面上是具备可行性的。

# **第四章 系统设计**

## 4.1系统的总体功能设计

系统的总体功能设计阶段，是通过结合系统分析阶段的相关内容，对系统的整体功能设计进行规划的过程。系统的总体功能设计是系统详细功能设计的一个大方向，也就是说系统的各类子功能模块的设计，都是以总体功能设计为目标而进行的。通过对系统进行需求分析可知，可以大致了解系统具体所需要的相关的主要功能模块。本系统主要的功能需求包括物资信息管理、物资运输管理等模块。管理员功能设计图如图4-1所示，用户功能设计图如图4-2所示。

![](media/image1.emf)

图4-1管理员功能设计图

![](media/image2.emf)

图4-2用户功能设计图

## 4.2数据库设计

### 4.2.1概念设计

本系统使用轻量级的MySQL数据库，对系统相关的数据信息进行管理和维护^\[12\]^。数据库设计阶段一般可以被分为概念设计和逻辑设计这两个阶段。概念设计阶段是对系统进行数据库设计的重要基础，将现实世界中用户的相关需求抽象化为虚拟世界中的概念模型，为后续的逻辑设计做好准备工作。本人通过设计E-R图，详细的对系统中的实体以及实体之间的联系进行了表达。各实体信息的实体属性图如图4-3、图4-4、图4-5、图4-6、图4-7、图4-8、图4-9、图4-10所示，系统总体E-R图如图4-11所示。

![](media/image3.emf)

图4-3管理员信息实体属性图

![](media/image4.emf)

图4-4用户信息实体属性图

![](media/image5.emf)

图4-5字典信息实体属性图

![](media/image6.emf)

图4-6部门信息实体属性图

![](media/image7.emf)

图4-7物资信息实体属性图

![](media/image8.emf)

图4-8物资申请信息实体属性图

![](media/image9.emf)

图4-9 物资运输信息实体属性图

![](media/image10.emf)

图4-10健康打卡信息实体属性图

![](media/image11.emf)

图4-11系统总体E-R图

### 4.2.2逻辑设计

逻辑设计阶段主要的工作是将概念设计中的E-R图，转换成方便系统进行存储和管理的二维表格形式。这一阶段也可以被称为数据库的详细设计，其直接关系到系统功能模块的正常运行、数据信息的正常更新等^\[13\]^。在设计过程中，需要充分考虑数据库的规范性和合理性，使得能够满足系统的功能和性能需求。本系统相关的数据表格设计内容如下所示。

表4-1 管理员信息表

  ------ ---------------- -------------------- ------------------- --------
   序号        列名             数据类型              说明          允许空

    1           id                Int                 编号            否

    2        username            String              用户名           是

    3        password            String               密码            是

    4          role              String               角色            是

    5        addtime              Date              新增时间          是
  ------ ---------------- -------------------- ------------------- --------

表4-2 用户信息表

  ------ ------------------ -------------------- ------------------- --------
   序号         列名              数据类型              说明          允许空

    1            Id                 Int                  id             否

    2         username             String               账户            是

    3         password             String               密码            是

    4         bumen_id            Integer               部门            是

    5       yonghu_name            String             用户姓名          是

    6       yonghu_phone           String            用户手机号         是

    7     yonghu_id_number         String           用户身份证号        是

    8       yonghu_photo           String             用户头像          是

    9        sex_types            Integer               性别            是

    10      yonghu_email           String             电子邮箱          是

    11      create_time             Date              创建时间          是
  ------ ------------------ -------------------- ------------------- --------

表4-3 字典信息表

  ------ ---------------- -------------------- ------------------- --------
   序号        列名             数据类型              说明          允许空

    1           id                Int                 编号            否

    2        dic_code            String               字段            是

    3        dic_name            String              字段名           是

    4       code_index          Integer               编码            是

    5       index_name           String             编码名字          是

    6        super_id           Integer            父字段编号         是

    7         beizhu             String               备注            是

    8      create_time            Date              创建时间          是
  ------ ---------------- -------------------- ------------------- --------

表4-4 部门信息表

  ------ ---------------- -------------------- ------------------- --------
   序号        列名             数据类型              说明          允许空

    1           Id                Int                  id             否

    2       bumen_name           String             部门名称          是

    3      bumen_zhize           String             部门职责          是

    4      bumen_number         Integer             部门人数          是

    5     bumen_content          String             部门介绍          是

    6      insert_time            Date              添加时间          是

    7      create_time            Date              创建时间          是
  ------ ---------------- -------------------- ------------------- --------

表4-5 物资信息表

  ------ ------------------- -------------------- ------------------- --------
   序号         列名               数据类型              说明          允许空

    1            Id                  Int                  id             否

    2         wuzi_name             String             物资名称          是

    3        wuzi_photo             String             物资照片          是

    4        wuzi_types            Integer             物资类型          是

    5     wuzi_kucun_number        Integer             物资库存          是

    6        wuzi_danwei            String               单位            是

    7        wuzi_delete           Integer             逻辑删除          是

    8       wuzi_content            String             物资介绍          是

    9        create_time             Date              创建时间          是
  ------ ------------------- -------------------- ------------------- --------

表4-6 物资申请信息表

  ------ -------------------------- -------------------- ------------------- --------
   序号             列名                  数据类型              说明          允许空

    1                Id                     Int                  id             否

    2            yonghu_id                Integer               用户            是

    3             wuzi_id                 Integer               物资            是

    4       wuzishenqing_number           Integer             申请数量          是

    5       wuzishenqing_content           String             申请详情          是

    6           insert_time                 Date              申请时间          是

    7     wuzishenqing_yesno_types        Integer               审核            是

    8     wuzishenqing_yesno_text          String             审核意见          是

    9           create_time                 Date              创建时间          是
  ------ -------------------------- -------------------- ------------------- --------

表4-7 物资运输信息表

  ------ ------------------------ -------------------- ------------------- --------
   序号            列名                 数据类型              说明          允许空

    1               Id                    Int                  id             否

    2            wuzi_id                Integer               物资            是

    3     wuziyunshu_uuid_number         String           运输唯一编号        是

    4       wuziyunshu_quxiang           String               去向            是

    5       wuziyunshu_number           Integer             运输数量          是

    6       wuziyunshu_content           String             运输详情          是

    7        wuziyunshu_types           Integer             当前状态          是

    8          insert_time                Date              添加时间          是

    9          update_time                Date            最后更新时间        是

    10         create_time                Date              创建时间          是
  ------ ------------------------ -------------------- ------------------- --------

表4-8 健康打卡信息表

  ------ ---------------- -------------------- ------------------- --------
   序号        列名             数据类型              说明          允许空

    1           Id                Int                  id             否

    2       yonghu_id           Integer               用户            是

    3      daka_content          String             打卡备注          是

    4      insert_time            date              打卡日期          是

    5      create_time            Date              创建时间          是
  ------ ---------------- -------------------- ------------------- --------

# **第五章 系统实现**

## 5.1管理员角色功能设计

### 5.1.1管理员首页

通过设计的首页功能模块，管理用户可以成功登录系统，并且选择点击相关的功能模块按钮，操作和实现自己所需要的功能，管理员首页解饿设计如图5-1所示。

![](media/image12.png){width="6.288888888888889in"
height="2.252083333333333in"}

图5-1管理员首页界面

本功能模块的核心代码如下：

/\*\*

\* 登录

\*/

\@IgnoreAuth

\@PostMapping(value = \"/login\")

public R login(String username, String password, String captcha,
HttpServletRequest request) {

UsersEntity user = usersService.selectOne(new
EntityWrapper\<UsersEntity\>().eq(\"username\", username));

if(user==null \|\| !user.getPassword().equals(password)) {

return R.error(\"账号或密码不正确\");

}

String token = tokenService.generateToken(user.getId(),username,
\"users\", user.getRole());

R r = R.ok();

r.put(\"token\", token);

r.put(\"role\",user.getRole());

r.put(\"userId\",user.getId());

return r;

}

/\*\*

\* 列表

\*/

\@RequestMapping(\"/page\")

public R page(@RequestParam Map\<String, Object\> params,UsersEntity
user){

EntityWrapper\<UsersEntity\> ew = new EntityWrapper\<UsersEntity\>();

PageUtils page = usersService.queryPage(params,
MPUtil.sort(MPUtil.between(MPUtil.allLike(ew, user), params), params));

return R.ok().put(\"data\", page);

}

### 5.1.2个人中心

通过设计的个人中心功能模块，管理用户可以选择修改账号密码，查看个人资料信息，通过不定期的对个人账户密码进行更新，保障个人信息安全，修改密码界面设计如图5-1所示，个人信息界面设计如图5-2所示。

![](media/image13.png){width="6.290972222222222in"
height="1.4826388888888888in"}

图5-1修改密码界面

![](media/image14.png){width="6.2965277777777775in" height="1.05in"}

图5-2个人信息界面

本功能模块的核心代码如下：

/\*\*

\* 密码重置

\*/

\@IgnoreAuth

\@RequestMapping(value = \"/resetPass\")

public R resetPass(String username, HttpServletRequest request){

UsersEntity user = usersService.selectOne(new
EntityWrapper\<UsersEntity\>().eq(\"username\", username));

if(user==null) {

return R.error(\"账号不存在\");

}

user.setPassword(\"123456\");

usersService.update(user,null);

return R.ok(\"密码已重置为：123456\");

}

/\*\*

\* 信息

\*/

\@RequestMapping(\"/info/{id}\")

public R info(@PathVariable(\"id\") String id){

UsersEntity user = usersService.selectById(id);

return R.ok().put(\"data\", user);

}

### 5.1.3健康打卡管理

通过设计的健康打卡管理功能模块，管理用户可以管理相关的健康打卡信息记录，比如进行查看健康打卡的详细信息，修改健康打卡的日期信息，删除已经失效的健康打卡信息记录等操作，健康打卡管理界面设计如图5-3所示。

![](media/image15.png){width="6.297916666666667in"
height="2.467361111111111in"}

图5-3健康打卡管理界面

本功能模块的核心代码如下：

/\*\*

\* 健康打卡后端修改

\*/

\@RequestMapping(\"/update\")

public R update(@RequestBody DakaEntity daka, HttpServletRequest
request){

logger.debug(\"update方法:,,Controller:{},,daka:{}\",this.getClass().getName(),daka.toString());

String role =
String.valueOf(request.getSession().getAttribute(\"role\"));

// if(false)

// return R.error(511,\"永远不会进入\");

// else if(\"用户\".equals(role))

//
daka.setYonghuId(Integer.valueOf(String.valueOf(request.getSession().getAttribute(\"userId\"))));

//根据字段查询是否有相同数据

Wrapper\<DakaEntity\> queryWrapper = new EntityWrapper\<DakaEntity\>()

.notIn(\"id\",daka.getId())

.andNew()

.eq(\"yonghu_id\", daka.getYonghuId())

.eq(\"insert_time\", new
SimpleDateFormat(\"yyyy-MM-dd\").format(daka.getInsertTime()))

;

logger.info(\"sql语句:\"+queryWrapper.getSqlSegment());

DakaEntity dakaEntity = dakaService.selectOne(queryWrapper);

if(dakaEntity==null){

dakaService.updateById(daka);//根据id更新

return R.ok();

}else {

return R.error(511,\"表中有相同数据\");

}

}

### 5.1.4基础数据管理

通过设计的基础数据管理功能模块，管理用户可以管理相关的物资类型信息记录，比如进行查看物资类型的详细信息，修改物资类型的名称信息，删除已经失效的物资类型信息记录等操作，物资类型管理界面设计如图5-4所示。

![](media/image16.png){width="6.294444444444444in"
height="2.673611111111111in"}

图5-4物资类型管理界面

本功能模块的核心代码如下：

/\*\*

\* 基础数据后端修改

\*/

\@RequestMapping(\"/update\")

public R update(@RequestBody DictionaryEntity dictionary,
HttpServletRequest request){

logger.debug(\"update方法:,,Controller:{},,dictionary:{}\",this.getClass().getName(),dictionary.toString());

String role =
String.valueOf(request.getSession().getAttribute(\"role\"));

// if(false)

// return R.error(511,\"永远不会进入\");

//根据字段查询是否有相同数据

Wrapper\<DictionaryEntity\> queryWrapper = new
EntityWrapper\<DictionaryEntity\>()

.notIn(\"id\",dictionary.getId())

.eq(\"dic_code\", dictionary.getDicCode())

.eq(\"index_name\", dictionary.getIndexName())

;

if(dictionary.getDicCode().contains(\"\_erji_types\")){

queryWrapper.eq(\"super_id\",dictionary.getSuperId());

}

logger.info(\"sql语句:\"+queryWrapper.getSqlSegment());

DictionaryEntity dictionaryEntity =
dictionaryService.selectOne(queryWrapper);

if(dictionaryEntity==null){

dictionaryService.updateById(dictionary);//根据id更新

//如果字典表修改数据的话,把数据再重新查出,放入监听器中

List\<DictionaryEntity\> dictionaryEntities =
dictionaryService.selectList(new EntityWrapper\<DictionaryEntity\>());

ServletContext servletContext = request.getServletContext();

Map\<String, Map\<Integer,String\>\> map = new HashMap\<\>();

for(DictionaryEntity d :dictionaryEntities){

Map\<Integer, String\> m = map.get(d.getDicCode());

if(m ==null \|\| m.isEmpty()){

m = new HashMap\<\>();

}

m.put(d.getCodeIndex(),d.getIndexName());

map.put(d.getDicCode(),m);

}

servletContext.setAttribute(\"dictionaryMap\",map);

return R.ok();

}else {

return R.error(511,\"表中有相同数据\");

}

}

### 5.1.5物资管理

通过设计的物资管理功能模块，管理用户可以管理相关的物资信息记录，比如进行查看物资的详细信息，修改物资的库存信息，删除已经失效的物资信息记录等操作，物资管理界面设计如图5-5所示。

![](media/image17.png){width="6.297916666666667in"
height="2.841666666666667in"}

图5-5物资管理界面

本功能模块的核心代码如下：

/\*\*

\* 物资后端修改

\*/

\@RequestMapping(\"/update\")

public R update(@RequestBody WuziEntity wuzi, HttpServletRequest
request){

logger.debug(\"update方法:,,Controller:{},,wuzi:{}\",this.getClass().getName(),wuzi.toString());

String role =
String.valueOf(request.getSession().getAttribute(\"role\"));

// if(false)

// return R.error(511,\"永远不会进入\");

//根据字段查询是否有相同数据

Wrapper\<WuziEntity\> queryWrapper = new EntityWrapper\<WuziEntity\>()

.notIn(\"id\",wuzi.getId())

.andNew()

.eq(\"wuzi_name\", wuzi.getWuziName())

.eq(\"wuzi_types\", wuzi.getWuziTypes())

.eq(\"wuzi_kucun_number\", wuzi.getWuziKucunNumber())

.eq(\"wuzi_danwei\", wuzi.getWuziDanwei())

.eq(\"wuzi_delete\", wuzi.getWuziDelete())

;

logger.info(\"sql语句:\"+queryWrapper.getSqlSegment());

WuziEntity wuziEntity = wuziService.selectOne(queryWrapper);

if(\"\".equals(wuzi.getWuziPhoto()) \|\|
\"null\".equals(wuzi.getWuziPhoto())){

wuzi.setWuziPhoto(null);

}

if(wuziEntity==null){

wuziService.updateById(wuzi);//根据id更新

return R.ok();

}else {

return R.error(511,\"表中有相同数据\");

}

}

### 5.1.6物资申请管理

通过设计的物资申请管理功能模块，管理用户可以管理相关的物资申请信息记录，比如进行查看物资申请的详细信息，修改物资的申请时间信息，删除已经失效的物资申请信息记录等操作，物资申请管理界面设计如图5-6所示。

![](media/image18.png){width="6.290972222222222in"
height="3.1152777777777776in"}

图5-6物资申请管理界面

本功能模块的核心代码如下：

/\*\*

\* 物资申请后端保存

\*/

\@RequestMapping(\"/save\")

public R save(@RequestBody WuzishenqingEntity wuzishenqing,
HttpServletRequest request){

logger.debug(\"save方法:,,Controller:{},,wuzishenqing:{}\",this.getClass().getName(),wuzishenqing.toString());

String role =
String.valueOf(request.getSession().getAttribute(\"role\"));

if(false)

return R.error(511,\"永远不会进入\");

else if(\"用户\".equals(role))

wuzishenqing.setYonghuId(Integer.valueOf(String.valueOf(request.getSession().getAttribute(\"userId\"))));

wuzishenqing.setInsertTime(new Date());

wuzishenqing.setWuzishenqingYesnoTypes(1);

wuzishenqing.setCreateTime(new Date());

wuzishenqingService.insert(wuzishenqing);

return R.ok();

}

/\*\*

\* 物资申请后端修改

\*/

\@RequestMapping(\"/update\")

public R update(@RequestBody WuzishenqingEntity wuzishenqing,
HttpServletRequest request){

logger.debug(\"update方法:,,Controller:{},,wuzishenqing:{}\",this.getClass().getName(),wuzishenqing.toString());

wuzishenqingService.updateById(wuzishenqing);//根据id更新

return R.ok();

}

### 5.1.7物资运输管理

通过设计的物资运输管理功能模块，管理用户可以管理相关的物资运输信息记录，比如进行查看物资运输的详细信息，修改物资运输的当前状态信息，删除已经失效的物资运输信息记录等操作，物资运输管理界面设计如图5-7所示。

![](media/image19.png){width="6.293055555555555in"
height="3.088888888888889in"}

图5-7物资运输管理界面

本功能模块的核心代码如下：

/\*\*

\* 物资运输后端保存

\*/

\@RequestMapping(\"/save\")

public R save(@RequestBody WuziyunshuEntity wuziyunshu,
HttpServletRequest request){

logger.debug(\"save方法:,,Controller:{},,wuziyunshu:{}\",this.getClass().getName(),wuziyunshu.toString());

String role =
String.valueOf(request.getSession().getAttribute(\"role\"));

if(false)

return R.error(511,\"永远不会进入\");

wuziyunshu.setUpdateTime(new Date());

wuziyunshu.setInsertTime(new Date());

wuziyunshu.setCreateTime(new Date());

wuziyunshuService.insert(wuziyunshu);

return R.ok();

}

/\*\*

\* 物资运输后端修改

\*/

\@RequestMapping(\"/update\")

public R update(@RequestBody WuziyunshuEntity wuziyunshu,
HttpServletRequest request){

logger.debug(\"update方法:,,Controller:{},,wuziyunshu:{}\",this.getClass().getName(),wuziyunshu.toString());

wuziyunshu.setUpdateTime(new Date());

wuziyunshuService.updateById(wuziyunshu);//根据id更新

return R.ok();

}

### 5.1.8用户管理

通过设计的用户管理功能模块，管理用户可以管理相关的用户信息资料，比如进行查看用户的详细资料，修改用户的联系方式，删除已经注销的用户信息记录等操作，用户管理界面设计如图5-8所示。

![](media/image20.png){width="6.297916666666667in"
height="3.0305555555555554in"}

图5-8用户管理界面

本功能模块的核心代码如下：

/\*\*

\* 用户后端修改

\*/

\@RequestMapping(\"/update\")

public R update(@RequestBody YonghuEntity yonghu, HttpServletRequest
request){

logger.debug(\"update方法:,,Controller:{},,yonghu:{}\",this.getClass().getName(),yonghu.toString());

String role =
String.valueOf(request.getSession().getAttribute(\"role\"));

// if(false)

// return R.error(511,\"永远不会进入\");

//根据字段查询是否有相同数据

Wrapper\<YonghuEntity\> queryWrapper = new
EntityWrapper\<YonghuEntity\>()

.notIn(\"id\",yonghu.getId())

.andNew()

.eq(\"username\", yonghu.getUsername())

.or()

.eq(\"yonghu_phone\", yonghu.getYonghuPhone())

.or()

.eq(\"yonghu_id_number\", yonghu.getYonghuIdNumber())

;

logger.info(\"sql语句:\"+queryWrapper.getSqlSegment());

YonghuEntity yonghuEntity = yonghuService.selectOne(queryWrapper);

if(\"\".equals(yonghu.getYonghuPhoto()) \|\|
\"null\".equals(yonghu.getYonghuPhoto())){

yonghu.setYonghuPhoto(null);

}

if(yonghuEntity==null){

yonghuService.updateById(yonghu);//根据id更新

return R.ok();

}else {

return R.error(511,\"账户或者用户手机号或者用户身份证号已经被使用\");

}

}

### 5.1.9部门管理

通过设计的部门管理功能模块，管理用户可以管理相关的部门信息记录，比如进行查看部门的详细信息，修改部门的职责信息，删除已经失效的部门信息记录等操作，部门管理界面设计如图5-9所示。

![](media/image21.png){width="6.2875in" height="2.852777777777778in"}

图5-9部门管理界面

本功能模块的核心代码如下：

/\*\*

\* 部门后端修改

\*/

\@RequestMapping(\"/update\")

public R update(@RequestBody BumenEntity bumen, HttpServletRequest
request){

logger.debug(\"update方法:,,Controller:{},,bumen:{}\",this.getClass().getName(),bumen.toString());

String role =
String.valueOf(request.getSession().getAttribute(\"role\"));

// if(false)

// return R.error(511,\"永远不会进入\");

//根据字段查询是否有相同数据

Wrapper\<BumenEntity\> queryWrapper = new EntityWrapper\<BumenEntity\>()

.notIn(\"id\",bumen.getId())

.andNew()

.eq(\"bumen_name\", bumen.getBumenName())

.eq(\"bumen_zhize\", bumen.getBumenZhize())

.eq(\"bumen_number\", bumen.getBumenNumber())

;

logger.info(\"sql语句:\"+queryWrapper.getSqlSegment());

BumenEntity bumenEntity = bumenService.selectOne(queryWrapper);

if(bumenEntity==null){

bumenService.updateById(bumen);//根据id更新

return R.ok();

}else {

return R.error(511,\"表中有相同数据\");

}

}

## 5.2用户功能设计

### 5.2.1用户首页

通过设计的首页功能模块，管理用户可以成功登录系统，并且选择点击相关的功能模块按钮，操作和实现自己所需要的功能，管理员首页解饿设计如图5-10所示。

![](media/image22.png){width="6.294444444444444in"
height="1.5645833333333334in"}

图5-10用户首页界面

本功能模块的核心代码如下：

/\*\*

\* 首页后端保存

\*/

\@RequestMapping(\"/save\")

public R save(@RequestBody YonghuEntity yonghu, HttpServletRequest
request){

logger.debug(\"save方法:,,Controller:{},,yonghu:{}\",this.getClass().getName(),yonghu.toString());

String role =
String.valueOf(request.getSession().getAttribute(\"role\"));

if(false)

return R.error(511,\"永远不会进入\");

Wrapper\<YonghuEntity\> queryWrapper = new
EntityWrapper\<YonghuEntity\>()

.eq(\"username\", yonghu.getUsername())

.or()

.eq(\"yonghu_phone\", yonghu.getYonghuPhone())

.or()

.eq(\"yonghu_id_number\", yonghu.getYonghuIdNumber())

;

logger.info(\"sql语句:\"+queryWrapper.getSqlSegment());

YonghuEntity yonghuEntity = yonghuService.selectOne(queryWrapper);

if(yonghuEntity==null){

yonghu.setCreateTime(new Date());

yonghu.setPassword(\"123456\");

yonghuService.insert(yonghu);

return R.ok();

}else {

return R.error(511,\"账户或者用户手机号或者用户身份证号已经被使用\");

}

}

### 5.2.2个人中心

通过设计的个人中心管理功能模块，用户可以选择查看个人资料信息，选择更新个人相关的资料信息记录；也可以选择修改账号密码，通过不定期的对个人账户密码进行更新，保障个人信息安全，修改密码界面设计如图5-11所示，个人信息界面设计如图5-12所示。

![](media/image23.png){width="6.285416666666666in"
height="1.4756944444444444in"}

图5-11修改密码界面

![](media/image24.png){width="6.291666666666667in"
height="2.560416666666667in"}

图5-12个人信息界面

本功能模块的核心代码如下：

//查询是否重复

//账户

List\<YonghuEntity\> yonghuEntities_username =
yonghuService.selectList(new
EntityWrapper\<YonghuEntity\>().in(\"username\",
seachFields.get(\"username\")));

if(yonghuEntities_username.size() \>0 ){

ArrayList\<String\> repeatFields = new ArrayList\<\>();

for(YonghuEntity s:yonghuEntities_username){

repeatFields.add(s.getUsername());

}

return R.error(511,\"数据库的该表中的 \[账户\] 字段已经存在
存在数据为:\"+repeatFields.toString());

}

//用户手机号

List\<YonghuEntity\> yonghuEntities_yonghuPhone =
yonghuService.selectList(new
EntityWrapper\<YonghuEntity\>().in(\"yonghu_phone\",
seachFields.get(\"yonghuPhone\")));

if(yonghuEntities_yonghuPhone.size() \>0 ){

ArrayList\<String\> repeatFields = new ArrayList\<\>();

for(YonghuEntity s:yonghuEntities_yonghuPhone){

repeatFields.add(s.getYonghuPhone());

}

return R.error(511,\"数据库的该表中的 \[用户手机号\] 字段已经存在
存在数据为:\"+repeatFields.toString());

}

//用户身份证号

List\<YonghuEntity\> yonghuEntities_yonghuIdNumber =
yonghuService.selectList(new
EntityWrapper\<YonghuEntity\>().in(\"yonghu_id_number\",
seachFields.get(\"yonghuIdNumber\")));

if(yonghuEntities_yonghuIdNumber.size() \>0 ){

ArrayList\<String\> repeatFields = new ArrayList\<\>();

for(YonghuEntity s:yonghuEntities_yonghuIdNumber){

repeatFields.add(s.getYonghuIdNumber());

}

return R.error(511,\"数据库的该表中的 \[用户身份证号\] 字段已经存在
存在数据为:\"+repeatFields.toString());

}

yonghuService.insertBatch(yonghuList);

return R.ok();

}

### 5.2.3健康打卡管理

通过设计的健康打卡管理功能模块，用户可以管理相关的健康打卡信息记录，比如进行查看健康打卡的详细信息，修改健康打卡的日期信息，删除已经失效的健康打卡信息记录等操作，健康打卡管理界面设计如图5-13所示。

![](media/image25.png){width="6.285416666666666in"
height="2.470833333333333in"}

图5-13健康打卡管理界面

本功能模块的核心代码如下：

/\*\*

\* 健康打卡后端详情

\*/

\@RequestMapping(\"/info/{id}\")

public R info(@PathVariable(\"id\") Long id, HttpServletRequest
request){

logger.debug(\"info方法:,,Controller:{},,id:{}\",this.getClass().getName(),id);

DakaEntity daka = dakaService.selectById(id);

if(daka !=null){

//entity转view

DakaView view = new DakaView();

BeanUtils.copyProperties( daka , view );//把实体数据重构到view中

//级联表

YonghuEntity yonghu = yonghuService.selectById(daka.getYonghuId());

if(yonghu != null){

BeanUtils.copyProperties( yonghu , view ,new String\[\]{ \"id\",
\"createTime\", \"insertTime\",
\"updateTime\"});//把级联的数据添加到view中,并排除id和创建时间字段

view.setYonghuId(yonghu.getId());

}

//修改对应字典表字段

dictionaryService.dictionaryConvert(view, request);

return R.ok().put(\"data\", view);

}else {

return R.error(511,\"查不到数据\");

}

}

### 5.2.4物资管理

通过设计的物资管理功能模块，管理用户可以查看相关的物资信息记录，可以查到物资名称、物资图片、物资类型、物资库存等详细信息，物资管理界面设计如图5-14所示。

![](media/image26.png){width="6.299305555555556in"
height="2.8381944444444445in"}

图5-14物资管理界面

本功能模块的核心代码如下：

/\*\*

\* 物资后端详情

\*/

\@RequestMapping(\"/info/{id}\")

public R info(@PathVariable(\"id\") Long id, HttpServletRequest
request){

logger.debug(\"info方法:,,Controller:{},,id:{}\",this.getClass().getName(),id);

WuziEntity wuzi = wuziService.selectById(id);

if(wuzi !=null){

//entity转view

WuziView view = new WuziView();

BeanUtils.copyProperties( wuzi , view );//把实体数据重构到view中

//修改对应字典表字段

dictionaryService.dictionaryConvert(view, request);

return R.ok().put(\"data\", view);

}else {

return R.error(511,\"查不到数据\");

}

}

### 5.2.5物资申请管理

通过设计的物资申请管理功能模块，用户可以管理相关的物资申请信息记录，比如进行查看物资申请的详细信息，新增相关的物资申请信息记录，物资申请管理界面设计如图5-15所示。

![](media/image27.png){width="6.2875in" height="2.75625in"}

图5-15物资申请管理界面

本功能模块的核心代码如下：

/\*\*

\* 物资申请后端详情

\*/

\@RequestMapping(\"/info/{id}\")

public R info(@PathVariable(\"id\") Long id, HttpServletRequest
request){

logger.debug(\"info方法:,,Controller:{},,id:{}\",this.getClass().getName(),id);

WuzishenqingEntity wuzishenqing = wuzishenqingService.selectById(id);

if(wuzishenqing !=null){

//entity转view

WuzishenqingView view = new WuzishenqingView();

BeanUtils.copyProperties( wuzishenqing , view );//把实体数据重构到view中

//级联表

WuziEntity wuzi = wuziService.selectById(wuzishenqing.getWuziId());

if(wuzi != null){

BeanUtils.copyProperties( wuzi , view ,new String\[\]{ \"id\",
\"createTime\", \"insertTime\",
\"updateTime\"});//把级联的数据添加到view中,并排除id和创建时间字段

view.setWuziId(wuzi.getId());

}

//级联表

YonghuEntity yonghu =
yonghuService.selectById(wuzishenqing.getYonghuId());

if(yonghu != null){

BeanUtils.copyProperties( yonghu , view ,new String\[\]{ \"id\",
\"createTime\", \"insertTime\",
\"updateTime\"});//把级联的数据添加到view中,并排除id和创建时间字段

view.setYonghuId(yonghu.getId());

}

//修改对应字典表字段

dictionaryService.dictionaryConvert(view, request);

return R.ok().put(\"data\", view);

}else {

return R.error(511,\"查不到数据\");

}

}

### 5.2.6物资运输管理

通过设计的物资运输管理功能模块，用户可以查看相关的物资运输信息记录，比如查到物资名称、物资图片、单位、运输数量、当前状态等详细信息，物资运输管理界面设计如图5-16所示。

![](media/image28.png){width="6.2868055555555555in"
height="3.079861111111111in"}

图5-16物资运输管理界面

本功能模块的核心代码如下：

/\*\*

\* 物资运输后端详情

\*/

\@RequestMapping(\"/info/{id}\")

public R info(@PathVariable(\"id\") Long id, HttpServletRequest
request){

logger.debug(\"info方法:,,Controller:{},,id:{}\",this.getClass().getName(),id);

WuziyunshuEntity wuziyunshu = wuziyunshuService.selectById(id);

if(wuziyunshu !=null){

//entity转view

WuziyunshuView view = new WuziyunshuView();

BeanUtils.copyProperties( wuziyunshu , view );//把实体数据重构到view中

//级联表

WuziEntity wuzi = wuziService.selectById(wuziyunshu.getWuziId());

if(wuzi != null){

BeanUtils.copyProperties( wuzi , view ,new String\[\]{ \"id\",
\"createTime\", \"insertTime\",
\"updateTime\"});//把级联的数据添加到view中,并排除id和创建时间字段

view.setWuziId(wuzi.getId());

}

//修改对应字典表字段

dictionaryService.dictionaryConvert(view, request);

return R.ok().put(\"data\", view);

}else {

return R.error(511,\"查不到数据\");

}

}

# **第六章 系统测试**

## 6.1 测试概述

系统测试是将系统的软件、硬件看成一个整体，对系统相关功能模块设计进行测试。系统测试阶段首要的工作任务就是根据相关的测试要求书，检验系统开发是否可以达到所规定的设计要求。在测试的过程中，可以在非常短的时间中，快速地查找系统存在漏洞，并尽快对其进行解决和处理，达到改进和完善系统的目的^\[14\]^。白盒测试和黑盒测试是相关测试人员使用较多的两种测试方法。白盒测试又被称为结构测试，其主要通过对系统的内部代码、结构进行测试，检测系统的代码结构、逻辑关系、数据结构等内容是否是合理的、有效的，对于某些设计不合理的代码，测试人员将形成相关的程序清单，并将其反馈给开发技术人员，再由开发技术人员对代码进行一定的修改^\[15\]^。黑盒测试又被称为功能测试，其主要通过对系统的用户界面、功能实现进行测试，检测相关的功能模块是否设计合理，能否正常使用。测试人员会记录某些设计不合理的，或者不能正常操作的功能模块，并将其撰写成相关的测试报告，并将相关报告告知相关开发人员，开发技术人员根据测试报告，对系统进行更新和完善^\[16\]^。除此之外，还有性能测试、单元测试、安全测试等，本人主要使用功能测试对本系统进行检验。

## 6.2 测试结果

在不同的操作系统、浏览器等测试环境中，对常规应急物资管理系统进行测试，在一定程度上，也影响着系统的测试结果。为了加强系统的适用性和稳定性，本人通过在windows10操作系统的计算机上，使用360、谷歌、IE等不同类型的浏览器，对系统进行了详细的功能测试。测试流程图如图6-1所示，用户登录测试如图6-2、图6-3所示，物资管理测试如图6-4、图6-5所示。

![](media/image29.emf)

图6-1测试流程图

![](media/image30.png){width="6.2965277777777775in"
height="3.4305555555555554in"}

图6-2用户登录界面

![](media/image31.png){width="6.288194444444445in"
height="1.5208333333333333in"}

图6-3用户登录成功界面

![](media/image32.png){width="6.297916666666667in"
height="2.828472222222222in"}

图6-4查询物资信息界面

![](media/image33.png){width="6.2965277777777775in"
height="1.9597222222222221in"}

图6-5查询物资信息成功界面

本系统主要使用功能测试的方法进行测试，系统测试的结果表明，本人开发的基于SpringBoot+Vue的常规应急物资管理系统，虽然还存在着一些不足，比如页面不够美观，数据安全有待加强等，但是整体来说，能够满足相关行业管理常规应急物资的相关功能需求，并且有利于改进整个相关行业的管理模式，提高服务质量，提升管理水平。因此，本系统的设计与实现基本上是比较成功。

# **结 论**

本文首先通过介绍课题的研究现状、研究方法等内容，解释系统的研发所具备实用价值和理论依据，便于初步地了解和认识系统。其次通过介绍系统的开发工具，阐明系统开发的实现可能以及技术支持，接着通过系统分析过程，分析系统的研发在现实生活中的需求情况以及运用可行性，再通过设计系统的功能模块、数据库表格等，详细的对系统功能进行设计，有利于更快更好的实现系统，最后通过测试过程，对设计的相关功能模块进行详细地测试，检查和查验相关功能在运行过程是是否会出现问题，能否满足使用需求。

整体来说，本系统的设计是比较理想的，但是由于本人经验不够丰富，时间不够充裕，所设计的系统功能可能不够完备，数据信息不够加密保障，用户界面不够交互，数据安全可能有待加强。本人将提高自己的专业技术水平，学习更加先进的计算机技术，并将其运用到系统的设计中，不断地对系统进行优化和完善，在未来设计出一款功能更强大、页面更美观、数据安全更高的系统软件，提高系统的实用价值，使其能够被到运用更多的应用场景中。

# 参考文献

\[1\]王金朔,孙延辉.基于SSM和Java的网上订餐系统设计\[J\].信息通信,2020(10):99-100.

\[2\]欧楠.计算机软件开发中 Java 语言的应用分析\[J\].
信息与电脑(理论版),2019(04):110-111.

\[3\]周劼翀.计算机软件开发中 Java 编程语言的应用研究\[J\].
信息与电脑(理论版), 2019(05): 131-132.

\[4\]马梓昂，贾克斌. 基于 Web 的高性能智能快递柜管理系统\[J\].
计算机应用与软件，2020, 37(4): 1-5,47.

\[5\]张海宾.基于 C/S 架构客户端嵌入 B/S
架构系统的设计与实现\[J\].电子世界, 2020, 4(17): 125-126.

\[6\]杨兰.计算机软件开发的 JAVA 编程语言及其实际应用\[J\]. 电子设计工程,
2020, 25(21): 49-52+56.

\[7\]洪植林. 基于SSM框架的高校实验室信息管理系统的设计与实现\[D\].
浙江:浙江工业大学，2020.

\[8\]徐鹏涛. 基于Vue的前端开发框架的设计与实现\[D\].山东大学,
2020.DOI:10.27272/d. cnki.gshdu.2020.000715.

\[9\]乔岚. 基于MyBatis 和 Spring 的JavaEE 数据持久层的研究与应用\[J\].
信息与电脑（理论版），2019，378(08): 79-82.

\[10\]郭冰. 基于MySQL数据库的索引优化研究\[J\].信息与电脑(理论 版),
2019(12): 154-156+163.

\[11\]翟剑锟. Spring
框架技术分析及应用研究\[D\].中国科学院大学(工程管理与信息技术学院),
2020.

\[12\]梁琰.MySQL 数据库在 PHP 网页中的动态应用研究\[J\]. 电脑知识与技术,
2019, 15 (09): 7-8.

\[13\]陈年飞,王麒森,王志勃. MySQL 数据库中关于索引的研究\[J\].
信息与电脑(理 论版), 2019(05): 175-176.

\[14\]张新华, 何永前. 软件测试方法概述\[J\]. 科技视界, 2019(4):125-125.

\[15\]Konstantins Gusarovs. An Analysis on Java Programming Language
Decompiler Capabilities\[J\]. Applied Computer Systems,2019,23(2).

\[16\]Tan Yiyu. A Hardware-oriented Object Model for Java in an Embedded
Processor\[J\]. Microprocessors and Microsystems,2020.

# **致 谢**

大学生活将要结束了，这样想来，时间还真过得非常快。在本次的毕业设计过程中，我需要跟许多帮助过我的人表示最真诚地感谢。非常感谢我的导伦立军华老师，在导师的指导下，我汲取了很多书本上没有记录的专业知识，使得我成功地设计出了基于SpringBoot+Vue的常规应急物资管理系统，也顺利地撰写完了毕业论文。感谢我的同学和朋友们，正当我在设计系统遇到非常棘手的困难时，是我的同学和朋友们帮助我分析问题，寻找问题的最佳解决方案，而后得以成功地解决问题。感谢我的家人，一直不断地支持和鼓励我，为我提供了一个温暖的避风港，让我可以无忧无虑的在学校学习。感谢我的学校，为我们提供了一个师资力量雄厚、图书种类繁多的学习环境，让我们可以在一个良好的学习氛围中，学习到许多有价值的知识，可以使我扩充知识面，扩宽视野，积累专业知识，提高专业水平和能力。由此打下扎实的技术基础，在未来，有利于寻找更多的就业机会，更好的适应社会生活。


### 0155springboot基于SpringBoot+Vue的常规应急物资管理系统 项目图片
![图片](/images/0155springbootimg_001.jpg)
![图片](/images/0155springbootimg_003.jpg)
![图片](/images/0155springbootimg_002.jpg)
![图片](/images/0155springbootimg_006.jpg)
![图片](/images/0155springbootimg_007.jpg)
![图片](/images/0155springbootimg_005.jpg)
![图片](/images/0155springbootimg_004.jpg)








