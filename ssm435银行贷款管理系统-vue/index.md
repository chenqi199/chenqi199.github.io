# ssm435银行贷款管理系统+vue


# [项目清单 包安装运行](http://chenqi1990.site) 官网地址 http://chenqi1990.site

# [ssm435银行贷款管理系统+vue](https://github.com/GraduationProject-springboot/)

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### [github 项目仓库](https://github.com/GraduationProject-springboot/allSpringbootProjects) 开源仅有后端代码

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1t58veLEnL?p=33)

# 系统概述
进过系统的分析后，就开始记性系统的设计，系统设计包含总体设计和详细设计。总体设计只是一个大体的设计，经过了总体设计，我们能够划分出系统的一些东西，例如文件、文档、数据等。而且我们通过总体设计，大致可以划分出了程序的模块，以及功能。但是只是一个初步的分类，并没有真正的实现。

整体设计，只是一个初步设计，而且，对于一个项目，我们可以进行多个整体设计，通过对比，包括性能的对比、成本的对比、效益的对比，来最终确定一个最优的设计方案，选择优秀的整体设计可以降低开发成本，增加公司效益，从这一点来讲，整体设计还是非常重要的。

银行贷款管理系统工作原理图如图4-1所示：

![](/images/0400ssm/ssm435/blog.013.png)

图4-1 系统工作原理图
## 4.2 系统结构设计
系统架构图属于系统设计阶段，系统架构图只是这个阶段一个产物，系统的总体架构决定了整个系统的模式，是系统的基础。银行贷款管理系统的整体结构设计如图4-2所示。

![](/images/0400ssm/ssm435/blog.014.png)

图4-2 系统结构图
## 4.3数据库设计
数据库是计算机信息系统的基础。目前，电脑系统的关键与核心部分就是数据库。数据库开发的优劣对整个系统的质量和速度有着直接影响。
### 4.3.1 数据库设计原则
数据库的概念结构设计采用实体—联系（E-R）模型设计方法。E-R模型法的组成元素有：实体、属性、联系，E-R模型用E-R图表示，是提示用户工作环境中所涉及的事物，属性则是对实体特性的描述。在系统设计当中数据库起着决定性的因素。下面设计出这几个关键实体的实体—关系图。
### 4.3.2 数据库实体
数据模型中的实体（Entity），也称为实例，对应现实世界中可区别于其他对象的“事件”或“事物”。例如，公司中的每个员工，家里中的每个家具。

本系统的E-R图如下图所示：

1、还款信息实体图如图4-3所示：

![](/images/0400ssm/ssm435/blog.015.png)

图4-3还款信息实体图

2、通知信息实体图如图4-4所示：

![](/images/0400ssm/ssm435/blog.016.png)

`       `图4-4通知信息实体图

3、金额发布信息实体图如图4-5所示：

![](/images/0400ssm/ssm435/blog.017.png)

`     `图4-5金额发布信息实体图
#########

### 4.3.3 数据库表设计
数据库的表信息属于设计的一部分，下面介绍数据库中的各个表的详细信息。

表4-1 allusers表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|int|11|NOT NULL|
|username|varchar|50|` `default NULL|
|pwd|varchar|50|` `default NULL|
|cx|varchar|50|` `default NULL|

表4-2：daikuanxinxi表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|` `int|11|NOT NULL |
|addtime|varchar|50|default NULL|
|yinxingmingcheng|varchar|50|default NULL|
|daikuanedu|varchar|50|default NULL|
|haikuanlilv|varchar|50|default NULL|
|daikuanyaoqiu|varchar|50|default NULL|
|haikuanyaoqiu|varchar|50|default NULL|
|haikuanshijian|varchar|50|default NULL|
|zhanghao|varchar|50|default NULL|

表4-3：haikuanxinxi表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|int|11|NOT NULL|
|addtime|varchar|50|default NULL|
|yinxingmingcheng|varchar|50|default NULL|
|zhanghao|varchar|50|default NULL|
|jine|varchar|50|default NULL|
|haikuanriqi|varchar|50|default NULL|
|yonghuming|varchar|50|default NULL|
|xingming|varchar|50|default NULL|

表4-4：jinefabu表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|` `int|11|NOT NULL|
|addtime|varchar|50|default NULL|
|dingdanbianhao|varchar|50|default NULL|
|yinxingmingcheng|varchar|50|default NULL|
|daikuanjine|varchar|50|default NULL|
|lixi|varchar|50|default NULL|
|jine|varchar|50|default NULL|
|yonghuming|varchar|50|default NULL|
|xingming|varchar|50|default NULL|
|beizhu|varchar|50|default NULL|
|fabushijian|varchar|50|default NULL|
|zhanghao|varchar|50|default NULL|

表4-5：tongzhixinxi表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|` `int|11|NOT NULL|
|addtime|varchar|50|default NULL|
|biaoti|varchar|50|default NULL|
|yonghuming|varchar|50|default NULL|
|xingming|varchar|50|default NULL|
|tongzhineirong|varchar|50|default NULL|
|tongzhishijian|varchar|50|default NULL|
|zhanghao|varchar|50|default NULL|
|yinxingmingcheng|varchar|50|default NULL|



# 5系统界面实现
## 5.1 管理员登录
管理员输入个人的用户名、密码和角色登录系统，这时候系统的数据库就会在进行查找相关的信息，如果我们输入的用户名、密码和角色不正确，数据库就会提示出错误的信息提示，同时会提示管理员重新输入自己的用户名、密码、角色，直到用户名、密码输入成功后，会提登录成功的信息。网站管理员登录效果图如图5-1所示：

![](/images/0400ssm/ssm435/blog.018.png)     
图5-1管理员登录界面

## 5.2  管理员功能模块     
### 5.2.1 用户管理
管理员对用户管理进行查看用户名、姓名、性别、身份证、手机并进行详情、删除、修改等操作。程序成效图如下图5-2所示:

![](/images/0400ssm/ssm435/blog.019.png)

图5-2用户管理界面图
### 5.2.2 银行管理
管理员对银行管理进行查看账号、银行名称、负责人、性别、咨询电话等信息并可以进行详情、删除、修改操作。程序效果图如下图5-3所示：

![](/images/0400ssm/ssm435/blog.020.png)

图5-3银行管理界面
### 5.2.3 贷款信息管理
管理员对贷款信息管理进行查看银行名称、贷款额度、还款利率、还款时间、账号等信息并可以进行详情、删除、修改操作。程序效果图如下图5-4所示：

![](/images/0400ssm/ssm435/blog.021.png) 

图5-4贷款信息管理界面

### 5.2.4贷款申请管理
管理员对贷款申请管理进行查看银行名称、贷款额度、贷款金额、还款时间、账号、申请文件、申请时间、用户名、姓名、身份证、手机、审核回复、审核状态等信息进行详情、删除、修改操作。程序效果图如下图5-5所示：

![](/images/0400ssm/ssm435/blog.022.png)

图5-5贷款申请管理界面
### 5.2.5金额发布管理
管理员对金额发布管理进行查看订单编号、银行名称、贷款金额、利息、金额、用户名、姓名、发布时间、账号、是否支付等信息并可以进行详情、删除、修改操作。程序效果图如下图5-6所示：

![](/images/0400ssm/ssm435/blog.023.png) 

图5-6金额发布管理界面
### 5.2.6还款信息管理
管理员对还款信息管理进行查看银行名称、账号、金额、还款日期、用户名、姓名等信息并可以进行详情、删除、修改操作。程序效果图如下图5-7所示：

![](/images/0400ssm/ssm435/blog.024.png) 

图5-7还款信息管理界面

### 5.2.7通知信息管理
管理员对通知信息管理进行查看标题、用户名、姓名、通知时间、账号、银行名称等信息并可以进行详情、删除、修改操作。程序效果图如下图5-8所示：

![](/images/0400ssm/ssm435/blog.025.png) 

图5-8通知信息管理界面

## 5.3 用户功能模块
用户进入银行贷款管理系统可以查看首页、个人中心、贷款信息管理、贷款申请管理、金额发布管理、还款信息管理、通知信息管理等功能。程序效果图如下图5-9所示：

![](/images/0400ssm/ssm435/blog.026.png)

图5-9用户功能界面



### 5.3.1贷款信息管理
用户对贷款信息管理进行查看银行名称、贷款额度、还款利率、还款时间、账号等信息并可以进行详情、申请操作。程序效果图如下图5-10所示：

![](/images/0400ssm/ssm435/blog.027.png) 

图5-10贷款信息管理界面

### 5.3.2贷款申请管理
用户对贷款申请管理进行查看银行名称、贷款额度、贷款金额、还款时间、账号、申请文件、申请时间、用户名、姓名、身份证、手机、审核回复、审核状态等信息并可以进行详情、删除操作。程序效果图如下图5-11所示：

![](/images/0400ssm/ssm435/blog.028.png) 

图5-11贷款申请管理界面

### 5.3.3金额发布管理
用户对金额发布管理进行查看订单编号、银行名称、贷款金额、利息、金额、用户名、姓名、发布时间、账号、是否支付等信息并可以进行详情、还款操作。程序效果图如下图5-12所示：

![](/images/0400ssm/ssm435/blog.029.png) 

图5-12金额发布管理界面








## 5.4银行功能模块
银行进入银行贷款管理系统可以查看首页、个人中心、贷款信息管理、贷款申请管理、金额发布管理、还款信息管理、通知信息管理等功能。程序效果图如下图5-13所示：

![](/images/0400ssm/ssm435/blog.030.png)

图5-13银行功能界面
## 5.4.1贷款申请管理
银行进入贷款申请管理可以查看银行名称、贷款额度、贷款金额、还款时间、账号、申请文件、申请时间、用户名、姓名、身份证、手机、审核回复、审核状态、审核等信息进行详情、删除等操作。程序效果图如下图5-14所示：

![](/images/0400ssm/ssm435/blog.031.png)

图5-14贷款申请管理界面

## 5.4.2通知信息管理
银行进入通知信息管理可以查看标题、用户名、姓名、通知时间、账号、银行名称等信息进行详情、修改、删除操作。程序效果图如下图5-15所示：

![](/images/0400ssm/ssm435/blog.032.png)

图5-15通知信息管理界面


## 5.4.3金额发布管理
银行进入金额发布管理可以查看订单编号、银行名称、贷款金额、利息、金额、用户名、姓名、发布时间、账号、是否支付等信息进行详情、修改、删除操作。程序效果图如下图5-16所示：

![](/images/0400ssm/ssm435/blog.033.png)

图5-16金额发布管理界面

## 5.4.4还款信息管理
银行进入还款信息管理可以查看银行名称、账号、金额、还款日期、用户名、姓名等信息进行查看详情操作。程序效果图如下图5-17所示：

![](/images/0400ssm/ssm435/blog.034.png)

图5-17还款信息管理界面













