# screenSharerAndControler

开发语言：C 、 C++
采用框架：Qt

本项目目的是实现各终端之间的相互远程控制，各终端需要跨平台。内含对应的服务器段程序。

目前来说，项目中的几个文件的作用分别如下：
1、screenShareAndControler目录下的文件全部是客户端程序，使用C++语言的Qt库编写
2、server目录下的文件全是是服务器端程序，服务器端程序实现账号管理，账号所登录的终端的访问ID的分配和管理，也实现各个终端之间的消息的传递。
3、ScreenRecorder-master.zip文件是网友编写的Android的录屏程序
4、g.c是在修改客户端程序中的录屏部分代码时的一点备份，具体作用还需再阅读代码及其注释
