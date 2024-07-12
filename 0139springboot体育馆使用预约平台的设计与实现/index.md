# 0139springboot体育馆使用预约平台的设计与实现


# [0139springboot体育馆使用预约平台的设计与实现](https://github.com/GraduationProject-springboot/0139springboot)

### 微信： chen_q123456  qq:462201886
### github:chenqi199

### [所有项目](https://github.com/GraduationProject-springboot/allSpringbootProjects) 包安装运行

### [所有项目列表excel 腾讯文档 项目清单](https://docs.qq.com/sheet/DSHRFSVZ5aEVYT3N3?tab=BB08J2) 包安装运行

### [github](https://chenqi199.github.io)








# 0139springboot体育馆使用预约平台的设计与实现

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://player.bilibili.com/player.html?isOutside=true&aid=BV1jqaLe1ECs&bvid=BV1jqaLe1ECs&cid=500001610828023&p=38)

### [所有项目](https://github.com/GraduationProject-springboot/allSpringbootProjects) 包安装运行












**毕 业 设 计（论 文）**

题目：[体育馆使用预约平台的设计与实现]{.underline}

# 体育馆使用预约平台

# 摘要

如今社会上各行各业，都在用属于自己专用的软件来进行工作，互联网发展到这个时候，人们已经发现离不开了互联网。互联网的发展，离不开一些新的技术，而新技术的产生往往是为了解决现有问题而产生的。针对于场地预约信息管理方面的不规范，容错率低，管理人员处理数据费工费时，采用新开发的体育馆使用预约平台可以从根源上规范整个数据处理流程的正规性和合法性。

体育馆使用预约平台能够实现场地管理，用户管理，论坛管理，公告管理，场地订单管理等功能。该系统采用了Mysql数据库，Java语言，Spring
Boot框架等技术进行编程实现。

体育馆使用预约平台可以提高场地预约信息管理问题的解决效率，优化场地预约信息处理流程，并且能够保证存储数据的安全，它是一个非常可靠，非常安全的应用程序。

**关键词：**体育馆使用预约平台；Mysql数据库；Java语言

**Gymnasium Use Reservation Platform**

Nowadays, all walks of life in society are using their own dedicated
software for work. At this point in the development of the Internet,
people have found that they cannot do without the Internet. The
development of the Internet is inseparable from some new technologies,
and the emergence of new technologies is often produced to solve
existing problems. In view of the non-standard management of venue
reservation information, low fault tolerance rate, and time-consuming
and labor-intensive processing of data by managers, the newly developed
gym use reservation platform can standardize the formality and
legitimacy of the entire data processing process from the root.

The stadium uses the reservation platform to realize the functions of
venue management, user management, forum management, announcement
management, venue order management and other functions. The system uses
Mysql database, Java language, Spring Boot framework and other
technologies for programming.

The use of the reservation platform in the gym can improve the
efficiency of solving the problem of venue reservation information
management, optimize the process of venue reservation information, and
ensure the safety of stored data. It is a very reliable and very safe
application.

Key Words：Gymnasium uses reservation platform; Mysql database; Java
language

[第1章 绪论 1](#第1章-绪论)

[1.1 课题背景 1](#课题背景)

[1.2 课题意义 1](#课题意义)

[1.3 研究内容 2](#研究内容)

[第2章 开发环境与技术 3](#第2章-开发环境与技术)

[2.1 Java语言 3](#java语言)

[2.2 MYSQL数据库 3](#mysql数据库)

[2.3 IDEA开发工具 4](#idea开发工具)

[2.4 Spring Boot框架 4](#spring-boot框架)

[第3章 需求分析 5](#第3章-需求分析)

[3.1 可行性分析 5](#可行性分析)

[3.1.1 技术可行性 5](#技术可行性)

[3.1.2 经济可行性 5](#经济可行性)

[3.1.3 操作可行性 5](#操作可行性)

[3.2 系统流程分析 6](#系统流程分析)

[3.3 系统性能需求 8](#系统性能需求)

[3.4 系统功能需求 8](#系统功能需求)

[第4章 系统设计 11](#第4章-系统设计)

[4.1 功能模块划分 11](#功能模块划分)

[4.1.1 管理员模块功能 11](#管理员模块功能)

[4.1.2 用户模块功能 12](#用户模块功能)

[4.2 数据库设计 12](#数据库设计)

[4.2.1 E-R图 13](#e-r图)

[4.2.2 数据库表设计 15](#数据库表设计)

[第5章 系统设计与实现 19](#__RefHeading___Toc26881)

[5.1 管理员后台功能实现 19](#管理员后台功能实现)

[5.1.1 论坛管理 19](#论坛管理)

[5.1.2 用户管理 20](#用户管理)

[5.1.3 场地管理 22](#场地管理)

[5.1.4 场地订单管理 23](#场地订单管理)

[5.1.5 公告信息管理 24](#公告信息管理)

[5.2 用户前台功能实现 25](#用户前台功能实现)

[5.2.1 场地信息 25](#场地信息)

[5.2.2 在线论坛 27](#在线论坛)

[5.2.3 场地预约 27](#场地预约)

[第6章 软件测试 29](#__RefHeading___Toc22282)

[6.1 测试用例 29](#测试用例)

[6.2 测试结果 33](#测试结果)

[结 论 34](#结-论)

[参考文献 36](#参考文献)

[致 谢 37](#__RefHeading___Toc10420)

# 第1章 绪论

## 1.1 课题背景

二十一世纪互联网的出现，改变了几千年以来人们的生活，不仅仅是生活物资的丰富，还有精神层次的丰富。时代进步的标志，就是让人们过上更好的生活。在互联网诞生之前，地域位置往往是人们思想上不可跨域的鸿沟，信息的传播速度极慢，信息处理的速度和要求还是通过人们骑马或者是信鸽传递，这些信息传递都是不可控制的，中间很有可能丢失，信息的传递水平决定了人们生活的水平。现如今，大家都在用互联网来实现自己的目的，从内部管理设置计算机管理，提高内部信息管理水平，从外部市场也可以用计算机获取相关数据进行处理，如今各行各业已经严重依赖于计算机了。

本课题研究和开发体育馆使用预约平台，让安装在计算机上的该系统变成管理人员的小帮手，提高场地预约信息处理速度，规范场地预约信息处理流程，让管理人员的产出效益更高。

## 1.2 课题意义

传统处理数据，必须是一张张纸，然后处理完毕又是统计在一张张纸上面，不断的重复处理，最终有个结果给最高层作为参考，这个模式在互联网没有出现之前，是一种常见的事情，信息管理的效率提不上去，那就用人才，人多力量大，是一个以前人们的常识。计算机的诞生就是发现了人多力量大的不足，比如高端计算人才的培养已经跟不上使用了，所以人们研究出专门帮助人们计算的机器，就是计算机的前身，到了互联网时代，人们发现完全可以让程序供应商提供解决方案，自己挑选自己合适的方案来提高自己的产出比。于是市面上就出现了各种各样的依靠程序处理信息的解决方案。

本课题研发的体育馆使用预约平台，就是提供场地预约信息处理的解决方案，它可以短时间处理完信息，并且只需要使用者动动鼠标和键盘就能获取自己需要的信息，并且这些信息都有专门的存储设备，而且数据的备份和迁移都可以设定为无人值守，从人力角度和信息处理角度以及信息安全角度，体育馆使用预约平台是完胜传统纸质操作的，所以体育馆使用预约平台就是如此的值得信赖。

## 1.3 研究内容

本文对体育馆使用预约平台的设计与实现分成六个章节进行描述。

第1章：研究体育馆使用预约平台的背景，以及开发体育馆使用预约平台的意义。

第2章：对开发体育馆使用预约平台的环境还有技术进行说明。

第3章：分析体育馆使用预约平台的可行性，性能，流程以及功能。

第4章：设计体育馆使用预约平台的功能结构，设计数据库E-R图以及对数据表的存储结构进行设计。

第5章：实现体育馆使用预约平台的功能并进行功能界面展示。

第6章：对系统测试进行阐述，以及对本系统部分功能进行检测。

# 第2章 开发环境与技术

本章节对开发体育馆使用预约平台需要搭建的开发环境，还有体育馆使用预约平台开发中使用的编程技术等进行阐述。

## 2.1 Java语言 

Java语言是当今为止依然在编程语言行业具有生命力的常青树之一。Java语言最原始的诞生，不仅仅是创造者感觉C语言在编程上面很麻烦，如果只是专注于业务逻辑的处理，会导致忽略了各种指针以及垃圾回收这些操作，导致出现问题需要解决的时间往往大于正常编程处理业务逻辑的时间，这些是非常浪费时间的。Java语言的创造者就完美的解决了这个问题，把指针处理和垃圾处理全部自动化，虽然这会损失一些性能，但是随着计算机硬件的不断发展，这些性能是可以忽略考虑的。并且C语言是针对硬件开发的语言，在符合条件的硬件上面进行编程可以最大化利用硬件的性能，但是随着硬件的变化或者操作系统的变更，如果还是用C语言的话需要对整个程序进行重新编程，只有随着市场变化而变化的语言才是符合潮流，符合生存规律的语言。Java语言的创造者就针对C语言的缺点专门开发了Java语言。让Java语言不管是在什么样的环境里都是可以运行，因为在Java语言运行外面套了一个壳，也就是虚拟机，只要是Java虚拟机能安装的电脑都可以运行Java的程序。

## 2.2 MYSQL数据库

MySQL数据库是关系型数据库的一种，也是传统的行式数据模式，获取一些数据是先一行一行的获取，然后一行一行的显示，与最近大数据兴起的列式数据库有着明显的不同。行式数据库主要是处理最重要的数据逻辑部分，并且必须是有效数据，这样每一处的数据关联都是不可损坏，如果对数据安全性比较高的肯定是需要选择MySQL数据库，列式数据库的发明仅仅是因为读取效率高，与传统的MySQL数据库比起来在数据写入方面并不会高明到哪里。MySQL虽然比起oracle或者SQL
SERVER来讲，安装包只是几十兆甚至几百兆，有点小，但是功能并不会弱到哪里，严格遵循SQL标准语法。MySQL的数据存放形式从大向小的说是数据库最大，然后是表，每个表里面存放数据是有一定的规则的，数据存放是表格形式的，也就是说有横也有竖，横着的为行，一般表示一条数据，每个表都有字段，而字段是以列的形式存在，这样能保证一条数据每一个字段对应的是相同数据类型的数据。表与表之间还可以进行关联，进行分表操作，如果一条数据相关项目属性太多，那么可以把有效的相关联系做成关联，可以设定是否唯一。

## 2.3 IDEA开发工具

IDEA是捷克共和国的Java程序员开发人员创造的一个开发软件，刚开始主要是对于用Eclipse软件他们用得不顺手，所以直接开发了这款软件。之所以不顺手原因在于没有代码提升功能，原因是Eclipse只是把代码提示作为一种插件形式的存在，如果有些程序开发人员不清楚代码提示插件可能会出问题，并且代码提示只是用来作为插件，所以功能上有所欠缺。IDEA不仅仅代码提示做的很好，在代码重构上面更上如虎添翼，程序开发人员可以选择一段代码然后IDEA就会对代码进行分解重构，有效的把代码弄得更够层次感，复用性更高，用着更简洁和方便，大大的减少了代码工作量，提升了代码开发效率。当然，IDEA对于使用者这么好，肯定也是有目的的，原因在于插件越多越友好，就需要花费大量的金钱来使用，所以说IDEA使用主要是看自己喜好。

## 2.4 Spring Boot框架

Spring
Boot是一种不需要代码生成的一种框架，并且可以不需要配置任何的XML文件就可以，因为Spring
Boot里面自带了很多接口，只需要配置不同的接口就会自动的应用并且识别需要的依赖，在配置方面非常的方便，使用起来感觉像没有用到框架的感觉。Spring
Boot有很多默认的配置文件，并且可以对默认的配置文件进行修改，可以设置为自动加载，可以对异常处理分为全局异常处理和默认异常处理。Spring
Boot使用过程中就像是使用什么直接注册什么，所谓的注册也就是在对应的类和方法上面进行一个特殊的声明即可。

# 第3章 需求分析

本文作者在确定了研究的课题之后，从各大数字图书馆下载文献来阅读，并了解同类型的网站具备的大致功能，然后与本系统用户的实际需求结合进行分析，得出本系统要研究的具体功能与性能。虽然分析系统这一阶段性工作主要是确定功能，但它却影响着后面系统开发环节的进展，它也是系统开发流程中比较重要的一个环节。

## 3.1 可行性分析

以下部分是从三个角度来进行可行性分析，确保开发成功的前提是有可行性分析，只有进行提前分析，符合程序开发流程才不至于开发过程的中断。

### 3.1.1 技术可行性

在技术实现层次，分析了好几种技术实现方法，并且都有对应的成功案例，也有很多开源模块可以进行参考，所以从技术可行性分析来讲，实现体育馆使用预约平台是没有问题的。

### 3.1.2 经济可行性

对于身为学生的开发者而言，在经济资源上面可用者很少，为了开发体育馆使用预约平台，通过从技术分析发现可以用自己用的电脑进行开发，并且学校机房的配置也可以达到要求。最重要的是技术资源一般都是开源免费使用的，因此得出结论，经济方面是具有可行性的。

### 3.1.3 操作可行性

体育馆使用预约平台的具体实现，本身参考人类的正常操作逻辑，把常用的操作习惯当做主要的导航实现，可以让使用者更快速的理解并且上手操作，实现符合逻辑的操作流程是操作可行性的具体体现。

以上就是从不同的角度来分析，确保了体育馆使用预约平台的正常开展。

## 3.2 系统流程分析

体育馆使用预约平台投入使用后，其各个功能的内部操作逻辑需要使用者通过流程图来进行了解。

1.操作流程

使用者在操作体育馆使用预约平台中，应该按照本系统提供的操作流程（图3.1即为本系统的操作流程图）进行操作，这样可以减少使用者操作中出现的错误，从而节省进入体育馆使用预约平台的时间。

![](media/image1.wmf)

图3.1 系统操作流程

2.登录流程

体育馆使用预约平台通过登录功能（图3.2即为其登录的流程）引导使用者进入指定的功能操作区，也避免非本系统的用户享受本系统提供的服务以及查看本系统提供的信息，从而保障本系统用户的安全使用。

![](media/image2.wmf)

图3.2 登录流程

3.删除信息流程

体育馆使用预约平台在经过长期使用后，会产生很多的数据信息。为了腾出存储空间存放更多的数据，本系统数据库中存储的数据，一些没有参考价值的数据需要进行删除（图3.3即为删除信息的流程），删除数据过程中，为避免误删，使用者要根据系统的提示来决定是否删除数据。

![](media/image3.wmf)

图3.3 删除信息流程

4\. 添加信息流程

体育馆使用预约平台提供可视化的功能操作区，非常方便使用者进行数据操作，当使用者往系统中录入数据时（图3.4即为添加信息的流程），本系统也会进行数据合法性的判断，符合要求的数据才能够在数据库指定表中进行登记。

![](media/image4.wmf)

图3.4 添加信息流程

## 3.3 系统性能需求

在需求分析中就应该对项目所需服务器性能进行分析，这样才符合正常的分析流程。只谈功能需求不谈性能需求，是一件很严重的事情，可能会导致使用过程中出现一系列不可预测的问题，所以性能需求也是需要考虑的重要项。

下面就是从几个方面来进行系统的性能分析，从每个角度来分析系统性能。

(1)系统数据的容量：从数据角度来分析，每个表和每个数据库，达到的数据量到一定的程度，是否需要分表或者是分库，超过了数据的设定限度，可能会导致数据反映迟钝，容错量增加。

(2)数据精度的要求：需要对需求分析里面数据设定环节，考虑相应的数据精度问题，需要发现数据是常用的精度还是非常用的精度，进而设定不同的数值。数据的精度问题，会直接导致设计的性能问题。

(3)时间响应要求：从用户提交操作，到页面反映，中间有个数据处理的问题，如果数据量大，那么考虑索引问题和分库问题，数据量再大就要考虑增加列式数据库的问题，这些都要根据数据量的增加以及逻辑的严密性来进行判断，才能符合用户的要求，毕竟响应时间太久操作起来也不舒服。

系统的性能需求从业务需求之初就能大致了解到性能需求相关的概念，再从系统性能需求来逐条实现，可以让设计的系统有使用价值。

## 3.4 系统功能需求

体育馆使用预约平台根据使用权限的角度进行功能分析，并运用用例图来展示各个权限需要操作的功能。

图3.5即为管理员用例图，管理员权限操作的功能包括对注册用户信息的管理，对场地，场地预约订单，公告，论坛帖子等信息的管理。

![](media/image5.wmf)

图3.5 管理员用例图

图3.6即为用户用例图，用户权限操作的功能包括参与论坛帖子发布与评论，查看公告，预约场地，收藏场地等。

![](media/image6.wmf)

图3.6 用户用例图

# 第4章 系统设计

系统的设计一切都是为了用户的使用，虽然用户使用过程中可能只是面对着浏览器进行各种操作，但是不代表着系统对于用户在浏览器上的操作不进行处理，所以说，设计一个系统需要考虑到方方面面。

## 4.1 功能模块划分

### 4.1.1 管理员模块功能

图4.1即为设计的管理员功能结构，管理员权限操作的功能包括对注册用户信息的管理，对场地，场地预约订单，公告，论坛帖子等信息的管理。

![](media/image7.wmf)

图4.1 管理员功能结构

### 4.1.2 用户模块功能

图4.2即为设计的用户功能结构，用户权限操作的功能包括参与论坛帖子发布与评论，查看公告，预约场地，收藏场地等。

![](media/image8.wmf)

图4.2 用户功能结构

## 4.2 数据库设计

体育馆使用预约平台运行中产生的数据需要按照提前设置的存储规则进行保存，而这个存储规则则是在数据库的设计中进行设置的。通常情况下，为了更好的配合系统运行，也要给用户带来良好的使用体验，设计一个很好的数据库是必须的，因为它能减少用户的等待时间，还可以对系统的请求在最短时间内进行响应。所以，对数据库设计时，需要花费一定的时间来分析系统对于数据存储的要求以及存储的具体数据，然后设计具体的存储规则，保证数据库能够对系统的各种数据请求进行及时回应，缩短数据处理时间，并在一定程度上降低数据冗余，节省存储空间。

### 4.2.1 E-R图

实体-联系图还有一个名称即E-R图，是Entity Relationship
Diagram各英文单词首字母的缩写，它这种概念模型通常用于对现实世界进行描述。同时它还是一种能够直观表达数据中实体，联系，属性的有效手段。绘制E-R图能够选择的工具也有很多，但是Office
Visio 这款软件在E-R图的绘制上一般都是作为首选工具，因为它是基于可视化处理，使用它创建E-R图非常简单。使用基本的E-R图构成元素，比如椭圆，菱形，矩形，还有实线段来表达对应的信息，椭圆代表属性，即实体的特征，矩形代表实体，即数据库中的一个具体数据表，菱形代表实体中相互关系，实线段主要是完成椭圆，矩形，菱形的连接，基于这样的方式即可完成对本系统的E-R图进行完整绘制。

（1）图4.4即为场地这个实体所拥有的属性值。

![](media/image9.wmf)

图4.4 场地实体属性图

（2）图4.5即为用户这个实体所拥有的属性值。

![](media/image10.wmf)

图4.5 用户实体属性图

（3）图4.6即为公告这个实体所拥有的属性值。

![](media/image11.wmf)

图4.6 公告实体属性图

4.  图4.7即为管理员这个实体所拥有的属性值。

![](media/image12.wmf)

图4.7 管理员实体属性图

5.  图4.8即为上面介绍的实体中存在的联系。

![](media/image13.wmf)

图4.8 实体间关系E-R图

### 4.2.2 数据库表设计

本小节主要任务即是根据上述内容进行数据存储结构的设计，也就是在数据库中设计存放本系统的数据的数据表，设计数据表时，需要对各个字段进行确定，通常来说，一个实体与一张数据表相对应，实体的属性就用来表示字段名称，不同的字段表示的数据类型以及取值都不相同，这里需要根据系统实际数据的情况进行设置，同时也需要在具体表中确定该表的主键，以及该表各个字段是否能够保持空等进行说明，设计完成一张数据表的结构之后，在保存时同样要命名，尽量选择英文名称进行命名并保存，方便今后系统对数据表进行数据存储访问时，在提高数据存储效率的同时，还不容易导致系统出错。接下来就对设计的数据表进行展示。

**表4.1 用户表**

  ------------------- ----------------------------- --------------- -----
  字段                注释                          类型            空

  id (主键)           主键                          int(11)         否

  username            账户                          varchar(200)    是

  password            密码                          varchar(200)    是

  yonghu_name         用户姓名                      varchar(200)    是

  yonghu_phone        用户手机号                    varchar(200)    是

  yonghu_id_number    用户身份证号                  varchar(200)    是

  yonghu_photo        用户头像                      varchar(200)    是

  sex_types           性别                          int(11)         是

  yonghu_email        电子邮箱                      varchar(200)    是

  new_money           余额                          decimal(10,2)   是

  create_time         创建时间                      timestamp       是
  ------------------- ----------------------------- --------------- -----

**表4.2 场地表**

  ---------------------- -------------------------- --------------- -----
  字段                   注释                       类型            空

  id (主键)              主键                       int(11)         否

  changdi_uuid_number    场地编号                   varchar(200)    是

  changdi_name           场地名称                   varchar(200)    是

  changdi_photo          场地照片                   varchar(200)    是

  changdi_types          场地类型                   int(11)         是

  changdi_old_money      场地原价                   decimal(10,2)   是

  changdi_new_money      场地现价                   decimal(10,2)   是

  shijianduan            时间段                     varchar(200)    是

  shijianduan_ren        人数                       int(11)         是

  changdi_clicknum       点击次数                   int(11)         是

  banquan_types          半全场                     int(11)         是

  shangxia_types         是否上架                   int(11)         是

  tuijian                推荐吃饭地点               varchar(200)    是

  changdi_delete         逻辑删除                   int(11)         是

  changdi_content        场地简介                   text            是

  create_time            创建时间                   timestamp       是
  ---------------------- -------------------------- --------------- -----

**表4.3 场地收藏表**

  ---------------------------- ------------------------ ----------- -----
  字段                         注释                     类型        空

  id (主键)                    主键                     int(11)     否

  changdi_id                   场地                     int(11)     是

  yonghu_id                    用户                     int(11)     是

  changdi_collection_types     类型                     int(11)     是

  insert_time                  收藏时间                 timestamp   是

  create_time                  创建时间                 timestamp   是
  ---------------------------- ------------------------ ----------- -----

**表4.4 场地预约表**

  ----------------------------- ------------------- --------------- -----
  字段                          注释                类型            空

  id (主键)                     主键                int(11)         否

  changdi_order_uuid_number     订单号              varchar(200)    是

  changdi_id                    场地                int(11)         是

  yonghu_id                     用户                int(11)         是

  changdi_order_true_price      实付价格            decimal(10,2)   是

  changdi_order_types           订单类型            int(11)         是

  shijianduan                   预约时间段          varchar(200)    是

  buy_time                      预约日期            date            是

  insert_time                   订单创建时间        timestamp       是

  create_time                   创建时间            timestamp       是
  ----------------------------- ------------------- --------------- -----

**表4.5 论坛表**

  -------------------- ----------------------------- -------------- -----
  字段                 注释                          类型           空

  id (主键)            主键                          int(11)        否

  forum_name           帖子标题                      varchar(200)   是

  yonghu_id            用户                          int(11)        是

  users_id             管理员                        int(11)        是

  forum_content        发布内容                      text           是

  super_ids            父id                          int(11)        是

  forum_types          帖子类型                      int(11)        是

  forum_state_types    帖子状态                      int(11)        是

  insert_time          发帖时间                      timestamp      是

  update_time          修改时间                      timestamp      是

  create_time          创建时间                      timestamp      是
  -------------------- ----------------------------- -------------- -----

**表4.6 公告信息表**

  ------------------ -------------------------------- -------------- -----
  字段               注释                             类型           空

  id (主键)          主键                             int(11)        否

  gonggao_name       公告名称                         varchar(200)   是

  gonggao_photo      公告图片                         varchar(200)   是

  gonggao_types      公告类型                         int(11)        否

  insert_time        公告发布时间                     timestamp      是

  gonggao_content    公告详情                         text           是

  create_time        创建时间                         timestamp      是
  ------------------ -------------------------------- -------------- -----

**表4.7 管理员表**

  -------------- -------------------------------- ----------------- ------
  字段           注释                             类型              空

  id (主键)      主键                             bigint(20)        否

  username       用户名                           varchar(100)      否

  password       密码                             varchar(100)      否

  role           角色                             varchar(100)      是

  addtime        新增时间                         timestamp         否
  -------------- -------------------------------- ----------------- ------

[]{#__RefHeading___Toc26881 .anchor}**设计与**

编程人员在搭建的开发环境中，运用编程技术实现本系统设计的各个操作权限的功能。在本节中，就展示部分操作权限的功能与界面。

## 5.1 管理员后台功能实现

### 5.1.1 论坛管理

图5.1
即为编码实现的论坛管理界面，管理员在该界面中查看论坛回复信息，修改论坛帖子内容，可以删除论坛帖子。论坛信息包含帖子标题，用户姓名，用户手机号，用户身份证，查询的时候可以通过这些信息查询出来结果，添加内容的时候需要输入帖子类型，帖子标题，发布内容。

![](media/image14.png){width="5.759722222222222in"
height="2.747916666666667in"}

图5.1 论坛管理界面

管理员添加论坛：

\@RequestMapping(**\"/save\"**)\
**public** R save(@RequestBody ForumEntity forum, HttpServletRequest
request){\
***logger***.debug(**\"save方法:,,Controller:{},,forum:{}\"**,**this**.getClass().getName(),forum.toString());\
\
String role =
String.*valueOf*(request.getSession().getAttribute(**\"role\"**));\
**if**(StringUtil.*isEmpty*(role))\
**return** R.*error*(511,**\"权限为空\"**);\
**else if**(**\"用户\"**.equals(role))\
forum.setYonghuId(Integer.*valueOf*(String.*valueOf*(request.getSession().getAttribute(**\"userId\"**))));\
**else if**(**\"管理员\"**.equals(role))\
forum.setUsersId(Integer.*valueOf*(String.*valueOf*(request.getSession().getAttribute(**\"userId\"**))));\
\
Wrapper\<ForumEntity\> queryWrapper = **new**
EntityWrapper\<ForumEntity\>()\
.eq(**\"forum_name\"**, forum.getForumName())\
.eq(**\"yonghu_id\"**, forum.getYonghuId())\
.eq(**\"users_id\"**, forum.getUsersId())\
.eq(**\"super_ids\"**, forum.getSuperIds())\
.eq(**\"forum_types\"**, forum.getForumTypes())\
.eq(**\"forum_state_types\"**, forum.getForumStateTypes())\
;\
\
***logger***.info(**\"sql语句:\"**+queryWrapper.getSqlSegment());\
ForumEntity forumEntity = **forumService**.selectOne(queryWrapper);\
**if**(forumEntity==**null**){\
forum.setInsertTime(**new** Date());\
forum.setCreateTime(**new** Date());\
**forumService**.insert(forum);\
**return** R.*ok*();\
}**else** {\
**return** R.*error*(511,**\"表中有相同数据\"**);\
}\
}

### 5.1.2 用户管理

图5.2
即为编码实现的用户管理界面，管理员在该界面中为注册系统的用户重置密码，更改用户的头像，电子邮箱等基础信息，删除需要删除的用户。用户信息包含账号，密码，手机号，身份证，头像，性别，电子信箱，余额等。查询的时候只需要提供用户姓名，手机号，身份证就可以查询。

![](media/image15.png){width="5.759722222222222in"
height="2.747916666666667in"}

图5.2 用户管理界面

用户添加：

\@RequestMapping(**\"/save\"**)\
**public** R save(@RequestBody YonghuEntity yonghu, HttpServletRequest
request){\
***logger***.debug(**\"save方法:,,Controller:{},,yonghu:{}\"**,**this**.getClass().getName(),yonghu.toString());\
\
String role =
String.*valueOf*(request.getSession().getAttribute(**\"role\"**));\
**if**(StringUtil.*isEmpty*(role))\
**return** R.*error*(511,**\"权限为空\"**);\
\
Wrapper\<YonghuEntity\> queryWrapper = **new**
EntityWrapper\<YonghuEntity\>()\
.eq(**\"username\"**, yonghu.getUsername())\
.or()\
.eq(**\"yonghu_phone\"**, yonghu.getYonghuPhone())\
.or()\
.eq(**\"yonghu_id_number\"**, yonghu.getYonghuIdNumber())\
;\
\
***logger***.info(**\"sql语句:\"**+queryWrapper.getSqlSegment());\
YonghuEntity yonghuEntity = **yonghuService**.selectOne(queryWrapper);\
**if**(yonghuEntity==**null**){\
yonghu.setCreateTime(**new** Date());\
yonghu.setPassword(**\"123456\"**);\
**yonghuService**.insert(yonghu);\
**return** R.*ok*();\
}**else** {\
**return**
R.*error*(511,**\"账户或者用户手机号或者用户身份证号已经被使用\"**);\
}\
}

### 5.1.3 场地管理

图5.3
即为编码实现的场地管理界面，管理员在该界面中可以更改场地信息，新增新的场地信息，删除需要删除的场地资料。场地搜索只需要输入场地名称，场地类型就可以查到结果。新增场地则需要输入场地编号，场地名称，照片，类型，原价，现价，时间段，半全场，推荐吃饭地点，场地介绍等。

![](media/image16.png){width="5.759722222222222in"
height="2.747916666666667in"}

图5.3 场地管理界面

场地修改：

\@RequestMapping(**\"/update\"**)\
**public** R update(@RequestBody ChangdiEntity changdi,
HttpServletRequest request){\
***logger***.debug(**\"update方法:,,Controller:{},,changdi:{}\"**,**this**.getClass().getName(),changdi.toString());\
String role =
String.*valueOf*(request.getSession().getAttribute(**\"role\"**));\
Wrapper\<ChangdiEntity\> queryWrapper = **new**
EntityWrapper\<ChangdiEntity\>()\
.notIn(**\"id\"**,changdi.getId())\
.andNew()\
.eq(**\"changdi_uuid_number\"**, changdi.getChangdiUuidNumber())\
.eq(**\"changdi_name\"**, changdi.getChangdiName())\
.eq(**\"changdi_types\"**, changdi.getChangdiTypes())\
.eq(**\"shijianduan\"**, changdi.getShijianduan())\
.eq(**\"shijianduan_ren\"**, changdi.getShijianduanRen())\
.eq(**\"changdi_clicknum\"**, changdi.getChangdiClicknum())\
.eq(**\"banquan_types\"**, changdi.getBanquanTypes())\
.eq(**\"shangxia_types\"**, changdi.getShangxiaTypes())\
.eq(**\"tuijian\"**, changdi.getTuijian())\
.eq(**\"changdi_delete\"**, changdi.getChangdiDelete())\
;\
\
***logger***.info(**\"sql语句:\"**+queryWrapper.getSqlSegment());\
ChangdiEntity changdiEntity =
**changdiService**.selectOne(queryWrapper);\
**if**(**\"\"**.equals(changdi.getChangdiPhoto()) \|\|
**\"null\"**.equals(changdi.getChangdiPhoto())){\
changdi.setChangdiPhoto(**null**);\
}\
**if**(changdiEntity==**null**){\
**changdiService**.updateById(changdi);*//根据id更新\
***return** R.*ok*();\
}**else** {\
**return** R.*error*(511,**\"表中有相同数据\"**);\
}\
}

### 5.1.4 场地订单管理

图5.4
即为编码实现的场地订单管理界面，管理员在该界面中对用户预约的场地订单进行查询，更改等，查看场地预约订单的预约时间段信息以及订单类型等信息。可以通过输入场地名称，类型，用户姓名，用户手机号，用户身份证号来进行查询场地预约信息。

![](media/image17.png){width="5.759722222222222in"
height="2.747916666666667in"}

图5.4 场地订单管理界面

场地订单列表：

*/\*\*\
\* 后端列表\
\*/\
*\@RequestMapping(**\"/page\"**)\
**public** R page(@RequestParam Map\<String, Object\> params,
HttpServletRequest request){\
***logger***.debug(**\"page方法:,,Controller:{},,params:{}\"**,**this**.getClass().getName(),JSONObject.*toJSONString*(params));\
String role =
String.*valueOf*(request.getSession().getAttribute(**\"role\"**));\
**if**(StringUtil.*isEmpty*(role))\
**return** R.*error*(511,**\"权限为空\"**);\
**else if**(**\"用户\"**.equals(role))\
params.put(**\"yonghuId\"**,request.getSession().getAttribute(**\"userId\"**));\
**if**(params.get(**\"orderBy\"**)==**null** \|\|
params.get(**\"orderBy\"**)==**\"\"**){\
params.put(**\"orderBy\"**,**\"id\"**);\
}\
PageUtils page = **changdiOrderService**.queryPage(params);\
\
*//字典表数据转换\
*List\<ChangdiOrderView\> list
=(List\<ChangdiOrderView\>)page.getList();\
**for**(ChangdiOrderView c:list){\
*//修改对应字典表字段\
***dictionaryService**.dictionaryConvert(c, request);\
}\
**return** R.*ok*().put(**\"data\"**, page);\
}

### **5.1.5 公告信息管理**

图5.5
即为编码实现的公告信息管理界面，管理员在该界面中负责发布公告信息，更改公告信息的部分信息，删除需要删除的公告。

![](media/image18.png){width="5.759722222222222in"
height="2.747916666666667in"}

图5.5 公告信息管理界面

## 5.2 用户前台功能实现

### 5.2.1 场地信息

图5.6
即为编码实现的场地信息界面，用户在该界面中对场地进行预定，或收藏场地方便下次查看场地信息。可以看到的场地名称，类型，原价，现价，人数，点击次数，半全场，推荐吃饭地点，订购日期，订购时间段详情介绍。

![](media/image19.png){width="5.759722222222222in"
height="2.747916666666667in"}

图5.6 场地信息界面

场地预约：

\@RequestMapping(**\"/add\"**)\
**public** R add(@RequestBody ChangdiOrderEntity changdiOrder,
HttpServletRequest request){\
***logger***.debug(**\"add方法:,,Controller:{},,changdiOrder:{}\"**,**this**.getClass().getName(),changdiOrder.toString());\
String role =
String.*valueOf*(request.getSession().getAttribute(**\"role\"**));\
**if**(**\"用户\"**.equals(role)){\
ChangdiEntity changdiEntity =
**changdiService**.selectById(changdiOrder.getChangdiId());\
**if**(changdiEntity == **null**){\
**return** R.*error*(511,**\"查不到该场地\"**);\
}\
**if**(changdiEntity.getChangdiNewMoney() == **null**){\
**return** R.*error*(511,**\"场地价格不能为空\"**);\
}\
\
Integer userId = (Integer)
request.getSession().getAttribute(**\"userId\"**);\
YonghuEntity yonghuEntity = **yonghuService**.selectById(userId);\
**if**(yonghuEntity == **null**)\
**return** R.*error*(511,**\"用户不能为空\"**);\
**if**(yonghuEntity.getNewMoney() == **null**)\
**return** R.*error*(511,**\"用户金额不能为空\"**);\
**double** balance = yonghuEntity.getNewMoney() -
changdiEntity.getChangdiNewMoney();*//余额\
***if**(balance\<0)\
**return** R.*error*(511,**\"余额不够支付\"**);\
\
List\<Integer\> changdiOrderTypes = **new** ArrayList\<\>();\
changdiOrderTypes.add(2);\
String buyTime = **new**
SimpleDateFormat(**\"yyyy-MM-dd\"**).format(changdiOrder.getBuyTime());\
List\<ChangdiOrderEntity\> changdiOrderEntities =
**changdiOrderService**.selectList(**new**
EntityWrapper\<ChangdiOrderEntity\>().notIn(**\"changdi_order_types\"**,
changdiOrderTypes).eq(**\"shijianduan\"**,
changdiOrder.getShijianduan()).eq(**\"buy_time\"**,buyTime));\
\
**if**(changdiOrderEntities != **null** &&
changdiOrderEntities.size()\>0)\
**return** R.*error*(511,buyTime+**\" 那天的
\"**+changdiOrder.getShijianduan()+**\" 的时间段已经被预约了\"**);\
\
changdiOrder.setYonghuId(userId); *//设置订单支付人id\
*changdiOrder.setInsertTime(**new** Date());\
changdiOrder.setCreateTime(**new** Date());\
changdiOrder.setChangdiOrderTypes(1);\
changdiOrder.setChangdiOrderTruePrice(changdiEntity.getChangdiNewMoney());\
changdiOrder.setChangdiOrderUuidNumber(String.*valueOf*(**new**
Date().getTime()));\
**changdiOrderService**.insert(changdiOrder);*//新增订单\
*yonghuEntity.setNewMoney(balance);*//设置金额\
***yonghuService**.updateById(yonghuEntity);\
**return** R.*ok*();\
}**else**{\
**return** R.*error*(511,**\"您没有权限支付订单\"**);\
}\
}

### 5.2.2 在线论坛

图5.7
即为编码实现的在线论坛界面，用户在该界面中对论坛所有帖子进行查看，查看帖子之后可以发布帖子评论，用户也能点击发布帖子链接进入新界面发布自己的帖子。主要可以看到帖子标题，发布人权限，发布时间，可以对这些帖子进行回复操作。

![](media/image20.png){width="5.759722222222222in"
height="2.747916666666667in"}

图5.7 在线论坛界面

### 5.2.3 场地预约

图5.8
即为编码实现的场地预约界面，用户在该界面中浏览已经预约的场地。如果存在误操作，用户可以取消预约的场地。在个人中心我的场地预约里面，有全部场地预约，已使用，取消预约，已预约这几个状态的预约信息，已经取消预约的不能再取消，已预约尚未取消预约的才可以取消预约。

![](media/image21.png){width="5.759722222222222in"
height="2.747916666666667in"}

图5.8 场地预约界面

我的预约:

*/\*\*\
\* 前端列表\
\*/\
*\@IgnoreAuth\
\@RequestMapping(**\"/list\"**)\
**public** R list(@RequestParam Map\<String, Object\> params,
HttpServletRequest request){\
***logger***.debug(**\"list方法:,,Controller:{},,params:{}\"**,**this**.getClass().getName(),JSONObject.*toJSONString*(params));\
\
*// 没有指定排序字段就默认id倒序\
***if**(StringUtil.*isEmpty*(String.*valueOf*(params.get(**\"orderBy\"**)))){\
params.put(**\"orderBy\"**,**\"id\"**);\
}\
PageUtils page = **changdiOrderService**.queryPage(params);\
\
*//字典表数据转换\
*List\<ChangdiOrderView\> list
=(List\<ChangdiOrderView\>)page.getList();\
**for**(ChangdiOrderView c:list)\
**dictionaryService**.dictionaryConvert(c, request);
*//修改对应字典表字段\
***return** R.*ok*().put(**\"data\"**, page);\
}

[]{#__RefHeading___Toc22282 .anchor}**6章
软件**当系统测试环节开始的时候，也就说明对于系统的编码已经弄得大致通顺了，剩下来需要对一些模块和功能进行测试，这个环节就叫系统测试。在程序开发过程中，系统测试是整个开发过程必不可少的一个环节。原因很简单，系统开发人员在面对各种需求需要对各个模块进行编码，开发人员编写过程中，对于程序的理解全部都在编码里面，一人计短，当一个人去做一些事情的时候，把自己的理解变成成果，很有可能会出现理解偏差，甚至是理解错误，这个在程序开发过程中很常见。程序开发人员在面对复杂的逻辑，没有想象中的多么清晰，开发过程就是面对着一堆代码，不断的变换数据类型，并且对各种操作用计算机编程语言进行实现，这些很容易实现程序开发人员的想法，但是如果是比较复杂的逻辑，很可能会出现各种问题，这是无法避免的。所以说，需要额外的人员进行系统测试编写，不要站在程序开发人员的角度去思考问题，要站在用户使用的角度去发现问题，这样开发与测试的分离，有助于系统开发的强壮，让程序表达的更完美一些。之所以把系统测试安排到程序开发过程中的原因在于，当测试发现问题，就可以直接反馈到程序开发人员手里，可以以最快的时间解决问题，这样能大大的提高开发效率。总的来说，在整个软件开发过程中，系统测试这个环节也必须要重视的，所以必须在系统测试环节做好应该做好的事情，让程序开发从开始到结束都有一个完美的流程。

## 6.1 测试用例

本节主要选择一些功能进行具体测试描述，在相应的功能里面，根据不同的合法与不合法条件输入看程序是否设定的有相关的判断，能否达到使用效果。以下会描述部分功能的测试过程和结果。

1.登录功能测试

登录是一个常规功能，虽然是常规功能，但是用处很大，可以拒绝非法用户访问，只有合法用户才可以访问对应的功能，这样能保证程序设定的功能符合安全性要求。

**表6.1 管理员登录功能测试表**

  ---------------- ------------------ -----------------------------------
  管理员账号       管理员密码         结果

  uuu              uuu                成功登录系统

  yyy              uuu                登录失败

  uuu              yyy                登录失败
  ---------------- ------------------ -----------------------------------

只有正确的账号密码才会进行跳转到对应的功能区，如果输入的账号密码不对的话，肯定会有相关提示，用来提示操作人员注意输入正确的账号密码，这样有助于提高用户体验。这里以使用者提交错误的账号为"yyy",正确的密码为"uuu"为例进行测试，具体反馈结果看下面。

![](media/image22.png){width="5.759722222222222in"
height="2.747916666666667in"}

图6.1 登录失败提示

2\. 修改密码功能测试

任何用户角色都有安全性要求，那么对应的密码最好是经常更改，只有经常更改才会降低坏人的有机可乘几率，达到密码保护的最低要求，当然，如果用户登录人离开了，为了防止其他人乘机篡改密码，那么也会设定旧密码要求，只有输入正确的旧密码才可以进行密码的修改。下面就是测试过程。

**表6.2 修改密码功能测试表**

  ------------------ ----------------------------- ----------------------
  之前的旧密码       设置的新密码                  结果

  uuu                yyy                           成功修改密码

  hhh                yyy                           修改密码失败

  uuu                                              修改密码失败
  ------------------ ----------------------------- ----------------------

不管是旧密码错误还是新密码不合规，都会提示相应的要求，下面就是关于旧密码输入错误的提示。

![](media/image23.png){width="5.759722222222222in"
height="2.747916666666667in"}

图6.2 错误的旧密码反馈提示

3\. 公告功能测试

公告信息属于管理员发布的，如果不输入则不让提交，输入了才可以提交。下面就是测试过程。

**表6.3 公告功能测试表**

  ------------------------------------ ----------------------------------------------------------
  公告信息                             结果

  不输入公告名称，公告图片，公告类型   提示公告名称不能为空，公告图片不能为空，公告类型不能为空

  全部输入不留空                       操作成功
  ------------------------------------ ----------------------------------------------------------

不输入任何信息就提交公告会会提示。下图就是提示。

![](media/image24.png){width="4.559722222222222in"
height="2.8472222222222223in"}

图6.3 不输入直接提交的反馈提示

4\. 论坛功能测试

论坛信息属于管理员发布的，如果不输入则不让提交，输入了才可以提交。下面就是测试过程。

**表6.4 论坛功能测试表**

  ------------------------------------ ------------------------------------------
  论坛信息                             结果

  不输入帖子类型，帖子标题，发布内容   提示帖子类型，帖子标题，发布内容不能为空

  全部输入不留空                       操作成功
  ------------------------------------ ------------------------------------------

不输入任何信息就提交论坛会提示。下图就是提示。

![](media/image25.png){width="6.2972222222222225in"
height="2.5854166666666667in"}

图6.4 不输入直接提交的反馈提示

5\. 用户功能测试

管理员添加用户信息，必须都输入，哪个不输入就提示哪个不能为空。下面就是测试过程。

**表6.4 用户功能测试表**

  -------------------------------- --------------------------------------
  用户信息                         结果

  都不输入                         都提示不能为空

  全部输入不留空                   操作成功
  -------------------------------- --------------------------------------

不输入任何信息就提交会提示。下图就是提示。

![](media/image26.png){width="6.2972222222222225in"
height="4.768055555555556in"}

图6.5 不输入直接提交的反馈提示

## 6.2 测试结果

对体育馆使用预约平台进行了各种检测，包含功能检测和性能检测，甚至是系统的操作性方面也进行了检测，以及兼容性检测，通过各方面检测结果来判定系统是符合设计目标，达到开发预期。系统是可以实现所开发的功能，并且在扩展性或者是稳定性上面，也有很好的表现，能完全的满足用户需求。

# 结 论

由于本人学习的是计算机方面的专业，对于计算机软件方面的相关知识也进行过课堂上的学习以及课后的实际操作练习，因此，对于开发一款已经确定了课题的体育馆使用预约平台，从功能需求，功能模块划分，数据库的选择，数据库的设计，编程语言的确定，系统界面的布局和设计等知识，我都有个大致的思路。所以，在参照软件设计思想以及设计流程的基础上，我运用已经具备的理论知识，加上后期从网络渠道获取的相关技术知识，我能够根据制定的系统开发时间安排完成各个阶段性的开发任务。并能够在系统完成开发后期，编写相应的系统文档。

体育馆使用预约平台制作期间，我也遇到过一些难题，在最开始的时候，我并不知道该系统具体要设计几个功能模块，以及数据表需要设计几张表，还有对于开发技术的深度理论学习还不充分等，值得庆幸的是，我在面临这些困难时，我能够通过网络或者通过学院提供的图书馆寻求解决办法。比如在不知道具体功能的情况下，我从网上下载了很多的与体育馆使用预约平台相关的程序，分析了它们的功能之后，我再结合即将开发的体育馆使用预约平台进行综合分析，选取了适合体育馆使用预约平台的功能部分，再结合实际情况以及使用者的需求确定本系统功能。对于数据表的设计，我先是在图书馆借阅了一本数据库方面的书籍进行查看，然后查看相似系统对于数据表的结构设计等知识，然后在本系统功能确定的情况下，结合本系统设计了配套的数据表，对于难度最大的开发技术部分，我花费了很多的时间研究网络上的相似系统的功能模块上的代码，一般都是对基础数据的增加，更新，查询或修改方面的代码，然后把本系统能够运用的代码部分在简单更改后进行使用，在完成了一个功能模块以及又一个功能模块之后，又经过了简单的测试工作，最终呈现出一个完整的能够解决用户实际问题的体育馆使用预约平台。该系统唯一不足的就是代码方面还有很多重复的部分，不够精简，还有用户操作本系统，对于用户的误操作行为，本系统还不能及时反馈，这也是一大缺点。

体育馆使用预约平台完成了，其相应的配套文档也需要进行编写，该文档主要描述体育馆使用预约平台是如何进行分析，设计以及实现的，让其他阅读本文档的人增加对该系统的了解，编写文档过程中，由于自己平时对于办公软件的操作不是很频繁，根据学院要求的文档排版格式进行编辑也花了很多时间，在不断学习排版技巧以及对本系统配套文档的反复修改之后，最终在学院规定的时间内进行了文档定稿。

毕业项目各个工作进行到此，我也是收获颇丰，正因为自己努力学习知识，积极寻求解决办法，才让我能够提交一个完整的作品。制作毕业项目让我又得到了成长，不仅是专业知识的增加，也包括解决问题的能力得到了提高，很感谢学院给的制作毕业项目的机会。

# 参考文献

\[1\]岳增霖,金浩轩,张伟豪,汤毅.
基于Onenet及微信小程序的校园运动场地预约系统\[J\].
电子产品世界,2019,26(12):55-59.

\[2\]刘美琪,李婉萍,孙方斌,付国强. 基于Web的体育场馆预约系统\[J\].
电子科技,2016,29(04):104-106+110.

\[3\]余涛.计算机软件开发中Java编程语言的应用研究\[J\].信息记录材料,2020,21(01):113-115.

\[4\]王子虎,胡丽珍.基于计算机软件安全开发的JAVA编程语言研究\[J\].数字技术与应用,2019,37(12):133-134.

\[5\]刘星淇.Java编程语言的特点与应用分析\[J\].通讯世界,2019,26(09):149-150.

\[6\]张云健.计算机软件Java编程特点及其技术应用\[J\].信息与电脑(理论版),2019(13):97-98.

\[7\]张振超,吴杰,陈序蓬.浅谈Java中Mysql数据库的连接与操作\[J\].信息记录材料,2020,21(02):144-145.

\[8\]范开勇,陈宇收.MySQL数据库性能优化研究\[J\].中国新通信,2019,21(01):57.

\[9\]丁佳.基于JSP+MySQL的用户登录系统SQL注入实例及防范\[J\].网络安全技术与应用,2020(09):49-51.

\[10\]王丹,孙晓宇,杨路斌,高胜严.基于SpringBoot的软件统计分析系统设计与实现\[J\].软件工程,2019,22(03):40-42.

\[11\]张峰.应用SpringBoot改变web应用开发模式\[J\].科技创新与应用,2017(23):193-194.

\[12\]谢志坚.计算机应用软件开发技术支撑思考\[J\].电子世界,2020(15):53-54.

\[13\]姬晓鹏.计算机软件开发技术与设计探究\[J\].电子测试,2020(16):133-134.

\[14\]Raffi Khatchadourian.Automated refactoring of legacy Java software
to enumerated types\[J\].Automated Software Engineering,2017,24(4).

\[15\]Ben White.Marx and Chayanov at the margins:understanding agrarian
change in Java\[J\].The Journal of Peasant Studies,2018,45(5-6).

[]{#__RefHeading___Toc10420 .anchor}**致 谢**

也许是大学校园在管理上比较开放，学习知识时不像高中时期那样一整天都在学习，而是一天当中抽出部分时间安排学习，其余的时间就可以自由安排，可以去社会上参加实践，可以在学校的图书馆阅读书籍，丰富自己的知识，也可以加入学校的社团进行个人能力的锻炼等等，加上学院的学生都来自全国各地，大家的风俗习惯都有些不一样，这样同学之间也有更多的话题进行畅聊。基于这些原因，我觉得我的性格也逐渐变得开朗起来，正因为如此，我很快乐的度过了大学四年时光。然而，我们都要面临毕业，同学间，师生间也将面临分离，我们都会离开学校，进入社会这样的大环境学习并生活。虽然很不舍，但这也是人生成长中必经的阶段！

临走之际，对这几年的大学生活简单的进行了回想，发现自己学到的专业知识也增加了很多，在本专业上，自己也得到了一定的实操能力锻炼。这些成长都是我们的专业老师带来的，他们这几年辛苦教学，我们也从中获取了许多的专业知识，提高了个人的专业方面的能力，非常感谢他们。

还有一位老师也需要在此特别感谢，即论文指导老师。可以说最后这一年，跟指导老师接触比较多，指导老师在本专业上，非常全能，在我进行本课题的任务期间，导师给予我全面的指导，也能根据我的不足之处推荐合适的书籍让我查看，让我的能力得以提升，继而可以从容面对开发期间遇到的困难。

另外，我也要感谢我的寝室室友，还有我们班上的同学，从接到毕业项目任务之后，我们常常谈论各自课题进展的情况以及面临的问题，也经常互相鼓励对方要积极认真面对毕业项目，这种陪伴，让我在制作毕业项目期间并没有产生过多的焦虑，非常感谢他们。

最后时刻，我也要对我的大学校园表达谢意，我的大学校园是一个非常美丽的地方，而我这几年，在这么优美的环境下学习知识，我已经感到非常幸福。希望在今后能看到我的校园在众多师生共同努力下变得强大，校园的环境也将变得更加美丽。


### 0139springboot体育馆使用预约平台的设计与实现 项目图片
![图片](/images/0139springbootimg_014.jpg)
![图片](/images/0139springbootimg_015.jpg)
![图片](/images/0139springbootimg_001.jpg)
![图片](/images/0139springbootimg_017.jpg)
![图片](/images/0139springbootimg_003.jpg)
![图片](/images/0139springbootimg_002.jpg)
![图片](/images/0139springbootimg_016.jpg)
![图片](/images/0139springbootimg_012.jpg)
![图片](/images/0139springbootimg_006.jpg)
![图片](/images/0139springbootimg_007.jpg)
![图片](/images/0139springbootimg_013.jpg)
![图片](/images/0139springbootimg_005.jpg)
![图片](/images/0139springbootimg_011.jpg)
![图片](/images/0139springbootimg_010.jpg)
![图片](/images/0139springbootimg_004.jpg)
![图片](/images/0139springbootimg_009.jpg)
![图片](/images/0139springbootimg_021.jpg)
![图片](/images/0139springbootimg_020.jpg)
![图片](/images/0139springbootimg_008.jpg)
![图片](/images/0139springbootimg_022.jpg)
![图片](/images/0139springbootimg_023.jpg)
![图片](/images/0139springbootimg_026.jpg)
![图片](/images/0139springbootimg_024.jpg)
![图片](/images/0139springbootimg_018.jpg)
![图片](/images/0139springbootimg_019.jpg)
![图片](/images/0139springbootimg_025.jpg)








