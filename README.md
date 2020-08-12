# 在线学习考试系统

### 介绍
在线学习考试系统，多角色考试系统

### 软件架构

#### 考生角色：
用户端登录后，可以列出正在进行的课程、最近考试、最高考试得分；    
用户可以进行在线考试；试题简单分为单选题和多选题，试卷可以自定义考试时长、到时间自动交卷；用户交卷以后实时出现考试结果及分数。    
对于考试过程中错误的题目、希望有一个错题库、用户可以有针对性的对错题进行训练；    


#### 管理员角色：
1、包含考生角色的所有功能；    
2、系统分角色进行登录、有比较简单的用户角色管理体系；    
3、可以维护题库，试题与题库是多对多的关系，即一个题目可以存着于多个题库中    
4、有试题管理、可以添加单选题和多选题、对应的题目解析等。    
5、可以建立考试规则，如：整个考试的时长、考试的总分值、题目来源、每题的分数等等；    
6、简单的课程管理、课程下面包含各种课件、支持在线观看等。    

### 系统功能：
核心在线考试、选择题的答案随机排列，不能固定，防止作弊；
在线学习、训练过程可以展示题目的详细解析等；
其它等等。。。


![输入图片说明](https://images.gitee.com/uploads/images/2020/0812/140134_bd69c408_2189748.png "1.png")
![输入图片说明](https://images.gitee.com/uploads/images/2020/0812/140145_2740a0f3_2189748.png "2.png")
![输入图片说明](https://images.gitee.com/uploads/images/2020/0812/140153_17ff15eb_2189748.png "3.png")
![输入图片说明](https://images.gitee.com/uploads/images/2020/0812/140204_47ff8a05_2189748.png "4.png")

### 快速运行
快速运行资源目录：exam-api/docs/快速运行      
1、安装JAVA1.8以上版本    
2、安装MySQL和Redis，并修改application.yml    
3、导入: exam-api/docs/云帆考试系统-数据库.sql到MySQL数据库    
4、运行：java -jar exam-api.jar --Dspring.config.location=application.yml    
  



### 演示
 
完整版演示地址：https://exam.yfhl.net    
QQ交流群：865330294      
邮箱：18365918@qq.com    
