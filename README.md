# homework5

## 描述
未来的几期作业会带你们做一个完整的博客系统

本期做的是用户登录注册，本来应该是你们早应该弄明白的，这次接入数据库

在3.7前完成

## 细节要求
使用mysql数据库

python用flask，go用gin

需要有真正的注册、登录、用户主页，也就是说，除了后端代码，还需要写简单的前端代码，前端内容不需要前后端分离，用模板渲染就行了。[flask看这里](https://www.jianshu.com/p/23e2bc731598)，[gin看这里](https://www.bookstack.cn/read/topgoer/ecf3f148f88a6f17.md)，用gin的也可以看一下flask的那篇文章，模板渲染这个名词说的比较详细。

登录页面：用户名、密码、确定按钮、到注册的链接

注册页面：用户名、密码、确认密码、确定按钮、到登录的链接

用户主页：显示用户名

界面和逻辑可以参考 [http://user.ibeike.com](http://user.ibeike.com)

## 具体操作

### 环境准备
我建议你们是直接去弄个云服务器算了，反正也是得简单学习linux环境的。[腾讯云](https://curl.qcloud.com/a74cTk2i)有学生计划，10元/月。[阿里云](https://developer.aliyun.com/plan/grow-up?source=5176.11533457&userCode=xfjbv1lc)这个好像是可以领？也有优惠价就是了。

或者自己用vmware或者virtualbox开虚拟机也是可以，virtualbox是免费软件官网下载就好，vmware是收费软件但是也不需要找破解，网上有15（最新版本）的key。

虚拟机建议使用ubuntu或者debian，不要centos，你用起来会想死的。

linux环境准备好之后就可以用 bt.cn 一键安装面板（对小白很友好），安装mysql，当然你想自己装那就更好了。

不过数据库默认都是只允许本机连接，你需要自己配置一下。

当然，你可以选择在windows上用mysql，有比如phpstudy或者wnmp/wamp能给你一个很简单的mysql服务，那个也行。

### 继续
弄好数据库之后就没啥了，有问题群里问

## 预计时间
环境 1d

前端部分因为内容特少 2h

阅读session原理 1h

学习数据库基础知识（本次涉及语句select, insert） 3h

后端 2h

再提一句，数据库（关系型数据库）很简单的，别想着多难，你就把他当成一个excel表格就好了


