# tianti
    项目描述：天梯（tianti）是一款使用Java编写的轻量级权限系统，目前可以实现后端登陆、用户管理、角色管理、资源目录管理、角色授权等基本权限管理。
    同时也是一款服务端后台模板，使用layer和自身样式实现了固定模块的增删查改功能。项目技术分层明显，用户可以根据自己的业务模块进行相应地扩展。
    
    技术选型：Spring Data JPA、Hibernate、Shiro、 Spring MVC、Layer、Mysql等。
    
    项目结构：
     tianti-common：系统基础服务抽象，包括entity、dao和service的基础抽象；
     tianti-org：用户权限模块服务实现；
     tianti-module-admin：后台web项目实现；
  
    使用说明：
     1、数据库使用mysql，初始化脚本位于tianti-module-admin中的src/main/webapp/scripts/tianti_stage.sql。
     2、后台的登陆路径为http://ip:端口/login,用户名为admin，初始密码为123456。
      
    项目概览(节选)：
    ![image](https://raw.githubusercontent.com/xujeff/tianti/master/screenshots/login.png)                                                
    ![image](https://raw.githubusercontent.com/xujeff/tianti/master/screenshots/menulist.png)
    ![image](https://raw.githubusercontent.com/xujeff/tianti/master/screenshots/roleset.png)

    联系方式：xuzhexu@139.com 
    qq交流群：422039518
  

