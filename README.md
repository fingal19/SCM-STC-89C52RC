# 高校联盟作品
## 题目

智能温控迷你电风扇

一、 概述

本次竞赛采用 ST89C52 单片机作为主控，参赛队应根据题目要求及参考电路原理图，设计并制作完成“智能温控迷你电风扇”作品，实现简单环境温度测试及显示，并根据温度自动调节风扇转速等功能。设计并完成如图 1 所示系统：

![](https://github.com/fingal19/SCM-STC-89C52RC/blob/master/pics/%E7%B3%BB%E7%BB%9F%E6%A1%86%E5%9B%BE.png)

二、 基本要求

1.系统工作电压为 5V；

2.实现数码管开机自检功能，全部一起或者间隔点亮所有数码管；

3.实现环境温度测试功能，温度精确到传感器精度，并实现数码管温度显示功能；

4.实现按键控制风扇速度功能，至少三级可调，不得使用滑动变阻器；

5.器件布局合理，作品外观美观，使用方便。

三、扩展要求

1.实现迷你风扇转速自动控制功能，电机转速能随环境温度变化而人性化变化；

2.风扇待机时，用嘴吹动叶片，实现风扇自动启动功能；

3.按键关闭数码管显示时，开启风扇自启功能，待机过程中实现功耗尽可能小；

其它自行扩展功能，如遥控、风扇转速可视化、改善的人体交互控制功能等，允许自行添加元器件，但与本系统关系不大的功能加分较少。

-----
作品图片

![url](https://github.com/fingal19/SCM-STC-89C52RC/blob/master/pics/%E9%AB%98%E6%A0%A1%E8%81%94%E7%9B%9F%E4%BD%9C%E5%93%81%E5%9B%BE1.jpg)

![url](https://github.com/fingal19/SCM-STC-89C52RC/blob/master/pics/%E9%AB%98%E6%A0%A1%E8%81%94%E7%9B%9F%E4%BD%9C%E5%93%81%E5%9B%BE2.jpg)

本次作品要求功能全部实现，并且新增定时和风扇转速显示功能，具体代码请在FanDemo.c文件中查看。

### Group

杨茜麟   文章   黄辉云
