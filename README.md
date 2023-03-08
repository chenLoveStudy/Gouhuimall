# 仿天猫商城
迷你天猫商城是一个基于SSM框架的综合性B2C电商平台，需求设计主要参考天猫商城的购物流程：用户从注册开始，到完成登录，浏览商品，加入购物车，进行下单，确认收货，评价等一系列操作。
作为模拟天猫商城系统的核心组成部分之一，采用SSM框架的购惠商城管理后台包含商品管理，订单管理，类别管理，用户管理和交易额统计等模块，实现了对整个商城的一站式管理和维护。
（仅供参考，如有问题还请见谅！）

后端页面兼容IE10及以上现代浏览器，Chrome,Edge,Firebox等浏览器表现效果最佳。

# 部署方式
1.项目使用IntelliJ IDEA开发，请使用IntelliJ IDEA的版本控制检出功能，输入“https://gitee.com/HaiTao87/TmallDemo.git”拉取项目即可。
2.项目数据库为(MySQL 8.0.27)MySQL 5.7版本，请在码云附件上下载SQL文件或者在resources下的sql文件夹中下载sql，并导入到数据库中。（代码分支不同数据库sql文件也不同，请正确导入）
3.使用IDEA打开项目后，在maven面板刷新项目，下载依赖包。（项目jdk为1.8）
4.在IDEA中启动springboot项目即可（run方式或debug方式都行）。
5.账户名和密码详见附件中的sql文件或者在resources下的sql文件夹中的sql文件（前台页面和后台页面账户密码下方有说明）。
![输入图片说明](https://images.gitee.com/uploads/images/2020/1016/150457_5c0c7304_996301.png "屏幕截图.png")

注意事项：后台管理界面的订单图表没有数据为正常现象，该图表显示的为近7天的交易额。

---后台界面(部分)--- 访问地址：http://localhost:8082/tmall/admin/login（账户名和密码在admin表里）
![登录界面](https://gitee.com/uploads/images/2018/0526/222324_71d64249_1616166.png "2018-05-26_221417.png")
![首页](https://gitee.com/uploads/images/2018/0526/222349_00d5df29_1616166.png "2018-05-26_221445.png")
![产品列表](https://gitee.com/uploads/images/2018/0526/222414_c3a74f51_1616166.png "2018-05-26_221454.png")
![添加产品](https://gitee.com/uploads/images/2018/0526/222440_813cf8d7_1616166.png "2018-05-26_221504.png")
![产品详情](https://gitee.com/uploads/images/2018/0526/222457_7727da44_1616166.png "2018-05-26_221513.png")
![产品类别列表](https://gitee.com/uploads/images/2018/0526/222515_0f605a1a_1616166.png "2018-05-26_221522.png")
![用户列表](https://gitee.com/uploads/images/2018/0526/222531_2ddbba60_1616166.png "2018-05-26_221530.png")
![用户详情](https://gitee.com/uploads/images/2018/0526/222542_f816afc9_1616166.png "2018-05-26_221539.png")
![订单列表](https://gitee.com/uploads/images/2018/0526/222601_ac370928_1616166.png "2018-05-26_221547.png")
![订单详情](https://gitee.com/uploads/images/2018/0526/222628_e539faf6_1616166.png "2018-05-26_221554.png")
![管理员详情](https://gitee.com/uploads/images/2018/0526/222839_911d4e0d_1616166.png "2018-05-26_221607.png")

---前台界面(部分)--- 访问地址 http://localhost:8082/tmall/login (账户名和密码在user表里)
![登陆界面](https://gitee.com/uploads/images/2018/0526/223030_17b28619_1616166.png "2018-05-26_221715.png")
![首页](https://gitee.com/uploads/images/2018/0526/223018_14e999f1_1616166.png "2018-05-26_221703.png")
![产品详情](https://gitee.com/uploads/images/2018/0526/223044_e481ec5f_1616166.png "2018-05-26_221725.png")
![下单界面](https://gitee.com/uploads/images/2018/0526/223100_ef6e9612_1616166.png "2018-05-26_221837.png")
![订单列表](https://gitee.com/uploads/images/2018/0526/223117_dfd64b43_1616166.png "2018-05-26_221901.png")
![确认收货](https://gitee.com/uploads/images/2018/0526/223220_71e2ee3d_1616166.png "2018-05-26_221911.png")
![产品列表](https://gitee.com/uploads/images/2018/0526/223233_18e131a5_1616166.png "2018-05-26_222006.png")
![购物车](https://gitee.com/uploads/images/2018/0526/223245_3f80d8f4_1616166.png "2018-05-26_223157.png")
