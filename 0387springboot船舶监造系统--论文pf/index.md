# 0387springboot船舶监造系统--论文pf


# [0387springboot船舶监造系统--论文pf](https://github.com/GraduationProject-springboot/0387springboot)

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

# [项目清单](https://chenqi1990.site) 包安装运行

### [github 项目仓库](https://github.com/GraduationProject-springboot/allSpringbootProjects) 开源仅有后端代码

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1T1bpekEK7?p=59)


# 绪论
## 1.1研究背景与意义
信息化管理模式是将行业中的工作流程由人工服务，逐渐转换为使用计算机技术的信息化管理服务。这种管理模式发展迅速，使用起来非常简单容易，用户甚至不用掌握相关的专业知识，根据教程指导即可正常使用相关的系统，因而被越来越多的用户所使用。由于相关行业管理信息化，这就使得管理工作不在受到时间和区域的限制，随时随地即可完成相关的工作任务和结果[1]。就目前而言，管理信息化在现代社会中非常流行，使用比较广泛。早在20世纪70年代末，就出现了早期的电子商务，相关的公司企业使用计算机建立专用的内部网络，通过内部网络完成相应的采购、销售等活动，加快相关的企业之间的交易速度，提高了工作效率[2]。

当下，许多行业采用互联网技术将工作流程信息化、数字化，提高了相关人员的服务质量和效率，节约了相关行业的人力、财力、物力等资源，与此同时，人们获取外界的相关信息主要依赖于主流的信息化技术和工具。人们对生活的需求也在不断的发生着变化，为了应对用户的多样化需求，许多相关的第三产业应运而生，管理信息化也逐渐的流行起来，比如电子商务行业。本人通过查询大量学习资料，了解基本的开发系统的基本背景和关键任务，学习与掌握Java语言、web技术、AJAX技术、HTML语言等开发技术，设计系统功能模块，以及MySQL数据库的相关语法和工具，创建和存储数据表格，反映和关联表格之间相互存在的关系，由此对船舶监造系统进行研发和实现。
## 1.2国内外研究现状
大概在20世纪90年代，我国才开始研发船舶监造系统，与一些发达国家相比，系统研发起步比较晚。当时的计算机技术刚开始发展起来，国家经济力量比较薄弱，各地区的经济发展水平不平衡，再加上相关的网络应用技术不太先进，我国也使用了一段较长的时间对网络信息化管理进行探索[3]。近些年，因为国家非常重视和支持第三产业的发展，以及人们的日常生活需求越来越离不开信息管理技术的使用，所以我国的信息管理系统行业发展速度非常快，并且相关的体制法规也正在不断地被完善和改进。新时代背景下，根据人们的相关需求，不断地促进着相关产业的产生与发展，一系列电子产品、应用软件、信息管理系统等新时代的产物逐渐出现在人们的视野中，并且在近几年发展迅速，日渐趋于成熟[4]。

与国内相比，国外船舶监造系统领域发展较早。国外的计算机技术发展比较成熟，所以系统相关的设计也比较完善。19世纪60年代左右，国外就开始研发船舶监造系统，并且不久之后，迅速将其投入市场进行使用。美国、英国等一些发达国家快速发展计算机技术，促进了船舶监造系统管理行业信息化建设[5]。而后随着相关的技术不断地发展，覆盖面非常广泛，应用领域比较多，促进着船舶监造系统等相关的信息管理系统不断地发展和完善，并且其所设计的系统功能结构也比较合理、全面。相对而言，国外系统的研发在相关领域上还是占据着较大的优势[6]。因此，我们需要吸收国外系统开发领域中的较好的技术精华，发展我国的信息化管理系统，使得其面向大众，能够更好的、更全面的服务于相关的工作人员。
## 1.3研究内容
现今，互联网在我们的日常生活占据着日益重要的地位，我们也越来越离不开对移动设备、电脑等上网设备的使用。传统的船舶监造系统模式主要依靠管理人员纯手工记录的相关信息，比较繁琐，不方便查找，也非常容易出现错误。如今，如果再通过手工记录监造项目，将大大不利于船舶监造系统行业管理相关的船舶监造系统信息，严重影响船舶监造系统行业的发展。因此，本人结合传统的船舶监造系统业务模式和先进的电子信息管理模式，使用Java语言编程设计功能模块，AJAX实现前台和后台之间的交互，MySQL数据库创建和存储数据表格，对船舶监造系统进行设计和开发。本系统的设计有利于相关行业实现最大化的资源管理与共享，促进相关行业的信息交流、分工合作，提高相关工作人员的工作效率，最终实现整个船舶监造系统行业服务的信息化管理。
## 1.4论文结构
本文围绕着船舶监造系统的整个开发过程，展开了详细的描述和说明，设计和实现本系统的主要工作有：首先分析研究背景、研究状态，其次介绍设计系统时使用到的相关技术，然后通过系统分析确定系统的功能需求，接着通过编码工作详细设计和实现系统，最后再通过系统测试，找出系统存在的问题和解决问题的方法，不断地修改和完善系统。论文内容的组织结构设计如下。

第一章绪论，通过介绍本系统的研究背景、研究现状等内容，帮助用户了解和认识本系统的发展过程。

第二章相关技术介绍，主要介绍了Java语言、VUE框架、MySQL数据库等相关的开发技术，为后期系统的功能实现提供技术上的支持。

第三章系统分析，分析用户的使用需求，以及系统实现的可行性，最后通过用例建模分析与系统相关的参与者及其用例之间的关系。

第四章系统设计，主要根据系统总体功能设计，确定将要设计的系统功能模块，设计相关的数据表格。

第五章系统实现，通过相关的功能模块运行图，展现出系统的主要功能模块操作流程。

第六章系统测试，主要使用功能测试的方式，测试系统的相关功能运行和使用的具体情况。

第七章总结与展望，通过本文的各章节描述总结得出，基本上完成了系统的设计，展望未来将学习和使用更加先进的技术，提高系统的实用性，使得系统更好的服务于使用人员。
## 1.5本章小结
本章主要介绍了课题的研究背景与意义，研究现状，研究内容等内容，最后介绍了本论文的组织结构设计。信息化管理模式顺应了信息化时代的变化，本人以现在主流的管理模式为前提，根据使用者的相关需求，设计出一款符合大众需求的船舶监造系统。

#
# 2理论基础
## 2.1 VUE框架
Vue (读音 /vjuː/，类似于 view) 是一套用于构建用户界面的渐进式框架。与其它大型框架不同的是，Vue 被设计为可以自底向上逐层应用。Vue 的核心库只关注视图层，不仅易于上手，还便于与第三方库或既有项目整合。另一方面，当与[现代化的工具链](https://v2.cn.vuejs.org/v2/guide/single-file-components.html)以及各种[支持类库](https://github.com/vuejs/awesome-vue#libraries--plugins)结合使用时，Vue 也完全能够为复杂的单页应用提供驱动。
## 2.2 IDEA开发环境
软件开发使用的编程语言有许多种，而每种编程语言需要通过与其相对应的开发平台进行编译和运行。IDEA平台都是目前比较常用的开发环境。IDEA平台是开源的，具有功能强大、可扩展性强等特点，可以应用于C/S模式软件的开发，但是它所占据的内存容量比较大，运行较慢，并且其并未提供Tomcat服务器，运行过程中需要将代码发布到Tomcat服务器中，测试使用的时间较长，故而不太适用于VUE软件的开发。

IDEA平台是建立在IDEA平台的基础之上，增加了许多的应用插件，比如Tomcat插件、mail组件等。IDEA平台增加了Tomcat插件，代码编写完成或者更新完成时，程序员无需将代码发布到Tomcat服务器中，可以直接通过调试实现程序的运行。IDEA平台增加了Mail组件，该组件可以为本程序提供标准的邮件方法，便于开发人员完成与邮件功能相关的编译工作。IDEA平台占据的内存空间较小，同时其也具有较高的可扩展性，编程人员可以根据需要添加和使用相关的插件。可以支持主流的开源产品和相关的开发框架，被广泛运用到相关的移动系统、web应用系统等开发中。相比于IDEA平台，本系统比较适合使用IDEA平台进行编程和开发。
## 2.3 MySQL数据库
MySQL是一种小型的关系型数据库管理系统，因为其运行速度快，占用内存空间小，并且源代码也是开源的，运行和维护成本低，系统性能稳定，受到了许多开发人员的喜爱[9]。考虑到MySQL数据库开发成本低，功能齐全等因素，大多中小型网站选择使用MySQL数据库管理数据信息。

SQL Server也是近几年使用较多的关系型数据库，其与MySQL数据库存在的不同之处主要有，在环境方面，SQL Server数据库比较适合于.NET环境，而MySQL数据库适用于几乎所有的语言；在成本方面，SQL Server数据库是商业化的，其运行多个数据库可许证，虽然有一个免费版，但是只能让你对关系型数据库管理系统有一定的认识与了解，熟悉相关的使用流程。如果要想使用SQL Server数据库的话，就需要支付相关费用，而MySQL数据库是开源的，其对于用户来说，使用是完全免费；在实际应用方面，SQL Server数据库和MySQL数据库均支持Java语言、PHP语言、C++语言等多种编程语言，但是MySQL数据库除了支持上述SQL Server数据库能支持的编程语言外，还支持Scheme、Eiffel等其他编程语言，故而MySQL数据库受欢迎程度比SQL Server数据库更高。
## 2.4 Java语言
Java语言是一种面向对象的编程语言，其主要具有继承、封装、多态等特征，从而提高编程工作效率，实现软件的设计和开发[10]。继承机制可以继承相关的类和方法，新的类可以在继承已经定义的类的相关特性基础上，扩展自己新的数据和功能，进而提高自身的能力。封装机制可以提高程序的安全性，其隐藏对象的相关属性和行为，对外只提供一个接口，用户直接通过访问相应的接口来实现自己需要的功能操作。多态机制可以描述对象的多样性，简单的来说就是引用相同的对象做不同的事务。Java语言具有安全高效的优点，并且其通过依靠Java虚拟机，可以实现跨平台操作[11]。Java语言比较容易学习和掌握，就目前软件开发所使用的开发类语言而言，Java语言比较受程序员喜爱，应用比较广泛。

## 2.5本章小结
本章主要介绍了实现船舶监造系统的相关理论基础以及开发工具。本系统采用VUE，使用Java语言、AJAX技术、MySQL数据库等工具，设计系统功能、页面布局、后台数据等。开发本系统所使用的相关技术操作简单、容易掌握，Java语言具有跨平台性，可以支持在不同的浏览器使用本系统，MySQL数据库是开源的，减少了本系统的开发成本。
# 3需求分析
## 3.1功能需求分析
需求分析过程是系统能否成功投入市场，也能否被用户所接受和使用的非常关键的一个步骤。功能需求分析是通过设计系统功能来实现相关的业务事项，详细分析用户的实际需要，确定需要设计的相关业务事项，其是系统实现的关键，本系统存在的主要功能需求包括用户注册管理、用户信息管理、密码信息管理等。
## 3.2技术需求分析
本系统需要使用Java语言编码设计相关的功能模块，MySQL数据库创建和存储数据表格，AJAX实现前台和后台之间的交互，并且需要在IDEA开发环境中，编写相关的Java代码等系统程序文件，使用MySQL数据库存储数据信息，然后通过使用连接代码完成与MySQL数据库的搭建工作，再通过使用开发环境中的Tomcat插件，完成与Tomcat服务器的发布工作，最后通过与Tomcat服务器的交互行为可以实现代码调试工作。满足以上相关的技术需求，本系统才可以在浏览器上进行访问和使用。
## 3.3数据需求分析
在设计系统功能模块时，需要收集与系统有关的数据信息，并且对采集的数据信息进行组织和存储，分析系统功能设计，筛选有价值的数据，而后形成数据字典。其中，从庞大的数据信息中筛选出有价值的数据是比较耗时，也是非常重要的一步，主要依据信息的来源、信息的有效性、信息的扩充性、信息的真实性等内容筛选数据。数据需求分析阶段，为系统的开发工作做好进一步准备，便于更好的设计和完成系统。
## 3.4安全需求分析
安全需求分析是在系统使用过程中对性能的具体要求，对功能需求的一个补充内容，也是对功能需求的一个补充内容，主要包括响应需求、安全性需求、稳定性需求、可扩展性需求等内容。安全需求是在系统功能需求以外的其他必要的需求内容，其不论在系统设计过程，还是在系统投入市场过程，都起到了极其重要的作用。
## 3.5可行性分析
### 3.5.1经济可行性
经济可行性是决定是否研发系统的关键性因素。我们主要通过比较实际的收益和成本的方法，来确定一个系统是否具有经济可行性。在使用系统的过程中，当获得的收益大于开发的成本时，说明此系统的研发在经济上是可行的。由于本系统的开发使用的技术基本上是开源的，获得技术上的支持是没有多少问题的，在软件实现方面所花费的成本是很低的，甚至不需要花费成本。研发系统的成本主要是来自调研、硬件和技术人员等方面。如果系统中需要存储的数据量不是很大，仅需要配置一台普通的服务器，即可满足相关需求。如果需要存储的数据量很大，则需要配置一台具有独立功能的服务器，比如管理数据库需要单独的数据库服务器，负责接入网站需要web服务器等等，但是一台服务器的价格是比较贵的。考虑到数据量和成本，我们使用小型集群服务器，这样既可以充分利用相关的资源，又可以让系统正常访问服务器。
### 3.5.2技术可行性
Java语言具有跨平台性，本系统主要通过Java语言进行编码实现的，所以本系统可以支持在多个操作系统或者多个浏览器上运行和使用[14]。MySQL数据库是可以被免费使用的，并且MySQL数据库的日常运行和维护工作比较简单，这样有利于降低本系统的开发成本[15]。在学校期间，本人已经学习和掌握了Java语言、MySQL数据库、AJAX技术等相关的技术相关知识以及用法，因此在技术可行性方面，本系统是可以实现被设计与实现的。
### 3.5.3操作可行性
本系统所采用网络结构是VUE，对于开发人员来说，可以直接复用相关的代码，或者稍微对原代码进行修改，使得其满足于本系统的相关需求，如此便可大大节约了开发时间，在最优最短的时间内完成对系统的设计。对于用户来说，在传统的模式下，需要下载客户端才可使用系统。现在，在新型的模式下，使用本系统，就不需要下载，直接选择浏览器打开网址，即可访问和使用本系统。并且，用户可以根据自身的工作需要，选择相关的菜单按钮操作本系统。在系统的一些功能模块中，本人还添加了相关的使用提示信息，方便用户更好更快的了解和使用本系统。因此，本系统的设计和实现是具备操作可行性的。
## 3.6本章小结
需求分析在软件开发周期中是耗时最长的一个环节，系统的整个设计和实现过程主要依赖于需求分析报告。调查收集出不同用户对本系统的相关使用需求，由此设计相关的功能模块，从而期望实现用户满意度较高的实用型系统。本章主要从功能需求、技术需求、数据需求、安全需求、可行性分析等方面，对系统进行需求分析，确保设计出一款实用价值比较高的管理系统。

#
# 4系统设计
## 4.1系统功能设计
本系统主要通过使用Java语言编码设计系统功能，MySQL数据库管理数据，AJAX技术设计简洁的、友好的网址页面，然后在IDEA开发平台中，编写相关的Java代码文件，接着通过连接语言完成与数据库的搭建工作，再通过平台提供的Tomcat插件完成信息的交互，最后在浏览器中打开系统网址便可使用本系统。本系统的使用角色可以被分为用户和管理员，用户具有注册、查看信息、留言信息等功能，管理员具有修改用户信息，发布项目图纸等功能，系统总体功能设计图如图4-1所示。

![结构设计图](/images/0300stringboot/0387springboot/blog.002.jpeg)

图4-1系统总体功能设计图

## 4.2数据库设计
### 4.2.1概念设计
在数据库设计过程中，概念设计阶段是逻辑设计阶段得以实现的基础，也是根据用户参与情况确定对数据的处理要求，从而使得数据库设计成功的关键。概念设计的主要任务是将现实世界的所收集到的使用需求转化为抽象的信息世界结构的过程，能够真实的反映现实生活中实体与实体之间的联系，数据库的相关语法和代码比较容易理解和修改，方便相关人员将相关的数据信息存储到数据库中，并对其进行修改和使用[18]。

通过将现实世界中的实体、属性、联系等内容进行概念设计，建立比较抽象的概念数据模型，即E-R图。通过E-R图可将现实世界抽象到的概念设计转变成数据库的实体设计，并且能够明显的看见各个实体之间，数据的流动情况，具体较强的表达能力，更加方便于开发人员寻找与发现用户具体的需求[19]。因此，E-R的建立，在整个数据库的设计过程中，起着至关重要的作用。本系统主要的实体有管理员、用户、留言等。在E-R图中，矩形表示实体集，椭圆形表示属性，菱形表示联系。其中，联系的类型包括1:1（一对一）、1:n（一对多）、n:m（多对多）关系。

（1）下图是用户实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.1\\_\_\_\_img\用户.jpg](/images/0300stringboot/0387springboot/blog.003.jpeg)

用户实体属性图

（2）下图是项目实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.1\\_\_\_\_img\项目.jpg](/images/0300stringboot/0387springboot/blog.003.jpeg)

项目实体属性图

（3）下图是员工实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.1\\_\_\_\_img\员工.jpg](/images/0300stringboot/0387springboot/blog.003.jpeg)

员工实体属性图

（4）下图是监造进度实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.1\\_\_\_\_img\监造进度.jpg](/images/0300stringboot/0387springboot/blog.003.jpeg)

监造进度实体属性图

（5）下图是材料参考实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.1\\_\_\_\_img\材料参考.jpg](/images/0300stringboot/0387springboot/blog.003.jpeg)

材料参考实体属性图

（6）下图是公告实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.1\\_\_\_\_img\公告.jpg](/images/0300stringboot/0387springboot/blog.004.jpeg)

公告实体属性图

（7）下图是材料验收实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.1\\_\_\_\_img\材料验收.jpg](/images/0300stringboot/0387springboot/blog.003.jpeg)

材料验收实体属性图

（8）下图是工艺验收实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.1\\_\_\_\_img\工艺验收.jpg](/images/0300stringboot/0387springboot/blog.003.jpeg)

工艺验收实体属性图

（9）下图是项目图纸实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.1\\_\_\_\_img\项目图纸.jpg](/images/0300stringboot/0387springboot/blog.003.jpeg)

项目图纸实体属性图

（10）下图是成果验收实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.1\\_\_\_\_img\成果验收.jpg](/images/0300stringboot/0387springboot/blog.003.jpeg)

成果验收实体属性图

（11）下图是监造财务实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.1\\_\_\_\_img\监造财务.jpg](/images/0300stringboot/0387springboot/blog.003.jpeg)

监造财务实体属性图

（12）下图是经费预估实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.1\\_\_\_\_img\经费预估.jpg](/images/0300stringboot/0387springboot/blog.003.jpeg)

经费预估实体属性图


### 4.2.2逻辑设计
本系统使用MySQL数据库管理与系统相关的数据信息。逻辑设计阶段是将上一个阶段中的概念数据模型，转换为方便数据库进行存储的关系模型，即基本表的形式，方便开发人员后期对数据模型进行优化和管理[20]。逻辑设计阶段是整个数据库设计设计的关键，与系统有关的信息将会在这一阶段中被存储在数据库中，当用户使用本系统进行相关的功能操作时，与之有关的数据信息所在的基本表会发生相应的更新变化。数据库的逻辑设计阶段主要任务是将与系统相关的数据信息，设计成为方便数据库存储和管理的基本表格的形式，具体内容如下。

表4.1材料参考表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|cailiaocankao\_uuid\_number|String|材料编号|是|
|3|cailiaocankao\_name|String|材料名称|是|
|4|cailiao\_types|Integer|材料类型|是|
|5|cailiaocankao\_danwei|String|单价单位|是|
|6|cailiaocankao\_danjia|BigDecimal|参考单价|是|
|7|cailiaocankao\_guige|String|材料规格|是|
|8|cailiaocankao\_file|String|执行标准|是|
|9|cailiaocankao\_gongsi|String|推荐公司|是|
|10|cailiaocankao\_content|String|备注|是|
|11|insert\_time|Date|上传时间|是|
|12|create\_time|Date|创建时间|是|
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
|3|gonggao\_types|Integer|公告类型|是|
|4|insert\_time|Date|发布时间|是|
|5|gonggao\_content|String|公告详情|是|
|6|create\_time|Date|创建时间|是|
表4.4监造财务表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|xiangmu\_id|Integer|项目|是|
|3|yuangong\_id|Integer|员工|是|
|4|jianzaocaiwu\_uuid\_number|String|监造财务编号|是|
|5|jianzaocaiwu\_name|String|花费标题|是|
|6|jianzaocaiwu\_types|Integer|消费类型|是|
|7|jianzaojindu\_file|String|附件|是|
|8|jianzaocaiwu\_mingcheng|String|名称|是|
|9|jianzaocaiwu\_danjia|BigDecimal|单价|是|
|10|jianzaocaiwu\_number|Integer|数量|是|
|11|jianzaocaiwu\_zongjine|BigDecimal|应金额|是|
|12|jianzaocaiwu\_shiji\_zongjine|BigDecimal|实际金额|是|
|13|hege\_types|Integer|是否合格|是|
|14|jianzaocaiwu\_content|String|备注|是|
|15|insert\_time|Date|验收时间|是|
|16|create\_time|Date|创建时间|是|
表4.5监造进度表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|xiangmu\_id|Integer|项目|是|
|3|yuangong\_id|Integer|员工|是|
|4|jianzaojindu\_uuid\_number|String|监造进度编号|是|
|5|jianzaojindu\_name|String|进度标题|是|
|6|jianzaojindu\_types|Integer|进度类型|是|
|7|jianzaojindu\_zhengchang\_number|Integer|正常进度(%)|是|
|8|jianzaojindu\_xianzai\_number|Integer|现在进度(%)|是|
|9|jianzaojindu\_file|String|附件|是|
|10|jianzaojindu\_time|Date|记录时间|是|
|11|jianzaojindu\_content|String|备注|是|
|12|insert\_time|Date|上传时间|是|
|13|create\_time|Date|创建时间|是|
表4.6经费预估表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|xiangmu\_id|Integer|项目|是|
|3|yuangong\_id|Integer|员工|是|
|4|jingfeiyugu\_uuid\_number|String|经费预估编号|是|
|5|jingfeiyugu\_name|String|材料名称|是|
|6|jingfeiyugu\_danwei|String|单价单位|是|
|7|jingfeiyugu\_danjia|BigDecimal|材料单价|是|
|8|cailiao\_types|Integer|材料类型|是|
|9|jingfeiyugu\_number|Integer|所需数量|是|
|10|jingfeiyugu\_zongjia|BigDecimal|预计总价|是|
|11|jingfeiyugu\_gongsi|String|推荐公司|是|
|12|jingfeiyugu\_file|String|执行标准|是|
|13|jingfeiyugu\_content|String|备注|是|
|14|insert\_time|Date|上传时间|是|
|15|create\_time|Date|创建时间|是|
表4.7项目表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_id|Integer|用户|是|
|3|xiangmu\_uuid\_number|String|项目编号|是|
|4|xiangmu\_name|String|项目名称|是|
|5|xiangmu\_address|String|监造地点|是|
|6|xiangmu\_file|String|建造资料|是|
|7|xiangmu\_types|Integer|项目类型|是|
|8|xiangmu\_kucun\_number|Integer|监造数量|是|
|9|shenqing\_time|Date|申请时间|是|
|10|nachuan\_time|Date|拿船时间|是|
|11|xiangmu\_content|String|监造要求|是|
|12|insert\_time|Date|录入时间|是|
|13|create\_time|Date|创建时间|是|
表4.8项目图纸表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|xiangmu\_id|Integer|项目|是|
|3|yuangong\_id|Integer|员工|是|
|4|xiangmu\_tuzhi\_uuid\_number|String|图纸编号|是|
|5|xiangmu\_tuzhi\_name|String|图纸名称|是|
|6|xiangmu\_tuzhi\_file|String|图纸文件|是|
|7|xiangmu\_tuzhi\_types|Integer|图纸类型|是|
|8|xiangmu\_tuzhi\_content|String|图纸介绍|是|
|9|insert\_time|Date|上传时间|是|
|10|xiangmu\_tuzhi\_yesno\_types|Integer|申请状态|是|
|11|xiangmu\_tuzhi\_yesno\_text|String|审核回复|是|
|12|xiangmu\_tuzhi\_shenhe\_time|Date|审核时间|是|
|13|create\_time|Date|创建时间|是|
表4.9材料验收表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|xiangmu\_id|Integer|项目|是|
|3|yuangong\_id|Integer|员工|是|
|4|yanshou\_cailiao\_name|String|材料名称|是|
|5|yanshou\_cailiao\_buwei|String|监造部位|是|
|6|yanshou\_cailiao\_biaozhun|String|使用标准|是|
|7|yanshou\_cailiao\_shijishiyong|String|实际使用|是|
|8|jianzaojindu\_file|String|附件|是|
|9|hege\_types|Integer|是否合格|是|
|10|yanshou\_time|Date|验收时间|是|
|11|yanshou\_cailiao\_content|String|备注|是|
|12|insert\_time|Date|录入时间|是|
|13|create\_time|Date|创建时间|是|
表4.10成果验收表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|xiangmu\_id|Integer|项目|是|
|3|yuangong\_id|Integer|员工|是|
|4|yanshou\_chengguo\_buwei|String|验收部位|是|
|5|yanshou\_chengguo\_chuandong|String|船东要求|是|
|6|yanshou\_chengguo\_shiji|String|实际结果|是|
|7|jianzaojindu\_file|String|附件|是|
|8|hege\_types|Integer|是否合格|是|
|9|yanshou\_time|Date|验收时间|是|
|10|yanshou\_chengguo\_content|String|缘由|是|
|11|yanshou\_chengguo\_beizhu\_content|String|备注|是|
|12|insert\_time|Date|录入时间|是|
|13|create\_time|Date|创建时间|是|
表4.11工艺验收表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|xiangmu\_id|Integer|项目|是|
|3|yuangong\_id|Integer|员工|是|
|4|yanshou\_gongyi\_name|String|工艺名称|是|
|5|yanshou\_gongyi\_buwei|String|验收部位|是|
|6|yanshou\_gongyi\_biaozhun|String|使用标准|是|
|7|yanshou\_gongyi\_shijishiyong|String|实际使用|是|
|8|jianzaojindu\_file|String|附件|是|
|9|hege\_types|Integer|是否合格|是|
|10|yanshou\_time|Date|验收时间|是|
|11|yanshou\_gongyi\_content|String|备注|是|
|12|insert\_time|Date|录入时间|是|
|13|create\_time|Date|创建时间|是|
表4.12用户表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_uuid\_number|String|用户编号|是|
|3|yonghu\_name|String|用户姓名|是|
|4|yonghu\_phone|String|用户手机号|是|
|5|yonghu\_id\_number|String|用户身份证号|是|
|6|yonghu\_photo|String|用户头像|是|
|7|yonghu\_email|String|用户邮箱|是|
|8|jinyong\_types|Integer|账户状态|是|
|9|create\_time|Date|创建时间|是|
表4.13员工表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yuangong\_uuid\_number|String|员工编号|是|
|3|yuangong\_name|String|员工姓名|是|
|4|yuangong\_phone|String|员工手机号|是|
|5|yuangong\_id\_number|String|员工身份证号|是|
|6|yuangong\_photo|String|员工头像|是|
|7|bumen\_types|Integer|部门|是|
|8|zhiwei\_types|Integer|职位|是|
|9|yuangong\_email|String|员工邮箱|是|
|10|jinyong\_types|Integer|账户状态|是|
|11|create\_time|Date|创建时间|是|
表4.14管理员表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|username|String|员工名|是|
|3|password|String|密码|是|
|4|role|String|角色|是|
|5|addtime|Date|新增时间|是|

##
##
## 4.3本章小结
本章主要介绍了系统功能设计、数据库设计等内容。通过设计系统的总体功能框架，确定系统的功能设计主要包括监造项目等模块。数据库设计主要分为概念设计阶段和逻辑设计阶段，其中，概念设计是将现实世界中的数据转变为信息世界中的概念模型，逻辑设计是将概念设计中的概念模型转变成可以被数据库存储的数据表格。系统功能设计好坏是系统得以被编码实现的重要依据。数据库设计是否符合规范，是系统能够成功运行的基本保障，也是用户和系统实现交互处理的重要前提。
# 5系统实现
## 5.1管理员功能模块实现
### 5.1.1管理员登录
管理员可以选择任一浏览器打开网址，输入信息无误后，以管理员的身份行使相关的管理权限，管理员登录界面设计如图5-1所示。

![](/images/0300stringboot/0387springboot/blog.005.png)

图5-1管理员登录界面
### 5.1.2监造项目管理
管理员可以通过选择监造项目管理，管理相关的监造项目信息记录，比如进行查看监造项目信息标题，修改监造项目信息来源等操作，监造项目管理界面设计如图5-2所示。

![](/images/0300stringboot/0387springboot/blog.005.png)

图5-2监造项目管理界面

### 5.1.3公告管理
管理员可以通过选择公告管理，管理相关的公告信息记录，比如进行查看公告详情,删除错误的公告信息,发布公告等操作，公告管理界面如图5-3所示。

![](/images/0300stringboot/0387springboot/blog.005.png)

图5-3 公告管理界面
### 5.1.4公告类型管理
管理员可以通过选择公告类型管理，管理相关的公告类型信息，比如查看所有公告类型,删除无用公告类型,修改公告类型,添加公告类型等操作，公告类型管理界面设计如图5-4所示。

![](/images/0300stringboot/0387springboot/blog.005.png)

图5-4公告类型管理界面
### 5.1.5 项目图纸管理
如图5.5显示的就是项目图纸管理页面，此页面提供给管理员的功能有：新增项目图纸,修改项目图纸,删除项目图纸。

![](/images/0300stringboot/0387springboot/blog.005.png)

图5.5项目图纸管理页面
### 5.1.6 项目图纸类型管理
如图5.5显示的就是项目图纸类型管理页面，此页面提供给管理员的功能有：新增项目图纸类型,修改项目图纸类型,删除项目图纸类型。

![](/images/0300stringboot/0387springboot/blog.005.png)

图5.6 项目图纸类型管理页面

# 系










