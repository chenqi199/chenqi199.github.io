# 0270springboot制造装备物联及生产管理ERP系统


# [项目清单 包安装运行](http://chenqi1990.site) 官网地址 http://chenqi1990.site

# [0270springboot制造装备物联及生产管理ERP系统](https://github.com/GraduationProject-springboot/0270springboot)

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### [github 项目仓库](https://github.com/GraduationProject-springboot/allSpringbootProjects) 开源仅有后端代码

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1ULbQeREgz?p=1)

# 第1章 绪论
## 1.1选题动因
当前的网络技术，软件技术等都具备成熟的理论基础，市场上也出现各种技术开发的软件，这些软件都被用于各个领域，包括生活和工作的领域。随着电脑和笔记本的广泛运用，以及各种计算机硬件的完善和升级，市面上的电脑和笔记本的性能都得到提升，可以支持的软件也逐渐增多，因此，在计算机上安装软件来发挥其高效地信息处理的作用，则很受人们的青睐。对于公交信息来讲，通过手工形式处理，在面对庞大的信息数量时，就显得不适宜了，首先需要花费的时间比较多，其次数据出错率比较高，而且对错误的数据进行更改也比较困难，最后，检索数据费事费力。因此，为了解决上述问题，有必要建立制造装备物联及生产管理ERP系统，来规范公交信息管理流程，让管理工作可以系统化和程序化，同时，制造装备物联及生产管理ERP系统的有效运用可以帮助管理人员准确快速地处理信息。
## 1.2目的和意义
制造装备物联及生产管理ERP系统可以对公交信息进行集中管理，可以真正避免传统管理的缺陷。制造装备物联及生产管理ERP系统是一款运用软件开发技术设计实现的应用系统，在信息处理上可以达到快速的目的，不管是针对数据添加，数据维护和统计，以及数据查询等处理要求，制造装备物联及生产管理ERP系统都可以轻松应对。所以，制造装备物联及生产管理ERP系统的运用是让公交信息管理升级的最好方式。它可以实现信息处理的便利化要求，还可以规范信息处理的流程，让事务处理成为管理人员手中的一件简单事，而不是之前手工处理时的困难事。尽管制造装备物联及生产管理ERP系统具备较完善的功能，但是也需要管理人员利用闲暇时间提升自身素质以及个人能力，在操作制造装备物联及生产管理ERP系统时可以最大化运用制造装备物联及生产管理ERP系统提供的功能，让系统在满足高效率处理数据的同时，也能始终稳定运行，还可以确保数据的可靠性与数据处理的质量。
## 1.3论文结构安排
本文总共分为6个章节，每个章节都对本系统描述了不同的内容。接下来就对本文的研究内容进行阐述。

第1章：这个章节是论文的绪论部分。从选题的背景和意义的角度阐述即将开发的系统。

第2章：这个章节是技术介绍部分。从本系统需要运用的技术知识的角度阐述系统。

第3章：这个章节是系统分析部分。从分析系统可行性，分析系统功能和性能等角度阐述系统。

第4章：这个章节是系统设计部分。从系统功能结构的角度和数据库设计的角度阐述系统。

第5章：这个章节是系统实现部分。从系统功能模块运行效果的角度阐述系统。

第6章：这个章节是系统测试部分。从测试系统功能，系统测试方法的角度阐述系统。


# 第2章 开发环境与技术
开发制造装备物联及生产管理ERP系统需要搭建编程的环境，也需要通过调查，对各个相关技术进行分析，选取适合本系统开发的技术与工具。
## 2.1 MYSQL数据库
题目确定了是一个应用程序之后，就开始按部就班的进行设计与分析。本课题是需要数据库作为数据管理工具以及数据载体，从程序功能分析到数据分析，选择合适的关系型数据库是当下所选择的重要环节。关系型数据库可选择余地不多，本身甲骨文公司的两个，微软的两个，IBM的一个，也就是这五个了，功能和差异都不影响数据库的选择，因为这些数据库都能实现应用程序功能所需的，那么只能从其他的方面来综合考虑哪种数据库更合适。作为开发使用的电脑硬件上来讲，还是大一的时候买的，当初并没有太多的钱买好一点的电脑，只是作为学习用的，所以经过这么几年的使用，电脑老化了，性能下降也比较厉害，还有好多需要用的学习资料，本身面临毕业，选择学校机房也不是一个长久的打算，选择一个数据库适合自己的老旧笔记本电脑作为学习开发当前的应用，是最重要的。综合考虑的结果就是选用MySQL数据库作为应用数据库，因为MySQL数据库体积小，占用内存小，不影响电脑上其他用的软件运行，并且不需要因为安装维护MySQL数据库而重装系统，最终选择的数据库就是MySQL数据库。
## 2.2 Tomcat 介绍
刚开始学习Java语言的时候，是不知道还有Tomcat这些东西的，各种语法各种输出在控制台进行输出结果，当Java网站开发的时候就不可避免的学习到了Tomcat服务器。Tomcat准确的来讲不算是服务器，可以说是vue引擎或者一个容器，这些都是学术上或者原理上都比较贴切的，但是实际工作中Tomcat就是作为一个web服务器来用的，因为可以实现网站的发布和运行。因为工作原理的原因，Tomcat一般作为中小型企业和并发量并不突出的一种轻量级的服务器存在的，比如某些行业的应用系统，本身客户端就不多，需要的连接也不多，一般都用Tomcat的。Tomcat里面可以配置多个网站，配置文件后缀是config的文档，类似于XML的结构，比较清晰明了。每当Java发布新的版本的时候，Tomcat也会为了匹配Java的版本进行升级，目前Tomcat版本已经到版本10了。Tomcat标识是一只有点发黄的小猫咪，当Tomcat配置成功一般测试的时候能看到这个小猫咪就算是成功的，才能进行下一步的配置。Tomcat服务器在Java网站开发中还是挺合适的。
## 2.3 vue技术
vue技术可以让初学者尽快上手进行编写动态网站，不需要变成高级的Java编程人员才可以书写代码，从学习的效率还有编写的效率上都有很大的提升。让着重于网页开发者与着重于后台逻辑开发进行分离合作开发变成了一种可能，降低了学习成本，不需要考虑程序运行解释编译阶段的话，vue网页本身就可以理解成一个普通的Servlet。vue结构上面，主要分为两个方面，一个是专属的vue引擎，通俗的讲就是可以实现vue编译后运行解释的一个东西，另一个就是web服务器。vue运行编译需要vue引擎和web服务器进行配合以及相互协作，当然他们的分工也是很明确的，这样才可以真正的运行起来。vue容器和引擎有Tomcat，这个Tomcat其实也还有Apache静态解释代码的部分，虽然看起来运行效果差不多，但是其实是两个截然不同的工具，在文件系统里目录也是不一样的，当然如果有特殊需求也是可以进行特殊的配置的，配置上面还是比较灵活的。虽然Tomcat部署了网站之后就可以运行网页让客户访问，但是Tomcat也只是vue引擎而非web服务器。比如JRUN和Resin都算是vue引擎，而web服务器的职责比较单一，就是处理客户端请求还有返回给客户显示请求处理后的数据而已。vue引擎则可以运行纯HTML编写的网站，也可以运行vue编写的动态网站，在效率上也只是比单纯的web服务器而已，但是从纯web服务器无法运行动态网站上来讲，vue引擎在功能上还是强大了很多，提升一点点效率反而算不了什么，对于必须实现的功能这些要素上，选择了vue技术。
## 2.4 SpringBoot框架
java一直被人诟病的一点就是臃肿、麻烦。当我们还在辛苦的搭建项目时，可能Python程序员已经把功能写好了，究其原因注意是两点：复杂的配置，项目各种配置其实是开发时的损耗， 因为在思考 Spring 特性配置和解决业务问题之间需要进行思维切换，所以写配置挤占了写应用程序逻辑的时间。一个是混乱的依赖管理。项目的依赖管理也是件吃力不讨好的事情。决定项目里要用哪些库就已经够让人头痛的了，你还要知道这些库的哪个版本和其他库不会有冲突，这难题实在太棘手。并且，依赖管理也是一种损耗，添加依赖不是写应用程序代码。一旦选错了依赖的版本，随之而来的不兼容问题毫无疑问会是生产力杀手。而SpringBoot让这一切成为过去！Spring Boot 简化了基于Spring的应用开发，只需要“run”就能创建一个独立的、生产级别的Spring应用。Spring Boot为Spring平台及第三方库提供开箱即用的设置（提供默认设置，存放默认配置的包就是启动器），这样我们就可以简单的开始。多数Spring Boot应用只需要很少的Spring配置。我们可以使用SpringBoot创建java应用，并使用java –jar 启动它，就能得到一个生产级别的web工程。
# 第3章 系统分析
用户的需求以及与本系统相似的在市场上存在的其它系统可以作为系统分析中参考的资料，分析人员可以根据这些信息确定出本系统具备的功能，分析出本系统具备的性能等内容。
## 3.1可行性分析
尽管系统是根据用户的要求进行制作，但是在确定制作前，有必要分析其可行性。
### 3.1.1操作可行性分析
开发本系统需要用到的工具，本人都比较熟悉，因此可以使用这些工具，完整开发制造装备物联及生产管理ERP系统。此外，制造装备物联及生产管理ERP系统在功能上，基本都是完成信息的处理，涵盖了添加，修改，删除等，而且操作者面对的都是各个功能操作界面，并不是编码后台，所以一般的使用者都可以通过操作界面轻松完成信息的加工处理。因此，本系统操作可行。
### 3.1.2经济可行性分析
开发本系统，并没有投入资金购买开发工具。因为使用的开发工具都是事先在百度上下载安装在本人电脑上的，随着软件开发技术的成熟，系统功能实现的编码也都模块化，很容易通过各大软件开发类网站获取，并通过小部分代码改动，运用到本系统中，这些都不需要资金投入，同时，本系统开发的结构选用B/S，成本可以忽略不计。
### 3.1.3技术可行性分析
本系统需要的软件包括Eclipse，Tomcat，Mysql等，这些工具都接触并使用过，至于JAVA，B/S，vue，Html等技术，图书馆都有对应的书籍可以参考学习，加上平时课堂上学习的编程小项目对这些技术都有讲解，另外，本人也从课程设计作业中锻炼了编程能力。所以在技术上，可以完成制造装备物联及生产管理ERP系统的编程开发。

通过上面的分析，已经确定了本系统在经济上的可行，本系统在技术上的可行，本系统在操作上的可行。由此，可以得出在目前的条件下，对于制造装备物联及生产管理ERP系统的设计与实现是可以进行下去的。
## 3.2系统流程分析
本系统在处理数据时，其内部的操作逻辑也需要使用相应的工具进行展示。

在本系统的数据录入页面，对于操作者提供的每条数据都有相应的检验规则，比如数据信息不能有非法字符，或者本来应该是汉字的数据，不能用字母代替，还有对数据内容的长度等进行规范，这样的可以确保数据准确性的检验规则，在编码时，就提前编写好了。数据添加的流程见下图。如果数据已经保存进入数据库，则说明操作者提供的数据内容和格式都是符合要求的。

![](/images/0200wxapp//blog.001.png)

图3.1 添加信息流程图

很多时候，面对系统中的大量数据，难免会发现一些错误，因此需要及时纠正错误，本系统也提供数据后期的修改功能，其流程见下图。但是更新的数据也需要通过数据有效性检验。能够最终写入数据库则说明修改的数据是符合要求的。

![](/images/0200wxapp//blog.002.png)

图3.2 修改信息流程图

面对数据库里面大量数据，在系统的前台，要想快速获取需要的信息，就需要使用查询功能。其流程见下图。该功能需要操作者提前输入关键词，当系统的后台数据库保存了与关键词匹配的数据时，就会及时显示出来，整个过程耗时很短。

![](/images/0200wxapp//blog.003.png)

图3.3 查询信息流程图
## 3.3系统性能分析
分析制造装备物联及生产管理ERP系统对于性能的需求主要还是从下面的5个角度来分析，它们分别是系统的实用性，系统的适应性，系统的易操作性，系统的安全性和系统的易维护性。

性能需求一：系统的实用性，本系统主要是让管理人员集中处理相关信息，可以提供方便快捷的信息添加，信息编辑等操作。在提高信息管理人员的工作效率的同时，也可以降低管理成本，并大大减少管理人员日常繁琐的工作量。

性能需求二：系统的适应性，本系统对于运行环境的要求并不高，可以被广泛运用在生活中。因为使用者只要在日常使用的计算机，或者是随身携带的笔记本上搭建运行环境都能运行本系统，另外系统提供的基础功能包括添加，修改等都能随时操作。

性能需求三：系统的易操作性，本系统提供的功能跟同类型系统一样，也具备简单的增删改操作，操作流程的逻辑也符合广大使用者的使用需求，使用者使用本系统管理数据会非常顺手。

性能需求四：系统的安全性，本系统在数据保存与管理上安全系数要达标，在设计与编码阶段，通过对用户进行权限分配，把系统的功能依照不同用户的角色进行分配，在首次进入系统时，通过编写安全验证的代码模块，引导不同用户进入不同的操作界面。还可以对用户基础信息包括登录的账号密码等进行加密保存，可以利用当下常用的技术成熟的MD5加密技术实现。

性能需求五：系统的易维护性，本系统在后期运行中，会根据使用者的操作，产生许多数据信息，为了便于维护，就要求这些数据可以通过工具从数据库中导出来，对于一些阶段性数据，可以进行批量删除，以此达到轻负荷处理数据的目标，让本系统可以变得更加轻盈。
# 第4章 系统设计
市面上设计比较好的系统都有一个共同特征，就是主题鲜明突出。通过对页面简洁清晰的布局，让页面的内容，包括文字语言，或者视频图片等元素可以清晰表达出系统的主题。让来访用户无需花费过多精力和时间找寻需要的内容。
## 4.1界面设计原则
一般来说，大部分用户使用系统，有些是想从系统中获取需要的信息，有些则是使用系统提供的服务。所以，为了改善用户体验，提高系统的使用率，在对系统界面设计时，需要按照下面的原则进行。

第一点，对用户进行分析，了解用户使用系统的目的，以及使用系统的方式，考虑大部分用户的阅读习惯，设计Z字形或F型结构可以方便用户获取信息。

第二点：设计有效的导航，这个包括每个页面上都有导航条的显示，有时也可以在页面的底部设计导航条，当用户进入具体页面时，要设计相应的位置提示，在页面中比较特殊的位置，需要设计返回链接，可以返回上个页面，也可以返回首页等。

第三点：对整个系统要运用统一的设计方案，包括色彩方案的一致性，页面模板的相似性等，对相同操作和专业术语的描述在整个系统中也应该保持一致。

第四点：设计的界面要保证传达的内容清晰准确。要避免在同一个页面设计非常多的内容，另外可以准确对系统内容进行分类，把页面中用户视觉集中的位置，用来显示重要信息。

作为初学者，并没有那么多的设计经验，但是可以运用上面提到的界面设计原则设计出比较好的系统，可以让用户产生良好的使用体验。
## 4.2功能结构设计
为了让系统的编码可以顺利进行，特意对本系统功能进行细分设计，设计的系统功能结构见下图。

制造装备物联及生产管理ERP系统


员工信息管理

设备类型管理

材料类型管理

材料信息管理


员工信息修改

员工信息新增

材料信息添加 

材料信息删除

材料信息修改

设备信息添加

设备信息修改


设备信息删除

设备类型添加

设备类型删改

设备类型删除

材料类型添加 

材料类型修改 

材料类型删除 

产品信息管理

产品信息修改

产品信息删除


产品信息添加


设备信息管理

![](/images/0200wxapp//blog.004.png)

图4.1 系统功能结构图

4.3 数据库设计

开发一个系统也需要提前设计数据库。这里的数据库是相关数据的集合，存储在一起的这些数据也是按照一定的组织方式进行的。目前，数据库能够服务于多种应用程序，则是源于它存储方式最佳，具备数据冗余率低的优势。虽然数据库为程序提供信息存储服务，但它与程序之间也可以保持较高的独立性。总而言之，数据库经历了很长一段时间的发展，从最初的不为人知，到现在的人尽皆知，其相关技术也越发成熟，同时也拥有着坚实的理论基础。

4.3.1 数据库概念设计

这部分内容需要借助数据库关系图来完成，也需要使用专门绘制数据库关系图的工具，比如Visio工具就可以设计E-R图（数据库关系图）。设计数据库，也需要按照设计的流程进行，首先还是要根据需求完成实体的确定，分析实体具有的特征，还有对实体间的关联关系进行确定。最后才是使用E-R模型的表示方法，绘制本系统的E-R图。不管是使用亿图软件，还是Visio工具，对于E-R模型的表示符号都一样，通常矩形代表实体，实体间存在的关系用菱形符号表示，实体的属性也就是实体的特征用符号椭圆表示。最后使用直线将矩形，菱形和椭圆等符号连接起来。接下来就开始对本系统的E-R图进行绘制。

（1）下图是出入库详情实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\zizhaozhuanbeiwulianjishengcan\出入库详情.jpg](/images/0200wxapp//blog.005.jpeg "C:\Users\Administrator\Desktop\img\zizhaozhuanbeiwulianjishengcan\出入库详情.jpg")
图4.1 出入库详情实体属性图

（2）下图是产品信息实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\zizhaozhuanbeiwulianjishengcan\产品信息.jpg](/images/0200wxapp//blog.006.jpeg "C:\Users\Administrator\Desktop\img\zizhaozhuanbeiwulianjishengcan\产品信息.jpg")
图4.2 产品信息实体属性图

（3）下图是质量监控实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\zizhaozhuanbeiwulianjishengcan\质量监控.jpg](/images/0200wxapp//blog.007.jpeg "C:\Users\Administrator\Desktop\img\zizhaozhuanbeiwulianjishengcan\质量监控.jpg")
图4.3 质量监控实体属性图

（4）下图是字典表实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\zizhaozhuanbeiwulianjishengcan\字典表.jpg](/images/0200wxapp//blog.008.jpeg "C:\Users\Administrator\Desktop\img\zizhaozhuanbeiwulianjishengcan\字典表.jpg")
图4.4 字典表实体属性图

（5）下图是员工实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\zizhaozhuanbeiwulianjishengcan\员工.jpg](/images/0200wxapp//blog.009.jpeg "C:\Users\Administrator\Desktop\img\zizhaozhuanbeiwulianjishengcan\员工.jpg")
图4.5 员工实体属性图

（6）下图是材料信息实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\zizhaozhuanbeiwulianjishengcan\材料信息.jpg](/images/0200wxapp//blog.010.jpeg "C:\Users\Administrator\Desktop\img\zizhaozhuanbeiwulianjishengcan\材料信息.jpg")
图4.6 材料信息实体属性图

（7）下图是设备信息实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\zizhaozhuanbeiwulianjishengcan\设备信息.jpg](/images/0200wxapp//blog.011.jpeg "C:\Users\Administrator\Desktop\img\zizhaozhuanbeiwulianjishengcan\设备信息.jpg")
图4.7 设备信息实体属性图

（8）下图是生产计划实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\zizhaozhuanbeiwulianjishengcan\生产计划.jpg](/images/0200wxapp//blog.012.jpeg "C:\Users\Administrator\Desktop\img\zizhaozhuanbeiwulianjishengcan\生产计划.jpg")
图4.8 生产计划实体属性图

（9）下图是顾客订单实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\zizhaozhuanbeiwulianjishengcan\顾客订单.jpg](/images/0200wxapp//blog.013.jpeg "C:\Users\Administrator\Desktop\img\zizhaozhuanbeiwulianjishengcan\顾客订单.jpg")
图4.9 顾客订单实体属性图

（10）下图是出入库实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\zizhaozhuanbeiwulianjishengcan\出入库.jpg](/images/0200wxapp//blog.014.jpeg "C:\Users\Administrator\Desktop\img\zizhaozhuanbeiwulianjishengcan\出入库.jpg")
图4.10 出入库实体属性图

（11）下图是设备检修实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\zizhaozhuanbeiwulianjishengcan\设备检修.jpg](/images/0200wxapp//blog.015.jpeg "C:\Users\Administrator\Desktop\img\zizhaozhuanbeiwulianjishengcan\设备检修.jpg")
图4.11 设备检修实体属性图

（12）下图是维修员实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\zizhaozhuanbeiwulianjishengcan\维修员.jpg](/images/0200wxapp//blog.016.jpeg "C:\Users\Administrator\Desktop\img\zizhaozhuanbeiwulianjishengcan\维修员.jpg")
图4.12 维修员实体属性图

（13）下图是用户表实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\zizhaozhuanbeiwulianjishengcan\用户表.jpg](/images/0200wxapp//blog.017.jpeg "C:\Users\Administrator\Desktop\img\zizhaozhuanbeiwulianjishengcan\用户表.jpg")
图4.13 用户表实体属性图
### 4.3.2 数据库物理设计
作为程序后台的支持，本数据库也需要设计数据存储的结构。而数据存储结构的设计就包括了数据表结构的设计和创建。数据表结构包括了字段，数据类型，还有字段的取值范围等信息。而E-R模型中的实体就是一张表，实体的特征就可以作为该表中的字段，根据本程序信息存储要求，设计每个字段需要的类型，还有该字段的取值范围等。每当设计完成一张数据表，就需要及时保存在数据库里面，并对该设计的数据表准确命名，要求设置的数据表的名称尽量不要是中文，而且要方便记忆。因为在程序编码阶段，通过SQL语句可以把程序里面的数据写入在各个数据表里面，而这个环节需要使用到数据表的名称。如果数据表名称是中文的话，可能会乱码并影响程序运行。下面就以表格形式展示设计的结果。

表4.1材料信息表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|cailiao\_uuid\_unmber|String|材料编号|是|
|3|cailiao\_name|String|材料名称|是|
|4|cailiao\_types|Integer|材料类型|是|
|5|cailiao\_kucun\_number|Integer|材料数量|是|
|6|cailiao\_danwei|String|单位|是|
|7|create\_time|Date|创建时间|是|
表4.2出入库表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|cailiao\_churu\_inout\_uuid\_number|String|出入库流水号|是|
|3|cailiao\_churu\_inout\_name|String|出入库名称|是|
|4|cailiao\_churu\_inout\_types|Integer|出入库类型|是|
|5|cailiao\_churu\_inout\_content|String|备注|是|
|6|insert\_time|Date|添加时间|是|
|7|create\_time|Date|创建时间|是|
表4.3出入库详情表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|cailiao\_churu\_inout\_id|Integer|出入库|是|
|3|cailiao\_id|Integer|材料|是|
|4|cailiao\_churu\_inout\_list\_number|Integer|操作数量|是|
|5|insert\_time|Date|操作时间|是|
|6|create\_time|Date|创建时间|是|
表4.4产品信息表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|chanpin\_uuid\_unmber|String|产品编号|是|
|3|chanpin\_name|String|产品名称|是|
|4|chanpin\_types|Integer|产品类型|是|
|5|shangxia\_types|Integer|是否上架|是|
|6|chanpin\_content|String|产品详情|是|
|7|create\_time|Date|创建时间|是|
表4.5字典表表

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
表4.6顾客订单表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|gukedingdan\_uuid\_unmber|String|订单编号|是|
|3|chanpin\_id|Integer|产品|是|
|4|gukedingdan\_number|Integer|订购数量|是|
|5|insert\_time|Date|下订单日期|是|
|6|gukedingdan\_time|Date|订单截止时间|是|
|7|gukedingdan\_types|Integer|订单状态|是|
|8|gukedingdan\_text|String|顾客订单内容|是|
|9|create\_time|Date|创建时间|是|
表4.7设备信息表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|shebei\_uuid\_unmber|String|设备编号|是|
|3|shebei\_name|String|设备名称|是|
|4|shebei\_types|Integer|设备类型|是|
|5|shebei\_time|Date|上次检修日期|是|
|6|status\_types|Integer|设备状态|是|
|7|create\_time|Date|创建时间|是|
表4.8设备检修表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|shebei\_id|Integer|设备|是|
|3|weixiuyuan\_id|Integer|员工|是|
|4|shebeijianxiu\_time|Date|上次检修日期|是|
|5|create\_time|Date|创建时间|是|
表4.9生产计划表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|gukedingdan\_id|Integer|订单编号|是|
|3|shengcanjihukaishi\_time|Date|开始的时间|是|
|4|shengcanjihujieshu\_time|Date|结束时间|是|
|5|shengcanjihua\_types|Integer|计划状态|是|
|6|create\_time|Date|创建时间|是|
表4.10维修员表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|weixiuyuan\_name|String|维修员姓名|是|
|3|weixiuyuan\_photo|String|头像|是|
|4|weixiuyuan\_phone|String|维修员手机号|是|
|5|weixiuyuan\_id\_number|String|维修员身份证号|是|
|6|weixiuyuan\_email|String|邮箱|是|
|7|weixiuyuan\_delete|Integer|假删|是|
|8|weixiuyuan\_time|Date|入职日期|是|
|9|create\_time|Date|创建时间|是|
表4.11员工表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_name|String|员工姓名|是|
|3|yonghu\_photo|String|头像|是|
|4|yonghu\_phone|String|员工手机号|是|
|5|yonghu\_id\_number|String|员工身份证号|是|
|6|yonghu\_email|String|邮箱|是|
|7|yonghu\_zhineng|String|职能|是|
|8|bumen\_types|Integer|部门|是|
|9|yonghu\_delete|Integer|假删|是|
|10|yonghu\_time|Date|入职日期|是|
|11|create\_time|Date|创建时间|是|
表4.12质量监控表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|shengcanjihua\_id|Integer|生产计划|是|
|3|zhiljiankong\_name|String|不合格产品名称|是|
|4|shebei\_types|Integer|设备类型|是|
|5|yonghu\_id|Integer|员工|是|
|6|zhiljiankong\_number|Integer|不合格产品数量|是|
|7|insert\_time|Date|时间|是|
|8|create\_time|Date|创建时间|是|
表4.13用户表表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|username|String|用户名|是|
|3|password|String|密码|是|
|4|role|String|角色|是|
|5|addtime|Date|新增时间|是|


# 第5章 系统实现
这个环节需要使用前面的设计方案，包括对系统模块的设计，还有对程序后台的数据支持的数据库的设计等。不过这部分内容还是强调系统编码人员的开发能力，要把前面设计的内容通过编码的形式以一个完整的，可以运行的系统呈现出来。

功能模块的实现
### 5.1员工信息管理
如图5.1显示的就是员工信息管理页面，此页面提供给管理员的功能有：员工信息的查询管理，可以删除员工信息、修改员工信息、新增员工信息，

还进行了对用户名称的模糊查询的条件

![](/images/0200wxapp//blog.018.png)

图5.1 员工信息管理页面
### 5.2 材料信息管理
如图5.2显示的就是材料信息管理页面，此页面提供给管理员的功能有：查看已发布的材料信息数据，修改材料信息，材料信息作废，即可删除，还进行了对材料信息名称的模糊查询 材料信息信息的类型查询等等一些条件。

![](/images/0200wxapp//blog.019.png)

图5.2 材料信息管理页面
### 5.3设备信息管理
如图5.3显示的就是设备信息管理页面，此页面提供给管理员的功能有：根据设备信息进行条件查询，还可以对设备信息进行新增、修改、查询操作等等。

![](/images/0200wxapp//blog.020.png)


图5.3 设备信息管理页面
### 5.1设备类型管理
如图5.4显示的就是设备类型管理页面，此页面提供给管理员的功能有：根据设备类型进行新增、修改、查询操作等等。

![](/images/0200wxapp//blog.021.png)

图5.4 设备类型管理页面




# 










