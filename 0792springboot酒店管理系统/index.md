# 0792springboot酒店管理系统


# [0792springboot酒店管理系统](https://github.com/GraduationProject-springboot/0792springboot)

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

# [项目清单](https://chenqi1990.site) 包安装运行

### [github 项目仓库](https://github.com/GraduationProject-springboot/allSpringbootProjects) 开源仅有后端代码

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)]()


# 系统概述
进过系统的分析后，就开始记性系统的设计，系统设计包含总体设计和详细设计。总体设计只是一个大体的设计，经过了总体设计，我们能够划分出系统的一些东西，例如文件、文档、数据等。而且我们通过总体设计，大致可以划分出了程序的模块，以及功能。但是只是一个初步的分类，并没有真正的实现。

整体设计，只是一个初步设计，而且，对于一个项目，我们可以进行多个整体设计，通过对比，包括性能的对比、成本的对比、效益的对比，来最终确定一个最优的设计方案，选择优秀的整体设计可以降低开发成本，增加公司效益，从这一点来讲，整体设计还是非常重要的。

酒店管理系统工作原理图如图4-1所示：

![](/images/0700stringboot/0792springboot/blog.012.png)

图4-1 系统工作原理图
## 4.2 系统结构设计
系统架构图属于系统设计阶段，系统架构图只是这个阶段一个产物，系统的总体架构决定了整个系统的模式，是系统的基础。酒店管理系统的整体结构设计如图4-2所示。

![](/images/0700stringboot/0792springboot/blog.013.png)

图4-2 系统结构图
## 4.3数据库设计
数据库是计算机信息系统的基础。目前，电脑系统的关键与核心部分就是数据库。数据库开发的优劣对整个系统的质量和速度有着直接影响。
### 4.3.1 数据库设计原则
数据库的概念结构设计采用实体—联系（E-R）模型设计方法。E-R模型法的组成元素有：实体、属性、联系，E-R模型用E-R图表示，是提示用户工作环境中所涉及的事物，属性则是对实体特性的描述。在系统设计当中数据库起着决定性的因素。下面设计出这几个关键实体的实体—关系图。
### 4.3.2 数据库实体
数据模型中的实体（Entity），也称为实例，对应现实世界中可区别于其他对象的“事件”或“事物”。例如，公司中的每个员工，家里中的每个家具。

本系统的E-R图如下图所示：

1、客房信息管理实体图如图4-3所示：

![](/images/0700stringboot/0792springboot/blog.014.png)

图4-3客房信息管理实体图

2、入住登记管理实体图如图4-4所示：

![](/images/0700stringboot/0792springboot/blog.015.png)

图4-4入住登记管理实体图

### 4.3.3 数据库表设计
数据库的表信息属于设计的一部分，下面介绍数据库中的各个表的详细信息。

表4-1：酒店公告

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|title|varchar|200|标题|||
|introduction|longtext|4294967295|简介|||
|picture|varchar|200|图片|||
|content|longtext|4294967295|内容|||

表4-2：客房预订

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yudingbianhao|varchar|200|预订编号|||
|kefangmingcheng|varchar|200|客房名称|||
|kefangleixing|varchar|200|客房类型|||
|kefangtupian|varchar|200|客房图片|||
|jiudianmingcheng|varchar|200|酒店名称|||
|jiudiandizhi|varchar|200|酒店地址|||
|kefangjiage|int||客房价格|||
|shuliang|int||数量|||
|zongjiage|int||总价格|||
|ruzhurenshu|int||入住人数|||
|xiadanshijian|datetime||下单时间|||
|yonghuzhanghao|varchar|200|用户账号|||
|yonghuxingming|varchar|200|用户姓名|||
|lianxidianhua|varchar|200|联系电话|||
|beizhu|longtext|4294967295|备注|||
|sfsh|varchar|200|是否审核||否|
|shhf|longtext|4294967295|审核回复|||
|ispay|varchar|200|是否支付||未支付|

表4-3：客房信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|kefangmingcheng|varchar|200|客房名称|||
|kefangleixing|varchar|200|客房类型|||
|kefangtupian|varchar|200|客房图片|||
|kefangjiage|int||客房价格|||
|kefangsheshi|longtext|4294967295|客房设施|||
|shuliang|varchar|200|数量|||
|jiudianmingcheng|varchar|200|酒店名称|||
|jiudiandizhi|varchar|200|酒店地址|||
|kefangjieshao|longtext|4294967295|客房介绍|||
|clicknum|int||点击次数||0|

表4-4：客房类型

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|kefangleixing|varchar|200|客房类型|||

表4-5：客房服务

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|fuwuxiangmu|varchar|200|服务项目|||
|fuwufeiyong|varchar|200|服务费用|||
|fengmian|varchar|200|封面|||
|shijianduan|varchar|200|时间段|||
|fuwuxiangqing|longtext|4294967295|服务详情|||

表4-6：用户

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yonghuzhanghao|varchar|200|用户账号|||
|yonghuxingming|varchar|200|用户姓名|||
|mima|varchar|200|密码|||
|xingbie|varchar|200|性别|||
|nianling|int||年龄|||
|lianxidianhua|varchar|200|联系电话|||
|dianziyouxiang|varchar|200|电子邮箱|||

表4-7：服务费用

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yonghuzhanghao|varchar|200|用户账号|||
|yonghuxingming|varchar|200|用户姓名|||
|fangjianhao|varchar|200|房间号|||
|fuwuxiangmu|varchar|200|服务项目|||
|fuwufeiyong|varchar|200|服务费用|||
|dengjishijian|datetime||登记时间|||
|beizhu|longtext|4294967295|备注|||
|ispay|varchar|200|是否支付||未支付|

表4-8：用户表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|username|varchar|100|用户名|||
|password|varchar|100|密码|||
|role|varchar|100|角色||管理员|
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|

表4-9：客房信息评论表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|refid|bigint||关联表id|||
|userid|bigint||用户id|||
|nickname|varchar|200|用户名|||
|content|longtext|4294967295|评论内容|||
|reply|longtext|4294967295|回复内容|||

表4-10：退房登记

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yudingbianhao|varchar|200|预订编号|||
|kefangmingcheng|varchar|200|客房名称|||
|kefangleixing|varchar|200|客房类型|||
|fangjianhao|varchar|200|房间号|||
|yonghuzhanghao|varchar|200|用户账号|||
|yonghuxingming|varchar|200|用户姓名|||
|lianxidianhua|varchar|200|联系电话|||
|tuifangshijian|datetime||退房时间|||
|beizhu|longtext|4294967295|备注|||

表4-11：配置文件

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|name|varchar|100|配置参数名称|||
|value|varchar|100|配置参数值|||

表4-12：token表

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

表4-13：收藏表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|userid|bigint||用户id|||
|refid|bigint||收藏id|||
|tablename|varchar|200|表名|||
|name|varchar|200|收藏名称|||
|picture|varchar|200|收藏图片|||

表4-14：入住登记

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yudingbianhao|varchar|200|预订编号|||
|kefangmingcheng|varchar|200|客房名称|||
|kefangleixing|varchar|200|客房类型|||
|fangjianhao|varchar|200|房间号|||
|yonghuzhanghao|varchar|200|用户账号|||
|yonghuxingming|varchar|200|用户姓名|||
|lianxidianhua|varchar|200|联系电话|||
|dengjishijian|datetime||登记时间|||
|yajin|varchar|200|押金|||
|beizhu|longtext|4294967295|备注|||
|ispay|varchar|200|是否支付||未支付|










# 5统详细设计
## 5.1系统功能模块
酒店管理系统，在系统首页可以查看首页、客房服务、客房信息、酒店公告、个人中心、后台管理等内容进行操作，如图5-1所示。

![](/images/0700stringboot/0792springboot/blog.016.png)

图5-1系统首页界面图



`   `用户注册，在用户注册页面通过填写用户账号、用户姓名、密码、年龄、联系电话、电子邮箱等信息完成用户注册，如图5-2所示。在个人中心页面通过填写用户账号、用户姓名、密码、性别、年龄、联系电话、电子邮箱等信息进行更新操作，还可以对我的收藏进行相应操作；如图5-3所示。

![](/images/0700stringboot/0792springboot/blog.017.png)

图5-2用户注册界面图

![](/images/0700stringboot/0792springboot/blog.018.png)

图5-3个人中心界面图

客房服务，在客房服务页面可以查看服务项目、服务费用、封面、时间段、服务详情等详细内容进预约，如图5-4所示。

![](/images/0700stringboot/0792springboot/blog.019.png)

图5-4客房服务界面图 

客房信息，在客房信息页面可以查看客房名称、客房类型、客房图片、客房价格、客房设施、数量、酒店名称、酒店地址、客房介绍等详细内容进预约，评论或收藏等操作；如图5-5所示。

![](/images/0700stringboot/0792springboot/blog.020.png)

图5-5客房信息界面图


## 5.2管理员功能模块
管理员登录，通过填写注册时输入的用户名、密码、选择角色进行登录，如图5-6所示。

![](/images/0700stringboot/0792springboot/blog.021.jpeg)

图5-6管理员登录界面图

管理员登录进入系统可以查看首页、个人中心、用户管理、客房类型管理、客房服务管理、客房信息管理、客房预订管理、入住登记管理、服务费用管理、退房登记管理、系统管理等信息进行详细操作，如图5-7所示。

![](/images/0700stringboot/0792springboot/blog.022.png)

图5-7管理员功能界面图

用户管理，在用户管理页面中可以对索引、用户账号、用户姓名、性别、年龄、联系电话、电子邮箱等信息进行详情，修改或删除等操作，如图5-8所示。

![](/images/0700stringboot/0792springboot/blog.023.png)

图5-8用户管理界面图

客房类型管理，在客房类型管理页面中可以对索引、客房类型等信息进行详情，修改或删除等操作，如图5-9所示。

![](/images/0700stringboot/0792springboot/blog.024.png)

图5-9客房类型管理界面图

客房服务管理，在客房服务管理页面中可以对索引、服务项目、服务费用、封面、时间段等信息进行详情，修改或删除等操作，如图5-10所示。

![](/images/0700stringboot/0792springboot/blog.025.png)

图5-10客房服务管理界面图

客房信息管理，在客房信息管理页面中可以对索引、客房名称、客房类型、客房图片、客房价格、客房设施、数量、酒店名称、酒店地址等信息进行详情、修改、查看评论或删除等操作，如图5-11所示。

![](/images/0700stringboot/0792springboot/blog.026.png)

图5-11客房信息管理界面图

客房预订管理，在客房预订管理页面中可以对索引、预订编号、客房名称、客房类型、客房图片、客房状态、酒店名称、酒店地址、客房价格、数量、总价格、入住人数、下单时间、用户账号、用户姓名、联系电话、是否支付、审核回复、审核状态等信息进行详情、入住、修改或删除等操作，如图5-12所示。

![](/images/0700stringboot/0792springboot/blog.027.png)

图5-12客房预订管理界面图

入住登记管理，在入住登记管理页面中可以对索引、预订编号、客房名称、客房类型、房间号、用户账号、用户姓名、联系电话、登记时间、押金、是否支付等信息进行详情、退房、修改、删除等操作，如图5-13所示。

![](/images/0700stringboot/0792springboot/blog.028.png)

图5-13入住登记管理界面图

服务费用管理，在服务费用管理页面中可以对索引、用户账号、用户姓名、房间号、服务项目、服务费用、登记时间、备注、是否支付等信息进行详情，修改或删除等操作，如图5-14所示。

![](/images/0700stringboot/0792springboot/blog.029.png)

图5-14服务费用管理界面图

退房登记管理，在退房登记管理页面中可以对索引、预订编号、客房名称、客房类型、房间号、用户账号、用户姓名、联系电话、退房时间等信息进行详情，修改或删除等操作，如图5-15所示。

![](/images/0700stringboot/0792springboot/blog.030.png)

图5-15退房登记管理界面图

系统管理，在酒店公告页面中可以对索引、标题、简介、图片等信息进行详情，修改或删除等操作，还可以对轮播图管理进行相应操作；如图5-16所示。

![](/images/0700stringboot/0792springboot/blog.031.png)

图5-16系统管理界面图


## 5.3用户后台功能模块
用户登录进入系统后台可以查看首页、个人中心、客房预订管理、入住登记管理、服务费用管理、退房登记管理、我的收藏管理等内容进行详细操作，如图5-17所示。

![](/images/0700stringboot/0792springboot/blog.032.png)

图5-17用户后台功能界面图

个人中心，在个人中心页面中通过填写用户账号、用户姓名、性别、年龄、联系电话、电子邮箱等信息进行修改，如图5-18所示。

![](/images/0700stringboot/0792springboot/blog.033.png)

图5-18个人中心界面图

客房预订管理，在客房预订管理页面中可以对索引、预订编号、客房名称、客房类型、客房图片、客房状态、酒店名称、酒店地址、客房价格、数量、总价格、入住人数、下单时间、用户账号、用户姓名、联系电话、是否支付、审核回复、审核状态等信息进行详情、修改或删除等操作，如图5-19所示。

![](/images/0700stringboot/0792springboot/blog.034.png)

图5-19客房预订管理界面图

我的收藏管理，在我的收藏管理页面中可以对索引、收藏名称、收藏图片等信息进行修改或删除等操作，如图5-20所示。

![](/images/0700stringboot/0792springboot/blog.035.png)

图5-20我的收藏管理界面图












