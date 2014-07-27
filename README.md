RaspberryPi_SmartHouse
======================

树莓派的守护程序，在系统开机后运行，每隔几秒检查一下标志文件的内容来达到控制电器的目的。

Deamon for Smart House in Raspberry Pi.Start after system ready.Check some symbol states every few seconds to control some appliances.

树莓派智能家居项目
==
---
项目说明
--
本项目由运行[Raspbian]（基于[Debian]）系统的[树莓派]（英文：Raspberry Pi）`B型 Rev2.0 UK 开发板`，运行其上的[PHP]和运行在[Android]的APP控制端组成。

**项目链接**

  - [Raspberry Pi系统上的C语言源代码][1]
  - [Android APP源代码][2]
  - [PHP源代码][3]

本文想法由`亓根火柴`发表在CSDN上的[《用树莓派通过Java实现远程控制电灯》][4]所启发，在此感谢原作者，以下是部分参考：

> 我们用[Yeelink]的手机客户端（浏览器也行）去改变服务上设备的状态（0/1），然后让树莓派检测该设备上的状态，最后根据获取到的状态控制继电器。


**启发**：我们可以用Android APP访问由树莓派搭建的PHP网页，对应的网页在树莓派系统中`创建或者修改`文件，`系统每隔几秒检测下文件的内容`，以此来达到模拟Yeelink的按钮操作，达到控制电器的目的。

##Project Explanation
This project is consist of `Raspberry Pi Rev2.0 UK Board` running [Raspbian] (based on Debian),php on it and using Android APP to control it.

**Project Link**

  - [C programming languages source code on Raspberry Pi][1]
  - [Android APP source code][2]
  - [PHP source code][3]

This article is inspired by the article [《用树莓派通过Java实现远程控制电灯》][4] posted on [CSDN Blog][5] by `亓根火柴`,thanks for the author,some referances are as follows:

> 我们用[Yeelink]的手机客户端（浏览器也行）去改变服务上设备的状态（0/1），然后让树莓派检测该设备上的状态，最后根据获取到的状态控制继电器。
(We use [Yeelink] mobile client (browser too) to change the status of the service equipment (0/1), and then let the raspberry pie detect the status of the device, according to the acquired control relay final state. --by google)

**Inspired ideas:**
We have access PHP webpages by using Android APP,these websites `create or modify` files on Raspberry Pi,`system detects these files every few seconds`,to simulate the button on Yeelink,in order to control appliances.

---

版本修订记录
--

**0.1 内部测试版本 [2014-07-27]**
  - 确定思路
  - 由受到启发的思路来`创建项目`
  - `创建说明文件`

**x.x 公开测试版本 [20xx-xx-xx]**

**x.x 候选版本 [20xx-xx-xx]**

**x.x 稳定版本 [20xx-xx-xx]**


##Revision
**0.1 Alpha [2014-07-27]**
  - Confirm Thought
  - `create project` from inspired ideas
  - `Create readme`

**x.x Beta [20xx-xx-xx]**

**x.x Release Candidate [20xx-xx-xx]**

**x.x Stable [20xx-xx-xx]**

[Raspbian]:http://raspbian.org/
[Debian]:http://debian.org
[树莓派]:http://www.raspberrypi.org/
[PHP]:http://php.net
[Android]:http://www.android.com/
[1]:https://github.com/angeiv/RaspberryPi_SmartHouse
[2]:https://github.com/angeiv/Android_SmartHouse
[3]:https://github.com/angeiv/PHP_SmartHouse
[Yeelink]:http://www.yeelink.net/
[4]:http://blog.csdn.net/qigenhuochai/article/details/17661845
[5]:http://blog.csdn.net
