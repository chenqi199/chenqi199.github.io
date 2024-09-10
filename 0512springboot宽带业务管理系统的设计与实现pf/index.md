# 0512springboot宽带业务管理系统的设计与实现pf


# [0512springboot宽带业务管理系统的设计与实现pf](https://github.com/GraduationProject-springboot/0512springboot)

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

# [项目清单](https://chenqi1990.site) 包安装运行

### [github 项目仓库](https://github.com/GraduationProject-springboot/allSpringbootProjects) 开源仅有后端代码

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1eMbYemE1U?p=14)


# 第1章 绪论
## 1.1 课题背景
二十一世纪互联网的出现，改变了几千年以来人们的生活，不仅仅是生活物资的丰富，还有精神层次的丰富。在互联网诞生之前，地域位置往往是人们思想上不可跨域的鸿沟，信息的传播速度极慢，信息处理的速度和要求还是通过人们骑马或者是信鸽传递，这些信息传递都是不可控制的，中间很有可能丢失，信息的传递水平决定了人们生活的水平。如今大家都在使用互联网软件产品，从内部管理设置计算机管理，提高内部信息化的管理水准，从外部市场也可以用计算机获取相关数据进行处理，如今各行各业已经严重依赖于计算机了。

本课题研究和开发宽带业务管理系统管理系统，让安装在计算机上的该系统变成管理人员的小帮手，提高宽带业务管理系统信息处理速度，规范宽带业务管理系统信息处理流程，让管理人员的产出效益更高。
## 1.2 课题意义
传统处理数据，必须是一张张纸，然后处理完毕又是统计在一张张纸上面，不断的重复处理，最终有个结果给最高层作为参考，这个模式在互联网没有出现之前，是一种常见的事情，信息管理的效率提不上去，人多不一定力量大，因为人多肯定更加消耗资源，并且因为人类需要休息，需要管理，思想会不统一，会偷懒，所以人们研究出专门帮助人们计算的机器，就是计算机的前身，到了互联网时代，人们发现完全可以让程序供应商提供解决方案，自己挑选自己合适的方案来提高自己的产出比。所以在日常工作和生活中会发现各种各样方便人们的工具。

本课题研发的宽带业务管理系统管理系统，就是提供宽带业务管理系统信息处理的解决方案，它可以短时间处理完信息，并且这些信息都有专门的存储设备，而且数据的备份和迁移都可以设定为无人值守，从人力角度和信息处理角度以及信息安全角度，宽带业务管理系统管理系统是完胜传统纸质操作的。
## 1.3 研究内容
本文对宽带业务管理系统管理系统的设计与实现分成六个章节来说明。

第1章：研究宽带业务管理系统管理系统的背景，以及开发宽带业务管理系统管理系统的意义。

第2章：对开发宽带业务管理系统管理系统的环境还有技术进行说明。

第3章：分析宽带业务管理系统管理系统的可行性，性能，流程以及功能。

第4章：设计宽带业务管理系统管理系统的功能结构，设计数据库E-R图以及对数据表的存储结构进行设计。

第5章：实现宽带业务管理系统管理系统的功能并进行功能界面展示。

第6章：对系统测试进行阐述，以及对本系统部分功能进行检测。
# 第2章 开发环境与技术
本章节对开发宽带业务管理系统管理系统需要搭建的开发环境，还有宽带业务管理系统管理系统开发中使用的编程技术等进行阐述。
## 2.1 Spring Boot框架
Spring Boot框架是一个SpringMVC架构的快速轻量快速框架，能够帮助开发人员迅速搭建靠谱高效率的应用程序。依据自动部署和协议书，改善了Spring的研究过程，使开发人员可以更加专注于领域模型。

Spring Boot有许多特性，当中最主要的是它提供了内置Tomcat、Jetty、Undertow等Web网络服务器能够轻松搭建Web应用程序。除此之外，它也提供自动部署、无需撰写XML文件等功能。这种功能使开发人员能够迅速建立和布署应用程序，而无需解决繁杂的环境变量和其它繁琐复杂每日任务。

开发系统时，Spring Boot能够帮助开发人员完成模块化设计和松耦合的代码结构，从而更好地日常维护拓展应用程序。除此之外，它也提供了很多常见的库和部件，如Spring Data、Spring Security等，能够轻松集成化这种部件，完成数据库操作、验证、受权等功能。

2.2 MySQL数据库

MySQL是一种具有安全系数、安全系数、混合开发性、高效化等特征的轻量关联数据库智能管理系统。MySQL由C语言和C语言构成  由C语言和C语言撰写成的，由于C语言和C语言  这是混合开发的，因此MySQL源码是生命期的。MySQL提供多种多样数据种类，常见的数据种类包含[34]。伴随着数据库技术发展，MySQL逐步形成数据库管理方法的重要工具之一。它不仅能提供简单实用的操作作用，还能实现复杂多变的数据检索方法和查询记录导出方式。因为MySQL具有较好的兼容模式和扩展性，因而广泛应用于各行各业。

MySQL在WEB行业越来越受单位和个人开发者的亲睐。大部分大中小型网址都采用MySQL数据库，它不仅可以提供简单高效的数据浏览作用，还会对数据进行相应的剖析解决。因为Linux电脑操作系统和MySQL数据库全是开源系统免费体验，能够为公司节约许多费用，让很多企业使用Linux   MySQL做为网址数据库，体型小，启动速度快，也不会影响网址性能，导致用户体验感极差。

MySQL数据库能够支持各种各样操作系统的运作，包含AIX、HP-UX、OS/2 Wrap、Solaris、Mac OS、Linux和Windows等。性能好，使用便捷。因而，MySQL数据库已成为当下数据库行业最流行产品之一。MySQL数据库系统使用面向对象设计方式，客户至上开展编程设计。是利用面向对象观念来达到各项功能。它不仅能管理方法大中型数据表或关系数据库，还可以把这种复杂且庞大信息系统集成到一个简单的中小型数据库系统内。现阶段，中国很多公司早已运用了这一尖端技术。但是由于该操作系统是根据远程服务器/服务器结构的（C/S），因而，存在一些缺陷：最先，系统软件不可以提供完备的数据访问接口，客户只能依靠浏览器浏览所需要的数据；次之，系统软件并没有统一的标准，不同类型的客户端难以实现数据分享；第三，系统软件没有很好的权限管理体制。
## 2.3 Java语言技术
Java语言已经存在了25年有余。通过这些年的发展趋势，it行业在市场占有率上仍然占据一半，仍然受到了很多程序员的工作钟爱。许多从业者都是在学习培训。近年来随着从业者的提高，Java语言的位置并没减少，算得上是常青藤。Java语言学习培训比较简单，自然，它是对于C前辈们的  而言的，C  语言非常强劲。Java取消了许多特点，如go这种描述，也取消了主文件，让所有文件夹全是类，类是二维数组以及各种对象，也使Java处理一些对象的引入和回收利用，让开发者只需建立对象，应用对象，编写代码逻辑，不需要留意性能，让各种各样文件存储给Java自己解决，你能花很多时间科学研究应用软件相互关系，使研发更为集中化，如同跑车驾驶员一样，只要了解各种汽车的性能，实际操作，不需要科学研究如何生产车轮子，使软件开发更为详尽。

## 2.4 其他技术使用
spring-jdbc联接：

这是一个专业生产制造Connection对象工厂类，大部分全部用以建立数据库联接框架都是会完成这一插口，Springjdbc包就实现了这一插口，实现类是DriverManagerdasource、现阶段的项目是由DataSource的getconection方式获得配备MySQL5.7数据库连接信息。

提交Fileupload文件：

项目中应用Fileupload完成文件提交，通常是Fileupload前面提交文件提交请求，请求形式为POST：<form action="uploadServlet" method="post" ....="">请求编码方式：等候文件提交，启用Fileitem的isformField()方式，判断出表格域到底还是不是表格域，文件提交到后台管理，应用Fileupload接受文件信息，并把文件解决包存储在硬盘和库中。

Alibaba驱动：

比照各大网站Alibababababababababa.Druid是JAVA语言中比较好的数据库连接池。Druid可提供强有力的拓展和监控功能。该项目应用Alibababa.Druid开展数据库系统连接，Druid 0.1.18 以后，全部版本号都分享到maven中央仓库，在项目pome中.在xml里加入dependency就可以使用。

log4j日志：

宽带业务管理系统，其全世界错误处理和日志信息纪录，应用log4j开展日志日常维护管理与查询，其核心优势是错误处理：在logback中，应用软件里的出现异常不被应用软件认知，特性提升，关键或没有废弃物体制，log4j在很多情况下，可采取设计的一套无废弃物体制，防止经常日志搜集所引起的jvm gc。操作方法很简单，在pom中.新增log4j有关jarxml就可以。

# 第3章 系统分析
本文作者在确定了研究的课题之后，从各大数字图书馆下载文献来阅读，并了解同类型的网站具备的大致功能，然后具体事务具体分析，得出本系统要研究的具体功能与性能。虽然分析系统这一阶段性工作主要是确定功能，但它却影响着后面系统开发环节的进展，系统分析这个环节是不能少的。
## 3.1可行性分析
### 3.1.1技术可行性分析
研发设计程序流程挑选面向对象设计、功能齐全、简单实用的Java编程设计核心理念。MySQL数据库存储数据。IDEA工具作为编程软件，Windows 10计算机操作系统作为应用系统，以及数据库可视化工具等技术职称。一般来说，该程序流程的开发能够从技术上开展是可行的。
### 3.1.2经济可行性分析
开发的程序并不是向着商业程序方向设计与开发的，反而是做为一个新的毕业论文新项目开发的。它主要运用于检测小朋友们在院校所学的知识，并锻练客户使用网络、书籍和其他方式自学能力。因而，程序软件的开发不容易涉及到边际收益，也不会为软件的挑选付钱。你可以在开发软件的官网上下载所需要的软件，并依据所需要的安装方法将应用安装到你的电脑里。一般来说，开发这一程序并没有社会经济发展花费。
### 3.1.3运行可行性分析
由于程序软件就是针对大部分一般操作用户，考虑到他的知识与文化水准，尤其开发了一个可操作度高的程序软件，能够轻而易举地让用户应用，数据可视化操作页面。一般来说，从用户操作程序的角度看，这一程序其实并不难操作。只需用户开启程序，就能避免专职人员学习培训开展程序作用操作。
## 3.2 系统流程
宽带业务管理系统管理系统投入使用后，使用者如果能看到相应的流程操作图会提高程序的理解能力。
### 3.2.1 操作流程
使用者在操作宽带业务管理系统管理系统中，应该按照本系统提供的操作流程（图3.1即为本系统的操作流程图）进行操作，可以减少操作失误，从而节省进入宽带业务管理系统管理系统的时间。

![](/images/0500stringboot/0512springboot/blog.001.png)

图3.1 系统操作流程
### 3.2.2 登录流程
宽带业务管理系统管理系统通过登录功能（图3.2即为其登录的流程）引导使用者进入指定的功能操作区，也避免非本系统的用户享受本系统提供的服务以及查看本系统提供的信息，进而保证用户安全。

![](/images/0500stringboot/0512springboot/blog.002.png)

图3.2 登录流程
### 3.2.3 删除信息流程
宽带业务管理系统管理系统在经过长期使用后，会产生很多的数据信息。为了腾出存储空间存放更多的数据，本系统数据库中存储的数据，一些没有参考价值的数据需要进行删除（图3.3即为删除信息的流程），删除数据过程中，为避免误删，使用者要根据系统的提示来决定是否删除数据。

![](/images/0500stringboot/0512springboot/blog.003.png)

图3.3 删除信息流程
### 3.2.4 添加信息流程
宽带业务管理系统管理系统提供可视化的功能操作区，非常方便使用者进行数据操作，当使用者往系统中录入数据时（图3.4即为添加信息的流程），本系统也会进行数据合法性的判断，符合要求的数据才能够在数据库指定表中进行登记。

![](/images/0500stringboot/0512springboot/blog.004.png)

图3.4 添加信息流程
## 3.3 性能需求
(1)完好性

此次研发的宽带业务管理系统中记载的数据信息不可以维持为空，数据信息务必恰当查验。系统中数据联系不可以出差错，也无法弹冠相庆。数据分析表中同一数据信息在各个数据分析表里的表明具体内容应同样。

(2)技术性能

当用户操作宽带业务管理系统的各部分时，弹出来界面的响应速度不可以过长，最好是保持在3秒，较大限定数值4秒，给用户一个良好的程序流程感受。该系统还应当可以另外带上多人合作浏览宽带业务管理系统。

(3)界面要求

宽带业务管理系统界面设计方案应注意用户的日常操作习惯性，如导航条设计方案不可以在右边，彻底违背用户应用页面的操作习惯性，作用导航栏字体样式和色彩应更为醒目，便捷用户非常容易寻找，防止用户消耗太多的时间开展作用操作。

(4)安全规定

确保宽带业务管理系统的安全性，给用户一种靠谱、可信赖的觉得，系统在运行中，不可以一直出差错，与用户作用界面互动，及时沟通信息内容，系统设定登陆页面，使非系统用户无法打开系统作用界面。系统用户还填写用户名登陆密码方可进入系统主界面，充分保证系统数据信息处在运行状态。
# 第4章 系统设计
用户对着浏览器操作，肯定会出现某些不可预料的问题，但是不代表着系统对于用户在浏览器上的操作不进行处理，所以说，要提前考虑可能会出现的问题。
## 4.1 系统设计模式
宽带业务管理系统选用B/S架构模式，即电脑浏览器和服务器架构模式开发方式。现阶段这类系统架构是当前的主力，可以理解为恰当 C/S 在过去的，C/S方式架构设计需要安装当地程序流程，因而系统的扩大和移殖线相对较弱，B/S架构模式能够进行下列系统信息分布式计算材料结构维护保养，减少了系统维护保养网络资源成本，提升了定制的系统性能扩展性。在这里架构设计下，前面负责款式程序代码撰写和接口连接，后面关键负责处理事件逻辑与全过程信息控制。

系统的前面表现层款式是给用户展现前面能够免费看高清效果，用以表明渲染数据，接受后台管理传输数据，根据需求递交，交到系统后台管理开展业务逻辑解决，现阶段系统设计方案选用HTTP/HTTPS协议书通讯方式、AJAX要求，以及一些必须常见API方式的部件，系统控制层关键负责从前面推送HTTP要求中获取参数信息，减少要求，提交到后台管理controle控制层，控制层引入解决服务项目(service层)、并把它发放给不一样的处理方法服务项目(service层)，启用数据库最底层实行一系列SQL实际操作，随后回到前面SERVice层解决数据，回到json文件格式数据结果集，前面依据结果集渲染和前端显示，系统业务逻辑层挑选客户键入信息，保持特殊作用业务逻辑，浏览SQL数据；系统数据浏览层关键负责实际操作数据，为业务层或控制层给予数据服务项目；完成特殊业务需要数据适用，纪录信息实现业务。
## 4.2 功能结构设计
图4.1即为设计的管理员功能结构，管理员权限操作的功能包括管理公告，管理宽带业务管理系统信息，包括宽带管理，宽带，报修管理，论坛管理等，可以管理宽带缴费。

![结构设计图](/images/0500stringboot/0512springboot/blog.005.jpeg "结构设计图")

图4.1 管理员功能结构
## 4.3 数据库设计
宽带业务管理系统管理系统运行中产生的数据需要按照提前设置的存储规则进行保存，设计出一个符合项目的最优数据存储格式，因为它能减少用户的等待时间，还可以对系统的请求在最短时间内进行响应。所以，对数据库设计时，需要对功能需求进行详细的拆分，以及对业务状态的细分，然后设计具体的存储规则，保证数据库能正常运作，缩短数据处理时间，并在一定程度上降低数据冗余，节省存储空间。
### 4.3.1 数据库概念设计
实体-联系图还有一个名称即E-R图，是Entity Relationship Diagram各英文单词首字母的缩写，它这种概念模型通常用于对现实世界进行描述。同时它还是一种能够直观表达数据中实体，联系，属性的有效手段。绘制E-R图能够选择的工具也有很多，但是Office Visio 这款软件在E-R图的绘制上一般都是作为首选工具，因为它是基于可视化处理，使用它创建E-R图非常简单。使用基本的E-R图构成元素，比如椭圆，菱形，矩形，还有实线段来表达对应的信息，椭圆代表属性，即实体的特征，矩形代表实体，即数据库中的一个具体数据表，菱形代表实体中相互关系，实线段主要是完成椭圆，矩形，菱形的连接。

（1）下图是宽带开户实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\宽带开户.jpg](/images/0500stringboot/0512springboot/blog.006.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\宽带开户.jpg")
宽带开户实体属性图

（2）下图是用户实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\用户.jpg](/images/0500stringboot/0512springboot/blog.007.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\用户.jpg")
用户实体属性图

（3）下图是宽带实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\宽带.jpg](/images/0500stringboot/0512springboot/blog.008.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\宽带.jpg")
宽带实体属性图

（4）下图是宽带收藏实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\宽带收藏.jpg](/images/0500stringboot/0512springboot/blog.009.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\宽带收藏.jpg")
宽带收藏实体属性图

（5）下图是报修实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\报修.jpg](/images/0500stringboot/0512springboot/blog.010.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\报修.jpg")
报修实体属性图

（6）下图是业务人员实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\业务人员.jpg](/images/0500stringboot/0512springboot/blog.011.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\业务人员.jpg")
业务人员实体属性图

（7）下图是报修评价实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\报修评价.jpg](/images/0500stringboot/0512springboot/blog.012.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\报修评价.jpg")
报修评价实体属性图

（8）下图是宽带缴费实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\宽带缴费.jpg](/images/0500stringboot/0512springboot/blog.013.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\宽带缴费.jpg")
宽带缴费实体属性图

（9）下图是迁移申请实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\迁移申请.jpg](/images/0500stringboot/0512springboot/blog.014.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\迁移申请.jpg")
迁移申请实体属性图

（10）下图是论坛实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\论坛.jpg](/images/0500stringboot/0512springboot/blog.015.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\论坛.jpg")
论坛实体属性图

（11）下图是宽带留言实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\宽带留言.jpg](/images/0500stringboot/0512springboot/blog.016.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\宽带留言.jpg")
宽带留言实体属性图

（12）下图是公告实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\公告.jpg](/images/0500stringboot/0512springboot/blog.017.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\公告.jpg")
公告实体属性图

（13）下图是报修分配实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\报修分配.jpg](/images/0500stringboot/0512springboot/blog.018.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\报修分配.jpg")
报修分配实体属性图

（14）下图是宽带预约安装实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\宽带预约安装.jpg](/images/0500stringboot/0512springboot/blog.019.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\宽带预约安装.jpg")
宽带预约安装实体属性图

### 4.3.2 数据库物理设计
本小节主要任务即是根据上述内容进行数据存储结构的设计，实体的属性就用来表示字段名称，不同的字段表示的数据类型以及取值都不相同，以及该表各个字段是否能够保持空等进行说明，设计完成一张数据表的结构之后，在保存时同样要命名，尽量选择英文名称进行命名并保存，还不容易导致系统出错。接下来就对设计的表进行简单说明。

表4.1报修表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_id|Integer|用户|是|
|3|baoxiu\_name|String|报修名称|是|
|4|baoxiu\_photo|String|报修图片|是|
|5|baoxiu\_types|Integer|报修类型|是|
|6|insert\_time|Date|申请报修时间|是|
|7|baoxiu\_zhuangtai\_types|Integer|报修状态|是|
|8|baoxiu\_content|String|报修详情|是|
|9|create\_time|Date|创建时间|是|
表4.2报修评价表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|baoxiu\_id|Integer|报修|是|
|3|yonghu\_id|Integer|用户|是|
|4|baoxiu\_commentback\_text|String|评价内容|是|
|5|insert\_time|Date|评价时间|是|
|6|reply\_text|String|回复内容|是|
|7|update\_time|Date|回复时间|是|
|8|create\_time|Date|创建时间|是|
表4.3报修分配表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|baoxiu\_id|Integer|车位|是|
|3|yewurenyuan\_id|Integer|工作人员|是|
|4|fenpei\_time|Date|分配时间|是|
|5|create\_time|Date|创建时间|是|
表4.4字典表

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
表4.5宽带缴费表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_id|Integer|用户|是|
|3|feiyong\_name|String|缴费|是|
|4|feiyong\_types|Integer|缴费类型|是|
|5|feiyong\_zhuangtai\_types|Integer|缴费状态|是|
|6|feiyong\_time|String|年月|是|
|7|feiyong\_old\_money|BigDecimal|缴费金额|是|
|8|feiyong\_delete|Integer|逻辑删除|是|
|9|insert\_time|Date|录入时间|是|
|10|create\_time|Date|创建时间|是|
表4.6论坛表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|forum\_name|String|帖子标题|是|
|3|yonghu\_id|Integer|用户|是|
|4|users\_id|Integer|管理员|是|
|5|forum\_content|String|发布内容|是|
|6|super\_ids|Integer|父id|是|
|7|forum\_state\_types|Integer|帖子状态|是|
|8|insert\_time|Date|发帖时间|是|
|9|update\_time|Date|修改时间|是|
|10|create\_time|Date|创建时间|是|
表4.7公告表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|gonggao\_name|String|公告名称|是|
|3|gonggao\_photo|String|公告图片|是|
|4|gonggao\_types|Integer|公告类型|是|
|5|insert\_time|Date|公告发布时间|是|
|6|gonggao\_content|String|公告详情|是|
|7|create\_time|Date|创建时间|是|
表4.8宽带表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|kuandai\_name|String|宽带名称|是|
|3|kuandai\_uuid\_number|String|宽带编号|是|
|4|kuandai\_photo|String|宽带照片|是|
|5|kuandai\_types|Integer|宽带类型|是|
|6|kuandai\_content|String|宽带介绍|是|
|7|kuandai\_delete|Integer|逻辑删除|是|
|8|insert\_time|Date|录入时间|是|
|9|create\_time|Date|创建时间|是|
表4.9宽带收藏表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|kuandai\_id|Integer|宽带|是|
|3|yonghu\_id|Integer|用户|是|
|4|kuandai\_collection\_types|Integer|类型|是|
|5|insert\_time|Date|收藏时间|是|
|6|create\_time|Date|创建时间|是|
表4.10宽带留言表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|kuandai\_id|Integer|商品|是|
|3|yonghu\_id|Integer|用户|是|
|4|kuandai\_liuyan\_text|String|留言内容|是|
|5|insert\_time|Date|留言时间|是|
|6|reply\_text|String|回复内容|是|
|7|update\_time|Date|回复时间|是|
|8|create\_time|Date|创建时间|是|
表4.11宽带开户表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|kuandai\_order\_uuid\_number|String|订单编号|是|
|3|kuandai\_id|Integer|宽带|是|
|4|yonghu\_id|Integer|用户|是|
|5|kuandai\_order\_types|Integer|订单类型|是|
|6|insert\_time|Date|订单创建时间|是|
|7|create\_time|Date|创建时间|是|
表4.12宽带预约安装表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|kuandai\_id|Integer|宽带|是|
|3|yonghu\_id|Integer|用户|是|
|4|kuandai\_yuyue\_text|String|理由|是|
|5|kuandai\_yuyue\_address|String|地点|是|
|6|kuandai\_yuyue\_yesno\_types|Integer|报名状态|是|
|7|kuandai\_yuyue\_yesno\_text|String|审核回复|是|
|8|kuandai\_yuyue\_shenhe\_time|Date|审核时间|是|
|9|insert\_time|Date|活动报名时间|是|
|10|create\_time|Date|创建时间|是|
表4.13迁移申请表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|qianyi\_yuyue\_uuid\_number|String|报名唯一编号|是|
|3|yonghu\_id|Integer|用户|是|
|4|qianyi\_yuyue\_text|String|理由|是|
|5|qianyi\_yuyue\_yesno\_types|Integer|报名状态|是|
|6|qianyi\_yuyue\_yesno\_text|String|审核回复|是|
|7|qianyi\_yuyue\_shenhe\_time|Date|审核时间|是|
|8|insert\_time|Date|活动报名时间|是|
|9|create\_time|Date|创建时间|是|
表4.14业务人员表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yewurenyuan\_name|String|业务人员姓名|是|
|3|yewurenyuan\_phone|String|业务人员手机号|是|
|4|yewurenyuan\_id\_number|String|业务人员身份证号|是|
|5|yewurenyuan\_photo|String|业务人员头像|是|
|6|new\_money|BigDecimal|余额|是|
|7|yewurenyuan\_email|String|业务人员邮箱|是|
|8|create\_time|Date|创建时间|是|
表4.15用户表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_name|String|用户姓名|是|
|3|yonghu\_phone|String|用户手机号|是|
|4|yonghu\_id\_number|String|用户身份证号|是|
|5|yonghu\_photo|String|用户头像|是|
|6|new\_money|BigDecimal|余额|是|
|7|yonghu\_email|String|用户邮箱|是|
|8|create\_time|Date|创建时间|是|
表4.16管理员表

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
### 5.1.1 宽带管理
图5.1 即为编码实现的宽带管理界面，管理员在宽带管理界面中可以对界面中显示，可以对宽带信息的宽带状态进行查看，可以添加新的宽带信息等。

![](/images/0500stringboot/0512springboot/blog.020.png)

图5.1 宽带管理界面
### 5.1.2 报修管理
图5.2 即为编码实现的报修管理界面，管理员在报修管理界面中查看新增报修信息等。

![](/images/0500stringboot/0512springboot/blog.021.png)

图5.2 报修管理界面
### 5.1.3 宽带缴费管理
图5.3 即为编码实现的宽带缴费管理界面，管理员在宽带缴费管理界面中新增宽带缴费，可以删除宽带缴费。

![](/images/0500stringboot/0512springboot/blog.022.png)

图5.3 宽带缴费管理界面
### 5.1.4 公告管理
图5.4 即为编码实现的公告管理界面，管理员在公告管理界面查看公告的工作状态，可以对公告的数据进行导出，可以添加新公告的信息，可以编辑公告信息，删除公告信息。

![](/images/0500stringboot/0512springboot/blog.023.png)

图5.4 公告管理界面
## 5.2 用户功能实现
### 5.2.1 宽带缴费
图5.5 即为编码实现的宽带缴费界面。

![](/images/0500stringboot/0512springboot/blog.024.png)

图5.5 宽带缴费界面
### 5.2.2 宽带管理
图5.6 即为编码实现的宽带界面。

![](/images/0500stringboot/0512springboot/blog.025.png)

图5.6 宽带界面
### 5.2.3 论坛管理
图5.7 即为编码实现的论坛管理界面。

图5.7 论坛管理界面
# 










