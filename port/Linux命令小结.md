---
title: Linux命令小结
date: 2018-01-20 17:08:19
tags:
- Linux
categories:
- 学习
---
# Linux命令小结
- linux操作系统是一种很简介、方便的语言，使用命令行能够解决很多鼠标困难甚至不能完成的事情

<!--more-->

## 基本的电脑命令
- 关闭计算机
```
shutdown -h now
```

- 重启计算机
```
reboot
```

- 查看Linux系统版本信息
```
cat /etc/issue
```

- 查看IP
```
ifconfig -a
```

- 显示当前进程
```
top
```

- 清屏
```
clear
```

## 基本的文件处理命令
- 查看文件内容
```
cat     由第一行开始显示内容，并将所有内容输出
tac     从最后一行倒序显示内容，并将所有内容输出
more    根据窗口大小，一页一页的现实文件内容
less    和more类似，但其优点可以往前翻页，而且进行可以搜索字符
head    只显示头几行
tail    只显示最后几行
nl      类似于cat -n，显示时输出行号
```

- 创建、复制、移动、删除文件（如操作文件test到目录/home）
```
touch test
cp test /home
mv test /home
rm test /home
```

- 创建、复制、移动、删除目录（如操作目录test到目录/home）
```
mkdir test
cp -r test /home
mv -r test /home
rm -r test /home
```

- 压缩、解压文件
```
.tar
tar xvf FileName.tar （解包）
tar cvf FileName.tar DirName（tar是打包，不是压缩）
.gz
gunzip FileName.gz（解压）
gzip FileName（压缩）
.tar.gz 和 .tgz
tar zxvf FileName.tar.gz（解压）
tar zcvf FileName.tar.gz DirName（压缩）
.zip
unzip FileName.zip（解压）
zip FileName.zip DirName（压缩）
.rar
rar x FileName.rar（解压）
rar a FileName.rar DirName（压缩）
```

- 修改文件内容、属性及权限（如操作文件test）
```
vim test
chgrp users test（修改文件 test 的所属用户组为 users ）
chown use test（修改文件 test 的所有者为 use ）
chmod 777 test（修改文件test的权限为任何人都有读、写、运行三项权限）
```

- 下载、安装、卸载软件
```
(Ubuntu)
sudo apt-get install tree           安装tree
sudo apt-get remove tree            卸载tree
sudo apt-get update                 更新软件
```
















