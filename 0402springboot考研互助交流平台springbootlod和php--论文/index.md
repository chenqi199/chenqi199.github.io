# 0402springboot考研互助交流平台springbootlod和php--论文


# [0402springboot考研互助交流平台springbootlod和php--论文](https://github.com/GraduationProject-springboot/0402springboot)

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

# [项目清单](https://chenqi1990.site) 包安装运行

### [github 项目仓库](https://github.com/GraduationProject-springboot/allSpringbootProjects) 开源仅有后端代码

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1ULbQeREgz?p=3)


# 系统概述
该系统由管理员和用户两部分组成。其中：用户注册登录后，在我的页面可以对首页、院校信息、备考经验、考研政策、课程资料、历年真题、考研倒计时、测评信息、交流论坛、复试调剂、后台管理、个人中心等进行详细操作；管理员则是根据不同需求设置了不同功能，可以通过后台管理接口管理用户信息。
## 3.2　需求分析
需求分析，也称为软件需求分析、系统需求分析或需求分析工程，是指开发人员经过充分的研究和分析，准确地理解用户和项目在功能、性能、可靠性等方面的具体需求，并将用户的非正式需求表述转化为确定系统必须执行的需求的完整定义的过程[11]。

功能需求分析是系统设计的前提，它要求开发者和用户定义开发什么样的体系和系统需要什么样的功能。本文主要介绍了一种基于PHP的考研互助交流系统。该系统为用户找到考研信息提供了更安全、更高效、更便捷的途径。本系统有两个角色：管理员和用户，要求具备以下功能：

（1）用户可以浏览主页了解考研政策和交流论坛等，并对课程进行在线测评、评论或收藏等操作；

（2）管理员通过后台管理员界面，实现对用户信息管理，或发布系统公告，让用户实时知道最新的考研信息；
## 3.3　可行性分析
可行性分析是指通过比较项目的主要内容和支撑条件，如市场需求、资源供应、环境影响、资金筹措情况、盈利能力等，预测项目建成后可能产生的资金、经济效益、社会和环境影响，为项目决策提供依据的综合性系统分析方法。可行性研究报告编制的质量直接影响着投资决策的成，而可行性研究报告编制程序又决定了可行性研究报告能否得到有效执行。因此，必须重视可行性研究工作，提高其编制水平。可行性分析应当具有预见性、公正性、可靠性和科学性[13]。
### 3.3.1　技术可行性分析 
本系统是为了为用户考研互助交流提供更加安全、高效、便捷的方式，本系统需要运用到PHP、MySQL和B/S结构等技术，这些技术在国内外已经非常成熟[14]，在大学期间也有所涉及，相关的知识和工具在网络上也可以查到，再加上老师的指导，在技术上的难题可以得到解决。
### 3.3.2　经济可行性分析
该系统的主题是基于php的考研互助交流系统的设计与实现。开发所需的软件资源是Eclipse。我们可以在它的网站上安装一个免费的版本，这对我们的开发和使用是足够好的。数据库就是MySQL数据库。是开源是免费的，服务器使用Tomcat服务器，浏览器使用日常IE浏览器。经过可行性评估，软件资源支出符合经济可行性[15]。硬件方面，配备齐全的笔记本电脑作为工具在经济上是可行的。
## 3.4　系统流程分析
### 3.4.1 登录流程图
登录流程是该系统的第一个流程，登录的第一步是输入账号、密码登录，系统会验证账号与密码是否正确，正确时系统会判断账号类型再进入不同的后台；不正确时，会返回到登录的第一步，输入用户重新执行登录流程。该流程如图3-1所示。

![](/images/0400stringboot/0402springboot/blog.001.png)

图3-1登录流程图
### 3.4.2 添加新用户流程图
添加新用户的流程是先查询新用户名是否已存在，如已有该用户名，需重拟用户名并同时输入新用户的其它信息，添加新用户到数据库时会先验证数据是否完整，信息都正确且完整时，返回并刷新用户列表；信息不正确时，会返回输入信息的那一步。该流程如图3-2所示。

![](/images/0400stringboot/0402springboot/blog.002.png)

图3-2添加新用户流程图

## 3.5　本章小结
基于php的考研互助交流系统从市场、技术、经济、功能等方面分析了系统的功能需求，可以满足用户的考研互助交流需求，帮助用户安全、高效地找到合适的考研信息，因此有必要对其进行课题研究。
# 第4章　系统设计
系统设计是将被设计对象划分为单个模块进行构建，各个模块相互支持，相互制约，它们的组合是一个完整的系统。通过系统设计，可以最大限度地满足系统的预期目标，明确软件开发的目的。
## 4.1　系统基本结构设计
本次系统采用php技术，系统总体结构图如图4-1所示。

![](/images/0400stringboot/0402springboot/blog.003.png)

图4-1　系统总体结构图
## 4.2　数据库设计
数据库结构设计的好坏直接影响到考研互助交流系统的效率和实现的效果。本系统的数据库采用MySQL数据库，MySQL是一种开放源代码的关系型数据库管理系统，使用最常见的数据库管理语言SQL进行数据库管理。
### 4.2.1　数据库E-R图设计
E-R图也可称为实体-联系图，其可以清楚的显示实体与实体之间的关系，是描述概念模型的有效方式，通过各实体间的关系方便数据库结构的设计。以下是本系统主要的实体属性图如下所示。

院校信息实体如图4-2所示。

![](/images/0400stringboot/0402springboot/blog.004.png)

图4-2院校信息实体属性图

备考经验实体如图4-3所示。

![](/images/0400stringboot/0402springboot/blog.005.png)

图4-3备考经验实体属性图

测评信息实体如图4-4所示。

![](/images/0400stringboot/0402springboot/blog.006.png)

图4-4测评信息实体属性图

交流论坛实体如图4-5所示。

![](/images/0400stringboot/0402springboot/blog.007.png)

图4-5交流论坛实体属性图

用户注册实体如图4-6所示。

![](/images/0400stringboot/0402springboot/blog.008.png)

图4-6用户注册实体属性图
### 4.2.2　数据库表设计
数据表是用来保存多种数据的表，它是所有数据库的核心对象，且对于软件开发有着不可替代的作用。其相关数据表如下：

表4-1 复试调剂

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|title|varchar|200|标题|||
|introduction|longtext|4294967295|简介|||
|picture|longtext|4294967295|图片|||
|content|longtext|4294967295|内容|||

表4-2：历年真题

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|biaoti|varchar|200|标题|||
|fengmian|longtext|4294967295|封面|||
|nianfen|varchar|200|年份|||
|timuleibie|varchar|200|题目类别|||
|neirong|longtext|4294967295|内容|||

表4-3：课程资料

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|kechengmingcheng|varchar|200|课程名称|||
|kechengfenlei|varchar|200|课程分类|||
|kechengfengmian|longtext|4294967295|课程封面|||
|kechengshipin|longtext|4294967295|课程视频|||
|kaikeshijian|date||开课时间|||
|jiaoshixingming|varchar|200|教师姓名|||
|kechengneirong|longtext|4294967295|课程内容|||
|clicktime|datetime||最近点击时间|||
|clicknum|int||点击次数||0|

表4-4：在线测评

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|biaoti|varchar|200|标题|||
|ceshijieguo|longtext|4294967295|测试结果|||
|ceshishijian|date||测试时间|||
|yonghuzhanghao|varchar|200|用户账号|||
|yonghuxingming|varchar|200|用户姓名|||
|sfsh|varchar|200|是否审核||待审核|
|shhf|longtext|4294967295|审核回复|||

表4-5：考研政策

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|biaoti|varchar|200|标题|||
|fengmian|longtext|4294967295|封面|||
|diqu|varchar|200|地区|||
|kaoyanxuzhi|longtext|4294967295|考研须知|||
|zhengceneirong|longtext|4294967295|政策内容|||
|faburiqi|date||发布日期|||
|clicktime|datetime||最近点击时间|||
|clicknum|int||点击次数||0|

表4-6：院校信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yuanxiaomingcheng|varchar|200|院校名称|||
|yuanxiaotupian|longtext|4294967295|院校图片|||
|yuanxiaozhuanye|varchar|200|院校专业|||
|fuzeren|varchar|200|负责人|||
|lianxidianhua|varchar|200|联系电话|||
|yuanxiaodizhi|varchar|200|院校地址|||
|zhaoshengrenshu|int||招生人数|||
|fenshuxian|varchar|200|分数线|||
|chengliriqi|date||成立日期|||
|zhaoshengjianjie|longtext|4294967295|招生简介|||
|yuanxiaojianjie|longtext|4294967295|院校简介|||
|clicktime|datetime||最近点击时间|||
|clicknum|int||点击次数||0|

表4-7：考研倒计时

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|biaoti|varchar|200|标题|||
|fengmian|longtext|4294967295|封面|||
|daojishi|varchar|200|倒计时|||
|neirong|longtext|4294967295|内容|||
|fabushijian|date||发布时间|||

表4-8：用户

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yonghuzhanghao|varchar|200|用户账号|||
|mima|varchar|200|密码|||
|yonghuxingming|varchar|200|用户姓名|||
|xingbie|varchar|200|性别|||
|lianxifangshi|varchar|200|联系方式|||
|touxiang|longtext|4294967295|头像|||

表4-9：交流论坛

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|title|varchar|200|帖子标题|||
|content|longtext|4294967295|帖子内容|||
|parentid|bigint||父节点id|||
|userid|bigint||用户id|||
|username|varchar|200|用户名|||
|isdone|varchar|200|状态|||

表4-10：打卡信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|dakabianhao|varchar|200|打卡编号|||
|biaoti|varchar|200|标题|||
|yonghuzhanghao|varchar|200|用户账号|||
|yonghuxingming|varchar|200|用户姓名|||
|dakashijian|date||打卡时间|||
|dakabeizhu|longtext|4294967295|打卡备注|||

表4-11：配置文件

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|name|varchar|100|配置参数名称|||
|value|varchar|100|配置参数值|||

表4-12：用户表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|username|varchar|100|用户名|||
|password|varchar|100|密码|||
|role|varchar|100|角色||管理员|
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|

表4-13：测评信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|biaoti|varchar|200|标题|||
|tupian|longtext|4294967295|图片|||
|cepingtimu|longtext|4294967295|测评题目|||
|cepingjianjie|longtext|4294967295|测评简介|||
|faburiqi|date||发布日期|||

表4-14：关于我们

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

表4-15：备考经验

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|biaoti|varchar|200|标题|||
|fengmian|longtext|4294967295|封面|||
|jianjie|longtext|4294967295|简介|||
|neirong|longtext|4294967295|内容|||
|faburiqi|date||发布日期|||

表4-16：收藏表

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

## 4.3　本章小结
通过本章针对考研互助交流系统功能的总体结构、E-R属性图和数据表的大概介绍，对在开发系统时所要涉及到的数据库进行简单设计，为下一章系统的实现做好铺垫。

# 第5章　界面设计与功能实现
## 5.1系统功能实现
当人们打开系统的网址后，首先看到的就是首页界面。在这里，人们能够看到系统的导航条，通过导航条导航进入各功能展示页面进行操作。系统首页界面如图5-1所示。

![](/images/0400stringboot/0402springboot/blog.009.png)

图5-1 系统首页界面

在用户注册页面的输入用户注册信息进行注册操作，用户注册页面如图5-2所示：

![](/images/0400stringboot/0402springboot/blog.010.png)

图5-2用户注册页面

在院校信息页面的输入栏中输入院校名称和院校专业进行查询，进入院校信息页面可以查看院校信息详细信息，并进行收藏操作；院校信息页面如图5-3所示：

![](/images/0400stringboot/0402springboot/blog.011.png)

图5-3院校信息详细页面

在备考经验页面的输入栏中输入标题进行查询，进入备考经验页面可以查看到备考经验详细信息，并进行收藏操作，页面如图5-4所示：

![](/images/0400stringboot/0402springboot/blog.012.png)

图5-4备考经验详细页面

在历年真题页面的输入栏中输入标题和题目类别进行查询，进入历年真题页面可以查看到历年真题详细信息，并进行收藏操作；页面如图5-5所示：

![](/images/0400stringboot/0402springboot/blog.013.jpeg)

图5-5历年真题详细页面

在测评信息页面的输入栏中输入标题进行查询，进入测评信息页面可以查看到测评信息详细信息，并进行测评和收藏操作；页面如图5-6所示：

![](/images/0400stringboot/0402springboot/blog.014.png)

图5-6测评信息详细页面

在个人中心页面输入个人信息可以进行更新操作，还可以对我的发布和我的收藏页面进行详细操作；如图5-7所示：

![](/images/0400stringboot/0402springboot/blog.015.png)

图5-7 个人中心界面

## 5.2 后台功能实现
后台用户登录，在登录页面选择需要登录的角色，在正确输入用户名和密码后，进入系统进行操作，如图5-8所示。

![](/images/0400stringboot/0402springboot/blog.016.png)

图5-8 后台登录界面图
### 5.2.1管理员模块实现
管理员登录系统后可以查看到系统首页、个人中心、用户管理、院校信息管理、备考经验管理、考研政策管理、课程资料管理、历年真题管理、考研倒计时管理、测评信息管理、在线测评管理、打卡信息管理、交流论坛、系统管理等功能进行详细操作，如图5-9所示。

![](/images/0400stringboot/0402springboot/blog.017.png)

图5-9管理员功能界面图

用户管理；在用户页面输入用户账号和用户姓名进行查询，新增或删除用户列表，并对用户详细信息进行详情、修改或删除操作；如图5-10所示。

![](/images/0400stringboot/0402springboot/blog.018.png)

图5-10用户管理界面图

院校信息管理；在院校信息页面输入院校名称和院校专业进行查询，新增或删除院校信息列表，并对院校信息详细信息进行详情、修改或删除操作；如图5-11所示。

![](/images/0400stringboot/0402springboot/blog.019.png)

图5-11院校信息管理界面图

备考经验管理；在备考经验页面输入标题进行查询，新增或删除备考经验列表，并对备考经验详细信息进行详情、修改或删除操作；如图5-12所示。

![](/images/0400stringboot/0402springboot/blog.020.png)

图5-12备考经验管理界面图

考研政策管理；在考研政策页面输入标题进行查询，新增或删除考研政策列表，并对考研政策详细信息进行详情、修改或删除操作；如图5-13所示。

![](/images/0400stringboot/0402springboot/blog.021.png)

图5-13考研政策管理界面图

课程资料管理；在课程资料页面输入课程名称进行查询，新增或删除课程资料列表，并对课程资料详细信息进行详情、修改或删除操作；如图5-14所示。

![](/images/0400stringboot/0402springboot/blog.022.png)

图5-14课程资料管理界面图

历年真题管理；在历年真题页面输入标题和题目类别进行查询，新增或删除历年真题列表，并对历年真题详细信息进行详情、修改或删除操作；如图5-15所示。

![](/images/0400stringboot/0402springboot/blog.023.png)

图5-15历年真题管理界面图

考研倒计时管理；在考研倒计时页面输入标题进行查询，新增或删除考研倒计时列表，并对考研倒计时详细信息进行详情、修改或删除操作；如图5-16所示。

![](/images/0400stringboot/0402springboot/blog.024.png)

图5-16考研倒计时管理界面图

测评信息管理；在测评信息页面输入标题进行查询，新增或删除测评信息列表，并对测评信息详细信息进行详情、修改或删除操作；如图5-17所示。

![](/images/0400stringboot/0402springboot/blog.025.png)

图5-17测评信息管理界面图

在线测评管理；在在线测评页面输入标题、测试结果和选择是否提高审核进行查询或删除在线测评列表，并对在线测评详细信息进行详情、、审核、修改或删除操作；如图5-18所示。

![](/images/0400stringboot/0402springboot/blog.026.png)

图5-18在线测评管理界面图

打卡信息管理；在打卡信息页面输入标题和用户姓名进行查询或删除打卡信息列表，并对打卡信息详细信息进行详情、修改或删除操作；如图5-19所示。

![](/images/0400stringboot/0402springboot/blog.027.png)

图5-19打卡信息管理界面图

交流论坛管理；在交流论坛页面输入帖子标题进行查询或删除交流论坛列表，并对交流论坛详细信息进行详情、修改、查看评论或删除操作；如图5-20所示。

![](/images/0400stringboot/0402springboot/blog.028.png)

图5-20交流论坛管理界面图

系统管理管理；在系统简介页面输入标题进行查询系统简介列表，并对系统简介详细信息进行详情或修改操作，还可以对轮播图和关于我们进行详细操作；如图5-21所示。

![](/images/0400stringboot/0402springboot/blog.029.png)

图5-21系统管理界面图

### 5.2.2用户模块实现
用户登录进入系统后可以查看到系统首页、个人中心、在线测评管理、打卡信息管理等功能进行详细操作，如图5-22所示。

![](/images/0400stringboot/0402springboot/blog.030.png)

图5-22用户功能界面图

## 5.3　本章小结
第五章主要内容是系统实现，首先实现了本系统中最重要的前台功能，其次分别实现了对管理员功能的管理和对用户的管理，完成了系统全部功能设计。












