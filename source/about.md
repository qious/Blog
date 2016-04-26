---
title: 个人简介
date: 2016-04-26
---

### **基本信息**
* 邱俊 / 男 / 1996
* 2017.06毕业 / 四年制本科
* 湖南科技大学 / 计算机科学与技术专业
* 博客：[qious.cn](https://qious.cn/) / GitHub： [github.com/qious](https://github.com/qious)
* QQ: [351310146](http://wpa.qq.com/msgrd?v=3&uin=351310146&site=qq&menu=yes) / Mail: [mail@qious.cn](mailto:mail@qious.cn)

### **技能清单**
* 熟悉PHP、Node.js、Python等
* 熟悉AngularJS、Gulp、CoffeeScript等
* 熟悉MySQL，了解Redis、MongoDB等NoSQL
* 熟悉 BootStrap、Semantic UI 等前端框架
* 熟悉微信平台、微信企业号的开发与运维
* 熟悉Linux，有IaaS、PaaS、SaaS等开发及管理经验
* 有过ACM经历，获得过省级、市级、校级奖励
* 有Docker容器、ZStack云平台搭建及使用经验

### **主要项目经历**

#### **第三方查询网站**(独立完成)
在后面的“查水表小分队”微信被关闭后，独立开发完成(小范围使用)
* 后端主要使用 PHP + Node.js 开发，前端使用 Semantic + Angular 完成，主要功能如下:
* 基于模拟登陆、验证码识别的成绩、课表、考试、绩点、教室、评教、选课、图书检索、续借、一卡通、学费等功能
* 基于数据统计分析等的全班成绩、成绩排名、挂科率统计、教室反查上课班级、选修课同学统计、指定一定成员的无课时间查询、一卡通学期账单等功能
* 对成绩、课表、排名等常用功能提供图片、Excel导出等功能
* 基于 Cron 的成绩提醒、图书自动续借、图书超期提醒、一卡通提醒等功能 (通过邮件、微信、Socket等)
* 基于 Socket.io 的实时日志、在线用户、推送、彩蛋等功能
* 为其他同学提供 HTTP + JSON 的API(同学在此基础上开发了安卓客户端)
* GitHub地址：[github.com/qious/hnust](https://github.com/qious/hnust) (已去除敏感数据)

#### **湖南科技大学企业号**(主力开发成员、负责人)
基于微信企业号，独立或主导开发过一系列企业号应用
由于学校各大系统无相应接口，所以涉及到其他系统的部分均为模拟登陆、爬虫等实现
下列应用前后端均为独立完成：
* 基于WebSocket的多管理员的留言反馈平台(IM)
* 基于模拟登陆的成绩、课表、考试安排、空闲教室等查询模块
* 仿今日头条的学校十多个新闻整合站点
* 其他如失物招领、学校概况、天气、快递等小应用
![新闻](/uploads/about/news.png) ![留言板](/uploads/about/board.png)

#### **"查水表小分队" 微信**(主要开发成员)
此为企业号的前身，与一相同兴趣爱好同学基于SAE共同开发
首月关注量突破3000，一年关注量突破24000(全校90%以上在校本科生)
* 功能模块主要基于验证码识别、模拟登陆、爬虫等
* 完成了校内学生所涉及到各项教务、图书、财务(非充值)等近乎所有功能功能
* 娱乐方面更是提供微信小游戏、微信墙、答题等功能
* 由于与学校沟通存在问题被关闭，[关闭前详细介绍>>](https://github.com/qious/csbxfd)

#### **微信课堂**(主要开发成员)
微信课堂主要包括课前签到、上课推题、在线答题、课后做题、自主学习等功能
但是由于学校教室存在无网问题、以及学生教师等数据对接问题，开发出测试版本后暂时被搁置
* 上课签到:使用动态二维码进行上课签到
* 上课推题:利用微信平台教师将提前准备好的题目推送给学生
* 在线答题:学生端对收到老师的题目进行回答，同时生成答题报告。同时教师端也生成总的答题报告
* 课后做题:类似于上课推题，只是做题是课后完成的
* 自主学习:教师端在线编辑好的学习资料、上传的PPT、WORD文档等，学生可自由浏览或下载
![微信课堂](/uploads/about/class.png)

#### **微信签到**(主要开发成员)
此项目主要为了解决学校大一大二学生每周体育锻炼签到签到问题
由于微信限制，定位主要利用WIFI定位数据，同时提供扫码签到等作为辅助方案
* 签到主要有定位签到和扫码签到(基于微信平台)，扫码为定位失败的补充
* 扫码使用为动态二维码，使用Socket签到一个换一个(一次只能扫一个)或定时更换两种方案
* 数据与学校人事系统对接
![微信签到](/uploads/about/sign.png) ![开始签到](/uploads/about/signin.png)

#### **一卡通学期账单分析**（独立完成）
* 对一卡通消费数据进行简单统计分析
* 由于数据太少，数据分析能力弱。[DEMO>>](http://bill.ticknet.cn)
![一卡通](/uploads/about/bill.png)

#### **闲置Docker**（独立完成）
利用学校闲置的服务器，使用Docker主要搭建了以下工具:
* 内网Ubuntu 14.04源
* 内网Samba文件共享
* [基于Gogs的Git服务器](http://git.ticknet.cn/)
* 为其他同学提供实验平台。利用闲置服务器搭建的Docker

#### **基于ZStack的校园私有云**(成员参与)
* 基于ZStack进行二次开发(校大学生创新重点项目)
* 由于ZStack提供一键式部署，并未投入过多精力。