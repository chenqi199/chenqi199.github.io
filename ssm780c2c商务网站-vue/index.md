# ssm780C2C商务网站+vue


# [项目清单 包安装运行](http://chenqi1990.site) 官网地址 http://chenqi1990.site

# [ssm780C2C商务网站+vue](https://github.com/GraduationProject-springboot/)

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### [github 项目仓库](https://github.com/GraduationProject-springboot/allSpringbootProjects) 开源仅有后端代码

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)]()

# 绪论
## 1.1课题研究背景意义
随着科技的发展，计算机的应用，人们的生活方方面面都和互联网密不可分。计算机的普及使得人们的生活更加方便快捷，网络也遍及到我们生活的每个角落，为我们的学习、生活和工作带来了极大的方便。随着计算机技术的发展以及计算机网络的逐渐普及，互联网成为人们查找信息的重要场所，二十一世纪是信息的时代，信息的交换和信息流通显得特别重要。
## 1.2设计目标
首先对系统所涉及到的相关计算机知识整体把握，并进行基础的系统分析。系统分析是程序开发中的一个非常重要的环节，为了能够使设计程序更好、更充分的被展现出来，必须事先进行调查研究。在基础的调查的同时，也要对新系统的功能进行详细的解析分析，这样才能够研究开发出更加完整的系统设计。

在本次毕业设计中，使用了JSP技术，SSM框架，MYSQL数据库进行系统的开发。构建了一个C2C 商务网站软件。

无论哪个系统都应该有自己的设计目标。该C2C 商务网站软件也具有重要的设计目标有如下几个：

1.简洁性：操作简便、界面良好，简单明了的页面布局。 

2.适用性：系统设计可以实现数据信息查看、公告等，具有良好的可用性。

3.即时可见：实现信息"即时发布、即时见效"的功能。
## 1.3 设计原则
一个成功的网站应明确建设网站的目的，确定网站的具体功能，确定网站规模、投入费用，进行必要的市场分析等。只有经过详细的策划，才能避免在网站建设中出现的很多问题，使网站建设能够顺利进行。同时，一个大型的计算机网站系统，必须有一个正确的设计思想，并且通过合理的选择数据结构、网络结构、操作系统以及系统的开发环境，逐步构成一个完善的网络结构系统，只有这样才能充分使得计算机数据管理的优势发挥到最大。根据现实生活中扶贫的需求，该C2C 商务网站软件的开发按照以下原则进行。

1、有效性：实际上这里所说的有效性包括了两个方面的意思，即有用性和可用性。其中有用性是指的是站点能满足用户需求的潜在功能，而可用性指的是能够通过站点来操作实现系统的体现功能。因此可以看出一个站点如果不能够恰当的运行或者是设计得非常不好，那就不是一个好的站点。可用站点的效益应该非常高，并易于学习，在实现用户目标时令人满意而不出错。

2、高可靠性：一个实用的网站同时必须是可靠的，本设计通过合理而先进的网络设计以及软、硬件的优化选型，可保证网站的可靠性与容错性。

3、高安全性：在设计中，将把网络软、硬件所能够提供的各种安全措施充分利用，这样既能够保证用户资源的共享，又能够充分考虑到系统以及数据资源的容灾、备份以及恢复的要求。为系统强大的数据库提供备份。以至于可以保证主要数据的安全性。同时操作权限级，我们设置不同的角色来保证每一步的操作权限，可以由管理员进行设置。

4、先进性：采用目前国际上最先进的数据库技术，使用JSP作为开发工具，MVC模式，MYSQL作为网站的数据库。本系统采用的这些技术完全基于微软平台进行开发，从来有效的降低了系统的运营成本，大大提高了该C2C 商务网站软件的稳定性和易维护性。

5、采用标准技术：本网站的所有设计遵循国际上现行的标准进行，以提高系统的开放性。

1. # 系统开发环境
## 2.1 JSP技术
JSP程序使用了Java编程语言，JSP技术可以对动态网页进行封装。通过tags和scriptlets，网页还能访问存在于服务端的资源的应用逻辑。JSP可以分离网页逻辑与网页设计和显示，对可重用的基于组件的开发进行支撑，更容易的对基于Web的应用程序进行设计。

当Web服务器接收到访问JSP网页的请求时，首先运行的程序段，接下来将JSP文件中的HTML代码和运行效果一并返还给用户。通过Java文件的插入能够对数据库、网页多重定向等运行，从而满足构建动态网页所需要的程序。JSP和Servle相同，都可以通过服务器端运行。由于能够将一个HTML文本返回给用户端，所以用户端具备浏览器就可以进行浏览。HTML程序和穿插在内部的Java程序可以构建JSP网页。在服务器被用户端访问时，能够处理相应的Java代码，然后将产生的HTML页面再返回给用户端的浏览器。JSP的设计关键是Servlet，通常大型的Web应用程序的设计成果也通过Java Servlet和JSP的协作。JSP既拥有了方便快捷的Java程序，又统统的面向用户，既实现了平台的无关性危险还比较小，可以具备互联网的全部优势。JSP技术的优点：

（1）一次编写，到处运行。除了系统之外，代码无需做任何改动。 

（2）系统的多平台支持。通常情况下，能够在任何情况下的全部平台上进行设计，能够安排在任何情况中，也能够在任何情况下进行发展。相比ASP/.net来说，优点是显而易见的。

（3）强大的可塑性。通过一个不大的Jar程序能够对Servlet/JSP进行运行，也能够通过很多服务器进行集群和负载平衡，甚至能够通过多台Application解决问题。单台服务器到多台服务器，Java展现了一个强大的功能。 

（4）具有强大和多样化的开发工具支持。Java已经有了很多的设计方法，何况大部分工具都是没有花费的，这中间有很多都在多种平台之下顺畅的进展。

` `(5)支持服务器端组件。只有很有力的服务器端组件才能支撑web运行，因此开发者可以在调用web页面时通过另外的开发工具来达成纷乱效用的组件，来加强系统的可操作性。JSP可以通过完善的JAVA BEANS 组件来达成纷乱的商务功能。
## 2.2 B/S结构
在三层体系结构的B/S（Browser/Server，浏览器/服务器结构）系统中，用户可以通过浏览器向分布在网络上的众多服务器发出请求。B/S系统极大地简化了客户机的工作量，客户机上只需要安装、配置少量的客户端运行软件即可，服务器将担负大量的工作，对数据库的访问以及应用程序的执行都将由服务器来完成。

B/S架构的不断成熟，主要使用WWW浏览器技术，结合多种浏览器脚本语言，用通用浏览器需要实现原本复杂的专有软件来实现的强大功能，并节约了开发成本，是一种新的软件架构。
## 2.3 JAVA简介
Java非常适合于企业网络和Internet环境，现在已成为Internet中最受欢迎、最有影响的编程语言之一。Java来自于Sun公司的一个叫Green的项目，其原先的目的是为家用消费电子产品开发一个分布式代码系统，这样我们可以把E-mail发给电冰箱、电视机等家用电器，对它们进行控制，和它们进行信息交流。他们用Java编制了HotJava浏览器，得到了Sun公司首席执行官ScottMcNealy的支持，触发了Java进军Internet。面向对象的程序设计很接近于我们人类自然的思维，相对于面向过程的程序设计，它具有更好的可扩展性和可维护性，使我们编写的代码更健壮。

面向对象主要有四大特性：封装、抽象、继承和多态。 

封装：在面向对象语言中，封装特性是由类来体现的，我们将现实生活中的一类实体定义成类，其中包括属性和行为（在Java中就是方法），就好像人类，可以具有name,sex,age等属性，同时也具有eat(),sleep()等行为，我们在行为中实现一定的功能，也可操作属性，这是面向对象的封装特性； 

抽象：抽象就是将一类实体的共同特性抽象出来，封装在一个抽象类中，所以抽象在面向对象语言是由抽象类来体现的。比如鸟就是一个抽象实体，因为抽象实体并不是一个真正的对象，它的属性还不能完全描述一个对象，所以在语言中体现为抽象类不能实例化； 

继承：继承就像是我们现实生活中的父子关系，儿子可以遗传父亲的一些特性，在面向对象语言中，就是一个类可以继承另一个类的一些特性，从而可以代码重用，其实继承体现的是is-a关系，父类同子类在本质上还是一类实体。

多态：多态就是通过传递给父类对象引用不同的子类对象从而表现出不同的行为，多态可为程序提供更好的可扩展性，同样也可以代码重用。
## 2.4 MYSQL数据库
### 2.4.1MySQL数据库简介
在软件项目中，通过使用数据库来操作数据，可以保证数据的独立性、一致性和安全性，为系统提供有效地访问数据的方式，同时为程序员减少了应用程序的开发时间。
常见的数据库无非分为两类，一类是关系型数据库(Oracle，DB2，MySQL，SQL Server )和非关系型数据库(NoSql、MongeDB)。不同的数据库有各自的优缺点，此处不做具体介绍。
MySQL支持多线程的特点，可以方便的利用系统资源，有效提高速度，而且提供了TCP/IP、ODBC和JDBC等多种方式途径来连接数据库；虽说其功能不够强大、规模也相对较小，但是对于本系统来说足够了，同时也可以进行二次开发的数据库表结构空间的扩展。使用MySQL建立系统数据库，不仅有利于前期对数据的整合处理操作，同时利于后期的二次开发的数据扩展操作，对于有限级的数据处理，MySQL可以很好的胜任 。

MySQL的海豚标志被称为“Sakila”，这是一个很大的名称，被称为“海豚”MySQL AB公司的创始人。

MySQL是一个真正的多用户、多线程SQL数据库服务器。 是基于SQL的客户/服务器模式的关系数据库管理系统，它的有点有有功能强大、使用简单、管理方便、安全可靠性高。
### 2.4.2 MySQL特点特性
（1）C和C ++中使用和测试，以确保源代码的编译器的便携性和灵活性。

（2）支持多种操作系统AIX的，FreeBSD下，HP-UX，Linux和Mac OS中，Novell公司的Netware，OpenBSD系统，OS/2裹时，Solaris，Windows等。

（3）提供了用于不同的编程语言的API。编程语言，如C,, C ++，Python和Java的，的Perl，PHP，埃菲尔铁塔，Ruby和Tcl的。

（4），以及使用的CPU资源来支持多线程。

（5）算法优化查询SQL，切实提高搜索速度。

（6）网络上的客户端和服务器可以用来编程任何独立的编程环境，也有中国，GB2312，BIG5，日文写作，一般基金，用于支持多国语言，并且可以嵌入在数据表和其他软件shift\_jis访问柱可以用作的名称。

（7），TCP / IP，ODBC和JDBC数据库，并提供连接到其他

（8）管理工具的管理，控制和优化数据库的操作

（9）可以数以千万计的记录在一个大的数据库
### 2.4.3 MySQL数据库应用环境
如Oracle，DB2，SQL Server，小相对于其他主要数据库如MySQL有自己的缺点，如有限（MySQL集群，是一个相对贫穷的效率），但它并没有降低它的声誉。一般的个人消费者和中小型企业，以及充足的空间，和MySQL MySQL是一个开源软件，因为它拥有一个非常降低成本。

目前，互联网的结构来最流行的网站上的LAMP（Linux操作系统，Apache+ MySQL的+ PHP），使用的操作系统，如Linux操作系统，Apache Web服务器，服务器端脚本解释器的MySQL数据库， PHP等四个免费软件或开源软件（也），因为，可持续和可以创建一个免费的网站系统（劳动力成本），所以你的花费不大。
## 2.5 SSM框架介绍
### 2.5.1 SSM框架作用
SSM框架是spring MVC ，spring和mybatis框架的整合，是标准的MVC模式，将整个系统划分为表现层，controller层，service层，DAO层四层

使用spring MVC负责请求的转发和视图管理

spring实现业务对象管理，mybatis作为数据对象的持久化引擎
### 2.5.2 SSM框架原理
SpringMVC：

1.客户端发送请求到DispacherServlet（分发器）

2.由DispacherServlet控制器查询HanderMapping，找到处理请求的Controller

3.Controller调用业务逻辑处理后，返回ModelAndView

4.DispacherSerclet查询视图解析器，找到ModelAndView指定的视图

5.视图负责将结果显示到客户端

1. # 系统的需求分析
需求分析的任务是通过详细调查C2C 商务网站软件所需的对象，充分了解系统的工作概况，明确功能实现的各种需求，然后在此基础上确定系统的功能。系统必须充分考虑今后可能的扩充和改变。
## 3.1可行性分析
通过对系统实行的目的初步调查和分析，提出可行性方案并对其一一进行论证。我们在这里主要从技术可行性、经济可行性、操作可行性等方面进行分析。
### 3.1.1 技术可行性
1.硬件可行性分析

C2C 商务网站系统的硬件要求方面不存在特殊的要求，只需要在普通的硬件配置就能够轻松的实现，只是需要确保系统的正常工作即可，以及拥有较高的效率。如果有特别低的硬件，它可以导致系统的低性能以及效率低，从而导致整个网站的运行不顺畅。以目前普遍的个人计算机的配置而言，这是十分容易实现的 。因此，本系统的开发在硬件方面是可行的。

2.软件可行性分析

JSP技术提供了一个共同的机制类似的借口动态模型，设计更集中。此外，代码复用，也可以很好的体现。因此，考虑到系统的实际情况，选择JSP技术作为本系统的开发技术。通过上述分析，该系统的设计实现在软件方面是可行的。
### 3.1.2经济可行性
从经济许可上分析，系统开发需求成本并不高,而且采用的都是开源码,降低了开发成本，而且系统设计一旦完成，就能为运行，同时系统对计算机配置要求也不高，即使是网吧淘汰下来的计算机也能够满足需要。因此，从经济角度考虑，此系统开发可行。
### 3.1.3操作可行性
本系统操作比较容易，大部分输入信息页面选择的形式都是下拉框。在有些页面，信息可以自动生成，不需要输入。输入时间也采用了日历控件，操作比较容易，对用户的要求不高，只需要熟练操作WINDOWS即可。
## 3.2系统设计原则
系统的架构设计，要能够反映出用户与整个系统模块的接口之间存在有效互动，而且应该是非常清楚的，从而才能够保障在后期系统真正实现的时候数据的扩展性和安全性，只有设计出的系统实现这个目标才能有一个更好的扩展空间，以适应社会的的发展需求。

整个系统的设计中，系统必须满足以下要求：

（1）数据安全性

存储C2C 商务网站的数据，需要确保数据的安全性，在网站设计时必须要采取安全防范措施，以解决潜在的安全问题。

（2）易用性

在用户权限范围内，可在一个统一风格的界面内即可完成相关的所有流程操作或者获取所有相关信息，大大使用者的工作效率和易用性，灵活应用本系统。

（3）柔软性

由于这个C2C 商务网站主要针对新闻、公告等，设计出的系统必须能够处理接受变化的能力。
## 3.3流程分析
### 3.3.1 系统开发流程
C2C 商务网站开发中时，首先进行需求分析，进而对系统进行总体的设计规划，设计系统功能模块，数据库的选择等，本系统的开发流程如图3-1所示

![](/images/0700ssm/ssm780/blog.001.png)

图3-1系统开发流程图
### 3.3.2 系统登录流程
用户要想进入系统，必须首先通过正确的用户名、密码、权限和验证码进行登录系统。登录模块主要完成系统管理员和用户的登入，输入账号、密码、权限和验证码，系统自动验证数据的正确与否，登录信息正确则进行对应用户主界面，否则无权进行登录系统。系统流程图如图3-2所示

![](/images/0700ssm/ssm780/blog.002.png)

图3-2系统登录流程图
## 3.4系统设计规则与运行环境
无论哪个系统都应该有自己的设计规则。该系统也具有重要的设计标准有如下几个：

1.简单：在保证C2C 商务网站能够成功实现的前提下，并尽量使C2C 商务网站更容易操作，对于一个平台，这是非常重要的。

2.针对性：系统设计的重点是利于用户对相关信息的查看和管理员对信息的管理，它具有针对性很强的特点。

3.适用范围：适用范围广，平台都可以使用。

4.操作环境

（1）硬件平台：

CPU：酷睿i3 -3.0GHZ    内存：2G以上     硬盘：320GB

（2）软件平台：

5.操作系统：Window XP 或Win 7或Win10均可

6.数据库： MYSQL数据库
1. # 系统的概要设计
## 4.1 系统结构设计
C2C 商务网站主要分为管理员和用户两个主要用户角色，本网站采用B/S结构(Browser/Server,浏览器/服务器结构)和基于Web服务两种模式，是一个适用于Internet环境下的模型结构。只要用户能连上Internet,便可以在任何时间、任何地点使用。系统结构图如图4-1所示：

网络

管理员

用户

服务器和程序

![](/images/0700ssm/ssm780/blog.003.png)

图4-1 系统结构图
## 4.2 系统架构设计
### 4.2.1总体架构设计
系统架构的整体设计是一个将一个庞大的任务细分为多个小的任务的过程，这些小的任务分段完成后，组合在一起形成一个完整的任务。它具体的工作步骤是：

1）系统被分解多个子模块

2）对各个子模块的功能进行预先的设计

3）对各个子模块之间的逻辑关系进行设计

4）对各个模块的界面以及模块间信息的传输进行设计

在整个设计过程，以确定可能的具体方案达成每一个小的最终目标，对于每一个小的目标而言，我们必须先了解一些相关的需求分析的信息。然后对系统进行初步的设计，并对其逐渐进行优化，设计出一个具体可实现的系统框架。

如图4-2所示为系统的框架图。

C2C 商务网站

用户信息管理

商品留言管理

商品类型管理

商品投诉管理

商品信息管理

用户信息修改

用户信息新增

商品信息添加 

商品信息删除

商品信息修改

商品投诉添加

商品投诉修改

商品投诉删除

商品留言添加

商品留言删改

商品留言删除

商品类型添加 

商品类型修改 

商品类型删除 

新闻信息管理

新闻信息修改

新闻信息删除

新闻信息添加

![](/images/0700ssm/ssm780/blog.004.png)    

图4-2 系统框架图
### 4.2.2系统网络拓扑结构图
本C2C 商务网站采用先进的B/S架构，该架构具有开发简单、共享性强、维护简单方便等诸多优点。本系统的网络拓扑图如图4-3所示：

![](/images/0700ssm/ssm780/blog.005.png)

图4-3 系统的网络拓扑图

4.3 数据库设计

开发一个系统也需要提前设计数据库。这里的数据库是相关数据的集合，存储在一起的这些数据也是按照一定的组织方式进行的。目前，数据库能够服务于多种应用程序，则是源于它存储方式最佳，具备数据冗余率低的优势。虽然数据库为程序提供信息存储服务，但它与程序之间也可以保持较高的独立性。总而言之，数据库经历了很长一段时间的发展，从最初的不为人知，到现在的人尽皆知，其相关技术也越发成熟，同时也拥有着坚实的理论基础。

4.3.1 数据库概念设计

这部分内容需要借助数据库关系图来完成，也需要使用专门绘制数据库关系图的工具，比如Visio工具就可以设计E-R图（数据库关系图）。设计数据库，也需要按照设计的流程进行，首先还是要根据需求完成实体的确定，分析实体具有的特征，还有对实体间的关联关系进行确定。最后才是使用E-R模型的表示方法，绘制本系统的E-R图。不管是使用亿图软件，还是Visio工具，对于E-R模型的表示符号都一样，通常矩形代表实体，实体间存在的关系用菱形符号表示，实体的属性也就是实体的特征用符号椭圆表示。最后使用直线将矩形，菱形和椭圆等符号连接起来。接下来就开始对本系统的E-R图进行绘制。

（1）下图是商品投诉实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\shangwuwangzhan\商品投诉.jpg](/images/0700ssm/ssm780/blog.006.jpeg "C:\Users\Administrator\Desktop\img\shangwuwangzhan\商品投诉.jpg")
图4.1 商品投诉实体属性图

（2）下图是用户实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\shangwuwangzhan\用户.jpg](/images/0700ssm/ssm780/blog.007.jpeg "C:\Users\Administrator\Desktop\img\shangwuwangzhan\用户.jpg")
图4.2 用户实体属性图

（3）下图是商品信息实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\shangwuwangzhan\商品信息.jpg](/images/0700ssm/ssm780/blog.008.jpeg "C:\Users\Administrator\Desktop\img\shangwuwangzhan\商品信息.jpg")
图4.3 商品信息实体属性图

（4）下图是字典表实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\shangwuwangzhan\字典表.jpg](/images/0700ssm/ssm780/blog.009.jpeg "C:\Users\Administrator\Desktop\img\shangwuwangzhan\字典表.jpg")
图4.4 字典表实体属性图

（5）下图是购物车实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\shangwuwangzhan\购物车.jpg](/images/0700ssm/ssm780/blog.010.jpeg "C:\Users\Administrator\Desktop\img\shangwuwangzhan\购物车.jpg")
图4.5 购物车实体属性图

（6）下图是积分记录实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\shangwuwangzhan\积分记录.jpg](/images/0700ssm/ssm780/blog.011.jpeg "C:\Users\Administrator\Desktop\img\shangwuwangzhan\积分记录.jpg")
图4.6 积分记录实体属性图

（7）下图是新闻信息实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\shangwuwangzhan\新闻信息.jpg](/images/0700ssm/ssm780/blog.012.jpeg "C:\Users\Administrator\Desktop\img\shangwuwangzhan\新闻信息.jpg")
图4.7 新闻信息实体属性图

（8）下图是客服聊天实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\shangwuwangzhan\客服聊天.jpg](/images/0700ssm/ssm780/blog.013.jpeg "C:\Users\Administrator\Desktop\img\shangwuwangzhan\客服聊天.jpg")
图4.8 客服聊天实体属性图

（9）下图是商家实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\shangwuwangzhan\商家.jpg](/images/0700ssm/ssm780/blog.014.jpeg "C:\Users\Administrator\Desktop\img\shangwuwangzhan\商家.jpg")
图4.9 商家实体属性图

（10）下图是商品收藏实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\shangwuwangzhan\商品收藏.jpg](/images/0700ssm/ssm780/blog.015.jpeg "C:\Users\Administrator\Desktop\img\shangwuwangzhan\商品收藏.jpg")
图4.10 商品收藏实体属性图

（11）下图是商品评价实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\shangwuwangzhan\商品评价.jpg](/images/0700ssm/ssm780/blog.016.jpeg "C:\Users\Administrator\Desktop\img\shangwuwangzhan\商品评价.jpg")
图4.11 商品评价实体属性图

（12）下图是商品订单实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\shangwuwangzhan\商品订单.jpg](/images/0700ssm/ssm780/blog.017.jpeg "C:\Users\Administrator\Desktop\img\shangwuwangzhan\商品订单.jpg")
图4.12 商品订单实体属性图

（13）下图是用户表实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\shangwuwangzhan\用户表.jpg](/images/0700ssm/ssm780/blog.018.jpeg "C:\Users\Administrator\Desktop\img\shangwuwangzhan\用户表.jpg")
图4.13 用户表实体属性图

（14）下图是收货地址实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\shangwuwangzhan\收货地址.jpg](/images/0700ssm/ssm780/blog.019.jpeg "C:\Users\Administrator\Desktop\img\shangwuwangzhan\收货地址.jpg")
图4.14 收货地址实体属性图

### 4.3.4 数据库表
本系统数据库的功能主要是存储网站中所有数据，以便进行操作。

表4.1收货地址表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_id|Integer|创建用户|是|
|3|address\_name|String|收货人|是|
|4|address\_phone|String|电话|是|
|5|address\_dizhi|String|地址|是|
|6|isdefault\_types|Integer|是否默认地址|是|
|7|insert\_time|Date|添加时间|是|
|8|update\_time|Date|修改时间|是|
|9|create\_time|Date|创建时间|是|
表4.2购物车表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_id|Integer|所属用户|是|
|3|shangpin\_id|Integer|商品|是|
|4|buy\_number|Integer|购买数量|是|
|5|create\_time|Date|添加时间|是|
|6|update\_time|Date|更新时间|是|
|7|insert\_time|Date|创建时间|是|
表4.3客服聊天表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_id|Integer|提问用户|是|
|3|chat\_issue|String|问题|是|
|4|issue\_time|Date|问题时间|是|
|5|chat\_reply|String|回复|是|
|6|reply\_time|Date|回复时间|是|
|7|zhuangtai\_types|Integer|状态|是|
|8|chat\_types|Integer|数据类型|是|
|9|insert\_time|Date|创建时间|是|
表4.4字典表表

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
表4.5积分记录表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_id|Integer|用户姓名|是|
|3|jifenjilu\_name|String|原因|是|
|4|jifenjilu\_number|BigDecimal|积分数量|是|
|5|jifen\_types|Integer|类型|是|
|6|insert\_time|Date|插入时间|是|
|7|create\_time|Date|创建时间|是|
表4.6新闻信息表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|news\_name|String|新闻名称|是|
|3|news\_photo|String|新闻图片|是|
|4|news\_types|Integer|新闻类型|是|
|5|insert\_time|Date|新闻发布时间|是|
|6|news\_content|String|新闻详情|是|
|7|create\_time|Date|创建时间|是|
表4.7商家表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|shangjia\_name|String|商家姓名|是|
|3|new\_money|BigDecimal|现有余额|是|
|4|shangjia\_id\_number|String|身份证号|是|
|5|shangjia\_phone|String|手机号|是|
|6|shangjia\_email|String|邮箱|是|
|7|shangjia\_photo|String|营业执照展示|是|
|8|shangjia\_xingji|String|商家星级|是|
|9|shangjia\_content|String|商家简介|是|
|10|shangjia\_delete|Integer|假删|是|
|11|create\_time|Date|创建时间|是|
表4.8商品信息表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|shangjia\_id|Integer|商家|是|
|3|shangpin\_name|String|商品名称|是|
|4|shangpin\_types|Integer|商品类型|是|
|5|shangpin\_photo|String|商品照片|是|
|6|Shangpin\_kucun\_number|Integer|商品库存|是|
|7|shangpin\_price|Integer|购买获得积分|是|
|8|shangpin\_old\_money|BigDecimal|商品原价|是|
|9|shangpin\_new\_money|BigDecimal|现价/积分|是|
|10|shangpin\_clicknum|Integer|点击次数|是|
|11|shangxia\_types|Integer|是否上架|是|
|12|shangpin\_delete|Integer|逻辑删除|是|
|13|shangpin\_content|String|商品简介|是|
|14|create\_time|Date|创建时间|是|
表4.9商品收藏表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|shangpin\_id|Integer|商品|是|
|3|yonghu\_id|Integer|用户|是|
|4|insert\_time|Date|收藏时间|是|
|5|create\_time|Date|创建时间|是|
表4.10商品评价表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|shangpin\_id|Integer|商品|是|
|3|yonghu\_id|Integer|用户|是|
|4|shangpin\_commentback\_text|String|评价内容|是|
|5|reply\_text|String|回复内容|是|
|6|insert\_time|Date|评价时间|是|
|7|update\_time|Date|回复时间|是|
|8|create\_time|Date|创建时间|是|
表4.11商品订单表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|shangpin\_order\_uuid\_number|String|订单号|是|
|3|address\_id|Integer|收获地址|是|
|4|shangpin\_id|Integer|商品|是|
|5|yonghu\_id|Integer|用户|是|
|6|buy\_number|Integer|购买的数量|是|
|7|shangpin\_order\_true\_price|BigDecimal|实付价格|是|
|8|shangpin\_order\_types|Integer|订单类型|是|
|9|shangpin\_order\_payment\_types|Integer|支付类型|是|
|10|insert\_time|Date|订单创建时间|是|
|11|create\_time|Date|创建时间|是|
表4.12商品投诉表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|shangpin\_id|Integer|投诉商品|是|
|3|yonghu\_id|Integer|投诉用户|是|
|4|shangpintousu\_types|Integer|投诉类型|是|
|5|minsu\_text|String|投诉内容|是|
|6|insert\_time|Date|投诉时间|是|
|7|create\_time|Date|创建时间|是|
表4.13用户表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_name|String|用户姓名|是|
|3|yonghu\_photo|String|头像|是|
|4|yonghu\_phone|String|用户手机号|是|
|5|yonghu\_id\_number|String|用户身份证号|是|
|6|new\_money|BigDecimal|余额|是|
|7|yonghu\_sum\_jifen|BigDecimal|总积分|是|
|8|yonghu\_new\_jifen|BigDecimal|现积分|是|
|9|huiyuandengji\_types|Integer|会员等级|是|
|10|yonghu\_delete|Integer|假删|是|
|11|create\_time|Date|创建时间|是|
表4.14用户表表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|role|String|角色|是|
|3|addtime|Date|新增时间|是|



1. # `  `系统的实现
## 5.1用户信息管理
如图5.1显示的就是用户信息管理页面，此页面提供给管理员的功能有：用户信息的查询管理，可以删除用户信息、修改用户信息、新增用户信息，

还进行了对用户名称的模糊查询的条件

![](/images/0700ssm/ssm780/blog.020.png)

图5.1 用户信息管理页面
### 5.2 商品信息管理
如图5.2显示的就是商品信息管理页面，此页面提供给管理员的功能有：查看已发布的商品信息数据，修改商品信息，商品信息作废，即可删除。


![](/images/0700ssm/ssm780/blog.021.png)

![](/images/0700ssm/ssm780/blog.022.png)

![](/images/0700ssm/ssm780/blog.023.png)

图5.2 商品信息管理页面
### 5.3商品类型管理
如图5.3显示的就是商品类型管理页面，此页面提供给管理员的功能有：根据商品类型进行条件查询，还可以对商品类型进行新增、修改、查询操作等等。


![](/images/0700ssm/ssm780/blog.024.png)

图5.3 商品类型管理页面
### 5.1新闻信息管理
如图5.4显示的就是新闻信息管理页面，此页面提供给管理员的功能有：根据新闻信息进行新增、修改、查询操作等等。

![](/images/0700ssm/ssm780/blog.025.png)

![](/images/0700ssm/ssm780/blog.026.png)

图5.4 新闻信息管理页面
1. # 系










