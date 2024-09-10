# 0370springboot高校实习管理系统--论文pf


# [0370springboot高校实习管理系统--论文pf](https://github.com/GraduationProject-springboot/0370springboot)

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

# [项目清单](https://chenqi1990.site) 包安装运行

### [github 项目仓库](https://github.com/GraduationProject-springboot/allSpringbootProjects) 开源仅有后端代码

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1T1bpekEK7?p=43)


# 第1章 绪论
## 1.1 课题背景
二十一世纪互联网的出现，改变了几千年以来人们的生活，不仅仅是生活物资的丰富，还有精神层次的丰富。在互联网诞生之前，地域位置往往是人们思想上不可跨域的鸿沟，信息的传播速度极慢，信息处理的速度和要求还是通过人们骑马或者是信鸽传递，这些信息传递都是不可控制的，中间很有可能丢失，信息的传递水平决定了人们生活的水平。如今大家都在使用互联网软件产品，从内部管理设置计算机管理，提高内部信息化的管理水准，从外部市场也可以用计算机获取相关数据进行处理，如今各行各业已经严重依赖于计算机了。

本课题研究和开发高校实习管理系统管理系统，让安装在计算机上的该系统变成管理人员的小帮手，提高高校实习管理系统信息处理速度，规范高校实习管理系统信息处理流程，让管理人员的产出效益更高。
## 1.2 课题意义
传统处理数据，必须是一张张纸，然后处理完毕又是统计在一张张纸上面，不断的重复处理，最终有个结果给最高层作为参考，这个模式在互联网没有出现之前，是一种常见的事情，信息管理的效率提不上去，人多不一定力量大，因为人多肯定更加消耗资源，并且因为人类需要休息，需要管理，思想会不统一，会偷懒，所以人们研究出专门帮助人们计算的机器，就是计算机的前身，到了互联网时代，人们发现完全可以让程序供应商提供解决方案，自己挑选自己合适的方案来提高自己的产出比。所以在日常工作和生活中会发现各种各样方便人们的工具。

本课题研发的高校实习管理系统管理系统，就是提供高校实习管理系统信息处理的解决方案，它可以短时间处理完信息，并且这些信息都有专门的存储设备，而且数据的备份和迁移都可以设定为无人值守，从人力角度和信息处理角度以及信息安全角度，高校实习管理系统管理系统是完胜传统纸质操作的。
## 1.3 研究内容
本文对高校实习管理系统管理系统的设计与实现分成六个章节来说明。

第1章：研究高校实习管理系统管理系统的背景，以及开发高校实习管理系统管理系统的意义。

第2章：对开发高校实习管理系统管理系统的环境还有技术进行说明。

第3章：分析高校实习管理系统管理系统的可行性，性能，流程以及功能。

第4章：设计高校实习管理系统管理系统的功能结构，设计数据库E-R图以及对数据表的存储结构进行设计。

第5章：实现高校实习管理系统管理系统的功能并进行功能界面展示。

第6章：对系统测试进行阐述，以及对本系统部分功能进行检测。
# 第2章 开发环境与技术
本章节对开发高校实习管理系统管理系统需要搭建的开发环境，还有高校实习管理系统管理系统开发中使用的编程技术等进行阐述。

2.1 MySQL数据库

MySQL是一种具有安全系数、安全系数、混合开发性、高效化等特征的轻量关联数据库智能管理系统。MySQL由C语言和C++语言构成，由于C语言和CC++语言混合开发的，因此MySQL源码是生命期的。MySQL提供多种多样数据种类，常见的数据种类包含[34]。伴随着数据库技术发展，MySQL逐步形成数据库管理方法的重要工具之一。它不仅能提供简单实用的操作作用，还能实现复杂多变的数据检索方法和查询记录导出方式。因为MySQL具有较好的兼容模式和扩展性，因而广泛应用于各行各业。

MySQL在WEB行业越来越受单位和个人开发者的亲睐。大部分大中小型网址都采用MySQL数据库，它不仅可以提供简单高效的数据浏览作用，还会对数据进行相应的剖析解决。因为Linux电脑操作系统和MySQL数据库全是开源系统免费体验，能够为公司节约许多费用，让很多企业使用Linux   MySQL做为网址数据库，体型小，启动速度快，也不会影响网址性能，导致用户体验感极差。

MySQL数据库能够支持各种各样操作系统的运作，包含AIX、HP-UX、OS/2 Wrap、Solaris、Mac OS、Linux和Windows等。性能好，使用便捷。因而，MySQL数据库已成为当下数据库行业最流行产品之一。MySQL数据库系统使用面向对象设计方式，客户至上开展编程设计。是利用面向对象观念来达到各项功能。它不仅能管理方法大中型数据表或关系数据库，还可以把这种复杂且庞大信息系统集成到一个简单的中小型数据库系统内。现阶段，中国很多公司早已运用了这一尖端技术。但是由于该操作系统是根据远程服务器/服务器结构的（C/S），因而，存在一些缺陷：最先，系统软件不可以提供完备的数据访问接口，客户只能依靠浏览器浏览所需要的数据；次之，系统软件并没有统一的标准，不同类型的客户端难以实现数据分享；第三，系统软件没有很好的权限管理体制。
## 2.2 Java语言技术
Java语言已经存在了25年有余。通过这些年的发展趋势，it行业在市场占有率上仍然占据一半，仍然受到了很多程序员的工作钟爱。许多从业者都是在学习培训。近年来随着从业者的提高，Java语言的位置并没减少，算得上是常青藤。Java语言学习培训比较简单，自然，它是对于C前辈们的  而言的，C  语言非常强劲。Java取消了许多特点，如go这种描述，也取消了主文件，让所有文件夹全是类，类是二维数组以及各种对象，也使Java处理一些对象的引入和回收利用，让开发者只需建立对象，应用对象，编写代码逻辑，不需要留意性能，让各种各样文件存储给Java自己解决，你能花很多时间科学研究应用软件相互关系，使研发更为集中化，如同跑车驾驶员一样，只要了解各种汽车的性能，实际操作，不需要科学研究如何生产车轮子，使软件开发更为详尽。
## 2.3 Spring Boot框架
Spring Boot框架是一个SpringMVC架构的快速轻量快速框架，能够帮助开发人员迅速搭建靠谱高效率的应用程序。依据自动部署和协议书，改善了Spring的研究过程，使开发人员可以更加专注于领域模型。

Spring Boot有许多特性，当中最主要的是它提供了内置Tomcat、Jetty、Undertow等Web网络服务器能够轻松搭建Web应用程序。除此之外，它也提供自动部署、无需撰写XML文件等功能。这种功能使开发人员能够迅速建立和布署应用程序，而无需解决繁杂的环境变量和其它繁琐复杂每日任务。

开发系统时，Spring Boot能够帮助开发人员完成模块化设计和松耦合的代码结构，从而更好地日常维护拓展应用程序。除此之外，它也提供了很多常见的库和部件，如Spring Data、Spring Security等，能够轻松集成化这种部件，完成数据库操作、验证、受权等功能。
## 2.4 其他技术使用
spring-jdbc联接：

这是一个专业生产制造Connection对象工厂类，大部分全部用以建立数据库联接框架都是会完成这一插口，Springjdbc包就实现了这一插口，实现类是DriverManagerdasource、现阶段的项目是由DataSource的getconection方式获得配备MYSQL5.7数据库连接信息。

提交Fileupload文件：

项目中应用Fileupload完成文件提交，通常是Fileupload前面提交文件提交请求，请求形式为POST：<form action="uploadServlet" method="post" ....="">请求编码方式：等候文件提交，启用Fileitem的isformField()方式，判断出表格域到底还是不是表格域，文件提交到后台管理，应用Fileupload接受文件信息，并把文件解决包存储在硬盘和库中。

Alibaba驱动：

比照各大网站Alibaba.Druid是JAVA语言中比较好的数据库连接池。Druid可提供强有力的拓展和监控功能。该项目应用Alibababa.Druid开展数据库系统连接，Druid 0.1.18 以后，全部版本号都分享到maven中央仓库，在项目pome中.在xml里加入dependency就可以使用。

log4j日志：

高校实习管理系统，其全世界错误处理和日志信息纪录，应用log4j开展日志日常维护管理与查询，其核心优势是错误处理：在logback中，应用软件里的出现异常不被应用软件认知，特性提升，关键或没有废弃物体制，log4j在很多情况下，可采取设计的一套无废弃物体制，防止经常日志搜集所引起的jvm gc。操作方法很简单，在pom中.新增log4j有关jarxml就可以。

# 第3章 系统分析
本文作者在确定了研究的课题之后，从各大数字图书馆下载文献来阅读，并了解同类型的网站具备的大致功能，然后具体事务具体分析，得出本系统要研究的具体功能与性能。虽然分析系统这一阶段性工作主要是确定功能，但它却影响着后面系统开发环节的进展，系统分析这个环节是不能少的。
## 3.1 可行性分析
从三个不同的角度来分析，确保开发成功的前提是有可行性分析，只有进行提前分析，符合程序开发流程才不至于开发过程的中断。
### 3.1.1 技术可行性
在技术实现层次，分析了好几种技术实现方法，并且都有对应的成功案例，也有很多开源模块可以进行参考，所以从技术可行性分析来讲，实现高校实习管理系统管理系统是没有问题的。
### 3.1.2 经济可行性
对于身为学生的开发者而言，在经济资源上面可用者很少，为了开发高校实习管理系统管理系统，通过开发软件对硬件的要求，发现自己的电脑是完全能用来开发的，并且学校机房的配置也可以达到要求。最重要的是选择的技术都可以在网上找到不花钱的教程以及资料，因为不花钱，所以经济方面是具有可行性的。
### 3.1.3 操作可行性
高校实习管理系统管理系统的具体实现，本身参考人类的正常操作逻辑，把常用的操作习惯当做主要的导航实现，可以让使用者更快速的理解并且上手操作，实现符合逻辑的操作流程是操作可行性的具体体现。

以上就是从不同的角度来分析，确保了高校实习管理系统管理系统的正常开展。
## 3.2 系统流程
高校实习管理系统管理系统投入使用后，使用者如果能看到相应的流程操作图会提高程序的理解能力。
### 3.2.1 操作流程
使用者在操作高校实习管理系统管理系统中，应该按照本系统提供的操作流程（图3.1即为本系统的操作流程图）进行操作，可以减少操作失误，从而节省进入高校实习管理系统管理系统的时间。

![](/images/0300stringboot/0370springboot/blog.001.png)

图3.1 系统操作流程
### 3.2.2 登录流程
高校实习管理系统管理系统通过登录功能（图3.2即为其登录的流程）引导使用者进入指定的功能操作区，也避免非本系统的用户享受本系统提供的服务以及查看本系统提供的信息，进而保证用户安全。

![](/images/0300stringboot/0370springboot/blog.002.png)

图3.2 登录流程
### 3.2.3 删除信息流程
高校实习管理系统管理系统在经过长期使用后，会产生很多的数据信息。为了腾出存储空间存放更多的数据，本系统数据库中存储的数据，一些没有参考价值的数据需要进行删除（图3.3即为删除信息的流程），删除数据过程中，为避免误删，使用者要根据系统的提示来决定是否删除数据。

![](/images/0300stringboot/0370springboot/blog.003.png)

图3.3 删除信息流程
### 3.2.4 新增信息流程
高校实习管理系统管理系统提供可视化的功能操作区，非常方便使用者进行数据操作，当使用者往系统中录入数据时（图3.4即为新增信息的流程），本系统也会进行数据合法性的判断，符合要求的数据才能够在数据库指定表中进行登记。

![](/images/0300stringboot/0370springboot/blog.004.png)

图3.4 新增信息流程
## 3.3 性能需求
分析高校实习管理系统对于性能的需求主要还是从下面的5个角度来分析，它们分别是系统的实用性，系统的适应性，系统的易操作性，系统的安全性和系统的易维护性。

性能需求一：系统的实用性，本系统主要是让管理人员集中处理相关信息，可以提供方便快捷的信息添加，信息编辑等操作。在提高信息管理人员的工作效率的同时，也可以降低管理成本，并大大减少管理人员日常繁琐的工作量。

性能需求二：系统的适应性，本系统对于运行环境的要求并不高，可以被广泛运用在生活中。因为使用者只要在日常使用的计算机，或者是随身携带的笔记本上搭建运行环境都能运行本系统，另外系统提供的基础功能包括添加，修改等都能随时操作。

性能需求三：系统的易操作性，本系统提供的功能跟同类型系统一样，也具备简单的增删改操作，操作流程的逻辑也符合广大使用者的使用需求，使用者使用本系统管理数据会非常顺手。

性能需求四：系统的安全性，本系统在数据保存与管理上安全系数要达标，在设计与编码阶段，通过对用户进行权限分配，把系统的功能依照不同用户的角色进行分配，在首次进入系统时，通过编写安全验证的代码模块，引导不同用户进入不同的操作界面。还可以对用户基础信息包括登录的账号密码等进行加密保存，可以利用当下常用的技术成熟的MD5加密技术实现。

性能需求五：系统的易维护性，本系统在后期运行中，会根据使用者的操作，产生许多数据信息，为了便于维护，就要求这些数据可以通过工具从数据库中导出来，对于一些阶段性数据，可以进行批量删除，以此达到轻负荷处理数据的目标，让本系统可以变得更加轻盈。
# 第4章 系统设计
用户对着浏览器操作，肯定会出现某些不可预料的问题，但是不代表着系统对于用户在浏览器上的操作不进行处理，所以说，要提前考虑可能会出现的问题。
## 4.1 系统设计模式
高校实习管理系统选用B/S架构模式，即网页页面和网站架构设计的开发方式。这类系统构造可以理解为正确的 C/S 系统构造的改变与推广能够进行信息分布式存储，减少资源成本，提升订制系统性能。在这种设计下，极少有事务处理在前进行，绝大多数重要事务管理的思路需要在服务端完成。

系统的性能层为表明给用户页面，用以表明与理解用户的数据，回到用户所提供的数据，递交给系统解决方法，同时提供用户与系统之间的沟通控制面板；系统通讯层承担为性能层给予后面数据，并把性能层和系统后台管理间的通信连接下去。HTTP/HTTPS协议书采用，系统控制层主要是针对从HTTP规定中获得信息，获得基本参数。并把它发放给不一样的处理方式服务(service层)，并把service层处理后的数据回到前边(本系统运用JSON数据)；系统业务逻辑层的主要作用是挑选用户的键入信息，进行特定业务逻辑和数据访问；系统数据访问层主要是针对操作过程数据，为业务逻辑层或控制层给予数据服务；系统数据库是系统存放数据的地区。进行独特业务需要数据可用，务必纪录信息才能达到工作流程。
## 4.2 功能结构设计
图4.1即为设计的管理员功能结构，管理员权限操作的功能包括管理公告，管理高校实习管理系统信息，包括职位招聘管理，培训管理，简历管理，薪资管理等，可以管理公告。

![结构设计图](/images/0300stringboot/0370springboot/blog.005.jpeg "结构设计图")

图4.1 管理员功能结构
## 4.3 数据库设计
高校实习管理系统管理系统运行中产生的数据需要按照提前设置的存储规则进行保存，设计出一个符合项目的最优数据存储格式，因为它能减少用户的等待时间，还可以对系统的请求在最短时间内进行响应。所以，对数据库设计时，需要对功能需求进行详细的拆分，以及对业务状态的细分，然后设计具体的存储规则，保证数据库能正常运作，缩短数据处理时间，并在一定程度上降低数据冗余，节省存储空间。
### 4.3.1 数据库概念设计
实体-联系图还有一个名称即E-R图，是Entity Relationship Diagram各英文单词首字母的缩写，它这种概念模型通常用于对现实世界进行描述。同时它还是一种能够直观表达数据中实体，联系，属性的有效手段。绘制E-R图能够选择的工具也有很多，但是Office Visio 这款软件在E-R图的绘制上一般都是作为首选工具，因为它是基于可视化处理，使用它创建E-R图非常简单。使用基本的E-R图构成元素，比如椭圆，菱形，矩形，还有实线段来表达对应的信息，椭圆代表属性，即实体的特征，矩形代表实体，即数据库中的一个具体数据表，菱形代表实体中相互关系，实线段主要是完成椭圆，矩形，菱形的连接。

（1）下图是用户实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\用户.jpg](/images/0300stringboot/0370springboot/blog.006.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\用户.jpg")
用户实体属性图

（2）下图是公司实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\公司.jpg](/images/0300stringboot/0370springboot/blog.007.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\公司.jpg")
公司实体属性图

（3）下图是老师实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\老师.jpg](/images/0300stringboot/0370springboot/blog.008.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\老师.jpg")
老师实体属性图

（4）下图是简历实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\简历.jpg](/images/0300stringboot/0370springboot/blog.009.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\简历.jpg")
简历实体属性图

（5）下图是简历投递实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\简历投递.jpg](/images/0300stringboot/0370springboot/blog.010.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\简历投递.jpg")
简历投递实体属性图

（6）下图是院系实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\院系.jpg](/images/0300stringboot/0370springboot/blog.011.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\院系.jpg")
院系实体属性图

（7）下图是班级实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\班级.jpg](/images/0300stringboot/0370springboot/blog.012.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\班级.jpg")
班级实体属性图

（8）下图是公告实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\公告.jpg](/images/0300stringboot/0370springboot/blog.013.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\公告.jpg")
公告实体属性图

（9）下图是实习作业实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\实习作业.jpg](/images/0300stringboot/0370springboot/blog.014.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\实习作业.jpg")
实习作业实体属性图

（10）下图是职位招聘实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\职位招聘.jpg](/images/0300stringboot/0370springboot/blog.015.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\职位招聘.jpg")
职位招聘实体属性图

（11）下图是作业提交实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\作业提交.jpg](/images/0300stringboot/0370springboot/blog.016.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\作业提交.jpg")
作业提交实体属性图

（12）下图是实习评分实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\实习评分.jpg](/images/0300stringboot/0370springboot/blog.017.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\实习评分.jpg")
实习评分实体属性图
### 4.3.2 数据库物理设计
本小节主要任务即是根据上述内容进行数据存储结构的设计，实体的属性就用来表示字段名称，不同的字段表示的数据类型以及取值都不相同，以及该表各个字段是否能够保持空等进行说明，设计完成一张数据表的结构之后，在保存时同样要命名，尽量选择英文名称进行命名并保存，还不容易导致系统出错。接下来就对设计的表进行简单说明。

表4.1班级表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|banji\_uuid\_number|String|班级编号|是|
|3|banji\_name|String|班级名称|是|
|4|banji\_address|String|班级位置|是|
|5|banji\_content|String|班级备注|是|
|6|insert\_time|Date|录入时间|是|
|7|create\_time|Date|创建时间|是|
表4.2字典表

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
表4.3公告表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|gonggao\_name|String|公告名称|是|
|3|gonggao\_photo|String|公告图片|是|
|4|gonggao\_types|Integer|公告类型|是|
|5|insert\_time|Date|发布时间|是|
|6|gonggao\_content|String|公告详情|是|
|7|create\_time|Date|创建时间|是|
表4.4公司表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|gongsi\_name|String|公司名称|是|
|3|gongsi\_types|Integer|公司类型|是|
|4|gongsi\_phone|String|联系方式|是|
|5|gongsi\_email|String|邮箱|是|
|6|gongsi\_photo|String|公司封面|是|
|7|gongsi\_content|String|公司简介|是|
|8|gongsi\_delete|Integer|逻辑删除|是|
|9|create\_time|Date|创建时间|是|
表4.5简历表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_id|Integer|用户|是|
|3|jianli\_uuid\_number|String|简历唯一编号|是|
|4|jianli\_name|String|简历标题|是|
|5|jianli\_xingming|String|姓名|是|
|6|jianli\_types|Integer|求职意向|是|
|7|jianli\_xinzi|String|期望工资|是|
|8|jianli\_xueli|String|学历|是|
|9|jianli\_jingli|String|工作经历|是|
|10|sex\_types|Integer|性别|是|
|11|jianli\_file|String|简历文件|是|
|12|jianli\_phone|String|手机号|是|
|13|jianli\_photo|String|照片|是|
|14|jianli\_address|String|位置|是|
|15|jiaoyu\_text|String|教育经历|是|
|16|shixi\_text|String|实习或工作经历|是|
|17|geren\_text|String|个人介绍|是|
|18|create\_time|Date|创建时间|是|
表4.6老师表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|laoshi\_name|String|老师姓名|是|
|3|laoshi\_phone|String|老师手机号|是|
|4|laoshi\_id\_number|String|老师身份证号|是|
|5|laoshi\_photo|String|老师头像|是|
|6|laoshi\_email|String|电子邮箱|是|
|7|create\_time|Date|创建时间|是|
表4.7实习评分表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|gongsi\_id|Integer|公司|是|
|3|yonghu\_id|Integer|用户|是|
|4|pingfen\_pingfen|BigDecimal|评分|是|
|5|pingfen\_text|String|评价内容|是|
|6|insert\_time|Date|评价时间|是|
|7|create\_time|Date|创建时间|是|
表4.8简历投递表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|jianli\_id|Integer|简历|是|
|3|zhaopin\_id|Integer|招聘|是|
|4|mianshi\_yesno\_types|Integer|投递状态|是|
|5|mianshi\_yesno\_text|String|投递回复|是|
|6|insert\_time|Date|投递时间|是|
|7|create\_time|Date|创建时间|是|
表4.9用户表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yuanxi\_id|Integer|院系|是|
|3|banji\_id|Integer|班级|是|
|4|yonghu\_name|String|用户姓名|是|
|5|yonghu\_phone|String|用户手机号|是|
|6|yonghu\_id\_number|String|用户身份证号|是|
|7|yonghu\_photo|String|用户头像|是|
|8|yonghu\_email|String|电子邮箱|是|
|9|create\_time|Date|创建时间|是|
表4.10院系表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yuanxi\_uuid\_number|String|院系编号|是|
|3|yuanxi\_name|String|院系名称|是|
|4|yuanxi\_address|String|院系位置|是|
|5|yuanxi\_content|String|院系备注|是|
|6|insert\_time|Date|录入时间|是|
|7|create\_time|Date|创建时间|是|
表4.11职位招聘表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|gongsi\_id|Integer|公司|是|
|3|zhaopin\_name|String|招聘信息名称|是|
|4|zhaopin\_photo|String|招聘信息照片|是|
|5|zhaopin\_daiyu|String|薪资待遇|是|
|6|zhaopin\_address|String|上班地点|是|
|7|lianxiren\_name|String|联系人|是|
|8|zhaopin\_phone|String|招聘电话|是|
|9|zan\_number|Integer|赞|是|
|10|cai\_number|Integer|踩|是|
|11|zhaopin\_types|Integer|招聘岗位|是|
|12|leixing\_types|Integer|招聘类型|是|
|13|zhaopin\_renshu\_number|Integer|招聘人数|是|
|14|zhaopin\_content|String|招聘信息详情|是|
|15|create\_time|Date|创建时间|是|
表4.12实习作业表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|laoshi\_id|Integer|老师|是|
|3|zuoye\_name|String|作业名称|是|
|4|zuoye\_uuid\_number|String|作业编号|是|
|5|zuoye\_photo|String|作业封面|是|
|6|zuoye\_types|Integer|作业类型|是|
|7|zuoye\_file|String|作业下载|是|
|8|zuoye\_content|String|作业介绍|是|
|9|zuoye\_delete|Integer|逻辑删除|是|
|10|insert\_time|Date|录入时间|是|
|11|create\_time|Date|创建时间|是|
表4.13作业提交表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|zuoye\_tijiao\_uuid\_number|String|报名唯一编号|是|
|3|zuoye\_id|Integer|作业|是|
|4|laoshi\_id|Integer|老师|是|
|5|yonghu\_id|Integer|用户|是|
|6|zuoye\_tijiao\_text|String|内容|是|
|7|zuoye\_shangchuan\_file|String|作业上传|是|
|8|zuoye\_tijiao\_yesno\_types|Integer|提交状态|是|
|9|zuoye\_tijiao\_pigai|Integer|批改分数|是|
|10|insert\_time|Date|作业提交时间|是|
|11|create\_time|Date|创建时间|是|
表4.14管理员表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|username|String|儿童名|是|
|3|password|String|密码|是|
|4|role|String|角色|是|
|5|addtime|Date|新增时间|是|

第5章 系统实现

编程人员在搭建的开发环境中，会让各种编程技术一起呈现出最终效果。本节就展示关键部分的页面效果。
## 5.1 管理员功能实现
### 5.1.1 职位招聘管理
图5.1 即为编码实现的职位招聘管理界面，管理员在职位招聘管理界面中可以对界面中显示，可以对职位招聘信息的职位招聘状态进行查看，可以新增新的职位招聘信息等。

![](/images/0300stringboot/0370springboot/blog.018.png)

图5.1 职位招聘管理界面
### 5.1.2 简历管理
图5.2 即为编码实现的简历管理界面，管理员在简历管理界面中查看简历种类信息，简历描述信息，新增简历信息等。

![](/images/0300stringboot/0370springboot/blog.019.png)

图5.2 简历管理界面
### 5.1.3 公告管理
图5.3 即为编码实现的公告管理界面，管理员在公告管理界面中新增公告，可以删除公告。

![](/images/0300stringboot/0370springboot/blog.020.png)

图5.3 公告管理界面
### 5.1.4 公告类型管理
图5.4 即为编码实现的公告类型管理界面，管理员在公告类型管理界面查看公告的工作状态，可以对公告的数据进行导出，可以新增新公告的信息，可以编辑公告信息，删除公告信息。

![](/images/0300stringboot/0370springboot/blog.021.png)

图5.4 公告类型管理界面
# 










