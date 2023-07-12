**完整代码收费  可以加qq 931708230 或者加微信ynwwxid 咨询**

**接毕业设计和论文**

**博客地址：
[https://blog.csdn.net/2303_76227485/article/details/131666452](https://blog.csdn.net/2303_76227485/article/details/131666452)**

**视频演示：
[https://www.bilibili.com/video/BV1wu41177fk/](https://www.bilibili.com/video/BV1wu41177fk/)**

**毕业设计所有选题地址：
[https://github.com/ynwynw/allProject](https://github.com/ynwynw/allProject)**

## 基于springboot的微信小程序宠物领养医院系统(源代码+数据库+10000字论文)085

## 一、系统介绍
本项目有网页版和小程序端

本系统分为管理员、医生、用户三种角色

用户角色包含以下功能：
- 登录、注册、宠物领养、医生在线咨询、查看挂号、个人中心、密码修改、宠物寄养查看

医生角色包含以下功能：
- 登录、查询挂号、在线回复、挂号、挂号查询处理、个人中心、密码修改

管理员角色包含以下功能：
- 登录、用户管理、医生管理、宠物管理、挂号管理、领养管理、寄养管理、公告管理、员工管理、科室管理、个人中心、密码修改

**系统结构图和论文目录截图**
![contents](./picture/picture0.png)

## 二、所用技术

后端技术栈：

- springboot
- mybatisPlus
- mysql
- shiro

前端技术栈：

- bootstrap
- html
- axios
- 微信小程序



## 三、环境介绍

基础环境 :IDEA/eclipse, JDK 17, Mysql5.7及以上,Node.js(14),Maven3.6, 微信开发者工具

所有项目以及源代码本人均调试运行无问题 可支持远程调试运行

## 四、页面截图

![contents](./picture/picture1.png)
![contents](./picture/picture2.png)
![contents](./picture/picture3.png)
![contents](./picture/picture4.png)
![contents](./picture/picture5.png)
![contents](./picture/picture6.png)
![contents](./picture/picture7.png)
![contents](./picture/picture8.png)
![contents](./picture/picture9.png)
![contents](./picture/picture10.png)
![contents](./picture/picture11.png)
![contents](./picture/picture12.png)
![contents](./picture/picture13.png)
![contents](./picture/picture14.png)
![contents](./picture/picture15.png)
![contents](./picture/picture16.png)
![contents](./picture/picture17.png)
![contents](./picture/picture18.png)
![contents](./picture/picture19.png)
![contents](./picture/picture20.png)
![contents](./picture/picture21.png)
![contents](./picture/picture22.png)
![contents](./picture/picture23.png)
![contents](./picture/picture24.png)
![contents](./picture/picture25.png)
![contents](./picture/picture26.png)
![contents](./picture/picture27.png)
![contents](./picture/picture28.png)
![contents](./picture/picture29.png)
![contents](./picture/picture30.png)
![contents](./picture/picture31.png)
![contents](./picture/picture32.png)
![contents](./picture/picture33.png)
![contents](./picture/picture34.png)
![contents](./picture/picture35.png)
![contents](./picture/picture36.png)
![contents](./picture/picture37.png)
![contents](./picture/picture38.png)
![contents](./picture/picture39.png)
![contents](./picture/picture40.png)
![contents](./picture/picture41.png)
![contents](./picture/picture42.png)
![contents](./picture/picture43.png)

## 五、浏览地址
前台访问地址：http://localhost:8086/index.html
-用户账号/密码：ying/123456

后台访问地址：http://localhost:8086/login.html
-医生账号/密码：yun/123456
-管理员账号/密码：admin/admin

## 六、部署教程

1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并执行项目的sql文件；

2. 使用IDEA/Eclipse导入forgePet项目，若为maven项目请选择maven，等待依赖下载完成；

3. 进入src/main/resources修改application.yml里面的数据库配置

4. src/main/java/com/forge/ForgePetApplication.java启动后端项目

5. 微信开发者工具打开forgePetWX项目，编译后就能看见页面

## 七、配置文件中需要修改的参数

```yml
spring:
  datasource:
    driver-class-name: com.mysql.cj.jdbc.Driver
    url: jdbc:mysql://localhost:3306/pet_forge?useSSL=true
    username: root # mysql用户名
    password: root # mysql密码
  mail:
    host: smtp.qq.com
    port: 587
    username: 931708230@qq.com # 发送者的邮箱，必须是QQ邮箱
    password: dspwtwceobsfeafa # 发送者邮箱的授权码
    default-encoding: UTF-8
```
*以及资源文件夹的路径：*

```yml
pet-forge:
  images-path: C:\MixJade\MixPet\images\ # 照片存储路径
  notice-path: C:\MixJade\MixPet\notice\ # 公告存储路径
  chatImg-path: C:\MixJade\MixPet\chatImg\ # 聊天图片存储路径
```

**完整代码收费  可以加qq 931708230 或者加微信ynwwxid 咨询**

**接毕业设计和论文**





