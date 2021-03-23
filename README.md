# 007ssm课程在线学习与测试系统
007ssm课程在线学习与测试系统



### 启动说明

***

项目为maven管理，最近集成了redis，所以在运行项目是先要下载redis并启动客户端，方可正常运行项目。
由于只需要下载redis，无需其他配置，这里就不做过多说明。


源码获取：[ **点此获取** ](http://www.shuyue.fun/index.php?type=productinfo&id=105)

### 最近更新

***

集成redis来保存用户登录信息，添加过滤器重置用户登录有效期。拦截器实现统一登录和权限校验（相关重构还未完成）。


修改配置文件：com.bs.commonn.RedisPool 地址、端口号

pool = new JedisPool(config,"127.0.0.1",6379,1000*2);


修改数据库配置文件，导入项目bs.sql文件

学生账号测试：lwj   123456

教师测试账号：lwj   123456

管理员测试账号：admin admin


### 项目采用前后端分离技术实现

***

- 框架：SSM（Spring，SpringMVC，Mybatis）

- 缓存：redis

- 数据库：MySQL

- IDE：Intellij IDEA/Eclipse

- 其他：Maven，Git


### 项目亮点：

***

1. 前后端分离。

1. 用户登录权限区分和控制。

1. 防止横向越权和纵向越权。

1. 密码MD5明文加密。

1. 设计高复用的服务器响应对象。

1. guava缓存。

1. pojo，vo抽象模型。

1. 数据绑定对象。

1. Mybatis分页

1. Bootstrap。

1. artTemplate，artDialog，iframe前端模板使用。

1. select2、toastr、sweetalert等等前端插件的使用。

1. redis缓存。

1. 全局异常处理，拦截器权限统一检验。

1. excel批量导入数据（未完成）。


## 运行截图
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/140807_69ae67b5_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/140815_2ad076a3_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/140824_95a5133c_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/140831_28c6a163_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/140840_3895f8bb_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/140849_f43c0d23_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/140858_092376bb_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/140910_8e6f9fec_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/140918_c0b4df2e_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/140926_74c7ef4f_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/140935_f0d4b15e_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/140947_59d1a9e0_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/140954_060039de_863230.png "屏幕截图.png")


