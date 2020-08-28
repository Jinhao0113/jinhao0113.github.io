---
layout:     post
title:      mac上利用vmware安装windows10
subtitle:   解决双系统与虚拟机之间的决定
date:       2020-03-29
author:     lz2019hjh
header-img: img/post-bg-hacker.jpg
catalog: true
tags:
    - 虚拟机
    - windows10
---


> 相信用苹果电脑的小伙伴们一定会被`mac`上一些应用的缺少或者不习惯而想装上`windows`对吧,再不换电脑的情况下解决方案有两个`双系统`与`虚拟机`,在我看来,`虚拟机`会比`双系统`效率与性能更强,安装更方便.

### 工具及软件准备

一台装有**mac**的电脑,**vmware**和**windows10的镜像文件**

### 材料收集

**vmware**[官方下载网址](https://download3.vmware.com/software/fusion/file/VMware-Fusion-11.5.3-15870345.dmg)

**windows10镜像文件**[官方下载网址](https://www.microsoft.com/zh-cn/software-download/windows10ISO?36261b60-2f68-4336-abe2-4b00f210b6aa=True)自己找一个适合自己的版本下载

>上述文件下载很慢很慢,可以使用迅雷下载之类的方法加速

### 激活vmware

网上有很多激活码,随便尝试几个,总有可以的

我用的是

    XKZYV-PK9CC-A1Y0X-K5HZL-Y65ZV

现在不一定还可以用

### 开始安装windows10

![](https://tva1.sinaimg.cn/large/00831rSTly1gdb52li3a2j31850u0qms.jpg)

然后点击`新建`

会出现

![](https://tva1.sinaimg.cn/large/00831rSTly1gdb54ndrnoj30yz0u07ia.jpg)

打开你**Windows10镜像文件的下载目录**

接下去将文件拖到窗口里

点击继续

然后可以看见

![](https://tva1.sinaimg.cn/large/00831rSTly1gdirqc53n5j30yz0u0wvk.jpg)

写好账户名和密码

然后选择你的windows10版本

我用的是`windows10 pro Education`

![](https://tva1.sinaimg.cn/large/00831rSTly1gdirstszi6j30yz0u0h2x.jpg)

然后点击继续

![](https://tva1.sinaimg.cn/large/00831rSTly1gdirtnm8dkj30yz0u0dwv.jpg)

点击 ![](https://tva1.sinaimg.cn/large/00831rSTly1gdirusss0oj309s01a0sx.jpg)

然后点击 ![](https://tva1.sinaimg.cn/large/00831rSTly1gdirvtdmnfj309e08o755.jpg)

还是点击继续

接下去，进行一些虚拟机的配置

点击![](https://tva1.sinaimg.cn/large/00831rSTly1gdirx93nvdj305e01qmx8.jpg)

保存好你的虚拟机命名

![](https://tva1.sinaimg.cn/large/00831rSTly1gdiryljq0nj31560u0wqz.jpg)

点击储存

然后会跳出

![](https://tva1.sinaimg.cn/large/00831rSTly1gdirzcdx9hj31340u0dz3.jpg)

强烈建议将内存开到`4096MB`,因为`windows10`有点大。

点击![](https://tva1.sinaimg.cn/large/00831rSTly1gdis163zw8j304q054q38.jpg)

看到

![](https://tva1.sinaimg.cn/large/00831rSTly1gdis3djkj0j315s0pktht.jpg)

改为

![](https://tva1.sinaimg.cn/large/00831rSTly1gdis4ic1foj315s0pkaj8.jpg)

然后点击`显示全部`

点击![](https://tva1.sinaimg.cn/large/00831rSTly1gdiy9mq3dvj304s04u0t8.jpg)


在点击高级选项

将`拆分为多个文件`，点掉，大小自己改

最后


![](https://tva1.sinaimg.cn/large/00831rSTly1gdiybktn1dj315s0n2471.jpg)

长这样

然后就可以启动虚拟机了

![](https://tva1.sinaimg.cn/large/00831rSTly1gdiycnolrcj310h0u0tru.jpg)

点击中间的三角形

接下去就只要坐等一段时间

![](https://tva1.sinaimg.cn/large/00831rSTly1gdiyf0j2v1j31140u0178.jpg)

![](https://tva1.sinaimg.cn/large/00831rSTly1gdiyfy3nuqj31140u04e0.jpg)

![](https://tva1.sinaimg.cn/large/00831rSTly1gdiz6wd8cuj31c00u0b29.jpg)

![](https://tva1.sinaimg.cn/large/00831rSTly1gdizc2u6q6j31c00u04qs.jpg)

![](https://tva1.sinaimg.cn/large/00831rSTly1gdizd68teoj31c00u01kz.jpg)

这样就装完了

接下去，我们来激活`windows10`吧

方法很多（不花钱），下面我介绍一种我成功的（貌似是永久的）

点击[下载](https://lz2019hjh.github.io/doc/HWIDGEN.zip)

解压后

在共享文件夹中打开

![](https://tva1.sinaimg.cn/large/00831rSTly1gdj07361mpj31c00u0npd.jpg)

复制到桌面

管理员运行`Activation.cmd`

![](https://tva1.sinaimg.cn/large/00831rSTly1gdj0b2sv25j31c00u0qv5.jpg)

按回车。

![](https://tva1.sinaimg.cn/large/00831rSTly1gdj0dvciw0j31c00u0qv5.jpg)

按`1`

等一会就可以激活了

![](https://tva1.sinaimg.cn/large/00831rSTly1gdj0ct1amwj31c00u0qv5.jpg)

这样就可以快乐使用`windows10`