# 0264springboot基于Spring Boot的库存管理系统


# [0264springboot基于Spring Boot的库存管理系统](https://github.com/GraduationProject-springboot/0264springboot)

### 微信： chen_q123456  qq:462201886
### github:chenqi199

### [所有项目](https://github.com/GraduationProject-springboot/allSpringbootProjects) 包安装运行

### [所有项目列表excel 腾讯文档 项目清单](https://docs.qq.com/sheet/DSHRFSVZ5aEVYT3N3?tab=BB08J2) 包安装运行

### [github](https://chenqi199.github.io)








# 0264springboot基于Spring Boot的库存管理系统

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://player.bilibili.com/player.html?isOutside=true&aid=BV1jqaLe1EbH&bvid=BV1jqaLe1EbH&cid=500001610884276&p=31)

### [所有项目](https://github.com/GraduationProject-springboot/allSpringbootProjects) 包安装运行












**毕业设计（论文）**

基于Spring Boot库存管理系统

Inventory Meanagement System based on Spring Boot

： [王 豪]{.underline}

： [本 科]{.underline}

： [计算机技术与工程学院]{.underline}

： [计算机科学与技术]{.underline}

： [聂振海]{.underline}

： [讲 师]{.underline}

： [2022年05月29日]{.underline}

学生姓名

学历层次

所在系部

所学专业

指导教师

教师职称

完成时间

**长 春 工 程 学 院**

摘 要

当下，如果还依然使用纸质文档来记录并且管理相关信息，可能会出现很多问题，比如原始文件的丢失，因为采用纸质文档，很容易受潮或者怕火，不容易备份，需要花费大量的人员和资金来管理用纸质文档存储的信息，最重要的是数据出现问题寻找起来很麻烦，并且修改也困难，如果还这样操作会造成很大的资源浪费和经济损失。

库存管理系统运用的工具包括IDEA，Tomcat，Spring
Boot框架以及MySQL等。该系统可以实现对公告信息，员工，供应商类型，供应商信用等级，商品类型，公告类型，供应商，商品，商品预定，采购入库，采购入库详情，客户等信息进行管理。

库存管理系统就是采用目前最流行的互联网应用思维，让信息处理变得更加高效，并且处理结果更加的符合预期，只要是关于数据管理方面，不管是添加还是修改，以及数据维护甚至是数据迁移，都可以达到更快更安全的要求。

关键词

库存管理系统 商品 采购入库

Abstract

At present, if paper documents are still used to record and manage
related information, there may be many problems, such as the loss of
original documents, because paper documents are easily damped or afraid
of fire, not easy to back up, and require a lot of personnel. and funds
to manage the information stored in paper documents, the most important
thing is that it is very troublesome to find problems with the data, and
it is difficult to modify.

The tools used by the inventory management system include IDEA, Tomcat,
Spring Boot framework and MySQL. The system can realize the management
of announcement information, employee, supplier type, supplier credit
rating, commodity type, announcement type, supplier, commodity,
commodity reservation, purchase storage, purchase storage details,
customers and other information.

The inventory management system adopts the most popular Internet
application thinking to make information processing more efficient, and
the processing results are more in line with expectations. As long as it
is about data management, whether it is adding or modifying, and data
maintenance or even data migration, All can achieve faster and safer
requirements.

Key Words**：**Inventory Management System Commodities Procurement and
Warehousing

# 目 录

[1 绪论 1](#绪论)

[1.1 选题动因 1](#选题动因)

[1.2 目的和意义 1](#目的和意义)

[2 开发环境与技术 2](#开发环境与技术)

[2.1 AJAX技术 2](#ajax技术)

[2.2 JDK简介 2](#jdk简介)

[2.3 MySQL数据库 2](#mysql数据库)

[2.5 Spring Boot框架 3](#spring-boot框架)

[2.6 Vue框架 3](#vue框架)

[2.8 Navicat简介 3](#navicat简介)

[3 系统分析 4](#__RefHeading___Toc29089)

[3.1 可行性分析 4](#可行性分析)

[3.2 系统流程分析 5](#系统流程分析)

[3.3 系统性能分析 6](#系统性能分析)

[3.4 系统功能分析 7](#系统功能分析)

[4 系统设计 9](#系统设计)

[4.1 布局设计原则 9](#布局设计原则)

[4.2 功能结构设计 10](#功能结构设计)

[4.3 数据库设计 11](#数据库设计)

[5 系统实现 17](#系统实现)

[5.1 管理员功能实现 17](#管理员功能实现)

[5.2 员工功能实现 21](#员工功能实现)

[6 系统测试 24](#系统测试)

[6.1 系统测试方法 24](#系统测试方法)

[6.2 功能测试 24](#功能测试)

[6.3 测试结果分析 25](#测试结果分析)

[7 结 论 26](#结-论)

[参考文献 27](#参考文献)

[致 谢 28](#__RefHeading___Toc5985)

#  {#section .unnumbered}

# 1 绪论

## 1.1 选题动因

在现在社会，对于信息处理方面，是有很高的要求的，因为信息的产生是无时无刻的，并且信息产生的数量是呈几何形式的增加，而增加的信息如何存储以及短时间分析检索，也是有时效性的，所以，不管是任何的企业和个人，只要需要处理信息，必然是要寻找到一个适合自己的解决方案，而软件开发商和数据库提供商就是为了解决这些问题。相比之前人工信息处理的水平，现代的信息处理方法是完胜以前的信息处理方法。开发一个符合自己需求的信息管理系统，可以把整个信息处理的过程变得很有规范，并且很有水准，让整个信息处理变成一个自动化的过程，并且在数据处理结果之中直接设定好检索标准，或者是多条件检索标准，通过数据分析获得自己需要的内容，这都是信息化的好处。当一切信息数据存在小小的存储介质之中，那么数据迁移备份的重要性也变得更加简洁，可以设置自动化远程备份，自动化远程处理，不管是使用过程还是维护过程，都会变得更加的高效和整洁，最重要的成本上面的控制，可以极限减少，开源节流，不外如是，减少社会资源的浪费，也是计算机技术的存在的一个优势。

## 1.2 目的和意义

如今的年代，已经是步入信息社会了，不仅信息更新速度频繁，信息量也大，在信息时代必须有相应的处理信息的方法，如果还采用以前的结绳记事或者笔写纸记，不仅是信息录入效率上赶不上节奏，在信息检索的速度上更是让人无法承受。幸而当今社会上计算机技术发展的相当不错，可以通过计算机在信息处理上面实现自动化或者半自动化的作业，采用计算机技术，能有效的提高信息录入以及信息检索的效率，社会上相同行业之间本身就是效率高的淘汰效率低的，既然采用计算机来替代手工记录，必然是效率更高，稳定性更强，成本更低等诸多优点。针对于商品库存信息管理，开发一个库存管理系统不仅可以实现现代化的信息管理，也更符合现代化信息管理规范。

在实际的使用效果中，库存管理系统的意义如下：

第一点：库存管理系统的出现，就是为了提高工作人员的效率，能够在规定时间完成工作任务。

第二点：操作页面符合人体工程美学，符合日常人为操作习惯，使用友好。

第三点：区别于传统用纸张记录，提高了信息化水平。

第四点：在信息处理方面，极大的降低了人工处理成本。

在库存管理系统实际操作中，使用者会发现使用起来相当的方便，并且对数据的管理者来讲，也能及时的获得自己想要的数据，对整个数据的所有者能提供强大的帮助，库存管理系统从操作者的角度出发，不管是在数据的接收以及传递，以及处理结果，都有一个很明显的要求，对有效数据的处理，并且形成集合，并且对有效数据集合进行固定化处理，可以得到更有效的数据，有了库存管理系统，让管理层不至于把大量的人力和财力资源消耗在数据处理整合方面，完全可以让不知疲倦的计算机来进行，不仅投入减低，并且产出也不少。互联网时代就是如此，顺之者昌，响应互联网时代，不至于说可以乘风破浪，起码可以降低直接淘汰出局的几率。库存管理系统的出现是顺应时代的。

# 2 开发环境与技术

库存管理系统需要提前对功能进行调查分析，并且根据分析结果进行技术上的辩证，可以选择更合理的开发技术以及开发工具。

## 2.1 AJAX技术

AJAX是一门技术，不是一个框架。AJAX的产生，最主要的原因是因为当时的互联网速度非常慢，而网页的图片缓存本身就造成了很不好的用户体验，如果页面上所有的表单数据全部提交给后台处理，不符合规范又会造成页面的刷新，用户又需要重新填写，次数多了体验不好了就会造成用户的流失。AJAX通过对JS标准、HTML标准、XML标准这些标准的集成，在不影响页面布局效果的情况下又能提交数据与服务器进行数据校验和页面提示，很好的解决了用户的无感刷新体验，目前市面上所有的浏览器都支持AJAX技术的。

## 2.2 JDK简介 

JDK这个是Java开发所必须的东西。Java开发必须用JDK，运行必须用JRE，而JDK往往携带了JRE环境，也就是说只要安装了JDK就不需要再去重复性的安装JRE，所以JDK这款开发Java的必备品也就很受欢迎。一台电脑上可以安装多个版本的JDK，并且可以对不同的项目指定不同的JDK，这一点做的相当的友好。如果一台电脑默认没有安装过JDK是不需要配置环境变量，就可以直接访问JDK的，这一点对于初学者来讲，起码配置环境变量方面就方便了很多。JDK目前最新版本是JDK17，版本已经很高了，但是不管是学习还是使用，一般都喜欢用比较稳定的版本，比如JDK1.7或者JDK1.8版本。

## 2.3 MySQL数据库

本设计用到的数据库就是MySQL数据库，之所以用到这个数据库的原因很多。首先，从满足功能需求上面来讲，MySQL是符合的；其次，从学习程度来讲，MySQL相比其他数据库不管是从安装还是使用上面来讲，都比较简单，最重要的是学习起来相当便捷，比较容易入手；再次，MySQL数据库对电脑要求不高，不管是什么样的电脑都可以安装MySQL数据库，并且并不会对电脑性能造成过多的影响。所以，就平常普普通通的电脑就可以作为开发用的电脑，不需要进行额外的电脑升级。虽然自从MySQL数据库被Oracle数据库收购后，有了一些闭源的风险，但是使用者还是很多，MySQL数据库目前的开发人员已经超过五百人了，对数据库开发者来讲已经是一个很大的开发团队了。MySQL在使用上面来讲，普通的增删改查操作已经可以满足大部分业务需求，像一些数据导出导入，以及一些函数，都可以满足一些不同的需求，最重要的是MySQL数据库可以创建索引，可以大大的提高数据的查询效率，当然，物极必反，如果因为索引好用而滥用，索引弄得比数据库表还要多，这样会造成MySQL数据库更新表数据时候的运行效率。总而言之，MySQL数据库在本次设计的使用上，是完全符合使用要求的。

## 2.5 Spring Boot框架

Spring是一个很好的框架，但是发展到现在，在使用上面已经诟病不断，需要配置的越来越多，配置大于开发，让程序员用更多的精力去配置Spring，有点本末倒置了。Spring
Boot框架是为了解决Spring框架的缺点而生，Spring框架好用是好用，但是配置起来相当的繁琐，Spring
Boot则让简化了很多配置过程，让开发变得更有趣也更有效率，并且学过Spring框架的开发人员很容易理解Spring
Boot框架，没有用过框架的人员学习Spring Boot框架的速度也很快的，Spring
Boot得到了Java开发者的一致好评。

## 2.6 Vue框架

Vue框架的开发者是一个中国人，区别于其他框架的最核心的概念就是渐进式框架，Vue的出现，让网页前端的开发变成了一种纯前端职业，不需要在考虑后台数据类型以及业务逻辑，只需要进行数据绑定即可，大大的减少了前端开发工程师的学习难度。Vue是当前世界上最火的一种前段框架，学习成本比较低，只需要熟悉最基本的网页知识就可以理解相关知识，并且有很好的免费教程进行学习，有各个国家语言的教程，尤其是因为是中国人开发的框架，让中国的高级程序开发人员做了汉语教程。Vue框架发展之初就是高于IE8版本的，所以说只要是当前的主流浏览器都支持Vue框架，如果是很旧的那种电脑是不支持的，必须安装支持HTML5的浏览器才可以访问用Vue发布的站点。

## 2.8 Navicat简介

Navicat是一款管理数据库的软件。众所周知，所有的数据库只是以特定的存放格式进行存放的，访问也需要特定的接口以及语句进行访问。如果访问数据库都用各种命令，不仅仅是开发效率上会大大的降低，并且看起来也不舒服，对于某些数据或者数据库来讲这样并不友好，如何对数据库进行友好的访问到现在为止，不同的数据库厂商都推出了适合自己数据库的管理工具，但是有一点就是，数据库厂商推出之后，只要能用就行，并没有符合人体工程学，所有的数据库厂商推出的数据库管理工具都是免费的，所以并没有对于数据库管理工具进行过多的优化，用起来相当的不友好，并且各个数据库工具是不能通用的，这一点数据库厂商肯定不会去做匹配其他数据库的管理工具，所以Navicat就应运而生，可以采用Navicat管理各种各样的数据库，可以同时访问各种数据库并且通过不同的连接进行访问，还可以访问不同电脑的数据库，页面操作简单，美观大方，用起来很好用，并且占用电脑资源很小，很适合作为替代其他数据库厂商推出的数据库管理工具使用。

[]{#__RefHeading___Toc29089 .anchor}

通过对系统的功能进行具体分析，可以参考已经发表过的具有参考价值的文章作为对比，这样能把功能分析的很透彻，并且也会因为功能的分析而对性能也有大致的了解，并且可以预测性能，实现性能分析的结果。

## 3.1 可行性分析

系统的设计必须符合正常逻辑，所以设计之处，也需要从其他方面来论证其可行性。

### 3.1.1 经济可行性

开发库存管理系统，存在经济上面的支持，必须经济上的支持才可以有序进行，比如是否需要额外购买开发工具，购买开发电脑，或者从开发技术上是否是免费开源，达到的效果上面是否支出与收入不匹配，这些都需要进行分析。由于开发本系统，开发技术开源且稳定，电脑用正在使用的电脑就能满足，不需要太多的经济支出就可以达到目的，经济可行性通过。

### 3.1.2 技术可行性

库存管理系统软件主要用到的一些工具，而这些工具正好在学校就使用过，并且网上有很多免费的并且符合的开发工具，技术方面也学过，并且有图书馆的资源和网络资源可以充分利用。所以在技术角度上面来分析是可以的。

### 3.1.3 操作可行性

操作方面分为开发过程，实现过程，项目具体操作流程。这些因为都学过，并且有其他的项目流程作为参考。总体实现一般就是用户的登录相关，权限分配，基础数据的变更体现。让不同的角色有不同的操作界面，符合正确角色定位，使用者在操作上面并不会感觉到很突兀，影响操作流程。所以操作方面是可以的。

通过以上不同角度的分析，最后论证分析了可行性是没有问题的，完全可以进行后续步骤。

## 3.2 系统流程分析

操作逻辑是一个可以用画图工具展示的，因为数据在录入过程中的不可见，只能看到返回结果，所以把流程画成图可以更好的理解其中的顺序。

在系统的各项操作中，其他的录入环节，会对操作者具体操作的每条信息都会提出验证要求，比如不能为空，只能是汉字，以及其他的要求等，这些都在前端需要编写清楚，达到友好提示的目的，有效的帮助操作人员理解操作。具体数据的流程如下面的图所示。当操作员输入信息后，点击提交后台就会接收操作员提交的信息，并且提前编写好的逻辑会继续验证，如果数据合格就存入到数据库里并且返回成功提示，这样一个录入环节就达到了设计要求。

![](media/image1.wmf)

图3.1 添加信息流程图

有时候录入的一些数据可能需要修改，修改就是纠正之前的操作，所以修改数据必须是先把想要修改的数据从数据库里获取出来，然后在这个之上进行修改，修改数据也有相应的操作流程。

![](media/image2.wmf)

图3.2 修改信息流程图

数据的查询是在任何程序上都是一个常规的操作，面对的数据量不一样，想要获取想要的数据时间也不一样，都是尽快的获取自己想要的结果，所以数据查询就需要有个查询条件作为查询关键词，这样可以更好的获取符合关键词的数据。

![](media/image3.wmf)

图3.3 查询信息流程图

## 3.3 系统性能分析

关于库存管理系统从性能需求方面来分析，主要从五个角度分析。五个角度分别从设计的实用性，设计的操作性，设计的安全性，设计的适应性和维护性这五个角度来进行分析。

首先分析第一点，设计的实用性。本设计的目的就是让管理员可以综合的处理各种基础信息，并且有相应的权限来进行操作，达到数据同步，集中管理的目的，并且可以让用户处理用户相关信息，符合设计的既定目标，达到使用效果。

其次分析第二点，设计的操作性。开发出来的系统必须有操作性，如果操作起来丢三落四，出现各种不符合流程的操作，那么就是不符合设计规则的，设计的操作性必须符合人体工程学使用原则，从上到下，从左到右，让操作起来更加的有逻辑性，不需要不符合逻辑的页面数据体验和操作流程，让设计的操作性体现出来，看到操作界面就会有相应的下一步理解。

再次是安全性，虽然从任何角度来讲，安全性应该放到第一位，但是有些时候安全性是在数据量大并且数据重要的前提下才会对数据的安全性来进行设计，正常的软件使用过程只要数据设计合理，并且目标单一，让黑客不屑于或者付出不成正比的情况下，安全性自然可以稍微降低一点，毕竟面对的使用群体决定了安全性的强度。本设计主要是从毕业设计的角度出发，增加一点数据校验的安全性就行，没必要设置硬件防火墙之类的资源，所以安全性上面也是符合的。

再次是适应性。适应性主要是面对各种平台的操作系统，目前本设计的开发可以使用本人电脑进行开发，服务器可以架设到任何地方，并且有对应的服务器软件版本。而用户方面只需要能上网，有最新版本的浏览器进行支持即可，所以适应性是相当不错的。

最后是分析维护性。这一点只需要维护服务端代码即可，每次服务端代码维护都可以先把服务器停止，然后在开发电脑上进行测试，最后测试无误再在服务器上进行部署，维护性并不会增加多少成本。

## 3.4 系统功能分析

当设计人员通过参考各种文献以及其他类似项目的调研后，就会对项目具体的功能进行分析，这样有的放矢可以更快的设计程序的功能。

库存管理系统的操作者有管理员，分析的管理员功能将使用用例图进行展示。图3.4展示了管理员用例图。管理员查看商品库存统计报表，对商品，商品预定信息，供应商信息，商品采购入库信息，客户信息，公告信息，员工信息等进行管理。

![](media/image4.wmf)

图3.4 管理员用例图

库存管理系统的操作者有员工，分析的员工的功能将使用用例图进行展示。图3.5展示了员工用例图。员工查询商品，添加商品预定信息，添加商品采购入库信息，添加客户信息，查看公告等。

![](media/image5.wmf)

图3.5 员工用例图

# 

# **4 系统设计**

在系统设计环境，业务的处理逻辑和数据的设计逻辑虽然是重中之重，但是这些都是用户看不见摸不着的，用户也只是能看到部署好的项目运行起来的结果，所以用户对界面布局以及界面功能比较看重。所以说，如今只要是开发网站不仅仅是需要懂一点页面设计就行，也需要懂得UI设计的人群。传统的网页设计其实就是换几个颜色，放几张图片，然后来充实操作页面，让操作页面不至于太单调，但是互联网发展至今，开发也越来越精细化，用户越来越挑剔，还用凑合方式来进行程序开发，已经是属于落后的状态了。

## 4.1 布局设计原则

布局不是传统的把页面分分类，输入和显示页面，调整调整间距这些笼统的说法了，布局设计也是有一定的原则的。

首先，布局一定要清晰合理。布局的清晰不是说图片清晰或者文字清晰，而是说用户在使用过程中，看到导航的布局，就能明白所有功能模块都可以在导航里寻找，打开一个页面，就能知道重要与不重要的资料，必须与不必须的填写，甚至是输入的格式是什么规格，都可以让用户使用的时候一目了然。因为界面是有限的，所以说布局是相当重要的一点设计原则。

其次，布局的体现要符合大众审美，比如说导航，尽量都是网页的上方或者左侧。如果把导航放到网页下方或者右方，这些代码都是可以实现，但是不符合正常人的思维定向。现代人的读写习惯都是从上而下，从左到右的阅读方式，人们身体和心灵已经习惯了这种方式，如果布局到其他方向首先用户会感到新颖，但是却不会买账，因为操作几遍后就会不习惯。

最后，布局也要考虑这个软件是用来做什么的，常用这个软件的人员的年龄划分，性别划分，以及职业划分。划分了使用人群，就可以对背景进行调色填充，如果是长时间用电脑的人群尽量设计的有护眼功能，不至于看一会眼睛就受不了，尽量要区分长时间使用和短时间使用的背景，这一点很重要。

综上所述，系统设计需要考虑方方面面，布局设计也是需要精细化考虑，系统设计需要考虑太多，但是实现却不能弄得操作上太复杂，系统设计尽量的要满足用户需要，提高用户满意度。

## 4.2 功能结构设计

在基于系统功能分析的基础之上，开始对系统的详细功能进行设计，最终将使用结构图的形式对设计的结果进行展示。

管理员具备的详细功能将参照最终的设计结果，即图4.1所示的管理员功能结构图。其中管理员查看商品库存统计报表，对商品，商品预定信息，供应商信息，商品采购入库信息，客户信息，公告信息，员工信息等进行管理。

![](media/image6.wmf)

图4.1 管理员功能结构图

员工具备的详细功能将参照最终的设计结果，即图4.2所示的员工功能结构图。其中员工查询商品，添加商品预定信息，添加商品采购入库信息，添加客户信息，查看公告等。

![](media/image7.wmf)

图4.2 员工功能结构图

## 4.3 数据库设计

数据库的选用方面肯定要选一个市场反应比较好，性价比比较高的数据库，不能凭空想象数据库，要结合程序设计的需求来选择对应的数据库。目前来讲，市面上常用的关系型数据库足够达到需求。

### 4.3.1 数据库E-R图设计

想好更好的设计出数据库使用效果，那么就要对数据的存放格式以及存放关系作出调查和梳理，所以通过分析E-R图之间的数据实体关系是最好不过的。而设计数据库E-R图是有下面几点好处：

第一点：数据的冗余是一件很恐怖的事情，所以要对有些数据进行冗余筛选；

第二点：防止内存溢出，数据量太大，需要提前做好预测并且设定好规则；

第三点：数据库一定要完整，非完整数据也只是数据垃圾而已，没有任何作用；

第四点：提高数据检索性能；

这节主要是描述对系统的E-R模型的设计，数据存储格式的判断，实现的方法，用户的需要，这些都要统一，不能想当然。并且各个模型中间的关系尤其要突出。

（1）把出入库信息具备的属性通过属性图进行展示，绘制的属性图见图4.4。

![](media/image8.wmf)

图4.4 出入库信息实体属性图

（2）把商品具备的属性通过属性图进行展示，绘制的属性图见图4.5。

![](media/image9.wmf)

图4.5 商品实体属性图

（3）把员工具备的属性通过属性图进行展示，绘制的属性图见图4.6。

![](media/image10.wmf)

图4.6 员工实体属性图

（4）把管理员具备的属性通过属性图进行展示，绘制的属性图见图4.7。

![](media/image11.wmf)

图4.7 管理员实体属性图

（5）上述实体间关系见图4.8。

![](media/image12.wmf)

图4.8 实体间关系E-R图

### 4.3.2 数据库表结构设计

数据库设计必须符合规范，那就是三大范式，这样能确保数据的合理：

第一范式：保证表之间的字段关系不存在混淆的描述，必须描述准确，并且单一，不能分解；

第二范式：在上述的满足条件上，主键的设计必须要在固定的列上，不能忽前忽后；

第三范式：继续满足上个条件，保证每个字段都可以根据主键获取到，并且在一个数据表里体现。

所以说，三个范式是一脉相承的，不是说零碎的，从第一个范式上就会发现，第一个永远是基础，后面的设定就是后者的实现必须在前面范式的基础之上的要求，这些设计可以最大化的减少数据冗余，提高数据库运行效率。

表4.1 员工信息表

  --------------- ---------------------------------- -------------- -----
  字段            注释                               类型           空

  id (主键)       主键                               int(11)        否

  username        账号                               varchar(200)   是

  password        密码                               varchar(200)   是

  yonghu_name     员工姓名                           varchar(200)   是

  yonghu_photo    头像                               varchar(255)   是

  sex_types       性别                               int(11)        是

  yonghu_phone    联系方式                           varchar(200)   是

  yonghu_email    邮箱                               varchar(200)   是

  yonghu_delete   假删                               int(11)        是

  insert_time     添加时间                           timestamp      是

  create_time     创建时间                           timestamp      是
  --------------- ---------------------------------- -------------- -----

表4.2 供应商信息表

  -------------------------------- -------------------- -------------- -----
  字段                             注释                 类型           空

  id (主键)                        主键                 int(11)        否

  gongyinghsang_name               供应商名称           varchar(200)   是

  gongyinghsang_types              供应商类型           int(11)        是

  gongyinghsang_xinyong_types      供应商信用等级名称   int(11)        是

  insert_time                      添加时间             timestamp      是

  gongyinghsang_content            供应商详情           text           是

  create_time                      创建时间             timestamp      是
  -------------------------------- -------------------- -------------- -----

表4.3 商品信息表

  --------------------- --------------------------- --------------- -----
  字段                  注释                        类型            空

  id (主键)             主键                        int(11)         否

  goods_name            商品名字                    varchar(200)    是

  goods_types           商品类型                    int(11)         是

  goods_kucun_number    商品库存                    int(11)         是

  gongyinghsang_id      供应商                      int(11)         是

  cangku_types          存储仓库                    int(11)         是

  danwei                单位                        varchar(200)    是

  goods_new_money       单价                        decimal(10,2)   是

  goods_content         商品详情                    text            是

  create_time           创建时间                    timestamp       是
  --------------------- --------------------------- --------------- -----

表4.4 出入库信息表

  ---------------------------------- --------------- -------------- -----
  字段                               注释            类型           空

  id (主键)                          主键            int(11)        否

  goods_churu_inout_uuid_number      出入库流水号    varchar(200)   是

  goods_churu_inout_name             出入库名称      varchar(200)   是

  goods_churu_inout_types            出入库类型      int(11)        是

  goods_churu_inout_content          备注            text           是

  insert_time                        添加时间        timestamp      是

  create_time                        创建时间        timestamp      是
  ---------------------------------- --------------- -------------- -----

表4.5 出入库详情信息表

  ---------------------------------- ------------------- ----------- -----
  字段                               注释                类型        空

  id (主键)                          主键                int(11)     否

  goods_churu_inout_id               出入库              int(11)     是

  goods_id                           商品                int(11)     是

  goods_churu_inout_list_number      操作数量            int(11)     是

  insert_time                        操作时间            timestamp   是

  create_time                        创建时间            timestamp   是
  ---------------------------------- ------------------- ----------- -----

表4.6 商品预定信息表

  ----------------------------- -------------------- -------------- -----
  字段                          注释                 类型           空

  id (主键)                     主键                 int(11)        否

  goods_id                      商品                 int(11)        是

  kehu_id                       客户                 int(11)        是

  yonghu_id                     员工                 int(11)        是

  goods_order_danhao_number     单号                 varchar(200)   是

  goods_order_number            预定数量             int(11)        是

  goods_order_time              预定时间             timestamp      是

  goods_order_types             预定状态             int(11)        是

  goods_order_content           备注                 text           是

  create_time                   创建时间             timestamp      是
  ----------------------------- -------------------- -------------- -----

表4.7 客户信息表

  --------------------- ---------------------------- -------------- -----
  字段                  注释                         类型           空

  id (主键)             主键                         int(11)        否

  kehu_name             客户姓名                     varchar(200)   是

  kehu_phone            客户联系方式                 varchar(200)   是

  sex_types             性别                         int(11)        是

  kehu_order_content    客户详情                     text           是

  create_time           创建时间                     timestamp      是
  --------------------- ---------------------------- -------------- -----

表4.8 公告信息

  -------------- ----------------------------------- -------------- -----
  字段           注释                                类型           空

  id (主键)      主键                                int(11)        否

  news_name      公告标题                            varchar(200)   是

  news_types     公告类型                            int(11)        是

  news_photo     公告图片                            varchar(200)   是

  insert_time    添加时间                            timestamp      是

  news_content   公告详情                            text           是

  create_time    创建时间                            timestamp      是
  -------------- ----------------------------------- -------------- -----

表4.9 管理员信息表

  -------------- -------------------------------- ----------------- ------
  字段           注释                             类型              空

  id (主键)      主键                             bigint(20)        否

  username       用户名                           varchar(100)      否

  password       密码                             varchar(100)      否

  role           角色                             varchar(100)      是

  addtime        新增时间                         timestamp         否
  -------------- -------------------------------- ----------------- ------

![](media/image13.png){width="9.722222222222222e-3in"
height="9.722222222222222e-3in"}

# 5 系统实现

下面主要是对系统实现的功能进行描述，一般在系统实现阶段只算是一个粗略的功能实现，可能符合开发人员的设计预期，但是对于具体使用者来讲还是需要其他人进行发现的，所以这个环节是很有必要进行描述的。

## 5.1 管理员功能实现

### 5.1.1 供应商管理

实现供应商管理功能，其界面运行的效果图见图5.1。供应商信息有供应商类型，供应商信用等级名称，供应商名称等信息，管理员需要新增供应商，发现登记错误数据的供应商信息可以使用修改功能及时更改，需要删除的供应商信息可以使用删除功能删除。

![](media/image14.png){width="5.759722222222222in"
height="2.747916666666667in"}

图5.1 供应商管理界面

### 5.1.2 商品管理

实现商品管理功能，其界面运行的效果图见图5.2。商品信息有商品类型，存储仓库，单位，单价，供应商名称等信息，管理员新增商品信息，使用修改功能对有错误数据的商品信息进行更改，需要删除的商品信息可以使用删除功能删除。

![](media/image15.png){width="5.759722222222222in"
height="2.747916666666667in"}

图5.2 商品管理界面

### 5.1.3 商品统计报表

实现商品统计报表功能，其界面运行的效果图见图5.3。管理员通过柱形图可以查看各个商品的库存数据，管理员可以切换柱形图统计报表为折线图，可以下载商品库存的统计报表图片。

![](media/image16.png){width="5.759722222222222in"
height="2.747916666666667in"}

图5.3 商品统计报表界面

### 5.1.4 商品预定管理

实现商品预定管理功能，其界面运行的效果图见图5.4。商品预定信息有预定数量，客户姓名，员工姓名，预定的商品，预定时间等信息。商品预定信息可以让管理员新增，需要删除的商品预定信息可以使用删除功能删除。

![](media/image17.png){width="5.759722222222222in"
height="2.747916666666667in"}

图5.4 商品预定管理界面

### 5.1.5 采购入库管理

实现采购入库管理功能，其界面运行的效果图见图5.5。采购入库信息包括采购入库名称，采购入库流水号等信息，采购入库信息也允许管理员新增，需要删除的采购入库信息也能够使用删除功能删除。管理员查询采购入库信息需要提供的查询条件是采购入库名称。

![](media/image18.png){width="5.759722222222222in"
height="2.747916666666667in"}

图5.5 采购入库管理界面

### 5.1.6 公告信息管理

实现公告信息管理功能，其界面运行的效果图见图5.6。公告信息有公告类型，公告图片等信息，公告信息允许管理员新增，发现有错误数据的公告信息可以使用修改功能更正，需要删除的公告也能使用删除功能删除。

![](media/image19.png){width="5.759722222222222in"
height="2.747916666666667in"}

图5.6 公告信息管理界面

### 5.1.7 客户管理

实现客户管理功能，其界面运行的效果图见图5.7。客户信息有客户姓名，客户联系方式，客户性别等信息，管理员也能新增客户信息，客户信息存在数据登记错误的情况，管理员可以使用修改功能更改，需要删除的客户信息可以使用删除功能删除。对于客户信息的查询，需要管理员提供客户姓名，提供客户联系方式等。

![](media/image20.png){width="5.759722222222222in"
height="2.747916666666667in"}

图5.7 客户管理界面

## 5.2 员工功能实现

### 5.2.1 商品管理

实现商品管理功能，其界面运行的效果图见图5.8。员工查看商品存储仓库，查看商品库存，查看商品单价等信息，员工查询商品有很多种方式，可以根据商品名字，商品类型，存储仓库，单价，供应商名称等信息来查询商品。

![](media/image21.png){width="5.759722222222222in"
height="2.747916666666667in"}

图5.8 商品管理界面

### 5.2.2 商品预定管理

实现商品预定管理功能，其界面运行的效果图见图5.9。员工新增商品预定信息，员工只能查看自己登记的商品预定信息的详情信息，同时，员工也只能查询自己登记的商品预定信息，查询商品预定信息也有很多种方式，可以根据预定数量，商品名字，客户姓名，客户联系方式，单号等信息查询。

![](media/image22.png){width="5.759722222222222in"
height="2.747916666666667in"}

图5.9 商品预定管理界面

### 5.2.3 采购入库管理

实现采购入库管理功能，其界面运行的效果图见图5.10。员工可以新增采购入库信息，主要是登记采购入库名称，选择采购入库类型，主要有采购入库，出库两种采购入库类型可供选择，最后提交新增的采购入库信息。已经提交的采购入库信息，员工也能随时查看其详细信息。

![](media/image23.png){width="5.759722222222222in"
height="2.747916666666667in"}

图5.10 采购入库管理界面

### 5.2.4 采购入库

实现采购入库功能，其界面运行的效果图见图5.11。员工对商品采购入库时，需要选择采购入库的商品，然后对该商品的入库数量进行编辑，包括增加商品采购入库的数量，减少商品采购入库的数量，查看商品库存，最后提交商品采购入库信息。

![](media/image24.png){width="5.759722222222222in"
height="2.747916666666667in"}

图5.11 采购入库界面

### 5.2.5 采购入库详情管理

实现采购入库详情管理功能，其界面运行的效果图见图5.12。员工主要是查看采购入库的商品的操作数量信息，操作时间信息，采购入库名称以及采购入库类型等信息。查询采购入库详情需要员工提供商品名字，单价，采购入库名称才能查询。

![](media/image25.png){width="5.759722222222222in"
height="2.747916666666667in"}

图5.12 采购入库详情管理界面

### 5.2.6 客户管理

实现客户管理功能，其界面运行的效果图见图5.13。员工新增客户信息，查看各个客户的联系方式信息，查询客户需要员工提供客户的联系方式，提供客户姓名等信息才能查询。

![](media/image26.png){width="5.759722222222222in"
height="2.747916666666667in"}

图5.13 客户管理界面

# 6 系统测试

系统测试的含义并不是说只要有了系统测试就不需要程序员自己测试，程序员开发过程中，因为面对的是不断的编码，一个模块一个模块的编写，甚至有些模块不是自己编写的，在整个程序测试中，程序员是必须要自己测试自己写的代码的，如果程序员不自己测试自己写的代码，那么代码的存在是没有意义的。程序员自己测试只是属于系统测试中的第一个环节而已，后续需要专业的测试人员继续测试。

## 6.1 系统测试方法

系统测试的环节有很多要求，并且有不同的测试方式，有模块测试，整体测试，验收测试，回归测试等。以下内容着重描述不同的测试方法。

模块测试：就是单元测试，每个模块每个功能，分别测试，有问题就反馈。

整体测试：就是集成测试，是模块测试的后续，只要是一个模块相关联的模块，全部测试，这样的好处就是不会漏掉任何一个关联模块。

验收测试：这个是甲方人员所负责的，主要是验收的，自然有验收的方法，可外包第三方测试公司，也可以自己派人测试。

回归测试：测试出问题就修改问题，但是为了避免出现新的问题，所以继续新一轮的测试。只有不断的回归测试，才能把整个程序完美的测试出来，让问题更少，让开发和测试变得更加统一。

## 6.2 功能测试

既然程序开发好了，那么必备的测试功能是必不可少的，必须测试合格的程序才算是符合正常使用要求的程序，所以测试也是一项很重要的任务。

### 6.2.1 登录功能测试

系统的登录是首先要测试的环节，虽然系统登录在各个软件上都有这个操作，看起来微不足道，其实也是用户访问的最基本的安全操作，必须登录才算是合法用户。测试结果如下：

表6.1 登录功能测试表

+-----------+--------------+----------------+---------------+---------+
| 功能      | 数据输入     | 预期的结果     | 实际的结果    | 测      |
|           |              |                |               | 试结果  |
+-----------+--------------+----------------+---------------+---------+
| 管        | 用户         | 系统           | 提示用        | 合格    |
| 理员登录  | 名：保持为空 | 弹出提示信息： | 户名不能为空  |         |
|           |              | 用户名不能为空 |               |         |
|           | 密           |                |               |         |
|           | 码：保持为空 |                |               |         |
+-----------+--------------+----------------+---------------+---------+
| 管        | 用户名：kkk  | 系             | 提示          | 合格    |
| 理员登录  |              | 统弹出提示信息 | 密码不能为空  |         |
|           | 密           | ：密码不能为空 |               |         |
|           | 码：保持为空 |                |               |         |
+-----------+--------------+----------------+---------------+---------+
| 管        | 用户名：kkk  | 系统弹         | 提示用户      | 合格    |
| 理员登录  |              | 出提示信息：用 | 名或密码错误  |         |
|           | 密码：mmm    | 户名或密码错误 |               |         |
+-----------+--------------+----------------+---------------+---------+
| 管        | 用户名：kkk  | 系统弹出提示   | 提示成功登录  | 合格    |
| 理员登录  |              | 信息：成功登录 |               |         |
|           | 密码：kkk    |                |               |         |
+-----------+--------------+----------------+---------------+---------+

### 6.2.2 采购入库查询功能测试

系统功能里面关于数据录入成功后，有查询模块的功能必须要测试查询，查询功能必须根据提前设定好的条件来进行查询，如果符合设定的条件会查询出来结果，不符合就不会出现结果。

表6.2 采购入库查询功能测试表

  -------------- --------------------------- ---------------------------------------- -------------------------- ----------
  功能           数据输入                    预期的结果                               实际的结果                 测试结果

  采购入库查询   采购入库名称：保持为空      系统弹出提示信息：采购入库名称不能为空   提示采购入库名称不能为空   合格

  采购入库查询   采购入库名称：%&\*          系统弹出提示信息：数据格式有误           提示数据格式有误           合格

  采购入库查询   采购入库名称：出入库名称4   显示出查询的结果                         显示出查询的结果           合格
  -------------- --------------------------- ---------------------------------------- -------------------------- ----------

## 6.3 测试结果分析

整个测试流程完毕后，从测试功能结果上看，库存管理系统的功能完全符合设计的要求。从运行结果上看，能保证整天运行，并且运行过程中也没有发现运行异常。从性能消耗结果上看，符合预期消耗，并没有过多的消耗其他服务器资源。系统可以在用户操作违规时能正常提示用户，让用户正常操作，这个机制是相当友好的，一方面避免了用户的野蛮操作，也平复了用户的情绪，让用户有机会改正。整个操作页面和操作流程都符合现代人的操作行为习惯。本系统可以正常上线，可以让用户使用，解决用户生产中面临的问题。

# 7 结 论

本课题主要是研究与实现库存管理系统，在经历了资料查找，技术选择，功能分析，模块设计，数据库设计，界面设计，功能编码，功能测试等阶段性工作之后，本人已如期完成了一个可供目标用户群使用的库存管理系统。

库存管理系统选用Java语言，搭配MySQL数据库进行设计与开发，相比于大部分相似系统而言，其具备的特点如下：

（1）库存管理系统的功能完全根据目标人群的使用需求进行分析设计与编码，也经过了开发流程中的最后测试环节，最终确定其功能基本得到实现，可以在生活中发挥其用于信息管理的作用。

（2）库存管理系统的界面设计很简单，具备简洁直观的特点，因为每个功能模块都有单独的界面展示，使用者点击不同的功能就会出现与之相应的界面，每个界面的颜色搭配比较统一，界面的布局也合理，界面上使用的各种图片都经过了Photoshop这样的图片处理工具进行了美化，所以使用者在浏览本系统的各个界面的时候，对本系统显示的各种信息能够一目了然。

（3）库存管理系统的使用与操作非常便利，因为本系统能够规避大部分用户的误操作现象，所以使用人群在使用期间能够在短时间内找到需要的功能并操作，这样可以节省操作时间，并且本系统在操作的流程上也进行了优化，去掉了一些比较繁琐的操作步骤，同时本系统在各个界面上也把一些常用的功能放在了比较显眼的区域，也方便使用者对库存管理系统功能的操作。

由于本人在系统开发经验上的不足，库存管理系统也存在一些缺陷，具体如下：

（1）对于数据的存储上面，设计的数据表存在不合理之处，对于同一数据在多张表中都有记录，造成了存储空间的浪费以及系统响应时间的延迟。

（2）对于系统编码上面，有很多代码并没有进行注释，这个对于开发人员来讲，在进行系统的后续升级与维护上会消耗很多时间，提升了对系统升级与维护的难度，还有就是，很多代码使用的函数都是相同的函数，这个函数在各个代码文件中都重新进行了编写，没有单独独立出来进行调用，让该系统变得臃肿，同时也消耗了很多存储空间。

所以在今后，也需要本人花费很多时间来对库存管理系统进行完善，对于上面提到的数据库中的数据冗余问题，打算学习数据库连接池方面的技术来改善数据冗余的现象，对于编码文件占用存储空间过多的问题，打算使用函数的调用功能，把相同函数写在一个编码文件上让其他需要使用该函数的编码文件进行函数调用，以此节省存储空间，让系统变得更加轻盈。

# 参考文献

\[1\]刘华锋,苏艳刚,刘跃.生产型企业库存管理系统开发\[J\].现代工业经济和信息化,2021,11(07):70-71+139.

\[2\]柯海波.计量资产库存管理系统设计与实现\[D\].电子科技大学,2021.

\[3\]王妍.JSP开发手册（码出高效JSP开发手册+阿里巴巴JSP开发手册）\[M\].北京：电子工业出版社,2019.

\[4\]明日科技.Java从入门到精通(第3版)\[M\].清华大学出版社,2014.

\[5\]宋长龙.基于互联网的数据库及程序设计\[M\].清华大学出版社,2016.

\[6\]何玉洁.数据库原理与应用教程.第4版\[M\].机械工业出版社,2016.

\[7\]李辉.数据库系统原理及MySQL应用教程\[M\].机械工业出版社,2016.

\[8\]萨师煊,王珊.数据库系统概论\[M\].北京：高等教育出版社,2017.

\[9\]邓立国,佟强.数据库原理与应用（SQL Server
2016版本）\[M\].北京：清华大学出版社,2017.

\[10\]韩路彪.看透Spring MVC:源代码分析与实践\[M\].机械工业出版社,2016.

\[11\]梁灏.Vue.js实战\[M\].清华大学出版社,2017.

\[12\]孙卫秦,李洪成.Tomcat与Java
Web开发技术详解\[M\].北京:电子工业出版社,2018.

\[13\]徐建波.JavaWeb应用开发原理与技术\[M\].长沙:国防科技大学出版社,2010.

\[14\]谈文蓉,崔梦天.软件开发项目实践\[M\].西南交通大学出版社,2016.

\[15\]Benymol Jose,Sajimon Abraham.Performance analysis of NoSQL and
relational databases with MongoDB and MySQL.2020,24(Pt 3):2036-2043.

\[16\]Dragos-Paul Pop,Adam Altar.Designing an MVC Model for Rapid Web
Application Development\[J\].Procedia Engineering,2017.

[]{#__RefHeading___Toc5985 .anchor}致 谢

制作毕业设计这段时间又像回到了高考前夕的那段岁月，每天都充满激情，整天都斗志昂然，当整个项目完成的那一瞬间，心情多重天。一方面有一种淡淡的成就感，另一方面有也有淡淡的失落，但更有的就是信心的坚定。

成就感就是经过这几个月的忙碌，让设计的项目可以正常运行了，每一个模块和每一个功能都是一个一个的去实现的，这个过程中少不了感谢我的导师，每当思路混淆都有导师的耐心指导，每次导师说一句能顶上网上搜半天，因为网上好多言语都似是而非自相矛盾，不知道该相信谁，导师说了之后自己去实际操作，按照导师的说法，往往都能成功，说实话，仅仅靠自己靠百度，是完不成毕业设计的，没有导师就没有我的这个项目的成果。从项目开始的选题到项目的结束，导师的每一次指导都让我的耳目一新，让我重生斗志，再次感谢我的学校，再次感谢我的导师，我是真心感谢！

毕设制作过程中，肯定少不了同学的帮忙，大家都是从网上找资料，每个人的理解不一样，没有同学的帮忙，少不了把每个操作过程中的坑都踩一遍，大家都在做设计，有很多坑他们有的都踩过了能及时的帮助我，而我有时候也帮助别人，大大的提高了效率，避免了很多操作过程中的未知问题，我非常的感谢有这么一群小伙伴们，俗话说良师益友，我统统具备，感谢他们这么些年的陪伴，真心感谢！

即将离开校园，将要步入社会，去实现自己的理想，报效父母，报效祖国，感谢我的大学，感谢我的导师，感谢我的同学，回忆这几年，还真没有仔细的观看自己的校园，绕着自己的校园漫步，每一寸土地都去丈量，发现了校园真的好美，每一个笑容都是那么的灿烂，在这样的氛围之中，心中淡淡的疏离之感产生，我要走出校园了，以后这里仅仅是我的母校，感谢母校的关怀，让我在走的时候还能体会到什么是快乐时光。

再次感谢母校，感谢导师，感谢同学！

供应商模块：

/\*\*

\* 后端列表

\*/

\@RequestMapping(\"/page\")

public R page(@RequestParam Map\<String, Object\> params,
HttpServletRequest request){

logger.debug(\"page方法:,,Controller:{},,params:{}\",this.getClass().getName(),JSONObject.toJSONString(params));

String role =
String.valueOf(request.getSession().getAttribute(\"role\"));

if(false)

return R.error(511,\"永不会进入\");

else if(\"员工\".equals(role))

params.put(\"yonghuId\",request.getSession().getAttribute(\"userId\"));

if(params.get(\"orderBy\")==null \|\| params.get(\"orderBy\")==\"\"){

params.put(\"orderBy\",\"id\");

}

PageUtils page = gongyinghsangService.queryPage(params);

//字典表数据转换

List\<GongyinghsangView\> list
=(List\<GongyinghsangView\>)page.getList();

for(GongyinghsangView c:list){

//修改对应字典表字段

dictionaryService.dictionaryConvert(c, request);

}

return R.ok().put(\"data\", page);

}

/\*\*

\* 后端详情

\*/

\@RequestMapping(\"/info/{id}\")

public R info(@PathVariable(\"id\") Long id, HttpServletRequest
request){

logger.debug(\"info方法:,,Controller:{},,id:{}\",this.getClass().getName(),id);

GongyinghsangEntity gongyinghsang = gongyinghsangService.selectById(id);

if(gongyinghsang !=null){

//entity转view

GongyinghsangView view = new GongyinghsangView();

BeanUtils.copyProperties( gongyinghsang , view
);//把实体数据重构到view中

//修改对应字典表字段

dictionaryService.dictionaryConvert(view, request);

return R.ok().put(\"data\", view);

}else {

return R.error(511,\"查不到数据\");

}

}

/\*\*

\* 后端保存

\*/

\@RequestMapping(\"/save\")

public R save(@RequestBody GongyinghsangEntity gongyinghsang,
HttpServletRequest request){

logger.debug(\"save方法:,,Controller:{},,gongyinghsang:{}\",this.getClass().getName(),gongyinghsang.toString());

String role =
String.valueOf(request.getSession().getAttribute(\"role\"));

if(false)

return R.error(511,\"永远不会进入\");

Wrapper\<GongyinghsangEntity\> queryWrapper = new
EntityWrapper\<GongyinghsangEntity\>()

.eq(\"gongyinghsang_name\", gongyinghsang.getGongyinghsangName())

.eq(\"gongyinghsang_types\", gongyinghsang.getGongyinghsangTypes())

.eq(\"gongyinghsang_xinyong_types\",
gongyinghsang.getGongyinghsangXinyongTypes())

;

logger.info(\"sql语句:\"+queryWrapper.getSqlSegment());

GongyinghsangEntity gongyinghsangEntity =
gongyinghsangService.selectOne(queryWrapper);

if(gongyinghsangEntity==null){

gongyinghsang.setInsertTime(new Date());

gongyinghsang.setCreateTime(new Date());

gongyinghsangService.insert(gongyinghsang);

return R.ok();

}else {

return R.error(511,\"表中有相同数据\");

}

}

/\*\*

\* 后端修改

\*/

\@RequestMapping(\"/update\")

public R update(@RequestBody GongyinghsangEntity gongyinghsang,
HttpServletRequest request){

logger.debug(\"update方法:,,Controller:{},,gongyinghsang:{}\",this.getClass().getName(),gongyinghsang.toString());

String role =
String.valueOf(request.getSession().getAttribute(\"role\"));

// if(false)

// return R.error(511,\"永远不会进入\");

//根据字段查询是否有相同数据

Wrapper\<GongyinghsangEntity\> queryWrapper = new
EntityWrapper\<GongyinghsangEntity\>()

.notIn(\"id\",gongyinghsang.getId())

.andNew()

.eq(\"gongyinghsang_name\", gongyinghsang.getGongyinghsangName())

.eq(\"gongyinghsang_types\", gongyinghsang.getGongyinghsangTypes())

.eq(\"gongyinghsang_xinyong_types\",
gongyinghsang.getGongyinghsangXinyongTypes())

;

logger.info(\"sql语句:\"+queryWrapper.getSqlSegment());

GongyinghsangEntity gongyinghsangEntity =
gongyinghsangService.selectOne(queryWrapper);

if(gongyinghsangEntity==null){

gongyinghsangService.updateById(gongyinghsang);//根据id更新

return R.ok();

}else {

return R.error(511,\"表中有相同数据\");

}

}

/\*\*

\* 删除

\*/

\@RequestMapping(\"/delete\")

public R delete(@RequestBody Integer\[\] ids){

logger.debug(\"delete:,,Controller:{},,ids:{}\",this.getClass().getName(),ids.toString());

gongyinghsangService.deleteBatchIds(Arrays.asList(ids));

return R.ok();

}

出入库模块：

/\*\*

\* 后端列表

\*/

\@RequestMapping(\"/page\")

public R page(@RequestParam Map\<String, Object\> params,
HttpServletRequest request){

logger.debug(\"page方法:,,Controller:{},,params:{}\",this.getClass().getName(),JSONObject.toJSONString(params));

String role =
String.valueOf(request.getSession().getAttribute(\"role\"));

if(false)

return R.error(511,\"永不会进入\");

else if(\"员工\".equals(role))

params.put(\"yonghuId\",request.getSession().getAttribute(\"userId\"));

if(params.get(\"orderBy\")==null \|\| params.get(\"orderBy\")==\"\"){

params.put(\"orderBy\",\"id\");

}

PageUtils page = goodsChuruInoutService.queryPage(params);

//字典表数据转换

List\<GoodsChuruInoutView\> list
=(List\<GoodsChuruInoutView\>)page.getList();

for(GoodsChuruInoutView c:list){

//修改对应字典表字段

dictionaryService.dictionaryConvert(c, request);

}

return R.ok().put(\"data\", page);

}

/\*\*

\* 后端详情

\*/

\@RequestMapping(\"/info/{id}\")

public R info(@PathVariable(\"id\") Long id, HttpServletRequest
request){

logger.debug(\"info方法:,,Controller:{},,id:{}\",this.getClass().getName(),id);

GoodsChuruInoutEntity goodsChuruInout =
goodsChuruInoutService.selectById(id);

if(goodsChuruInout !=null){

//entity转view

GoodsChuruInoutView view = new GoodsChuruInoutView();

BeanUtils.copyProperties( goodsChuruInout , view
);//把实体数据重构到view中

//修改对应字典表字段

dictionaryService.dictionaryConvert(view, request);

return R.ok().put(\"data\", view);

}else {

return R.error(511,\"查不到数据\");

}

}

/\*\*

\* 后端保存

\*/

\@RequestMapping(\"/save\")

public R save(@RequestBody GoodsChuruInoutEntity goodsChuruInout,
HttpServletRequest request){

logger.debug(\"save方法:,,Controller:{},,goodsChuruInout:{}\",this.getClass().getName(),goodsChuruInout.toString());

String role =
String.valueOf(request.getSession().getAttribute(\"role\"));

if(false)

return R.error(511,\"永远不会进入\");

Wrapper\<GoodsChuruInoutEntity\> queryWrapper = new
EntityWrapper\<GoodsChuruInoutEntity\>()

.eq(\"goods_churu_inout_uuid_number\",
goodsChuruInout.getGoodsChuruInoutUuidNumber())

.eq(\"goods_churu_inout_name\",
goodsChuruInout.getGoodsChuruInoutName())

.eq(\"goods_churu_inout_types\",
goodsChuruInout.getGoodsChuruInoutTypes())

;

logger.info(\"sql语句:\"+queryWrapper.getSqlSegment());

GoodsChuruInoutEntity goodsChuruInoutEntity =
goodsChuruInoutService.selectOne(queryWrapper);

if(goodsChuruInoutEntity==null){

goodsChuruInout.setInsertTime(new Date());

goodsChuruInout.setCreateTime(new Date());

goodsChuruInoutService.insert(goodsChuruInout);

return R.ok();

}else {

return R.error(511,\"表中有相同数据\");

}

}

/\*\*

\* 后端修改

\*/

\@RequestMapping(\"/update\")

public R update(@RequestBody GoodsChuruInoutEntity goodsChuruInout,
HttpServletRequest request){

logger.debug(\"update方法:,,Controller:{},,goodsChuruInout:{}\",this.getClass().getName(),goodsChuruInout.toString());

String role =
String.valueOf(request.getSession().getAttribute(\"role\"));

//根据字段查询是否有相同数据

Wrapper\<GoodsChuruInoutEntity\> queryWrapper = new
EntityWrapper\<GoodsChuruInoutEntity\>()

.notIn(\"id\",goodsChuruInout.getId())

.andNew()

.eq(\"goods_churu_inout_uuid_number\",
goodsChuruInout.getGoodsChuruInoutUuidNumber())

.eq(\"goods_churu_inout_name\",
goodsChuruInout.getGoodsChuruInoutName())

.eq(\"goods_churu_inout_types\",
goodsChuruInout.getGoodsChuruInoutTypes())

;

logger.info(\"sql语句:\"+queryWrapper.getSqlSegment());

GoodsChuruInoutEntity goodsChuruInoutEntity =
goodsChuruInoutService.selectOne(queryWrapper);

if(goodsChuruInoutEntity==null){

goodsChuruInoutService.updateById(goodsChuruInout);//根据id更新

return R.ok();

}else {

return R.error(511,\"表中有相同数据\");

}

}

/\*\*

\* 出库

\*/

\@RequestMapping(\"/outGoodsChuruInoutList\")

public R outGoodsChuruInoutList(@RequestBody Map\<String, Object\>
params,HttpServletRequest request){

logger.debug(\"outGoodsChuruInoutList方法:,,Controller:{},,params:{}\",this.getClass().getName(),JSONObject.toJSONString(params));

String role =
String.valueOf(request.getSession().getAttribute(\"role\"));

//取出入库名称并判断是否存在

String goodsChuruInoutName =
String.valueOf(params.get(\"goodsChuruInoutName\"));

Wrapper\<GoodsChuruInoutEntity\> queryWrapper = new
EntityWrapper\<GoodsChuruInoutEntity\>()

.eq(\"goods_churu_inout_name\", goodsChuruInoutName)

;

GoodsChuruInoutEntity goodsChuruInoutSelectOne =
goodsChuruInoutService.selectOne(queryWrapper);

if(goodsChuruInoutSelectOne != null)

return R.error(511,\"出入库名称已被使用\");

//取当前表的级联表并判断是否前台传入

Map\<String, Integer\> map = (Map\<String, Integer\>)
params.get(\"map\");

if(map == null \|\| map.size() == 0)

return R.error(511,\"列表内容不能为空\");

Set\<String\> ids = map.keySet();

List\<GoodsEntity\> goodsList = goodsService.selectBatchIds(ids);

if(goodsList == null \|\| goodsList.size() == 0){

return R.error(511,\"查数据库查不到数据\");

}else{

for(GoodsEntity w:goodsList){

Integer value =
w.getGoodsKucunNumber()-map.get(String.valueOf(w.getId()));

if(value \<0){

return R.error(511,\"出库数量大于库存数量\");

}

w.setGoodsKucunNumber(value);

}

}

//当前表

GoodsChuruInoutEntity goodsChuruInoutEntity = new
GoodsChuruInoutEntity\<\>();

goodsChuruInoutEntity.setGoodsChuruInoutUuidNumber(String.valueOf(new
Date().getTime()));

goodsChuruInoutEntity.setGoodsChuruInoutName(goodsChuruInoutName);

goodsChuruInoutEntity.setGoodsChuruInoutTypes(1);

goodsChuruInoutEntity.setGoodsChuruInoutContent(\"\");

goodsChuruInoutEntity.setInsertTime(new Date());

goodsChuruInoutEntity.setCreateTime(new Date());

boolean insertGoodsChuruInout =
goodsChuruInoutService.insert(goodsChuruInoutEntity);

if(insertGoodsChuruInout){

//级联表

ArrayList\<GoodsChuruInoutListEntity\> goodsChuruInoutLists = new
ArrayList\<\>();

for(String id:ids){

GoodsChuruInoutListEntity goodsChuruInoutListEntity = new
GoodsChuruInoutListEntity();

goodsChuruInoutListEntity.setGoodsChuruInoutId(goodsChuruInoutEntity.getId());

goodsChuruInoutListEntity.setGoodsId(Integer.valueOf(id));

goodsChuruInoutListEntity.setGoodsChuruInoutListNumber(map.get(id));

goodsChuruInoutListEntity.setInsertTime(new Date());

goodsChuruInoutListEntity.setCreateTime(new Date());

goodsChuruInoutLists.add(goodsChuruInoutListEntity);

goodsService.updateBatchById(goodsList);

}

goodsChuruInoutListService.insertBatch(goodsChuruInoutLists);

}

return R.ok();

}

/\*\*

\*入库

\*/

\@RequestMapping(\"/inGoodsChuruInoutList\")

public R inGoodsChuruInoutList(@RequestBody Map\<String, Object\>
params,HttpServletRequest request){

logger.debug(\"inGoodsChuruInoutList方法:,,Controller:{},,params:{}\",this.getClass().getName(),JSONObject.toJSONString(params));

//params:{\"map\":{\"1\":2,\"2\":3},\"wuziOutinName\":\"订单1\"}

String role =
String.valueOf(request.getSession().getAttribute(\"role\"));

//取当前表名称并判断

String goodsChuruInoutName =
String.valueOf(params.get(\"goodsChuruInoutName\"));

Wrapper\<GoodsChuruInoutEntity\> queryWrapper = new
EntityWrapper\<GoodsChuruInoutEntity\>()

.eq(\"goods_churu_inout_name\", goodsChuruInoutName)

;

GoodsChuruInoutEntity goodsChuruInoutSelectOne =
goodsChuruInoutService.selectOne(queryWrapper);

if(goodsChuruInoutSelectOne != null)

return R.error(511,\"出入库名称已被使用\");

//取当前表的级联表并判断是否前台传入

Map\<String, Integer\> map = (Map\<String, Integer\>)
params.get(\"map\");

if(map == null \|\| map.size() == 0)

return R.error(511,\"列表内容不能为空\");

Set\<String\> ids = map.keySet();

List\<GoodsEntity\> goodsList = goodsService.selectBatchIds(ids);

if(goodsList == null \|\| goodsList.size() == 0){

return R.error(511,\"查数据库查不到数据\");

}else{

for(GoodsEntity w:goodsList){

w.setGoodsKucunNumber(w.getGoodsKucunNumber()+map.get(String.valueOf(w.getId())));

}

}

//当前表

GoodsChuruInoutEntity goodsChuruInoutEntity = new
GoodsChuruInoutEntity\<\>();

goodsChuruInoutEntity.setGoodsChuruInoutUuidNumber(String.valueOf(new
Date().getTime()));

goodsChuruInoutEntity.setGoodsChuruInoutName(goodsChuruInoutName);

goodsChuruInoutEntity.setGoodsChuruInoutTypes(2);

goodsChuruInoutEntity.setGoodsChuruInoutContent(\"\");

goodsChuruInoutEntity.setInsertTime(new Date());

goodsChuruInoutEntity.setCreateTime(new Date());

boolean insertGoodsChuruInout =
goodsChuruInoutService.insert(goodsChuruInoutEntity);

if(insertGoodsChuruInout){

//级联表

ArrayList\<GoodsChuruInoutListEntity\> goodsChuruInoutLists = new
ArrayList\<\>();

for(String id:ids){

GoodsChuruInoutListEntity goodsChuruInoutListEntity = new
GoodsChuruInoutListEntity();

goodsChuruInoutListEntity.setGoodsChuruInoutId(goodsChuruInoutEntity.getId());

goodsChuruInoutListEntity.setGoodsId(Integer.valueOf(id));

goodsChuruInoutListEntity.setGoodsChuruInoutListNumber(map.get(id));

goodsChuruInoutListEntity.setInsertTime(new Date());

goodsChuruInoutListEntity.setCreateTime(new Date());

goodsChuruInoutLists.add(goodsChuruInoutListEntity);

goodsService.updateBatchById(goodsList);

}

goodsChuruInoutListService.insertBatch(goodsChuruInoutLists);

}

return R.ok();

}

/\*\*

\* 删除

\*/

\@RequestMapping(\"/delete\")

public R delete(@RequestBody Integer\[\] ids){

logger.debug(\"delete:,,Controller:{},,ids:{}\",this.getClass().getName(),ids.toString());

goodsChuruInoutService.deleteBatchIds(Arrays.asList(ids));

goodsChuruInoutListService.delete(new
EntityWrapper\<GoodsChuruInoutListEntity\>().in(\"goods_churu_inout_id\",ids));

return R.ok();

}

出入库详情模块：

/\*\*

\* 后端列表

\*/

\@RequestMapping(\"/page\")

public R page(@RequestParam Map\<String, Object\> params,
HttpServletRequest request){

logger.debug(\"page方法:,,Controller:{},,params:{}\",this.getClass().getName(),JSONObject.toJSONString(params));

String role =
String.valueOf(request.getSession().getAttribute(\"role\"));

if(false)

return R.error(511,\"永不会进入\");

else if(\"员工\".equals(role))

params.put(\"yonghuId\",request.getSession().getAttribute(\"userId\"));

if(params.get(\"orderBy\")==null \|\| params.get(\"orderBy\")==\"\"){

params.put(\"orderBy\",\"id\");

}

PageUtils page = goodsChuruInoutListService.queryPage(params);

//字典表数据转换

List\<GoodsChuruInoutListView\> list
=(List\<GoodsChuruInoutListView\>)page.getList();

for(GoodsChuruInoutListView c:list){

//修改对应字典表字段

dictionaryService.dictionaryConvert(c, request);

}

return R.ok().put(\"data\", page);

}

/\*\*

\* 后端详情

\*/

\@RequestMapping(\"/info/{id}\")

public R info(@PathVariable(\"id\") Long id, HttpServletRequest
request){

logger.debug(\"info方法:,,Controller:{},,id:{}\",this.getClass().getName(),id);

GoodsChuruInoutListEntity goodsChuruInoutList =
goodsChuruInoutListService.selectById(id);

if(goodsChuruInoutList !=null){

//entity转view

GoodsChuruInoutListView view = new GoodsChuruInoutListView();

BeanUtils.copyProperties( goodsChuruInoutList , view
);//把实体数据重构到view中

//级联表

GoodsEntity goods =
goodsService.selectById(goodsChuruInoutList.getGoodsId());

if(goods != null){

BeanUtils.copyProperties( goods , view ,new String\[\]{ \"id\",
\"createTime\", \"insertTime\",
\"updateTime\"});//把级联的数据添加到view中,并排除id和创建时间字段

view.setGoodsId(goods.getId());

}

//级联表

GoodsChuruInoutEntity goodsChuruInout =
goodsChuruInoutService.selectById(goodsChuruInoutList.getGoodsChuruInoutId());

if(goodsChuruInout != null){

BeanUtils.copyProperties( goodsChuruInout , view ,new String\[\]{
\"id\", \"createTime\", \"insertTime\",
\"updateTime\"});//把级联的数据添加到view中,并排除id和创建时间字段

view.setGoodsChuruInoutId(goodsChuruInout.getId());

}

//修改对应字典表字段

dictionaryService.dictionaryConvert(view, request);

return R.ok().put(\"data\", view);

}else {

return R.error(511,\"查不到数据\");

}

}

/\*\*

\* 后端保存

\*/

\@RequestMapping(\"/save\")

public R save(@RequestBody GoodsChuruInoutListEntity
goodsChuruInoutList, HttpServletRequest request){

logger.debug(\"save方法:,,Controller:{},,goodsChuruInoutList:{}\",this.getClass().getName(),goodsChuruInoutList.toString());

String role =
String.valueOf(request.getSession().getAttribute(\"role\"));

if(false)

return R.error(511,\"永远不会进入\");

Wrapper\<GoodsChuruInoutListEntity\> queryWrapper = new
EntityWrapper\<GoodsChuruInoutListEntity\>()

.eq(\"goods_churu_inout_id\",
goodsChuruInoutList.getGoodsChuruInoutId())

.eq(\"goods_id\", goodsChuruInoutList.getGoodsId())

.eq(\"goods_churu_inout_list_number\",
goodsChuruInoutList.getGoodsChuruInoutListNumber())

;

logger.info(\"sql语句:\"+queryWrapper.getSqlSegment());

GoodsChuruInoutListEntity goodsChuruInoutListEntity =
goodsChuruInoutListService.selectOne(queryWrapper);

if(goodsChuruInoutListEntity==null){

goodsChuruInoutList.setInsertTime(new Date());

goodsChuruInoutList.setCreateTime(new Date());

goodsChuruInoutListService.insert(goodsChuruInoutList);

return R.ok();

}else {

return R.error(511,\"表中有相同数据\");

}

}

/\*\*

\* 后端修改

\*/

\@RequestMapping(\"/update\")

public R update(@RequestBody GoodsChuruInoutListEntity
goodsChuruInoutList, HttpServletRequest request){

logger.debug(\"update方法:,,Controller:{},,goodsChuruInoutList:{}\",this.getClass().getName(),goodsChuruInoutList.toString());

String role =
String.valueOf(request.getSession().getAttribute(\"role\"));

// if(false)

// return R.error(511,\"永远不会进入\");

//根据字段查询是否有相同数据

Wrapper\<GoodsChuruInoutListEntity\> queryWrapper = new
EntityWrapper\<GoodsChuruInoutListEntity\>()

.notIn(\"id\",goodsChuruInoutList.getId())

.andNew()

.eq(\"goods_churu_inout_id\",
goodsChuruInoutList.getGoodsChuruInoutId())

.eq(\"goods_id\", goodsChuruInoutList.getGoodsId())

.eq(\"goods_churu_inout_list_number\",
goodsChuruInoutList.getGoodsChuruInoutListNumber())

;

logger.info(\"sql语句:\"+queryWrapper.getSqlSegment());

GoodsChuruInoutListEntity goodsChuruInoutListEntity =
goodsChuruInoutListService.selectOne(queryWrapper);

if(goodsChuruInoutListEntity==null){

goodsChuruInoutListService.updateById(goodsChuruInoutList);//根据id更新

return R.ok();

}else {

return R.error(511,\"表中有相同数据\");

}

}

/\*\*

\* 删除

\*/

\@RequestMapping(\"/delete\")

public R delete(@RequestBody Integer\[\] ids){

logger.debug(\"delete:,,Controller:{},,ids:{}\",this.getClass().getName(),ids.toString());

goodsChuruInoutListService.deleteBatchIds(Arrays.asList(ids));

return R.ok();

}

商品模块：

\@RequestMapping(\"/page\")

public R page(@RequestParam Map\<String, Object\> params,
HttpServletRequest request){

logger.debug(\"page方法:,,Controller:{},,params:{}\",this.getClass().getName(),JSONObject.toJSONString(params));

String role =
String.valueOf(request.getSession().getAttribute(\"role\"));

if(false)

return R.error(511,\"永不会进入\");

else if(\"员工\".equals(role))

params.put(\"yonghuId\",request.getSession().getAttribute(\"userId\"));

if(params.get(\"orderBy\")==null \|\| params.get(\"orderBy\")==\"\"){

params.put(\"orderBy\",\"id\");

}

PageUtils page = goodsService.queryPage(params);

//字典表数据转换

List\<GoodsView\> list =(List\<GoodsView\>)page.getList();

for(GoodsView c:list){

//修改对应字典表字段

dictionaryService.dictionaryConvert(c, request);

}

return R.ok().put(\"data\", page);

}

/\*\*

\* 后端详情

\*/

\@RequestMapping(\"/info/{id}\")

public R info(@PathVariable(\"id\") Long id, HttpServletRequest
request){

logger.debug(\"info方法:,,Controller:{},,id:{}\",this.getClass().getName(),id);

GoodsEntity goods = goodsService.selectById(id);

if(goods !=null){

//entity转view

GoodsView view = new GoodsView();

BeanUtils.copyProperties( goods , view );//把实体数据重构到view中

//级联表

GongyinghsangEntity gongyinghsang =
gongyinghsangService.selectById(goods.getGongyinghsangId());

if(gongyinghsang != null){

BeanUtils.copyProperties( gongyinghsang , view ,new String\[\]{ \"id\",
\"createTime\", \"insertTime\",
\"updateTime\"});//把级联的数据添加到view中,并排除id和创建时间字段

view.setGongyinghsangId(gongyinghsang.getId());

}

//修改对应字典表字段

dictionaryService.dictionaryConvert(view, request);

return R.ok().put(\"data\", view);

}else {

return R.error(511,\"查不到数据\");

}

}

/\*\*

\* 后端保存

\*/

\@RequestMapping(\"/save\")

public R save(@RequestBody GoodsEntity goods, HttpServletRequest
request){

logger.debug(\"save方法:,,Controller:{},,goods:{}\",this.getClass().getName(),goods.toString());

String role =
String.valueOf(request.getSession().getAttribute(\"role\"));

if(false)

return R.error(511,\"永远不会进入\");

Wrapper\<GoodsEntity\> queryWrapper = new EntityWrapper\<GoodsEntity\>()

.eq(\"goods_name\", goods.getGoodsName())

.eq(\"goods_types\", goods.getGoodsTypes())

.eq(\"goods_kucun_number\", goods.getGoodsKucunNumber())

.eq(\"gongyinghsang_id\", goods.getGongyinghsangId())

.eq(\"cangku_types\", goods.getCangkuTypes())

.eq(\"danwei\", goods.getDanwei())

;

logger.info(\"sql语句:\"+queryWrapper.getSqlSegment());

GoodsEntity goodsEntity = goodsService.selectOne(queryWrapper);

if(goodsEntity==null){

goods.setCreateTime(new Date());

goodsService.insert(goods);

return R.ok();

}else {

return R.error(511,\"表中有相同数据\");

}

}

/\*\*

\* 后端修改

\*/

\@RequestMapping(\"/update\")

public R update(@RequestBody GoodsEntity goods, HttpServletRequest
request){

logger.debug(\"update方法:,,Controller:{},,goods:{}\",this.getClass().getName(),goods.toString());

String role =
String.valueOf(request.getSession().getAttribute(\"role\"));

//根据字段查询是否有相同数据

Wrapper\<GoodsEntity\> queryWrapper = new EntityWrapper\<GoodsEntity\>()

.notIn(\"id\",goods.getId())

.andNew()

.eq(\"goods_name\", goods.getGoodsName())

.eq(\"goods_types\", goods.getGoodsTypes())

.eq(\"goods_kucun_number\", goods.getGoodsKucunNumber())

.eq(\"gongyinghsang_id\", goods.getGongyinghsangId())

.eq(\"cangku_types\", goods.getCangkuTypes())

.eq(\"danwei\", goods.getDanwei())

;

logger.info(\"sql语句:\"+queryWrapper.getSqlSegment());

GoodsEntity goodsEntity = goodsService.selectOne(queryWrapper);

if(goodsEntity==null){

goodsService.updateById(goods);//根据id更新

return R.ok();

}else {

return R.error(511,\"表中有相同数据\");

}

}

/\*\*

\* 删除

\*/

\@RequestMapping(\"/delete\")

public R delete(@RequestBody Integer\[\] ids){

logger.debug(\"delete:,,Controller:{},,ids:{}\",this.getClass().getName(),ids.toString());

goodsService.deleteBatchIds(Arrays.asList(ids));

return R.ok();

}

商品预订模块：

\@RequestMapping(\"/page\")

public R page(@RequestParam Map\<String, Object\> params,
HttpServletRequest request){

logger.debug(\"page方法:,,Controller:{},,params:{}\",this.getClass().getName(),JSONObject.toJSONString(params));

String role =
String.valueOf(request.getSession().getAttribute(\"role\"));

if(false)

return R.error(511,\"永不会进入\");

else if(\"员工\".equals(role))

params.put(\"yonghuId\",request.getSession().getAttribute(\"userId\"));

if(params.get(\"orderBy\")==null \|\| params.get(\"orderBy\")==\"\"){

params.put(\"orderBy\",\"id\");

}

PageUtils page = goodsOrderService.queryPage(params);

//字典表数据转换

List\<GoodsOrderView\> list =(List\<GoodsOrderView\>)page.getList();

for(GoodsOrderView c:list){

//修改对应字典表字段

dictionaryService.dictionaryConvert(c, request);

}

return R.ok().put(\"data\", page);

}

/\*\*

\* 后端详情

\*/

\@RequestMapping(\"/info/{id}\")

public R info(@PathVariable(\"id\") Long id, HttpServletRequest
request){

logger.debug(\"info方法:,,Controller:{},,id:{}\",this.getClass().getName(),id);

GoodsOrderEntity goodsOrder = goodsOrderService.selectById(id);

if(goodsOrder !=null){

//entity转view

GoodsOrderView view = new GoodsOrderView();

BeanUtils.copyProperties( goodsOrder , view );//把实体数据重构到view中

//级联表

GoodsEntity goods = goodsService.selectById(goodsOrder.getGoodsId());

if(goods != null){

BeanUtils.copyProperties( goods , view ,new String\[\]{ \"id\",
\"createTime\", \"insertTime\",
\"updateTime\"});//把级联的数据添加到view中,并排除id和创建时间字段

view.setGoodsId(goods.getId());

}

//级联表

KehuEntity kehu = kehuService.selectById(goodsOrder.getKehuId());

if(kehu != null){

BeanUtils.copyProperties( kehu , view ,new String\[\]{ \"id\",
\"createTime\", \"insertTime\",
\"updateTime\"});//把级联的数据添加到view中,并排除id和创建时间字段

view.setKehuId(kehu.getId());

}

//级联表

YonghuEntity yonghu =
yonghuService.selectById(goodsOrder.getYonghuId());

if(yonghu != null){

BeanUtils.copyProperties( yonghu , view ,new String\[\]{ \"id\",
\"createTime\", \"insertTime\",
\"updateTime\"});//把级联的数据添加到view中,并排除id和创建时间字段

view.setYonghuId(yonghu.getId());

}

//修改对应字典表字段

dictionaryService.dictionaryConvert(view, request);

return R.ok().put(\"data\", view);

}else {

return R.error(511,\"查不到数据\");

}

}

/\*\*

\* 后端保存

\*/

\@RequestMapping(\"/save\")

public R save(@RequestBody GoodsOrderEntity goodsOrder,
HttpServletRequest request){

logger.debug(\"save方法:,,Controller:{},,goodsOrder:{}\",this.getClass().getName(),goodsOrder.toString());

String role =
String.valueOf(request.getSession().getAttribute(\"role\"));

if(false)

return R.error(511,\"永远不会进入\");

else if(\"员工\".equals(role))

goodsOrder.setYonghuId(Integer.valueOf(String.valueOf(request.getSession().getAttribute(\"userId\"))));

GoodsEntity goodsEntity =
goodsService.selectById(goodsOrder.getGoodsId());

if(goodsEntity.getGoodsKucunNumber() \<
goodsOrder.getGoodsOrderNumber()){

return R.error(\"库存不足\");

}

goodsEntity.setGoodsKucunNumber(goodsEntity.getGoodsKucunNumber() -
goodsOrder.getGoodsOrderNumber());

goodsService.updateById(goodsEntity);

goodsOrder.setCreateTime(new Date());

goodsOrderService.insert(goodsOrder);

return R.ok();

}

/\*\*

\* 后端修改

\*/

\@RequestMapping(\"/update\")

public R update(@RequestBody GoodsOrderEntity goodsOrder,
HttpServletRequest request){

logger.debug(\"update方法:,,Controller:{},,goodsOrder:{}\",this.getClass().getName(),goodsOrder.toString());

String role =
String.valueOf(request.getSession().getAttribute(\"role\"));

goodsOrder.setYonghuId(Integer.valueOf(String.valueOf(request.getSession().getAttribute(\"userId\"))));

//根据字段查询是否有相同数据

Wrapper\<GoodsOrderEntity\> queryWrapper = new
EntityWrapper\<GoodsOrderEntity\>()

.eq(\"id\",0)

;

logger.info(\"sql语句:\"+queryWrapper.getSqlSegment());

GoodsOrderEntity goodsOrderEntity =
goodsOrderService.selectOne(queryWrapper);

if(goodsOrderEntity==null){

goodsOrderService.updateById(goodsOrder);//根据id更新

return R.ok();

}else {

return R.error(511,\"表中有相同数据\");

}

}

/\*\*

\* 删除

\*/

\@RequestMapping(\"/delete\")

public R delete(@RequestBody Integer\[\] ids){

logger.debug(\"delete:,,Controller:{},,ids:{}\",this.getClass().getName(),ids.toString());

goodsOrderService.deleteBatchIds(Arrays.asList(ids));

return R.ok();

}

客户模块：

\@RequestMapping(\"/page\")

public R page(@RequestParam Map\<String, Object\> params,
HttpServletRequest request){

logger.debug(\"page方法:,,Controller:{},,params:{}\",this.getClass().getName(),JSONObject.toJSONString(params));

String role =
String.valueOf(request.getSession().getAttribute(\"role\"));

if(false)

return R.error(511,\"永不会进入\");

else if(\"员工\".equals(role))

params.put(\"yonghuId\",request.getSession().getAttribute(\"userId\"));

if(params.get(\"orderBy\")==null \|\| params.get(\"orderBy\")==\"\"){

params.put(\"orderBy\",\"id\");

}

PageUtils page = kehuService.queryPage(params);

//字典表数据转换

List\<KehuView\> list =(List\<KehuView\>)page.getList();

for(KehuView c:list){

//修改对应字典表字段

dictionaryService.dictionaryConvert(c, request);

}

return R.ok().put(\"data\", page);

}

/\*\*

\* 后端详情

\*/

\@RequestMapping(\"/info/{id}\")

public R info(@PathVariable(\"id\") Long id, HttpServletRequest
request){

logger.debug(\"info方法:,,Controller:{},,id:{}\",this.getClass().getName(),id);

KehuEntity kehu = kehuService.selectById(id);

if(kehu !=null){

//entity转view

KehuView view = new KehuView();

BeanUtils.copyProperties( kehu , view );//把实体数据重构到view中

//修改对应字典表字段

dictionaryService.dictionaryConvert(view, request);

return R.ok().put(\"data\", view);

}else {

return R.error(511,\"查不到数据\");

}

}

/\*\*

\* 后端保存

\*/

\@RequestMapping(\"/save\")

public R save(@RequestBody KehuEntity kehu, HttpServletRequest request){

logger.debug(\"save方法:,,Controller:{},,kehu:{}\",this.getClass().getName(),kehu.toString());

String role =
String.valueOf(request.getSession().getAttribute(\"role\"));

if(false)

return R.error(511,\"永远不会进入\");

Wrapper\<KehuEntity\> queryWrapper = new EntityWrapper\<KehuEntity\>()

.eq(\"kehu_name\", kehu.getKehuName())

.eq(\"kehu_phone\", kehu.getKehuPhone())

.eq(\"sex_types\", kehu.getSexTypes())

;

logger.info(\"sql语句:\"+queryWrapper.getSqlSegment());

KehuEntity kehuEntity = kehuService.selectOne(queryWrapper);

if(kehuEntity==null){

kehu.setCreateTime(new Date());

kehuService.insert(kehu);

return R.ok();

}else {

return R.error(511,\"表中有相同数据\");

}

}

/\*\*

\* 后端修改

\*/

\@RequestMapping(\"/update\")

public R update(@RequestBody KehuEntity kehu, HttpServletRequest
request){

logger.debug(\"update方法:,,Controller:{},,kehu:{}\",this.getClass().getName(),kehu.toString());

String role =
String.valueOf(request.getSession().getAttribute(\"role\"));

// if(false)

// return R.error(511,\"永远不会进入\");

//根据字段查询是否有相同数据

Wrapper\<KehuEntity\> queryWrapper = new EntityWrapper\<KehuEntity\>()

.notIn(\"id\",kehu.getId())

.andNew()

.eq(\"kehu_name\", kehu.getKehuName())

.eq(\"kehu_phone\", kehu.getKehuPhone())

.eq(\"sex_types\", kehu.getSexTypes())

;

logger.info(\"sql语句:\"+queryWrapper.getSqlSegment());

KehuEntity kehuEntity = kehuService.selectOne(queryWrapper);

if(kehuEntity==null){

kehuService.updateById(kehu);//根据id更新

return R.ok();

}else {

return R.error(511,\"表中有相同数据\");

}

}

/\*\*

\* 删除

\*/

\@RequestMapping(\"/delete\")

public R delete(@RequestBody Integer\[\] ids){

logger.debug(\"delete:,,Controller:{},,ids:{}\",this.getClass().getName(),ids.toString());

kehuService.deleteBatchIds(Arrays.asList(ids));

return R.ok();

}

公告模块：

\@RequestMapping(\"/page\")

public R page(@RequestParam Map\<String, Object\> params,
HttpServletRequest request){

logger.debug(\"page方法:,,Controller:{},,params:{}\",this.getClass().getName(),JSONObject.toJSONString(params));

String role =
String.valueOf(request.getSession().getAttribute(\"role\"));

if(false)

return R.error(511,\"永不会进入\");

else if(\"员工\".equals(role))

params.put(\"yonghuId\",request.getSession().getAttribute(\"userId\"));

if(params.get(\"orderBy\")==null \|\| params.get(\"orderBy\")==\"\"){

params.put(\"orderBy\",\"id\");

}

PageUtils page = newsService.queryPage(params);

//字典表数据转换

List\<NewsView\> list =(List\<NewsView\>)page.getList();

for(NewsView c:list){

//修改对应字典表字段

dictionaryService.dictionaryConvert(c, request);

}

return R.ok().put(\"data\", page);

}

/\*\*

\* 后端详情

\*/

\@RequestMapping(\"/info/{id}\")

public R info(@PathVariable(\"id\") Long id, HttpServletRequest
request){

logger.debug(\"info方法:,,Controller:{},,id:{}\",this.getClass().getName(),id);

NewsEntity news = newsService.selectById(id);

if(news !=null){

//entity转view

NewsView view = new NewsView();

BeanUtils.copyProperties( news , view );//把实体数据重构到view中

//修改对应字典表字段

dictionaryService.dictionaryConvert(view, request);

return R.ok().put(\"data\", view);

}else {

return R.error(511,\"查不到数据\");

}

}

/\*\*

\* 后端保存

\*/

\@RequestMapping(\"/save\")

public R save(@RequestBody NewsEntity news, HttpServletRequest request){

logger.debug(\"save方法:,,Controller:{},,news:{}\",this.getClass().getName(),news.toString());

String role =
String.valueOf(request.getSession().getAttribute(\"role\"));

if(false)

return R.error(511,\"永远不会进入\");

Wrapper\<NewsEntity\> queryWrapper = new EntityWrapper\<NewsEntity\>()

.eq(\"news_name\", news.getNewsName())

.eq(\"news_types\", news.getNewsTypes())

;

logger.info(\"sql语句:\"+queryWrapper.getSqlSegment());

NewsEntity newsEntity = newsService.selectOne(queryWrapper);

if(newsEntity==null){

news.setInsertTime(new Date());

news.setCreateTime(new Date());

newsService.insert(news);

return R.ok();

}else {

return R.error(511,\"表中有相同数据\");

}

}

/\*\*

\* 后端修改

\*/

\@RequestMapping(\"/update\")

public R update(@RequestBody NewsEntity news, HttpServletRequest
request){

logger.debug(\"update方法:,,Controller:{},,news:{}\",this.getClass().getName(),news.toString());

String role =
String.valueOf(request.getSession().getAttribute(\"role\"));

// if(false)

// return R.error(511,\"永远不会进入\");

//根据字段查询是否有相同数据

Wrapper\<NewsEntity\> queryWrapper = new EntityWrapper\<NewsEntity\>()

.notIn(\"id\",news.getId())

.andNew()

.eq(\"news_name\", news.getNewsName())

.eq(\"news_types\", news.getNewsTypes())

;

logger.info(\"sql语句:\"+queryWrapper.getSqlSegment());

NewsEntity newsEntity = newsService.selectOne(queryWrapper);

if(\"\".equals(news.getNewsPhoto()) \|\|
\"null\".equals(news.getNewsPhoto())){

news.setNewsPhoto(null);

}

if(newsEntity==null){

newsService.updateById(news);//根据id更新

return R.ok();

}else {

return R.error(511,\"表中有相同数据\");

}

}

/\*\*

\* 删除

\*/

\@RequestMapping(\"/delete\")

public R delete(@RequestBody Integer\[\] ids){

logger.debug(\"delete:,,Controller:{},,ids:{}\",this.getClass().getName(),ids.toString());

newsService.deleteBatchIds(Arrays.asList(ids));

return R.ok();

}

员工模块：

\@RequestMapping(\"/page\")

public R page(@RequestParam Map\<String, Object\> params,
HttpServletRequest request){

logger.debug(\"page方法:,,Controller:{},,params:{}\",this.getClass().getName(),JSONObject.toJSONString(params));

String role =
String.valueOf(request.getSession().getAttribute(\"role\"));

if(false)

return R.error(511,\"永不会进入\");

else if(\"员工\".equals(role))

params.put(\"yonghuId\",request.getSession().getAttribute(\"userId\"));

params.put(\"yonghuDeleteStart\",1);params.put(\"yonghuDeleteEnd\",1);

if(params.get(\"orderBy\")==null \|\| params.get(\"orderBy\")==\"\"){

params.put(\"orderBy\",\"id\");

}

PageUtils page = yonghuService.queryPage(params);

//字典表数据转换

List\<YonghuView\> list =(List\<YonghuView\>)page.getList();

for(YonghuView c:list){

//修改对应字典表字段

dictionaryService.dictionaryConvert(c, request);

}

return R.ok().put(\"data\", page);

}

/\*\*

\* 后端详情

\*/

\@RequestMapping(\"/info/{id}\")

public R info(@PathVariable(\"id\") Long id, HttpServletRequest
request){

logger.debug(\"info方法:,,Controller:{},,id:{}\",this.getClass().getName(),id);

YonghuEntity yonghu = yonghuService.selectById(id);

if(yonghu !=null){

//entity转view

YonghuView view = new YonghuView();

BeanUtils.copyProperties( yonghu , view );//把实体数据重构到view中

//修改对应字典表字段

dictionaryService.dictionaryConvert(view, request);

return R.ok().put(\"data\", view);

}else {

return R.error(511,\"查不到数据\");

}

}

/\*\*

\* 后端保存

\*/

\@RequestMapping(\"/save\")

public R save(@RequestBody YonghuEntity yonghu, HttpServletRequest
request){

logger.debug(\"save方法:,,Controller:{},,yonghu:{}\",this.getClass().getName(),yonghu.toString());

String role =
String.valueOf(request.getSession().getAttribute(\"role\"));

if(false)

return R.error(511,\"永远不会进入\");

Wrapper\<YonghuEntity\> queryWrapper = new
EntityWrapper\<YonghuEntity\>()

.eq(\"username\", yonghu.getUsername())

.or()

.eq(\"yonghu_phone\", yonghu.getYonghuPhone())

.andNew()

.eq(\"yonghu_delete\", 1)

;

logger.info(\"sql语句:\"+queryWrapper.getSqlSegment());

YonghuEntity yonghuEntity = yonghuService.selectOne(queryWrapper);

if(yonghuEntity==null){

yonghu.setYonghuDelete(1);

yonghu.setInsertTime(new Date());

yonghu.setCreateTime(new Date());

yonghu.setPassword(\"123456\");

yonghuService.insert(yonghu);

return R.ok();

}else {

return R.error(511,\"账户或者联系方式已经被使用\");

}

}

/\*\*

\* 后端修改

\*/

\@RequestMapping(\"/update\")

public R update(@RequestBody YonghuEntity yonghu, HttpServletRequest
request){

logger.debug(\"update方法:,,Controller:{},,yonghu:{}\",this.getClass().getName(),yonghu.toString());

String role =
String.valueOf(request.getSession().getAttribute(\"role\"));

//根据字段查询是否有相同数据

Wrapper\<YonghuEntity\> queryWrapper = new
EntityWrapper\<YonghuEntity\>()

.notIn(\"id\",yonghu.getId())

.andNew()

.eq(\"username\", yonghu.getUsername())

.or()

.eq(\"yonghu_phone\", yonghu.getYonghuPhone())

.andNew()

.eq(\"yonghu_delete\", 1)

;

logger.info(\"sql语句:\"+queryWrapper.getSqlSegment());

YonghuEntity yonghuEntity = yonghuService.selectOne(queryWrapper);

if(\"\".equals(yonghu.getYonghuPhoto()) \|\|
\"null\".equals(yonghu.getYonghuPhoto())){

yonghu.setYonghuPhoto(null);

}

if(yonghuEntity==null){

yonghuService.updateById(yonghu);//根据id更新

return R.ok();

}else {

return R.error(511,\"账户或者联系方式已经被使用\");

}

}

/\*\*

\* 删除

\*/

\@RequestMapping(\"/delete\")

public R delete(@RequestBody Integer\[\] ids){

logger.debug(\"delete:,,Controller:{},,ids:{}\",this.getClass().getName(),ids.toString());

ArrayList\<YonghuEntity\> list = new ArrayList\<\>();

for(Integer id:ids){

YonghuEntity yonghuEntity = new YonghuEntity();

yonghuEntity.setId(id);

yonghuEntity.setYonghuDelete(2);

list.add(yonghuEntity);

}

if(list != null && list.size() \>0){

yonghuService.updateBatchById(list);

}

return R.ok();

}

/\*\*

\* 登录

\*/

\@IgnoreAuth

\@RequestMapping(value = \"/login\")

public R login(String username, String password, String captcha,
HttpServletRequest request) {

YonghuEntity yonghu = yonghuService.selectOne(new
EntityWrapper\<YonghuEntity\>().eq(\"username\", username));

if(yonghu==null \|\| !yonghu.getPassword().equals(password))

return R.error(\"账号或密码不正确\");

else if(yonghu.getYonghuDelete() != 1)

return R.error(\"账户已被删除\");

// // 获取监听器中的字典表

// ServletContext servletContext =
ContextLoader.getCurrentWebApplicationContext().getServletContext();

String token = tokenService.generateToken(yonghu.getId(),username,
\"yonghu\", \"员工\");

R r = R.ok();

r.put(\"token\", token);

r.put(\"role\",\"员工\");

r.put(\"username\",yonghu.getYonghuName());

r.put(\"tableName\",\"yonghu\");

r.put(\"userId\",yonghu.getId());

return r;

}

/\*\*

\* 注册

\*/

\@IgnoreAuth

\@PostMapping(value = \"/register\")

public R register(@RequestBody YonghuEntity yonghu){

Wrapper\<YonghuEntity\> queryWrapper = new
EntityWrapper\<YonghuEntity\>()

.eq(\"username\", yonghu.getUsername())

.or()

.eq(\"yonghu_phone\", yonghu.getYonghuPhone())

.andNew()

.eq(\"yonghu_delete\", 1)

;

YonghuEntity yonghuEntity = yonghuService.selectOne(queryWrapper);

if(yonghuEntity != null)

return R.error(\"账户或者联系方式已经被使用\");

yonghu.setYonghuDelete(1);

yonghu.setInsertTime(new Date());

yonghu.setCreateTime(new Date());

yonghuService.insert(yonghu);

return R.ok();

}

/\*\*

\* 重置密码

\*/

\@GetMapping(value = \"/resetPassword\")

public R resetPassword(Integer id){

YonghuEntity yonghu = new YonghuEntity();

yonghu.setPassword(\"123456\");

yonghu.setId(id);

yonghu.setInsertTime(new Date());

yonghuService.updateById(yonghu);

return R.ok();

}

/\*\*

\* 忘记密码

\*/

\@IgnoreAuth

\@RequestMapping(value = \"/resetPass\")

public R resetPass(String username, HttpServletRequest request) {

YonghuEntity yonghu = yonghuService.selectOne(new
EntityWrapper\<YonghuEntity\>().eq(\"username\", username));

if(yonghu!=null){

yonghu.setPassword(\"123456\");

boolean b = yonghuService.updateById(yonghu);

if(!b){

return R.error();

}

}else{

return R.error(\"账号不存在\");

}

return R.ok();

}

/\*\*

\* 获取用户的session用户信息

\*/

\@RequestMapping(\"/session\")

public R getCurrYonghu(HttpServletRequest request){

Integer id = (Integer)request.getSession().getAttribute(\"userId\");

YonghuEntity yonghu = yonghuService.selectById(id);

if(yonghu !=null){

//entity转view

YonghuView view = new YonghuView();

BeanUtils.copyProperties( yonghu , view );//把实体数据重构到view中

//修改对应字典表字段

dictionaryService.dictionaryConvert(view, request);

return R.ok().put(\"data\", view);

}else {

return R.error(511,\"查不到数据\");

}

}

/\*\*

\* 退出

\*/

\@GetMapping(value = \"logout\")

public R logout(HttpServletRequest request) {

request.getSession().invalidate();

return R.ok(\"退出成功\");

}

管理员模块：

/\*\*

\* 登录

\*/

\@IgnoreAuth

\@PostMapping(value = \"/login\")

public R login(String username, String password, String captcha,
HttpServletRequest request) {

UsersEntity user = usersService.selectOne(new
EntityWrapper\<UsersEntity\>().eq(\"username\", username));

if(user==null \|\| !user.getPassword().equals(password)) {

return R.error(\"账号或密码不正确\");

}

String token = tokenService.generateToken(user.getId(),username,
\"users\", user.getRole());

R r = R.ok();

r.put(\"token\", token);

r.put(\"role\",user.getRole());

r.put(\"userId\",user.getId());

return r;

}

/\*\*

\* 退出

\*/

\@GetMapping(value = \"logout\")

public R logout(HttpServletRequest request) {

request.getSession().invalidate();

return R.ok(\"退出成功\");

}

/\*\*

\* 密码重置

\*/

\@IgnoreAuth

\@RequestMapping(value = \"/resetPass\")

public R resetPass(String username, HttpServletRequest request){

UsersEntity user = usersService.selectOne(new
EntityWrapper\<UsersEntity\>().eq(\"username\", username));

if(user==null) {

return R.error(\"账号不存在\");

}

user.setPassword(\"123456\");

usersService.update(user,null);

return R.ok(\"密码已重置为：123456\");

}

/\*\*

\* 获取用户的session用户信息

\*/

\@RequestMapping(\"/session\")

public R getCurrUser(HttpServletRequest request){

Integer id = (Integer)request.getSession().getAttribute(\"userId\");

UsersEntity user = usersService.selectById(id);

return R.ok().put(\"data\", user);

}

/\*\*

\* 修改

\*/

\@RequestMapping(\"/update\")

public R update(@RequestBody UsersEntity user){

usersService.updateById(user);//全部更新

return R.ok();

}


### 0264springboot基于Spring Boot的库存管理系统 项目图片
![图片](/images/0264springbootimg_001.jpg)
![图片](/images/0264springbootimg_003.jpg)
![图片](/images/0264springbootimg_002.jpg)
![图片](/images/0264springbootimg_004.jpg)








