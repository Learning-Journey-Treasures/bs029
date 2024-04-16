**郑重声明：项目经过本地测试，确保可以运行。项目仅供学习和毕业设计参考~**

![image text](https://github.com/Learning-Journey-Treasures/bs029/blob/main/qrcode_for_gh_1266b4b5294a_258.jpg "DBSCAN Performance Comparison")

 **微信扫码关注发送BS029，获得源码**💕🤞
#### 1.项目介绍

技术栈+环境：SSM + jsp + tomcat8.5 + idea2022 + jdk8

项目角色：学生、教师、管理员

项目功能 ：管理员（班级管理、教师管理、试题管理、试卷管理、学生管理、考试发布管理、考试历史管理等）、教师（学生管理、试题管理、试卷管理、考试管理）、学生（登录注册、在线考试、查看考试结果等）

#### 2.项目部署

- 创建数据库，导入db目录下的sql文件

- 根据本地数据库环境修改数据库连接属性，src/config/db.properties，1-4 行

- 如果你的数据库是8.0及以上，需要修改src/config/db.properties的第2行，在后面加上时区的配置
