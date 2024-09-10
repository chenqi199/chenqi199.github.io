# 0031springboot阿博图书馆管理系统


# [0031springboot阿博图书馆管理系统](https://github.com/GraduationProject-springboot/0031springboot)

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

# [项目清单](https://chenqi1990.site) 包安装运行

### [github 项目仓库](https://github.com/GraduationProject-springboot/allSpringbootProjects) 开源仅有后端代码

[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV16ia6epENY?p=32)


# 研究背景
近年来，随着网络技术的不断发展，越来越多人喜欢在网络上查找各种自己所需信息。阿博图书馆管理系统对用户和管理员都有很大帮助，阿博图书馆管理系统通过和数据库管理系软件协作来实现用户与管理员之间的一个很好的操作平台，基于这一点，设计了一个阿博图书馆管理系统。

经过对以上的情况进行分析，我们对用户的实际需求进行了详细的分析，指定出了相应的开发计划，为了方便用户在线进行查看阿博图书馆管理系统各种信息进行操作，帮助管理员节省很多的管理时间以及可以减少工作量，使得管理工作更加快捷顺利的进行，因此开发设计了该系统。

随着计算机的不断发展，已经融入到我们生活工作的每一个领域中，给我们的生活工作带来了很多的便利，因此，希望可以通过该系统的开发也能使阿博图书馆管理系统实现信息化管理，减轻人的负担，提高工作效率。
## 1.2 研究现状
与其他国家相比，我国的软件产业相对落后，在信息化建设方面起步也比较晚，但是随着我国经济的不断发展，以及网络技术的不断提高，我国也在不断的进行软件行业的摸索，也得到了一些成果，我国的软件产业得到了快速的发展，越来越多的软件系统出现在人们的视线中，也逐渐改变着人们生活工作的方式。但是，对于信息化的建设，与很多发达国家相比，由于信息化程度的落后以及经费的不足，我国的阿博图书馆管理系统开发方面还是相对落后的，因此，要不断的努力探索，争取开发出一个实用的阿博图书馆管理系统，来实现阿博图书馆管理系统的信息化。因此本课题以图书信息为例，目的是开发一个实用的阿博图书馆管理系统。

阿博图书馆管理系统的开发运用java技术，以及MYSQL数据库、springboot框架等技术的支持下共同完成了该网站系统的开发，使用户可以有一个非常好的平台体验，管理员也可以通过该系统进行更加方便的管理操作，实现了之前指定好的计划。 
## 1.3 研究内容
通过对管理员和用户的需求分析，我们将该阿博图书馆管理系统的功能逐步进行了添加，然后进行功能分析和检测，而且针对这两方面进行了深入研究探讨，该阿博图书馆管理系统主要对开发背景、市场需求、数据库分析、功能模块以及开发技术进行了着重介绍和分析。最后对系统中的功能信息进行测试和分析。本次毕业实现的阿博图书馆管理系统，不管是可行性分析、系统整体框架设计还是编码，都需要严格遵守软件开发的三个周期八个阶段，在该系统的开发过程中，要保证系统具有良好的时效性、易安装性以及稳定性。在代码编写时一定要按照要求进行，让代码编写看起来更美观，开发出一个便于用户的使用的阿博图书馆管理系统是本次开发的主要目标。在系统完成之后，利用电脑来将系统进行安置，并且用户可以通过电脑随时进行查看图书信息、图书借阅、图书归还等信息。此次在阿博图书馆管理系统的开发中，对系统要进行可行性分析、系统需求分析等基本分析，并且完成系统的部署和测试，在这些功能都实现之后，通过电脑进行操作系统。系统规划分析中，需要按照以下所示的技术路线。




# `	`第二章 开发技术介绍
此次B/S结构、Java技术以及mysql数据库是该阿博图书馆管理系统的主要开发技术，然后对系统的整体设计、数据库设计、功能模块设计、系统页面设计以及系统程序设计进行了详细的研究与规划。
## 2.1  系统开发平台
在该阿博图书馆管理系统中，Eclipse 技术可以给用户带来极大方便，其主要特点就是可以使用户学习起来方便、快捷，另一方面就是信息储存量也是非常大的，该功能主要被应用为数据库中进行查询和编程。并且该功能的数据应用比较灵活，通过我们现在的发展可以得知，只要利用一小部分代码就可以来实现非常强大的功能。因此，该系统数据库开发主要是由Eclipse 技术进行系统代码管理。
## 2.2 平台开发相关技术
## ` `2.2.1 B/S结构
B/S模式也就是浏览器/服务器模式，它的界面部分是在浏览器端展示，而主要工作是由服务器端进行实现的，用户的请求由浏览器端提交给服务器端进行处理，而服务器将处理结果反馈给浏览器端，在浏览器端界面描画给用户查看。采用B/S模式不仅可以避免用户必须安装毕节教育扶贫网站软件才能开发系统或者访问系统的局限性，而且更加便利[12]。
## 2.2.2 java技术
java是一种跨平台的网页技术，最终实现网页的动态效果，与 JSP技术类似，都是在HTML中混合一些程序的相关代码，运用语言引擎来执行代码，java能够实现与管理员的交互，方便管理员的使用。

java技术具有诸多优点，可以忽略所使用的平台，实现仅需一次编写就能够到处运行使用，而且还具有很好的安全性和多平台支持的特性，能够在任何平台的任何环境中进行开发，进行系统部署和环境扩展。它也有属于自己的功能强大的开发工具的支持，并且可以通过很多渠道免费得到，这就为java技术的传播也准备了条件[6]。

## 2.2.3 Spring Boot框架
Spring Boot是Pivotal团队的一个新框架，旨在简化新Spring应用程序的初始设置和开发。该框架使用特定的配置方法，无需开发人员定义样板配置。通过这种方式，Spring Boot旨在成为蓬勃发展的快速应用程序开发领域的领导者。
Spring Boot特点：
1、创建一个单独的Spring应用程序；
2、嵌入式Tomcat，无需部署WAR文件；
3、简化Maven配置；
4、自动配置Spring；
5、提供生产就绪功能，如指标，健康检查和外部配置；
6、绝对没有代码生成和XML的配置要求；
`  `安装步骤：
`   `最基本的是，Spring Boot是一个可以被任何项目的构建系统使用的库集合。为简单起见，该框架还提供了一个命令行界面，可用于运行和测试Boot应用程序。可以从Spring存储库手动下载和安装框架的已发布版本，包括集成的CLI（命令行界面）。更简单的方法是使用Groovy enVironment Manager（GVM），它负责处理Boot版本的安装和管理。可以从GVM命令行GVMinstall springboot安装Boot及其CLI。在OS X上安装Boot时可以使用Homebrew包管理器。要完成安装，首先使用brewtappivotal / tap切换到pivotal存储库，然后执行brew install springboot命令。

## 2.2.4 MySQL数据库
MySQL是目前中小型企业进行软件系统开发时广泛使用的传统关系数据库之一，特别是近年来在 Oracle 公司的管理下，MySQL数据库的性能有了很大的提升，而且支持的功能也更加丰富。MySQL作为最早的开源关系数据库之一，最初是由瑞典的数据库公司 MySQLAB 进行开发维护的，现归甲骨文公司管理。MySQL作为最为流行的开源关系数据库，是Web应用开发者进行Web 应用开发时的首选数据库。MySQL数据库虽然是开发数据库产品，但是在广发MySQL使用者的共同维护下，MySQL本身的性能并不差。MySQL作为传统的关系数据库，与其它传统的关系数据库并无大的差别，在 MySQL数据库中，数据根据数据库使用者的定义被存储于不同的数据库表中，而且用户可以定于不同的数据库来存放不同的数据表，这和目前新兴的非关系数据库数据存储方式有着很大的不同。MySQL数据库中数据的分表分库存储方式能够最大程度的避免数据同步代码的性能损耗，使得数据库的存取速度有了很大提升，而且同时保持了很大的灵活性。因此目前的中小型软件系统大多采用 MySQL数据库进行系统数据的存储。

2.2.5 Vue.js简介

Vue.js 可以说是MVVM 架构的最佳实践，是一个JavaScriptMVVM库，是一套构建用户界面的渐进式框架。专注于 MVVM 中的 ViewModel，不仅做到了数据双向绑定，

而且也是一款相对比较轻量级的JS 库，API 简洁因为vue的双向数据绑定特性以及技术的成形，实现了项目的热加载，改完页面代码能立即在浏览器方面显示效果，提高开发效率Vue.js 是采用 Object.defineProperty 的 getter 和 setter，并结合观察者模式来实现数据绑定的。当把一个普通 Javascript 对象传给 Vue 实例来作为它的 data 选项时，

Vue 将遍历它的属性，用 Object.defineProperty 将它们转为 gettertter。用户看不到 gettertter，但是在内部它们让 Vue 追踪依赖，在属性被访问和修改时通知变化。



# 第三章 系统分析
` `通过对系统功能模块分析可以得知，主要是对项目元素组合、分解和更换做出相应的单元，再通过系统模块来规划出一个原则，系统的设计首先是围绕用户需求进行开发设计的，主要是为了能够更好的管理信息和方便用户，其次就是围绕阿博图书馆管理系统进行设计，最终的设计必须要满足用户的需求，这样才能够实现系统的最大意义和价值，并且在设计的时候一定要避免代码相互重复的情况发生。
## 3.1 可行性分析
可行性分析是每开发一个项目必不可少的一部分，可行性分析可以直接影响一个系统的存活问题，针对开发意义进行分析，还有就是是否可以通过所开发的系统来弥补传统手工统计模式的不足，是否能够更好的解决阿博图书馆管理系统存在的问题等，通过对该阿博图书馆管理系统的开发设计，不仅能够逐步减少工作人员的工作量，而且还可以进行高效工作和管理。所以该系统的开发实现了最大的意义和价值，在系统完成后，利益是否大过于成本，是否能够达到预期效果，这些方面都要进行可行性分析，再通过分析之后，就可以决定是否开发此系统。该阿博图书馆管理系统的开发设计中，以下几点进行了可行性分析：技术可行性：通过Java技术的采用，由于该技术不断成熟，所以使用该技术设计阿博图书馆管理系统是具有可行性的。经济可行性：在开发过程中，系统完成后的利益是否大过于开发成本。操作可行性：阿博图书馆管理系统的开发设计中，方便用户的可操作性和实用性。
### 3.1.1  技术可行性
由于Java技术的不断成熟，所以它在本次阿博图书馆管理系统中是非常重要的，该系统的开发主要是基于服务端采用Java 、B/S结构和mysql数据库进行开发设计的。通过对这些技术进行使用，从而保证了系统的完整性和简单性。并且在数据库中保证数据的安全性和稳定性。在校时间我们对Java语言技术和mysql数据库技术进行了学习和交流，并且对软件测试也是简单的了解，然后根据这些管理方式我们可以做出一个简单的系统开发、检验和辨别。通过Java技术和Mysql数据库的相互配合开发出一个高效、稳定的阿博图书馆管理系统。

（1）轻量级系统，使用灵活：阿博图书馆管理系统，设计时，考虑到不同使用者的习惯，让系统比较轻量级，便于安装，也完成了系统所具备的所有功能，在以上基础上，通过系统测试与优化，让操作更加灵活。

（2）系统开发0成本：该阿博图书馆管理系统，以开源的Windows 7 操作系统为基础，采用Java技术编码开发，并使用MySQL轻量级数据库，没有多余的开发成本。

（3）覆盖范围：任何城市，都能安装使用本次设计的阿博图书馆管理系统，对系统使用方没有严格的规定，平台搭建好了就能使用。
### 3.1.2 经济可行性 
通过经济效益和社会价值来决定一个系统的存活问题，是否通过开发阿博图书馆管理系统来帮助管理员减少工作，是否能够方便用户的使用，假如开发的软件不能够实现成本节约和资源节约，并且还要投入大量的时间、经济和精力，那么这个系统的开发设计是没有意义和价值的，就不具备开发设计的条件。
### 3.1.3 操作可行性
此次开发的阿博图书馆管理系统登录界面是我们最常见的一种登录窗口进行造成的，只需通过电脑就可以登录访问，没有那些复杂的登录过程。该阿博图书馆管理系统主要是采用B/S结构、Java语言技术以及mysql数据库进行开发设计的，使得系统的开发更高效和稳定，也体现出来该系统的的现代化和规范化。用户可以轻松的进行学习，其系统主要特点就是易操作和易管理。
## 3.2 系统性能分析
1.系统功能完整性：根据系统每一个功能模块，都能够设计出当初的算法和代码，用户信息主要是以文字和表格的模式进行介绍。

2.系统运行分析：系统中的每一个功能都要有相应的代码和编写数据的关系。系统的物理的数据主要是通过需求分析和可行性分析进行分析和显示的。

3.界面设计：系统中的软件都是由不同的代码来进行处理和分析的，并且保证了系统界面的易操作性能。

4.安全分析：不同的角色要有不同的信息，所以我们登录系统时必须要使用自己的账号和密码进行登录，不能随意进行操作，这样才可以保证系统的安全性。
## 3.3 系统功能需求分析
任务需求分析是每个系统开发设计必不可少的一部分，系统质量的好坏可以直接影响系统的存活问题，所以我们必须要将任务需求分析做到位，阿博图书馆管理系统的设计在初期的分析是尤为重要的，通过任务分析可以更顺利的进行系统设计，并且保证了用户的满意度。

（1）用户功能需求

用户进入系统可以查看首页、个人中心、图书借阅管理、图书归还管理、缴纳罚金管理、我的收藏管理等操作。用户用例图如图3-1所示。
######### ![](/images/0000stringboot/0031springboot/blog.001.png)
图3-1用户用例图

（2）管理员功能需求

管理员登陆后，主要功能模块包括首页、个人中心、用户管理、图书分类管理、图书信息管理、图书借阅管理、图书归还管理、缴纳罚金管理、留言板管理、系统管理等功能。管理员用例图如图3-2所示。

![](/images/0000stringboot/0031springboot/blog.002.png)

图3-2 管理员用例图


















# 第四章 系统设计
## 4.1 系统的功能结构图
过系统需求分析，该阿博图书馆管理系统功能结构图如图4-1所示：
#########
![](/images/0000stringboot/0031springboot/blog.003.png)

图4-1 系统功能结构图


## 4.2 数据库概念结构设计
### ` `4.2.1  数据库E-R图
概念设计主要是通过数据库的概念结构和模式进行建立数据库嗯逻辑结构，然后利用数据库的DBMS进行完成，它不需要计算机系统的支持。通过系统的整体来看，主要是对数据库进行管理、整理、更新等操作。数据库的功能是非常强大的，每个系统的开发肯定离不开数据库，通过数据库可以看得出整个系统的质量和效率，根据以上的系统分析，对系统中的主要实体进行规划。以下是几个关键实体的实体关系图：

(1) 用户管理实体E-R图如图4-2所示：

![](/images/0000stringboot/0031springboot/blog.004.png)

`        `图4-2用户管理实体属性图

` `(2) 图书信息管理实体E-R图如图4-3所示：

![](/images/0000stringboot/0031springboot/blog.005.png)

图4-3图书信息管理实体属性图

(3) 缴纳罚金管理实体E-R图如图4-4所示：

![](/images/0000stringboot/0031springboot/blog.006.png)

`   `图4-4缴纳罚金管理实体图


### 4.2.2 数据库逻辑结构设计
数据库的主要功能就是对相关信息就行存储，通过某种计算进行数据储存，其数据库的数据存储是井井有条的。并且其中的数据具有一定的独立性和安全性。通过对系统功能设计的要求和功能模块的规划，该阿博图书馆管理系统的设计与实现设计到了多个数据表。以下信息是介绍数据库表的设计结构以及功能建立数据库表：

表4-1：jiaonafajin表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|int|11|PRIMARY KEY|
|addtime|varchar|200|DEFAULT NULL|
|jieyuedanhao|varchar|200|DEFAULT NULL|
|tushubianhao|varchar|200|DEFAULT NULL|
|tushumingcheng|varchar|200|DEFAULT NULL|
|fakuanshuoming|varchar|200|DEFAULT NULL|
|fakuanjine|varchar|200|DEFAULT NULL|
|fakuanriqi|varchar|200|DEFAULT NULL|
|yonghuming|varchar|200|DEFAULT NULL|
|shouji|varchar|200|DEFAULT NULL|
表4-2：tushuguihai表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|int|11|PRIMARY KEY|
|addtime|varchar|200|DEFAULT NULL|
|jieyuedanhao|varchar|200|DEFAULT NULL|
|tushubianhao|varchar|200|DEFAULT NULL|
|tushumingcheng|varchar|200|DEFAULT NULL|
|tushufenlei|varchar|200|DEFAULT NULL|
|tupian|varchar|200|DEFAULT NULL|
|kejietianshu|varchar|200|DEFAULT NULL|
|jieyueriqi|varchar|200|DEFAULT NULL|
|yinghairiqi|varchar|200|DEFAULT NULL|
|guihairiqi|varchar|200|DEFAULT NULL|
|yonghuming|varchar|200|DEFAULT NULL|
|shouji|varchar|200|DEFAULT NULL|
|sfsh|varchar|200|DEFAULT NULL|
|shhf|varchar|200|DEFAULT NULL|

表4-3：tushujieyue表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|int|11|PRIMARY KEY|
|addtime|varchar|200|DEFAULT NULL|
|jieyuedanhao|varchar|200|DEFAULT NULL|
|tushubianhao|varchar|200|DEFAULT NULL|
|tushumingcheng|varchar|200|DEFAULT NULL|
|tushufenlei|varchar|200|DEFAULT NULL|
|tupian|varchar|200|DEFAULT NULL|
|kejietianshu|varchar|200|DEFAULT NULL|
|kejieshuliang|varchar|200|DEFAULT NULL|
|jieyueriqi|varchar|200|DEFAULT NULL|
|jieyuetianshu|varchar|200|DEFAULT NULL|
|yinghairiqi|varchar|200|DEFAULT NULL|
|jieyuezhuangtai|varchar|200|DEFAULT NULL|
|yonghuming|varchar|200|DEFAULT NULL|
|xingming|varchar|200|DEFAULT NULL|
|shouji|varchar|200|DEFAULT NULL|
|shenfenzheng|varchar|200|DEFAULT NULL|
|sfsh|varchar|200|DEFAULT NULL|
|shhf|varchar|200|DEFAULT NULL|

表4-4：tushuxinxi表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|int|11|PRIMARY KEY|
|addtime|varchar|200|DEFAULT NULL|
|tushubianhao|varchar|200|DEFAULT NULL|
|tushumingcheng|varchar|200|DEFAULT NULL|
|tushufenlei|varchar|200|DEFAULT NULL|
|tupian|varchar|200|DEFAULT NULL|
|zuozhe|varchar|200|DEFAULT NULL|
|chubanshe|varchar|200|DEFAULT NULL|
|tushuzhuangtai|varchar|200|DEFAULT NULL|
|kejietianshu|varchar|200|DEFAULT NULL|
|kejieshuliang|varchar|200|DEFAULT NULL|
|tushujianjie|varchar|200|DEFAULT NULL|

表4-5：yonghu表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|int|11|PRIMARY KEY|
|addtime|varchar|200|DEFAULT NULL|
|yonghuming|varchar|200|DEFAULT NULL|
|mima|varchar|200|DEFAULT NULL|
|xingming|varchar|200|DEFAULT NULL|
|xingbie|varchar|200|DEFAULT NULL|
|touxiang|varchar|200|DEFAULT NULL|
|shouji|varchar|200|DEFAULT NULL|
|shenfenzheng|varchar|200|DEFAULT NULL|

表4-6：tushufenlei表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|int|11|PRIMARY KEY|
|addtime|varchar|200|DEFAULT NULL|
|tushufenlei|varchar|200|DEFAULT NULL|

#########

# 第五章 系统功能实现
5.1管理员功能模块

管理员登录，通过填写用户名、密码、角色进行登录，如图5-1所示。

![](/images/0000stringboot/0031springboot/blog.007.png)

图5-1管理员登录界面图

管理员登录进入阿博图书馆管理系统页面可以查看首页、个人中心、用户管理、图书分类管理、图书信息管理、图书借阅管理、图书归还管理、缴纳罚金管理、留言板管理、系统管理等信息，如图5-2所示。

![](/images/0000stringboot/0031springboot/blog.008.png)

图5-2管理员功能界面图

用户管理，在用户管理列表可以查看用户名、姓名、性别、头像、手机、身份证等内容，还可以根据需要进行详情、修改或删除等操作，如图5-3所示。

![](/images/0000stringboot/0031springboot/blog.009.png)

图5-3用户管理界面图

图书分类管理，在图书分类管理列表可以查看图书分类等信息，并可根据需要进行详情、修改或删除等操作，如图5-4所示。

![](/images/0000stringboot/0031springboot/blog.010.png)

图5-4图书分类管理界面图

图书信息管理，在图书信息管理列表可以查看图书编号、图书名称、图书分类、图片、作者、出版社、图书状态、可借天数、可借数量等信息，并可根据需要进行详情、修改查看评论或删除等操作，如图5-5所示。

![](/images/0000stringboot/0031springboot/blog.011.png)

图5-5图书信息管理界面图

图书借阅管理，在图书借阅管理页面可以查看借阅单号、图书编号、图书名称、图书分类、图片、可借天数、可借数量、借阅日期、借阅天数、应还日期、借阅状态、用户名、姓名、手机、身份证、审核回复、审核状态、审核等内容，并且根据需要进行详情、修改等操作，如图5-6所示。

![](/images/0000stringboot/0031springboot/blog.012.png)

图5-6图书借阅管理界面图

缴纳罚金管理，在缴纳罚金管理页面可以查看借阅单号、图书编号、图书名称、罚款说明、罚款金额、罚款日期、用户名、手机、是否支付等内容，并且根据需要进行详情、修改或删除等操作，如图5-7所示。

![](/images/0000stringboot/0031springboot/blog.013.png)

图5-7缴纳罚金管理界面图

轮播图；该页面为轮播图管理界面。管理员可以在此页面进行首页轮播图的管理，通过新建操作可在轮播图中加入新的图片，还可以对以上传的图片进行修改操作，以及图片的删除操作，如图5-8所示。

![](/images/0000stringboot/0031springboot/blog.014.png)

图5-8轮播图管理界面图



5.2用户功能模块

用户登录进入阿博图书馆管理系统可以查看首页、个人中心、图书借阅管理、图书归还管理、缴纳罚金管理、我的收藏管理等内容，如图5-9所示。

![](/images/0000stringboot/0031springboot/blog.015.png)

图5-9用户功能界面图

图书归还管理，在图书归还管理列表中通过查看借阅单号、图书编号、图书名称、图书分类、图片、可借天数、借阅日期、应还日期、归还日期、用户名、手机、审核回复、审核状态等信息，并且根据需要进行详情、修改或删除等操作，如图5-10所示。

![](/images/0000stringboot/0031springboot/blog.016.png)

图5-10图书归还管理界面图

##
## 5.3前台首页功能模块
阿博图书馆管理系统，在阿博图书馆管理系统页面可以查看首页、图书信息、公告信息、留言反馈、个人中心、后台管理等内容，如图5-11所示。

![](/images/0000stringboot/0031springboot/blog.017.png)

图5-11前台首页界面图

用户注册、用户登录，通过注册填写用户名、密码、姓名、性别、手机、身份证等信息进行注册、登录，如图5-12所示。

![](/images/0000stringboot/0031springboot/blog.018.png)

![](/images/0000stringboot/0031springboot/blog.019.png)


图5-12用户注册、用户登录界面图

图书信息，在图书信息页面可以查看图书编号、图书名称、图书分类、图片、作者、出版社、图书状态、可借天数、可借数量、点击次数等信息，进行借阅、点我收藏操作，如图5-13所示。 

![](/images/0000stringboot/0031springboot/blog.020.png)

图5-13图书信息界面图

个人中心，在个人中心页面可以填写用户名、密码、姓名、性别、头像、手机、身份证等信息进行更新信息、退出登录操作，如图5-14所示。

![](/images/0000stringboot/0031springboot/blog.021.png)

图5-14个人中心界面图

留言反馈，在留言反馈页面可以填写留言内容、回复内容、用户名等信息进行立即提交操作，如图5-15所示。 

![](/images/0000stringboot/0031springboot/blog.022.png)

图5-15留言反馈界面图



# 系统测










