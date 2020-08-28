---
layout:     post
title:      vmware安装ubuntu
subtitle:   ubuntu linux相关
date:       2020-08-08
author:     lz2019hjh
header-img: img/post-bg-hacker.jpg
catalog: true
tags:
    - 虚拟机
    - ubuntu
    - linux
---

如果是一个合格的电脑~~作死~~玩家，就一定要会使用虚拟机进行~~进一步作死~~一些日常工作。

之前已经介绍过如何用`vmware`安装`windows10`，于是为了尝试一下`linux`，我进行了~~进一步作死~~

然后作为一个菜鸡，只能玩玩入门级的`ubuntu linux`了

### 材料准备

1. 一台装有`vmware`的`mac`
2. `ubuntu`系统镜像[网易镜像站下载地址](http://mirrors.163.com/ubuntu-releases/)，和`windows7`镜像[msdn下载](https://msdn.itellyou.cn/)实在不行，有`windows10`的也行，不过在安装`windows`的时候要花更多时间
3. 时间(一个小时左右)

### 思路

首先，经过我多年的经验，`vmware`安装`ubuntu`一定无法获得很好的清晰度。然而，`windows`却有，所以我们可以用`ubuntu`覆盖`windows`。

### 开始

##### windows安装

选择镜像文件
![](https://tva1.sinaimg.cn/large/007S8ZIlly1ghkv6iyqyyj30yz0u07lp.jpg)

点击继续

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ghkv7fdzvtj30yz0u0ne9.jpg)

因为不需要使用这台`windows`所以账户名，密码乱填都可以。我在这里使用专业版

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ghkv991kijj30yz0u0wvo.jpg)

再点击继续，跳出来叫你输入密匙直接`不输入并继续使用`

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ghkvb8zn59j30yz0u0k8o.jpg)

然后点击右边那个`更加独立`

再点击继续

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ghkvbxzxwkj30yz0u0tqg.jpg)

点击`自定设置`,然后保存好虚拟机

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ghkvd5lkxhj31560u0naw.jpg)

然后跳出

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ghkvdhahcdj313b0u0h4v.jpg)

先改`处理器和内存`

改成这样

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ghkvekg4fpj310z0u04bn.jpg)

`显示器`改成这样

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ghkvfs7mn3j313d0u0qhb.jpg)

然后将`硬盘`改成

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ghkvhcafn2j315s0n2doc.jpg)

其他可以不用改，关闭这个窗口，然后打开虚拟机

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ghkviojx9hj310h0u0dyp.jpg)

安装中...

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ghkvj69xmrj31c00u0tbh.jpg)

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ghkvk3lu9sj31c00u0h7h.jpg)

等它安装完`vmware tools`以后将其关机

经过`40min`的奋斗，终于安装完了`windows7`

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ghkwq4ber6j31c00u07wk.jpg)

关机，然后打开设置，将`软盘`移除(没啥卵用)

然后点击`CD/DVD(SATA)`点击

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ghkwtb5wf0j315s0higs7.jpg)

将下拉框拉到下面那个

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ghkwui8qiwj31a00u0kao.jpg)

选择你下载的`ubuntu镜像`，点击打开

然后点击`显示全部`回到主页面

点击的三行的`启动磁盘`

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ghkwwdt1thj315s0ls11q.jpg)

选择从`CD/DVD`启动

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ghkwxal3qwj31c00u0mzw.jpg)

正常的`ubuntu`启动

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ghkwz7taucj31c00u0tc3.jpg)

`ubuntu20.04`专有

打开`ubuntu`安装界面

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ghkx1ejnw7j31c00u0dmq.jpg)

左边是语言，我这边选择`中文（简体）`，点击右侧的`安装Ubuntu`

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ghkx40hn14j31c00u0jxt.jpg)

点击继续

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ghkx4fxk25j31c00u00yv.jpg)

自己选择选项，然后点击`继续`

安装类型选择`清除整个磁盘`

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ghkx7vxgudj31c00u04qu.jpg)

然后点击现在安装

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ghkx9guhqej31c00u04qu.jpg)

点击继续

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ghkxazc3orj31c00u07wm.jpg)

再点击继续

然后是注册

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ghpjfxyxbij31c00u01l2.jpg)

注册完了以后点击继续

就开始了安装

waiting......

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ghpjgx588cj31c00u04qu.jpg)

在`ubuntu18.04`开始，安装时会自动安装`vmware tools`

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ghpjld0eazj31c00u0kjq.jpg)

点击`现在重启`

过程中，可能会让你按回车

重启完就可以欢乐使用`ubuntu`了。

登陆后

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ghpjp11qaaj31c00u0qb1.jpg)

不停点右上角的按钮

接下去是安装`vmware tools`

在命令行里输入
```
open /Applications/VMware\ Fusion.app/Contents/Library/isoimages 
```

然后找到`linux.iso`复制到桌面。

将`~/Desktop/linux.iso`这个文件连接到虚拟机。

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ghpk4xd5fwj31c00u0gu4.jpg)

点击那个光盘

将里面那个压缩包打开，解压到桌面

然后打开目录

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ghpk7rgtf1j31c00u0n5p.jpg)

在终端里打开

输入`sudo ./vmware*.pl`

输入密码后

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ghpk8ucxfxj31c00u0gtw.jpg)

输入`yes`然后回车。

接下去只要不停按回车

然后你会发现

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ghpkaqnb0bj31c00u0wtl.jpg)

加载出来了

然后打开设置

点击显示器

![](https://tva1.sinaimg.cn/large/007S8ZIlly1ghpkbmed9zj31c00u0n6u.jpg)

将`100%`改为`200%`点击右上角的应用，然后点击`保留更改`。

这样就可以快乐使用`ubuntu`了。

在下一篇文章中，会介绍`ubuntu`的优化及设置。

