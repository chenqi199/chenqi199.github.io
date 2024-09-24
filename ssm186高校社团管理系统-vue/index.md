# ssm186高校社团管理系统+vue


# [项目清单 包安装运行](http://chenqi1990.site) 官网地址 http://chenqi1990.site

# [ssm186高校社团管理系统+vue](https://github.com/GraduationProject-springboot/)

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### [github 项目仓库](https://github.com/GraduationProject-springboot/allSpringbootProjects) 开源仅有后端代码

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1T48XecE9G?p=180)

# 系统概述
进过系统的分析后，就开始记性系统的设计，系统设计包含总体设计和详细设计。总体设计只是一个大体的设计，经过了总体设计，我们能够划分出系统的一些东西，例如文件、文档、数据等。而且我们通过总体设计，大致可以划分出了程序的模块，以及功能。但是只是一个初步的分类，并没有真正的实现。

整体设计，只是一个初步设计，而且，对于一个项目，我们可以进行多个整体设计，通过对比，包括性能的对比、成本的对比、效益的对比，来最终确定一个最优的设计方案，选择优秀的整体设计可以降低开发成本，增加公司效益，从这一点来讲，整体设计还是非常重要的。

高校社团管理系统工作原理图如图4-1所示：

![](/images/0100ssm/ssm186/blog.013.png)

图4-1 系统工作原理图
## 4.2 系统结构设计
系统架构图属于系统设计阶段，系统架构图只是这个阶段一个产物，系统的总体架构决定了整个系统的模式，是系统的基础。高校社团管理系统的整体结构设计如图4-2所示。

![](/images/0100ssm/ssm186/blog.014.png)

图4-2 系统结构图
## 4.3数据库设计
数据库是计算机信息系统的基础。目前，电脑系统的关键与核心部分就是数据库。数据库开发的优劣对整个系统的质量和速度有着直接影响。
### 4.3.1 数据库设计原则
数据库的概念结构设计采用实体—联系（E-R）模型设计方法。E-R模型法的组成元素有：实体、属性、联系，E-R模型用E-R图表示，是提示用户工作环境中所涉及的事物，属性则是对实体特性的描述。在系统设计当中数据库起着决定性的因素。下面设计出这几个关键实体的实体—关系图。
### 4.3.2 数据库实体
数据模型中的实体（Entity），也称为实例，对应现实世界中可区别于其他对象的“事件”或“事物”。例如，公司中的每个员工，家里中的每个家具。

本系统的E-R图如下图所示：

1、学生信息实体图如图4-3所示：

![](/images/0100ssm/ssm186/blog.015.png)

图4-3学生信息实体图

2、社团活动信息实体图如图4-4所示：

![](/images/0100ssm/ssm186/blog.016.png)

`       `图4-4社团活动信息实体图

3、活动参与信息实体图如图4-5所示：

![](/images/0100ssm/ssm186/blog.017.png)

`     `图4-5活动参与信息实体图
###
### 4.3.3 数据库表设计
数据库的表信息属于设计的一部分，下面介绍数据库中的各个表的详细信息。

表4-1 huiyuan表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|int|11|NOT NULL|
|addtime|varchar|200|default NULL|
|xuehao|varchar|200|default NULL|
|mima|varchar|200|default NULL|
|xingming|varchar|200|default NULL|
|xingbie|varchar|200|default NULL|
|nianling|varchar|200|default NULL|
|dianhua|varchar|200|default NULL|
|youxiang|varchar|200|default NULL|
|shenfenzheng|varchar|200|default NULL|
|zhaopian|varchar|200|default NULL|


`  `表4-2 huodongcanyu表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|int|11|NOT NULL|
|addtime|varchar|200|default NULL|
|huodongmingcheng|varchar|200|default NULL|
|huodongleixing|varchar|200|default NULL|
|zhaopian|varchar|200|default NULL|
|jubanriqi|varchar|200|default NULL|
|jubanshetuan|varchar|200|default NULL|
|huodongdidian|varchar|200|default NULL|
|canyushijian|varchar|200|default NULL|
|xuehao|varchar|200|default NULL|
|xingming|varchar|200|default NULL|
|sfsh|varchar|200|default NULL|
|shhf|varchar|200|default NULL|

表4-3：shetuanhuodong表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|` `int|11|NOT NULL |
|addtime|varchar|200|default NULL|
|huodongmingcheng|varchar|200|default NULL|
|huodongleixing|varchar|200|default NULL|
|zhaopian|varchar|200|default NULL|
|`      `jubanriqi|varchar|200|default NULL|
|jubanshetuan|varchar|200|default NULL|
|huodongdidian|varchar|200|default NULL|
|huodongshizhang|varchar|200|default NULL|
|huodongneirong|varchar|200|default NULL|


表4-4：shetuanshenqingxinxi表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|` `int|11|NOT NULL |
|addtime|varchar|200|default NULL|
|shetuanmingcheng|varchar|200|default NULL|
|shetuantupian|varchar|200|default NULL|
|shetuanleibie|varchar|200|default NULL|
|shenqingshijian|varchar|200|default NULL|
|xuehao|varchar|200|default NULL|
|xingming|varchar|200|default NULL|
|shenqingliyou|varchar|200|default NULL|
|sfsh|varchar|200|default NULL|
|shhf|varchar|200|default NULL|

表4-5：xuesheng表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|` `int|11|NOT NULL |
|addtime|varchar|200|default NULL|
|xuehao|varchar|200|default NULL|
|mima|varchar|200|default NULL|
|xingming|varchar|200|default NULL|
|xingbie|varchar|200|default NULL|
|nianling|varchar|200|default NULL|
|dianhua|varchar|200|default NULL|
|youxiang|varchar|200|default NULL|
|shenfenzheng|varchar|200|default NULL|
|zhaopian|varchar|200|default NULL|

#########
# 5系统界面实现
## 5.1 管理员登录
管理员输入个人的用户名、密码和角色登录系统，这时候系统的数据库就会在进行查找相关的信息，如果我们输入的用户名、密码和角色不正确，数据库就会提示出错误的信息提示，同时会提示管理员重新输入自己的用户名、密码、角色，直到账号密码输入成功后，会提登录成功的信息。管理员登录效果图如图5-1所示：

![](/images/0100ssm/ssm186/blog.018.png)     
图5-1管理员登录界面图

## 5.2  管理员功能模块     
### 5.2.1 管理员功能
管理员在高校社团管理系统页面可以查看首页、个人中心、学生管理、社团申请信息管理、校园社团管理、社团活动管理、会员管理、活动参与管理、会员申请管理、系统管理等。程序成效图如下图5-2所示:

![](/images/0100ssm/ssm186/blog.019.png)

图5-2管理员功能界面图
### 5.2.2学生管理
管理员对学生管理进行查看学号、姓名、性别、年龄、电话、邮箱、身份证、照片等信息并可以进行详情、删除、修改操作。程序效果图如下图5-3所示：

![](/images/0100ssm/ssm186/blog.020.png)

图5-3学生管理界面图
### 5.2.3 社团申请信息管理
管理员对社团申请信息管理进行查看社团名称、社团图片、社团类别、申请时间、学号、姓名、审核回复、审核状态、审核等信息并可以进行详情、删除操作。程序效果图如下图5-4所示：

![](/images/0100ssm/ssm186/blog.021.png) 

图5-4社团申请信息管理界面图

### 5.2.4校园社团管理
管理员对校园社团管理进行查看社团名称、社团图片、成立时间、社团类别、社团人数等信息进行详情、删除、修改操作。程序效果图如下图5-5所示：

![](/images/0100ssm/ssm186/blog.022.png)

图5-5校园社团管理界面图
### 5.2.5社团活动管理
管理员对社团活动管理进行查看活动名称、活动类型、照片、举办日期、举办社团、活动地点、活动时长等信息并可以进行详情、删除、修改操作。程序效果图如下图5-6所示：

![](/images/0100ssm/ssm186/blog.023.png) 

图5-6社团活动管理界面
### 5.2.6会员管理
管理员对会员管理进行查看学号、姓名、性别、年龄、电话、邮箱、身份证、照片等信息并可以进行详情、删除、修改操作。程序效果图如下图5-7所示：

![](/images/0100ssm/ssm186/blog.024.png) 

图5-7会员管理界面图


### 5.2.7轮播图
轮播图；该页面为轮播图管理界面。管理员可以在此页面进行首页轮播图的管理，通过新建操作可在轮播图中加入新的图片，还可以对以上传的图片进行修改操作，以及图片的删除操作。程序效果图如下图5-8所示：

![](/images/0100ssm/ssm186/blog.025.png) 

图5-8轮播图管理界面图




## 5.3 前台首页功能模块
学生在高校社团管理系统页面可以查看首页、社团申请信息、校园社团、社团活动、活动参与、会员申请、校园资讯、个人中心、后台管理、在线资讯等功能。程序效果图如下图5-9所示：

![](/images/0100ssm/ssm186/blog.026.png)

图5-9前台首页功能界面图
## 5.3.1学生注册、学生登录
学生在线填写学号、密码、姓名、年龄、电话、邮箱、身份证等信息进行注册、登录操作。程序效果图如下图5-10所示：

![](/images/0100ssm/ssm186/blog.027.png)

![](/images/0100ssm/ssm186/blog.028.png)

图5-10学生登录、学生注册界面图
## 5.3.2校园社团
学生进入校园社团页面可以查看社团名称、社团图片、成立时间、社团类别、社团人数等信息，并可以进行加入社团操作。程序效果图如下图5-11所示：

![](/images/0100ssm/ssm186/blog.029.png)


图5-11校园社团界面图
## 5.3.3社团活动
学生进入社团活动页面可以查看活动名称、活动类型、照片、举办日期、举办社团、活动地点、活动时长等信息进行报名参加操作。程序效果图如下图5-12所示：

![](/images/0100ssm/ssm186/blog.030.png)

图5-12社团活动界面图

## 5.3.4活动参与
学生进入活动参与页面可以查看活动名称、活动类型、照片、举办日期、举办社团、活动地点、参与时间、学号、姓名等信息进行提交操作。程序效果图如下图5-13所示：

![](/images/0100ssm/ssm186/blog.031.png)

图5-13活动参与界面图


## 5.4 会员功能模块

## 5.4.1会员功能
会员在高校社团管理系统页面可以查看首页、个人中心、社团申请信息管理、校园社团管理、社团活动管理、活动参与管理等功能。程序效果图如下图5-14所示：

![](/images/0100ssm/ssm186/blog.032.png)

图5-14会员功能界面图
## 5.4.2社团申请信息管理
会员进入社团申请信息管理页面可以查看社团名称、社团图片、社团类别、申请时间、学号、姓名、审核回复、审核状态等信息并可以进行详情、修改、删除等操作。程序效果图如下图5-15所示：

![](/images/0100ssm/ssm186/blog.033.png)

图5-15社团申请信息管理界面图


## 5.5 学生功能模块

## 5.5.1学生功能
学生在高校社团管理系统页面可以查看首页、个人中心、校园社团管理、社团活动管理、会员申请管理等功能。程序效果图如下图5-16所示：

![](/images/0100ssm/ssm186/blog.034.png)

图5-16学生功能界面图














