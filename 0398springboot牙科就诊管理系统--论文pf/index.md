# 0398springboot牙科就诊管理系统--论文pf


# [0398springboot牙科就诊管理系统--论文pf](https://github.com/GraduationProject-springboot/0398springboot)

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

# [项目清单](https://chenqi1990.site) 包安装运行

### [github 项目仓库](https://github.com/GraduationProject-springboot/allSpringbootProjects) 开源仅有后端代码

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1T1bpekEK7?p=69)


# 绪论
## 1.1 研究背景
当前社会各行业领域竞争压力非常大，随着当前时代的信息化，科学化发展，让社会各行业领域都争相使用新的信息技术，对行业内的各种相关数据进行科学化，规范化管理。这样的大环境让那些止步不前，不接受信息改革带来的信息技术的企业随时面临被淘汰，被取代的风险。所以当今，各个行业领域，不管是传统的教育行业，餐饮行业，还是旅游行业，医疗行业等领域都将使用新的信息技术进行信息革命，改变传统的纸质化，需要人手工处理工作事务的办公环境。软件信息技术能够覆盖社会各行业领域是时代的发展要求，各种数据以及文件真正实现电子化是信息社会发展的不可逆转的必然趋势。本牙科就诊管理系统也是紧跟科学技术的发展，运用当今一流的软件技术实现软件系统的开发，让牙科就诊管理系统完全通过管理系统实现科学化，规范化，程序化管理。从而帮助信息管理者节省事务处理的时间，降低数据处理的错误率，对于基础数据的管理水平可以起到促进作用，也从一定程度上对随意的业务管理工作进行了避免，同时，牙科就诊管理系统的数据库里面存储的各种动态信息，也为上层管理人员作出重大决策提供了大量的事实依据。总之，牙科就诊管理系统是一款可以真正提升管理者的办公效率的软件系统。
## 1.2 目的和意义
伴随着互联网发展，现今信息类型愈来愈多，信息量也非常大，那也是信息时代的缩影。近些年，电子元器件信息科学合理发展的趋势变的越来越快，系统的开发也日趋成熟。因而，在生活各行各业，只要是有信息管理方法，基本都有电子计算机黑影。可以这么说，很多行业都利用计算机来处理信息。与手工制做对比，一个新的信息解决方法具备安全系数强、能力强、内存空间大、成本费用低等特点。对于销售商品高效信息管理方法，牙科就诊管理系统的挑选可以有效的管理方法，使信息管理方法更科学。与软件工具管理方法信息、散播信息、分享信息，提升总体水平，提升市场竞争力，从数次残酷竞争中获取发展契机。针对特色产品市场销售信息各自为政、差错率高、信息安全系数差、工作强度高、用时费劲等一系列问题，经剖析考虑到，目前可引进牙科就诊管理系统，可以解决以上问题的最佳方式。它不仅可以马上处理信息，还能够降低管理人员的信息智能管理系统，使之系统化、规范性。与此同时，还能够提高效率，节省管理人员信息管理处必须人力资源和资产。因而，牙科就诊管理系统是产品销售信息管理方面不可或缺的专用型管理系统软件，对管理人员尤为重要。
## 1.3 论文结构安排
为了帮助用户更好的了解和理解程序的开发流程与相关内容，本文将通过六个章节进行内容阐述。

第一章：描述了程序的开发背景，程序运用于现实生活的目的与意义，以及程序文档的结构安排信息；

第二章：描述了程序的开发环境，包括程序开发涉及到的技术，程序开发使用的数据存储工具等信息；

第三章：描述了程序着手进行开发时，会面临的可行性问题，并对程序功能以及性能要求进行描述；

第四章：描述了程序大功能模块下的功能细分信息，以及存储程序数据的数据库表文件结构的设计信息等；

第五章：描述了程序的功能实现界面的内容，也对程序操作人员操作的部分功能进行了描述；

第六章：描述了程序功能的测试内容，并介绍了系统测试的概念与方法。
# 2 相关技术
## 2.1 MySQL数据库
本设计用到的数据库就是MySQL数据库[3]，之所以用到这个数据库的原因很多。首先，从满足功能需求上面来讲，MySQL是符合的；其次，从学习程度来讲，MySQL相比其他数据库不管是从安装还是使用上面来讲，都比较简单，最重要的是学习起来相当便捷，比较容易入手；再次，MySQL数据库对电脑要求不高，不管是什么样的电脑都可以安装MySQL数据库，并且并不会对电脑性能造成过多的影响。所以，就平常普普通通的电脑就可以作为开发用的电脑，不需要进行额外的电脑升级。虽然自从MySQL数据库被Oracle数据库收购后，有了一些闭源的风险，但是使用者还是很多，MySQL数据库目前的开发人员已经超过五百人了，对数据库开发者来讲已经是一个很大的开发团队了。MySQL在使用上面来讲，普通的增删改查操作已经可以满足大部分业务需求，像一些数据导出导入，以及一些函数，都可以满足一些不同的需求，最重要的是MySQL数据库可以创建索引，可以大大的提高数据的查询效率，当然，物极必反，如果因为索引好用而滥用，索引弄得比数据库表还要多，这样会造成MySQL数据库更新表数据时候的运行效率。总而言之，MySQL数据库在本次设计的使用上，是完全符合使用要求的。
## 2.2 IDEA简介
IDEA的诞生在Java集成开发工具行业正所谓平地起雷，瞬间震动了整个Java开发行业。真的是每个人用过的都说好。IDEA之所以相比于其他比如MyEclipse或者Eclipse之类的Java开发工具来讲比较好，原因首先在于设计方面。IDEA采用了所谓的人体工程学设计原理，让使用IDEA的人员用了就忘记不了。软件打开首先要设置主题，可以选择常规的白色或者暗色系列，长时间的白色或者长时间的暗色会让开发人员的眼睛疲劳加重，首先从这个细节就让程序开发人员备受青睐，让程序员看着舒服；然后再对一些常用性插件进行归类，让程序的开发注重于提升生产效率，而不是一味的让开发者找各种插件，有时候插件之间的版本还会存在不兼容，IDEA就把兼容的插件双手呈现，如此贴心的IDEA怎么能让人不喜爱。所以选择IDEA用来开发本项目就理所当然的了。
## 2.3 Ssm框架
SpringBoot是一个很好的框架[4]，但是发展到现在，在使用上面已经诟病不断，需要配置的越来越多，配置大于开发，让程序员用更多的精力去配置SpringBoot，有点本末倒置了。SpringBoot框架好用是好用，但是配置起来相当的繁琐，Ssm则让简化了很多配置过程，让开发变得更有趣也更有效率，并且学过SpringBoot框架的开发人员很容易理解SpringBoot框架[5]，没有用过框架的人员学习SpringBoot框架的速度也很快的，SpringBoot得到了Java开发者的一致好评。
## 2.4 Vue框架
Vue框架的开发者是一个中国人，区别于其他框架的最核心的概念就是渐进式框架，Vue的出现，让网页前端的开发变成了一种纯前端职业，不需要在考虑后台数据类型以及业务逻辑，只需要进行数据绑定即可，大大的减少了前端开发工程师的学习难度。Vue是当前世界上最火的一种前段框架，学习成本比较低，只需要熟悉最基本的网页知识就可以理解相关知识，并且有很好的免费教程进行学习，有各个国家语言的教程，尤其是因为是中国人开发的框架，让中国的高级程序开发人员做了汉语教程。Vue框架[6]发展之初就是高于IE8版本的，所以说只要是当前的主流浏览器都支持Vue框架，如果是很旧的那种电脑是不支持的，必须安装支持HTML5的浏览器才可以访问用Vue发布的站点。



# 3 系统分析
当用户确定开发一款程序时，是需要遵循下面的顺序进行工作，概括为：系统分析-->系统设计-->系统开发-->系统测试，无论这个过程是否有变更或者迭代，都是按照这样的顺序开展工作的。系统分析就是分析系统需要做什么的问题，主要目的就是确定系统的功能，这也为接下来的工作做了一个好的开端。
## 3.1 系统可行性分析
开发一款程序软件不仅需要时间，也需要人力，物力资源。而进行可行性分析这个环节就是解决用户这方面的疑问，看看程序在当前的条件下是否可以进行开发。
### 3.1.1 技术可行性分析
此程序选用的开发语言是Java，这种编程语言有着丰富的数据类型，在指令控制语句上也比较完善，更重要的就是对类与对象的大力支持，这些优点为程序开发者提供了技术保障，尤其是现在代码都逐渐模块化，有关系统功能开发的源码在网络上都公开展示了，所以让具备一定计算机开发基础的开发人员独立开发系统在技术上也逐渐容易。
### 3.1.2 经济可行性分析
开发此程序最关键的设备就是一台电脑，无论是学校计算机室配备的电脑，还是自己入学以来购置的笔记本，都是可以符合开发要求的设备，另外在网络上，学校本已完全覆盖了校园网，所以在设备以及网络上无须考虑经济问题。
### 3.1.3 运行可行性分析
随着电脑软件以及配套硬件的完善升级，当下的计算机环境是一片大好，尤其是计算机已经广泛普及到家家户户，所以计算机设备现在是随处可见，由于本次开发的程序占有的资源耗费较小，在一般的电脑或笔记本上都能轻松运转起来。

通过上面的可行性描述，可以从经济，技术，运行方面解决程序开发是否可行的问题。因此可以认为该程序软件是可以进行开发的。
## 3.2 系统性能分析
系统性能分析也是比较重要的内容，进行系统性能分析就是为了确保系统的功能要能够在生活中运行使用时，达到规定的指标，因此一个完整的系统软件，是需要进行系统的性能分析这个步骤的。本次进行性能分析主要从易用性指标，可扩展性指标，系统健壮性指标，系统安全性指标这几个方面进行分析。
### 3.2.1 易用性指标
本次程序软件的开发的目的就是让使用者可以通过使用该软件提高信息数据的管理效率，同时该程序软件也需要针对不同的操作用户设置对应的功能，因此，此程序的操作流程应该尽量与用户日常操作软件的行为习惯相贴合，另外，程序软件的设计与开发也应考虑非计算机专业用户的计算机操作水平，要让大部分使用者都可以轻松操作程序提供的各个功能。
### 3.2.2 可扩展性指标
当前需要开发的程序软件是根据当下的用户需求进行设计开发的，但是随着时间的推移，社会大环境的改变，开发出的程序也是需要与时俱进的，需要根据用户不断变换的需求进行相应的功能内容的扩展，需要注意的就是，当对成型的程序进行功能模块新增时，仍然需要保证程序原有架构以及功能不能受到影响，新增的功能模块在系统中也能够运行正常，该指标达标也就可以保证此程序是可以在满足信息管理要求下，从容应对市场环境的变化。
### 3.2.3 健壮性指标
程序软件的开发就是为了投入使用时，可以一直稳定的处理各种数据信息，程序软件一旦不稳定，也会给使用者带来干扰。因此从性能分析的角度，就要要求程序软件在应对使用者的误操作，或者是使用者因为各种原因，填写有误的数据等情况时，程序要一直保持稳定，并能够正常让使用者进行使用。当程序的某个功能模块出现异常时，程序的其它功能模块也要能够确保正常使用。程序的健壮性指标达标可以让使用者产生良好的用户体验。
### 3.2.4 安全性指标
程序软件的安全问题是首要问题，毕竟程序对应数据库里面存放的数据信息是庞大的，里面也包括了许多重要的个人信息，这就对程序要具备一个完善的安全机制提出了要求。因此程序必须要设置登录功能用以进行用户身份的检查，以及身份和权限的匹配，通过对不同用户身份进行功能约束，绝不容忍用户越权操作程序。另外，也需要时刻防范计算机病毒，还有黑客，通过采取针对性的办法进行安全应对，确保程序时刻处于安全的环境，让使用者放心使用。
## 3.3 系统流程分析
### 3.3.1 操作流程分析
程序上交给用户进行使用时，需要提供程序的操作流程图（如图3.1所示），这样便于用户容易理解程序的具体工作步骤，现如今程序的操作流程都有一个大致的标准，即先通过登录页面提交登录数据，通过程序验证正确之后，用户才能在程序功能操作区页面操作对应的功能。

![](/images/0300stringboot/0398springboot/blog.001.png)

图3.1 程序操作流程图
### 3.3.2 登录流程分析
在这个部分，需要对程序的登录功能模块的运行流程（如图3.2所示），进行单独说明。程序设置登录模块也是为了安全起见，让用户使用放心，登录模块主要就是让用户提交登录信息，程序进行数据验证，验证通过的用户才能够成功登录程序。

![](/images/0300stringboot/0398springboot/blog.002.png)

图3.2 程序登录流程图
### 3.3.3 信息添加流程分析
程序的添加功能就是提供给操作者录入信息的功能，不管是涉及到用户信息添加，还是其它功能模块涉及到的信息添加，程序的信息添加流程（如图3.3所示）都是一致的。程序都是先对操作者录入的数据进行判定，这个判定规则是一段提前编写完成的程序代码，当程序判定数据符合要求时，才会把操作者录入的数据登记在数据表里面，比如添加的用户信息，就会把新添加的用户信息写入用户信息的数据表文件里面。

![](/images/0300stringboot/0398springboot/blog.003.png)

图3.3 信息添加流程图
### 3.3.4 信息删除流程分析
当从程序里面删除某种无效数据时，遵循程序的信息删除流程（如图3.4所示），先要选中操作者需要删除的数据，程序为了预防操作者误删信息，也会进行提示，当操作者真正确定要删选中的信息时，该信息就会从数据库中被永久删除。

![](/images/0300stringboot/0398springboot/blog.004.png)

图3.4 信息删除流程图
## 3.4 系统功能分析
程序功能需要花费一定时间进行分析与设计，需要从大量的参考资料或者是社会上同种类型的程序中吸收对此程序开发有用的知识，可以将其它同类型程序中的合理功能部分规划到此程序里面，另外程序功能也需要针对用户的需求进行分析与设计。
# 4 系统设计
## 4.1 总体功能
牙科就诊管理系统是根据需求定制开发，开发软件选用idea平台配合MySQL数据库进行开发环境的搭建操作，网站采用为微信小程序结构进行开发，用户通过小程序访问项目,管理人员通过访问系统数据仅仅需要在客户端安装谷歌浏览器或者是当下常用浏览器就可以访问网站后台管理内容。
## 4.2 系统概要设计
本次拟开发的系统为了节约开发成本，也为了后期在维护和升级上的便利性，打算通过浏览器来实现系统功能界面的展示，让程序软件的主要事务集中在后台的服务器端处理，前端部分只用处理少量的事务逻辑。下面使用一张图（如图4.2所示）来说明程序的工作原理。

![](/images/0300stringboot/0398springboot/blog.005.png)

图4.2 程序工作的原理图
## 4.3 系统功能结构设计
在分析并得出使用者对程序的功能要求时，就可以进行程序设计了。如图4.3展示的就是管理员功能结构图，管理员在后台主要管理病例管理、字典管理、公告管理、药单管理、药品管理、药品收藏管理、药品评价管理、药品订单管理、牙医管理、牙医收藏管理、牙医评价管理、牙医挂号管理、用户管理、管理员管理等。

![结构设计图](/images/0300stringboot/0398springboot/blog.006.jpeg "结构设计图")


图4.3 管理员功能结构图
## 4.4 数据库设计
程序功能操作不管是添加，修改，还是删除等功能产生的数据都是经由数据库进行数据保存和更新的，所以一个数据库设计的好坏也是程序是否好坏的判定标准，因为程序的成功，有一半的功劳都是靠数据库的优秀设计。数据库一旦设计得良好是可以减轻开发人员的开发负担的。
### 4.4.1 数据库E-R图设计
这个部分的设计需要使用到E-R图绘制工具，常用的工具就是Visio工具来绘制E-R模型图，这款工具不仅可以快速创建需要的E-R模型图，而且该工具提供的操作界面很简单，可以短时间内修改绘图界面的图形或者是文字的属性。在绘制E-R模型图时，要分清楚各个图形代表的含义，以免绘制出错，E-R模型图由长方形（实体），椭圆形（属性），菱形（关系）这三部分图形符号组成，绘制期间要区分开来，用准确的图形符号代表相应的数据元素。

（1）下图是药品收藏实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.2\\_\_\_\_img\药品收藏.jpg](/images/0300stringboot/0398springboot/blog.007.jpeg "C:/Users/Administrator/Desktop/temp111\6.2\\_\_\_\_img\药品收藏.jpg")

药品收藏实体属性图

（2）下图是用户实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.2\\_\_\_\_img\用户.jpg](/images/0300stringboot/0398springboot/blog.008.jpeg "C:/Users/Administrator/Desktop/temp111\6.2\\_\_\_\_img\用户.jpg")

用户实体属性图

（3）下图是药品实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.2\\_\_\_\_img\药品.jpg](/images/0300stringboot/0398springboot/blog.009.jpeg "C:/Users/Administrator/Desktop/temp111\6.2\\_\_\_\_img\药品.jpg")

药品实体属性图

（4）下图是牙医收藏实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.2\\_\_\_\_img\牙医收藏.jpg](/images/0300stringboot/0398springboot/blog.010.jpeg "C:/Users/Administrator/Desktop/temp111\6.2\\_\_\_\_img\牙医收藏.jpg")

牙医收藏实体属性图

（5）下图是病例实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.2\\_\_\_\_img\病例.jpg](/images/0300stringboot/0398springboot/blog.011.jpeg "C:/Users/Administrator/Desktop/temp111\6.2\\_\_\_\_img\病例.jpg")

病例实体属性图

（6）下图是牙医挂号实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.2\\_\_\_\_img\牙医挂号.jpg](/images/0300stringboot/0398springboot/blog.012.jpeg "C:/Users/Administrator/Desktop/temp111\6.2\\_\_\_\_img\牙医挂号.jpg")

牙医挂号实体属性图

（7）下图是药品评价实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.2\\_\_\_\_img\药品评价.jpg](/images/0300stringboot/0398springboot/blog.013.jpeg "C:/Users/Administrator/Desktop/temp111\6.2\\_\_\_\_img\药品评价.jpg")

药品评价实体属性图

（8）下图是药品订单实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.2\\_\_\_\_img\药品订单.jpg](/images/0300stringboot/0398springboot/blog.014.jpeg "C:/Users/Administrator/Desktop/temp111\6.2\\_\_\_\_img\药品订单.jpg")

药品订单实体属性图

（9）下图是牙医实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.2\\_\_\_\_img\牙医.jpg](/images/0300stringboot/0398springboot/blog.015.jpeg "C:/Users/Administrator/Desktop/temp111\6.2\\_\_\_\_img\牙医.jpg")

牙医实体属性图

（10）下图是牙医评价实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.2\\_\_\_\_img\牙医评价.jpg](/images/0300stringboot/0398springboot/blog.016.jpeg "C:/Users/Administrator/Desktop/temp111\6.2\\_\_\_\_img\牙医评价.jpg")

牙医评价实体属性图

（11）下图是公告实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.2\\_\_\_\_img\公告.jpg](/images/0300stringboot/0398springboot/blog.017.jpeg "C:/Users/Administrator/Desktop/temp111\6.2\\_\_\_\_img\公告.jpg")

公告实体属性图

（12）下图是药单实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\6.2\\_\_\_\_img\药单.jpg](/images/0300stringboot/0398springboot/blog.018.jpeg "C:/Users/Administrator/Desktop/temp111\6.2\\_\_\_\_img\药单.jpg")

药单实体属性图


### 4.4.2 数据库表结构设计
该研究数据库是一个关系型数据库，因而二维表的结构设计尤为重要。终究，二维表格数字模型是关系型数据库里的关系模型。在设计关系模型以前，大家还应当把握一些常见的关系模型界定。在全面了解了表构造设计最常见的界定后，大家必须采用以前绘制的E-R数字模型去完成表结构的设计，并且在公共图书馆中建立数据报表，并取名每一个数据报表。下列设计结论以表格方法表明。 

表4.1病例表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|bingli\_uuid\_number|String|病例编号|是|
|3|yonghu\_id|Integer|用户|是|
|4|yayi\_id|Integer|牙医|是|
|5|bingren\_name|String|病人名称|是|
|6|sex\_types|Integer|性别|是|
|7|age|Integer|年龄|是|
|8|bingli\_zhusu\_content|String|主诉|是|
|9|bingli\_xianbingshi\_content|String|现病史|是|
|10|bingli\_jiwangshi\_content|String|既往史|是|
|11|bingli\_tijianjieguo\_content|String|体检结果|是|
|12|bingli\_fuzhujieguo\_content|String|辅助检查结果|是|
|13|bingli\_chubuzhenduan\_content|String|初步诊断|是|
|14|bingli\_zhiliaoyijian\_content|String|治疗意见|是|
|15|insert\_time|Date|上传时间|是|
|16|create\_time|Date|创建时间|是|
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
表4.4药单表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yaodan\_uuid\_number|String|药单编号|是|
|3|yonghu\_id|Integer|用户|是|
|4|yayi\_id|Integer|牙医|是|
|5|jiancha\_time|Date|检查时间|是|
|6|bingrenzishu\_content|String|病人自述|是|
|7|jianchajieguo\_content|String|检查结果|是|
|8|yishengkaifang\_yaopin\_content|String|药品信息|是|
|9|yishengkaifang\_content|String|医生开方|是|
|10|yishengjianyi\_content|String|医生建议|是|
|11|huafeijine|BigDecimal|花费金额|是|
|12|xiacijiuzhen\_time|Date|下次就诊时间|是|
|13|bingli\_types|Integer|状态|是|
|14|insert\_time|Date|录入时间|是|
|15|create\_time|Date|创建时间|是|
表4.5药品表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yaopin\_name|String|药品名称|是|
|3|yaopin\_uuid\_number|String|药品编号|是|
|4|yaopin\_photo|String|药品照片|是|
|5|yaopin\_types|Integer|药品类型|是|
|6|yaopin\_kucun\_number|Integer|药品库存|是|
|7|yaopin\_old\_money|BigDecimal|药品原价|是|
|8|yaopin\_new\_money|BigDecimal|现价|是|
|9|yaopin\_cangku|String|所属仓库|是|
|10|yaopin\_clicknum|Integer|药品热度|是|
|11|yaopin\_content|String|药品介绍|是|
|12|yaopin\_jinji\_content|String|禁忌|是|
|13|yaopin\_gongxiao\_content|String|功效|是|
|14|yaopin\_shuomingshu\_content|String|说明书|是|
|15|shangxia\_types|Integer|是否上架|是|
|16|yaopin\_delete|Integer|逻辑删除|是|
|17|insert\_time|Date|录入时间|是|
|18|create\_time|Date|创建时间|是|
表4.6药品收藏表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yaopin\_id|Integer|药品|是|
|3|yonghu\_id|Integer|用户|是|
|4|yaopin\_collection\_types|Integer|类型|是|
|5|insert\_time|Date|收藏时间|是|
|6|create\_time|Date|创建时间|是|
表4.7药品评价表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yaopin\_id|Integer|药品|是|
|3|yonghu\_id|Integer|用户|是|
|4|yaopin\_commentback\_text|String|评价内容|是|
|5|insert\_time|Date|评价时间|是|
|6|reply\_text|String|回复内容|是|
|7|update\_time|Date|回复时间|是|
|8|create\_time|Date|创建时间|是|
表4.8药品订单表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yaopin\_order\_uuid\_number|String|订单编号|是|
|3|yaopin\_id|Integer|药品|是|
|4|yonghu\_id|Integer|用户|是|
|5|buy\_number|Integer|购买数量|是|
|6|yaopin\_order\_true\_price|BigDecimal|实付价格|是|
|7|yaopin\_order\_types|Integer|订单类型|是|
|8|yaopin\_order\_payment\_types|Integer|支付类型|是|
|9|insert\_time|Date|订单创建时间|是|
|10|create\_time|Date|创建时间|是|
表4.9牙医表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yayi\_uuid\_number|String|牙医编号|是|
|3|yayi\_name|String|牙医姓名|是|
|4|yayi\_phone|String|牙医手机号|是|
|5|yayi\_id\_number|String|牙医身份证号|是|
|6|yayi\_photo|String|牙医头像|是|
|7|yayi\_email|String|牙医邮箱|是|
|8|new\_money|BigDecimal|挂号费用|是|
|9|zhiwei\_types|Integer|职位|是|
|10|yayi\_content|String|医生介绍|是|
|11|yayi\_shanchang\_content|String|擅长|是|
|12|yayi\_rongyu\_content|String|所获荣誉|是|
|13|jinyong\_types|Integer|账户状态|是|
|14|create\_time|Date|创建时间|是|
表4.10牙医收藏表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yayi\_id|Integer|牙医|是|
|3|yonghu\_id|Integer|用户|是|
|4|yayi\_collection\_types|Integer|类型|是|
|5|insert\_time|Date|收藏时间|是|
|6|create\_time|Date|创建时间|是|
表4.11牙医评价表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yayi\_id|Integer|牙医|是|
|3|yonghu\_id|Integer|用户|是|
|4|yayi\_commentback\_text|String|评价内容|是|
|5|insert\_time|Date|评价时间|是|
|6|reply\_text|String|回复内容|是|
|7|update\_time|Date|回复时间|是|
|8|create\_time|Date|创建时间|是|
表4.12牙医挂号表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yayi\_order\_uuid\_number|String|订单编号|是|
|3|yayi\_id|Integer|牙医|是|
|4|yonghu\_id|Integer|用户|是|
|5|yayi\_order\_yuyue\_types|Integer|预约类型|是|
|6|insert\_time|Date|申请时间|是|
|7|yayi\_order\_time|Date|预约日期|是|
|8|yayi\_order\_types|Integer|预约状态|是|
|9|create\_time|Date|创建时间|是|
表4.13用户表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_uuid\_number|String|用户编号|是|
|3|yonghu\_name|String|用户姓名|是|
|4|yonghu\_phone|String|用户手机号|是|
|5|yonghu\_id\_number|String|用户身份证号|是|
|6|yonghu\_photo|String|用户头像|是|
|7|yonghu\_email|String|用户邮箱|是|
|8|new\_money|BigDecimal|余额|是|
|9|jinyong\_types|Integer|账户状态|是|
|10|create\_time|Date|创建时间|是|
表4.14管理员表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|username|String|员工名|是|
|3|password|String|密码|是|
|4|role|String|角色|是|
|5|addtime|Date|新增时间|是|

# 5 系统实现
系统实现部分就是将系统分析，系统设计部分的内容通过编码进行功能实现，以一个实际应用系统的形式展示系统分析与系统设计的结果。前面提到的系统分析，系统设计最主要还是进行功能，系统操作逻辑的设计，也包括了存储数据的数据库方面的设计等内容，系统实现就是一个最终的实施阶段，将前面的设计成果进行物理转化，最终出具可以运用于实际的软件系统。
## 5.1 管理员功能介绍
### 5.1.1 牙医列表
如图5.1显示的就是牙医列表页面，此页面提供给管理员的功能有：查看牙医、新增牙医、修改牙医、删除牙医等。

![](/images/0300stringboot/0398springboot/blog.019.png)

图5.1 牙医列表页面
### 5.1.2 公告信息管理
公告信息管理页面提供的功能操作有：新增公告，修改公告，删除公告操作。下图就是公告信息管理页面。

![](/images/0300stringboot/0398springboot/blog.020.png)

图5.3 公告信息管理页面
### 5.1.3公告类型管理
公告类型管理页面显示所有公告类型，在此页面既可以让管理员添加新的公告信息类型，也能对已有的公告类型信息执行编辑更新，失效的公告类型信息也能让管理员快速删除。下图就是公告类型管理页面。

![](/images/0300stringboot/0398springboot/blog.021.png)

图5.3 公告类型列表页面
### 5.1.4 药品管理
如图5.4显示的就是药品管理页面，此页面提供给管理员的功能有：新增药品,修改药品,删除药品。

![](/images/0300stringboot/0398springboot/blog.022.png)

图5.4药品管理页面
### 5.1.5 药品类型管理
如图5.5显示的就是药品类型管理页面，此页面提供给管理员的功能有：新增药品类型,修改药品类型,删除药品类型。

![](/images/0300stringboot/0398springboot/blog.023.png)

图5.5 药品类型管理页面
# 系统










