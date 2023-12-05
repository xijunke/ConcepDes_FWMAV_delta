# Conceptual-design-and-application-of-insect-bioinspired-FWMAV 

# 软件概况

本软件为扑翼微飞行器的概念设计软件，应用于扑翼微飞行器样机研制领域。

# 软件运行环境

## 硬件要求：
   最低配置：处理器Intel(R) Core(TM) i3-2100、内存1G、硬盘5G；
   推荐配置：处理器Intel(R) Core(TM) i5及以上系列、内存2GM、硬盘 50G.
   操作系统：Microsoft Windows 7 Version 6.1 (Build 7601: Service Pack 1)
   Java VM Version: Java 1.6.0_17-b04 with Sun Microsystems Inc. Java HotSpot(TM) Client VM mixed mode.
   编译环境：Microsoft Visual C++2005 Redistributable (x86) and MCRinstaller.

# 编程语言版本及源程序量

   本软件采用MATLAB Version 7.13.0.564 (R2011b)的Matlab语言编写并最终封装开发，框架体系如下：
   (1) 主函数(ConcepDes_FMAV_delta)有 73行程序代码;
   (2) 模块一有 281行程序代码;
   (3) 模块二有 396行程序代码;
   (4) 模块三有146行程序代码;
   (5) 模块四有133行程序代码;
   整套软件源程序代码共计1029行。

# 软件特点

   基于任务需求，本软件是针对扑翼微飞行器(FMAV)的样机研制处于概念设计阶段而开发的。根据FMAV巡航时间、速度、航程以及负载等要求，本软件能够高效快速地完成如下参数的计算：
   ①	FMAV的驱动器质量百分比计算；最大飞行时间对应的翅膀长度计算；
   ②	给定飞行时间、负载质量百分比、FMAV总质量和翅膀结构惯性因子以及额外负载后，计算可行翅膀长度；
   ③	已知FMAV的关键组件设计参数以及前进比后，计算巡航速度和航程。



![ConcepDes_FMAV_delta](https://github.com/xijunke/wing_shape_of_fruit_fly/blob/master/pic_png_tif_eps_pdf/coordination_xy_4.png)

![ConcepDes_FMAV_delta](https://github.com/xijunke/wing_shape_of_fruit_fly/blob/master/pic_png_tif_eps_pdf/coordination_xy_4.png)

![ConcepDes_FMAV_delta](https://github.com/xijunke/wing_shape_of_fruit_fly/blob/master/pic_png_tif_eps_pdf/coordination_xy_4.png)

