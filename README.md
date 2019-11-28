# GoToolbox


### Go工具集合

1. `Gin` 框架

2. `GORM` 数据库操作. Docs:(http://gorm.io/zh_CN/)

3. `Gin-Session` Session操作

4. `godotenv` 程序读取环境变量,用于程序读取配置文件

5. `Gin-Cors` 跨域中间件, 解决前后端跨域



### 目录说明

1. `api` 文件夹就是MVC框架的`controller`, 负责协调各部件完成任务

2. `model` 文件夹负责存储数据库模型和数据库操作相关的代码

3. `service` 文件夹负责处理比较复杂的业务, 把业务代码模型化可以有效提高业务代码的质量（比如用户注册，充值，下单等）

4. `serializer` 文件夹储存通用的json模型，把`model` 得到的数据库模型转换成`api`需要的json对象.

5. `cache` 文件夹负责redis缓存相关的代码

6. `auth` 文件夹负责权限控制

7. `util` 文件夹存放一些通用的小工具

8. `conf` 文件夹放一些静态存放的配置文件，其中locales内放置翻译相关的配置文件

