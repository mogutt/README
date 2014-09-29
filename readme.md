# 项目背景
* 2013年我们蘑菇街从社区导购华丽转身时尚电商平台，为解决千万妹子和时尚卖家的沟通问题，我们开发了自己的即时通讯软件。后来我们问自己既然已经有了用于客服的IM，为什么不自己做一个IM用于公司内部的沟通工具？然后就有了TT(TeamTalk)的雏形，现在蘑菇街内部的在线沟通全部通过TT来完成。蘑菇街在发展壮大的过程中，采用了大量的开源软件，我们一直对开源社区怀有感恩之情，也想为开源社区贡献一份力。随着TT功能的逐渐完善，我们决定把TT开源来回馈开源社区，我们希望国内的中小企业都能用上免费、开源、好用的IM工具！

# 项目介绍
* 名称：TeamTalk
* 官网：http://tt.mogu.io/
* 开源协议：[Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html)
* 定位：中小型企业用户，member >= 2
* 特点：开源与产品并重
* 功能：可靠的消息传递机制；支持文字、图片、语音等富文本信息；文件收发；等	

# 项目框架


麻雀虽小五脏俱全，本项目涉及到多个平台、多种语言，简单关系如下图：
     
![teamtalk架构图](http://s6.mogucdn.com/b7/pic/140921/7n6ih_ieygmzjsmiywezjwmmytambqhayde_514x551.jpg)


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

# 代码下载

####服务端:

- [C++](https://github.com/mogutt/TTCppServer)
- [PHP](https://github.com/mogutt/TTPhpServer)
- [Java](https://github.com/mogutt/TTJavaServer)

####客户端：

- [windows](https://github.com/mogutt/TTWinClient)
- [iOS](https://github.com/mogutt/TTiOSClient)
- [mac](https://github.com/mogutt/TTMacClient)
- [Android](https://github.com/mogutt/TTAndroidClient)

# 交流

* qq交流群：341273218
* 邮件交流：tt@mogujie.com
* 报告issue：[issues](https://github.com/mgjkuaidao/test/issues)
