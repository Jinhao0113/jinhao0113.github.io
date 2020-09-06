---
title: github 使用进阶
date: 2020-08-31 17:14:42
tags: -github
---

# 前言

> github作为一个标准的国外网站；总是会被各种“墙”和“封”
> 有一种办法可以比较稳定的使用github;在一定程度上还能提速一点

### Start

使用[https://www.ipaddress.com/](https://www.ipaddress.com/)查询以下网址的真是IP地址

```txt
gist.github.com
github.com
www.github.com
api.github.com
avatars0.githubusercontent.com
avatars1.githubusercontent.com
avatars2.githubusercontent.com
avatars3.githubusercontent.com
avatars4.githubusercontent.com
avatars5.githubusercontent.com
avatars6.githubusercontent.com
avatars7.githubusercontent.com
avatars8.githubusercontent.com
camo.githubusercontent.com
cloud.githubusercontent.com
gist.githubusercontent.com
marketplace-screenshots.githubusercontent.com
raw.githubusercontent.com
repository-images.githubusercontent.com
user-images.githubusercontent.com
```

然后将其改为

```txt
IP + 域名的格式
```

以下是我查出来的结果

```txt
140.82.112.4 gist.github.com
140.82.114.4 github.com
140.82.112.4 www.github.com
140.82.113.5 api.github.com
199.232.68.133 avatars0.githubusercontent.com
199.232.68.133 avatars1.githubusercontent.com
199.232.68.133 avatars2.githubusercontent.com
199.232.68.133 avatars3.githubusercontent.com
199.232.68.133 avatars4.githubusercontent.com
199.232.68.133 avatars5.githubusercontent.com
199.232.68.133 avatars6.githubusercontent.com
199.232.68.133 avatars7.githubusercontent.com
199.232.68.133 avatars8.githubusercontent.com
199.232.68.133 camo.githubusercontent.com
199.232.68.133 cloud.githubusercontent.com
199.232.68.133 gist.githubusercontent.com
199.232.68.133 marketplace-screenshots.githubusercontent.com
199.232.68.133 raw.githubusercontent.com
199.232.68.133 repository-images.githubusercontent.com
199.232.68.133 user-images.githubusercontent.com
```

### Then

打开`hosts`文件,在文件末尾处添加上述内容

* Mac/linux 上在`/etc/hosts`
* Windows 上在`C:\Windows\System32\drivers\etc`

    注意:一定要管理员权限!!!!!!!

### Finally

直接重启一波;然后就OK了