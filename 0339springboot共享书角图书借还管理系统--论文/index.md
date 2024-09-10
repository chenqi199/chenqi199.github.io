# 0339springboot“共享书角”图书借还管理系统--论文


# [0339springboot“共享书角”图书借还管理系统--论文](https://github.com/GraduationProject-springboot/0339springboot)

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

# [项目清单](https://chenqi1990.site) 包安装运行

### [github 项目仓库](https://github.com/GraduationProject-springboot/allSpringbootProjects) 开源仅有后端代码

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1T1bpekEK7?p=12)


# 系统概述
该系统由个人管理员，出借者和借阅者三部分组成。其中：借阅者注册登录后，在我的页面可以对图书借阅，图书归还，反馈信息，留言簿等进行详细操作；管理员则是根据不同需求设置了不同功能，可以通过后台管理接口管理借阅者信息。
## 3.2 需求分析
需求分析，也称为软件需求分析、系统需求分析或需求分析工程，是指开发人员经过充分的研究和分析，准确地理解用户和项目在功能、性能、可靠性等方面的具体需求，并将用户的非正式需求表述转化为确定系统必须执行的需求的完整定义的过程[11]。

功能需求分析是系统设计的前提，它要求开发者和用户定义开发什么样的体系和系统需要什么样的功能。本文主要介绍了一种基于微信小程序实现的“共享书角”图书借还管理系统。该系统为借阅者找到图书借还信息提供了更安全、更高效、更便捷的途径。本系统有三个角色：管理员，出借者和借阅者，要求具备以下功能：

（1）借阅者可以浏览主页了解图书信息等，并对图书信息进行借阅、评论或收藏等操作；

（2）管理员通过后台管理员界面，实现对借阅者信息管理，或发布系统公告，让借阅者实时知道最新的图书借还信息。
## 3.3 可行性分析
可行性分析是指通过比较项目的主要内容和支撑条件，如市场需求、资源供应、环境影响、资金筹措情况、盈利能力等，预测项目建成后可能产生的资金、经济效益、社会和环境影响，为项目决策提供依据的综合性系统分析方法。可行性研究报告编制的质量直接影响着投资决策的成，而可行性研究报告编制程序又决定了可行性研究报告能否得到有效执行。因此，必须重视可行性研究工作，提高其编制水平。可行性分析应当具有预见性、公正性、可靠性和科学性[13]。
### 3.3.1 技术可行性分析
本系统是为了为借阅者寻找图书借还提供更加安全、高效、便捷的方式，本系统需要运用到Java、MySQL、springboot、B/S结构等技术，这些技术在国内外已经非常成熟[14]，在大学期间也有所涉及，相关的知识和工具在网络上也可以查到，再加上老师的指导，在技术上的难题可以得到解决。
### 3.3.2 经济可行性分析
该系统的主题是基于微信小程序的“共享书角”图书借还管理系统的设计与实现。开发所需的软件资源是Eclipse。我们可以在它的网站上安装一个免费的版本，这对我们的开发和使用是足够好的。数据库就是MySQL数据库。是开源是免费的，服务器使用Tomcat服务器，浏览器使用日常IE浏览器，springboot框架是开源的。经过可行性评估，软件资源支出符合经济可行性[15]。硬件方面，配备齐全的笔记本电脑作为工具在经济上是可行的。
## 3.4 系统流程分析
### 3.4.1 登录流程图
登录流程是该系统的第一个流程，登录的第一步是输入账号、密码登录，系统会验证账号与密码是否正确，正确时系统会判断账号类型再进入不同的后台；不正确时，会返回到登录的第一步，输入用户重新执行登录流程。该流程如图3-1所示。

![](/images/0300stringboot/0339springboot/blog.003.png)

图3-1登录流程图

### 3.4.2 添加新用户流程图
添加新用户的流程是先查询新用户名是否已存在，如已有该用户名，需重拟用户名并同时输入新用户的其它信息，添加新用户到数据库时会先验证数据是否完整，信息都正确且完整时，返回并刷新用户列表；信息不正确时，会返回输入信息的那一步。该流程如图3-2所示。

![](/images/0300stringboot/0339springboot/blog.004.png)

图3-2添加新用户流程图
## 3.5系统用例分析
### 3.5.1 管理员用例图
“共享书角”图书借还管理系统的最大权限用户是管理员，通过管理员菜单中的系统首页，个人中心，出借者管理，借阅者管理，图书分类管理，图书信息管理，图书借阅管理，图书归还管理，反馈信息管理，出租收入管理，留言簿，系统管理等选项来对系统后台信息进行管理。管理员用例如图3-3所示。

![](/images/0300stringboot/0339springboot/blog.005.png)

图3-3管理员用例图

### 3.5.2 出借者用例图
出借者进入系统可以对系统首页，个人中心，图书信息管理，图书借阅管理，图书归还管理，出租收入管理进行管理。出借者用例如图3-4所示。

![](/images/0300stringboot/0339springboot/blog.006.png)

图3-4出借者用例图

### 3.5.3 借阅者用例图
借阅者进入系统可以对图书借阅，图书归还，反馈信息，留言簿进行管理。借阅者用例如图3-5所示。

![](/images/0300stringboot/0339springboot/blog.007.png)

图3-5借阅者用例图

## 3.6 本章小结
基于微信小程序的“共享书角”图书借还管理系统从市场、技术、经济、功能等方面分析了系统的功能需求，可以满足借阅者的图书借还管理需求，帮助借阅者安全、高效地找到合适的图书借还信息，因此有必要对其进行课题研究。


# 第4章 系统设计
系统设计是将被设计对象划分为单个模块进行构建，各个模块相互支持，相互制约，它们的组合是一个完整的系统。通过系统设计，可以最大限度地满足系统的预期目标，明确软件开发的目的。
## 4.1 系统基本结构设计
本次系统采用springboot框架集进行开发，springboot框架是一款企业界主流的软件开发框架，其简化了开发流程，大大缩减了软件开发所需的时间提高了软件的响应速度。系统总体结构图如图4-1所示。

![](/images/0300stringboot/0339springboot/blog.008.png)

图4-1 系统总体结构图

## 4.2 数据库设计
数据库结构设计的好坏直接影响到“共享书角”图书借还管理系统的效率和实现的效果。本系统的数据库采用MySQL数据库，MySQL是一种开放源代码的关系型数据库管理系统，使用最常见的数据库管理语言SQL进行数据库管理。
### 4.2.1 数据库E-R图设计
E-R图也可称为实体-联系图，其可以清楚的显示实体与实体之间的关系，是描述概念模型的有效方式，通过各实体间的关系方便数据库结构的设计。以下是本系统主要的实体属性图如下所示。

图书资讯实体如图4-2所示。

![](/images/0300stringboot/0339springboot/blog.009.png)

图4-2图书资讯实体属性图

留言簿实体如图4-3所示。

![](/images/0300stringboot/0339springboot/blog.010.png)

图4-3留言簿实体属性图

反馈信息实体如图4-4所示。

![](/images/0300stringboot/0339springboot/blog.011.png)

图4-4反馈信息实体属性图

图书信息评论表实体如图4-5所示。

![](/images/0300stringboot/0339springboot/blog.012.png)

图4-5图书信息评论表实体属性图

出借者实体如图4-6所示。

![](/images/0300stringboot/0339springboot/blog.013.png)

图4-6出借者实体属性图

### 4.2.2 数据库表设计
数据表是用来保存多种数据的表，它是所有数据库的核心对象，且对于软件开发有着不可替代的作用。其相关数据表如下：

表4-1：token表

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

表4-2：收藏表

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

表4-3：图书资讯

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|title|varchar|200|标题|||
|introduction|longtext|4294967295|简介|||
|picture|longtext|4294967295|图片|||
|content|longtext|4294967295|内容|||

表4-4：留言簿

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

表4-5：反馈信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|jieyuezhanghao|varchar|200|借阅账号|||
|jieyuexingming|varchar|200|借阅姓名|||
|fankuishijian|datetime||反馈时间|||
|fankuineirong|longtext|4294967295|反馈内容|||

表4-6：图书信息评论表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|refid|bigint||关联表id|||
|userid|bigint||用户id|||
|avatarurl|longtext|4294967295|头像|||
|nickname|varchar|200|用户名|||
|content|longtext|4294967295|评论内容|||
|reply|longtext|4294967295|回复内容|||

表4-7：用户表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|username|varchar|100|用户名|||
|password|varchar|100|密码|||
|role|varchar|100|角色||管理员|
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|

表4-8：图书信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|tushubianhao|varchar|200|图书编号|||
|tushumingcheng|varchar|200|图书名称|||
|fengmian|longtext|4294967295|封面|||
|tushufenlei|varchar|200|图书分类|||
|shuliang|int||数量|||
|meirifeiyong|int||每日费用|||
|yajin|int||押金|||
|zuozhe|varchar|200|作者|||
|chubanshe|varchar|200|出版社|||
|jianjie|longtext|4294967295|简介|||
|xiangxijieshao|longtext|4294967295|详细介绍|||
|chujiezhanghao|varchar|200|出借账号|||
|chujiexingming|varchar|200|出借姓名|||
|thumbsupnum|int||赞||0|
|crazilynum|int||踩||0|
|clicktime|datetime||最近点击时间|||
|clicknum|int||点击次数||0|

表4-9：配置文件

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|name|varchar|100|配置参数名称|||
|value|varchar|100|配置参数值|||

表4-10：图书借阅

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|jieyuebianhao|varchar|200|借阅编号|||
|tushubianhao|varchar|200|图书编号|||
|tushumingcheng|varchar|200|图书名称|||
|shuliang|int||数量|||
|meirifeiyong|int||每日费用|||
|jieyuetianshu|int||借阅天数|||
|yajin|int||押金|||
|jine|int||金额|||
|jiechushijian|date||借出时间|||
|jieyuezhanghao|varchar|200|借阅账号|||
|jieyuejine|varchar|200|借阅金额|||
|chujiezhanghao|varchar|200|出借账号|||

表4-11：出租收入

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|zhuti|varchar|200|主题|||
|chujiezhanghao|varchar|200|出借账号|||
|chujiexingming|varchar|200|出借姓名|||
|jine|int||金额|||
|tuihaiyajin|varchar|200|退还压金|||
|shidejine|varchar|200|实得金额|||
|riqi|date||日期|||

表4-12：图书归还

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|jieyuebianhao|varchar|200|借阅编号|||
|tushubianhao|varchar|200|图书编号|||
|tushumingcheng|varchar|200|图书名称|||
|shuliang|int||数量|||
|yajin|int||押金|||
|guihaishijian|date||归还时间|||
|jieyuezhanghao|varchar|200|借阅账号|||
|chujiezhanghao|varchar|200|出借账号|||
|guihaibeizhu|varchar|200|归还备注|||
|sfsh|varchar|200|是否审核||待审核|
|shhf|longtext|4294967295|审核回复|||
|ispay|varchar|200|是否支付||未支付|

表4-13：出借者

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|chujiezhanghao|varchar|200|出借账号|||
|mima|varchar|200|密码|||
|chujiexingming|varchar|200|出借姓名|||
|touxiang|longtext|4294967295|头像|||
|xingbie|varchar|200|性别|||
|shoujihaoma|varchar|200|手机号码|||
|shidejine|int||实得金额|||

表4-14：图书分类

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|tushufenlei|varchar|200|图书分类|||

表4-15：借阅者

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|jieyuezhanghao|varchar|200|借阅账号|||
|mima|varchar|200|密码|||
|jieyuexingming|varchar|200|借阅姓名|||
|touxiang|longtext|4294967295|头像|||
|xingbie|varchar|200|性别|||
|shoujihaoma|varchar|200|手机号码|||
|jine|int||金额|||

## 4.3 本章小结
通过本章针对“共享书角”图书借还管理系统功能的总体结构、E-R属性图和数据表的大概介绍，对在开发系统时所要涉及到的数据库进行简单设计，为下一章系统的实现做好铺垫。


# 第5章 系统实现
系统实现章节的主要内容主要是将系统分析和系统设计方案进行实现，按照各个系统角色进行功能介绍，系统实现就是一个真正开始编写的阶段，将前面的分析结果以及设计方案进行实现，最终做出一个符合用户需求的软件系统。
## 5.1小程序端实现
### 5.1.1注册登录界面的实现
第一次使用本小程序的使用者，首先是要进行注册，点击“注册”，然后就会进入到注册的页面里面，将借阅者信息录入注册表，确认信息正确后，系统才会进入登录界面，借阅者登录成功后可使用本小程序所提供的所有功能。注册界面如图5-1所示。

![](/images/0300stringboot/0339springboot/blog.014.png)

图5-1 注册界面

首先双击打开小程序客户端，连上网络之后会显示出本系统的登录界面，这是进入小程序的初始页面“登录”，能成功进入到该登录界面则代表小程序的开启是成功的，接下来就可以操作本系统所带有的其他所有的功能。登录界面如图5-2所示。

![](/images/0300stringboot/0339springboot/blog.015.png)

图5-2 登录界面

5.1.2 小程序首页功能的实现

小程序首页是借阅者注册登录后进入的第一个界面，在这里，人们能够看到小程序的导航条，内容包括首页，图书信息，我的等。小程序首页界面如图5-3所示。

![](/images/0300stringboot/0339springboot/blog.016.png)

图5-3 小程序首页界面图

图书信息：在图书信息页面输入图书编号进行搜索，可以查看到图书详细信息；并根据需要进行收藏操作；图书信息详情如图5-4所示。

![](/images/0300stringboot/0339springboot/blog.017.png)

图5-4图书信息详情界面图

5.1.3借阅者功能

借阅者登录成功后，点击“我的”进入我的页面，在我的页面可以对图书借阅，图书归还，反馈信息，留言簿等进行详细操作。借阅者功能界面如图5-5所示。

![](/images/0300stringboot/0339springboot/blog.018.png)

图5-5借阅者功能界面图

## 5.2 后台功能的实现
后台登录，在登录页面选择需要登录的角色，在通过填写用户名和密码等信息进行登录操作，如图5-6所示。

![](/images/0300stringboot/0339springboot/blog.019.png)

图5-6后台登录界面图

### 5.2.1管理员模块实现
管理员登录进入小程序可以查看到系统首页，个人中心，出借者管理，借阅者管理，图书分类管理，图书信息管理，图书借阅管理，图书归还管理，反馈信息管理，出租收入管理，留言簿，系统管理等功能进行详细操作，如图5-7所示。

![](/images/0300stringboot/0339springboot/blog.020.png)

图5-7管理员功能界面图

管理员点击出借者管理；在出借者页面输入出借账号和出借姓名进行查询，新增或删除出借者信息列表，并根据需要对出借者详细信息进行详情、出租收入、修改或删除操作；如图5-8所示。

![](/images/0300stringboot/0339springboot/blog.021.png)

图5-8出借者管理界面图

管理员点击图书信息管理；在图书信息页面输入图书编号和图书名称进行查询或删除图书信息列表，并根据需要对图书详细信息进行详情、修改、查看评论或删除操作；如图5-9所示。

![](/images/0300stringboot/0339springboot/blog.022.png)

图5-9图书信息管理界面图

管理员点击图书归还管理；在图书归还页面输入图书编号、图书名称和选择是否通过进行查询或删除图书归还列表，并根据需要对图书归还详细信息进行详情、修改或删除操作；如图5-10所示。

![](/images/0300stringboot/0339springboot/blog.023.png)

图5-10图书归还管理界面图

管理员点击出租收入管理；在出租收入页面输入出租账号进行查询或删除出租收入列表，并根据需要对出租收入详细信息进行修改或删除操作；如图5-11所示。

![](/images/0300stringboot/0339springboot/blog.024.png)

图5-11出租收入管理界面图

管理员点击系统管理；在图书资讯页面输入标题进行查询、新增或删除图书资讯列表，并根据需要对图书资讯详细信息进行详情、修改或删除操作；还可根据需要对轮播图管理进行详细操作；如图5-12所示。

![](/images/0300stringboot/0339springboot/blog.025.png)

图5-12系统管理界面图

### 5.2.2出借者模块实现
出借者登录进入小程序可以查看到系统首页，个人中心，图书信息管理，图书借阅管理，图书归还管理，出租收入管理等功能进行详细操作，如图5-13所示。

![](/images/0300stringboot/0339springboot/blog.026.png)

图5-13出借者功能界面图

出借者点击图书信息管理；在图书信息页面输入图书编号和图书名称进行查询、新增或删除图书信息列表，并根据需要对图书详细信息进行详情、修改或删除操作；如图5-14所示。

![](/images/0300stringboot/0339springboot/blog.027.png)

图5-14图书信息管理界面图

出借者点击图书归还管理；在图书归还页面输入图书编号、图书名称和选择是否通过进行查询或删除图书归还列表，并根据需要对图书归还详细信息进行详情或删除操作；如图5-15所示。

![](/images/0300stringboot/0339springboot/blog.028.png)

图5-15图书归还管理界面图

## 5.3 本章小结
第五章主要内容是系统实现，首先实现了本系统中最重要的前台功能，其次分别实现了对管理员功能的管理员，出借者和借阅者的管理，完成了系统全部功能设计。













