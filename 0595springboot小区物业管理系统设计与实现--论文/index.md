# 0595springboot小区物业管理系统设计与实现--论文


# [0595springboot小区物业管理系统设计与实现--论文](https://github.com/GraduationProject-springboot/0595springboot)

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

# [项目清单](https://chenqi1990.site) 包安装运行

### [github 项目仓库](https://github.com/GraduationProject-springboot/allSpringbootProjects) 开源仅有后端代码

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1eMbYemE1U?p=91)


# 研究背景
小区物业管理系统主要通过计算机网络，对小区物业管理系统所需的信息进行统一管理，方便用户随时随地进行增添、修改、查询、删除各类信息。本系统极大的促进了系统与数据库管理系统软件之间的配合，满足了绝大部分用户的需求，给用户带来了很大的便利。以现在计算机的技术的应用，使计算机成为人们使用现代发达技术的桥梁。计算机可以有效的解决信息，十分方便的获取信息，从而提高工作的效率。
## 1.2　课题研究目的
全球经济在快速的发展，中国更是进步飞速，这使得国内的互联网技术进入了发展的高峰时期，这让中外资本不断转向互联网这个大市场。在这个信息高度发达的现在，利用网络进行信息管理改革已经成为了人们追捧的一种趋势。“小区物业管理系统”是运用java语言和SpringBoot框架，以Mysql数据库为基础而发出来的。为保证我国经济的持续性发展，必须要让互联网信息时代在我国日益壮大，蓬勃发展。伴随着信息社会的飞速发展，小区物业管理系统所面临的问题也一个接一个的出现，所以现在最该解决的问题就是信息的实时查询和访问需求的问题，以及如何利用快捷便利的方式让访问者在广大信息系统中进行查询、分享、储存和管理。这对我们的现实生活中具有非常重要的意义，所以小区物业管理系统诞生了。
## 1.3　课题的研究意义
现在还有许多人用纸质工具存储并管理信息，网络仅仅起到一般的辅助性作用。以我对人们常用软件的了解程度，大家仍然把传统的Office软件当成主要工具，小区物业管理系统相比Office软件来说会更全面更专业。本系统通过标签分类等方式，使管理人员对各项功能信息实现高效的管理，可以极大的提高管理人员的工作效率。
## 1.4　研究现状
在国外线上管理发展较早。相对应的软件的开发设计和保护也有所增加[4]。由于长時间的技术积累，产品研发工作更是持续推动，最终获得了较大的发展。如今，向着智能化，数字化和信息化的方位快速发展。各行各业都使用了相似的规章制度，推动发展，获得了较好的经济效益[5]。

在国内，因起步较晚，目前的管理还不够完善，发展不平衡，对小区物业的管理过程中应用电子计算机和网上的领域以及外部状况信息存有很大差别。技术性简易地取代了过去的形式或方式，但根据更科学的方式再次设计方案管理的这一环节中，大家必须舍弃传统的管理方式，尽早更改管理方法，变化管理理念合理操纵，使系统更细腻，控制成本、提升管理效益。

计算机作为信息科学的媒介和关键，它的出现和发展对人类社会的繁荣起着至关重要的作用。无论是政府机构还是公共机构，都会根据工作内容选择一套优秀的通信技术和专业的办公设备，利用这些技术和设备快速收集、解决和存储信息，使管理工作变得方便快捷，达到科学合理的管理目标。

总之，小区物业管理系统的发展呈不断上升的发展趋势，现在传统的手工制作和半手工管理的方法进入到信息化管理的转变过程中，必须使用和融合新的信息技术来完成传统的系统设计方法，才能保证系统的效果和质量。	


# 2  系统开发技术
小区物业管理系统采用B/S(Browser/Server)架构和MVC模型进行设计开发。在B/S架构下，用户在浏览器端进行使用，主要工作通过服务器端进行实现，用户通过网站进行访问大大节约了成本。本系统使用Java等语言同时运用了Springboot框架进行开发，使用MySQL进行数据存储。
## 2.1 Java技术
Java是一种面向对象的静态式编程语言。Java编程语言具有多线程和对象定向的特点。其特点是根据方案的属性将方案分为几个不同的模块，这些模块是封闭的和多样化的，在申请过程中具有很强的独立性。Java语言在计算机软件开发过程中的运用可以达到交互操作的目的，通过各种形式的交换，可以有效地处理所需的数据，从而确保计算机软件开发的可控性和可见性。开发Java语言时，保留了网络接口，Java保留的缺省网络接口可以与web应用程序编程所依赖的类别库相匹配。为了使Java开发的应用程序更加稳定和强健，Java会自动收集程序中的垃圾，并处理程序中存在的异常。Java语言是日常开发过程中广泛使用的通用基本语言。其中Java语言课程库、句子、语法规则和关键字经常用于计算机软件的开发和编程。

面向对象编程是Java语言最显着的特点。它具有原始接口和补充接口以及继承，不仅可以实现相同类型的单个继承，而且还支持接口之间的多个继承，从而实现类、接口和接口之间以及类和接口之间的有效通信。Java的面向对象特性主要包括三个方面:继承、多态性和封装。封装是Java的核心，可以封装所有数据操作。多态性是指由面向对象行为派生的相关行为。继承作为特殊编程模式有两种类型:父类和子类，这两种类型的属性具有相同的功能和特性。对于父类的属性特性，子类可以实现继承和优化。
## 2.2 Springboot框架
Spring框架是Java平台上的一种开源应用框架，提供具有控制反转特性的容器。尽管Spring框架自身对编程模型没有限制，但其在Java应用中的频繁使用让它备受青睐，以至于后来让它作为EJB（EnterpriseJavaBeans）模型的补充，甚至是替补。Spring框架为开发提供了一系列的解决方案，比如利用控制反转的核心特性，并通过依赖注入实现控制反转来实现管理对象生命周期容器化，利用面向切面编程进行声明式的事务管理，整合多种持久化技术管理数据访问，提供大量优秀的Web框架方便开发等等。Spring框架具有控制反转（IOC）特性，IOC旨在方便项目维护和测试，它提供了一种通过Java的反射机制对Java对象进行统一的配置和管理的方法。Spring框架利用容器管理对象的生命周期，容器可以通过扫描XML文件或类上特定Java注解来配置对象，开发者可以通过依赖查找或依赖注入来获得对象。Spring框架具有面向切面编程（AOP）框架，SpringAOP框架基于代理模式，同时运行时可配置；AOP框架主要针对模块之间的交叉关注点进行模块化。Spring框架的AOP框架仅提供基本的AOP特性，虽无法与AspectJ框架相比，但通过与AspectJ的集成，也可以满足基本需求。
## 2.3 MySQL数据库
MySql做为瑞典公司MySql AB开发的中小型开源数据库智能管理系统，具备配备低、低成本、运作速度更快的优势。与此同时，因为社区版的开源系统性，变成了许多网址减少开发成本费的最佳选择。被甲骨文回收后，MySQL也发布了商业版。另外Mysql具有以下特性：

（1）使用C和C++编写，并使用了多种编译器进行测试，保证源代码的可移植性。

（2）为C、C++、Eiffel、Java、Perl、PHP、Python、Ruby和Tcl等多种编程语言提供了API。

（3）采用多线程并行的方法提高了CPU的利用率。

（4）改善算法，有效地提高查询速度。
## 2.4 B/S结构
B/S结构（Browser/Server，浏览器/服务器模式），是WEB兴起后的一种网络结构模式，WEB浏览器是客户端最主要的应用软件。这种模式统一了客户端，将系统功能实现的核心部分集中到服务器上，简化了系统的开发、维护和使用。客户机上只要安装一个浏览器，如Chrome、Safari、Microsoft Edge、Netscape Navigator或Internet Explorer，服务器安装SQL Server、Oracle、MYSQL等数据库。浏览器通过Web Server同数据库进行数据交互。
## 2.5 Tomcat服务器
Tomcat服务器属于轻量级应用服务器，在访问用户数量不是很大的中小型应用中经常被使用。Tomcat服务器主要由三个核心组件Web容器、servlet容器、JSP容器组成。其中，Web容器主要用于完成Web服务器的功能，servlet容器主要用于处理servlet代码，JSP容器主要用于将JSP动态网页翻译成servlet代码。Tomcat作为Web服务器和APP容器，其核心功能主要包括负责接受和反馈外部请求的连接器Connector和负责处理请求的容器Container。二者相辅相成，共同构成了基本的Web服务。Tomcat支持管理多个服务。Tomcat因其技术先进、性能也较为稳定，最重要的是因为其价格免费，故而收到了大量Java爱好者的偏爱，成为比较流行的Web应用服务器。


# 3  系统需求分析
需求分析在系统开发中有着十分重要的作用。软件项目凭借软件工程的思想和步骤可以大大的提高开发效率，缩短软件开发周期，保证了软件项目的质量。需求分析作为软件工程方法中的一步是至关重要的。软件需求工程是一门分析并记录软件需求的学科。需求分析简单的来说就是用户需要什么，系统需要什么，对此进行问题的列举，等级的排列，需要缜密的思分析和大量的调研。
## 2.1 可行性分析
根据小区物业管理系统的功能，通过对经济可行性、技术可行性和法律可行性分析进行全面的分析，提供准确的可行性依据。以下是本系统的可行性分析:

1) 经济可行性

就是分析在现有经济情况下能否完成本小区物业管理系统的开发。下面对本系统开发、运行、维护的相关费用评估，以及投入到实际运用中完成小区物业管理可能费用进行估算。网络资源丰富，本小区物业管理系统只需使用任选一开源服务器即可，此方面无需投入费用。开发阶段，由于本小区物业管理系统不属于大型系统，常规的电脑就可完成开发，不用购置相关硬件设备。软件方面，本小区物业管理系统只需使用网上免费下载的软件即可完成开发，这些软件在使用时简单易懂，无需培训，因此在开发方面也无需投入费用。由于本小区物业管理系统不属于大型系统，运行时候电费可以忽略不记。小区物业管理系统作为自己毕设，由本人开发即可完成，无需人力费用。综上，整个系统开发花费很少，所以本小区物业管理系统在经济上可行。

1) 技术可行性

本系统的开发使用java作为系统开发的开发语言，开发工具选择 Eclipse，而 B/S架构决定了本系统的兼容性和多用户可操作性，此外选择MySql作为数据库不仅提高了数据安全性更保障了数据的可操作性。

1) 法律可行性分析

法律可行性分析，即分析本校小区物业管理系统是否与各类法律相悖。本校小区物业管理系统使用市面开源免费软件开发，且作为个人毕设，无商用，均为本人自主开发，并且页面设计合理，发布的信息要求符合常规。整个系统无抵触法律法规的问题。因此在法律上，本校小区物业管理系统可行。
## 3.2 功能需求分析 
小区物业管理系统综合网络空间开发设计要求。目的是将小区物业通过网络平台将传统管理方式转换为在网上管理，完成小区物业的方便快捷、安全性高障，目标明确。小区物业管理系统可以将功能划分为管理员的使用功能和用户使用的功能。

（1）管理员的功能是最高的，可以对系统所在功能进行查看，修改和删除，包括业主功能。管理员用例如下：

![](/images/0500stringboot/0595springboot/blog.001.png)

图3-1管理员用例图

（2）业主关键功能包含个人中心、业主车辆管理、业主宠物管理、购买车位管理、缴费通知管理等进行详细操作。业主用例如下：

![](/images/0500stringboot/0595springboot/blog.002.png)

图3-2 业主用例图

## 3.3 系统流程分析
### 3.3.1系统开发流程图：
![](/images/0500stringboot/0595springboot/blog.003.png)

图3-3 系统开发流程图
### 3.3.2管理员模块总体流程图：
![](/images/0500stringboot/0595springboot/blog.004.png)

图3-4 管理员模块总体流程图
### 3.3.3小区物业管理流程图：

![](/images/0500stringboot/0595springboot/blog.005.png)

图3-5 小区物业管理流程图




# 4  系统设计
## 4.1 功能模块设计
小区物业管理系统按照权限的类型进行划分，分为管理员和业主共两个模块。系统实现个人中心、业主管理、小区信息管理、资产信息管理、业主车辆管理、业主宠物管理、车位信息管理、购买车位管理、缴费通知管理、留言板管理、系统管理等功能进行操作，增强了使用者的操作体验。管理员模块主要针对整个系统的管理进行设计，提高了管理的效率和标准。系统的总体模块设计如下图所示:

![](/images/0500stringboot/0595springboot/blog.006.png)

图4-1 系统总体模块设计
## 4.2 系统数据库设计
### 4.2.1 数据库系统
本系统采用MySQL来进行数据库的管理。MySQL数据库具有体积小、速度快、成本低等优点。具备同时处理数千万条记录，实现大型数据库的高并发读写和高效读写需求[9]。
### 4.2.2 数据库概念设计
概念模型用于对信息世界建模，并与指定的数据库管理系统分离。它有助于将真实世界的事物抽象为适合于数据库管理系统的数据库模型。人们倾向于将现实世界抽象为信息世界，再把信息世界变成机器世界。也就是说，将现实世界的目标抽象成独立于专用计算机软件和专用数据库管理系统的信息结构的数据模型，然后将物理模型转化为适合电子计算机的数据库管理系统。事实上，数据模型是从真实世界到机器世界的中间层。

信息世界的基本要素包括实体和关联。现实存在且彼此可区别的事物称为实体。实体可以是实际的人、事或物，还可以是抽象化的概念或联络。以下是对部分主要的关键实体如下：

业主实体属性如图4-2所示。

![](/images/0500stringboot/0595springboot/blog.007.png)

图4-2业主实体属性图

小区信息实体属性如图4-3所示。

![](/images/0500stringboot/0595springboot/blog.008.png)

图4-3小区信息实体属性图

车位信息实体属性如图4-4所示。

![](/images/0500stringboot/0595springboot/blog.009.png)图4-4车位信息实体属性图

资产信息实体属性如图4-5所示。

![](/images/0500stringboot/0595springboot/blog.010.png)图4-5资产信息实体属性图

购买车位实体属性如图4-6所示。

![](/images/0500stringboot/0595springboot/blog.011.png)

图4-6购买车位实体属性图
### 4.2.3 数据表设计
本设计根据数据表管理系统的具体流程进行管理，方便用户对数据的添加、删除、修改和查询等操作。
### 4.2.4 数据表的建立
系统采用Navicat Premium对数据库进行操作，数据库管理操作简单，数据处理能力强。数据表建立如下:

表4-1：缴费通知

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|zhanghao|varchar|200|账号|||
|xingming|varchar|200|姓名|||
|loufanghao|varchar|200|楼房号|||
|xiaoqumingcheng|varchar|200|小区名称|||
|shoufeixiangmu|varchar|200|收费项目|||
|feiyong|float||费用|||
|feiyongxiangqing|longtext|4294967295|费用详情|||
|tongzhishijian|datetime||通知时间|||
|wuyegonghao|varchar|200|物业工号|||
|wuyexingming|varchar|200|物业姓名|||
|ispay|varchar|200|是否支付||未支付|

表4-2：购买车位

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|dingdanbianhao|varchar|200|订单编号|||
|cheweibianhao|varchar|200|车位编号|||
|cheweimingcheng|varchar|200|车位名称|||
|jiage|float||价格|||
|goumairiqi|date||购买日期|||
|zhanghao|varchar|200|账号|||
|xingming|varchar|200|姓名|||
|shouji|varchar|200|手机|||
|loufanghao|varchar|200|楼房号|||
|xiaoqumingcheng|varchar|200|小区名称|||
|sfsh|varchar|200|是否审核||待审核|
|shhf|longtext|4294967295|审核回复|||
|ispay|varchar|200|是否支付||未支付|

表4-3：业主

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|zhanghao|varchar|200|账号|||
|mima|varchar|200|密码|||
|xingming|varchar|200|姓名|||
|nianling|int||年龄|||
|xingbie|varchar|200|性别|||
|shouji|varchar|200|手机|||
|touxiang|longtext|4294967295|头像|||
|loudong|varchar|200|楼栋|||
|loufanghao|varchar|200|楼房号|||
|xiaoqumingcheng|varchar|200|小区名称|||

表4-4：配置文件

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|name|varchar|100|配置参数名称|||
|value|varchar|100|配置参数值|||

表4-5：小区信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|xiaoqumingcheng|varchar|200|小区名称|||
|xiaoqufengmian|longtext|4294967295|小区封面|||
|xiaoqumianji|varchar|200|小区面积|||
|xiaoquweizhi|varchar|200|小区位置|||
|xiaoqudongshu|varchar|200|小区栋数|||
|fuzeren|varchar|200|负责人|||
|lianxidianhua|varchar|200|联系电话|||
|chengliriqi|date||成立日期|||
|xiaoquxiangqing|longtext|4294967295|小区详情|||
|clicktime|datetime||最近点击时间|||
|clicknum|int||点击次数||0|

表4-6：车位信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|cheweibianhao|varchar|200|车位编号|||
|cheweimingcheng|varchar|200|车位名称|||
|tupian|longtext|4294967295|图片|||
|cheweiweizhi|varchar|200|车位位置|||
|zhuangtai|varchar|200|状态|||
|jiage|float||价格|||
|mianji|varchar|200|面积|||
|shishishijian|datetime||实时时间|||
|xiangxijieshao|longtext|4294967295|详细介绍|||
|clicktime|datetime||最近点击时间|||
|clicknum|int||点击次数||0|

表4-7：物业人员

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|wuyegonghao|varchar|200|物业工号|||
|mima|varchar|200|密码|||
|wuyexingming|varchar|200|物业姓名|||
|nianling|int||年龄|||
|xingbie|varchar|200|性别|||
|touxiang|longtext|4294967295|头像|||
|lianxidianhua|varchar|200|联系电话|||
|xiaoqumingcheng|varchar|200|小区名称|||

表4-8：用户表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|username|varchar|100|用户名|||
|password|varchar|100|密码|||
|role|varchar|100|角色||管理员|
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|

表4-9：token表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|userid|bigint||用户id|||
|username|varchar|100|用户名|||
|tablename|varchar|100|表名|||
|role|varchar|100|角色|||
|token|varchar|200|密码|||
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|
|expiratedtime|timestamp||过期时间||CURRENT\_TIMESTAMP|

表4-10：资产信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|zichanbianhao|varchar|200|资产编号|||
|zichanmingcheng|varchar|200|资产名称|||
|zichanleixing|varchar|200|资产类型|||
|zichanjiazhi|float||资产价值|||
|zhaopian|longtext|4294967295|照片|||
|xiaoqumingcheng|varchar|200|小区名称|||
|dengjishijian|datetime||登记时间|||
|xiangxijieshao|longtext|4294967295|详细介绍|||
|wuyegonghao|varchar|200|物业工号|||
|wuyexingming|varchar|200|物业姓名|||

表4-11：关于我们

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|title|varchar|200|标题|||
|subtitle|varchar|200|副标题|||
|content|longtext|4294967295|内容|||
|picture1|longtext|4294967295|图片1|||
|picture2|longtext|4294967295|图片2|||
|picture3|longtext|4294967295|图片3|||

表4-12：业主宠物

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|chongwumingcheng|varchar|200|宠物名称|||
|chongwuzhonglei|varchar|200|宠物种类|||
|xingbie|varchar|200|性别|||
|tupian|longtext|4294967295|图片|||
|nianling|varchar|200|年龄|||
|shifoujueyu|varchar|200|是否绝育|||
|faburiqi|date||发布日期|||
|chongwuxiangqing|longtext|4294967295|宠物详情|||
|zhanghao|varchar|200|账号|||
|xingming|varchar|200|姓名|||
|loufanghao|varchar|200|楼房号|||
|xiaoqumingcheng|varchar|200|小区名称|||

表4-13：收藏表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|userid|bigint||用户id|||
|refid|bigint||商品id|||
|tablename|varchar|200|表名|||
|name|varchar|200|名称|||
|picture|longtext|4294967295|图片|||
|type|varchar|200|类型(1:收藏,21:赞,22:踩,31:竞拍参与,41:关注)||1|
|inteltype|varchar|200|推荐类型|||
|remark|varchar|200|备注|||

表4-14：业主车辆

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|chepaihao|varchar|200|车牌号|||
|cheliangpinpai|varchar|200|车辆品牌|||
|cheliangleixing|varchar|200|车辆类型|||
|yanse|varchar|200|颜色|||
|huandangfangshi|varchar|200|换挡方式|||
|zhaopian|longtext|4294967295|照片|||
|zuoweishuliang|int||座位数量|||
|dengjiriqi|date||登记日期|||
|cheliangxiangqing|longtext|4294967295|车辆详情|||
|zhanghao|varchar|200|账号|||
|xingming|varchar|200|姓名|||
|loufanghao|varchar|200|楼房号|||
|xiaoqumingcheng|varchar|200|小区名称|||

表4-15：小区公告

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|title|varchar|200|标题|||
|introduction|longtext|4294967295|简介|||
|picture|longtext|4294967295|图片|||
|content|longtext|4294967295|内容|||

表4-16：留言板

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|userid|bigint||留言人id|||
|username|varchar|200|用户名|||
|avatarurl|longtext|4294967295|头像|||
|content|longtext|4294967295|留言内容|||
|cpicture|longtext|4294967295|留言图片|||
|reply|longtext|4294967295|回复内容|||
|rpicture|longtext|4294967295|回复图片|||



# 5  系统实现
## 5.1系统功能实现
当人们打开系统的网址后，首先看到的就是首页界面。在这里，人们能够看到系统的导航条，通过导航条导航进入各功能展示页面进行操作。系统首页界面如图5-1所示：

![](/images/0500stringboot/0595springboot/blog.012.png)

图5-1 系统首页界面

系统注册：在系统注册页面的输入栏中输入用户注册信息进行注册操作，系统注册页面如图5-2所示：

![](/images/0500stringboot/0595springboot/blog.013.png)

图5-2系统注册页面

小区信息：在小区信息页面的输入栏中输入小区名称、小区位置和负责人进行查询，可以查看到小区详细信息；小区信息页面如图5-3所示：

![](/images/0500stringboot/0595springboot/blog.014.png)

图5-3小区信息详细页面

车位信息：在车位信息页面的输入栏中输入车位名称、车位位置和选择状态进行查询，可以查看到车位详细信息，并进行购买车位或收藏操作，车位信息页面如图5-4所示：

![](/images/0500stringboot/0595springboot/blog.015.png)

图5-4车位信息详细页面

留言板：在留言板页面通过填写留言内容、上传图片并立即提交或重置进行在线留言，还可以对留言信息进行回复操作，留言板页面如图5-5所示：

![](/images/0500stringboot/0595springboot/blog.016.png)

图5-5留言板详细页面

个人中心：在个人中心页面通过填写个人详细信息进行信息更新操作；还可以对我的收藏进行详细操作；如图5-6所示：

![](/images/0500stringboot/0595springboot/blog.017.png)

图5-6个人中心界面

## 5.2后台模块实现
后台用户登录，在登录页面选择需要登录的角色，在正确输入用户名和密码后，进入操作系统进行操作；如图5-7所示。                               

![](/images/0500stringboot/0595springboot/blog.012.png)

图5-7 后台登录界面
### 5.2.1管理员模块实现
管理员进入主页面，主要功能包括对个人中心、业主管理、小区信息管理、资产信息管理、业主车辆管理、业主宠物管理、车位信息管理、购买车位管理、缴费通知管理、留言板管理、系统管理等进行操作。管理员主页面如图5-8所示：

![](/images/0500stringboot/0595springboot/blog.018.png)

图5-8 管理员主界面

管理员点击业主管理。在业主页面输入账号、姓名、楼栋、楼房号和选择小区名称进行查询、新增或删除业主列表，并根据需要对业主详情信息进行详情、修改或删除操作；如图5-9所示：

![](/images/0500stringboot/0595springboot/blog.019.png)

图5-9业主管理界面

管理员点击小区信息管理。在小区信息页面输入小区名称、小区位置和负责人进行查询、新增或删除小区信息列表，并根据需要对小区详情信息进行详情、修改或删除操作；如图5-10所示：

![](/images/0500stringboot/0595springboot/blog.020.png)

图5-10小区信息管理界面

管理员点击资产信息管理。在资产信息页面输入资产名称、资产类型和选择小区名称进行查询、新增、删除或统计报表资产信息列表，并根据需要对资产详情信息进行详情、修改或删除操作；如图5-11所示：

![](/images/0500stringboot/0595springboot/blog.021.png)

图5-11资产信息管理界面

管理员点击业主车辆管理。在业主车辆页面输入车牌号、车辆品牌、姓名和选择换挡方式进行查询或删除业主车辆列表，并根据需要对业主车辆详情信息进行详情、修改或删除操作；如图5-12所示：

![](/images/0500stringboot/0595springboot/blog.022.png)

图5-12业主车辆管理界面

管理员点击业主宠物管理。在业主宠物页面输入宠物名称、宠物种类、姓名和楼房号进行查询或删除业主宠物列表，并根据需要对业主宠物详情信息进行详情、修改或删除操作；如图5-13所示：

![](/images/0500stringboot/0595springboot/blog.023.png)

图5-13业主宠物管理界面

管理员点击车位信息管理。在车位信息页面输入车位名称、车位位置和选择状态进行查询、新增、删除或统计报表车位信息列表，并根据需要对车位详情信息进行详情、修改或删除操作；如图5-14所示：

![](/images/0500stringboot/0595springboot/blog.024.png)

图5-14车位信息管理界面

管理员点击购买车位管理。在购买车位页面输入车位名称、姓名、楼房号、小区名称和选择是否通过进行查询、删除或统计报表购买车位列表，并根据需要对购买车位详情信息进行详情、修改或删除操作；如图5-15所示：

![](/images/0500stringboot/0595springboot/blog.025.png)

图5-15购买车位管理界面

管理员点击缴费通知管理。在缴费通知页面输入姓名、楼房号和选择收费项目进行查询、新增、删除或统计报表缴费通知列表，并根据需要对缴费通知详情信息进行详情、修改或删除操作；如图5-16所示：

![](/images/0500stringboot/0595springboot/blog.026.png)

图5-16缴费通知管理界面

管理员点击留言板管理。在留言板页面输入用户名进行查询或删除留言板列表，并根据需要对留言板详情信息进行详情、修改、回复或删除操作；如图5-17所示：

![](/images/0500stringboot/0595springboot/blog.021.png)

图5-17留言板管理界面

管理员点击系统管理。在小区公告页面输入标题进行查询、新增或删除小区公告列表，并根据需要对小区公告详情信息进行详情、修改或删除操作；还可以对关于我们、系统简介和轮播图管理进行详细操作；如图5-18所示：

![](/images/0500stringboot/0595springboot/blog.027.png)

图5-18系统管理界面

### 5.2.2业主模块实现
业主进入系统可以对个人中心、业主车辆管理、业主宠物管理、购买车位管理、缴费通知管理等功能进行操作。业主主页面如图5-19所示：

![](/images/0500stringboot/0595springboot/blog.028.png)

图5-19 业主主界面

业主点击业主车辆管理。在业主车辆页面输入车牌号、车辆品牌、姓名和选择换挡方式进行查询、新增或删除业主车辆列表，并根据需要对业主车辆详情信息进行详情、修改或删除操作；如图5-20所示：

![](/images/0500stringboot/0595springboot/blog.029.png)

图5-20业主车辆管理界面

业主点击业主宠物管理。在业主宠物页面输入宠物名称、宠物种类、姓名和楼房号进行查询、新增或删除业主宠物列表，并根据需要对业主宠物详情信息进行详情、修改或删除操作；如图5-21所示：

![](/images/0500stringboot/0595springboot/blog.029.png)

图5-21业主宠物管理界面





# 系统测试











