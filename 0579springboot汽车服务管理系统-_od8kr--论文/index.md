# 0579springboot汽车服务管理系统 _od8kr--论文


# [0579springboot汽车服务管理系统 _od8kr--论文](https://github.com/GraduationProject-springboot/0579springboot)

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

# [项目清单](https://chenqi1990.site) 包安装运行

### [github 项目仓库](https://github.com/GraduationProject-springboot/allSpringbootProjects) 开源仅有后端代码

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1eMbYemE1U?p=77)


# 系统概述
该系统由个人管理员和员工管理，用户三部分组成。其中：用户进入系统首页可以实现首页，热销汽车，汽车配件，汽车资讯，后台管理，在线客服，个人中心等；员工管理可以对系统首页，个人中心，热销汽车管理，订单信息管理，汽车配件管理，配件订单管理，售后信息管理，潜在客户管理，系统管理等功能进行管理；管理员则是根据不同需求设置了不同功能，可以通过后台管理用户信息。
## 3.2　需求分析
需求分析，也称为软件需求分析、系统需求分析或需求分析工程，是指开发人员经过充分的研究和分析，准确地理解用户和项目在功能、性能、可靠性等方面的具体需求，并将用户的非正式需求表述转化为确定系统必须执行的需求的完整定义的过程[11]。

功能需求分析是系统设计的前提，它要求开发者和用户定义开发什么样的体系和系统需要什么样的功能。本文主要介绍了一种基于windows系统实现的汽车服务管理系统。该系统为用户找到汽车服务信息提供了更安全、更高效、更便捷的途径。本系统有三个角色：管理员和员工，用户，要求具备以下功能：

1. 用户可以浏览主页了解汽车服务信息，可以查看首页，热销汽车，汽车配件，汽车资讯，后台管理，在线客服，个人中心等功能；

![](/images/0500stringboot/0579springboot/blog.001.png)

图3-1：用户用例图

1. 管理员通过后台管理员界面，实现对系统首页，个人中心，用户管理，员工管理，部门信息管理，岗位信息管理，汽车品牌管理，热销汽车管理，订单信息管理，配件分类管理，汽车配件管理，配件订单管理，售后信息管理，潜在客户管理，系统管理等功能的操作；

![](/images/0500stringboot/0579springboot/blog.002.png)

图3-2：管理员用例图

1. 员工管理通过后台管理界面，实现对系统首页，个人中心，热销汽车管理，订单信息管理，汽车配件管理，配件订单管理，售后信息管理，潜在客户管理，系统管理等功能的操作；

![](/images/0500stringboot/0579springboot/blog.003.png)

图3-3：员工管理用例图

## 3.3　可行性分析
可行性分析是指通过比较项目的主要内容和支撑条件，如市场需求、资源供应、环境影响、资金筹措情况、盈利能力等，预测项目建成后可能产生的资金、经济效益、社会和环境影响，为项目决策提供依据的综合性系统分析方法。可行性研究报告编制的质量直接影响着投资决策的成，而可行性研究报告编制程序又决定了可行性研究报告能否得到有效执行。因此，必须重视可行性研究工作，提高其编制水平。可行性分析应当具有预见性、公正性、可靠性和科学性[13]。
### 3.3.1　技术可行性分析 
本系统是为了为用户寻找汽车服务提供更加安全、高效、便捷的方式，本系统需要运用到Java、MySQL、springboot、B/S结构等技术，这些技术在国内外已经非常成熟[14]，在大学期间也有所涉及，相关的知识和工具在网络上也可以查到，再加上老师的指导，在技术上的难题可以得到解决。
### 3.3.2　经济可行性分析
该系统的主题是汽车服务管理系统的设计与实现。开发所需的软件资源是Eclipse。我们可以在它的网站上安装一个免费的版本，这对我们的开发和使用是足够好的。数据库就是MySQL数据库。是开源是免费的，服务器使用Tomcat服务器，浏览器使用日常IE浏览器，springboot框架是开源的。经过可行性评估，软件资源支出符合经济可行性[15]。硬件方面，配备齐全的笔记本电脑作为工具在经济上是可行的。
## 3.4流程设计
### 3.4.1程序流程图设计
非本系统的用户要想进行汽车服务就要注册本系统，登录时需要填写相应的资料，如有使用者，则会显示使用者名称已经存在，请再次键入使用者名称的提示框，若使用者不存在，则填写密码、确认密码等资料，并由系统判定密码与确认密码相符，确认无误后，填写使用者所填写的资料，即可进行登记。而且，为了保证系统的安全，只有在登录了本系统以后，才能进行汽车服务。该系统的工作流程见图3-4。


![](/images/0500stringboot/0579springboot/blog.004.png)

图3-4 程序流程图
### 3.4.2添加信息流程图设计
在添加信息的时候，会判断是哪类用户，并根据用户类型判断执行是否合法，合法者可以进行添加，不合法者则不能进行此操作[12]。管理员登录账号后可以对内容进行添加，拥有着最高的权限，用户权限次于管理员。添加信息流程图如图3-5所示：

![](/images/0500stringboot/0579springboot/blog.005.png)

图3-5系统添加流程图
### 3.4.3删除信息流程图设计
删除数据时与添加数据功能类似，删除数据具体流程如图3-6所示：

![](/images/0500stringboot/0579springboot/blog.006.png)

图3-6系统删除流程图
## 3.5　本章小结
汽车服务管理系统从市场、技术、经济、功能等方面分析了系统的功能需求，可以满足用户的汽车服务管理需求，帮助用户安全、高效地找到合适的汽车服务信息，因此有必要对其进行课题研究。
# 第4章　系统设计
系统设计是将被设计对象划分为单个模块进行构建，各个模块相互支持，相互制约，它们的组合是一个完整的系统。通过系统设计，可以最大限度地满足系统的预期目标，明确软件开发的目的。
## 4.1　系统基本结构设计
本次系统采用springboot框架集进行开发，springboot框架是一款企业界主流的软件开发框架，其简化了开发流程，大大缩减了软件开发所需的时间提高了软件的响应速度。系统总体结构图如图4-1所示。

![](/images/0500stringboot/0579springboot/blog.007.png)

图4-1　系统总体结构图

## 4.2　数据库设计
数据库结构设计的好坏直接影响到汽车服务管理系统的效率和实现的效果。本系统的数据库采用MySQL数据库，MySQL是一种开放源代码的关系型数据库管理系统，使用最常见的数据库管理语言SQL进行数据库管理。
### 4.2.1　数据库E-R图设计
E-R图也可称为实体-联系图，其可以清楚的显示实体与实体之间的关系，是描述概念模型的有效方式，通过各实体间的关系方便数据库结构的设计。以下是本系统主要的实体属性图如下所示。

汽车配件评论表实体如图4-2所示。

![](/images/0500stringboot/0579springboot/blog.008.png)

图4-2汽车配件评论表实体属性图

员工实体如图4-3所示。

![](/images/0500stringboot/0579springboot/blog.009.png)

图4-3员工实体属性图

售后信息实体如图4-4所示。

![](/images/0500stringboot/0579springboot/blog.010.png)

图4-4售后信息实体属性图

订单信息评价实体如图4-5所示。

![](/images/0500stringboot/0579springboot/blog.011.png)

图4-5订单信息实体属性图

用户实体如图4-6所示。

![](/images/0500stringboot/0579springboot/blog.012.png)

图4-6用户实体属性图

### 4.2.2　数据库表设计
数据表是用来保存多种数据的表，它是所有数据库的核心对象，且对于软件开发有着不可替代的作用。其相关数据表如下：

表4-1：汽车配件评论表

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

表4-2：员工

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yuangonggonghao|varchar|200|员工工号|||
|mima|varchar|200|密码|||
|yuangongxingming|varchar|200|员工姓名|||
|touxiang|longtext|4294967295|头像|||
|xingbie|varchar|200|性别|||
|bumenmingcheng|varchar|200|部门名称|||
|gangweimingcheng|varchar|200|岗位名称|||
|lianxifangshi|varchar|200|联系方式|||
|yuangongzhuangtai|varchar|200|员工状态|||
|sfsh|varchar|200|是否审核||待审核|
|shhf|longtext|4294967295|审核回复|||

表4-3：售后信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|shouhoubianhao|varchar|200|售后编号|||
|yonghuzhanghao|varchar|200|用户账号|||
|yonghuxingming|varchar|200|用户姓名|||
|lianxifangshi|varchar|200|联系方式|||
|kehudizhi|varchar|200|客户地址|||
|xiacibaoyang|date||下次保养|||
|yuangonggonghao|varchar|200|员工工号|||
|yuangongxingming|varchar|200|员工姓名|||

表4-4：订单信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|dingdanbianhao|varchar|200|订单编号|||
|qichemingcheng|varchar|200|汽车名称|||
|qichetupian|longtext|4294967295|汽车图片|||
|qichepinpai|varchar|200|汽车品牌|||
|qichejiage|int||汽车价格|||
|shuliang|int||数量|||
|zongjine|int||总金额|||
|weituodaigou|varchar|200|委托代购|||
|yonghuzhanghao|varchar|200|用户账号|||
|yonghuxingming|varchar|200|用户姓名|||
|lianxifangshi|varchar|200|联系方式|||
|goumaishijian|date||购买时间|||
|ispay|varchar|200|是否支付||未支付|

表4-5：用户

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yonghuzhanghao|varchar|200|用户账号|||
|mima|varchar|200|密码|||
|yonghuxingming|varchar|200|用户姓名|||
|touxiang|longtext|4294967295|头像|||
|xingbie|varchar|200|性别|||
|lianxifangshi|varchar|200|联系方式|||

表4-6：热销汽车

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|qichemingcheng|varchar|200|汽车名称|||
|qichetupian|longtext|4294967295|汽车图片|||
|qichepinpai|varchar|200|汽车品牌|||
|qichefenlei|varchar|200|汽车分类|||
|peizhi|varchar|200|配置|||
|zuowei|varchar|200|座位|||
|qicheyanse|varchar|200|汽车颜色|||
|shangshinianfen|varchar|200|上市年份|||
|qichejiage|int||汽车价格|||
|shuliang|int||数量|||
|canshupeizhi|longtext|4294967295|参数配置|||
|clicktime|datetime||最近点击时间|||
|clicknum|int||点击次数||0|

表4-7：配置文件

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|name|varchar|100|配置参数名称|||
|value|varchar|100|配置参数值|||

表4-8：用户表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|username|varchar|100|用户名|||
|password|varchar|100|密码|||
|role|varchar|100|角色||管理员|
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|

表4-9：汽车品牌

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|qichepinpai|varchar|200|汽车品牌|||

表4-10：部门信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|bumenbianhao|varchar|200|部门编号|||
|bumenmingcheng|varchar|200|部门名称|||
|chuangjianshijian|date||创建时间|||

表4-11：token表

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

表4-12：汽车配件

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|peijianbianhao|varchar|200|配件编号|||
|peijianmingcheng|varchar|200|配件名称|||
|tupian|longtext|4294967295|图片|||
|peijianfenlei|varchar|200|配件分类|||
|xinghao|varchar|200|型号|||
|shiyongpinpai|varchar|200|适用品牌|||
|shiyongchexi|varchar|200|适用车系|||
|peijianjiage|int||配件价格|||
|shuliang|int||数量|||
|peijianshuoming|longtext|4294967295|配件说明|||
|peijianxiangqing|longtext|4294967295|配件详情|||

表4-13：关于我们

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

表4-14：潜在客户

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|kehubianhao|varchar|200|客户编号|||
|kehuxingming|varchar|200|客户姓名|||
|kehudianhua|varchar|200|客户电话|||
|kehunianling|int||客户年龄|||
|yixiangchexing|varchar|200|意向车型|||
|goucheyusuan|varchar|200|购车预算|||
|yuangonggonghao|varchar|200|员工工号|||
|yuangongxingming|varchar|200|员工姓名|||
|bumenmingcheng|varchar|200|部门名称|||

表4-15：收藏表

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

表4-16：配件分类

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|peijianfenlei|varchar|200|配件分类|||

表4-17：配件订单

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|dingdanbianhao|varchar|200|订单编号|||
|peijianmingcheng|varchar|200|配件名称|||
|tupian|longtext|4294967295|图片|||
|peijianfenlei|varchar|200|配件分类|||
|peijianjiage|int||配件价格|||
|shuliang|int||数量|||
|hejijine|int||合计金额|||
|yonghuzhanghao|varchar|200|用户账号|||
|yonghuxingming|varchar|200|用户姓名|||
|lianxifangshi|varchar|200|联系方式|||
|ispay|varchar|200|是否支付||未支付|

表4-18：汽车资讯

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|title|varchar|200|标题|||
|introduction|longtext|4294967295|简介|||
|picture|longtext|4294967295|图片|||
|content|longtext|4294967295|内容|||

表4-19：岗位信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|gangweibianhao|varchar|200|岗位编号|||
|gangweimingcheng|varchar|200|岗位名称|||
|zhuangtai|varchar|200|状态|||

表4-20：热销汽车评论表

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

## 4.3　本章小结
通过本章针对汽车服务管理系统功能的总体结构、E-R属性图和数据表的大概介绍，对在开发系统时所要涉及到的数据库进行简单设计，为下一章系统的实现做好铺垫。

# 第五章 系统实现
## 5.1系统功能实现
当人们打开系统的网址后，首先看到的就是首页界面。在这里，人们能够看到汽车服务管理系统的导航条和。系统首页界面如图5-1所示：

![](/images/0500stringboot/0579springboot/blog.013.png)

图5-1 系统首页界面

系统注册：在系统注册页面输入用户注册信息进行注册操作；系统注册页面如图如图5-2所示：

![](/images/0500stringboot/0579springboot/blog.013.png)

图5-2系统注册页面

热销汽车：在热销汽车页面的输入栏中输入汽车名称，选择汽车分类和配置，汽车颜色进行查询；还可以进行收藏或立即购买操作；热销汽车页面如图5-3所示：

![](/images/0500stringboot/0579springboot/blog.013.png)

图5-3热销汽车详细页面

汽车配件：在汽车配件页面的输入栏中输入配件名称，型号，适用品牌和适用车系进行查询，还可以进行收藏和立即购买操作；汽车配件页面如图5-4所示：

![](/images/0500stringboot/0579springboot/blog.013.png)

图5-4汽车配件详细页面

个人中心：在个人中心页面通过填写个人详细信息进行信息更新操作，还可以对我的收藏进行详细操作；如图5-5所示：

![](/images/0500stringboot/0579springboot/blog.013.png)

图5-5个人中心界面

## 5.2管理员模块实现
管理员登录，在登录页面选择需要登录的角色，在正确输入用户名和密码后，进入操作系统进行操作；如图5-6所示。

![](/images/0500stringboot/0579springboot/blog.013.png)

图5-6管理员登录界面

管理员进入主页面，主要功能包括对系统首页，个人中心，用户管理，员工管理，部门信息管理，岗位信息管理，汽车品牌管理，热销汽车管理，订单信息管理，配件分类管理，汽车配件管理，配件订单管理，售后信息管理，潜在客户管理，系统管理等进行操作。管理员主页面如图5-7所示：

![](/images/0500stringboot/0579springboot/blog.013.png)

图5-7 管理员主界面

管理员点击员工管理。在员工页面输入员工工号，员工姓名，部门名称，岗位名称和选择是否通过进行查询、新增或删除员工列表，并根据需要对员工详情信息进行详情、修改或删除操作；如图5-8所示：

![](/images/0500stringboot/0579springboot/blog.013.png)

图5-8员工管理界面

管理员点击部门信息管理。在部门信息页面输入部门编号和部门名称进行查询、新增或删除部门信息列表，并根据需要对部门详情信息进行详情、修改或删除操作；如图5-9所示：

![](/images/0500stringboot/0579springboot/blog.013.png)

图5-9部门信息管理界面

管理员点击岗位信息管理。在岗位信息页面输入岗位名称和状态进行查询、新增或删除岗位信息列表，并根据需要对岗位详情信息进行详情、修改或删除操作；如图5-10所示：

![](/images/0500stringboot/0579springboot/blog.013.png)

图5-10岗位信息管理界面

管理员点击汽车品牌管理。在汽车品牌页面输入汽车品牌进行查询，新增或删除汽车品牌列表，并根据需要对汽车品牌详情信息进行详情、修改或删除操作；如图5-11所示：

![](/images/0500stringboot/0579springboot/blog.013.png)

图5-11汽车品牌管理界面
## 5.3用户模块实现
用户进入系统可以对系统首页,个人中心,订单信息管理，配件信息管理，售后信息管理等功能进行操作。用户主页面如图5-12所示：

![](/images/0500stringboot/0579springboot/blog.013.png)

图5-12用户主界面

## 5.4员工模块实现
员工进入系统可以对系统首页，个人中心，热销汽车管理，订单信息管理，汽车配件管理，配件订单管理，售后信息管理，潜在客户管理，系统管理等功能进行操作。员工主页面如图5-13所示：

![](/images/0500stringboot/0579springboot/blog.013.png)

图5-13员工主界面
## 5.5本章小结
第五章主要内容是系统实现，首先实现了本系统中最重要的前台功能，其次分别实现了对管理员功能的管理和对用户，员工管理后台的管理，并对主要代码的编写，完成了系统全部功能设计。












