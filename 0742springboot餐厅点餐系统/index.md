# 0742springboot餐厅点餐系统


# [项目清单 包安装运行](http://chenqi1990.site) 官网地址 http://chenqi1990.site

# [0742springboot餐厅点餐系统](https://github.com/GraduationProject-springboot/0742springboot)

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### [github 项目仓库](https://github.com/GraduationProject-springboot/allSpringbootProjects) 开源仅有后端代码

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV14HerezEwW?p=98)

# 系统概述
进过系统的分析后，就开始记性系统的设计，系统设计包含总体设计和详细设计。总体设计只是一个大体的设计，经过了总体设计，我们能够划分出系统的一些东西，例如文件、文档、数据等。而且我们通过总体设计，大致可以划分出了程序的模块，以及功能。但是只是一个初步的分类，并没有真正的实现。

整体设计，只是一个初步设计，而且，对于一个项目，我们可以进行多个整体设计，通过对比，包括性能的对比、成本的对比、效益的对比，来最终确定一个最优的设计方案，选择优秀的整体设计可以降低开发成本，增加公司效益，从这一点来讲，整体设计还是非常重要的。

高校校园点餐系统工作原理图如图4-1所示：

![](/images/0700stringboot/0742springboot/blog.012.png)

图4-1 系统工作原理图
## 4.2 系统结构设计
系统架构图属于系统设计阶段，系统架构图只是这个阶段一个产物，系统的总体架构决定了整个系统的模式，是系统的基础。高校校园点餐系统的整体结构设计如图4-2所示。

![](/images/0700stringboot/0742springboot/blog.013.png)

图4-2 系统结构图
## 4.3数据库设计
数据库是计算机信息系统的基础。目前，电脑系统的关键与核心部分就是数据库。数据库开发的优劣对整个系统的质量和速度有着直接影响。
### 4.3.1 数据库设计原则
数据库的概念结构设计采用实体—联系（E-R）模型设计方法。E-R模型法的组成元素有：实体、属性、联系，E-R模型用E-R图表示，是提示用户工作环境中所涉及的事物，属性则是对实体特性的描述。在系统设计当中数据库起着决定性的因素。下面设计出这几个关键实体的实体—关系图。
### 4.3.2 数据库实体
数据模型中的实体（Entity），也称为实例，对应现实世界中可区别于其他对象的“事件”或“事物”。例如，学校中的每个学生，家里中的每个家具。

本系统的E-R图如下图所示：

1、用户信息实体图如图4-3所示：

![](/images/0700stringboot/0742springboot/blog.014.png)

图4-3用户信息实体图

2、食堂信息实体图如图4-4所示：

![](/images/0700stringboot/0742springboot/blog.015.png)

`   `图4-4食堂信息实体图

3、留言板信息实体图如图4-5所示：

![](/images/0700stringboot/0742springboot/blog.016.png)

图4-5留言板信息实体图

#########

### 4.3.3 数据库表设计
数据库的表信息属于设计的一部分，下面介绍数据库中的各个表的详细信息。

表名：shitang

功能：食堂表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|
|shitanghao|varchar|100|食堂号|||
|mima|varchar|100|密码|||
|shitangming|varchar|100|食堂名|||
|guanliyuan|varchar|200|管理员|||
|shitangzhaopian|varchar|100|食堂照片|||
|weishengdengji|varchar|200|卫生等级|||
|lianxidianhua|varchar|200|联系电话|||
|shitangdizhi|varchar|200|食堂地址|||




表名：shitangcaidan

功能：食堂菜单表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|shitanghao|varchar|200|食堂号|||
|shitangming|varchar|200|食堂名|||
|caipin|varchar|200|菜品|||
|caixi|varchar|200|菜系|||
|tupian|varchar|200|图片|||
|fenliang|varchar|200|分量|||
|shicai|varchar|200|食材|||
|shitangdizhi|varchar|200|食堂订单|||
|xiangqing|varchar|200|详情|||




表名：xiaoxiliuyan

功能：消息留言表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|zhanghao|varchar|200|账号|||
|xingming|varchar|200|姓名|||
|jiaose|longtext|4294967295|角色|||
|shitanghao|varchar|200|食堂号|||
|shitangming|varchar|200|食堂名|||
|dingdanhao|varchar|200|订单号|||
|peisongfen|varchar|200|配送分|||
|baozhuangfen|varchar|200|包装分|||
|caipinfen|varchar|200|菜品分|||
|shijian|varchar|200|时间|||
|jianyi|varchar|200|建议|||
|sfsh|varchar|200|是否审核|||
|shhf|varchar|200|审核回复|||




表名：caixifenlei

功能：菜系分类表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|caixi|varchar|200|菜系|||




表名：yonghu

功能：用户表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|
|zhanghao|varchar|100|账号|||
|mima|varchar|100|密码|||
|xingming|varchar|100|姓名|||
|jiaose|varchar|100|角色|||
|xingbie|varchar|100|性别|||
|nianling|varchar|100|年龄|||
|shouji|varchar|100|手机|||
|youxiang|varchar|100|邮箱|||
|zhaopian|varchar|100|照片|||








# 5统详细设计
##
## 5.1前台首页功能模块
高校校园点餐系统，在系统首页可以查看首页、食堂菜单、新闻资讯、留言反馈、我的、跳转到后台、购物车等内容，如图5-1所示。

![](/images/0700stringboot/0742springboot/blog.017.png)

图5-1前台首页功能界面图





用户注册、用户登录，在用户注册页面可以填写账号、密码、姓名、角色、性别、年龄、手机、邮箱等信息进行用户注册、登录，如图5-2所示。

![](/images/0700stringboot/0742springboot/blog.018.png)

![](/images/0700stringboot/0742springboot/blog.019.png)

图5-2用户注册、登录界面图
#########
食堂菜单，在食堂菜单页面通过填写食堂号、食堂名、菜品、菜系、图片、分量、食材、食堂地址、详情、价格、座位总数等信息进行添加到购物车、立即预定、点我收藏等操作，如图5-3所示。在我的地址页面通过填写联系人、手机号码、默认地址、选择地址等信息进行添加或重置操作，如图5-4所示。

![](/images/0700stringboot/0742springboot/blog.020.png)

图5-3食堂菜单界面图
#########
![](/images/0700stringboot/0742springboot/blog.021.png)

图5-4我的地址界面图

## 5.2管理员功能模块
管理员登录，通过填写输入用户名、密码进行登录，如图5-5所示。

![](/images/0700stringboot/0742springboot/blog.022.png)

图5-5管理员登录界面图



管理员登录进入高校校园点餐系统可以查看个人中心、用户管理、食堂管理、食堂菜单管理、菜系分类管理、消息留言管理、留言板管理、系统管理、订单管理等信息。

用户管理，在用户管理页面中可以通过填写账号、密码、姓名、角色、性别、年龄、手机、邮箱、照片、余额等内容进行查看、修改、删除等操作，如图5-6所示。

食堂管理，在食堂管理页面中可以查看食食堂号、密码、食堂名、管理员、食堂照片、卫生等级、联系电话、食堂地址、余额等信息，并可根据需要对已有食堂管理进行查看、修改、删除等操作，如图5-7所示。

![](/images/0700stringboot/0742springboot/blog.023.png)

图5-6用户管理界面图

![](/images/0700stringboot/0742springboot/blog.024.png)

图5-7食堂管理界面图

菜系分类管理，在菜系分类管理页面中可以查看菜系等信息，并可根据需要对已有菜系分类管理进行修改或删除等操作，如图5-8所示。

![](/images/0700stringboot/0742springboot/blog.025.png)

图5-8菜系分类管理界面图

消息留言管理，在消息留言管理页面中可以查看账号、姓名、角色、食堂号、食堂名、订单号、配送分、包装分、菜品分、时间、建议、是否审核、审核回复等信息，并可根据需要对已有消息留言管理进行审核、查看、修改或删除等详细操作，如图5-9所示。

![](/images/0700stringboot/0742springboot/blog.026.png)

图5-9消息留言管理界面图

留言板管理，在留言板管理页面中可以查看留言人id 、用户名、留言内容、回复内容等内容，并且根据需要对已有留言板管理进行查看、回复、修改或删除等详细操作，如图5-10所示。

![](/images/0700stringboot/0742springboot/blog.027.png)

图5-10留言板管理界面图

美食资讯管理，在美食资讯管理页面中可以查看标题、简介、图片、内容等内容，并且根据需要对已有美食资讯管理进行查看、修改或删除等详细操作，如图5-11所示。

![](/images/0700stringboot/0742springboot/blog.027.png)

图5-11美食资讯管理界面图


订单管理，在订单管理页面中可以查看订单编号、商品表名、用户ID、商品ID、商品名称、商品图片、购买数量、价格/积分、折扣价格、总价格/总积分、折扣总价格、

支付类型、状态、地址等内容，并且根据需要对已有订单管理进行查看，修改或删除等详细操作，如图5-12所示。

![](/images/0700stringboot/0742springboot/blog.028.png)

图5-12订单管理界面图


## 5.3食堂功能模块
食堂登录进入高校校园点餐系统可以查看个人中心、食堂菜单管理、菜系分类管理、消息留言管理、订单管理等内容。

食堂菜单管理，在食堂菜单管理页面中通过填写食堂号、食堂名、菜品、菜系、图片、分量、食材、食堂地址、详情、价格、座位总数、已选座位[用号隔开]等信息，还可以根据需要对食堂菜单管理进行查看、修改、删除等操作，如图5-13所示。

![](/images/0700stringboot/0742springboot/blog.029.png)

图5-13食堂菜单管理界面图

菜系分类管理，在菜系分类管理页面中可以填写菜系等信息，并且根据需要对已有菜系分类管理进行修改、删除等其他详细操作，如图5-14所示。

![](/images/0700stringboot/0742springboot/blog.030.png)

图5-14菜系分类管理界面图
#########
订单管理，在订单管理页面中通过填写订单编号、商品表名、用户ID、商品ID、商品名称、商品图片、购买数量、价格/积分、折扣价格、总价格/总积分、折扣总价格、

支付类型、状态、地址等内容进行查看、发货等操作，如图5-15所示。

![](/images/0700stringboot/0742springboot/blog.031.png)

图5-15订单管理界面图
#########
## 5.4用户功能模块
用户登录进入高校校园点餐系统可以查看个人中心、消息留言管理、我的收藏管理、订单管理等内容。

消息留言管理，在消息留言管理页面中通过填写账号、姓名、角色、食堂号、食堂名、订单号、配送分、包装分、菜品分、时间、建议、是否审核、审核回复等信息，还可以根据需要对消息留言管理进行查看、修改、删除等操作，如图5-16所示。

![](/images/0700stringboot/0742springboot/blog.032.png)

图5-16消息留言管理界面图

订单管理，在订单管理页面中可以查看订单编号、商品表名、用户ID、商品ID、商品名称、商品图片、购买数量、价格/积分、折扣价格、总价格/总积分、折扣总价格、

支付类型、状态、地址等信息，并且根据需要对已有订单管理进行查看等其他详细操作，如图5-17所示。

![](/images/0700stringboot/0742springboot/blog.021.png)

图5-17订单管理界面图
#########


#########












