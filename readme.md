# 项目背景
* 随着蘑菇街由导购向电商转型，蘑菇街自己的IM也应运而生，IM起初只是用于商家和买家之间沟通的工具。后来我们问自己既然已经有了用于客服的IM，为什么不自己做一个IM用于公司内部的沟通工具来替换RTX呢，然后就有了TT(TeamTalk)的雏形，现在蘑菇街内部的IM工具都是TT来完成的。随着TT的逐渐完善，我们再次决定把TT开源来回馈开源社区，我们希望国内的中小企业都能用上免费开源的IM内部沟通具。

# 项目介绍
* 名称：TeamTalk
* 官网：http://tt.mogu.io/
* 开源协议：[Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html)
* 定位：中小型企业用户，小到可以支持10人大到可以支持千人
* 特点：既是做开源，又是做产品的企业办公即时通信软件
* 功能：实时交流沟通，文字、图片、语音等富文本信息；文件收发，在线、离线收发文件；支持企业级别组织架构通讯录；可靠的消息传递机制	

# 项目框架图
![teamtalk架构图](http://s6.mogucdn.com/b7/pic/140921/7n6ih_ieygmzjsmiywezjwmmytambqhayde_514x551.jpg)

####简介
     麻雀虽小五脏俱全，本项目涉及到多个平台、多种技术、多种语言，简单关系如上图。

#### 服务端：
     CppServer对应TTCppServer工程：包括IM消息服务器、http服务器、文件传输服务器、文件存储服务器、登陆服务器
     java DB Proxy对应TTJavaServer工程：承载着后台消息存储、redis等接口
     PHP server对应TTPhpServer工程：teamtalk后台配置页面

#### 客户端：
     mac对应TTMacClient工程 :mac客户端工程
     iOS对应TTIOSClient工程 IOS客户端工程
     Android对应TTAndroidClient工程：android客户端工程
     Windows对应TTWinClient工程：windows客户端工程

* 语言：c++、objective-c、java、php
* 系统环境：Linux、Windows，Mac, iOS, Android

# 相关文档
* [使用文档](https://github.com/mogutt/README/wiki/%E4%BD%BF%E7%94%A8%E6%96%87%E6%A1%A3)
* [开发文档](https://github.com/mogutt/README/wiki/%E5%BC%80%E5%8F%91%E6%96%87%E6%A1%A3)

# 下载
####服务端:
[C++](https://github.com/mogutt/TTCppServer)、[PHP](https://github.com/mogutt/TTPhpServer)、[Java](https://github.com/mogutt/TTJavaServer)

####客户端：
[windows](https://github.com/mogutt/TTWinClient)、[iOS](https://github.com/mogutt/TTiOSClient)、[mac](https://github.com/mogutt/TTMacClient)、[Android](https://github.com/mogutt/TTAndroidClient)

# 交流
* qq交流群：341273218
* 邮件交流：tt@mogujie.com
* 报告issue：[issues](https://github.com/mgjkuaidao/test/issues)
