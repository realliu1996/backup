---
title: Java基础
date: 2018-01-26 15:37:10
tags:
- Java
categories:
- Java
---

# jdk配置

<!--more-->

- 到当前为止推荐下载JDK8（适用于初学者学习）[下载地址](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) 
> 配置jdk其实只用两步：
>> 1.将jdk压缩包解压缩到需要安装的位置
>> 2.配置系统环境变量
- Linux下：
> 1.解压jdk8到/usr/lib/jvm下
> 2.编辑/etc/profile文件，添加如下内容：
> 3.编辑~/.bashrc文件，添加如下内容：
> 4.使环境变量生效：
>> source /etc/profile
>> source ~/.bashrc
>> java -version
```
#JAVA_HOME
export JAVA_HOME=/usr/lib/jvm/jdk1.8.0_161    #解压的jdk8路径
export JRE_HOME=${JAVA_HOME}/jre
export CLASSPATH=.:${JAVA_HOME}/lib:${JAVA_HOME}/lib
export PATH=${JAVA_HOME}/bin:$PATH
```
![jdk8](http://realliublog.oss-cn-hangzhou.aliyuncs.com/study/Java/Java%E5%9F%BA%E7%A1%80/a.png  "jdk8")











