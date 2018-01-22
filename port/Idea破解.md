---
title: Idea破解
date: 2018-01-20 10:26:45
tags:
- 分享
categories:
- 分享
---
# Idea破解
- 最近在使用Idea学习，但是Idea Ultimate版需要收费，根据网上各种各样的破解方法，整理出了最有用的一种破解方法（适用于Windows系统和Linux系统）
<!--more-->

> 需要用到的东西：
>> 安装好的Idea Ultimate版
>> 破解补丁：JetbrainsCrack [下载地址](https://pan.baidu.com/s/1kWylaAz "JetbrainsCrack-2.6.10")

![](http://realliublog.oss-cn-hangzhou.aliyuncs.com/study/Idea%E7%A0%B4%E8%A7%A3/idea.jpg "Idea")
## Ubuntu下破解：
- 下载JetbrainsCrack破解补丁，将破解补丁复制到Idea安装目录的lib目录下：
```
cd /home/realliu/下载/
sudo cp JetbrainsCrack-2.6.10-release-enc.jar /opt/idea-IU-173.4127.27/lib/
```

- 编辑Idea安装目录的bin目录下的idea.vmoptions文件和idea64.vmoptions文件，在文件末尾添加文本：
```
sudo vi /opt/idea-IU-173.4127.27/bin/idea.vmoptions 
sudo vi /opt/idea-IU-173.4127.27/bin/idea64.vmoptions
```
![](http://realliublog.oss-cn-hangzhou.aliyuncs.com/study/Idea%E7%A0%B4%E8%A7%A3/Idea_1.png "idea.vmoptions文件")
![](http://realliublog.oss-cn-hangzhou.aliyuncs.com/study/Idea%E7%A0%B4%E8%A7%A3/Idea_2.png "idea64.vmoptions文件")

- 然后打开Idea Ultimate版，进入Help里面的Register，在Activation code 中输入：
```
ThisCrackLicenseId-{  
"licenseId":"ThisCrackLicenseId",  
"licenseeName":"idea",  
"assigneeName":"",  
"assigneeEmail":"idea@163.com",  
"licenseRestriction":"For This Crack, Only Test! Please support genuine!!!",  
"checkConcurrentUse":false,  
"products":[  
{"code":"II","paidUpTo":"2099-12-31"},  
{"code":"DM","paidUpTo":"2099-12-31"},  
{"code":"AC","paidUpTo":"2099-12-31"},  
{"code":"RS0","paidUpTo":"2099-12-31"},  
{"code":"WS","paidUpTo":"2099-12-31"},  
{"code":"DPN","paidUpTo":"2099-12-31"},  
{"code":"RC","paidUpTo":"2099-12-31"},  
{"code":"PS","paidUpTo":"2099-12-31"},  
{"code":"DC","paidUpTo":"2099-12-31"},  
{"code":"RM","paidUpTo":"2099-12-31"},  
{"code":"CL","paidUpTo":"2099-12-31"},  
{"code":"PC","paidUpTo":"2099-12-31"}  
],  
"hash":"2911276/0",  
"gracePeriodDays":7,  
"autoProlongated":false}
```

- 得到以下界面便破解了Idea：
![](http://realliublog.oss-cn-hangzhou.aliyuncs.com/study/Idea%E7%A0%B4%E8%A7%A3/Idea_3.png "Activation code")
![](http://realliublog.oss-cn-hangzhou.aliyuncs.com/study/Idea%E7%A0%B4%E8%A7%A3/Idea_4.png "Idea2017.3")




