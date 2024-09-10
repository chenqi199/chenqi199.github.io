# 0614springboot旅游出行指南_655ms--论文


# [0614springboot旅游出行指南_655ms--论文](https://github.com/GraduationProject-springboot/0614springboot)

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

# [项目清单](https://chenqi1990.site) 包安装运行

### [github 项目仓库](https://github.com/GraduationProject-springboot/allSpringbootProjects) 开源仅有后端代码

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1eMbYemE1U?p=110)


# 系统概述
该系统由个人管理员和用户两部分组成。其中：用户进入系统首页可以实现首页，景点信息，酒店信息，餐厅信息，交通路线，旅行日记，公告信息，后台管理，个人中心等；管理员则是根据不同需求设置了不同功能，可以通过后台管理接口管理用户信息。
## 3.2 需求分析
需求分析，也称为软件需求分析、系统需求分析或需求分析工程，是指开发人员经过充分的研究和分析，准确地理解用户和项目在功能、性能、可靠性等方面的具体需求，并将用户的非正式需求表述转化为确定系统必须执行的需求的完整定义的过程[11]。

功能需求分析是系统设计的前提，它要求开发者和用户定义开发什么样的体系和系统需要什么样的功能。本文主要介绍了一种基于windows平台实现的旅游出行指南。该系统为用户找到景点信息和酒店信息提供了更安全、更高效、更便捷的途径。本系统有两个角色：管理员和用户，要求具备以下功能：

（1）用户可以浏览主页了解旅游出行信息，并进行酒店预订和景点购票等操作；

（2）管理员通过后台管理员界面，实现对用户信息管理，或发布系统公告，让用户实时知道最新的旅游出行信息；
## 3.3 可行性分析
可行性分析是指通过比较项目的主要内容和支撑条件，如市场需求、资源供应、环境影响、资金筹措情况、盈利能力等，预测项目建成后可能产生的资金、经济效益、社会和环境影响，为项目决策提供依据的综合性系统分析方法。可行性研究报告编制的质量直接影响着投资决策的成，而可行性研究报告编制程序又决定了可行性研究报告能否得到有效执行。因此，必须重视可行性研究工作，提高其编制水平。可行性分析应当具有预见性、公正性、可靠性和科学性[13]。
### 3.3.1 技术可行性分析 
本系统是为了为用户寻找旅游出行提供更加安全、高效、便捷的方式，本系统需要运用到Java、MySQL、springboot、B/S结构等技术，这些技术在国内外已经非常成熟[14]，在大学期间也有所涉及，相关的知识和工具在网络上也可以查到，再加上老师的指导，在技术上的难题可以得到解决。
### 3.3.2 经济可行性分析
该系统的主题是基于springboot的旅游出行指南的设计与实现。开发所需的软件资源是Eclipse。我们可以在它的网站上安装一个免费的版本，这对我们的开发和使用是足够好的。数据库就是MySQL数据库。是开源是免费的，服务器使用Tomcat服务器，浏览器使用日常IE浏览器，springboot框架是开源的。经过可行性评估，软件资源支出符合经济可行性[15]。硬件方面，配备齐全的笔记本电脑作为工具在经济上是可行的。
## 3.4 系统用例分析
旅游出行指南综合网络空间开发设计要求。目的是将旅游出行指南从传统管理方式转换为在网上管理，完成旅游出行信息管理的方便快捷、安全性高、交易规范做了保障，目标明确。旅游出行指南可以将功能划分为管理员功能和用户功能。

（1）、管理员关键功能包含系统首页，个人中心，用户管理，天气预报管理，景点信息管理，门票预订管理，酒店信息管理，酒店预订管理，餐厅信息管理，餐厅预订管理，交通路线管理，旅行日记管理，旅游规划管理，系统管理等进行管理。管理员用例如下：

![](/images/0600stringboot/0614springboot/blog.003.png)

图3-1 管理员用例图

（2）、用户关键功能包含系统首页，个人中心，门票预订管理，酒店预订管理，餐厅预订管理，旅行日记管理，旅游规划管理等进行管理。用户用例如下：

![](/images/0600stringboot/0614springboot/blog.004.png)

图3-2 用户用例图

## 3.5系统流程分析
### 3.5.1 用户登录流程
要想利用这个软件来进行系统的安全管理，首先需要登录到该软件中。如图3-3所示。

![](/images/0600stringboot/0614springboot/blog.005.png)

图3-3登录流程图
### 3.5.2 添加信息流程
管理员可以添加信息，用户添加可以自己权限内的信息，输入信息后，要想利用这个软件来进行系统的安全管理，首先需要登录到该软件中。添加信息流程如图3-4所示。

![](/images/0600stringboot/0614springboot/blog.006.png)

图3-4添加信息流程图

### 3.5.3 修改信息流程
管理员可以修改旅游出行信息，用户可以修改自己权限内的信息，首先进入修改信息界面，输入需要修改信息，在系统进行判定为正确和合规后修改成功，并将数据更新至数据库。信息不合法则修改失败，重新输入。修改信息流程图如图3-5所示。

![](/images/0600stringboot/0614springboot/blog.007.png)

图3-5修改信息流程图

### 3.5.4 删除信息流程
管理员可以删除旅游出行信息，点击删除按钮，系统会提示是否删除信息，点击确定，则信息被删除，数据库中的信息随之删除，删除信息流程图如图3-6所示。

![](/images/0600stringboot/0614springboot/blog.008.png)

图3-6 删除信息流程图

## 3.6本章小结
基于springboot的旅游出行指南从市场、技术、经济、功能等方面分析了系统的功能需求，可以满足用户的旅游出行管理需求，帮助用户安全、高效地找到合适的旅游出行信息，因此有必要对其进行课题研究。


# 第4章 系统设计
系统设计是将被设计对象划分为单个模块进行构建，各个模块相互支持，相互制约，它们的组合是一个完整的系统。通过系统设计，可以最大限度地满足系统的预期目标，明确软件开发的目的。
## 4.1 系统基本结构设计
本次系统采用springboot框架集进行开发，springboot框架是一款企业界主流的软件开发框架，其简化了开发流程，大大缩减了软件开发所需的时间提高了软件的响应速度。系统总体结构图如图4-1所示。

![](/images/0600stringboot/0614springboot/blog.009.png)

图4-1 系统总体结构图

## 4.2 数据库设计
数据库结构设计的好坏直接影响到旅游出行指南的效率和实现的效果。本系统的数据库采用MySQL数据库，MySQL是一种开放源代码的关系型数据库管理系统，使用最常见的数据库管理语言SQL进行数据库管理。
### 4.2.1 数据库E-R图设计
E-R图也可称为实体-联系图，其可以清楚的显示实体与实体之间的关系，是描述概念模型的有效方式，通过各实体间的关系方便数据库结构的设计。以下是本系统主要的实体属性图如下所示。

餐厅信息评论表实体如图4-2所示。

![](/images/0600stringboot/0614springboot/blog.010.png)

图4-2餐厅信息评论表实体属性图

旅游规划实体如图4-3所示。

![](/images/0600stringboot/0614springboot/blog.011.png)

图4-3旅游规划实体属性图

公告信息实体如图4-4所示。

![](/images/0600stringboot/0614springboot/blog.012.png)

图4-4公告信息实体属性图

旅行日记实体如图4-5所示。

![](/images/0600stringboot/0614springboot/blog.013.png)

图4-5旅行日记实体属性图

用户实体如图4-6所示。

![](/images/0600stringboot/0614springboot/blog.014.png)

图4-6用户实体属性图

### 4.2.2 数据库表设计
数据表是用来保存多种数据的表，它是所有数据库的核心对象，且对于软件开发有着不可替代的作用。其相关数据表如下：

表4-1：收藏表

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

表4-2：餐厅信息评论表

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

表4-3：旅游规划

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|mudedi|varchar|200|目的地|||
|chufashijian|datetime||出发时间|||
|yujitianshu|int||预计天数|||
|lvyouluxian|longtext|4294967295|旅游路线|||
|guihuaneirong|longtext|4294967295|规划内容|||
|zhanghao|varchar|200|账号|||
|xingming|varchar|200|姓名|||

表4-4：公告信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|title|varchar|200|标题|||
|introduction|longtext|4294967295|简介|||
|picture|longtext|4294967295|图片|||
|content|longtext|4294967295|内容|||

表4-5：配置文件

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|name|varchar|100|配置参数名称|||
|value|varchar|100|配置参数值|||

表4-6：旅行日记评论表

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

表4-8：酒店信息评论表

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

表4-10：景点信息评论表

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

表4-11：交通路线评论表

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

表4-12：旅行日记

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|lvxingdidian|varchar|200|旅行地点|||
|lvxingleixing|varchar|200|旅行类型|||
|lvxingtianshu|int||旅行天数|||
|lvxingneirong|longtext|4294967295|旅行内容|||
|lvxingtupian|longtext|4294967295|旅行图片|||
|zhanghao|varchar|200|账号|||
|xingming|varchar|200|姓名|||
|thumbsupnum|int||赞||0|
|crazilynum|int||踩||0|

表4-13：门票预订

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|jingdianmingcheng|varchar|200|景点名称|||
|jingdiandizhi|varchar|200|景点地址|||
|menpiaojiage|float||门票价格|||
|jingdiandengji|varchar|200|景点等级|||
|yudingshijian|datetime||预订时间|||
|beizhu|varchar|200|备注|||
|zhanghao|varchar|200|账号|||
|xingming|varchar|200|姓名|||
|shouji|varchar|200|手机|||
|ispay|varchar|200|是否支付||未支付|

表4-15：餐厅预订

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|cantingmingcheng|varchar|200|餐厅名称|||
|cantingdidian|varchar|200|餐厅地点|||
|yudingjiage|float||预订价格|||
|yudingshijian|datetime||预订时间|||
|yudingshuoming|varchar|200|预订说明|||
|zhanghao|varchar|200|账号|||
|xingming|varchar|200|姓名|||
|shouji|varchar|200|手机|||
|ispay|varchar|200|是否支付||未支付|

表4-16：酒店预订

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|jiudianmingcheng|varchar|200|酒店名称|||
|jiudianleixing|varchar|200|酒店类型|||
|jiudiandizhi|varchar|200|酒店地址|||
|fangjianleixing|varchar|200|房间类型|||
|yuyuejiage|float||预约价格|||
|yudingshijian|datetime||预订时间|||
|yudingshuoming|varchar|200|预订说明|||
|zhanghao|varchar|200|账号|||
|xingming|varchar|200|姓名|||
|shouji|varchar|200|手机|||
|ispay|varchar|200|是否支付||未支付|

表4-17：餐厅信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|cantingmingcheng|varchar|200|餐厅名称|||
|cantingdidian|varchar|200|餐厅地点|||
|renjunxiaofei|int||人均消费|||
|yudingjiage|int||预订价格|||
|cantingjieshao|longtext|4294967295|餐厅介绍|||
|cantingtupian|longtext|4294967295|餐厅图片|||
|thumbsupnum|int||赞||0|
|crazilynum|int||踩||0|
|clicktime|datetime||最近点击时间|||
|clicknum|int||点击次数||0|

表4-18：酒店信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|jiudianmingcheng|varchar|200|酒店名称|||
|jiudianleixing|varchar|200|酒店类型|||
|jiudiandizhi|varchar|200|酒店地址|||
|fangjianleixing|varchar|200|房间类型|||
|yuyuejiage|float||预约价格|||
|lianxidianhua|varchar|200|联系电话|||
|jiudianjieshao|longtext|4294967295|酒店介绍|||
|jiudiantupian|longtext|4294967295|酒店图片|||
|thumbsupnum|int||赞||0|
|crazilynum|int||踩||0|
|clicktime|datetime||最近点击时间|||
|clicknum|int||点击次数||0|

表4-19：景点信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|jingdianmingcheng|varchar|200|景点名称|||
|jingdiandizhi|varchar|200|景点地址|||
|jingdiandengji|varchar|200|景点等级|||
|menpiaojiage|int||门票价格|||
|jingdiandianhua|varchar|200|景点电话|||
|jingdianjieshao|longtext|4294967295|景点介绍|||
|jingdiantupian|longtext|4294967295|景点图片|||
|thumbsupnum|int||赞||0|
|crazilynum|int||踩||0|
|clicktime|datetime||最近点击时间|||
|clicknum|int||点击次数||0|

表4-20：交通路线

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|luxianmingcheng|varchar|200|路线名称|||
|luxianleixing|varchar|200|路线类型|||
|shifadi|varchar|200|始发地|||
|zhongdiandi|varchar|200|终点地|||
|quanchengjuli|varchar|200|全程距离|||
|luxianxiangqing|longtext|4294967295|路线详情|||
|luxiantupian|longtext|4294967295|路线图片|||

表4-21：用户

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|zhanghao|varchar|200|账号|||
|mima|varchar|200|密码|||
|xingming|varchar|200|姓名|||
|xingbie|varchar|200|性别|||
|nianling|int||年龄|||
|shouji|varchar|200|手机|||
|touxiang|longtext|4294967295|头像|||

表4-22：天气预报

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|chengshi|varchar|200|城市|||
|fengmian|longtext|4294967295|封面|||
|tianqi|varchar|200|天气|||
|qiwen|varchar|200|气温|||
|shidu|varchar|200|湿度|||
|fengxiang|varchar|200|风向|||
|fengsu|varchar|200|风速|||
|shiyichuxing|varchar|200|适宜出行|||
|chuanyituijian|varchar|200|穿衣推荐|||
|gengxinshijian|datetime||更新时间|||

## 4.3 本章小结
通过本章针对旅游出行指南功能的总体结构、E-R属性图和数据表的大概介绍，对在开发系统时所要涉及到的数据库进行简单设计，为下一章系统的实现做好铺垫。


# 第5章 系统实现
系统实现章节的主要内容主要是将系统分析和系统设计方案进行实现，按照各个系统角色进行功能介绍，系统实现就是一个真正开始编写的阶段，将前面的分析结果以及设计方案进行实现，最终做出一个符合用户需求的软件系统。
## 5.1系统前台实现
当人们打开系统的网址后，首先看到的就是首页界面。在这里，人们能够看到系统的导航条，通过导航条导航进入各功能展示页面进行操作。系统首页界面如图5-1所示：

![](/images/0600stringboot/0614springboot/blog.015.png)

图5-1 系统首页界面

景点信息：在景点信息页面可以输入景点名称和景点地址进行查询，可以查看到景点详细信息，并根据需要进行订门票、评论或收藏操作；景点信息页面如图5-2所示：

![](/images/0600stringboot/0614springboot/blog.016.png)

图5-2景点信息详细页面

酒店信息：在酒店信息页面的输入栏中输入酒店名称、酒店类型和选择房间类型进行查询，可以查看到酒店详细信息，并根据需要进行订酒店、评论或收藏操作；酒店信息页面如图5-3所示：

![](/images/0600stringboot/0614springboot/blog.017.png)

图5-3酒店信息详细页面

在个人中心页面输入个人信息可以进行更新操作，并根据需要对我的收藏进行详细操作；如图5-4所示：

![](/images/0600stringboot/0614springboot/blog.018.png)

图5-4 个人中心界面

## 5.2后台功能实现
后台登录，在登录页面选择需要登录的角色，并正确输入用户名和密码后，进入操作系统进行操作；如图5-5所示。 

![](/images/0600stringboot/0614springboot/blog.019.png)

图5-5 后台登录界面
### 5.2.1管理员模块实现
管理员进入主页面，主要功能包括对系统首页，个人中心，用户管理，天气预报管理，景点信息管理，门票预订管理，酒店信息管理，酒店预订管理，餐厅信息管理，餐厅预订管理，交通路线管理，旅行日记管理，旅游规划管理，系统管理等进行操作。管理员主页面如图5-6所示：

![](/images/0600stringboot/0614springboot/blog.020.png)

图5-6 管理员主界面

管理员点击用户管理。在用户页面输入账号和姓名进行查询、新增或删除用户信息列表，并根据需要对用户详情信息进行详情、修改或删除操作；如图5-7所示：

![](/images/0600stringboot/0614springboot/blog.021.png)

图5-7用户管理界面

管理员点击门票预订管理。在门票预订页面输入景点名称和景点地址进行查询或删除门票预订列表，并根据需要对门票预订详情信息进行详情或删除操作；如图5-8所示：

![](/images/0600stringboot/0614springboot/blog.022.png)

图5-8门票预订管理界面

管理员点击餐厅预订管理。在餐厅预订页面输入餐厅名称、姓名和手机进行查询或删除餐厅预订列表，并根据需要对餐厅预订详情信息进行详情或删除操作；如图5-9所示：

![](/images/0600stringboot/0614springboot/blog.023.png)

图5-9餐厅预订管理界面

管理员点击旅行日记管理。在旅行日记页面输入旅行地点和选择旅行类型进行查询或删除旅行日记列表，并根据需要对旅行日记详情信息进行详情、查看评论或删除操作；如图5-10所示：

![](/images/0600stringboot/0614springboot/blog.024.png)

图5-10旅行日记管理界面

管理员点击系统管理，进入系统管理页面可以对轮播图管理进行详情或修改操作，在公告信息页面输入标题可以查询，新增或删除公告信息列表，并根据需要对公告详情信息进行查看详情，修改和删除等操作。如图5-11所示：

![](/images/0600stringboot/0614springboot/blog.025.png)

图5-11系统管理界面

### 5.2.2用户模块实现
用户进入主页面，主要功能包括对系统首页，个人中心，门票预订管理，酒店预订管理，餐厅预订管理，旅行日记管理，旅游规划管理等进行操作。用户主页面如图5-12所示：

![](/images/0600stringboot/0614springboot/blog.026.png)

图5-12 用户主界面

用户点击门票预订管理。在门票预订页面输入景点名称和景点地址进行查询门票预订列表，并根据需要对门票预订详情信息进行详情操作；如图5-13所示：

![](/images/0600stringboot/0614springboot/blog.027.png)

图5-13门票预订管理界面













