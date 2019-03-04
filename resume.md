# 左凯迪的简历

# 联系方式

* 手机：18784227116
* Email：kaidizuo@gmail.com
* QQ/微信号：1280700570

# 个人信息

* 左凯迪/男/1996
* 本科/湖北民族学院
* 工作年限：1年
* Github：http://github.com/caddyz
* 期望职位：java程序员
* 期望薪资：6k-8k
* 期望城市：成都

# 工作经历

## 湖北网乐信息科技有限公司 （2017年10月~2018年4月）

### 咸宁蓝天书屋OA系统

项目描述：蓝天书屋OA系统是一个后台管理系统，实现了权限分配、个人中心、操作日志、员工管理、产品管理、订单管理、后台账户管理、报表数据处理、采购与库存管理等功能。项目使用SSM框架，使用easyui作为前端框架，使用mysql数据库作为开发与生产数据库。
我在此项目中负责后台账户管理、员工管理功能的实现。在这个过程中我遇见比较困难的是后台账户的权限管理以及员工考勤表导入。权限管理我在数据库中建立了一张用户与权限对应的表，通过获取到的权限来控制用户访问，最后实现了用户权限，考勤表采用了poi工具将excel转化为csv并导入到数据库中。这个项目中我学习了easyui的前端框架，并在工作之外熟悉了bootstrap,layui等前端框架。

### 咸宁网上购物项目

项目描述：该项目使用SSH框架，数据库使用MySQL，用到html，css，js，ajax技术开发前端页面。后台实现利用Struts2的MVC模式对前端视图与后台数据交互，hibernate来处理dao层的业务逻辑的实现。
我在该项目中主要负责的是登陆注册功能以及销售排行功能实现。复杂的是登陆功能中的token的生成以及存储和如何避免不必要的数据以及加载缓慢，有关token，我采用了jjwt来生成token并将token存储到缓存中，对于加载缓慢和数据冗余，我采用了懒加载方式减少一次性加载数据的压力，然后我对页面改用了JSP 页面的展示方式，速度多有提升，但是随着图片的增多，还是变慢，然后我就开启hibernate 二次缓存和查询缓存，配置它内置的ehcache.xml 将缓存数据储存到用户磁盘中，性能有比较大的改善。在这个项目中我熟练掌握了SSH框架和jsp的使用，并学习了token。

## 湖北网乐信息科技有限公司（2018年6月~2019年1月）

### 优禾教育有限公司CRM系统

项目描述：项目采用springboot框架开发，前端采用vue、vue-element-admin、element-ui等前端技术，vuex实现状态管理，后端shiro实现权限控制，用mybatis-plus做持久层控制，redis做缓存，连接池采用druid+dbcp2，前后端交互采用axios。
我在这个项目中主要负责权限管理，跟踪管理，记录等功能。在这个项目中权限使用shiro框架，比较复杂的是权限粒度控制，将权限粒度分为角色、角色权限、数据接口三个粒度，并且实现在前端控制三个权限粒度的改变再写入数据库中。再有一个缓存数据更新的问题，后来采用的是read/write through模式。在这个项目中我掌握了vue相关知识，对权限管理框架shiro以及redis缓存也能熟练使用。

### 武汉世纪龙腾图书发展有限公司微信小程序

项目描述：项目主要有两个部分，前端是微信小程序，后端采用java后台，使用SSM框架。主要实现了主界面、个人中心管理、购物车、微信支付、商品评价、商品优惠、商品分类、商品详情展示、商品收藏等功能。
我在本项目中主要负责微信小程序主界面、搜索、商品优惠、商品评论和微信支付等功能的前后端实现，在这个项目中复杂在前端使用微信小程序需要去写微信前端，最后在自己的不断学习中成功的完成了微信小程序的前端实现。还有稍微复杂的点是微信支付，需要去查阅微信支付的文档。在这个项目中学会了微信小程序的开发，也去了解了微信公众号的开发，并且对微信支付也有能熟练的掌握。

# 开源项目和作品

## 开源项目

* [springcloud-demo](https://github.com/caddyz/springcloud-demo)：一个自己学习的spring cloud项目
* [htmlproject](https://github.com/caddyz/htmlproject)：这是自己写的一个vue前端博客

# 技能清单

以下均为我熟练使用的技能

* 开发语言：Java/JavaScript/Python
* 开发工具：IDEA/Eclipse/MyEclipse
* Web框架：Spring/SpringMVC/Spring Boot/Spring Cloud/MyBatis/Hibernate/Struts2/Shiro
* 前端框架：Bootstrap/Easyui/HTML5/CSS3/Layui/Vue-Element-Admin/Element-ui
* 前端工具：Vue/Jquery/Ajax/Axios/JSP/ servlet/EL/JSTL
* 数据库相关：MySQL/MyBatis-Plus
* 版本管理、文档和自动化部署工具：Svn/Git/Maven
* 单元测试：JUnit
* 云和开放平台：阿里云/微信应用开发
* 中间件：redis

# 致谢

感谢您花时间阅读我的简历，期待能有机会和您共事。
