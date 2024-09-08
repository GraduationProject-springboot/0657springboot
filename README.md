# [首页查询更多项目](https://github.com/GraduationProject-springboot) 包安装运行


# 0657springboot摄影跟拍预定管理系统--论文

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV14HerezEwW?p=14)


# 绪论
## 1.1项目研究的背景
困扰管理层的许多问题当中,摄影跟拍预定管理一定是不敢忽视的一块。但是管理好摄影跟拍预定又面临很多麻烦需要解决,例如有几个方面:第一,往往用户人数都比较多,如何保证能够管理到每一用户;第二,如何在工作琐碎,记录繁多的情况下将摄影跟拍预定的当前情况反应给领导相关部门决策等。在此情况下开发一款摄影跟拍预定管理系统，于是乎变得非常合乎时宜。

经过网上调查和搜集数据,我们可以发现摄影跟拍预定管理方面的系统在中并不是相当普及,在摄影跟拍预定管理方面的可以有许多改进。实际上如今信息化成为一个未来的趋势或者可以说在当前现代化的城市典范中,信息化已经成为主流,开发一个摄影跟拍预定管理系统一方面的可能会更合乎时宜,另一方面来说也可以提高在摄影跟拍预定管理方面的效率给相关部门人的工作带来一定的便利。
## 1.2开发意义
人类的进步带动信息化的发展，使人们生活节奏越来越快，所以人们越来越重视信息的时效性。以往的管理方式已经满足不了人们对获得信息的方式、方便快捷的需求。即摄影跟拍预定管理系统慢慢的被人们关注。首先，网上获取信息十分的实时、便捷，只要系统在线状态，无论在哪里都能第一时间查找到理想的信息。

计算机技术在管理中成为人们的重要工具。可以有效快捷的解决想要获取的信息，提高工作效率。
## 1.3项目研究内容与结构
摄影跟拍预定管理方面的任务繁琐,以至于每年都在摄影跟拍预定管理这方面投入较多的精力却效果甚微,摄影跟拍预定管理系统的目标就是为了能够缓解摄影跟拍预定管理工作方面面临的压力,让摄影跟拍预定管理方面的工作变得更加高效准确。

本项目在开发和设计过程中涉及到原理和技术有: B/S、java技术和MySQL数据库等等；将按以下章节进行开发设计；

1. 绪论；剖析项目背景,说明研究的内容。
1. 开发技术；系统主要使用了java技术， b/s模式和myspl数据库，并对此做了介绍。
1. 系统分析；包罗了系统总体结构、对系统的性能、功能、流程图进行了分析。
1. 系统设计；对软件功能模块和数据库进行详细设计。
1. 系统总体设计；对系统管理员、摄影师和用户的功能进行描述，
1. 对系统进行测试，
1. 总结心得；在论文最后结束章节总结了开发这个系统和撰写论文时候自己的总结、感想,包括致谢。


# 2开发技术介绍
## 2.1 B/S架构
B/S结构是目前使用最多的结构模式，它可以使得系统的开发更加的简单，好操作，而且还可以对其进行维护。使用该结构时只需要在计算机中安装数据库，和一些很常用的浏览器就可以了。浏览器就会与数据库进行信息的连接，可以实现很多的功能，B/S结构是可以直接进行使用的，而且B/S结构在使用中极大的减少了工作的维护。基于B/S的软件，所有的数据库之间都是相互独立的，因此是非常安全的。因为基于B/S结构可以清楚的看到系统正在处理的业务，并且能够及时的让管理人员做出决策，这样就可以避免企业的损失。B/S结构的基本特点是集中式的管理模式，用户使用系统生成数据后，这些数据就可以存储到系统的数据库中，方便日后能够用到，这样就可以满足人们的所有的需求。

![](/md/blog.002.png)

图2-1  B/S模式三层结构图
## 2.2Java技术
Java是由Sun公司推出的一门跨平台的面向对象的程序设计语言。因为Java 技术具有卓越的通用性、高效性、健壮的安全性和平台移植性的特点，而且Java是开源的，拥有全世界最大的开发者专业社群，所以Java的发展迅速。
## 2.3MySQL 介绍
在软件项目，通过经营性数据的数据库，可以保证其安全，独立和数据一致，访问数据的系统来提供，所以有效减少时间程序员开发应用程序。

MySQL可以支持多线程，可以方便使用系统的资源，提高运行的速度。并提供odbc、jdbc和tcp/ ip，以各种形式连接到MySQL; 功能方面表现欠缺，规模小，但对于这个系统就足够了。

因为MySQL是源代码对外开放的，所以任何人都可以通过相应的方法下载，并根据个性化需求进行修改。 由于MySQL的速度，可靠性和适应性，MySQL受到重视。

MySQL虽然功能可能不是很强大，但由于其开源，广泛传播，导致很多人都意识到这个数据库。
## 2.4MySQL环境配置
本系统的数据使用的是MySQL,所以要将MySQL安装到指定目录，如果下载的是非安装的MySQL压缩包，直接解压到指定目录就可以了。然后点击C:\Program Files\MySQL\bin\winMySQLadmin.exe这个文件其中C:\Program Files\MySQL是MySQL安装目录。输入winMySQLadmin的初始用户、密码（注：这不是MySQL里的用户、密码）随便填不必在意，确定之后右下角任务的启动栏会出现一个红绿灯的图标，红灯亮代表服务停止，绿灯亮代表服务正常，左击这个图标->winnt->install the service 安装此服务，再左击这个图标->winnt->start the service 启动MySQL服务。

修改MySQL数据库的root密码。用cmd进入命令行模式输入如下命令:

cd C:\Program Files\MySQL\bin

MySQLadmin -u root -p password 123

回车出现Enter password: ，这是要输入原密码. 刚安装时密码为空,所以直接回车，此时MySQL 中账号 root 的密码被改为 123 安装完毕。
## 2.5SpringBoot技术
本技术是Java平台的开源应用框架，其目的地简单化Spring的初始搭建和开发的过程。默认配置了很多框架的使用方式，自动加载Jar包，为了让用户尽可能快的跑起来spring应用程序。

SpringBoot的主要优点有：1.为所有Spring开发提供了一个更快、更广泛的入门体验；2.零配置；3.集成了大量常用的第三方库的配置；4.提供准备好的特性。当今，Java领域开发者几乎都在使用SpringBoot，在开发领域逐渐成为领导者。

# 3系统分析
## 3.1可行性分析
在开发系统之前要进行系统可行性分析，目的是在用最简单的方法去解决最大的问题，程序一旦开发出来满足了用户的需要，所带来的利益也很多。下面我们将从技术、操作、经济等方面来选择这个系统最终是否开发。
### 3.1.1技术可行性
本系统开发选择java技术，java技术是一个完全面向对象的语言，为开发者提供了丰富的类库，大大减少了使用windows编程的难度,减少开发人员在设计算法上的难度，作为java技术开发 Visual Studio更是一个必不可少的角色，它友好的界面，以及强大的功能，给程序开发人员带来了很多方便，加上环境简单，转移方便，无疑使此系统最佳的选择。所以后台设计选择使用MySQL数据库主要用来的建立和维护信息。对于前台开发要求应具备功能完善、易于操作等优点，后台数据库的要求则是能够建立和维护数据信息的统一性和完整性。

依据上述目标来分析本系统的硬件如下：

奔腾3的处理器；

内存是 2G；

硬盘是50G；

操作系统是Window 10；

在软件方面的话，安装了Visul Studio和MySQL数据库开发工具。根据以上的软件与硬件要求，得到这个系统的技术是可行的。
### 3.1.2经济可行性
基于springboot的摄影跟拍预定管理系统，该系统软件开发仅需要一台普通的计算机便可完成实现开发，其成本很低。另外，作为毕业设计作品来讲，开发成本基本上可以忽略不计，且该系统软件的投入使用，可以实现更加快速高效的摄影跟拍预定，同时还能实现对人力资源和管理资源的有效节约，该摄影跟拍预定管理系统在经济上完全可行。
### 3.1.3操作可行性
现在随着科技的飞速发展，计算机早已经进入了人们的日常生活中，人们的工作环境也不像以前有那么多的要求，需要员工一定要到公司办公，有的工作在家也可以完成。这使得人们的工作效益有了很大的提高。操作的多样性也变高了。因此，管理的计算机化，智能化是社会发展而带来的必然趋势，各种智能的软件层出不穷，不同的软件能完成用户不同的需求，这不仅提高了工作效率还能完成一些客户特定的一些需求。本系统不仅界面简洁明了还采用可视化界面，用户只要用鼠标和键盘就可以完成对相关信息的修改，删除，添加等操作。因为这个系统的操作十分简单，方便上手，对于第一次使用系统的人，只需要很少的时间就可以上手操作。由此可见，本系统在操作上是可行的。
## 3.2系统性能需求分析
对系统性能进行分析，可对系统反应度、界面简洁清晰度、储存能性、易学性和稳定性进行分析；

系统反应度：同时上万人在线时反应时间应该在两三秒以内，。

界面简洁清晰：系统界面要求简单明了，操作简单，用户操作容易上手。

储存性能高：摄影跟拍预定管理系统中需要存储的信息有很多，所以对系统的存储量要求很高，因此数据库就应该很强大，才能保证信息能安全稳定的进行存储；

易学性：该系统在操作上必须简单好上手，没有很多复杂的操作，只需要简单的进行学习就能操作该系统。

稳定性：要求摄影跟拍预定管理系统运行要稳定，界面清楚、字体清晰等。
## 3.3系统功能分析
考虑到实际生活中在摄影跟拍预定方面的需要以及对该系统认真的分析,将系统权限按管理员、摄影师和用户这三类涉及用户划分。

(a) 管理员；管理员使用本系统涉到的功能主要有：首页、个人中心、用户管理、摄影师管理、摄影跟拍管理、类别管理、周边商品管理、商品类型管理、跟拍预约管理、跟拍流程管理、成品信息管理、商品订单管理、系统管理等功能。管理员用例图如图3-1所示。

![](/md/blog.003.png)

图3-1　管理员用例图

` `(b)摄影师；摄影师使用本系统涉到的功能主要有：首页、个人中心、跟拍预约管理、跟拍流程管理、成品信息管理、商品订单管理等功能。摄影师用例图如图3-2所示。

![](/md/blog.004.png)

图3-2摄影师用例图

(c)用户主要包括首页、个人中心、跟拍预约管理、跟拍流程管理、成品信息管理、商品订单管理、评论信息管理、我的收藏管理等功能。用户用例图如图3-3所示。

![](/md/blog.005.png)

图3-3用户用例图
## 3.4系统流程的分析
由于不同的系统实际使用用户角色的不同,他们的业务分析也会变得有所不一样,为了论述方便接下来都将以用户功能权限下的系统业务流程来分析,如下图所展示:
### 3.4.1 用户管理的流程

![](/md/blog.006.png)

图3-4 用户管理流程
### 3.4.2个人中心管理流程

![](/md/blog.007.png)

图3-5 个人中心管理流程
### 3.4.3登录流程
![](/md/blog.008.png)

图3-6 登录流程























# 4系统设计
## 4.1 软件功能模块设计
系统整体功能如下图所示：

![](/md/blog.009.png)

图 4-1系统总体功能模块图
## 4.2数据库设计
### 4.2.1概念模型设计
概念模型是对现实中的问题出现的事物的进行描述，ER图是由实体及其关系构成的图，通过E-R图可以清楚地描述系统涉及到的实体之间的相互关系。

个人中心实体图如图4-2所示：

![](/md/blog.010.png)

图4-2个人中心实体图

摄影跟拍实体图如图4-3所示：

![](/md/blog.011.png)

图4-3摄影跟拍实体图

周边商品实体图如图4-4所示：

![](/md/blog.012.png)

图4-4周边商品实体图

### 4.2.2物理模型设计
根据上诉的逻辑模型设计,下面给出物理模型的设计,如下表:

表4-1：评论信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|gonghao|varchar|200|工号|||
|yuangongxingming|varchar|200|员工姓名|||
|pingjianeirong|longtext|4294967295|评价内容|||
|gerenzhanghao|varchar|200|个人账号|||
|xingming|varchar|200|姓名|||
|pingjiariqi|date||评价日期|||

表4-2：token表

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

表4-3：公告信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|title|varchar|200|标题|||
|introduction|longtext|4294967295|简介|||
|picture|varchar|200|图片|||
|content|longtext|4294967295|内容|||

表4-4：收藏表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|userid|bigint||用户id|||
|refid|bigint||收藏id|||
|tablename|varchar|200|表名|||
|name|varchar|200|收藏名称|||
|picture|varchar|200|收藏图片|||
|type|varchar|200|类型(1:收藏,21:赞,22:踩)||1|
|inteltype|varchar|200|推荐类型|||
表4-5：摄影师

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|gonghao|varchar|200|工号|||
|mima|varchar|200|密码|||
|yuangongxingming|varchar|200|员工姓名|||
|xingbie|varchar|200|性别|||
|youxiang|varchar|200|邮箱|||
|lianxishouji|varchar|200|联系手机|||
|xiangpian|varchar|200|相片|||

表4-6：周边商品

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|shangpinmingcheng|varchar|200|商品名称|||
|shangpinleixing|varchar|200|商品类型|||
|shangpintupian|varchar|200|商品图片|||
|shangpinguige|varchar|200|商品规格|||
|shangpinjianjie|longtext|4294967295|商品简介|||
|shangpinxiangqing|longtext|4294967295|商品详情|||
|shengchandi|varchar|200|生产地|||
|yuancailiao|varchar|200|原材料|||
|danjia|int||单价|||
|shuliang|int||数量|||
|shangjiariqi|date||上架日期|||
|clicktime|datetime||最近点击时间|||
|clicknum|int||点击次数||0|

表4-7：摄影跟拍

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|taocanmingcheng|varchar|200|套餐名称|||
|taocantupian|varchar|200|套餐图片|||
|leibie|varchar|200|类别|||
|taocanjianjie|longtext|4294967295|套餐简介|||
|paishedidian|varchar|200|拍摄地点|||
|taocanxiangqing|longtext|4294967295|套餐详情|||
|taocanjiage|int||套餐价格|||
|zhuyishixiang|varchar|200|注意事项|||
|faburiqi|date||发布日期|||
|clicktime|datetime||最近点击时间|||

表4-8：商品类型

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|shangpinleixing|varchar|200|商品类型|||

表4-9：用户

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|gerenzhanghao|varchar|200|个人账号|||
|mima|varchar|200|密码|||
|xingming|varchar|200|姓名|||
|xingbie|varchar|200|性别|||
|youxiang|varchar|200|邮箱|||
|shoujihaoma|varchar|200|手机号码|||
|xiangpian|varchar|200|相片|||

表4-10：商品订单

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|shangpinmingcheng|varchar|200|商品名称|||
|shangpinleixing|varchar|200|商品类型|||
|danjia|int||单价|||
|shuliang|int||数量|||
|jine|int||金额|||
|gerenzhanghao|varchar|200|个人账号|||
|xingming|varchar|200|姓名|||
|shoujihaoma|varchar|200|手机号码|||
|xiadanbeizhu|varchar|200|下单备注|||
|xiadanshijian|date||下单时间|||
|sfsh|varchar|200|是否审核||否|
|shhf|longtext|4294967295|审核回复|||
|ispay|varchar|200|是否支付||未支付|

表4-11：用户表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|username|varchar|100|用户名|||
|password|varchar|100|密码|||
|role|varchar|100|角色||管理员|
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|

表4-12：类别

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|leibie|varchar|200|类别|||

表4-13：跟拍预约

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|taocanmingcheng|varchar|200|套餐名称|||
|leibie|varchar|200|类别|||
|paishedidian|varchar|200|拍摄地点|||
|taocanjiage|varchar|200|套餐价格|||
|gerenzhanghao|varchar|200|个人账号|||
|xingming|varchar|200|姓名|||
|shoujihaoma|varchar|200|手机号码|||
|yuyueriqi|date||预约日期|||
|yuyuebeizhu|varchar|200|预约备注|||
|xiadanshijian|date||下单时间|||
|sfsh|varchar|200|是否审核||否|
|shhf|longtext|4294967295|审核回复|||
|ispay|varchar|200|是否支付||未支付|

表4-14：跟拍流程

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|taocanmingcheng|varchar|200|套餐名称|||
|leibie|varchar|200|类别|||
|paishedidian|varchar|200|拍摄地点|||
|gerenzhanghao|varchar|200|个人账号|||
|xingming|varchar|200|姓名|||
|shoujihaoma|varchar|200|手机号码|||
|anpaishijian|datetime||安排时间|||
|liuchengneirong|longtext|4294967295|流程内容|||
|gonghao|varchar|200|工号|||
|yuangongxingming|varchar|200|员工姓名|||
|lianxishouji|varchar|200|联系手机|||
|caozuoriqi|date||操作日期|||
|sfsh|varchar|200|是否审核||否|
|shhf|longtext|4294967295|审核回复|||

表4-15：周边商品评论表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|refid|bigint||关联表id|||
|userid|bigint||用户id|||
|nickname|varchar|200|用户名|||
|content|longtext|4294967295|评论内容|||
|reply|longtext|4294967295|回复内容|||

表4-16：摄影跟拍评论表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|refid|bigint||关联表id|||
|userid|bigint||用户id|||
|nickname|varchar|200|用户名|||
|content|longtext|4294967295|评论内容|||
|reply|longtext|4294967295|回复内容|||

表4-17：配置文件

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|name|varchar|100|配置参数名称|||
|value|varchar|100|配置参数值|||

表4-18：成品信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|chengpinmingcheng|varchar|200|成品名称|||
|chengpintupian|varchar|200|成品图片|||
|chengpinfujian|varchar|200|成品附件|||
|gerenzhanghao|varchar|200|个人账号|||
|xingming|varchar|200|姓名|||
|shoujihaoma|varchar|200|手机号码|||
|shangchuanriqi|date||上传日期|||
|gonghao|varchar|200|工号|||
|yuangongxingming|varchar|200|员工姓名|||
|lianxishouji|varchar|200|联系手机|||













# 5系统详细设计
## 5.1系统功能模块
摄影跟拍预定管理系统，在系统首页可以查看首页、摄影跟拍、周边商品、公告信息、个人中心、后台管理等内容，并进行详细操作，如图5-1所示。

![](/md/blog.013.png)

图5-1系统首页界面图

摄影跟拍，在摄影跟拍页面中可以查看套餐名称、类别、套餐简介、拍摄地点、套餐价格、注意事项、发布日期等内容进行预约、评论或收藏等操作，如图5-2所示。

![](/md/blog.014.png)

图5-2摄影跟拍界面图

周边商品，在周边商品页面可以查看商品名称、商品类型、商品规格、商品简介、原材料、生产地、单价、数量、上架日期、点击次数等内容进行购买、收藏或评论等操作，如图5-3所示。

![](/md/blog.015.png)

图5-3周边商品界面图

个人中心，在个人中心页面通过填写个人账号、密码、 姓名、邮箱、手机号码、图片等内容进行更新信息，并可以根据我的收藏进行相应的操作，如图5-4所示。

![](/md/blog.016.png)

图5-4个人中心界面图

## 5.2管理员功能模块
管理员进行登录，进入系统前在登录页面根据要求填写用户名和密码，选择角色等信息，点击登录进行登录操作，如图5-5所示。

![](/md/blog.017.jpeg)

图5-5管理员登录界面图

管理员登录系统后，可以对首页、个人中心、用户管理、摄影师管理、摄影跟拍管理、类别管理、周边商品管理、商品类型管理、跟拍预约管理、跟拍流程管理、成品信息管理、商品订单管理、系统管理等进行相应的操作管理，如图5-6所示。

![](/md/blog.018.png)

图5-6管理员功能界面图

用户管理，在用户管理页面可以对索引、个人账号、姓名、性别、邮箱、手机号码、照片等内容进行详情、修改或删除等操作，如图5-7所示。

![](/md/blog.019.png)

图5-7用户管理界面图

摄影师管理，在摄影师管理页面可以对索引、工号、员工姓名、性别、邮箱、联系手机、照片等内容进行详情、修改或删除等操作，如图5-8所示。

![](/md/blog.020.png)

图5-8摄影师管理界面图

摄影跟拍管理，在摄影跟拍管理页面可以对索引、套餐名称、套餐图片、类别、拍摄地点、套餐价格、注意事项、发布日期等内容进行详情、修改、查看评论或删除等操作，如图5-9所示。

![](/md/blog.021.png)

图5-9摄影跟拍管理界面图

类别管理，在课程分类管理页面可以对索引、类型等内容进行详情、修改或删除等操作，如图5-10所示。

![](/md/blog.022.png)

图5-10类别管理界面图

周边商品管理，在周边商品管理页面可以对索引、商品名称、商品类型、商品图片、商品规格、生产地、原材料、单价、数量、上架日期等内容进行详情、修改、查看评论或删除等操作，如图5-11所示。

![](/md/blog.023.png)

图5-11周边商品管理界面图

成品信息管理，在成品信息管理页面可以对索引、成品名称、 成品图片、成品附件、个人账号、姓名、手机号码、上传日期、工号、员工姓名、联系手机等内容进行详情或删除等操作，如图5-12所示。

![](/md/blog.024.png)

图5-12成品信息管理界面图

商品订单管理，在商品订单管理页面中可以对索引、商品名称、商品类型、单价、数量、金额、个人账号、姓名、手机号码、下单备注、下单时间、是否支付、审核回复、审核状态、审核等内容进行详情或删除等操作，如图5-13所示。

![](/md/blog.025.png)

图5-13商品订单管理界面图

系统管理，在轮播图管理页面中可以对索引、名称、值等内容进行详情或修改等操作，并可以根据公告信息进行相应的操作，如图5-14所示。

![](/md/blog.026.png)

图5-14系统管理界面图

## 5.3摄影师功能模块
摄影师登录进入摄影跟拍预定管理系统可以对首页、个人中心、跟拍预约管理、跟拍流程管理、成品信息管理、商品订单管理等进行相应操作，如图5-15所示。

![](/md/blog.027.png)

图5-15摄影师功能界面图

跟拍预约管理，在跟拍预约管理页面中可以对索引、套餐名称、类型、拍摄地点、套餐价格、个人账号、姓名、手机号码、预约日期、预约备注、下单时间、是否支付、审核回复、审核状态、审核等内容进行详情或流程等操作，如图5-16所示。

![](/md/blog.028.png)

图5-16跟拍预约管理界面图

跟拍流程管理，在跟拍流程管理页面可以对索引、套餐名称、类别、拍摄地点、个人账号、姓名、手机号码、安排时间、工号、员工姓名、联系手机、操作日期审核回复、审核状态等内容进行详情、成品、修改或删除等操作，如图5-17所示。

![](/md/blog.029.png)

图5-17跟拍流程管理界面图

## 5.4用户功能模块
用户注册，通过填写个人账号、密码、 确认密码、 姓名、邮箱、手机号码等内容进行注册等操作，如图5-18所示。

![](/md/blog.030.png)

图5-18用户注册界面图

用户登录进入摄影跟拍预定管理系统可以对首页、个人中心、跟拍预约管理、跟拍流程管理、成品信息管理、商品订单管理、评论信息管理、我的收藏管理等进行相应操作，如图5-19所示。

![](/md/blog.031.png)

图5-19用户功能界面图

成品信息管理，在成品信息管理页面可以对索引、成品名称、 成品图片、成品附件、个人账号、姓名、手机号码、上传日期、工号、员工姓名、联系手机等内容进行详情等操作，如图5-20所示。

![](/md/blog.032.png)

图5-20成品信息管理界面图

跟拍预约管理，在跟拍预约管理页面可以对索引、套餐名称、类型、拍摄地点、套餐价格、个人账号、姓名、手机号码、预约日期、预约备注、下单时间、是否支付、审核回复、审核状态、审核等内容进行详情等操作，如图5-21所示。

![](/md/blog.033.png)

图5-21跟拍预约管理界面图

#
#

#










