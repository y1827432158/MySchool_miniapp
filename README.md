# MySchool_miniapp
移动应用开发期末大作业
Myschool校园交流平台项目部署说明书
                                                      冯诗雨 余浩
一、项目概述
我们设计的是一个Daily MySchool的情侣交互小程序，是自己与另一半专属的空间。在这里，我们可以通过发帖来对情侣或者好友进行情话传输，同时还可以分享自己在校园生活的点点滴滴，看到喜欢的内容的可以进行评论或点赞等。为了增加情侣和好友之间的情感生活而设计的一个微信小程序。
二、功能
1.硬件要求：
①CPU：至少四核处理器，以保证在多用户同时访问时的处理能力。
②内存：建议配置8GB或以上内存，以支持更多的并发处理。
③硬盘：固态硬盘（SSD）至少256GB，提供更快的数据读写速度，提升响应时间。
④带宽：根据小程序的用户访问量来定，初期可以选择10Mbps共享带宽，随着用户增多可适当增加。
2.软件要求：
①操作系统：Windows操作系统
②数据库：微信云数据库
③编程语言环境：
后端开发：运用js语言配置相应的运行环境。
前端开发：由于微信小程序运行在用户的手机或平板上，所以前端主要依赖微信客户端提供的API和框架，不需要特定的软件环境。
④开发工具：微信开发者工具
三、安装步骤
   无特定安装步骤，用户仅需要打开微信并运行小程序即可。
四、数据库配置
   项目使用微信云数据库，在数据库中创建数据库和用户。
五、编译和构建
   直接在微信开发者工具中进行编译，以及运用js,css等语言构建项目。
六、部署和启动
①将项目部署到服务器指定路径。
②配置项目的环境变量和配置文件。
③启动项目。
七、验证和测试
可以通过扫描请求访问后在微信中访问小程序，之后就可以在小程序中测试功能以及验证程序的完整性和准确性。
八、常见问题和解决方案
在发布了表白信息或者交友信息后，可能过一段时间在主页上看不到自己发布的信息，因为内容过一段时间会刷新，但是发过的信息不会消失，用户可在“我的”页面中查看已经发送过的内容。
九、升级和维护
   会定期对小程序的功能进行完善以及调整，对整个程序进行升级维护，以保证更好地使用程序来交友和恋爱。
