# weiyi68
SSM优测项目管理平台的设计与实现 

#### 介绍
本课题分析了线上现有的软件测试管理工具，为了使项目管理和 Bug 管理实时性
更强，功能更加完整。设计和研发了一套基于 MVC 的测试项目管理平台。本平台集成
开发环境是 Eclipse，使用 MySQL 作为数据库管理系统，Web 服务器采用 Tomcat，运
用了 MVC 思想实现优测项目管理平台的 B/S 架构。平台具备的功能有：建立项目、建
立任务、测试用例管理、测试进度查看、测试结果的输入输出、Bug 的提交与流转、
Bug 的状态、日报月报输出功能等，初步的完成了测试项目管理测试 Bug 的管理。 
平台的实现能够大大的提高测试效率，并可以对于项目管理人员可以实时了解测
试任务进度，及时对下一步的测试任务进行预算和安排。日报月报的输出，可以快速
检索到完成时间较长，及时同步反馈，可以节省测试报告编写的时间。该平台运行稳
定，易用性强，能够满足测试人员、开发人员、项目管理人员的日常需求。 
 

![输入图片说明](https://images.gitee.com/uploads/images/2020/1129/234249_5b66ad2f_4865385.png "屏幕截图.png")

系统主要功能分为：管理人员、开发人员、测试人员三个模块。  
    （1）管理人员功能 
    对项目、版本、测试任务、用户角色、查看测试进的、报告输出等功能 。 
① 系统可以通过管理人员为工作人员添加开发人员与测试人员权限账号 。 
② 系统登陆功能，管理人员输入账号密码后可以登录项目管理平台。 
③ 项目管理功能，管理人员可以增加测试项目、测试版本、测试任务。 
④ 任务管理功能，管理人员可以通过平台分配每个项目对应版本的测试任务，并
且对任务做出修改操作。  
⑤ 测试报告导出功能，在测试人员结束自己对应的测试任务后，管理人员可以导
出测试结果。  
（2）测试人员功能 
查看当前测试任务、查看测试进度、对测试版本机型注释、回归测试等功能。 
① 测试人员登录功能，系统可以通过测试人员身份账号密码登录平台。 
② 测试人员查看测试进度功能，测试人员可以查看当前需要进行的测试任务。 
③ 测试人员查看测试任务进度功能，测试人员可以查看当前进行的测试任务进度。
 
④ 测试人员机型注释功能，测试人员可以在测试过程中对测试过机型添加备注。 
⑤ 测试人员提交 Bug 功能，测试人员可以根据测试流程及描述提交测试 Bug。 
（3）开发人员功能 
提交测试任务、查看测试任务进度、查看测试 Bug 等功能。 
① 开发人员登录功能，系统可以通过开发人员身份账号密码登录平台。 
② 开发人员提交测试任务功能，开发人员可以根据项目对应自己开发的版本提交
测试任务并上传测试机型。 
③ 开发人员查看测试进度功能，开发人员可以根据完成机型款次，查看测试任务
进度。 
④ 开发人员查看测试 Bug 功能，在查看 Bug 管理功能中，开发人员可以看到测试
人员提交的测试 Bug。 
在图 2.3 高层用例图中抽取了满足项目管理平台需求的基本用例。这些用例可以从
用管理人员、测试人员、开发人员三个方面完成整个项目管理平台的正常运作。 

![输入图片说明](https://images.gitee.com/uploads/images/2020/1129/234325_21de705c_4865385.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1129/234340_72e0a48d_4865385.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1129/234347_21d54b30_4865385.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1129/234355_56120004_4865385.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1129/234402_5da37852_4865385.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1129/234409_48aa7e3a_4865385.png "屏幕截图.png")


联系Q：2762501186
![输入图片说明](https://images.gitee.com/uploads/images/2020/1119/003728_cd598bb9_4865385.jpeg "微信.jpg")
