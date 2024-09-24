# ssm272基于VUE的新闻类网站+vue修改完的


# [项目清单 包安装运行](http://chenqi1990.site) 官网地址 http://chenqi1990.site

# [ssm272基于VUE的新闻类网站+vue修改完的](https://github.com/GraduationProject-springboot/)

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### [github 项目仓库](https://github.com/GraduationProject-springboot/allSpringbootProjects) 开源仅有后端代码

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1gn8XeNE2J?p=70)

# 系统概述
进过系统的分析后，就开始记性系统的设计，系统设计包含总体设计和详细设计。总体设计只是一个大体的设计，经过了总体设计，我们能够划分出系统的一些东西，例如文件、文档、数据等。而且我们通过总体设计，大致可以划分出了程序的模块，以及功能。但是只是一个初步的分类，并没有真正的实现。

整体设计，只是一个初步设计，而且，对于一个项目，我们可以进行多个整体设计，通过对比，包括性能的对比、成本的对比、效益的对比，来最终确定一个最优的设计方案，选择优秀的整体设计可以降低开发成本，增加公司效益，从这一点来讲，整体设计还是非常重要的。

新闻类网站工作原理图如图4-1所示：

![](/images/0200ssm/ssm272/blog.012.png)

图4-1 系统工作原理图
## 4.2 系统结构设计
系统架构图属于系统设计阶段，系统架构图只是这个阶段一个产物，系统的总体架构决定了整个系统的模式，是系统的基础。新闻类网站的整体结构设计如图4-2所示。

![](/images/0200ssm/ssm272/blog.013.png)

图4-2 系统结构图
## 4.3数据库设计
数据库是计算机信息系统的基础。目前，电脑系统的关键与核心部分就是数据库。数据库开发的优劣对整个系统的质量和速度有着直接影响。
### 4.3.1 数据库设计原则
数据库的概念结构设计采用实体—联系（E-R）模型设计方法。E-R模型法的组成元素有：实体、属性、联系，E-R模型用E-R图表示，是提示用户工作环境中所涉及的事物，属性则是对实体特性的描述。在系统设计当中数据库起着决定性的因素。下面设计出这几个关键实体的实体—关系图。
### 4.3.2 数据库实体
数据模型中的实体（Entity），也称为实例，对应现实世界中可区别于其他对象的“事件”或“事物”。例如，公司中的每个员工，家里中的每个家具。

本系统的E-R图如下图所示：

1、新闻信息实体图如图4-3所示：

![](/images/0200ssm/ssm272/blog.014.png)

图4-3新闻信息实体图

2、用户信息实体图如图4-4所示：

![](/images/0200ssm/ssm272/blog.015.png)

图4-4用户信息实体图

3、用户分享信息实体图如图4-5所示：

![](/images/0200ssm/ssm272/blog.016.png)

`     `图4-5用户分享信息实体图
### 4.3.3 数据库表设计
数据库的表信息属于设计的一部分，下面介绍数据库中的各个表的详细信息。

表4-1 allusers表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|int|11|NOT NULL|
|username|varchar|50|` `default NULL|
|pwd|varchar|50|` `default NULL|
|cx|varchar|50|` `default NULL|


表4-2 xinwenxinxi表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|int|11|NOT NULL|
|addtime|varchar|50|default NULL|
|xinwenbiaoti|varchar|50|default NULL|
|xinwenleibie|varchar|50|default NULL|
|xinwendiqu|varchar|50|default NULL|
|xinwentupian|varchar|50|default NULL|
|xinwenshipin|varchar|50|default NULL|
|xinwenxiangqing|varchar|50|default NULL|
|faburiqi|varchar|50|default NULL|

表4-3：yonghu表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|` `int|11|NOT NULL |
|addtime|varchar|50|default NULL|
|yonghuming|varchar|50|default NULL|
|mima|varchar|50|default NULL|
|xingming|varchar|50|default NULL|
|`      `xingbie|varchar|50|default NULL|
|touxiang|varchar|50|default NULL|
|`     `shouji|varchar|50|default NULL|
|`     `youxiang|varchar|50|default NULL|
|sfsh|varchar|50|default NULL|
|shhf|varchar|50|default NULL|


表4-4：yonghufenxiang表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|` `int|11|NOT NULL |
|addtime|varchar|50|default NULL|
|fenxiangbiaoti|varchar|50|default NULL|
|fenxiangleixing|varchar|50|default NULL|
|fenxiangtupian|varchar|50|default NULL|
|fenxiangshipin|varchar|50|default NULL|
|fenxiangriqi|varchar|50|default NULL|
|fenxiangneirong|varchar|50|default NULL|
|yonghuming|varchar|50|default NULL|
|youxiang|varchar|50|default NULL|
|sfsh|varchar|50|default NULL|
|shhf|varchar|50|default NULL|

表4-5：xinwenleibie表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|` `int|11|NOT NULL |
|addtime|varchar|50|default NULL|
|xinwenleibie|varchar|50|default NULL|

#########
# 5系统界面实现
## 5.1 管理员登录
管理员输入个人的用户名、密码和角色登录系统，这时候系统的数据库就会在进行查找相关的信息，如果我们输入的用户名、密码和角色不正确，数据库就会提示出错误的信息提示，同时会提示管理员重新输入自己的用户名、密码、角色，直到用户名、密码输入成功后，会提登录成功的信息。网站管理员登录效果图如图5-1所示：

![](/images/0200ssm/ssm272/blog.017.png)     
图5-1管理员登录界面

## 5.2  管理员功能模块     
### 5.2.1 用户管理
管理员对用户管理进行查看用户名、姓名、性别、头像、手机、邮箱、审核回复、审核状态、审核并进行详情、删除、修改等操作。程序成效图如下图5-2所示:

![](/images/0200ssm/ssm272/blog.018.png)

图5-2用户管理界面图
### 5.2.2新闻类别管理
管理员对新闻类别管理进行查看新闻类别等信息并可以进行删除、修改操作。程序效果图如下图5-3所示：

![](/images/0200ssm/ssm272/blog.019.png)

图5-3新闻类别管理界面
### 5.2.3 新闻信息管理
管理员对新闻信息管理进行查看新闻标题、新闻类别、新闻地区、新闻图片、新闻视频、发布日期等信息并可以进行详情、删除、修改操作。程序效果图如下图5-4所示：

![](/images/0200ssm/ssm272/blog.020.png) 

图5-4新闻信息管理界面

### 5.2.4 轮播图管理
轮播图；该页面为轮播图管理界面。管理员可以在此页面进行首页轮播图的管理，通过新建操作可在轮播图中加入新的图片，还可以对以上传的图片进行修改操作，以及图片的删除操作。程序效果图如下图5-5所示：

![](/images/0200ssm/ssm272/blog.021.png)

图5-5轮播图管理界面
### 5.2.5用户分享管理
管理员对用户分享管理进行查看分享标题、分享类型、分享图片、分享视频、分享日期、用户名、邮箱、审核回复、审核状态、审核等进行详情、删除、修改操作。程序效果图如下图5-6所示：

![](/images/0200ssm/ssm272/blog.022.png)

图5-6用户分享管理界面
### 5.2.6公告信息
管理员对公告信息进行查看标题、图片等信息并可以进行详情、删除、修改操作。程序效果图如下图5-7所示：

![](/images/0200ssm/ssm272/blog.023.png) 

图5-7公告信息界面

## 5.3 前台首页功能模块
前台首页详情页面查看首页、新闻信息、用户分享、公告信息、个人中心、后台管理等功能操作。程序效果图如下图5-8所示：

![](/images/0200ssm/ssm272/blog.024.png)

图5-8前台首页功能界面
## 5.3.1用户注册、用户登录
用户在线填写用户名、密码、姓名、手机、邮箱等信息进行注册、登录操作。程序效果图如下图5-9所示：

![](/images/0200ssm/ssm272/blog.025.png)

![](/images/0200ssm/ssm272/blog.026.png)

图5-9用户注册、用户登录界面
## 5.3.2新闻信息
用户进入新闻信息可以查看新闻标题、新闻类别、新闻地区、新闻图片、新闻视频、发布日期、点击次数等信息，并可以进行点我收藏操作。程序效果图如下图5-10所示：

![](/images/0200ssm/ssm272/blog.027.png)


图5-10新闻信息界面
## 5.3.3个人中心
用户进入个人中心可以填写用户名、密码、姓名、性别、头像、手机、邮箱等信息进行更新信息、退出登录操作。程序效果图如下图5-11所示：

![](/images/0200ssm/ssm272/blog.028.png)

图5-11个人中心界面

## 5.4 用户功能模块

## 5.4.1个人信息
用户进入个人信息可以填写用户名、姓名、性别、头像、手机、邮箱等信息进行修改。程序效果图如下图5-12所示：

![](/images/0200ssm/ssm272/blog.029.png)

图5-12个人信息界面
## 5.4.2用户分享管理
用户进入用户分享管理可以查看分享标题、分享类型、分享图片、分享视频、分享日期、用户名、邮箱、审核回复、审核状态并可以进行详情、修改、删除等操作。程序效果图如下图5-13所示：

![](/images/0200ssm/ssm272/blog.030.png)

图5-13用户分享管理界面












