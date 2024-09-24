# ssm291生鲜配送系统设计及实现+jsp


# [项目清单 包安装运行](http://chenqi1990.site) 官网地址 http://chenqi1990.site

# [ssm291生鲜配送系统设计及实现+jsp](https://github.com/GraduationProject-springboot/)

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### [github 项目仓库](https://github.com/GraduationProject-springboot/allSpringbootProjects) 开源仅有后端代码

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1gn8XeNE2J?p=88)

# 第1章 绪论
## 1.1 课题背景
互联网发展至今，无论是其理论还是技术都已经成熟，而且它广泛参与在社会中的方方面面。它让信息都可以通过网络传播，搭配信息管理工具可以很好地为人们提供服务。所以各行业，尤其是规模较大的企业和学校等都开始借助互联网和软件工具管理信息，传播信息，共享信息等等，以此可以增强自身实力，提高在同行业当中的竞争能力，并从各种激烈的竞争中获取发展的机会。针对生鲜配送信息管理混乱，出错率高，信息安全性差，劳动强度大，费时费力等问题，经过分析和考虑，在目前的情况下，可以引进一款生鲜配送系统这样的现代化管理工具，这个工具就是解决上述问题的最好的解决方案。它不仅可以实时完成信息处理，还缩短生鲜配送信息管理流程，使其系统化和规范化。同时还可以减少工作量，节约生鲜配送信息管理需要的人力和资金。所以生鲜配送系统是信息管理环节中不可缺少的工具，它对管理者来说非常重要。
## 1.2 课题意义 
现如今，信息种类变得越来越多，信息的容量也变得越来越大，这就是信息时代的标志。近些年，计算机科学发展得也越来越快，而且软件开发技术也越来越成熟，因此，在生活中的各个领域，只要存在信息管理，几乎都有计算机的影子，可以说很多行业都采用计算机的方式管理信息。信息计算机化处理相比手工操作，有着保密性强，效率高，存储空间大，成本低等诸多优点。针对生鲜配送信息，采用生鲜配送系统可以有效管理，使信息管理能够更加科学和规范。

总之，在实际中使用生鲜配送系统，其意义如下：

第一点：生鲜配送系统的实际运用，可以帮助管理人员在短时间内完成信息处理工作；

第二点：通过系统页面的合理排版布局，可以更加直观的展示系统的内容，并且使用者可以随时阅读页面信息，随时操作系统提供的功能；

第三点：可以实现信息管理计算机化；

第四点：可以降低信息管理成本；
## 1.3 研究内容
对生鲜配送系统设计制作，不仅需要技术支撑，也需要大量的理论研究。本文在对生鲜配送系统进行介绍时，将按照如下内容进行。

第一部分：介绍生鲜配送系统研究的背景意义，便于用户了解系统；

第二部分：介绍开发生鲜配送系统需要搭建的环境，包括技术和工具；

第三部分：介绍用户对生鲜配送系统的功能要求，以及对生鲜配送系统的性能要求等；

第四部分：介绍数据库的设计方案，以及根据功能要求设计的功能结构；

第五部分：介绍通过编码最终实现的系统功能运行效果；

第六部分：介绍系统的功能测试，对系统进行综合检测，并及时解决系统出现的问题，直至系统运行正常。
# 第2章 开发环境与技术
生鲜配送系统的编码实现需要搭建一定的环境和使用相应的技术，接下来的内容就是对生鲜配送系统用到的技术和工具进行介绍。
## 2.1 MYSQL数据库
本课题所开发的应用程序在数据操作方面是不可预知的，是经常变动的，没有办法直接把数据写在文档里，这样不仅仅不安全，也不能实现应用程序的功能。如果要能实现应用程序所需要的数据存储功能，就避免不了要进行专业数据库存储软件的选择。基本上应用程序实现的功能不算太复杂，市面上任何一个关系型数据库软件都可以实现。参考自己的学习进度和操作习惯来讲，Oracle数据库是适合的，但是所需要的的安装软件很大，并且有好多不需要的功能都是开启的状态，十分消耗电脑资源，所以没有选择Oracle数据库，而SQL Server数据库虽然学过，但是安装的时候因为电脑上可能有其他的软件存在，经常性的出问题，而安装问题不好解决就需要重新安装操作系统，这样对已经存在的软件来讲又是一种时间上的浪费。只有MySQL数据库，安装包小，安装速度快，操作简单，哪怕安装出问题也好解决，不用重装操作系统，也不影响电脑上运行的其他软件，消耗资源也少，最重要的是在功能方面完全的符合设计需要，所以最后选择了MySQL数据库作为应用软件开发需要的数据库。
## 2.2 Java语言
Java语言发展有25年多了，在互联网行业经过这么多年的发展，还依然在市场的占有率上有半壁江山，依然受到很多程序员的喜爱，好多从业人员进行学习，随着互联网从业人员的增加，并没有降低Java语言的江湖地位，算是一个常青藤。Java语言学习很简单，当然这是针对于前辈C++来讲的，C++语言相当的强悍。Java取消了很多C++特征，比如go to这些语句，还有取消了主文件，让所有的文件都是类，类里都是数组和各种对象，还让Java自己处理各种对象的引用和回收，让开发人员只需要创建对象，使用对象，编辑代码逻辑，不需要关注性能方面，让数据的各种存储交给Java自己处理，可以花更多的时间研究应用程序之间的关系，让开发变得更专注，就像赛车的驾驶员一样，只需要了解各种车辆的性能，并且进行操作，不需要研究轱辘如何制造，这样让程序开发更加的细化。
## 2.3 JSP技术  
在动态网站的兴起之初，作为高级编程语言的Java自然不会放弃这个领域的蛋糕。Sun公司推出了Servlet作为输出动态网站的一种技术标准，虽然不怎么受当时程序员的喜爱，但是当初也没有太多的选择，随后几个月PHP语言问世，不考虑性能和效率如何，起码在书写网页所需要的动态代码块和静态代码块方面进行了区分，让书写效率和可读效率大大的提升，所以很多Java程序员以及刚入行的初级程序员都选择了PHP语言作为自己职业的发展方向，Sun公司为了维护Java语言在高级编程语言上的江湖地位，防止PHP继续抢走市场份额占有率，Sun公司联合Apache基金会研发了一个关于Java动态网页的一个新型的技术标准，这就是JSP技术。JSP吸取了PHP语言在页面书写上面的所有优点，但是又背靠Java EE的庞大后台，又能实现很多通过Java组件就能实现的功能，在JSP页面上可以直接引用那些组件，让JSP更加的强壮丰富。保证了Java技术纵向的可持续发展，并且在动态网站开发领域终于站稳了脚跟，其他PHP开发人员可以很快的转移到JSP进行开发，不考虑一些特殊组件或者功能的开发，只从动态页面的开发上来讲，完全实现了PHP程序和JSP程序的几乎无成本的转换，JSP技术就这样的发展了起来。
## 2.4 SSM框架
SSM框架不是一个框架的名称，而是三个框架的首字母缩写，分别是Spring框架、SpringMVC框架、MyBatis框架。是目前Java开发者中学习的首选框架。

Spring框架继承了JavaEE和EJB框架的优点，在依赖注入方面去掉了臃肿的配置，在面向切面方面也简化了代码数量，提高了代码品质。依赖注解进行配置，让所有的依赖都可以通过程序的自动配置和寻找，减少了代码写作数量，提高了代码阅读性。

SpringMVC框架与Spring只是一个公司的，在底层代码结构上可以复用，但是最主要的功能是对数据提交请求进行过滤，并且对数据的返回进行过滤，不限于页面是JSP技术，也可以是其他的技术，更容易大型开发的集合技术。

MyBatis框架摒弃了Hibernate框架的配置臃肿方面，有时候Hibernate框架业务比较复杂的时候，代码量反而增加，性能下降，无法对底层的数据库语句优化，而MyBatis框架则有效的解决了这个方面，可以通过Java语句，对数据库操作语句进行优化，代码更简洁，执行效率更高，并且可以生产一些模块化代码，解决了开发过程中容易出现的实体映射方面的操作。
## 2.5 B/S架构
B/S架构是软件行业针对C/S架构来进行区分的，用来描述浏览器与服务器之间的一种架构模式。一般选择B/S架构最主要的原因就是方便维护，当程序开发的时候，可以在本地进行测试，一般的集成开发环境都自带的有开发和一键部署，本地浏览器可以及时的看到效果，测试人员有专门的服务器，只需要部署上去即可，如果中间有问题都可以进行整改的。应用程序升级，只需要后台维护代码即可，客户方面还是用之前的浏览器进行访问，所以客户端方面是很方便的。现在市面上基本上所有的操作系统平台只要是有视窗模式的，除了命令行操作界面的窗口之外，在视窗模式都是可以安装浏览器的，所以任何带视窗模式的电脑操作系统自带的浏览器或者是其他厂家的浏览器，或者是移动端的浏览器，都可以进行访问服务器的。访问服务器占用客户端资源是很少，而且不容易出错，哪怕客户端这边出现大的问题，只需要重装系统然后再安装上浏览器即可。在程序功能和客户体验上面，选择B/S架构进行应用程序开发，是很适合当今社会的主流发展趋势的。
## 2.6 Tomcat 介绍
刚开始学习Java语言的时候，是不知道还有Tomcat这些东西的，各种语法各种输出在控制台进行输出结果，当Java网站开发的时候就不可避免的学习到了Tomcat服务器。Tomcat准确的来讲不算是服务器，可以说是JSP引擎或者一个容器，这些都是学术上或者原理上都比较贴切的，但是实际工作中Tomcat就是作为一个web服务器来用的，因为可以实现网站的发布和运行。因为工作原理的原因，Tomcat一般作为中小型企业和并发量并不突出的一种轻量级的服务器存在的，比如某些行业的应用系统，本身客户端就不多，需要的连接也不多，一般都用Tomcat的。Tomcat里面可以配置多个网站，配置文件后缀是config的文档，类似于XML的结构，比较清晰明了。每当Java发布新的版本的时候，Tomcat也会为了匹配Java的版本进行升级，目前Tomcat版本已经到版本10了。Tomcat标识是一只有点发黄的小猫咪，当Tomcat配置成功一般测试的时候能看到这个小猫咪就算是成功的，才能进行下一步的配置。Tomcat服务器在Java网站开发中还是挺合适的。


# 第3章 系统分析
面对即将开发的系统，进行提前的分析是必要的。这也是开发流程中必须有的环节。通常分析系统期间，主要涉及的内容包括系统开发可行性问题，对系统功能和性能的分析等问题。
## 3.1 可行性分析
在正式对需要建设的项目进行投资前，有一个比较关键的步骤是不能缺少的，那就是可行性分析。它主要从当前技术，经济等角度去评估系统的可行性，在投资决策中常常采用这种科学的方法来论证项目。
### 3.1.1 技术可行性
当前，系统开发的技术已经发展成熟，而且通过计算机网络可以获取开发工具的使用方法，以及规范化编写的模块化代码，这些知识可以帮助开发者顺利完成本系统的编码工作。
### 3.1.2 经济可行性
本系统开发期间需要配置的软件环境，可以免费通过开发类官网下载安装，需要配置的硬件设备也不需要具备很高的性能，通常网吧电脑，或学校计算机机房的电脑都符合要求。因此，从经济方面考虑，生鲜配送系统开发可行。
### 3.1.3 操作可行性
生鲜配送系统根据用户使用习惯进行开发，设计的界面具有统一性，并具备优秀的导航功能。所以，只要会简单操作电脑的人员，可以无压力操作生鲜配送系统。

总之，从上述的论证来看，本系统可以开发。
## 3.2 系统流程
流程图这样的工具可以直观反映出系统内部的操作逻辑，可以帮助用户更好的理解系统。
### 3.2.1 操作流程
进入本系统需要访问者提供验证信息。验证合格的访问者才能获取访问资格。其具体的操作流程见下图。访问者根据登录界面设置的信息项如实填写，待信息通过验证后，访问者可以进入指定的页面享受本系统提供的服务和阅读本系统的相关信息。

![](/images/0200ssm/ssm291/blog.001.png)

图3.1 操作流程图
### 3.2.2 登录流程
本系统的登录模块，其内部的流程见下图。主要对访问本系统的人员提供的验证信息进行逐个判断，系统面对录入错误的信息会给出提示，比如，提示账号不对，或提示密码不匹配等提示信息。总之，在登录页面填写的所有信息都符合要求，访问者就登录成功了。

![](/images/0200ssm/ssm291/blog.002.png)

图3.2 登录流程图
### 3.2.3 删除信息流程
本系统在经常性的使用后，会产生很多失去价值的信息，因此就需要及时清理数据，腾出系统的空间。对这些数据进行清理时，其对应的流程见下图。先选中要清理的数据，通过反复确认需要清理的数据，避免操作人员误删。已经删除的数据就不会出现在系统里面。

![](/images/0200ssm/ssm291/blog.003.png)

图3.3 删除信息流程图
### 3.2.4 添加信息流程
本系统主要用于显示信息，提供服务，其中，数据添加功能就是其中的服务之一，具体流程见下图。让操作者在信息添加的页面录入数据，待这些数据被提交检验合格后，就会在系统指定页面显示出来。

![](/images/0200ssm/ssm291/blog.004.png)

图3.4 添加信息流程图
## 3.3 性能需求
进行需求分析，包括了根据用户实际需求制定功能，也涵盖了对即将设计的系统进行性能上的需求分析。所以一般分析系统时，一方面要分析系统功能，另一方面也要分析系统的性能。毕竟设计开发出一个好性能的系统可以确保系统的质量可靠。

接下来分析系统的性能，还要从界面友好性，系统的时间特性，系统的可靠性等方面来分析说明。

（1）系统的容量要求：对本系统完成数据处理的容量最大化进行确定。也就是确定系统处理数据的容量临界值，超过这个临界值，可能系统就运行不正常了。

（2）系统精度的要求：确定数据传输需要达到的精度值，也包括了数值计算的精度值，数据的精度值的设置等。

（3）时间特性要求：系统处理数据都有时间要求，这也是系统的时间特性。通常都会把数据处理的时间进行分析，也会设置用户请求的响应时间，还有系统在满负荷运行时可以偏离的范围数值等都需要提前分析确定。

（4）适应性要求：系统在面对系统环境的改变时，其自身适应这种变化的能力，也需要通过参数信息体现。比如说，在面对变化的需求，系统就要去适应这种变化，通过指出需要设计的过程或者是需要设计的软件来体现系统的适应性。

（5）界面友好性：除了功能上需要考虑用户需求外，在人机交互界面的设计上，也需要考虑用户的使用习惯，包括界面的布局，界面基调选择以及颜色搭配等。尽量做到用户在接受简单的培训之后，可以对系统进行独立操作。

（6）系统可靠性：对于初学者而言，很容易出现一个问题，就是设计开发的系统，因为人为的误操作出现崩溃，有些也会导致电脑死机。这样的现象也说明这种容错能力低下的系统是不可靠的。完全不能作为生活中处理信息的系统。当下，系统开发要保证可靠性，设计时，把模块化和结构化的设计理念也考虑进来。如果遇到对时效性要求比较严格的系统，也需要采取其它的措施，比如双机系统，还有磁盘阵列等方式。还有就是一个可靠性的系统，对设备的供电能力也有要求。

运行在计算机上的系统大都担负着信息处理的任务，对于它们而言，其性能要求有：完成信息查询，需要的响应时间；对终端设备的连接数量的确定；对存储数据的容量的安排；以及存储数据的可扩充的容量的设置，比如说系统存放近几个月，或者存放近几年的数据；完成报表打印数量的设置，也包括报表打印种类的设置等。
## 3.4 功能需求
不同的系统提供的服务也不相同，其对应的功能也不相同，所以，系统开工前，需要明确其用途，确定其功能。由此，才可以进行各个任务的开展。

生鲜配送系统经过分析，确定了其需要设置管理员的角色，其操作的功能通过用例图展示（见下图）。管理员管理商品，商品评价，积分记录，用户购物订单。

![](/images/0200ssm/ssm291/blog.005.png)

图3.5 管理员用例图

生鲜配送系统经过分析，确定了其需要设置用户的角色，其操作的功能通过用例图展示（见下图）。用户收藏商品，评价商品，购买商品，支付购买订单，管理收货地址。

![](/images/0200ssm/ssm291/blog.006.png)

图3.6 用户用例图

# 第4章 系统设计
一个成功设计的系统在内容上必定是丰富的，在系统外观或系统功能上必定是对用户友好的。所以为了提升系统的价值，吸引更多的访问者访问系统，以及让来访用户可以花费更多时间停留在系统上，则表明该系统设计得比较专业。
## 4.1 设计原则
本系统在设计过程中需要依照一定的设计原则进行，目的就是为了让开发的系统具备高质量，齐全完备的功能，方便简单的操作，如此才可以最大限度的满足使用者的要求。系统设计原则除了基本的易操作原则，安全性原则外，还有准确性原则，实用性原则，可维护性原则。

第一个设计原则：易操作原则，针对本系统设计的功能要完备齐全，编码时，设计的各个接口要具备友好性，使用者一旦使用本系统时，要能够轻松上手，操作本系统处理数据时，要具备便利性。此外，也需要设计一些必要提示，引导使用者操作系统。

第二个设计原则：安全性原则，本系统在登录模块要对各个访问者进行身份验证，系统会通过访问者输入的信息进行判断，使用提前编写的安全验证代码进行数据比对，引导匹配成功的访问者进入指定的操作界面。这样可以避免无关性访问者窃取系统的数据。

第三个设计原则：准确性原则，为了保证使用者登记的数据是正确的，需要提前设计数据纠错机制，让使用者可以通过系统的报错提示，仔细检查登记的错误信息，并及时纠正错误，填写规范正确的信息。比如设置密码时，要求密码的长度不能低于6个字符，且数据类型要求不能全部是数字等都能进行规范。

第四个设计原则：实用性原则，本系统主要用于处理信息，在实际工作中，要帮助使用者完成信息处理任务，同时本系统在面对特殊情况时，也要能够满足信息处理的需要。另外，为了后期便于在本系统中进行功能的扩充，也需要提前预留好空间。

第五个设计原则：可维护性原则，本系统在实际使用期间，难免会遇到一些故障，因此，本系统在应对故障时，要能够进行诊断并弱化故障，可以在短时间内进行自维护。
## 4.2 功能结构设计
在前面分析的管理员功能的基础上，进行接下来的设计工作，最终展示设计的管理员结构图（见下图）。管理员管理商品，商品评价，积分记录，用户购物订单。

![](/images/0200ssm/ssm291/blog.007.png)

图4.1 管理员功能结构图

在前面分析的用户功能的基础上，进行接下来的设计工作，最终展示设计的用户结构图（见下图）。用户收藏商品，评价商品，购买商品，支付购买订单，管理收货地址。

![](/images/0200ssm/ssm291/blog.008.png)

图4.2 用户功能结构图
## 4.3 数据库设计
开发一个系统也需要提前设计数据库。这里的数据库是相关数据的集合，存储在一起的这些数据也是按照一定的组织方式进行的。目前，数据库能够服务于多种应用程序，则是源于它存储方式最佳，具备数据冗余率低的优势。虽然数据库为程序提供信息存储服务，但它与程序之间也可以保持较高的独立性。总而言之，数据库经历了很长一段时间的发展，从最初的不为人知，到现在的人尽皆知，其相关技术也越发成熟，同时也拥有着坚实的理论基础。
### 4.3.1 数据库概念设计
这部分内容需要借助数据库关系图来完成，也需要使用专门绘制数据库关系图的工具，比如Visio工具就可以设计E-R图（数据库关系图）。设计数据库，也需要按照设计的流程进行，首先还是要根据需求完成实体的确定，分析实体具有的特征，还有对实体间的关联关系进行确定。最后才是使用E-R模型的表示方法，绘制本系统的E-R图。不管是使用亿图软件，还是Visio工具，对于E-R模型的表示符号都一样，通常矩形代表实体，实体间存在的关系用菱形符号表示，实体的属性也就是实体的特征用符号椭圆表示。最后使用直线将矩形，菱形和椭圆等符号连接起来。接下来就开始对本系统的E-R图进行绘制。

（1）下图是订单实体和其具备的属性。

![](/images/0200ssm/ssm291/blog.009.png)

图4.4 订单实体属性图

（2）下图是商品实体和其具备的属性。

![](/images/0200ssm/ssm291/blog.010.png)

图4.5 商品实体属性图

（3）下图是用户实体和其具备的属性。

![](/images/0200ssm/ssm291/blog.011.png)

图4.6 用户实体属性图

4. 下图是购物车实体和其具备的属性。

![](/images/0200ssm/ssm291/blog.012.png)

图4.7 购物车实体属性图

4. 下图为上述各实体间相互之间的关系。

![](/images/0200ssm/ssm291/blog.013.png)

图4.8 实体间关系E-R图
### 4.3.2 数据库物理设计
本数据库是关系型数据库，因此对二维表的结构设计也比较关键。毕竟二维表格模型就是关系型数据库中的关系模型。而一些常用的关系模型中的概念也需要了解，才可以对关系模型进行设计。下面就简单介绍关系，元组，属性，域，关键字等常用概念的含义。

关系：关系就是数据库中的一张数据表，每张数据表都有命名，也就是每个关系也有名字，那就是数据表名；

元组：元组就是数据表中的一行记录；

属性：属性就是数据表中的字段，也就是数据表中的一列；

域：域就是对数据表中属性的取值进行限定；

关键字：关键字就是数据表中的主键；

在了解了表结构设计的常用概念后，接下来就需要使用前面绘制的E-R模型完成表结构的设计工作，并在数据库中创建数据表，并为各个数据表进行命名。以下就对设计的结果通过表格形式进行展示。

![打开新的 phpMyAdmin 窗口](blog.014.png "打开新的 phpMyAdmin 窗口")表4.1 地址信息表

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|userid|bigint(20)|否||用户id|
|address|varchar(200)|否||地址|
|name|varchar(200)|否||收货人|
|phone|varchar(200)|否||电话|
|isdefault|varchar(200)|否||是否默认地址[是/否]|
表4.2 购物车信息表

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|tablename|varchar(200)|是|shangpinxinxi|商品表名|
|userid|bigint(20)|否||用户id|
|goodid|bigint(20)|否||商品id|
|goodname|varchar(200)|是|NULL|商品名称|
|picture|varchar(200)|是|NULL|图片|
|buynumber|int(11)|否||购买数量|
|price|float|是|NULL|单价|
|discountprice|float|是|NULL|会员价|
表4.3 商品评论信息表

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|refid|bigint(20)|否||关联表id|
|userid|bigint(20)|否||用户id|
|content|longtext|否||评论内容|
|reply|longtext|是|NULL|回复内容|
表4.4 积分信息表

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|yonghu\_id|bigint(20)|否||用户id|
|shangpinxinxi\_id|bigint(20)|否||商品id|
|jifenjilu\_types|varchar(200)|是|NULL|积分类型|
|buynumber|int(11)|否||积分数量|
|insert\_time|timestamp|否|CURRENT\_TIMESTAMP|记录时间|
|create\_time|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
表4.5 新闻资讯信息表

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|title|varchar(200)|否||标题|
|picture|varchar(200)|否||图片|
|content|longtext|否||内容|
表4.6 订单信息表

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|orderid|varchar(200)|否||订单编号|
|tablename|varchar(200)|是|shangpinxinxi|商品表名|
|userid|bigint(20)|否||用户id|
|goodid|bigint(20)|否||商品id|
|goodname|varchar(200)|是|NULL|商品名称|
|picture|varchar(200)|是|NULL|商品图片|
|buynumber|int(11)|否||购买数量|
|price|float|否|0|价格/积分|
|discountprice|float|是|0|折扣价格|
|total|float|否|0|总价格/总积分|
|discounttotal|float|是|0|折扣总价格|
|type|int(11)|是|1|支付类型|
|status|varchar(200)|是|NULL|状态|
|address|varchar(200)|是|NULL|地址|
表4.7 商品分类信息表

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|shangpinfenlei|varchar(200)|是|NULL|商品分类|
表4.8 商品信息表

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|shangpinbianhao|varchar(200)|是|NULL|商品编号|
|shangpinmingcheng|varchar(200)|是|NULL|商品名称|
|shangpinfenlei|varchar(200)|是|NULL|商品分类|
|shuliang|varchar(200)|是|NULL|数量|
|pinpai|varchar(200)|是|NULL|品牌|
|guige|varchar(200)|是|NULL|规格|
|xiangqing|longtext|是|NULL|详情|
|fengmian|varchar(200)|是|NULL|封面|
|clicktime|datetime|是|NULL|最近点击时间|
|clicknum|int(11)|是|0|点击次数|
|price|float|否||原价|
|discountprice|float|是|NULL|折扣价|
|jifen|float|是|NULL||
|flag|int(11)|是|NULL|是否上架(1:上架,2:下架)|
表4.9用户信息表

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|yonghuzhanghao|varchar(200)|否||用户账号|
|yonghuxingming|varchar(200)|否||用户姓名|
|mima|varchar(200)|否||密码|
|xingbie|varchar(200)|是|NULL|性别|
|lianxidianhua|varchar(200)|是|NULL|联系电话|
|dianziyouxiang|varchar(200)|是|NULL|电子邮箱|
|money|float|是|0|余额|
|jifen|float|是|NULL|积分|
表4.10 收藏信息表

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|创建时间|
|userid|bigint(20)|否||用户id|
|refid|bigint(20)|是|NULL|收藏id|
|tablename|varchar(200)|是|NULL|表名|
|name|varchar(200)|否||收藏名称|
|picture|varchar(200)|否||收藏图片|
表4.11 管理员信息表

|字段|类型|空|默认|注释|
| :-: | :-: | :-: | :-: | :-: |
|id (主键)|bigint(20)|否||主键|
|username|varchar(100)|否||用户名|
|password|varchar(100)|否||密码|
|role|varchar(100)|是|管理员|角色|
|addtime|timestamp|否|CURRENT\_TIMESTAMP|新增时间|
![打开新的 phpMyAdmin 窗口](blog.015.png "打开新的 phpMyAdmin 窗口")



# 第5章 系统实现
进入到这个环节，也就可以及时检查出前面设计的需求是否可靠了。一个设计良好的方案在运用于系统实现中，是会帮助系统编制人员节省时间，并提升开发效率的。所以在系统的编程阶段，也就是系统实现阶段，对于一些不合理的设计需求，也是可以及时发现。因为设计的方案是完全指导系统的编码过程的。
## 5.1 管理员功能实现
### 5.1.1 商品信息管理
管理员进入指定功能操作区之后可以管理商品信息。其页面见下图。管理员增删改查商品信息。对商品进行上架和下架操作，可以为商品添加库存或减少库存等操作。

![](/images/0200ssm/ssm291/blog.016.png)

图5.1 商品信息管理页面

管理员可以查询商品的信息列表，实现代码如下所示：

/\*\*

` `\* 后端列表

` `\*/

@RequestMapping("/page")

public R page(@RequestParam Map<String, Object> params,ShangpinxinxiEntity shangpinxinxi, 

`	`HttpServletRequest request){

`    `EntityWrapper<ShangpinxinxiEntity> ew = new EntityWrapper<ShangpinxinxiEntity>();

`	`PageUtils page = shangpinxinxiService.queryPage(params, MPUtil.sort(MPUtil.between(MPUtil.likeOrEq(ew, shangpinxinxi), params), params));

`    `return R.ok().put("data", page);

}

前端页面向后台控制器发送了一个查询商品信息的ajax的GET请求,请求的名为/shangpinxinxi/page，并传输过来要查询的条件，封装到后台中定义的params中，params中的key就是字段名，value就是条件，之后调用shangpinxinxiService类中的queryPage方法，查询出来数据返回给前端。
### 5.1.2 用户管理
管理员进入指定功能操作区之后可以管理用户信息。其页面见下图。管理员查看用户账户余额，可以修改用户的联系电话，电子邮箱等信息，在本页面也能删除指定的用户资料。

![](/images/0200ssm/ssm291/blog.017.png)

图5.2 用户管理页面

新增用户：

` `/\*\*

`     `\* 后端保存

`     `\*/

`    `@RequestMapping("/save")

`    `public R save(@RequestBody YonghuEntity yonghu, HttpServletRequest request){

`    	`yonghu.setId(new Date().getTime()+new Double(Math.floor(Math.random()\*1000)).longValue());

`    	`//ValidatorUtils.validateEntity(yonghu);

`    	`YonghuEntity user = yonghuService.selectOne(new EntityWrapper<YonghuEntity>().eq("yonghuzhanghao", yonghu.getYonghuzhanghao()));

`		`if(user!=null) {

`			`return R.error("用户已存在");

`		`}

`		`yonghu.setId(new Date().getTime());

`        `yonghuService.insert(yonghu);

`        `return R.ok();

`    `}

前端页面向后台控制器发送了一个新增用户的POST请求,请求的名为/yonghu/save，把用户信息封装在后台定义的yonghu对象中，由于id是唯一的，不允许重复，所以取当前时间的毫秒数加上随机出来的整数作为id，保证唯一性，通过mybatis的selectOne方法，查询账户是否存在，存在就返回错误信息，用户已存在，不存在就调用mybatis-plus的insert方法，把用户数据新增到数据库中。

### 5.1.3 新闻资讯
管理员进入指定功能操作区之后可以管理新闻资讯信息。其页面见下图。管理员负责新闻资讯的发布，在本页面可以对新闻资讯的内容或图片等信息进行修改，或者是删除指定的新闻资讯。

![](/images/0200ssm/ssm291/blog.018.png)

图5.3 新闻资讯页面

修改新闻资讯：

` `/\*\*

`     `\* 修改

`     `\*/

`    `@RequestMapping("/update")

`    `public R update(@RequestBody NewsEntity news, HttpServletRequest request){

`        `//ValidatorUtils.validateEntity(news);

`        `newsService.updateById(news);//全部更新

`        `return R.ok();

`    `}

前端页面向后台控制器发送了一个修改新闻的POST请求,请求的名为/new/update，把新闻资讯信息封装在后台定义的news对象中，通过mybatis的update

ById方法通过id把新闻资讯数据更改，更新完成后返回更新完成给前端，进行页面展示和跳转。

### 5.1.4 积分记录
管理员进入指定功能操作区之后管理积分记录。其页面见下图。管理员查询积分记录，查看用户的积分记录明细，包括添加的积分与使用的积分信息。

![](/images/0200ssm/ssm291/blog.019.png)

图5.4 积分记录页面

管理员可以查询积分记录的信息列表，实现代码如下所示：

/\*\*

`     `\* 后端列表

`     `\*/

`    `@RequestMapping("/page")

`    `public R page(@RequestParam Map<String, Object> params,JifenjiluEntity jifenjilu, HttpServletRequest request){

`        `if(!request.getSession().getAttribute("role").toString().equals("管理员")) {

`            `params.put("yonghuId",request.getSession().getAttribute("userId"));

`        `}

`        `PageUtils page= jifenjiluService.queryPage1(params);

`        `return R.ok().put("data", page);

`    `}

前端页面向后台控制器发送了一个查询积分记录信息的ajax的GET请求,请求的名为/jifenjilu/page，并传输过来要查询的条件，封装到后台中定义的params中，params中的key就是字段名，value就是条件，里面有条数，第几页，排序字段，用户姓名，联系电话等查询条件，之后调用jifenjiluService类中的queryPage方法，查询出来数据返回给前端进行展示。
### 5.1.5 商品评价管理
管理员进入指定功能操作区之后可以管理商品评价信息，其页面见下图。管理员根据评论的内容查询用户对商品的评价，在本页面，管理员可以删除指定的商品评价信息。

![](/images/0200ssm/ssm291/blog.020.png)

图5.5 商品评价管理页面

商品评价回复功能：

`  `/\*\*

`     `\* 修改

`     `\*/

`    `@RequestMapping("/update")

`    `public R update(@RequestBody DiscussshangpinxinxiEntity discussshangpinxinxi, HttpServletRequest request){

`        `//ValidatorUtils.validateEntity(discussshangpinxinxi);

`        `discussshangpinxinxiService.updateById(discussshangpinxinxi);//全部更新

`        `return R.ok();

`    `}

前端页面向后台控制器发送了一个商品评价的POST请求,请求的名为/discussshangpinxinxi/update，把回复信息封装在后台定义的discussshangpinxinxi对象中，通过mybatis的updateById方法通过id把回复信息修改进数据库中，更新完成后返回更新完成给前端，进行页面展示和跳转。

### 5.1.6 已支付订单
管理员进入指定功能操作区之后可以管理已支付订单。其页面见下图。管理员查看订单的收货地址信息，然后针对各个订单进行发货。

![](/images/0200ssm/ssm291/blog.021.png)

图5.6 已支付订单页面

查询已支付订单的信息列表，实现代码如下所示：

/\*\*

`     `\* 后端列表

`     `\*/

`    `@RequestMapping("/page")

`    `public R page(@RequestParam Map<String, Object> params,OrdersEntity orders, HttpServletRequest request){

`    	`if(!request.getSession().getAttribute("role").toString().equals("管理员")) {

`    		`orders.setUserid((Long)request.getSession().getAttribute("userId"));

`    	`}

`        `PageUtils page=null;

`        `if("已完成".equals(orders.getStatus())){

`            `params.put("status",orders.getStatus());

//            params.put("userid",orders.getStatus());

`            `page= ordersService.queryPage1(params);

`        `}else{

`            `EntityWrapper<OrdersEntity> ew = new EntityWrapper<OrdersEntity>();

`            `page = ordersService.queryPage(params, MPUtil.sort(MPUtil.between(MPUtil.likeOrEq(ew, orders), params), params));

`            `request.setAttribute("data", page);

`        `}

`        `return R.ok().put("data", page);

`    `}

前端页面向后台控制器发送了一个查询已支付订单信息的ajax的GET请求,请求的名为/orders/page，并传输过来要查询的条件，封装到后台中定义的params中，params中的key就是字段名，value就是条件，里面有条数，第几页，排序字段等查询条件，如果是管理员，就查询全部的，如果是用户的话，就把用户的id塞入查询条件中，只能查询自己的，如果是已完成订单的话，要级联查询售后表，所以单独提出来查询ordersService的queryPage1方法，如果不是已完成订单的话，调用ordersService类中的queryPage方法，查询出来数据返回给前端进行展示。

## 5.2 用户功能实现
### 5.2.1 商品信息
用户进入指定功能操作区之后可以查看商品信息。其页面见下图。用户在当前页面除了查看商品详情之外，也能收藏商品，对商品进行评价，或把商品添加进入购物车，也能选择直接购买商品。

![](/images/0200ssm/ssm291/blog.022.png)

图5.7 商品信息页面

商品查询：

` `/\*\*

`     `\* 前端详情

`     `\*/

`	`@IgnoreAuth

`    `@RequestMapping("/detail/{id}")

`    `public R detail(@PathVariable("id") String id){

`        `ShangpinxinxiEntity shangpinxinxi = shangpinxinxiService.selectById(id);

`		`shangpinxinxi.setClicknum(shangpinxinxi.getClicknum()+1);

`		`shangpinxinxi.setClicktime(new Date());

`		`shangpinxinxiService.updateById(shangpinxinxi);

`        `return R.ok().put("data", shangpinxinxi);

}

前端页面向后台控制器发送了一个查询商品的get请求,请求的名为/shangpinxinxi/detail/{id}，把商品的id传入后台的id对象中，然后通过mybatis-plus的selectById方法，通过id把数据查询出来，设置点击次数加1，最近点击时间设置为当前时间，更新点击次数和最近点击时间两个字段的数据更新数据库中，然后把商品信息返回给前台，进行展示。
### 5.2.2 购物车
用户进入指定功能操作区之后可以管理购物车信息。其页面见下图。购物车专门用来保存用户打算购买的商品的信息，用户在本页面除了修改商品购买数量，删除购买商品之外，也能选择购买购物车保存的商品。

![](/images/0200ssm/ssm291/blog.023.png)

图5.8 购物车页面

用户可以查询到当前用户的购物车中的商品信息，实现代码如下所示：

/\*\*

`     `\* 前端列表

`     `\*/

`    `@RequestMapping("/list")

`    `public R list(@RequestParam Map<String, Object> params,CartEntity cart, HttpServletRequest request){

`        `EntityWrapper<CartEntity> ew = new EntityWrapper<CartEntity>();

`    	`PageUtils page = cartService.queryPage(params, MPUtil.sort(MPUtil.between(MPUtil.likeOrEq(ew, cart), params), params));

`		`request.setAttribute("data", page);

`        `return R.ok().put("data", page);

`    `}

前端页面向后台控制器发送了一个查询购物车中商品的ajax的GET请求,请求的名为/cart/list，并传输过来要查询的条件，封装到后台中定义的params中，params中的key就是字段名，value就是条件，里面有条数，第几页，排序字段，当前用户的id等查询条件，之后调用cartService类中的queryPage方法，查询出当前用户的购物车的所有商品，然后返回给前台，进行页面展示。

### 5.2.3 在线下单
用户进入指定功能操作区之后可以对需要购买的商品提交订单。其页面见下图。用户检查购买的商品信息，对收货地址进行选择，然后点击支付按钮即可支付订单。

![](/images/0200ssm/ssm291/blog.024.png)

图5.9 在线下单页面

用户可以查询到当前用户的购物车中的商品信息，实现代码如下所示：

payClick() {

`	`console.log('payClick')

`	`var index = layui.jquery('input[name=address]:checked').val();

`	`console.log(index);

`	`if (!index) {

`		`layui.layer.msg('请选择收货地址', {

`			`time: 2000,

`			`icon: 5

`		`});

`		`return

`	`}

`	`// 生成订单

`	`for (let item of this.dataList) {

`		`// 获取商品详情信息

`		`layui.http.request(`${item.tablename}/info/${item.goodid}`, 'get', {}, (res) => {

`			`// 订单编号

`			`debugger

`			`var orderId = genTradeNo();

`			`let data = res.data;

`			`// 减少库存

`			`data.shuliang = data.shuliang - item.buynumber;

`			`// 更新库存信息

`			`layui.http.requestJson(`${item.tablename}/update`, 'post', data, (res) => {

`				`// 添加订单信息

`				`let order = {

`					`orderid: orderId,

`					`tablename: item.tablename,

`					`userid: this.user.id,

`					`goodid: item.goodid,

`					`goodname: item.goodname,

`					`picture: item.picture,

`					`buynumber: item.buynumber,

`					`discountprice: item.discountprice,

`					`price: item.price,

`					`total: item.price \* item.buynumber,

`					`discounttotal: item.discountprice \* item.buynumber,

`					`type: 1,

`					`address: this.addressList[index].address,

`					`status: '未支付'

`				`}

`				`layui.http.requestJson(`orders/add`, 'post', order, (res) => {

`					`// 减少余额，更新订单状态

`					`// 判断余额是否充足

`					`if (this.user.money < this.totalPrice) {

`						`layui.layer.msg('余额不足，请先充值', {

`							`time: 2000,

`							`icon: 5

`						`});

`						`return

`					`}

`					`// 如果该商品存在积分

`					`var date = new Date();

`					`var dateformat = date.getFullYear() + '-' + (date.getMonth() + 1) + '-' + date.getDate() + ' ' + date.getHours() + ':' + date.getMinutes() + ':' + date.getSeconds();

`					`var s =Number(this.shiyongJifen);

`					`if(s !=0){// 使用积分不为0

`						`let jifenjilu = {

`							`yonghuId: this.user.id,

`							`shangpinxinxiId:item.goodid,

`							`jifenjiluTypes:"使用",

`							`buynumber:this.shiyongJifen,

`							`insertTime:dateformat

`						`}

`						`layui.http.requestJson(`jifenjilu/add`, 'post', jifenjilu, (res) => {});

`					`}

`					`var a = Number(this.user.jifen)-s;

`					`if (data.jifen) {

`						`debugger

`						`// this.user.jifen = Number(this.user.jifen) + Number(data.jifen \* item.buynumber);

`						`//用户积分-这次使用的积分+这次订单的积分

`						`a+=Number(data.jifen \* item.buynumber);

`						`let jifenjilu = {

`							`yonghuId: this.user.id,

`							`shangpinxinxiId:item.goodid,

`							`jifenjiluTypes:"添加",

`							`buynumber:Number(data.jifen \* item.buynumber),

`							`insertTime:dateformat

`						`}

`						`layui.http.requestJson(`jifenjilu/add`, 'post', jifenjilu, (res) => {});

`					`}

`					`this.user.jifen=a;

`					`this.user.money = this.user.money - this.totalPrice;

`					`// 更新用户余额

`					`layui.http.requestJson(`${localStorage.getItem("userTable")}/update`, 'post', this.user, (res) => {

`						`order.status = '已支付'

`						`layui.http.request(`orders/list`, 'get', {

`							`orderid: orderId,

`							`page: 1,

`							`limit: 1,

`						`}, (res) => {

`							`order.id = res.data.list[0].id;

`							`layui.http.requestJson(`orders/update`, 'post', order, (res) => {

`								`// 删除购物车数据(如果是购物车下单)

`								`if (item.id) {

`									`layui.http.requestJson(`cart/delete`, 'post', [item.id], (res) => {});

`								`}

`								`layui.layer.msg('购买成功', {

`									`time: 2000,

`									`icon: 6

`								`}, function() {

`									`window.location.href='../order/list.jsp'

`								`});

`							`});

`						`});

`					`});

`				`})

`			`})

`		`});

`	`}

},

点击支付按钮，会调用payClick方法，进行支付操作，先获取收货地址是否被选择，选择了进入下一步，没选择就提示，请选择收货地址，然后获取当前所有商品的信息，把库存减去，添加订单信息，减少余额（如果余额够，就减去余额，如果余额不够就把该订单设置为未支付），如果有积分，就把当前商品的积分加给用户，把订单给新增到数据库中，把余额给更改到数据库中，执行完成后把购物车中的信息给清空。

### 5.2.4 已支付订单
用户进入指定功能操作区之后可以查看已支付订单。其页面见下图。用户在已支付订单模块查看订单明细，核对订单的收货地址以及购买的商品信息，用户在本页面可以点击退款按钮进行订单退款。

![](/images/0200ssm/ssm291/blog.025.png)

图5.10 已支付订单页面

查询已支付订单的信息列表，实现代码如下所示：

/\*\*

`     `\* 后端列表

`     `\*/

`    `@RequestMapping("/page")

`    `public R page(@RequestParam Map<String, Object> params,OrdersEntity orders, HttpServletRequest request){

`    	`if(!request.getSession().getAttribute("role").toString().equals("管理员")) {

`    		`orders.setUserid((Long)request.getSession().getAttribute("userId"));

`    	`}

`        `PageUtils page=null;

`        `if("已完成".equals(orders.getStatus())){

`            `params.put("status",orders.getStatus());

//            params.put("userid",orders.getStatus());

`            `page= ordersService.queryPage1(params);

`        `}else{

`            `EntityWrapper<OrdersEntity> ew = new EntityWrapper<OrdersEntity>();

`            `page = ordersService.queryPage(params, MPUtil.sort(MPUtil.between(MPUtil.likeOrEq(ew, orders), params), params));

`            `request.setAttribute("data", page);

`        `}

`        `return R.ok().put("data", page);

`    `}

前端页面向后台控制器发送了一个查询已支付订单信息的ajax的GET请求,请求的名为/orders/page，并传输过来要查询的条件，封装到后台中定义的params中，params中的key就是字段名，value就是条件，里面有条数，第几页，排序字段等查询条件，如果是管理员，就查询全部的，如果是用户的话，就把用户的id塞入查询条件中，只能查询自己的，如果是已完成订单的话，要级联查询售后表，所以单独提出来查询ordersService的queryPage1方法，如果不是已完成订单的话，调用ordersService类中的queryPage方法，查询出来数据返回给前端进行展示。

### 5.2.5 我的地址
用户进入指定功能操作区之后可以管理收货地址。其页面见下图。用户在当前页面新增收货地址，对已存在的收货地址进行信息更改，也能删除不需要的收货地址信息。

![](/images/0200ssm/ssm291/blog.026.png)

图5.11 我的地址页面

查询我的地址列表，实现代码如下所示：

/\*\*

`     `\* 后端列表

`     `\*/

`    `@RequestMapping("/page")

`    `public R page(@RequestParam Map<String, Object> params,AddressEntity address, HttpServletRequest request){

`    	`if(!request.getSession().getAttribute("role").toString().equals("管理员")) {

`    		`address.setUserid((Long)request.getSession().getAttribute("userId"));

`    	`}

`        `EntityWrapper<AddressEntity> ew = new EntityWrapper<AddressEntity>();

`    	`PageUtils page = addressService.queryPage(params, MPUtil.sort(MPUtil.between(MPUtil.likeOrEq(ew, address), params), params));

`		`request.setAttribute("data", page);

`        `return R.ok().put("data", page);

`    `}

前端页面向后台控制器发送了一个查询我的地址列表信息的ajax的GET请求,请求的名为/address/page，并传输过来要查询的条件，封装到后台中定义的params中，params中的key就是字段名，value就是条件，里面有条数，第几页，排序字段，当前用户的id等查询条件，通过addressService的queryPage方法，从service中把数据查询出来，然后返回给前端，进行展示。
### 5.2.6 新闻资讯
用户进入指定功能操作区之后可以查看新闻资讯信息。其页面见下图。用户查看新闻资讯的标题和图片，对感兴趣的新闻资讯进行其内容的详细查看。

![](/images/0200ssm/ssm291/blog.027.png)

图5.12 新闻资讯页面

查询新闻咨询列表，实现代码如下所示：

/\*\*

`     `\* 前端列表

`     `\*/

`	`@IgnoreAuth

`    `@RequestMapping("/list")

`    `public R list(@RequestParam Map<String, Object> params,NewsEntity news, HttpServletRequest request){

`        `EntityWrapper<NewsEntity> ew = new EntityWrapper<NewsEntity>();

`    	`PageUtils page = newsService.queryPage(params, MPUtil.sort(MPUtil.between(MPUtil.likeOrEq(ew, news), params), params));

`		`request.setAttribute("data", page);

`        `return R.ok().put("data", page);

`    `}

前端页面向后台控制器发送了一个查询新闻咨询信息的ajax的GET请求,请求的名为/news/page，并传输过来要查询的条件，封装到后台中定义的params中，params中的key就是字段名，value就是条件，里面有条数，第几页，排序字段等查询条件，通过newsService的queryPage方法，从service中把数据查询出来，然后返回给前端，进行展示。
# 










