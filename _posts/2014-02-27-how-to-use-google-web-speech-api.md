---
ID: 99
post_title: >
  如何利用Google实现语音转录文本
post_name: how-to-use-google-web-speech-api
author: banpie
post_date: 2014-02-27 20:56:24
layout: post
link: >
  https://www.banpie.info/2014/02/27/how-to-use-google-web-speech-api/
published: true
tags: [ ]
categories:
  - 工具
---
@蘑菇：我想要安装用嘴巴念就可以生成文字的软件，这样我写废话文章的时候的时候就不用打字打到手酸…

@山中小石头：经常地铁上有时候需要回复一份紧急邮件，拿着手机打字输入好痛苦，用微信又只能查看语音的文本内容，有什么好的工具，能直接把说的话转成文字吗？

音频转文本的功能，现在许多公司都在做，国内的百度语音搜索、搜狗的语音输入、微信的对话转文本、科大讯飞的语音识别，国外有苹果的Siri、Nuance，还有Google。

今天讲的就是Google 的Web Speech API，虽然这款产品还是在内测的阶段，但是区别与微信、百度或者搜狗的其他同类产品，功能足够强大了：

*   支持超长时间的录音（目前测试好像没有时间限制

*   支持32种语言的录音转文

*   识别能力超强（除了一些品牌名称无法很好识别之外，日常对话零失误识别

*   支持一键复制粘贴和直接创建发送Email，这样以来，出门在外有急事要发邮件，对着手机麦克风说说就行了

## 1、手机访问Web Speech API

用手机Chrome浏览器访问：[http://t.cn/zjgwkHW](http://t.cn/zjgwkHW)。

![](http://mmbiz.qpic.cn/mmbiz/z3T1vlHdIX8v4NK1p6MkKZVOgtQKCgQAfb2HvOKeQNa0xaeElz5zwfoGb5SyXSibMjKmJqJjm9zyE5Cm6A4LNYg/0)

## 2、选择录音语言

点击输入框底部的「语言选择条」，在弹出的菜单中选择你的录音语言。

![](http://mmbiz.qpic.cn/mmbiz/z3T1vlHdIX8v4NK1p6MkKZVOgtQKCgQAQCGnTDrz6eT7nRzWqXofT9iaNSnBISWJR0JD1buAyAzKSmdddG3uj9A/0)

## 3、对着手机麦克风说话

点击输入框右侧的「麦克风」按钮，之后会在底部弹出黄色的「使用麦克风」确认对话框，点击确认后，对着麦克风说话即可。

![](http://mmbiz.qpic.cn/mmbiz/z3T1vlHdIX8v4NK1p6MkKZVOgtQKCgQAVhSDLSfbryL9kxYFNwp8remclicGricNGnrIgzBpgACgSfngEEY7PmicA/0)

## 4、复制文本或发送邮件

录音完毕后，再次点击输入框右侧的「麦克风」按钮，即可完成语音文本转录。此后，下方会出现两个按钮，点击「Copy and paste」后，在输入框中的文本即可进行复制，点击「Create Email」可直接创建一个带录音文本的邮件。

![](http://mmbiz.qpic.cn/mmbiz/z3T1vlHdIX8v4NK1p6MkKZVOgtQKCgQAe1mrmCPghAM5WWRP7SCTI6nPqpLCuQY7BJLIY9iaWTrwTVuCuZEuicFg/0)