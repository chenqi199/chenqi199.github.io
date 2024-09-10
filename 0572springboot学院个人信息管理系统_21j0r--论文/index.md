# 0572springboot学院个人信息管理系统_21j0r--论文


# [0572springboot学院个人信息管理系统_21j0r--论文](https://github.com/GraduationProject-springboot/0572springboot)

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

# [项目清单](https://chenqi1990.site) 包安装运行

### [github 项目仓库](https://github.com/GraduationProject-springboot/allSpringbootProjects) 开源仅有后端代码

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1eMbYemE1U?p=70)


# 系统概述
该系统由个人管理员和教师，学生三部分组成。其中：学生进入系统首页可以实现首页，课程信息，在线论坛，新闻公告，留言板，后台管理，个人中心等；教师可以对个人中心，课程信息管理，学习课程管理，作业通知管理，学生作业管理，批改作业管理等功能进行管理；管理员则是根据不同需求设置了不同功能，可以通过后台管理用户信息。
## 3.2　需求分析
需求分析，也称为软件需求分析、系统需求分析或需求分析工程，是指开发人员经过充分的研究和分析，准确地理解用户和项目在功能、性能、可靠性等方面的具体需求，并将用户的非正式需求表述转化为确定系统必须执行的需求的完整定义的过程[11]。

功能需求分析是系统设计的前提，它要求开发者和用户定义开发什么样的体系和系统需要什么样的功能。本文主要介绍了一种基于windows系统实现的学院个人信息管理系统。该系统为用户找到学院个人信息提供了更安全、更高效、更便捷的途径。本系统有三个角色：管理员和教师，学生，要求具备以下功能：

1. 学生可以浏览主页了解学院个人信息，可以查看首页，课程信息，在线论坛，新闻公告，留言板，后台管理，个人中心等功能；

![](/images/0500stringboot/0572springboot/blog.001.png)

图3-1：学生用例图

1. 管理员通过后台管理员界面，实现对个人中心，学生管理，教师管理，课程分类管理，班级管理，课程信息管理，学习课程管理，作业通知管理，学生作业管理，批改作业管理，留言板，在线讨论，系统管理等功能的操作；

![](/images/0500stringboot/0572springboot/blog.002.png)

图3-2：管理员用例图

1. 教师通过系统实现对课程信息，在线论坛，新闻公告，留言板，后台管理，个人中心等功能的操作；

![](/images/0500stringboot/0572springboot/blog.003.png)

图3-3：教师用例图

## 3.3　可行性分析
可行性分析是指通过比较项目的主要内容和支撑条件，如市场需求、资源供应、环境影响、资金筹措情况、盈利能力等，预测项目建成后可能产生的资金、经济效益、社会和环境影响，为项目决策提供依据的综合性系统分析方法。可行性研究报告编制的质量直接影响着投资决策的成，而可行性研究报告编制程序又决定了可行性研究报告能否得到有效执行。因此，必须重视可行性研究工作，提高其编制水平。可行性分析应当具有预见性、公正性、可靠性和科学性[13]。
### 3.3.1　技术可行性分析 
本系统是为了为用户寻找学院个人信息提供更加安全、高效、便捷的方式，本系统需要运用到Java、MySQL、springboot、B/S结构等技术，这些技术在国内外已经非常成熟[14]，在大学期间也有所涉及，相关的知识和工具在网络上也可以查到，再加上老师的指导，在技术上的难题可以得到解决。
### 3.3.2　经济可行性分析
该系统的主题是学院个人信息管理系统的设计与实现。开发所需的软件资源是Eclipse。我们可以在它的网站上安装一个免费的版本，这对我们的开发和使用是足够好的。数据库就是MySQL数据库。是开源是免费的，服务器使用Tomcat服务器，浏览器使用日常IE浏览器，springboot框架是开源的。经过可行性评估，软件资源支出符合经济可行性[15]。硬件方面，配备齐全的笔记本电脑作为工具在经济上是可行的。
## 3.4流程设计
### 3.4.1程序流程图设计
非本系统的用户要想进行学院个人信息管理就要注册本系统，登录时需要填写相应的资料，如有使用者，则会显示使用者名称已经存在，请再次键入使用者名称的提示框，若使用者不存在，则填写密码、确认密码等资料，并由系统判定密码与确认密码相符，确认无误后，填写使用者所填写的资料，即可进行登记。而且，为了保证系统的安全，只有在登录了本系统以后，才能进行学院个人信息管理。该系统的工作流程见图3-4。


![](/images/0500stringboot/0572springboot/blog.004.png)

图3-4 程序流程图
### 3.4.2添加信息流程图设计
在添加信息的时候，会判断是哪类用户，并根据用户类型判断执行是否合法，合法者可以进行添加，不合法者则不能进行此操作[12]。管理员登录账号后可以对内容进行添加，拥有着最高的权限，用户权限次于管理员。添加信息流程图如图3-5所示：

![](/images/0500stringboot/0572springboot/blog.005.png)

图3-5系统添加流程图
### 3.4.3删除信息流程图设计
删除数据时与添加数据功能类似，删除数据具体流程如图3-6所示：

![](/images/0500stringboot/0572springboot/blog.006.png)

图3-6系统删除流程图
## 3.5　本章小结
学院个人信息管理系统从市场、技术、经济、功能等方面分析了系统的功能需求，可以满足用户的学院个人信息管理需求，帮助用户安全、高效地找到合适的学院个人信息，因此有必要对其进行课题研究。
# 第4章　系统设计
系统设计是将被设计对象划分为单个模块进行构建，各个模块相互支持，相互制约，它们的组合是一个完整的系统。通过系统设计，可以最大限度地满足系统的预期目标，明确软件开发的目的。
## 4.1　系统基本结构设计
本次系统采用springboot框架集进行开发，springboot框架是一款企业界主流的软件开发框架，其简化了开发流程，大大缩减了软件开发所需的时间提高了软件的响应速度。系统总体结构图如图4-1所示。

![](/images/0500stringboot/0572springboot/blog.007.png)

图4-1　系统总体结构图

## 4.2　数据库设计
数据库结构设计的好坏直接影响到学院个人信息管理系统的效率和实现的效果。本系统的数据库采用MySQL数据库，MySQL是一种开放源代码的关系型数据库管理系统，使用最常见的数据库管理语言SQL进行数据库管理。
### 4.2.1　数据库E-R图设计
E-R图也可称为实体-联系图，其可以清楚的显示实体与实体之间的关系，是描述概念模型的有效方式，通过各实体间的关系方便数据库结构的设计。以下是本系统主要的实体属性图如下所示。

批改作业实体如图4-2所示。

![](/images/0500stringboot/0572springboot/blog.008.png)

图4-2批改作业实体属性图

新闻公告实体如图4-3所示。

![](/images/0500stringboot/0572springboot/blog.009.png)

图4-3新闻公告实体属性图

在线论坛实体如图4-4所示。

![](/images/0500stringboot/0572springboot/blog.010.png)

图4-4在线论坛实体属性图

课程信息评论实体如图4-5所示。

![](/images/0500stringboot/0572springboot/blog.011.png)

图4-5课程信息评论实体属性图

作业通知实体如图4-6所示。

![](/images/0500stringboot/0572springboot/blog.012.png)

图4-6作业通知实体属性图

### 4.2.2　数据库表设计
数据表是用来保存多种数据的表，它是所有数据库的核心对象，且对于软件开发有着不可替代的作用。其相关数据表如下：

表4-1：配置文件

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|name|varchar|100|配置参数名称|||
|value|varchar|100|配置参数值|||

表4-2：关于我们

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

表4-3：收藏表

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

表4-4：批改作业

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|kechengmingcheng|varchar|200|课程名称|||
|kechengfenlei|varchar|200|课程分类|||
|jiaoshizhanghao|varchar|200|教师账号|||
|jiaoshixingming|varchar|200|教师姓名|||
|lianxifangshi|varchar|200|联系方式|||
|zhanghao|varchar|200|账号|||
|xueshengxingming|varchar|200|学生姓名|||
|pigairiqi|date||批改日期|||
|pingfen|int||评分|||

表4-5：新闻公告

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|title|varchar|200|标题|||
|introduction|longtext|4294967295|简介|||
|picture|longtext|4294967295|图片|||
|content|longtext|4294967295|内容|||

表4-6：留言板

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

表4-7：用户表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|username|varchar|100|用户名|||
|password|varchar|100|密码|||
|role|varchar|100|角色||管理员|
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|

表4-8：在线论坛

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|title|varchar|200|帖子标题|||
|content|longtext|4294967295|帖子内容|||
|parentid|bigint||父节点id|||
|userid|bigint||用户id|||
|username|varchar|200|用户名|||
|avatarurl|longtext|4294967295|头像|||
|isdone|varchar|200|状态|||

表4-9：课程信息评论表

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

表4-10：token表

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

表4-11：班级

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|banji|varchar|200|班级|||

表4-12：作业通知

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|kechengmingcheng|varchar|200|课程名称|||
|kechengfenlei|varchar|200|课程分类|||
|jiaoshizhanghao|varchar|200|教师账号|||
|jiaoshixingming|varchar|200|教师姓名|||
|lianxifangshi|varchar|200|联系方式|||
|zhanghao|varchar|200|账号|||
|xueshengxingming|varchar|200|学生姓名|||
|zuoyebuzhi|varchar|200|作业布置|||
|zhuyaoneirong|varchar|200|主要内容|||
|wanchengzhuangtai|varchar|200|完成状态|||

表4-13：学习课程

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|kechengmingcheng|varchar|200|课程名称|||
|kechengfenlei|varchar|200|课程分类|||
|jiaoshizhanghao|varchar|200|教师账号|||
|jiaoshixingming|varchar|200|教师姓名|||
|lianxifangshi|varchar|200|联系方式|||
|zhanghao|varchar|200|账号|||
|xueshengxingming|varchar|200|学生姓名|||
|xuexiriqi|date||学习日期|||

表4-14：学生作业

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|kechengmingcheng|varchar|200|课程名称|||
|kechengfenlei|varchar|200|课程分类|||
|jiaoshizhanghao|varchar|200|教师账号|||
|jiaoshixingming|varchar|200|教师姓名|||
|lianxifangshi|varchar|200|联系方式|||
|zhanghao|varchar|200|账号|||
|xueshengxingming|varchar|200|学生姓名|||
|zuoyeneirong|longtext|4294967295|作业内容|||
|wanchengriqi|date||完成日期|||

表4-15：课程信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|kechengmingcheng|varchar|200|课程名称|||
|kechengfenlei|varchar|200|课程分类|||
|tupian|longtext|4294967295|图片|||
|kechengziliao|longtext|4294967295|课程资料|||
|jiaoxueshipin|longtext|4294967295|教学视频|||
|zhuyaoneirong|longtext|4294967295|主要内容|||
|jiaoshizhanghao|varchar|200|教师账号|||
|jiaoshixingming|varchar|200|教师姓名|||
|lianxifangshi|varchar|200|联系方式|||
|thumbsupnum|int||赞||0|
|crazilynum|int||踩||0|
|clicktime|datetime||最近点击时间|||
|clicknum|int||点击次数||0|

表4-16：学生

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|zhanghao|varchar|200|账号|||
|mima|varchar|200|密码|||
|xueshengxingming|varchar|200|学生姓名|||
|touxiang|longtext|4294967295|头像|||
|xingbie|varchar|200|性别|||
|nianling|int||年龄|||
|banji|varchar|200|班级|||
|zhuanye|varchar|200|专业|||
|xueyuan|varchar|200|学院|||
|shouji|varchar|200|手机|||

表4-17：课程分类

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|kechengfenlei|varchar|200|课程分类|||

表4-18：教师

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|jiaoshizhanghao|varchar|200|教师账号|||
|mima|varchar|200|密码|||
|jiaoshixingming|varchar|200|教师姓名|||
|zhaopian|longtext|4294967295|照片|||
|nianling|varchar|200|年龄|||
|zili|varchar|200|资历|||
|lianxifangshi|varchar|200|联系方式|||
|youxiang|varchar|200|邮箱|||
|zigezhengshu|longtext|4294967295|资格证书|||


## 4.3　本章小结
通过本章针对学院个人信息管理系统功能的总体结构、E-R属性图和数据表的大概介绍，对在开发系统时所要涉及到的数据库进行简单设计，为下一章系统的实现做好铺垫。

# 第五章 系统实现
## 5.1系统功能实现
当人们打开系统的网址后，首先看到的就是首页界面。在这里，人们能够看到学院个人信息管理系统的导航条。系统首页界面如图5-1所示：

![f9445198f98776fbaf582dd14912130](/images/0500stringboot/0572springboot/blog.013.jpeg)

图5-1 系统首页界面

系统注册：在系统注册页面输入用户注册信息进行注册操作；系统注册页面如图如图5-2所示：

![283a9f66a5df33c5fff8e6114cff008](/images/0500stringboot/0572springboot/blog.013.jpeg)

图5-2系统注册页面

课程信息：在课程信息页面的输入栏中输入课程名称和选择课程分类进行查询；还可以进行下载，收藏和点赞操作；课程信息页面如图5-3所示：

![f5dfb17f60f7ab481b1c812a84e971e](/images/0500stringboot/0572springboot/blog.013.jpeg)

图5-3课程信息详细页面

新闻公告：在新闻公告页面的输入栏中输入标题进行查询，可以查看新闻公告详细信息；热门景点页面如图5-4所示：

![8568f680ba7c8c5fabb48c01a5008a9](/images/0500stringboot/0572springboot/blog.013.jpeg)

图5-4新闻公告详细页面

个人中心：在个人中心页面通过填写个人详细信息进行信息更新操作，还可以对我的收藏和我的发布进行详细操作；如图5-5所示：

![f4c07921a3fbce085c97c190f3af2f7](/images/0500stringboot/0572springboot/blog.013.jpeg)

图5-5个人中心界面

## 5.2后台模块实现
后台登录，在登录页面选择需要登录的角色，在正确输入用户名和密码后，进入操作系统进行操作；如图5-6所示。

![e33deaa3aa8b2c906ce2febe2844fec](/images/0500stringboot/0572springboot/blog.013.jpeg)

图5-6后台登录界面
### 5.2.1管理员模块实现
管理员进入主页面，主要功能包括对个人中心，学生管理，教师管理，课程分类管理，班级管理，课程信息管理，学习课程管理，作业通知管理，学生作业管理，批改作业管理，留言板，在线讨论，系统管理等进行操作。管理员主页面如图5-7所示：

![a44be79ba36a94af90a097457cd051d](/images/0500stringboot/0572springboot/blog.013.jpeg)

图5-7 管理员主界面

管理员点击课程信息管理。在课程信息页面输入课程名称和选择课程分类进行查询或删除课程信息列表，并根据需要对课程详情信息进行详情、修改、查看评论或删除操作；如图5-8所示：

![37b5f32e514a190b460efe4e987a8c1](/images/0500stringboot/0572springboot/blog.013.jpeg)

图5-8课程信息管理界面

管理员点击学生作业管理。在学生作业页面输入课程名称进行查询或删除学生作业列表，并根据需要对学生作业详情信息进行详情、修改或删除操作；如图5-9所示：

![a7fcfa2318b670119dc822e6b78d9b6](/images/0500stringboot/0572springboot/blog.013.jpeg)

图5-9学生作业管理界面

管理员点击批改作业管理。在批改作业页面输入课程名称进行查询、新增或删除批改作业列表，并根据需要对批改作业详情信息进行详情、修改或删除操作；如图5-10所示：

![eebc32aeb773dd626966da3d4f8eb37](/images/0500stringboot/0572springboot/blog.013.jpeg)

图5-10批改作业管理界面

管理员点击作业通知管理。在作业通知页面输入课程名称进行查询或删除作业通知列表，并根据需要对作业通知详情信息进行详情、修改或删除操作；如图5-11所示：

![c767c1aa2a0ef3bf77722c96ef7e5d2](/images/0500stringboot/0572springboot/blog.013.jpeg)

图5-11作业通知管理界面
### 5.2.2学生模块实现
学生进入系统可以对首页,个人中心,学习课程管理，作业通知管理，学生作业管理，批改作业管理等功能进行操作。学生主页面如图5-12所示：

![98b09b91b7f80e9209bfc2fc2d603b3](/images/0500stringboot/0572springboot/blog.013.jpeg)

图5-12学生主界面
### 5.2.3教师模块实现
教师进入系统可以对个人中心，课程信息管理，学习课程管理，作业通知管理，学生作业管理，批改作业管理等功能进行操作。教师主页面如图5-13所示：

![452c33af3b3c98a734581f561dfa1c6](/images/0500stringboot/0572springboot/blog.013.jpeg)

图5-13教师主界面
## 5.3本章小结
第五章主要内容是系统实现，首先实现了本系统中最重要的前台功能，其次分别实现了对管理员功能的管理和对学生，教师后台的管理，并对主要代码的编写，完成了系统全部功能设计。












