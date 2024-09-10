# 0691springboot智慧养老平台--论文


# [0691springboot智慧养老平台--论文](https://github.com/GraduationProject-springboot/0691springboot)

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

# [项目清单](https://chenqi1990.site) 包安装运行

### [github 项目仓库](https://github.com/GraduationProject-springboot/allSpringbootProjects) 开源仅有后端代码

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)]()


# 绪论
## 1.1项目研究的背景
困扰管理层的许多问题当中,智慧养老平台一定是养老平台不敢忽视的一块。但是管理好智慧养老又面临很多麻烦需要解决,例如有几个方面:第一,往往人数都比较多,如何保证能够管理到每一老人;第二,如何在工作琐碎,记录繁多的情况下将智慧养老的当前情况反应给智慧养老领导相关部门决策等。在此情况下开发一款智慧养老平台，于是乎变得非常合乎时宜。

经过网上调查和搜集数据,我们可以发现智慧养老方面的系统并不是相当普及,智慧养老方面的可以有许多改进。实际上如今信息化成为一个未来的趋势或者可以说在当前现代化的城市典范中,信息化已经成为主流,开发一个智慧养老平台一方面的可能会更合乎时宜,另一方面来说也可以提高智慧养老方面的效率给相关部门人的工作带来一定的便利。
## 1.2开发意义
人类的进步带动信息化的发展，使人们生活节奏越来越快，所以人们越来越重视信息的时效性。以往的管理方式已经满足不了人们对获得信息的方式、方便快捷的需求。即智慧养老平台慢慢的被人们关注。首先，网上获取信息十分的实时、便捷，只要系统在线状态，无论在哪里都能第一时间查找到理想的信息。

计算机技术在管理中成为人们的重要工具。可以有效快捷的解决想要获取的信息，提高工作效率。
## 1.3课题研究现状
在国外很多发达国家，软件产业早已得到全面普及，但我国经济已不断发展，不断引进国外信息化建设，使国内软件行业得以不断发展，在摸索中进步，最终也得到一些成果，我国的软件业迎来了高速的发展，使更多的软件系统得以开发出来，从此逐渐地改变人们的生活工作方式。但是，对于信息化的建设，与很多发达国家相比，由于信息化程度的落后以及经费的不足，我国的智慧养老平台开发方面还是相对落后的，因此，要不断的努力探索，争取开发出一个实用的信息化的智慧养老平台，来实现智慧养老管理的信息化。因此本课题以智慧养老为例，目的是开发一个实用的智慧养老平台。

智慧养老平台的开发运用java技术，MIS的总体思想，以及MYSQL等技术的支持下共同完成了该系统的开发，实现了智慧养老管理的信息化，使用户体验到更优秀的智慧养老平台，管理员管理操作将更加方便，实现目标。
## 1.4项目研究内容与结构
智慧养老方面的任务繁琐,以至于每年都在智慧养老这方面投入较多的精力却效果甚微,智慧养老平台的目标就是为了能够缓解智慧养老工作方面面临的压力,让智慧养老方面的工作变得更加高效准确。

本项目在开发和设计过程中涉及到原理和技术有: B/S架构、java技术、和 MySQL数据库等等；将按以下章节进行开发设计；

1. 绪论；剖析项目背景与意义,说明研究的内容等。
1. 开发技术。系统主要使用了java技术，、b/s模式和myspl数据库，并对此做了介绍。
1. 系统分析；包罗了系统总体结构、对系统的性能、功能、流程图进行了分析。
1. 系统设计；对软件功能模块和数据库进行详细设计。
1. 系统总体设计；对系统管理员和老人的功能进行描述，
1. 对系统进行测试，
1. 总结心得；在论文最后结束章节总结了开发这个系统和撰写论文时候自己的总结、感想,包括致谢。

























# 2开发技术介绍
## 2.1 Java技术
Java是由Sun养老平台推出的一门跨平台的面向对象的程序设计语言。因为Java 技术具有卓越的通用性、高效性、健壮的安全性和平台移植性的特点，而且Java是开源的，拥有全世界最大的开发者专业社群，所以Java技术的发展十分迅速。
## 2.2 SpringCloud简介
SpringCloud是基于SpringBoot提供了一套微服务解决方案，包括服务注册与发现，配置中心，全链路监控，服务网关，负载均衡，熔断器等组件，除了基于NetFlix的开源组件做高度抽象封装之外，还有一些选型中立的开源组件。

SpringCloud利用SpringBoot的开发便利性巧妙地简化了分布式系统基础设施的开发，SpringCloud为开发人员提供了快速构建分布式系统的一些工具，包括配置管理、服务发现、断路器、路由、微代理、事件总线、全局锁、决策竞选、分布式会话等等,它们都可以用SpringBoot的开发风格做到一键启动和部署。

SpringCloud并没有重复制造轮子，它只是将目前各家养老平台开发的比较成熟、经得起实际考验的服务框架组合起来，通过SpringBoot风格进行再封装屏蔽掉了复杂的配置和实现原理，最终给开发者留出了一套简单易懂、易部署和易维护的分布式系统开发工具包。
## 2.3 MySQL 介绍
在软件项目，通过经营性数据的数据库，可以保证其安全，独立和数据一致，访问数据的系统来提供，所以有效减少时间程序员开发应用程序。

MySQL可以支持多线程，可以方便使用系统的资源，提高运行的速度。并提供odbc、jdbc和tcp/ ip，以各种形式连接到MySQL; 功能方面表现欠缺，规模小，但对于这个系统就足够了。

因为MySQL是源代码对外开放的，所以任何人都可以通过相应的方法下载，并根据个性化需求进行修改。 由于MySQL的速度，可靠性和适应性，MySQL受到重视。

MySQL虽然功能可能不是很强大，但由于其开源，广泛传播，导致很多人都意识到这个数据库。

## 2.4 MySQL环境配置
本系统的数据使用的是MySQL,所以要将MySQL安装到指定目录，如果下载的是非安装的MySQL压缩包，直接解压到指定目录就可以了。然后点击C:\Program Files\MySQL\bin\winMySQLadmin.exe这个文件其中C:\Program Files\MySQL是MySQL安装目录。输入winMySQLadmin的初始用户、密码（注：这不是MySQL里的用户、密码）随便填不必在意，确定之后右下角任务的启动栏会出现一个红绿灯的图标，红灯亮代表服务停止，绿灯亮代表服务正常，左击这个图标->winnt->install the service 安装此服务，再左击这个图标->winnt->start the service 启动MySQL服务。

修改MySQL数据库的root密码。用cmd进入命令行模式输入如下命令:

cd C:\Program Files\MySQL\bin

MySQLadmin -u root -p password 123

回车出现Enter password: ，这是要输入原密码. 刚安装时密码为空,所以直接回车，此时MySQL 中账号 root 的密码被改为 123 安装完毕。
## 2.5 B/S架构
B/S结构是目前使用最多的结构模式，它可以使得系统的开发更加的简单，好操作，而且还可以对其进行维护。使用该结构时只需要在计算机中安装数据库，和一些很常用的浏览器就可以了。浏览器就会与数据库进行信息的连接，可以实现很多的功能，B/S结构是可以直接进行使用的，而且B/S结构在使用中极大的减少了工作的维护。基于B/S的软件，所有的数据库之间都是相互独立的，因此是非常安全的。因为基于B/S结构可以清楚的看到系统正在处理的业务，并且能够及时的让管理人员做出决策，这样就可以避免企业的损失。B/S结构的基本特点是集中式的管理模式，用户使用系统生成数据后，这些数据就可以存储到系统的数据库中，方便日后能够用到，这样就可以满足人们的所有的需求。

![](/images/0600stringboot/0691springboot/blog.002.png)

图2-1  B/S模式三层结构图


# 3系统分析
## 3.1可行性分析
在开发系统之前要进行系统可行性分析，目的是在用最简单的方法去解决最大的问题，程序一旦开发出来满足了用户的需要，所带来的利益也很多。下面我们将从技术、操作、经济等方面来选择这个系统最终是否开发。
### 3.1.1技术可行性
本系统开发选择java技术，java是一个完全面向对象的语言，java为开发者提供了丰富的类库，大大减少了使用windows编程的难度,减少开发人员在设计算法上的难度，作为java开发 Visual Studio更是一个必不可少的角色，它友好的界面，以及强大的功能，给程序开发人员带来了很多方便，加上环境简单，转移方便，无疑使此系统最佳的选择。所以后台设计选择使用MySQL数据库主要用来的建立和维护信息。对于前台开发要求应具备功能完善、易于操作等优点，后台数据库的要求则是能够建立和维护数据信息的统一性和完整性。

依据上述目标来分析本系统的硬件如下：

奔腾3的处理器；

内存是 2G；

硬盘是50G；

操作系统是Window 10；

在软件方面的话，安装了Visul Studio 0 和MySQL数据库开发工具。根据以上的软件与硬件要求，得到这个系统的技术是可行的。
### 3.1.2经济可行性
基于web的智慧养老平台，该系统软件开发仅需要一台普通的计算机便可完成实现开发，其成本很低。另外，作为毕业设计作品来讲，开发成本基本上可以忽略不计，且该系统软件的投入使用，可以实现更加快速高效的智慧养老平台，同时还能实现对人力资源和管理资源的有效节约，该智慧养老平台在经济上完全可行。
### 3.1.3操作可行性
现在随着科技的飞速发展，计算机早已经进入了人们的日常生活中，人们的工作环境也不像以前有那么多的要求，需要员工一定要到养老平台办公，有的工作在家也可以完成。这使得人们的工作效益有了很大的提高。操作的多样性也变高了。因此，管理的计算机化，智能化是社会发展而带来的必然趋势，各种智能的软件层出不穷，不同的软件能完成用户不同的需求，这不仅提高了工作效率还能完成一些客户特定的一些需求。本系统不仅界面简洁明了还采用可视化界面，用户只要用鼠标和键盘就可以完成对相关信息的修改，删除，添加等操作。因为这个系统的操作十分简单，方便上手，对于第一次使用系统的人，只需要很少的时间就可以上手操作。由此可见，本系统在操作上是可行的。
### 3.1.4 运行可行性
本系统作为以java作为开发语言的系统，而且选用springcloud微服务架构和B/S结构则决定了要操作本系统仅需要占用很小的资源，并没有过多地硬件配置要求，目前市面上只要能正常运行浏览器的个人电脑都可以正常运行使用该系统。

经过总结，本系统在经济方面、技术方面、操作方面和运行方面的条件都得以满足，为此系统的开发具备了可行性条件。
## 3.2系统性能需求分析
对系统性能进行分析，可对系统反应度、界面简洁清晰度、储存能性、易学性和稳定性进行分析；

系统反应度：同时上万人在线时反应时间应该在两三秒以内，。

界面简洁清晰：系统界面要求简单明了，操作简单，用户操作容易上手。

储存性能高：智慧养老平台中需要存储的信息有很多，所以对系统的存储量要求很高，因此数据库就应该很强大，才能保证信息能安全稳定的进行存储；

易学性：该系统在操作上必须简单好上手，没有很多复杂的操作，只需要简单的进行学习就能操作该系统。

稳定性：要求智慧养老平台运行要稳定，界面清楚、字体清晰等。
## 3.3系统功能分析
考虑到实际生活中智慧养老平台方面的需要以及对该平台认真的分析,将系统权限按管理员和老人这两类涉及用户划分。

(a) 管理员；管理员使用本系统涉到的功能主要有：首页、个人中心、老人管理、亲属管理、每日健康管理、既往病史管理、活动分类管理、活动信息管理、商品类型管理、便利店管理、商品购买管理、劳工管理、服务类型管理、服务项目管理、服务购买管理、紧急求助管理、礼品发放管理、积分增加管理、系统管理等功能。管理员用例图如图3-1所示。

![](/images/0600stringboot/0691springboot/blog.003.png)

图3-1　管理员用例图

` `(b)老人；进入系统可以实现首页、养老平台、电影信息、个人中心、后台管理等功能。老人用例图如图3-2所示。

![](/images/0600stringboot/0691springboot/blog.004.png)

图3-2老人用例图
## 3.4系统流程的分析
由于不同的系统实际使用用户角色的不同,他们的业务分析也会变得有所不一样,为了论述方便接下来都将以用户功能权限下的系统业务流程来分析,如下图所展示:
### 3.4.1 用户管理的流程
![](/images/0600stringboot/0691springboot/blog.005.png)

图3-3用户管理流程

### 3.4.2个人中心管理流程

![](/images/0600stringboot/0691springboot/blog.006.png)

图3-4 个人中心管理流程
### 3.4.3登录流程
![](/images/0600stringboot/0691springboot/blog.007.png)

图3-5 登录流程
# 4系统设计
## 4.1 软件功能模块设计
网站整体功能如下图所示：

![](/images/0600stringboot/0691springboot/blog.008.png)

图 4-1 系统功能模块图
## 4.2数据库设计与实现
在每一个系统中数据库有着非常重要的作用，数据库的设计得好将会增加系统的效率以及系统各逻辑功能的实现。所以数据库的设计我们要从系统的实际需要出发，才能使其更为完美的符合系统功能的实现。
### 4.2.1概念模型设计
概念模型是对现实中的问题出现的事物的进行描述，ER图是由实体及其关系构成的图，通过E-R图可以清楚地描述系统涉及到的实体之间的相互关系。

服务项目实体图如图4-2所示：

![](/images/0600stringboot/0691springboot/blog.009.png)

图4-2服务项目实体图

便利店实体图如图4-3所示：

![](/images/0600stringboot/0691springboot/blog.010.png)

图4-3便利店实体图

活动信息实体图如图4-4所示：

![](/images/0600stringboot/0691springboot/blog.011.png)

图4-4活动信息实体图

### 4.2.2物理模型设计
根据上诉的逻辑模型设计,下面给出物理模型的设计, 设计每张表的变量名，变量的类型及主键等如下表:

表4-1：紧急求助

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|laorenzhanghao|varchar|200|老人账号|||
|laorenxingming|varchar|200|老人姓名|||
|laorenshouji|varchar|200|老人手机|||
|weizhi|varchar|200|位置|||
|qiuzhushijian|datetime||求助时间|||
|sfsh|varchar|200|是否审核||否|
|shhf|longtext|4294967295|审核回复|||

表4-2：用户表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|username|varchar|100|用户名|||
|password|varchar|100|密码|||
|role|varchar|100|角色||管理员|
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|

表4-3：token表

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

表4-4：收藏表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|userid|bigint||用户id|||
|refid|bigint||收藏id|||
|tablename|varchar|200|表名|||
|name|varchar|200|收藏名称|||
|picture|varchar|200|收藏图片|||
|type|varchar|200|类型(1:收藏,21:赞,22:踩)||1|
|inteltype|varchar|200|推荐类型|||

表4-5：商品类型

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|shangpinleixing|varchar|200|商品类型|||

表4-6：商品进货

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|jinhuobianhao|varchar|200|进货编号|||
|shangpinmingcheng|varchar|200|商品名称|||
|shuliang|int||数量|||
|jinhuodanjia|int||进货单价|||
|jinhuozongjia|varchar|200|进货总价|||
|jinhuoshijian|datetime||进货时间|||
|beizhu|varchar|200|备注|||

表4-7：商品购买

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|dingdanbianhao|varchar|200|订单编号|||
|shangpinmingcheng|varchar|200|商品名称|||
|shangpinfenlei|varchar|200|商品分类|||
|shuliang|int||数量|||
|danjia|int||单价|||
|zongjia|varchar|200|总价|||
|laorenzhanghao|varchar|200|老人账号|||
|laorenxingming|varchar|200|老人姓名|||
|laorenshouji|varchar|200|老人手机|||
|xiadanshijian|datetime||下单时间|||
|beizhu|varchar|200|备注|||
|sfsh|varchar|200|是否审核||否|
|shhf|longtext|4294967295|审核回复|||
|ispay|varchar|200|是否支付||未支付|


表4-8：亲属

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|laorenzhanghao|varchar|200|老人账号|||
|qinshuxingming|varchar|200|亲属姓名|||
|xingbie|varchar|200|性别|||
|lianxifangshi|varchar|200|联系方式|||
|yulaorenguanxi|varchar|200|与老人关系|||

表4-9：礼品发放

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|laorenzhanghao|varchar|200|老人账号|||
|laorenxingming|varchar|200|老人姓名|||
|laorenshouji|varchar|200|老人手机|||
|jifen|varchar|200|积分|||
|lipin|varchar|200|礼品|||
|lipintupian|varchar|200|礼品图片|||
|fafangshijian|datetime||发放时间|||
|fafangren|varchar|200|发放人|||
|fafangshiyou|longtext|4294967295|发放事由|||

表4-10：每日健康

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|laorenzhanghao|varchar|200|老人账号|||
|laorenxingming|varchar|200|老人姓名|||
|xingbie|varchar|200|性别|||
|nianling|varchar|200|年龄|||
|tiwen|varchar|200|体温|||
|xueya|varchar|200|血压|||
|xintiao|varchar|200|心跳|||
|jiankangbaogao|varchar|200|健康报告|||
|jianyi|longtext|4294967295|建议|||
|tianjiashijian|date||添加时间|||

表4-11：老人

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|laorenzhanghao|varchar|200|老人账号|||
|mima|varchar|200|密码|||
|laorenxingming|varchar|200|老人姓名|||
|xingbie|varchar|200|性别|||
|nianling|varchar|200|年龄|||
|zhaopian|varchar|200|照片|||
|laorenshouji|varchar|200|老人手机|||
|jifen|int||积分|||
|laorenzhuzhi|varchar|200|老人住址|||

表4-12：劳工

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|laogongxingming|varchar|200|劳工姓名|||
|xingbie|varchar|200|性别|||
|nianling|varchar|200|年龄|||
|tupian|varchar|200|图片|||
|gongzuonianling|varchar|200|工作年龄|||
|zhuanzhang|varchar|200|专长|||
|laogongjieshao|longtext|4294967295|劳工介绍|||

表4-13：既往病史

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|laorenzhanghao|varchar|200|老人账号|||
|laorenxingming|varchar|200|老人姓名|||
|xingbie|varchar|200|性别|||
|nianling|varchar|200|年龄|||
|guominshi|longtext|4294967295|过敏史|||
|yichuanshi|longtext|4294967295|遗传史|||
|dengjishijian|date||登记时间|||

表4-14：积分增加

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|laorenzhanghao|varchar|200|老人账号|||
|laorenxingming|varchar|200|老人姓名|||
|jifen|int||积分|||
|zengjiashijian|datetime||增加时间|||
|zengjiashiyou|longtext|4294967295|增加事由|||

表4-15：活动信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|huodongbiaoti|varchar|200|活动标题|||
|fengmian|varchar|200|封面|||
|huodongfenlei|varchar|200|活动分类|||
|kaishishijian|date||开始时间|||
|jieshushijian|date||结束时间|||
|huodongdidian|varchar|200|活动地点|||
|huodongneirong|longtext|4294967295|活动内容|||

表4-16：活动分类

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|huodongfenlei|varchar|200|活动分类|||

表4-17：服务项目

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|xiangmumingcheng|varchar|200|项目名称|||
|fuwuleixing|varchar|200|服务类型|||
|tupian|varchar|200|图片|||
|xiangmujiage|int||项目价格|||
|laogongxingming|varchar|200|劳工姓名|||
|xiangmuxiangqing|longtext|4294967295|项目详情|||

表4-18：服务类型

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|fuwuleixing|varchar|200|服务类型|||

表4-19：服务购买

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|xiadanbianhao|varchar|200|下单编号|||
|xiangmumingcheng|varchar|200|项目名称|||
|fuwuleixing|varchar|200|服务类型|||
|xiangmujiage|varchar|200|项目价格|||
|laogongxingming|varchar|200|劳工姓名|||
|laorenzhanghao|varchar|200|老人账号|||
|laorenxingming|varchar|200|老人姓名|||
|laorenshouji|varchar|200|老人手机|||
|laorenzhuzhi|varchar|200|老人住址|||
|yuyueshijian|datetime||预约时间|||
|xiadanshijian|datetime||下单时间|||
|beizhu|varchar|200|备注|||
|sfsh|varchar|200|是否审核||否|
|shhf|longtext|4294967295|审核回复|||
|ispay|varchar|200|是否支付||未支付|

表4-20：劳工评论表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|refid|bigint||关联表id|||
|userid|bigint||用户id|||
|nickname|varchar|200|用户名|||
|content|longtext|4294967295|评论内容|||
|reply|longtext|4294967295|回复内容|||

表4-21：配置文件

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|name|varchar|100|配置参数名称|||
|value|varchar|100|配置参数值|||


表4-22：便利店

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|shangpinbianhao|varchar|200|商品编号|||
|shangpinmingcheng|varchar|200|商品名称|||
|shengchandi|varchar|200|生产地|||
|shuliang|int||数量|||
|danjia|int||单价|||
|shangpinfenlei|varchar|200|商品分类|||
|shangpintupian|varchar|200|商品图片|||
|shangpinxiangqing|longtext|4294967295|商品详情|||


# 5系统详细设计
## 5.1系统功能模块
智慧养老平台，在系统首页可以查看首页、活动信息、便利店、劳工、服务项目、个人中心、后台管理等内容，并进行详细操作；如图5-1所示。

![](/images/0600stringboot/0691springboot/blog.012.png)

图5-1系统首页界面图

活动信息，在活动信息页面中可以查看活动标题、活动分类、开始时间、结束时间、活动地点等内容进行收藏等操作，如图5-2所示。

![](/images/0600stringboot/0691springboot/blog.013.png)

图5-2活动信息界面图

便利店，在便利店页面可以查看商品名称、生产地、数量、单价、商品分类等内容进行详情或收藏等操作，如图5-3所示。

![](/images/0600stringboot/0691springboot/blog.014.png)

图5-3便利店界面图

服务项目，在服务项目页面可以查看项目名称、项目类型、项目价格、劳工姓名等内容进行详情或收藏等操作，如图5-4所示。

![](/images/0600stringboot/0691springboot/blog.015.png)

图5-4服务项目界面图

`    `个人中心，在个人中心页面通过填写老人账号、密码、老人姓名、性别、年龄、图片、老人手机、积分、老人地址等内容进行更新信息等操作，并可以根据我的收藏进行相应的操作，如图5-5所示。

![](/images/0600stringboot/0691springboot/blog.016.png)

图5-5个人中心界面图
## 5.2后台登录功能
管理员和老人进入系统前在登录页面根据要求填写用户名和密码，选择角色等信息，点击登录进行登录操作，如图5-6所示。

![](/images/0600stringboot/0691springboot/blog.017.png)

图5-6登录界面图
### 5.2.1管理员功能
管理员登录系统后，可以对首页、个人中心、老人管理、亲属管理、每日健康管理、既往病史管理、活动分类管理、活动信息管理、商品类型管理、便利店管理、商品购买管理、劳工管理、服务类型管理、服务项目管理、服务购买管理、紧急求助管理、礼品发放管理、积分增加管理、系统管理等功能进行相应的操作管理，如图5-7所示。

![](/images/0600stringboot/0691springboot/blog.018.png)

图5-7管理员功能界面图

老人管理，在老人管理页面可以对索引、老人账号、老人姓名、性别、年龄、照片、老人手机、积分、老人地址等内容进行详情、礼品发放、积分增加、修改或删除等操作，如图5-8所示。

![](/images/0600stringboot/0691springboot/blog.019.png)

图5-8老人管理界面图

亲属管理，在亲属管理页面可以对索引、老人账号、亲属姓名、性别、联系方式、与老人关系等内容进行详情、修改或删除等操作，如图5-9所示。

![](/images/0600stringboot/0691springboot/blog.020.png)

图5-9亲属管理界面图

每日健康管理，在每日健康管理页面可以对索引、老人账号、老人姓名、性别、年龄、体温、血压、心跳、健康报告、添加时间等内容进行详情、修改或删除等操作，如图5-10所示。

![](/images/0600stringboot/0691springboot/blog.021.png)

图5-10每日健康管理界面图

既往病史管理，在既往病史管理页面可以对索引、老人账号、老人姓名、性别、年龄、登记时间等内容进行详情、修改或删除等操作，如图5-11所示。

![](/images/0600stringboot/0691springboot/blog.022.png)

图5-11既往病史管理界面图

活动信息管理，在活动信息管理页面中可以对索引、活动标题、封面、活动分类、开始时间、结束时间、活动地点等内容进行详情、修改或删除等操作，如图5-12所示。

![](/images/0600stringboot/0691springboot/blog.023.png)

图5-12活动信息管理界面图

便利店管理，在便利店管理页面中可以对索引、商品编号、商品名称、出生地、数量、单价、商品分类、商品图片等内容进行详情、进货、修改或删除等操作，如图5-13所示。

![](/images/0600stringboot/0691springboot/blog.024.png)

图5-13便利店管理界面图

商品进货管理，在商品进货管理页面可以对索引、进货编号、商品名称、数量、进货单价、进货总价、进货时间、备注等内容进行详情、修改或删除等操作，如图5-14所示。

![](/images/0600stringboot/0691springboot/blog.025.png)

图5-14商品进货管理界面图

劳工管理，在劳工管理页面中可以对索引、劳工姓名、性别、年龄、图片、工作年龄、专长等内容进行详情、修改、查看评论或删除等操作；如图5-15所示。

![](/images/0600stringboot/0691springboot/blog.026.png)

图5-15劳工管理界面图

服务购买管理，在服务购买管理页面中可以对索引、下单编号、项目名称、服务类型、项目价格、劳工姓名、老人姓名、老人手机、老人地址、预约时间、下单时间、备注、是否支付、审核回复、审核状态、审核等内容进行详情、修改或删除等操作，如图5-16所示。

![](/images/0600stringboot/0691springboot/blog.027.png)

图5-16服务购买管理界面图

礼品发放管理，在礼品发放管理页面中可以对索引、老人账号、老人姓名、老人手机、积分、礼品、礼品图片、发放时间、发放人等内容进行详情、修改或删除等操作，如图5-17所示。

![](/images/0600stringboot/0691springboot/blog.028.png)

图5-17礼品发放管理界面图

积分增加管理，在积分增加管理页面中可以对索引、老人账号、老人姓名、积分、增加时间等内容进行详情、修改或删除等操作，如图5-18所示。

![](/images/0600stringboot/0691springboot/blog.029.png)

图5-18积分增加管理界面图

### 5.2.2老人功能
老人注册，通过填写老人账号、密码、确认密码、老人姓名、年龄老人手机、老人地址等内容进行注册等操作，如图5-19所示。

![](/images/0600stringboot/0691springboot/blog.030.png)

图5-19老人注册界面图

老人登录系统后，可以对首页、个人中心、亲属管理、每日健康管理、既往病史管理、商品购买管理、服务购买管理、紧急求助管理、礼品发放管理、积分增加管理等功能进行相应的操作管理，如图5-20所示。

![](/images/0600stringboot/0691springboot/blog.031.png)

图5-20老人功能界面图

亲属管理，在亲属管理页面中可以对索引、老人账号、亲属姓名、性别、联系方式、与老人关系等内容进行详情、修改或删除等操作；如图5-21所示。

![](/images/0600stringboot/0691springboot/blog.032.png)

图5-21亲属管理界面图

商品购买管理，在商品购买管理页面中可以对索引、订单编号、商品名称、商品分类、数量、单价、总价、老人账号、老人姓名、老人手机、下单时间、备注、是否支付、审核回复、审核状态等内容进行详情或删除等操作，如图5-22所示。

![](/images/0600stringboot/0691springboot/blog.033.png)

图5-22商品购买管理界面图

服务购买管理，在服务购买管理页面中可以对索引、下单编号、项目名称、 服务类型、项目价格、劳工姓名、老人账号、老人手机、老人地址、预约时间、下单时间、备注、是否支付、审核回复、审核状态等内容进行详情或删除等操作，如图5-23所示。

![](/images/0600stringboot/0691springboot/blog.034.png)

图5-23服务购买管理界面图

商品购买管理，在商品购买管理页面中可以对索引、订单编号、商品分类、数量、单价、总价、老人账号、老人姓名、老人手机、备注、是否支付、审核回复、审核状态等内容进行详情或删除等操作，如图5-24所示。

![](/images/0600stringboot/0691springboot/blog.035.png)

图5-24商品购买管理界面图















#










