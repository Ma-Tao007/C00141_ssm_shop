# C00141_ssm_shop
基于SSM的智能商城购物系统

@[TOC](基于SSM的智能商城购物系统)
# 项目简介

该智能商城系统主要实现两大功能模块:前台管理和后台管理
前台管理包括五大模块:用户登录注册、商品信息、购物车信息、个人信息管理、下单与订单管理、订单物流设置。
(1)用户登录注册模块:该功能模块的主要功能是为了确保交易信息的有效性，登录此网站的用户可以通过此模块进行会员的登录、注册、修改会员信息和注销账号等操作。
(2)商品信息模块:该功能模块的主要功能是对相关商品信息进行列出
(3)购物车信息模块:该功能模块是一个人性化的工具，浏览者对于中意的商品，在购买前存放在购物车中，并可以增减购物车中的商品种类数量，以提高购物效率。
(4)个人信息管理模块:该功能模块的主要功能是为用户提供个人信息查看与修改，以及密码修改等操作，除此之外还可以查看购物积分，以此生出用户等级。
(5)下单与订单管理模块:该功能模块的主要功能是生成订单信息、取消订单、查看订单号和订单状态。通过沙箱支付宝模拟支付！
(6)管理员发货后可以设置当前订单物流地址，用户在前台可以看到当前订单已经到哪里了（百度地图）
后台管理分别为管理员登录、管理员管理、用户管理、商品与分类管理、订单管理、配送员管理、统计查看
(1)管理员登录模块:该功能模块的主要功能是保障管理员的登录入口，且单独设置，用户无
法访问。
(2)管理员管理模块:该功能模块的主要功能是对本站的管理员进行相应添加、删除与更改
(3)用户管理模块:该功能模块的主要功能是对用户进行增删查改等操作
(4)商品与分类管理模块:此模块主要用于对网站商品信息和分类进行管理，商品分类管理又包括了添加分类、删除分类、对已有的分类进行编辑操作。
(5)订单管理模块:该功能模块主要实现管理员新建订单、删除已有的订单和修改订单信息的功能。订单可以配置配送员以及设置当前的订单物流地址位置。
(6)配送员管理：订单可以设置配送员
(7)统计查看：管理员在后台可以查看到当前系统的年度销售量以及年度销售额的图表查看情况
技术：
本系统采用当今社会比较先进的SSM(Spring+SpringMvc+MyBatis)框架技术开发一个性能优越、可扩展性强和安全可靠稳定的可视化智能商城系统。开发语言使用JAVA，数据库使用MySQL数据库，Web服务器使用Apache下的Tomcat服务器，同时会使用到JSP和Bootstrap框架，且部分数据交互会使用到Ajax异步的方式。



> 本项目亮点：
> 1.沙箱支付：支付订单使用沙箱支付模拟真实支付功能！
> 2.物流查看：管理员可以设置订单物流位置，用户可以在我的订单中点击在地图看到订单所在位置！
> 3.商品推荐：首页根据本系统的商品购买量自动推荐销售量多的随机几款商品给用户
> 4.统计查看：管理员首页可以通过echarts查看销售量统计数据



 # 项目获取
> [源码获取地址](http://www.manoncode.cn/details?id=141)

 
# 开发环境

运行环境：推荐jdk1.8；
开发工具：eclipse以及idea（推荐）；
操作系统：windows 10 8G内存以上（其他windows以及macOS支持，但不推荐）；
浏览器：Firefox(推荐)、Google Chrome(推荐)、Edge;
数据库：MySQL8.0(推荐)及其他版本（支持，但容易异常尤其MySQL5.7（不含）以下版本）；
数据库可视化工具：Navicat Premium 15（推荐）以及其他Navicat版本
是否maven项目：是


 # 项目技术
 
后端：Spring、SpringMVC、Mybatis、mysql
前端：jsp、bootstrap、jquery、ajax

 # 运行截图
 


  -1.流程图 

![-1.流程图](https://img-blog.csdnimg.cn/img_convert/f008112b20fe64f0655d7ae072e8d0e6.png)

  1.项目结构 

![1.项目结构](https://img-blog.csdnimg.cn/img_convert/d33dc76736d011335f04725ca8df468b.png)

  2.数据库 

![2.数据库](https://img-blog.csdnimg.cn/img_convert/c20b33da0d9a98a1ea9e4c6350c6c3c0.png)

  -2.下载所得 

![-2.下载所得](https://img-blog.csdnimg.cn/img_convert/9d4a7d8769389d24d41ff7f0c3bd0b45.png)

  3.数据库模型 

![3.数据库模型](https://img-blog.csdnimg.cn/img_convert/d8884d7bd3f5c5315466b78a849a2ee1.png)

  5.前台首页 

![5.前台首页](https://img-blog.csdnimg.cn/img_convert/f5bb300f81fed4ae8a3a1504ed82acd2.png)

  6.分类查询 

![6.分类查询](https://img-blog.csdnimg.cn/img_convert/527ab400f9b2b4f472aee530e7fc0ae4.png)

  7.商品详情页面 

![7.商品详情页面](https://img-blog.csdnimg.cn/img_convert/718de4b82384f696440541fee9ae637b.png)

  8.购物车 

![8.购物车](https://img-blog.csdnimg.cn/img_convert/410a66b01a5a18e379d1a9805e462137.png)

  9.我的订单 

![9.我的订单](https://img-blog.csdnimg.cn/img_convert/e1d34c8b125bcca98a54cd9fc7bb54f5.png)

  9-1.订单地址 

![9-1.订单地址](https://img-blog.csdnimg.cn/img_convert/b2bdd5241e146f6dbb628085a63a1292.png)

  9-2.查看物流信息 

![9-2.查看物流信息](https://img-blog.csdnimg.cn/img_convert/e101f59e8beab006ee0ae8d27a05cae1.png)

  10.个人信息 

![10.个人信息](https://img-blog.csdnimg.cn/img_convert/20334ec8cba5e0762bb8d1ede66267b5.png)

  11.系统留言 

![11.系统留言](https://img-blog.csdnimg.cn/img_convert/141b1fd3a3bc459307e9f583b1ee7014.png)

  12.修改密码 

![12.修改密码](https://img-blog.csdnimg.cn/img_convert/f2a9e5fc6c52775ccb008cb56b32b422.png)

  13.前台登录 

![13.前台登录](https://img-blog.csdnimg.cn/img_convert/05dc800a0829e714be323c4a007a22cd.png)

  14.前台注册 

![14.前台注册](https://img-blog.csdnimg.cn/img_convert/5faae1a47fe239f2e1391b21ad0dd954.png)

  15.后台登录 

![15.后台登录](https://img-blog.csdnimg.cn/img_convert/6a609645d8d4be4d171a29c048981809.png)

  16.后台首页统计展示 

![16.后台首页统计展示](https://img-blog.csdnimg.cn/img_convert/a89cb3da70f3b9a5f3802110df5138d7.png)

  17.管理员管理 

![17.管理员管理](https://img-blog.csdnimg.cn/img_convert/cac337b1d09a59abbb306c438b760630.png)

  18.用户管理 

![18.用户管理](https://img-blog.csdnimg.cn/img_convert/5d2c8991ebd4d0dc7ad289a335015d03.png)

  19.商品管理 

![19.商品管理](https://img-blog.csdnimg.cn/img_convert/1072b1987ca5ac12f2fd649507d23848.png)

  20.分类管理 

![20.分类管理](https://img-blog.csdnimg.cn/img_convert/afb77f80a1f9b7ffd048495cb3fd9c2e.png)

  21.订单管理 

![21.订单管理](https://img-blog.csdnimg.cn/img_convert/e64a91342fda2b3809c6012fc58cac27.png)

  22.订单处理 

![22.订单处理](https://img-blog.csdnimg.cn/img_convert/fc7096b770186664da63fc2d65e323a9.png)

  23.配送员管理 

![23.配送员管理](https://img-blog.csdnimg.cn/img_convert/c66a9793bc0c5e7ce42bd3c5337d331d.png)

  24.留言管理 

![24.留言管理](https://img-blog.csdnimg.cn/img_convert/256666ef485006e764542806b6c4d841.png)

  25.订单支付 

![25.订单支付](https://img-blog.csdnimg.cn/img_convert/4c24b7232c3b67108030509917616db1.png)
