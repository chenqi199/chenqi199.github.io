# 0060springboot基于B2B平台的医疗病历交互系统


# [0060springboot基于B2B平台的医疗病历交互系统](https://github.com/GraduationProject-springboot/0060springboot)

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

# [项目清单](https://chenqi1990.site) 包安装运行

### [github 项目仓库](https://github.com/GraduationProject-springboot/allSpringbootProjects) 开源仅有后端代码




# 绪论
计算机已经从科研院所，大中型企业，走进了平常百姓家，Internet遍及世界各地，在网上能够用计算机进行文字草拟、修改、打印清样、文件登陆、检索、综合统计、分类、数据库管理等，用科学的方法将无序的信息进行加工整理，组成有序的、方便存储和利用的艺术科研共享信息已经成为流行。计算机技术、网络技术和信息技术的发展，越来越多地改善这现代人的工作、生活。基于B2B平台的医疗病历交互系统是计算机技术和网络迅速发展的一个学习信息应用解决方案。基于B2B平台的医疗病历交互系统将Internet网络技术与现代管理观念相融合，针对信息技术的特点对基于B2B平台的医疗病历交互系统进行规划和重构，对学习信息流进行优化及合理配置，生成动态的、安全的、专有的数字化信息源，将学习体系全面自动化，流程化，数字化。以此为桥梁，横向连接学习信息系统，从而更明确、更有效地支持学习信息的管理和决策。目前社会已经进入了信息时代，社会的各个领域由于信息技术革命，都发生了改天换地的变化，紧跟时代的步伐是每个用户的发展所趋，提高各个用户现代化的管理能力，来适应整个科技社会的变化和发展。用户对信息需求的增长，使计算机、网络技术已经融合到各种用户的平常工作当中。本文研究了基于B2B平台的医疗病历交互系统，从而加快了学习信息化建设的步伐。
## 1.1 选题的依据及意义
信息技术的发展，带来机遇的同时，也使学习信息管理工作面临严峻的挑战。因为，在当前互联网开放式环境下，传统的学习信息管理模式是以资金运动为对象的，它存在许多局限性，在当前的环境下，已经很难再适应用户管理的要求，可以说，传统的学习信息管理模式，不仅不能适合用户的发展，也已经远远不能够适应当前社会发展新形势的要求。在互联网技术还没有得到广泛应用的早期，各用户信息之间的交流、基于B2B平台的医疗病历交互系统的处理都是人工操作完成的，随着社会进入信息时代和社会生活的快节奏化，在传统的学习信息管理中，需要经过若干道手续，整个过程都需要手工操作，效率十分低下。旧的学习信息的管理方法早就不能满足用户对大量的学习信息的快速处理与统计的需求，不能适应时代的发展趋势，且由于他们之间关联复杂，统计和查询的方式各不相同；且会出现信息的重复传递问题，因此该过程必须实现信息化，于是需要一种新的技术改善现状，因此基于B2B平台的医疗病历交互系统在适应时代发展需求中产生。。 
## 1.2 国内外现状研究
国内目前已有很多企业实现了信息化管理，建立了基于内部的局域网系统，外部和因特网相连，硬件设施也是非常完备。另外在软件应用方面，我国很多软件开发公司已开发了各种各样的学习信息管理系统，不过这些学习信息管理系统很多是基于当前国内的学习信息管理制度，没有实现特别强大的功能应用，尚未能够受到国际上的认可，暂时没有实现国际化标准的要求。基于B2B平台的医疗病历交互系统怎么去面对国际化的发展要求，将会是我国面临的非常重要的问题。近年来我国信息事业发展迅速，手工管理方式在学习信息管理等需要大量事务处理的应用中已显得不相适应，采用IT技术提高服务质量和管理水平势在必行。目前，对外开放必然趋势使信息行业直面外国同行单位的直接挑战，因此，信息行业必须提高其工作效率，改善其工作环境。 
## 1.3 研究目的   
本课题的目的是使学习信息管理清晰化，透明化，便于操作，易于管理。通过功能模块的优化组合实现不同的管理细节，使管理过程实现最大程度的自动化与信息化,并能自动对人工操作环节进行复查,使基于B2B平台的医疗病历交互系统出错率降至最低。

如何开发一个实用的基于B2B平台的医疗病历交互系统，是摆在设计者面前的一大难题。 通过对基于B2B平台的医疗病历交互系统进行深入分析和研究，本文从功能模块、数据格式、通用性三个方面进行细化，提出基于B2B平台的医疗病历交互系统设计的理论依据和实现的方法。 
# 第2章 设计技术与开发环境
## 2.1 相关技术介绍   
### 2.1.1 B/S模式分析
C/S模式主要由客户应用程序(Client)、服务器管理程序(Server)和中间件(middleware)三个部件组成。客户应用程序是系统中用户与数据组件交互。服务器程序负责系统资源，如管理信息数据库的有效管理，其主要工作是当多个客户端同时请求同一个服务器上的资源，以优化这些资源的管理。中间件是负责连接客户端应用程序和服务器管理器，一个合作作业完成，以满足用户的查询的管理数据的要求。  

B/S模式首先简化了客户端。它无需象C/S模式那样在不同的客户机上安装不同的客户应用程序，而只需安装通用的浏览器软件。这样不但可以节省客户机的硬盘空间与内存，而且使安装过程更加简便、网络结构更加灵活。  

再次，它使用户的操作变得更简单。对于C/S模式，客户应用程序有自己特定的规格，使用者需要接受专门培训。而采用B/S模式时，客户端只是一个简单易用的浏览器软件。无论是决策层还是操作层的人员都无需培训，就可以直接使用。B/S模式的这种特性，还使 MIS系统维护的限制因素更少。 

最后，B/S特别适用于网上信息发布，使得传统的MIS的功能有所扩展。这是C/S所无法实现的。而这种新增的网上信息发布功能恰是现代用户所需的。这使得用户的电子文件可以取代大部分的纸质文件，从而使用户工作的效率得以提高，简化用户工作的手续，节约了物力和人力。 

鉴于B/S比C/S的具有更先进性，B/S逐步的成为了当今流行的一种MIS平台系统。本系统也采用B/S结构开发。
### 2.1.2 mysql简介
MySQL是一个关系型数据库管理系统，由瑞典MySQL AB公司开发，目前属于Oracle公司。Mysql是最流行的关系型数据库管理系统，在WEB应用方面MySQL是最好的RDBMS(Relational Database Management System：关系数据库管理系统)应用软件之一。MySQL是一种关联数据库管理系统，关联数据库将数据保存在不同的表中，这样就增加了速度并提高了灵活性。MySQL所使用的SQL语言是用于访问数据库的最常用标准化语言。MySQL软件采用了双授权政策（本词条“授权政策”），它分为社区版和商业版，由于其体积小、速度快、总体拥有成本低，尤其是开放源码这一特点，一般中小型网站的开发都选择MySQL作为网站数据库。 
### 2.1.3 Spring Boot 简介
SpringBoot是由Pivotal团队在2013年开始研发、2014年4月发布第一个版本的全新开源的轻量级框架。它基于Spring4.0设计，不仅继承了Spring框架原有的优秀特性，而且还通过简化配置来进一步简化了Spring应用的整个搭建和开发过程。另外SpringBoot通过集成大量的框架使得依赖包的版本冲突，以及引用的不稳定性等问题得到了很好的解决。
## 2.2 开发环境介绍  
### 2.2.1 eclipse简介 
eclipse 是一个十分优秀的用于开发J2EE和Java,的 Eclipse 插件集合，eclipse的功能十分强大，支持也非常广泛，特别是对多种不同的开源产品的支持十分不错。eclipse目前支持Java Servlet,AJAX, JSP, JSF, Struts,Spring, Hibernate,EJB3,JDBC数据库链接工具等多项功能。可以说eclipse是几乎囊括了目前所有主流开源产品的专属eclipse开发工具。 

eclipse 是一个十分优秀的用于开发Java, J2EE的 Eclipse 插件集合，eclipse的功能非常强大，支持也十分广泛，尤其是对各种开源产品的支持十分不错。eclipse目前支持Java Servlet,AJAX, JSP, JSF, Struts,Spring, Hibernate,EJB3,JDBC数据库链接工具等多项功能。可以说eclipse是几乎囊括了目前所有主流开源产品的专属eclipse开发工具。[1]
### 2.2.2 Tomcat简介
Tomcat 服务器是一个免费的开放源代码的Web 应用服务器，属于小量级的应用服务器，广泛应用于中小型系统和并发访问用户不是很多的场合，是JSP程序首选的开发方式和调试方式。对于一个初学者，这可能是因为当一个好的Apache服务器上配置了一台机器，你可以用它来访问HTML页面的请求作出回应。 Apache Tomcat的实际上是服务器的扩展的一部分，但它是独立运行的，所以当你运行tomcat的，它实际上是作为与Apache单独运行的一个单独进程。

诀窍是，当配置正确时，Apache来提供HTML页面，但实际上运行Tomcat JSP页面和Servlet。另外，Tomcat和IIS，Apache和其他Web服务器，具有处理功能的HTML页面，而这是一个Servlet和JSP容器，独立的Tomcat Servlet容器是默认模式。不过，Tomcat是不如来处理静态HTML的Apache服务器的能力。目前Tomcat最新版本为8.0.0-RC1 (alpha) Released。
# 第3章 需求分析与可行性分析
## 3.1 需求分析
伴随着信息行业的蓬勃发展和人们办公自动化意识的增强，学习信息管理部门的工作也越来越繁重，原来的基于B2B平台的医疗病历交互系统已经不能完全满足相关人员使用的需要。为了协助信息开展学习信息管理工作，提高工作效率，充分利用信息行业的现有资源，开发更好的基于B2B平台的医疗病历交互系统势在必行。

本系统采用B/S结构、结合网络数据库开发技术来设计。本系统是一个独立的系统，用来解决学习信息的管理问题。采用JSP技术构建了一个有效而且实用的学习信息管理平台，目的是为高效地完成对学习信息的管理。本系统具有标准基于B2B平台的医疗病历交互系统所具有的现实中完整的学习信息管理步骤，完全的虚拟现实实现。真正实现节约资源、提高效率、业务处理的同时真正实现基于B2B平台的医疗病历交互系统的功能作用。
### 3.1.1 应用需求分析
|服务器|硬件|处理器：Intel 酷睿<br>内 存：512M 或更大<br>硬 盘：120G 或更大|
| - | - | - |
||软件|<p>Microsoft Windows 10</p><p>Mysql5.7<br>tomcat 7.0 </p>|
|客户机|硬件|无特殊要求，只要能上连接互联网即可|
||软件|<p>Microsoft Windows 10 </p><p>360急速浏览器</p>|
系统的性能要求通常指系统需要的存储容量以及后援存储，重新启动考虑到运行效率和安全性等方面的问题。系统的硬件环境：Core 5600、1G MB（RAM）、120GB（HD）。运行系统的时候对数据的安全保密性能要求不高，一般对数据不进行加密要求。另外，也不依赖其他的软件，程序有比较好的健壮性。
### 3.1.2 运行需求分析
硬件条件：局域网；酷睿 CPU、1G RAM、PC机要求10G硬盘以上；打印机。

软件条件：Windows 10  IE6.0以上。
### 3.1.3 其他需求分析
本次要开发的系统有效率，可理解性、可靠性和可维护性都比较高。用户很容易理解和学会操作。可维护性包括两种含义，即可读性和可测试性等。可靠性一般是指健壮性和正确性。在开发这个系统的过程中，需要权衡多种矛盾的目标，并在（时间、经费、可能用到的硬件和软件资源等条件）的限制下，使上面所说的各种要求得到最大限度的满足。
## 3.2 数据流程分析
### 3.2.1 系统操作流程
系统主界面

系统登录界面

系统管理

输入操作员及密码

检查

密码正确

功能界面

功能处理

错误信息

密码错误

数据库
![](/images/0000stringboot/0060springboot/blog.001.png)

图3-1  系统操作流程图
### 3.2.2 数据增加流程
添加信息时，编号字段由系统自动生成，且不能修改，其他信息由用户输入，之后对数据进行合法判断，合法则写入保存至数据库，不合法则重新输入数据。数据增加流程图：

开始

自动生成编号

输入数据

是否合法

写入数据库

结束

![](/images/0000stringboot/0060springboot/blog.002.png)

图3-2  数据增加流程图
### 3.2.3 数据修改流程
在修改信息时，先选中一条待修改的记录，然后直接输入数据，判断合法性，合法则保存至数据库，不合法重新输入。数据修改流程图如图3-3所示。

开始

选择需要修改记录

输入数据

是否合法

写入数据库

结束

![](/images/0000stringboot/0060springboot/blog.003.png)

图3-3  数据修改流程图
### 3.2.4 数据删除流程
当用户选定一条记录时，单击删除按钮，会提示用户是否确定删除，然后删除数据库相关内容。数据删除流程图如图3-4所示。

开始

选择需要删除记录

是否删除

更新数据库

![](/images/0000stringboot/0060springboot/blog.004.png)

图3-4  数据删除流程图
## 3.3 可行性研究
现在许多用户的管理方式既困难又浪费时间和成本，很容易出错。所以应该掌握先进的管理方式，从而提高用户的效率和降低成本。基于B2B平台的医疗病历交互系统主要有以下优势：
### 3.3.1 经济可行性
经济可行性研究是对组织的经济现状和投资能力进行分析，对系统建设运行和维护费用进行估算，对系统建成后可能取得的社会和经济效益进行估计。由于本系统是作为毕业设计由我们自己开发的，在经济上的投入甚微，系统建成之后将为今后学习信息管理提供很大的方便，估算新系统的开发费用和今后的运行、维护费用，本次研究开发的基于B2B平台的医疗病历交互系统可取代传统的学习管理的业务流程，减少人工开支，节省资金，并且可大大提高信息量的取得，缩短信息处理周期，提高信息管理的效率，具有用户使用更简单、界面更直观、权限分配更合理等优点大大减少管理成本。本项目开发经费在经济上是可以接受的，并且本项目实施后可以显著提高工作效率，节省开支。所有开支都不大，所以本项目在经济上是可行的。
### 3.3.2 技术可行性
技术可行性要考虑利用现有的技术能否顺利的完成开发系统的工作，硬件和软件配置能不能满足开发的需求等。本次要开发的基于B2B平台的医疗病历交互系统用的是是比较流行的JSP技术，用它来创建使用脚本语言，结合HTML代码来制作动态网页。即可快速完成系统的应用程序，不进行编译，容易编写，可直接在服务器端口执行，使用Windows记事本这种普通的文本编辑器，就可以设计编辑，不需要用到浏览器。因此较为简单易学调试也比较简单，软件方面：由于使用的是目前相对成熟发展的B/S模式软件，故软件开发的平台可行,因此在技术上本次开发是绝对可行的。

3.3.3 运行可行性

系统的开发，是典型的Mis开发，主要是对数据的处理，包括数据的收集，数据的变换，及数据的各种报表形式的输出。

新的系统运行后对现行旧的系统带来包括（工作环境、管理方式、组织机构等）的后果以及影响来进行评判和估计。同时更需要考虑到的是：对现有的管理人员进行培训，补充、分析在给出的时间里是不是能完成预定开发系统的任务等。

我国目前技术已经相当的普及信息化，各种工作人员都具备一定的高度的水平，所以本系统在运行上具备了可行性。

3.3.4 时间可行性

从时间上看，在两个月的时间里学习相关知识，并开发基于B2B平台的医疗病历交互系统，时间上是有点紧，但是不是不可能实现，在做毕业设计的这几个月里，我通过努力使得功能应该基本可以实现。

3.3.5 法律可行性

1. 所用到的技术资料全部都是合法的。
1. 在开发系统的过程里并没有存在知识产权的问题。
1. 并无抄袭任何已存在的基于B2B平台的医疗病历交互系统，故没有侵犯版权的问题。
1. ` `在设计开发系统的过程中并未涉及任何法律上的责任。

综上所述，开发本次系统从经济上、从技术上、从法律上都是完全可靠的。
# 第4章 系统设计
## 4.1 系统总体设计
系统不仅要求功能完善，而且还要界面友好，因此，对于一个成功的系统设计，功能模块的设计是关键。由于本系统可执行的是一般性质的学习信息管理工作，本系统具有一般适用性，其所实现的功能满足用户对日常性学习信息的管理。首先，整个系统分成几个小的模块，小的问题，然后，进一步细分模块，添加细节。

管理员功能模块如图4-1所示：

![](/images/0000stringboot/0060springboot/blog.005.png)

图4-1管理员功能模块图

医院功能模块如图4-2所示：

![](/images/0000stringboot/0060springboot/blog.006.png)

图4-2医院功能模块图

用户功能模块如图4-3所示：

![](/images/0000stringboot/0060springboot/blog.007.png)

图4-3用户功能模块图

医生功能模块如图4-4所示：

![](/images/0000stringboot/0060springboot/blog.008.png)

图4-4医生功能模块图


## 4.2 系统开发步骤
` 	`一般说来，信息管理系统的应用和成立可以分为三个阶段的：开发系统，总体规划和操作系统，可进一步划分为系统开发系统实施，系统设计和系统分析和工作等方面的阶段。每个发展阶段安排在一个严格的线性序列来开发，在每一个阶段所产生的工作指导和依据每个阶段处理文件审查下一阶段的完整的技术文档，相信这个阶段已经完成，之后实现要求进入下一个阶段，而在以后的工作中不能轻易对以前的评估结果有所改变。

上述开发的方法是有便于进行设计开发工作的管理和组织的最大优点，而且在最大程序上减少了开发信息管理系统的复杂性。国内外有很多已经开发好的系统的实际例子都能证明这是一个效果非常不错的开发方法。 
## 4.3 概要设计
在系统需求分析阶段，搞清楚了要开发的这个软件需要“做什么”的问题，形成一个系统目标的逻辑模型来。然后我们所要做的就是要把软件需要“做什么”的这个逻辑模型转换成“怎么做”的一个物理模型，最后再着手实现系统的需求。首先，我们需要描述的是系统的总的体系结构。
## 4.4 数据库概念结构设计
在每一个应用程序中，数据库的设计是其中非常重要的部分，选择合适的数据库并创建合计的结构式开发程序时首要的问题。数据库将用mysql进行设计和管理。数据库安全性就是保证数据库信息的保密性，完整性，一致性和可用性，防止非法用户越权使用数据库从而窃取，更改或破坏数据库中数据[6]，将提供一些安全措施来保证数据库的安全。根据以上章节对系统所做的需求分析和系统设计.

医院ER图

![](/images/0000stringboot/0060springboot/blog.009.png)

管理员ER图

![](/images/0000stringboot/0060springboot/blog.010.png)

文章类型ER图

![](/images/0000stringboot/0060springboot/blog.011.png)
## 4.5 数据库逻辑结构设计
模式设计的目的是确定物理数据结构。它的主要问题是处理具体的数据库管理系统的结构约束。第三范式形式的实体及关系模型是模式设计过程的输入。我们通常用“范式”定义来对数据冗余的程度进行消除。第一范式（1NF）数据冗余很大程度上，第五范式（5NF）最小的数据冗余水平。但是，范式级别越高，则需要存储相同的数据被分解成多个表，随着范式水平的提高，数据结构的存储结构和问题的域之间的匹配程度也在不断变化的数据需求下降的时候，因此，不太稳定。第三范式是需要提高访问表中增加的水平，因此性能（速度）将减少。从实际的角度来看，选择在大多数情况下，第三范式是比较合适的。该系统的大致轮廓确定以下，一个重要的步骤就是设计一个数据库的内容以及表的设计直接影响了开发的系统的质量。在设计的过程中，考虑了设计数据表范式规则，但更重要的考虑了用户使用的方便性。根据E-R模型，该软件建立了以下逻辑数据结构。

数据库概念模型独立于任何特定的数据库管理系统，因此，需要根据具体使用的数据库管理系统的特点进行转换。本系统的数据结构比较清晰，依据基于B2B平台的医疗病历交互系统的功能要求，主要设计出数据库的表如下：

表4.1 病人病历

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|zhanghao|varchar(200)|是|NULL|账号|
|xingming|varchar(200)|是|NULL|姓名|
|yiyuanbianhao|varchar(200)|是|NULL|医院编号|
|xingbie|varchar(200)|是|NULL|性别|
|hunyin|varchar(200)|是|NULL|婚姻|
|nianling|varchar(200)|是|NULL|年龄|
|xianzhudizhi|varchar(200)|是|NULL|现住地址|
|ruyuanriqi|varchar(200)|是|NULL|入院日期|
|zhusu|longtext|是|NULL|主诉|
|xianbingshi|longtext|是|NULL|现病史|
|jiwangshi|longtext|是|NULL|既往史|
|gerenshi|longtext|是|NULL|个人史|
|jiazushi|longtext|是|NULL|家族史|
|tigejiancha|longtext|是|NULL|体格检查|
|binglizhaiyao|longtext|是|NULL|病历摘要|
|chubuzhenduan|longtext|是|NULL|初步诊断|
|yishengzhanghao|varchar(200)|是|NULL|医生账号|
|yishengxingming|varchar(200)|是|NULL|医生姓名|
表4.2 医生展示评论表

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|refid|bigint(20)|否||关联表id|
|userid|bigint(20)|否||用户id|
|nickname|varchar(200)|是|NULL|用户名|
|content|longtext|否||评论内容|
|reply|longtext|是|NULL|回复内容|
表4.3 医院文章评论表

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|refid|bigint(20)|否||关联表id|
|userid|bigint(20)|否||用户id|
|nickname|varchar(200)|是|NULL|用户名|
|content|longtext|否||评论内容|
|reply|longtext|是|NULL|回复内容|
表4.4 院区展示评论表

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|refid|bigint(20)|否||关联表id|
|userid|bigint(20)|否||用户id|
|nickname|varchar(200)|是|NULL|用户名|
|content|longtext|否||评论内容|
|reply|longtext|是|NULL|回复内容|
表4.5 收藏表

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|userid|bigint(20)|否||用户id|
|refid|bigint(20)|是|NULL|收藏id|
|tablename|varchar(200)|是|NULL|表名|
|name|varchar(200)|否||收藏名称|
|picture|varchar(200)|否||收藏图片|
表4.6 管理员表

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|username|varchar(100)|否||用户名|
|password|varchar(100)|否||密码|
|role|varchar(100)|是|管理员|角色|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|新增时间|
表4.7 文章类型

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|wenzhangleixing|varchar(200)|是|NULL|文章类型|
表4.8 医疗安排

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|yiyuanbianhao|varchar(200)|是|NULL|医院编号|
|zhanghao|varchar(200)|是|NULL|账号|
|xingming|varchar(200)|是|NULL|姓名|
|ruyuanriqi|datetime|是|NULL|入院日期|
|ruzhukeshi|varchar(200)|是|NULL|入住科室|
|ruzhufanghao|varchar(200)|是|NULL|入住房号|
|yishengzhanghao|varchar(200)|是|NULL|医生账号|
|yishengxingming|varchar(200)|是|NULL|医生姓名|
|yongyaoanpai|longtext|是|NULL|用药安排|
|yongyaojindu|varchar(200)|是|NULL|用药进度|
|jianchaxiangmuanpai|longtext|是|NULL|检查项目安排|
|xiangmujianchajindu|varchar(200)|是|NULL|项目检查进度|
|hulianpai|longtext|是|NULL|护理安排|
|hulijindu|varchar(200)|是|NULL|护理进度|
表4.9 医生

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|yishengzhanghao|varchar(200)|否||医生账号|
|mima|varchar(200)|否||密码|
|yishengxingming|varchar(200)|否||医生姓名|
|xingbie|varchar(200)|是|NULL|性别|
|chushengriqi|date|是|NULL|出生日期|
|shouji|varchar(200)|是|NULL|手机|
|youxiang|varchar(200)|是|NULL|邮箱|
|shenfenzheng|varchar(200)|是|NULL|身份证|
|nianling|varchar(200)|是|NULL|年龄|
|keshi|varchar(200)|是|NULL|科室|
|zhicheng|varchar(200)|是|NULL|职称|
|zhiwu|varchar(200)|是|NULL|职务|
|gerenjianjie|longtext|是|NULL|个人简介|
|zhuanyetezhang|varchar(200)|是|NULL|专业特长|
|yiyuanbianhao|varchar(200)|否||医院编号|
|zhaopian|varchar(200)|是|NULL|照片|
|sfsh|varchar(200)|是|否|是否审核|
|shhf|longtext|是|NULL|审核回复|
表4.10 医生展示

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|yishengzhanghao|varchar(200)|是|NULL|医生账号|
|yishengxingming|varchar(200)|是|NULL|医生姓名|
|xingbie|varchar(200)|是|NULL|性别|
|chushengriqi|varchar(200)|是|NULL|出生日期|
|nianling|varchar(200)|是|NULL|年龄|
|keshi|varchar(200)|是|NULL|科室|
|zhicheng|varchar(200)|是|NULL|职称|
|zhiwu|varchar(200)|是|NULL|职务|
|gerenjianjie|longtext|是|NULL|个人简介|
|zhuanyetezhang|varchar(200)|是|NULL|专业特长|
|yiyuanbianhao|varchar(200)|是|NULL|医院编号|
|zhaopian|varchar(200)|是|NULL|照片|
|thumbsupnum|int(11)|是|0|赞|
|crazilynum|int(11)|是|0|踩|
表4.11 医院

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|yiyuanbianhao|varchar(200)|否||医院编号|
|mima|varchar(200)|否||密码|
|yiyuanmingcheng|varchar(200)|否||医院名称|
|fuzeren|varchar(200)|是|NULL|负责人|
|fuzerenshouji|varchar(200)|是|NULL|负责人手机|
|youxiang|varchar(200)|是|NULL|邮箱|
|fuzerenshenfenzheng|varchar(200)|是|NULL|负责人身份证|
表4.12 医院公告

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|biaoti|varchar(200)|是|NULL|标题|
|neirong|varchar(200)|是|NULL|内容|
|gonggaoshijian|datetime|是|NULL|公告时间|
|gonggaowenjian|varchar(200)|是|NULL|公告文件|
|gonggaotupian|varchar(200)|是|NULL|公告图片|
|yiyuanbianhao|varchar(200)|是|NULL|医院编号|
表4.13 医院工作人员

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|xingming|varchar(200)|否||姓名|
|xingbie|varchar(200)|是|NULL|性别|
|nianling|varchar(200)|是|NULL|年龄|
|chushengriqi|date|否||出生日期|
|xueli|varchar(200)|是|NULL|学历|
|bumen|varchar(200)|否||部门|
|zhiwu|varchar(200)|是|NULL|职务|
|keshi|varchar(200)|是|NULL|科室|
|shenfenzheng|varchar(200)|是|NULL|身份证|
|shouji|varchar(200)|是|NULL|手机|
|touxiang|varchar(200)|是|NULL|头像|
|yiyuanbianhao|varchar(200)|是|NULL|医院编号|
表4.14 医院科室

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|keshimingcheng|varchar(200)|是|NULL|科室名称|
|keshileixing|varchar(200)|是|NULL|科室类型|
|keshijianjie|longtext|是|NULL|科室简介|
|keshirenyuan|longtext|是|NULL|科室人员|
|keshitupian|varchar(200)|是|NULL|科室图片|
|yiyuanbianhao|varchar(200)|是|NULL|医院编号|
表4.15 医院科室预约

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|keshileixing|varchar(200)|是|NULL|科室类型|
|yiyuanbianhao|varchar(200)|是|NULL|医院编号|
|keshimingcheng|varchar(200)|是|NULL|科室名称|
|yuyueshijian|datetime|是|NULL|预约时间|
|zhanghao|varchar(200)|是|NULL|账号|
|xingming|varchar(200)|是|NULL|姓名|
|sfsh|varchar(200)|是|否|是否审核|
|shhf|longtext|是|NULL|审核回复|
表4.16 医院列表

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|yiyuanbianhao|varchar(200)|否||医院编号|
|mima|varchar(200)|否||密码|
|yiyuanmingcheng|varchar(200)|否||医院名称|
|fuzeren|varchar(200)|是|NULL|负责人|
|fuzerenshouji|varchar(200)|是|NULL|负责人手机|
|youxiang|varchar(200)|是|NULL|邮箱|
|fuzerenshenfenzheng|varchar(200)|是|NULL|负责人身份证|
|zhanghao|varchar(200)|是|NULL|账号|
|xingming|varchar(200)|是|NULL|姓名|
|zhuceshijian|datetime|是|NULL|注册时间|
表4.17 医院文章

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|biaoti|varchar(200)|是|NULL|标题|
|wenzhangleixing|varchar(200)|是|NULL|文章类型|
|neirong|longtext|是|NULL|内容|
|zuozhe|varchar(200)|是|NULL|作者|
|shipin|varchar(200)|是|NULL|视频|
|fabiaoshijian|datetime|是|NULL|发表时间|
|wenzhangtupian|varchar(200)|是|NULL|文章图片|
|yiyuanbianhao|varchar(200)|是|NULL|医院编号|
|thumbsupnum|int(11)|是|0|赞|
|crazilynum|int(11)|是|0|踩|
表4.18 医院注册

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|yiyuanmingcheng|varchar(200)|否||医院名称|
|mima|varchar(200)|否||密码|
|fuzeren|varchar(200)|是|NULL|负责人|
|fuzerenshouji|varchar(200)|是|NULL|负责人手机|
|youxiang|varchar(200)|是|NULL|邮箱|
|fuzerenshenfenzheng|varchar(200)|是|NULL|负责人身份证|
|zhanghao|varchar(200)|是|NULL|账号|
|xingming|varchar(200)|是|NULL|姓名|
|sfsh|varchar(200)|是|否|是否审核|
|shhf|longtext|是|NULL|审核回复|
表4.19 用户

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|zhanghao|varchar(200)|否||账号|
|mima|varchar(200)|否||密码|
|xingming|varchar(200)|否||姓名|
|xingbie|varchar(200)|是|NULL|性别|
|shouji|varchar(200)|是|NULL|手机|
|youxiang|varchar(200)|是|NULL|邮箱|
|shenfenzheng|varchar(200)|是|NULL|身份证|
|zhaopian|varchar(200)|是|NULL|照片|
表4.20 院区展示

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|yiyuanbianhao|varchar(200)|是|NULL|医院编号|
|yuanqumingcheng|varchar(200)|否||院区名称|
|yuanqujianjie|longtext|是|NULL|院区简介|
|yuanqudizhi|varchar(200)|是|NULL|院区地址|
|yuanqudianhua|varchar(200)|是|NULL|院区电话|
|yuanquzongmianji|varchar(200)|是|NULL|院区总面积|
|zhuanjia|longtext|是|NULL|专家|
|keshi|longtext|是|NULL|科室|
|yuanqutupian|varchar(200)|是|NULL|院区图片|



# 第5章 系统实现
## 5.1 管理员角色 
### 5.1.1 医院管理
管理员可以在医院管理界面对医院信息进行添加，修改，删除，查询操作。医院管理页面的运行结果如图5-1所示：

![](/images/0000stringboot/0060springboot/blog.012.png)

图5-1医院管理界面 
### 5.1.2 医院注册
管理员可以在医院注册界面对医院信息进行添加，修改，删除，查询操作。医院注册页面的运行结果如图5-2所示：



![](/images/0000stringboot/0060springboot/blog.013.png)

图5-2 医院注册界面 
### 5.1.3 医院文章
管理员可以在医院文章界面对医院文章进行查看和查询操作。医院文章页面的运行结果如图5-3所示：



![](/images/0000stringboot/0060springboot/blog.014.png)

图5-3 医院文章界面 
### 5.1.4 医生信息
管理员可以在医生信息界面对医生信息进行查看以及查询操作。医生信息页面的运行结果如图5-3所示：



![](/images/0000stringboot/0060springboot/blog.015.png)

图5-4 医生信息界面 
## 5.2 用户角色 
### 5.2.1 医院注册
用户可以在医院注册界面对注册医院信息。医院注册页面的运行结果如图5-3所示：



![](/images/0000stringboot/0060springboot/blog.016.png)

图5-5 医院注册界面 
### 5.2.2 医疗安排
用户可以在医疗安排界面查看医疗安排信息。医疗安排页面的运行结果如图5-3所示：



![](/images/0000stringboot/0060springboot/blog.017.png)

图5-6 医疗安排界面 

## 5.3 医院角色 
### 5.3.1 院区注册
医院可以在院区注册界面对注册院区信息。院区注册页面的运行结果如图5-3所示：



![](/images/0000stringboot/0060springboot/blog.018.png)

图5-7 院区注册界面 
### 5.3.2 医院公告
医院可以在医院公告界面对医院公告信息进行添加，修改，删除，查询等操作。医院公告页面的运行结果如图5-3所示：



![](/images/0000stringboot/0060springboot/blog.019.png)

图5-8 医院公告界面 
## 5.4 医生角色 
### 5.4.1 医院工作人员
医生可以在医院工作人员界面查看医院工作人员人员。医院工作人员页面的运行结果如图5-3所示：



![](/images/0000stringboot/0060springboot/blog.020.png)

图5-9 医院工作人员界面 
### 5.4.2 病人病历
医生可以在病人病历界面对病人病历信息进行添加，修改，删除，查询等操作。病人病历页面的运行结果如图5-3所示：



![](/images/0000stringboot/0060springboot/blog.021.png)

图5-10 病人病历界面 




















