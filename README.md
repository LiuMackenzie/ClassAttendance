<h1>课堂签到 </h1>
<br><br>
软件介绍
node.js+微信开发，实现课堂签到功能。
<br><br>
系统部署
将项目拷贝到服务器端
-node weChatServer.js
使用MySQL数据库，创建数据库需要用到的脚本，在MYSQL.txt中
<br><br>
使用帮助（见tip.jpg）<br>
1.老师身份用户发送课程号码至服务器端。<br>
2.服务器端，返回本次签到的课程验证码。<br>
3.学生按照老师给的签到码，输入到公众号内。<br>
4.学生再次发生自己的地理信息。<br>
5.签到结束，服务器项目的static文件夹下找寻学生签到的文件。
  （每个课程，某一天的签到情况作为一个签到文件，独立存放）<br>
<br>
开发人员信息
刘洋 1501210955