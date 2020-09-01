---
title: ubuntu linux 使用
date: 2020-08-30 22:34:04
tags: -linux -ubuntu
---

# 前言

> `ubuntu`虽然是最有好的`linux`之一，但还是有有一些设置需要改

### 换源

默认的源速度感人

终端输入

```bash
$ sudo cp /etc/apt/sources.list /etc/apt/sources.list.asd # 备份官方源
$ sudo rm /etc/apt/sources.list # 删除官方源
$ sudo apt-get install vim # 安装vim
$ sudo vim /etc/apt/sources.list # 创建并编辑软件源文件
$ # 输入`i`,然后将对应版本的软件源配置(见下)复制进去,然后按 `esc` 输入`:wq`
$ sudo apt update # 刷新软件源
$ sudo apt upgrade # 更新
```
### 安装日常使用软件

```bash
$ sudo apt-get install wget curl gcc git python make openssh-server # 日常工具
$ wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb # 下载google浏览器
$ sudo dpkg -i google-chrome-stable_current_amd64.deb # 安装google浏览器
$ wget https://vscode.cdn.azure.cn/stable/a0479759d6e9ea56afa657e454193f72aef85bd0/code_1.48.2-1598353430_amd64.deb # 下载vscode
$ sudo dpkg -i code_1.48.2-1598353430_amd64.deb # 安装vscode
$ sudo apt-get install http://d1.music.126.net/dmusic/netease-cloud-music_1.2.1_amd64_ubuntu_20190428.deb # 安装网易云音乐
$ sudo dpkg -i netease-cloud-music_1.2.1_amd64_ubuntu_20190428.deb
$ wget https://wdl1.cache.wps.cn/wps/download/ep/Linux2019/9615/wps-office_11.1.0.9615_amd64.deb # 下载WPS office
$ sudo dpkg -i wps-office_11.1.0.9615_amd64.deb # 安装WPS office
```

### sources.list

> 使用清华源

* ubuntu 14.04

```bash
deb http://mirrors.163.com/ubuntu/ trusty main restricted universe multiverse
deb-src http://mirrors.163.com/ubuntu/ trusty main restricted universe multiverse
deb http://mirrors.163.com/ubuntu/ trusty-updates main restricted universe multiverse
deb-src http://mirrors.163.com/ubuntu/ trusty-updates main restricted universe multiverse
deb http://mirrors.163.com/ubuntu/ trusty-backports main restricted universe multiverse
deb-src http://mirrors.163.com/ubuntu/ trusty-backports main restricted universe multiverse
deb http://mirrors.163.com/ubuntu/ trusty-security main restricted universe multiverse
deb-src http://mirrors.163.com/ubuntu/ trusty-security main restricted universe multiverse
```

* ubuntu 16.04

```bash
deb http://mirrors.163.com/ubuntu/ xenial main restricted universe multiverse
deb-src http://mirrors.163.com/ubuntu/ xenial main restricted universe multiverse
deb http://mirrors.163.com/ubuntu/ xenial-updates main restricted universe multiverse
deb-src http://mirrors.163.com/ubuntu/ xenial-updates main restricted universe multiverse
deb http://mirrors.163.com/ubuntu/ xenial-backports main restricted universe multiverse
deb-src http://mirrors.163.com/ubuntu/ xenial-backports main restricted universe multiverse
deb http://mirrors.163.com/ubuntu/ xenial-security main restricted universe multiverse
deb-src http://mirrors.163.com/ubuntu/ xenial-security main restricted universe multiverse
```

* ubuntu 18.04

```bash
deb http://mirrors.163.com/ubuntu/ bionic main restricted universe multiverse
deb-src http://mirrors.163.com/ubuntu/ bionic main restricted universe multiverse
deb http://mirrors.163.com/ubuntu/ bionic-updates main restricted universe multiverse
deb-src http://mirrors.163.com/ubuntu/ bionic-updates main restricted universe multiverse
deb http://mirrors.163.com/ubuntu/ bionic-backports main restricted universe multiverse
deb-src http://mirrors.163.com/ubuntu/ bionic-backports main restricted universe multiverse
deb http://mirrors.163.com/ubuntu/ bionic-security main restricted universe multiverse
deb-src http://mirrors.163.com/ubuntu/ bionic-security main restricted universe multiverse
```

* ubuntu 20.04

```bash
deb http://mirrors.163.com/ubuntu/ focal main restricted universe multiverse
deb-src http://mirrors.163.com/ubuntu/ focal main restricted universe multiverse
deb http://mirrors.163.com/ubuntu/ focal-updates main restricted universe multiverse
deb-src http://mirrors.163.com/ubuntu/ focal-updates main restricted universe multiverse
deb http://mirrors.163.com/ubuntu/ focal-backports main restricted universe multiverse
deb-src http://mirrors.163.com/ubuntu/ focal-backports main restricted universe multiverse
deb http://mirrors.163.com/ubuntu/ focal-security main restricted universe multiverse
deb-src http://mirrors.163.com/ubuntu/ focal-security main restricted universe multiverse
```
