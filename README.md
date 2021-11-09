# 2021F软件工程 电子相册仓库
## 概述
* 预计使用 jsp + servlet + Javabean 经典结构实现 MVC 。
* 服务器使用Tomcat https://tomcat.apache.org/download-90.cgi
* 数据库使用 MySQL 8
* 前端使用 bootstrap v4（已在css和js文件夹中）官网有中文文档和案例，主要关注下栅格系统，这个是我们网页自适应的重要保证。
* 服务器端计划使用 druid 连接池， Jackson 封装json包， spring 模板（都在lib下的jar包，使用前需右键导入工程中）
* 开发环境建议使用 IDEA，目录结构请参考下一节，工程旧版本是Java EE下的web application，2021版本可能会不太一样

## 目录结构
> Codes Here
>> src -- 用于放置 Java class  
>>> 
>> web -- 存放 web 工程
>>> * WEB-INF -- 存放不希望用户直接访问的文件，如除了主页外的jsp，当然也可以直接放在根目录下，到时候再说。库依赖也放在这里。
>>> * css -- 存放 css 样式文件
>>> * fonts -- 存放字体文件和部分图标字体
>>> * icons -- 存放矢量图标文件.svg
>>> * js -- 存放 js 文件

### 说明
1. 写代码时候最好先branch再修改，然后pull request，或者确认不会覆盖别人可能修改的代码后merge
2. 然后没啥，先这样吧`orz`

# commit 时务必确保不会覆盖他人修改的代码
