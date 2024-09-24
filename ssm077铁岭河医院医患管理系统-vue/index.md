# ssm077铁岭河医院医患管理系统+vue


# [项目清单 包安装运行](http://chenqi1990.site) 官网地址 http://chenqi1990.site

# [ssm077铁岭河医院医患管理系统+vue](https://github.com/GraduationProject-springboot/)

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### [github 项目仓库](https://github.com/GraduationProject-springboot/allSpringbootProjects) 开源仅有后端代码

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1T48XecE9G?p=75)

# 系统概述
进过系统的分析后，就开始记性系统的设计，系统设计包含总体设计和详细设计。总体设计只是一个大体的设计，经过了总体设计，我们能够划分出系统的一些东西，例如文件、文档、数据等。而且我们通过总体设计，大致可以划分出了程序的模块，以及功能。但是只是一个初步的分类，并没有真正的实现。

整体设计，只是一个初步设计，而且，对于一个项目，我们可以进行多个整体设计，通过对比，包括性能的对比、成本的对比、效益的对比，来最终确定一个最优的设计方案，选择优秀的整体设计可以降低开发成本，增加公司效益，从这一点来讲，整体设计还是非常重要的。

医院医患管理系统工作原理图如图4-1所示：

![](/images/0000ssm/ssm077/blog.012.png)

图4-1 系统工作原理图
## 4.2 系统结构设计
系统架构图属于系统设计阶段，系统架构图只是这个阶段一个产物，系统的总体架构决定了整个系统的模式，是系统的基础。医院医患管理系统的整体结构设计如图4-2所示。

![](/images/0000ssm/ssm077/blog.013.png)

图4-2 系统结构图
## 4.3数据库设计
数据库是计算机信息系统的基础。目前，电脑系统的关键与核心部分就是数据库。数据库开发的优劣对整个系统的质量和速度有着直接影响。
### 4.3.1 数据库设计原则
数据库的概念结构设计采用实体—联系（E-R）模型设计方法。E-R模型法的组成元素有：实体、属性、联系，E-R模型用E-R图表示，是提示用户工作环境中所涉及的事物，属性则是对实体特性的描述。在系统设计当中数据库起着决定性的因素。下面设计出这几个关键实体的实体—关系图。
### 4.3.2 数据库实体
数据模型中的实体（Entity），也称为实例，对应现实世界中可区别于其他对象的“事件”或“事物”。例如，公司中的每个员工，家里中的每个家具。

本系统的E-R图如下图所示：

1、用户管理实体图如图4-3所示：

![](/images/0000ssm/ssm077/blog.014.png)

图4-3用户管理实体图

2、挂号收费管理实体图如图4-4所示：

![](/images/0000ssm/ssm077/blog.015.png)

`       `图4-4挂号收费管理系统实体图

3、病史内容管理实体图如图4-5所示：

![](/images/0000ssm/ssm077/blog.016.png)

`     `图4-5病史内容管理实体图
#########
4、建议和注意事项管理实体图如图4-6所示：

![](/images/0000ssm/ssm077/blog.017.png)

`       `图4-6建议和注意事项管理实体图

### 4.3.3 数据库表设计
数据库的表信息属于设计的一部分，下面介绍数据库中的各个表的详细信息。

表4-1 allusers表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|int|11|NOT NULL|
|username|varchar|50|` `default NULL|
|pwd|varchar|50|` `default NULL|
|cx|varchar|50|` `default NULL|


表4-2 bingshineirong表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|int|11|NOT NULL|
|addtime|varchar|50|default NULL|
|zhusu|varchar|50|default NULL|
|xianbingshi|varchar|50|default NULL|
|jiwangbingshi|varchar|50|default NULL|
|guominshi|varchar|50|default NULL|

表4-3：caiwuguanli表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|` `int|11|NOT NULL |
|addtime|varchar|50|default NULL|
|yishenggongzuoliang|varchar|50|default NULL|
|keshigongzuoliang|varchar|50|default NULL|
|rijiefeiyong|varchar|50|default NULL|


表4-4：guahaoshoufei表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|` `int|11|NOT NULL |
|addtime|varchar|50|default NULL|
|zhanghao|varchar|50|default NULL|
|mima|varchar|50|default NULL|
|xianchangguahao|varchar|50|default NULL|
|rijie|varchar|50|default NULL|
|tuihao|varchar|50|default NULL|
|shoufei|varchar|50|default NULL|
|tuifei|varchar|50|default NULL|
|huanzhefeiyongmingxi|varchar|50|default NULL|

表4-5：jianyihezhuyishixiang表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|` `int|11|NOT NULL |
|addtime|varchar|50|default NULL|
|jianchajianyi|varchar|50|default NULL|
|zhuyishixiang|varchar|50|default NULL|
|chuliyijian|varchar|50|default NULL|
|zhenduanjieguo|varchar|50|default NULL|

表4-6：yonghu表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|` `int|11|NOT NULL |
|addtime|varchar|50|default NULL|
|zhanghao|varchar|50|default NULL|
|mima|varchar|50|default NULL|
|xingbie|varchar|50|default NULL|
|xingming|varchar|50|default NULL|
|keshi|varchar|50|default NULL|
|zhicheng|varchar|50|default NULL|
|nianling|varchar|50|default NULL|




# 5系统界面实现
## 5.1 管理员登录
管理员输入个人的用户名、密码和角色登录系统，这时候系统的数据库就会在进行查找相关的信息，如果我们输入的用户名、密码和角色不正确，数据库就会提示出错误的信息提示，同时会提示管理员重新输入自己的用户名、密码、角色，直到账号密码输入成功后，会提登录成功的信息。网站管理员登录效果图如图5-1所示：

![](/images/0000ssm/ssm077/blog.018.png)     
图5-1管理员登录界面

## 5.2  管理员功能模块     
### 5.2.1 用户管理
管理员对用户管理进行编辑填写账号、性别、姓名、科室、职称、年龄并进行详情、删除、修改等操作。程序成效图如下图5-2所示:

![](/images/0000ssm/ssm077/blog.019.png)

图5-2用户管理界面图
### 5.2.2 病史内容管理
管理员对病史内容管理进行编辑主诉、现病史、既往病史、过敏史等操作并可以进行详情、删除、修改操作。程序效果图如下图5-3所示：

![](/images/0000ssm/ssm077/blog.020.png)

图5-3病史内容管理界面
### 5.2.3 评估诊断管理
管理员对评估诊断管理进行编辑西医诊断、中医诊断等操作并可以进行详情、删除、修改操作。程序效果图如下图5-4所示：

![](/images/0000ssm/ssm077/blog.021.png) 

图5-4评估诊断管理界面

### 5.2.4建议和注意事项管理
管理员对建议和注意事项管理进行填写检查建议、注意事项、处理意见、诊断结果等进行详情、删除、修改操作。程序效果图如下图5-5所示：

![](/images/0000ssm/ssm077/blog.022.png)

图5-5建议和注意事项管理界面
### 5.2.5挂号收费管理
管理员对挂号收费管理进行编辑账号、密码、现场挂号、日结、退号、收费、退费、患者费用明细等操作并可以进行详情、删除、修改操作。程序效果图如下图5-6所示：

![](/images/0000ssm/ssm077/blog.023.png) 

图5-6挂号收费管理界面
### 5.2.6药房管理
管理员对药房管理进行编辑发药、退药等信息并可以进行详情、删除、修改操作。程序效果图如下图5-7所示：

![](/images/0000ssm/ssm077/blog.024.png) 

图5-7药房管理界面

### 5.2.7留言板管理
管理员对留言板管理进行编辑用户名、留言内容、回复内容等信息并可以进行详情、删除、修改操作。程序效果图如下图5-8所示：

![](/images/0000ssm/ssm077/blog.025.png) 

图5-8留言板管理界面




## 5.3 前台首页功能模块
前台首页详情页面：首页、建议和注意事项、轮播图管理、网站资讯、留言板管理、留言反馈、个人中心、后台管理等功能操作。程序效果图如下图5-9所示：

![](/images/0000ssm/ssm077/blog.026.png)

图5-9前台首页功能界面
## 5.3.1 用户登录、用户注册
用户在线填写账号、性别、姓名、科室、职称、年龄等信息进行注册、登录操作。程序效果图如下图5-10所示：

![](/images/0000ssm/ssm077/blog.027.png)

![](/images/0000ssm/ssm077/blog.028.png)

图5-10用户登录、用户注册界面
## 5.3.2留言反馈
用户进入留言反馈可以填写内容等信息，并可以进行提交操作。程序效果图如下图5-11所示：

![](/images/0000ssm/ssm077/blog.029.png)


图5-11留言反馈界面
## 5.3.3个人中心
用户进入个人中心可以填写账号、性别、姓名、科室、职称、年龄进行更新信息、退出登录操作。程序效果图如下图5-12所示：

![](/images/0000ssm/ssm077/blog.030.png)

图5-12个人中心界面

## 5.4 用户功能模块

## 5.4.1用户管理
用户进入用户管理可以查看账号、性别、姓名、科室、职称、年龄等操作。程序效果图如下图5-13所示：

![](/images/0000ssm/ssm077/blog.031.png)

图5-13用户管理界面
## 5.4.2病史内容管理
用户进入病史内容管理可以填写主诉、现病史、既往病史、过敏史并可以进行详情、删除等操作。程序效果图如下图5-14所示：

![](/images/0000ssm/ssm077/blog.032.png)

图5-14病史内容管理界面

## 5.4.3挂号收费管理
用户进入挂号收费管理可以填写账号、密码、现场挂号、日结、退号、收费、退费、患者费用明细并可以进行详情、删除等操作。程序效果图如下图5-15所示：

![](/images/0000ssm/ssm077/blog.033.png)

图5-15挂号收费管理界面














