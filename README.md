# demo
mall learning demo

# 2020/08/06
- eclipse 搭建springboot
- mysql数据库
- mybaits,yml
- springboot 2.2.7
- mvn
- swagger ui

# 2020/08/07

- 整合SpringSecurity和JWT实现认证和授权
- 整合SpringTask实现定时任务 
- 整合Elasticsearch实现商品搜索 
   - Elasticsearch下载
   - Kibana,作为访问Elasticsearch的客户端(http://localhost:5601)
- 整合Mongodb实现文档操作
   - Mongodb的安装和使用
    ```
    启动服务：net start MongoDB
    关闭服务：net stop MongoDB
    移除服务：D:\developer\env\MongoDB\bin\mongod.exe --remove
    ```
    - 客户端robo3t

# 2020/08/10

- 整合RabbitMQ实现延迟消息
    - 安装Erlang
    - 安装RabbitMQ
    - 启动RabbitMQ
        - sbin目录
        ```
        rabbitmq-plugins enable rabbitmq_management  
        ```
     - 访问地址查看是否安装成功：http://localhost:15672/
     - 输入账号密码并登录：guest guest
     - 创建帐号并设置其角色为管理员：mall mall
     - 创建一个新的虚拟host为：/mall
     - 点击mall用户进入用户配置页面
     - 给mall用户配置该虚拟host的权限