# 项目名：P2PMapleQQ

## 版本：1.0

## 一、设计内容及要求

  ### A.系统概述

          这是类似QQ这样的面向企业内部的聊天软件，基本功能和QQ类似。首先，系统分为两大部分，第一部分是客户端，
       是用户使用的部分，第二部分就是服务器，所有的客户端都是通过服务器来进行用户身份验证及聊天转接的。客
       户端提供主要的界面及服务请求，如：登录界面、注册界面、找回密码界面、主窗体界面、聊天界面、信息查看
       界面等。客户端主要提供服务请求界面，核心的业务逻辑处理主要由服务器提供，并向客户端发送请求的结果。
       同时，服务器要能提供服务的开启、关闭功能及查看在线人数。

  ### B.员组成和分工

       A.成员
       （组长）：负责整体的架构设计、后台数据库及通信部分、服务器连接。
    
       （组员）：聊天界面、注册界面、登录界面、找回密码
    
       （组员）：主窗体界面、添加好友、查看好友信息、修改个人信息
    
       （组员）：音乐和字体设置。
    
       B.要求
    
       1.小组成员必须按时完成各自的任务。
    
       2.设计上与技术上有问题的先自行解决（看书、上网查），如不能解决的集体讨论解决。有其它的问题及时提出来！
    
       4.每个类必须有类说明，每个函数也必须有函数说明,函数的具体设计也必须有必要的注释。
    
       C.开发环境：
    
       运行环境：Window
    
       使用数据库：SQL Server
    
       使用语言：C#

## 二、功能需求
  ### 功能介绍：
       1.客户端：提供登录、主窗体及聊天等界面及对应的业务逻辑，向服务器发送相应的服务请求，并接受相应的处理结果。
       客户端是轻量级的软件，只负责链接远程服务器，并发出相应的服务请求，并不进行核心业务逻辑的处理。具体的处理
       交给服务器，而客户端只接收服务器处理的结果并显示给用户。
    
       2. 服务器：监控登录信息及在线用户信息，接收客户端的服务请求，并做相应的处理，然后将处理结果发送给客户端。服
       务器负责处理核心的业务逻辑，并负责连接数据库，保存和读取数据。因此，服务器端设计的好坏也直接影响即时通信软
       件的质量。
    
       3. 各项功能需求：
              1.登陆：用户通过QQ号和密码登录。
    
              2.注册账号：用户要先注册账户才能登录聊天。
    
              3.好友聊天：这是最基本也是最主要的功能，可以发送文字、表情等。
    
              4.找回密码：为了避免用户忘记密码而无法登录。
    
              5.查看个人和好友信息：可以查看用户的个人信息。
    
              6.查找添加删除好友：查找好友可以添加，删除好友用于剔除用户。
    
              7.拍照和录视频：打开电脑摄像头完成拍照和录视频。
    
              8.发送文件：可以发送用户文件。


 ### 项目背景及介绍：
        这项目是模仿qq的一种基于C＃网络编程的社交聊天项目，可以实现简单的文字聊天以及
        进行一些文件传输，拍摄等功能，但其稳定性还有待提高，功能还不完善，不支持高并发，
        我是第一次做这种程序，经验与技术严重不足，还望大家多多指教。

 ### 项目部署与运行：

       1.安装VS
    
       2.安装Sqlserver2008
    
       4.创建数据库，导入数据库文件，文件已提供
    
       5.下载我所提供的项目文件，分为服务端与客户端
    
       6.运行项目：
    
         先运行服务端，需要注意的是设置服务端的IP与端口，如果是在本机运行服务端与客户端程序，
         IP可设置127.0.0.1，否则请设置运行服务端的机器上的ip且确保测试机位于同一初始中，
         然后运行客户端去连接服务端，两个客服端互相加上好友后就可以开始聊天，发送文件了，
         不过由于项目未完善，无法发送大文件，且有可能会出现线程堵塞的情况，就是卡死。

## 部分截图
![alt ""](https://www.picbed.cn/image/Zb3qI "登录")
![alt ""](https://www.picbed.cn/image/ZbNrN "注册")
<img alt="修改密码" src="https://www.picbed.cn/image/ZbhCQ" width="100%">
![alt "主页"](https://www.picbed.cn/image/Zb2SG "主页")
![alt ""](https://www.picbed.cn/image/ZbYcF)
![alt ""](https://www.picbed.cn/image/ZbU35)
![alt ""](https://www.picbed.cn/image/ZbnGf)
![alt ""](https://www.picbed.cn/image/ZbARk)
![alt ""](https://www.picbed.cn/image/Zb1KM)
![alt ""](https://www.picbed.cn/image/ZbCvC)

![alt ""](https://www.picbed.cn/image/ZbeSx)

![alt ""](https://www.picbed.cn/image/Zbt9q)