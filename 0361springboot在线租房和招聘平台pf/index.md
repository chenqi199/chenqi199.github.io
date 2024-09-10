# 0361springboot在线租房和招聘平台pf


# [0361springboot在线租房和招聘平台pf](https://github.com/GraduationProject-springboot/0361springboot)

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

# [项目清单](https://chenqi1990.site) 包安装运行

### [github 项目仓库](https://github.com/GraduationProject-springboot/allSpringbootProjects) 开源仅有后端代码

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1T1bpekEK7?p=33)


# 第1章 绪论
## 1.1 课题背景
二十一世纪互联网的出现，改变了几千年以来人们的生活，不仅仅是生活物资的丰富，还有精神层次的丰富。在互联网诞生之前，地域位置往往是人们思想上不可跨域的鸿沟，信息的传播速度极慢，信息处理的速度和要求还是通过人们骑马或者是信鸽传递，这些信息传递都是不可控制的，中间很有可能丢失，信息的传递水平决定了人们生活的水平。如今大家都在使用互联网软件产品，从内部管理设置计算机管理，提高内部信息化的管理水准，从外部市场也可以用计算机获取相关数据进行处理，如今各行各业已经严重依赖于计算机了。

本课题研究和开发在线租房和招聘平台管理系统，让安装在计算机上的该系统变成管理人员的小帮手，提高在线租房和招聘平台信息处理速度，规范在线租房和招聘平台信息处理流程，让管理人员的产出效益更高。
## 1.2 课题意义
传统处理数据，必须是一张张纸，然后处理完毕又是统计在一张张纸上面，不断的重复处理，最终有个结果给最高层作为参考，这个模式在互联网没有出现之前，是一种常见的事情，信息管理的效率提不上去，人多不一定力量大，因为人多肯定更加消耗资源，并且因为人类需要休息，需要管理，思想会不统一，会偷懒，所以人们研究出专门帮助人们计算的机器，就是计算机的前身，到了互联网时代，人们发现完全可以让程序供应商提供解决方案，自己挑选自己合适的方案来提高自己的产出比。所以在日常工作和生活中会发现各种各样方便人们的工具。

本课题研发的在线租房和招聘平台管理系统，就是提供在线租房和招聘平台信息处理的解决方案，它可以短时间处理完信息，并且这些信息都有专门的存储设备，而且数据的备份和迁移都可以设定为无人值守，从人力角度和信息处理角度以及信息安全角度，在线租房和招聘平台管理系统是完胜传统纸质操作的。
## 1.3 研究内容
本文对在线租房和招聘平台管理系统的设计与实现分成六个章节来说明。

第1章：研究在线租房和招聘平台管理系统的背景，以及开发在线租房和招聘平台管理系统的意义。

第2章：对开发在线租房和招聘平台管理系统的环境还有技术进行说明。

第3章：分析在线租房和招聘平台管理系统的可行性，性能，流程以及功能。

第4章：设计在线租房和招聘平台管理系统的功能结构，设计数据库E-R图以及对数据表的存储结构进行设计。

第5章：实现在线租房和招聘平台管理系统的功能并进行功能界面展示。

第6章：对系统测试进行阐述，以及对本系统部分功能进行检测。
# 第2章 开发环境与技术
本章节对开发在线租房和招聘平台管理系统需要搭建的开发环境，还有在线租房和招聘平台管理系统开发中使用的编程技术等进行阐述。
## 2.1 Java语言
电子计算机程序可以用很多不同的编程语言撰写，但到现在为止，Java语言依旧是IT行业深受认同和常用的编程语言之一。因而，在撰写这一程序时，大家毫不犹豫的挑选Java语言做为编程语言。经过多年发展，Java语言不但在Web开发设计行业作出了杰出贡献，并且广泛用于大数据工程师和Android应用程序开发。Java程序作为一种面向对象开源系统编程语言，无法直接在各类软件上运作，必须在操作系统上配置作业环境，包含安装及设定数据分析软件和Java编程工具。在Windows中 7、Windows 在10或其它操作系统上配置Java程序的作业环境时，要确保配置的成功实施，才能使Java程序成功运作。
## 2.2 Spring Boot框架
Spring Boot是一个根据Spring框架的轻量快速开发框架，能够帮助开发者迅速搭建靠谱高效率应用程序。根据自动部署和协议书好于配备，优化了Spring的研发流程，使开发者可以更加致力于业务逻辑。

Spring Boot有许多特性，其中最重要的是它提供了内置的Tomcat、Jetty、Undertow等Web服务器，可以轻松构建Web应用程序。另外，它还提供了自动配置、无需编写XML文件、等功能。这些特性使得开发人员可以快速创建和部署应用程序，而无需处理复杂的配置文件和其他繁琐的任务。

## 2.3 B/S架构
B/S架构（Browser/Server Architecture）它是一种常见的软件开发架构。其主要由手机客户端浏览器和服务器构成。手机客户端浏览器负责操作界面的展现和互动，服务器负责业务逻辑的处理方法和文件存储。B与传统C/S架构对比，/S架构具有更高的扩展性、便于日常维护布署等特点，因而在当代软件开发中得到广泛应用。

在B/S架构下，手机客户端浏览器应用HTML、CSS、JavaScript等Web科研开发网页页面积极与服务器的数据交换实现业务作用。服务器应用Java等各种编程语言、Python等完成业务逻辑，根据数据存储数据信息。全部体系结构清楚，完成了静态页面，大大提升了软件开发的效率和效果。

在B/S架构中，前端工程师工作人员关键负责网页页面设计和完成，而后端工程师工作人员则负责解决业务逻辑和文件存储。前端和后端分开的开发方式有益于团队协作和责任分工。每个人专注自己擅长领域，提升了研发效率。与此同时，该架构还充分利用了浏览器的优点，完成更强的使用体验。

总而言之，B/S架构已经成为当代软件开发的主力，用途广泛。它的存在使软件开发更高效、灵便、便于维护保养，让我们更加重视业务逻辑的完成和客户体验的提高。
## 2.4 Vue框架
Vue是一种最流行的JavaScript前端框架，它是由Evannn构成 You开发设计。Vue具备轻量、易学易用的特征，其核心库只关注视图层，便于与其它库或目前项目集成。Vue带来了相近Angular的双向数据绑定和React的组件开发方式，还提供了虚似DOM、模板编译程序等先进特点，使开发者能够迅速搭建可器重、可维修的当代Web应用软件。

Vue有着丰富的生态体系，包含Vue Router、Vuex等官方网软件，及其很多第三方插件和公共图书馆。Vue的模板词法简单易懂，让开发者快速入门。除此之外，Vue的回应数据绑定和动态组件系统软件还能提高应用软件性能和客户体验。

简单点来说，Vue是一个迅速、灵便、易学易用的前端框架，主要适用于体量的Web应用程序开发。

# 第3章 系统分析
本文作者在确定了研究的课题之后，从各大数字图书馆下载文献来阅读，并了解同类型的网站具备的大致功能，然后具体事务具体分析，得出本系统要研究的具体功能与性能。虽然分析系统这一阶段性工作主要是确定功能，但它却影响着后面系统开发环节的进展，系统分析这个环节是不能少的。
## 3.1 可行性分析
从三个不同的角度来分析，确保开发成功的前提是有可行性分析，只有进行提前分析，符合程序开发流程才不至于开发过程的中断。
### 3.1.1 技术可行性
在技术实现层次，分析了好几种技术实现方法，并且都有对应的成功案例，也有很多开源模块可以进行参考，所以从技术可行性分析来讲，实现在线租房和招聘平台管理系统是没有问题的。
### 3.1.2 经济可行性
开发的程序并不是向着商业服务程序方向设计与开发的，反而是做为毕业设计论文新项目开发的，主要运用于检测孩子在学校所学的知识，也锻练用户们使用互联网、书籍和别的方法进行自学能力。因而，该程序软件的开发不容易涉及到边际效益，也不会为软件的挑选付钱。你可以在开发软件的官网上下载所需要的软件，并根据要求的安装方法将软件安装在你的电脑中。一般来说，开发这一程序并没有经济发展开支。
### 3.1.3 操作可行性
在线租房和招聘平台管理系统的具体实现，本身参考人类的正常操作逻辑，把常用的操作习惯当做主要的导航实现，可以让使用者更快速的理解并且上手操作，实现符合逻辑的操作流程是操作可行性的具体体现。

以上就是从不同的角度来分析，确保了在线租房和招聘平台管理系统的正常开展。
## 3.2 系统流程
在线租房和招聘平台管理系统投入使用后，使用者如果能看到相应的流程操作图会提高程序的理解能力。
### 3.2.1 操作流程
使用者在操作在线租房和招聘平台管理系统中，应该按照本系统提供的操作流程（图3.1即为本系统的操作流程图）进行操作，可以减少操作失误，从而节省进入在线租房和招聘平台管理系统的时间。

![](/images/0300stringboot/0361springboot/blog.001.png)

图3.1 系统操作流程
### 3.2.2 登录流程
在线租房和招聘平台管理系统通过登录功能（图3.2即为其登录的流程）引导使用者进入指定的功能操作区，也避免非本系统的用户享受本系统提供的服务以及查看本系统提供的信息，进而保证用户安全。

![](/images/0300stringboot/0361springboot/blog.002.png)

图3.2 登录流程
### 3.2.3 删除信息流程
在线租房和招聘平台管理系统在经过长期使用后，会产生很多的数据信息。为了腾出存储空间存放更多的数据，本系统数据库中存储的数据，一些没有参考价值的数据需要进行删除（图3.3即为删除信息的流程），删除数据过程中，为避免误删，使用者要根据系统的提示来决定是否删除数据。

![](/images/0300stringboot/0361springboot/blog.003.png)

图3.3 删除信息流程
### 3.2.4 添加信息流程
在线租房和招聘平台管理系统提供可视化的功能操作区，非常方便使用者进行数据操作，当使用者往系统中录入数据时（图3.4即为添加信息的流程），本系统也会进行数据合法性的判断，符合要求的数据才能够在数据库指定表中进行登记。

![](/images/0300stringboot/0361springboot/blog.004.png)

图3.4 添加信息流程
## 3.3 性能需求
需求分析少不了对项目用到的硬件设备进行分析，这样才符合正常的分析流程。只谈功能需求不谈性能需求，是一件很严重的事情，可能会导致一些不可控的问题出现。

以下从这几个角度来分析系统性能。

(1)系统数据的容量：从数据角度来分析，每个表和每个数据库，达到的数据量到一定的程度，是否需要分表或者是分库，超过了数据的设定限度，可能会导致数据反映迟钝，容错量增加。

(2)数据精度的要求：需要对需求分析里面数据设定环节，考虑相应的数据精度问题，需要发现数据是常用的精度还是非常用的精度，进而设定不同的数值。

(3)时间响应要求：从用户提交操作，到页面反映，中间有个数据处理的问题，需要考虑预测数据量的大小，提前预案分库分表的设计，数据量再大就要考虑增加列式数据库的问题，这些都不是一拍脑门就能决定的，都需要经验和同行业的数据分析研判，才能符合用户的要求，毕竟响应时间太久操作起来也不舒服。

(4)普适性问题：用户使用应该不需要感知服务端的数据量问题或者响应问题，只需要任意一台电脑，不需要更多的操作，打开浏览器就能用，太多的设置以及操作，不符合普适性操作。

(5)页面设计问题：功能符合要求之后，肯定是要丰富页面的。页面设计才是用户长时间面对的问题，首先考虑数据的整洁性，让页面看起来更加的清爽。颜色与数据方面，该不同颜色就不同颜色，降低用户长时间使用出现的视觉疲劳，让用户使用起来心情不至于太差。

(6)系统的稳定性：正常用户操作系统页面，必须是该提交提交，正常输入符合逻辑，不能随随便便的就出各种问题，导致用户操作疲惫，并且输入的数据和回显的数据符合用户的要求。如果正常操作都会出现问题，那设计就是不稳定的，这一点肯定不行。只要是与数据进行交互的系统，都必须稳定。系统稳定从开发部署角度上来分析，可以考虑数据的冗余备份功能，自动值守功能，机房数据同步，机房分开的功能，这些都可以让系统的稳定性得到提升。

系统的性能需求需要对业务很熟练的情况下判断然后分析，再从系统性能需求来逐条实现，可以让设计的系统有使用价值。
## 3.4 功能需求
在线租房和招聘平台管理系统根据使用权限的角度进行功能分析，并运用用例图来展示各个权限需要操作的功能。
# 第4章 系统设计
用户对着浏览器操作，肯定会出现某些不可预料的问题，但是不代表着系统对于用户在浏览器上的操作不进行处理，所以说，要提前考虑可能会出现的问题。
## 4.1 系统设计思想
在设备设计过程中，遵照对应的设计原理至关重要。这种设计原理能够帮助室内设计师在短期内制作出合乎设计标准设计方案。下列应该是各种各样设计原理的简略论述：

稳定性：软件的稳定性取决于它是不是被用户应用。设计方案不安全的软件，用户很没有毅力应用。为了能确保程序的稳定性，应该考虑程序的各个领域，如异常处理、容错纠错机制、数据库备份等，以尽量减少程序不正确的概率。

安全系数：程序软件担负信息内容储存和体系等重大事项，因而安全系数不够的软件可能会对用户导致重大损失。因而，在设备设计过程中，安全就是一定要考虑的重要因素之一。除开确保程序自身的安全性外，还要考虑到传送数据、身份认证、密码加密等多种因素，以确保用户的网络信息安全。

支持定制：市场情况从没保持一致。应对目标客户、使用场景和市场需求转变，程序软件也要便于调节以满足各种转变。支持定制的完成应该考虑程序的模块化，便于用户可以根据实际情况加上、删掉或修改作用。

可扩展性：在程序软件的高效运行使用中，应该及时引进现阶段的技术开展系统，主要在系统的功能方面及系统性能方面进行一定的拓展。唯有如此，系统软件才可以现实生活中再次占据市场。可扩展性的完成应该考虑程序的可插拔性，即特色功能能通过软件或控制模块导入到系统内，且不危害初始系统架构图和结构。

可扩展性：程序软件日常维护需要一定的资产，不论是清除目前程序不正确或是软件更改的目前要求，都要在软件技术层面资金投入一定资金。因而，便于维修的软件程序能够减少技术方面资金耗费。可扩展性的完成应该考虑程序的易读性、可重构性与可测试性，以推动后面日常维护工作的顺利开展。可更新性：程序软件的交付使用可能面临用户的不断增加，用户对软件的使用率都将提升。因而，遇到这样的情况，系统软件仍需要根据更新来维持科学合理的性能，以适应市场。
## 4.2 功能结构设计
图4.1即为设计的管理员功能结构，管理员权限操作的功能包括管理平台资讯，管理在线租房和招聘平台信息，包括房屋管理，培训管理，招聘管理，薪资管理等，可以管理平台资讯。

![结构设计图](/images/0300stringboot/0361springboot/blog.005.jpeg "结构设计图")

图4.1 管理员功能结构
## 4.3 数据库设计
开发一个系统软件还要提前设计方案数据库。这儿的数据库是统计数据的结合，存放在一起的数据信息都是按照一定的组织模式所进行的。现阶段，数据库能够立足于多种多样应用软件，这是因为其数据存储方式最好是，具备数据冗余率不高的优势。尽管数据库为应用程序给予信息存储服务，但它还能与程序流程维持相对较高的自觉性。总而言之，数据库经历了很长一段时间的高速发展，从最开始的不明，到现在的知名，其有关技术日趋成熟，但是也有扎实的理论基础。
### 4.3.1 数据库概念设计
实体-联系图还有一个名称即E-R图，是Entity Relationship Diagram各英文单词首字母的缩写，它这种概念模型通常用于对现实世界进行描述。同时它还是一种能够直观表达数据中实体，联系，属性的有效手段。绘制E-R图能够选择的工具也有很多，但是Office Visio 这款软件在E-R图的绘制上一般都是作为首选工具，因为它是基于可视化处理，使用它创建E-R图非常简单。使用基本的E-R图构成元素，比如椭圆，菱形，矩形，还有实线段来表达对应的信息，椭圆代表属性，即实体的特征，矩形代表实体，即数据库中的一个具体数据表，菱形代表实体中相互关系，实线段主要是完成椭圆，矩形，菱形的连接。

（1）下图是房屋实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\房屋.jpg](/images/0300stringboot/0361springboot/blog.006.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\房屋.jpg")
房屋实体属性图

（2）下图是用户实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\用户.jpg](/images/0300stringboot/0361springboot/blog.007.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\用户.jpg")
用户实体属性图

（3）下图是职位留言实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\职位留言.jpg](/images/0300stringboot/0361springboot/blog.008.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\职位留言.jpg")
职位留言实体属性图

（4）下图是简历实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\简历.jpg](/images/0300stringboot/0361springboot/blog.009.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\简历.jpg")
简历实体属性图

（5）下图是简历投递实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\简历投递.jpg](/images/0300stringboot/0361springboot/blog.010.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\简历投递.jpg")
简历投递实体属性图

（6）下图是房屋评价实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\房屋评价.jpg](/images/0300stringboot/0361springboot/blog.011.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\房屋评价.jpg")
房屋评价实体属性图

（7）下图是房屋订单实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\房屋订单.jpg](/images/0300stringboot/0361springboot/blog.012.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\房屋订单.jpg")
房屋订单实体属性图

（8）下图是论坛实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\论坛.jpg](/images/0300stringboot/0361springboot/blog.013.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\论坛.jpg")
论坛实体属性图

（9）下图是企业实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\企业.jpg](/images/0300stringboot/0361springboot/blog.014.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\企业.jpg")
企业实体属性图

（10）下图是房东实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\房东.jpg](/images/0300stringboot/0361springboot/blog.015.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\房东.jpg")
房东实体属性图

（11）下图是职位收藏实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\职位收藏.jpg](/images/0300stringboot/0361springboot/blog.016.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\职位收藏.jpg")
职位收藏实体属性图

（12）下图是平台资讯实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\平台资讯.jpg](/images/0300stringboot/0361springboot/blog.017.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\平台资讯.jpg")
平台资讯实体属性图

（13）下图是房屋收藏实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\房屋收藏.jpg](/images/0300stringboot/0361springboot/blog.018.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\房屋收藏.jpg")
房屋收藏实体属性图

（14）下图是职位招聘实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\职位招聘.jpg](/images/0300stringboot/0361springboot/blog.019.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\职位招聘.jpg")
职位招聘实体属性图
### 4.3.2 数据库物理设计
本课题数据库是一个关系数据库，因此二维表的结构设计都比较重要。终究，二维表格实体模型是关系数据库里的关系模型。在设计关系模型以前，还要了解一些常见的关系模型这个概念。充分了解了表构造设计最常见的定义后，我们应该应用以前绘制的E-R实体模型去完成表结构的设计，并且在库中建立数据分析表，并取名每一个数据分析表。下列设计结论以表格形式表明。

表4.1字典表

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
表4.2房东表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|fangdong\_name|String|房东姓名|是|
|3|fangdong\_phone|String|房东手机号|是|
|4|fangdong\_id\_number|String|房东身份证号|是|
|5|fangdong\_photo|String|房东头像|是|
|6|fangdong\_email|String|房东邮箱|是|
|7|new\_money|BigDecimal|余额|是|
|8|create\_time|Date|创建时间|是|
表4.3房屋表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|fangdong\_id|Integer|房东|是|
|3|fangwu\_name|String|房屋名称|是|
|4|fangwu\_uuid\_number|String|房屋编号|是|
|5|fangwu\_photo|String|房屋照片|是|
|6|fangwu\_address|String|房屋地点|是|
|7|fangwu\_types|Integer|房屋类型|是|
|8|zan\_number|Integer|赞|是|
|9|cai\_number|Integer|踩|是|
|10|fangwu\_new\_money|BigDecimal|租金|是|
|11|fangwu\_content|String|房屋介绍|是|
|12|fangwu\_delete|Integer|逻辑删除|是|
|13|insert\_time|Date|录入时间|是|
|14|create\_time|Date|创建时间|是|
表4.4房屋收藏表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|fangwu\_id|Integer|房屋|是|
|3|yonghu\_id|Integer|用户|是|
|4|fangwu\_collection\_types|Integer|类型|是|
|5|insert\_time|Date|收藏时间|是|
|6|create\_time|Date|创建时间|是|
表4.5房屋评价表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|fangwu\_id|Integer|房屋|是|
|3|yonghu\_id|Integer|用户|是|
|4|fangwu\_commentback\_text|String|评价内容|是|
|5|insert\_time|Date|评价时间|是|
|6|reply\_text|String|回复内容|是|
|7|update\_time|Date|回复时间|是|
|8|create\_time|Date|创建时间|是|
表4.6房屋订单表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|fangwu\_order\_uuid\_number|String|订单编号|是|
|3|fangwu\_id|Integer|房屋|是|
|4|yonghu\_id|Integer|用户|是|
|5|fangwu\_order\_true\_price|BigDecimal|实付价格|是|
|6|fangwu\_order\_types|Integer|订单类型|是|
|7|insert\_time|Date|订单创建时间|是|
|8|create\_time|Date|创建时间|是|
表4.7论坛表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|forum\_name|String|帖子标题|是|
|3|yonghu\_id|Integer|用户|是|
|4|fangdong\_id|Integer|房东|是|
|5|gongsi\_id|Integer|公司|是|
|6|users\_id|Integer|管理员|是|
|7|forum\_content|String|发布内容|是|
|8|super\_ids|Integer|父id|是|
|9|forum\_types|Integer|帖子类型|是|
|10|forum\_state\_types|Integer|帖子状态|是|
|11|insert\_time|Date|发帖时间|是|
|12|update\_time|Date|修改时间|是|
|13|create\_time|Date|创建时间|是|
表4.8平台资讯表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|gonggao\_name|String|平台资讯名称|是|
|3|gonggao\_photo|String|平台资讯图片|是|
|4|gonggao\_types|Integer|平台资讯类型|是|
|5|insert\_time|Date|发布时间|是|
|6|gonggao\_content|String|平台资讯详情|是|
|7|create\_time|Date|创建时间|是|
表4.9企业表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|gongsi\_name|String|企业名称|是|
|3|gongsi\_types|Integer|企业类型|是|
|4|gongsi\_phone|String|联系方式|是|
|5|gongsi\_email|String|邮箱|是|
|6|gongsi\_photo|String|企业封面|是|
|7|gongsi\_content|String|企业简介|是|
|8|gongsi\_delete|Integer|逻辑删除|是|
|9|create\_time|Date|创建时间|是|
表4.10简历表

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
表4.11简历投递表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|jianli\_id|Integer|简历|是|
|3|zhaopin\_id|Integer|招聘|是|
|4|mianshi\_yesno\_types|Integer|投递状态|是|
|5|mianshi\_yesno\_text|String|投递回复|是|
|6|insert\_time|Date|投递时间|是|
|7|create\_time|Date|创建时间|是|
表4.12用户表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_name|String|用户姓名|是|
|3|yonghu\_phone|String|用户手机号|是|
|4|yonghu\_id\_number|String|用户身份证号|是|
|5|yonghu\_photo|String|用户头像|是|
|6|yonghu\_email|String|用户邮箱|是|
|7|new\_money|BigDecimal|余额|是|
|8|create\_time|Date|创建时间|是|
表4.13职位招聘表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|gongsi\_id|Integer|企业|是|
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
表4.14职位收藏表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|zhaopin\_id|Integer|职位|是|
|3|yonghu\_id|Integer|用户|是|
|4|zhaopin\_collection\_types|Integer|类型|是|
|5|insert\_time|Date|收藏时间|是|
|6|create\_time|Date|创建时间|是|
表4.15职位留言表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|zhaopin\_id|Integer|职位|是|
|3|yonghu\_id|Integer|用户|是|
|4|zhaopin\_liuyan\_text|String|留言内容|是|
|5|reply\_text|String|回复内容|是|
|6|insert\_time|Date|留言时间|是|
|7|update\_time|Date|回复时间|是|
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
### 5.1.1 房屋管理
图5.1 即为编码实现的房屋管理界面，管理员在房屋管理界面中可以对界面中显示，可以对房屋信息的房屋状态进行查看，可以添加新的房屋信息等。

![](/images/0300stringboot/0361springboot/blog.020.png)

图5.1 房屋管理界面
### 5.1.2 招聘管理
图5.2 即为编码实现的招聘管理界面，管理员在招聘管理界面中查看招聘种类信息，招聘描述信息，新增招聘信息等。

![](/images/0300stringboot/0361springboot/blog.021.png)

图5.2 招聘管理界面
### 5.1.3 平台资讯管理
图5.3 即为编码实现的平台资讯管理界面，管理员在平台资讯管理界面中新增平台资讯，可以删除平台资讯。

![](/images/0300stringboot/0361springboot/blog.022.png)

图5.3 平台资讯管理界面
### 5.1.4 平台资讯类型管理
图5.4 即为编码实现的平台资讯类型管理界面，管理员在平台资讯类型管理界面查看平台资讯的工作状态，可以对平台资讯的数据进行导出，可以添加新平台资讯的信息，可以编辑平台资讯信息，删除平台资讯信息。

![](/images/0300stringboot/0361springboot/blog.023.png)

图5.4 平台资讯类型管理界面
# 










