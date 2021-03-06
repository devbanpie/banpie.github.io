---
ID: 53
post_title: 如何实现定时关机
post_name: how-to-implement-timed-shutdown
author: banpie
post_date: 2014-02-13 17:32:42
layout: post
link: >
  https://www.banpie.info/2014/02/13/how-to-implement-timed-shutdown/
published: true
tags: [ ]
categories:
  - 工具
---
你是否经常在睡觉之前忘记关电脑，或者因为玩电脑而忘记了时间导致晚睡熬夜呢？本教程讲跟大家分享一个简单的定时关机的方法。

## 1、粘贴代码到记事本

打开记事本，将下面代码粘贴到记事本。

*   @echo of

*    :

*   if %time%==00:00:00.00 goto :

*   goto :

*    :

*   shutdown.exe /s /f /t 60 /c "Go to bed!!!!!!"

最后一行"Go to bed!!!!!!"可以改成你想要留的提醒信息。

## 2、设置关机时间

如下图所示，在 “if %time%== ”后面填上关机时间。注意时间填写按照HH:MM:SS(小时：分钟：秒)的格式，使用24时计时法。

[![How to Automatically Shut Down Your Computer at a Specified Time-01](http://7arnhx.com1.z0.glb.clouddn.com/wp-content/uploads/2014/02/How-to-Automatically-Shut-Down-Your-Computer-at-a-Specified-Time-01.jpg)](http://7arnhx.com1.z0.glb.clouddn.com/wp-content/uploads/2014/02/How-to-Automatically-Shut-Down-Your-Computer-at-a-Specified-Time-01.jpg)

## 3、存储

点击文件-保存，保存类型选择“所有文件”，文件名"timer.bat" 选好保存位置之后，点击保存。

[![How to Automatically Shut Down Your Computer at a Specified Time-02](http://7arnhx.com1.z0.glb.clouddn.com/wp-content/uploads/2014/02/How-to-Automatically-Shut-Down-Your-Computer-at-a-Specified-Time-02.jpg)](http://7arnhx.com1.z0.glb.clouddn.com/wp-content/uploads/2014/02/How-to-Automatically-Shut-Down-Your-Computer-at-a-Specified-Time-02.jpg)

## 4、运行timer文件

找到刚刚保存的timer文件，双击运行该文件，保持timer文件一直在运行。

[![How to Automatically Shut Down Your Computer at a Specified Time-03](http://7arnhx.com1.z0.glb.clouddn.com/wp-content/uploads/2014/02/How-to-Automatically-Shut-Down-Your-Computer-at-a-Specified-Time-03.jpg)](http://7arnhx.com1.z0.glb.clouddn.com/wp-content/uploads/2014/02/How-to-Automatically-Shut-Down-Your-Computer-at-a-Specified-Time-03.jpg)

等到关机时间到的时候，会弹出对话框，提醒要关机 了。

[![How to Automatically Shut Down Your Computer at a Specified Time-04](http://7arnhx.com1.z0.glb.clouddn.com/wp-content/uploads/2014/02/How-to-Automatically-Shut-Down-Your-Computer-at-a-Specified-Time-04.jpg)](http://7arnhx.com1.z0.glb.clouddn.com/wp-content/uploads/2014/02/How-to-Automatically-Shut-Down-Your-Computer-at-a-Specified-Time-04.jpg)

## 5、取消关机

在弹出关机对话框之后，系统会预留一分钟的时间然后关机，这个时候如果想取消关机可以按照下面操作。

在键盘上按win+R键，弹出运行对话框，在对话框中输入"shutdown-a"点击确定即可取消关机操作。

[![How to Automatically Shut Down Your Computer at a Specified Time-05](http://7arnhx.com1.z0.glb.clouddn.com/wp-content/uploads/2014/02/How-to-Automatically-Shut-Down-Your-Computer-at-a-Specified-Time-05.jpg)](http://7arnhx.com1.z0.glb.clouddn.com/wp-content/uploads/2014/02/How-to-Automatically-Shut-Down-Your-Computer-at-a-Specified-Time-05.jpg)