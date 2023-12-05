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

![ConcepDes_FMAV_delta](https://github.com/xijunke/ConcepDes_FMAV_delta/blob/master/pic_GUI/main_GUI.bmp)

![ConcepDes_FMAV_delta](https://github.com/xijunke/ConcepDes_FMAV_delta/blob/master/pic_GUI/%E8%BD%AF%E4%BB%B6%E7%95%8C%E9%9D%A2-ConcepDes_FMAV_delta.bmp)

# BMP format pictures to display th software GUI of ConcepDes_FMAV

![ConcepDes_FMAV_delta](https://github.com/xijunke/ConcepDes_FMAV_delta/blob/master/pic_GUI/m1-1.bmp)

![ConcepDes_FMAV_delta](https://github.com/xijunke/ConcepDes_FMAV_delta/blob/master/pic_GUI/m1-2.jpg)

![ConcepDes_FMAV_delta](https://github.com/xijunke/ConcepDes_FMAV_delta/blob/master/pic_GUI/m1-3.jpg)

![ConcepDes_FMAV_delta](https://github.com/xijunke/ConcepDes_FMAV_delta/blob/master/pic_GUI/m1-4.bmp)

![ConcepDes_FMAV_delta](https://github.com/xijunke/ConcepDes_FMAV_delta/blob/master/pic_GUI/m2-1.bmp)

![ConcepDes_FMAV_delta](https://github.com/xijunke/ConcepDes_FMAV_delta/blob/master/pic_GUI/m2-2.bmp)

![ConcepDes_FMAV_delta](https://github.com/xijunke/ConcepDes_FMAV_delta/blob/master/pic_GUI/m2-3.bmp)

![ConcepDes_FMAV_delta](https://github.com/xijunke/ConcepDes_FMAV_delta/blob/master/pic_GUI/m3-1.bmp)

![ConcepDes_FMAV_delta](https://github.com/xijunke/ConcepDes_FMAV_delta/blob/master/pic_GUI/m4-1.bmp)

![ConcepDes_FMAV_delta](https://github.com/xijunke/ConcepDes_FMAV_delta/blob/master/pic_GUI/ConcepDes_FMAV_delta_0.bmp)

![ConcepDes_FMAV_delta](https://github.com/xijunke/ConcepDes_FMAV_delta/blob/master/pic_GUI/ConcepDes_FMAV_delta_1.bmp)

# PNG format pictures with error characters:

![ConcepDes_FMAV_delta](https://github.com/xijunke/ConcepDes_FMAV_delta/blob/master/pic_png_tif_pdf_eps_bmp/png/%E8%A7%84%E5%AE%9A%E7%9A%84%E8%B0%90%E6%B3%A2%E6%8B%8D%E6%89%93%E8%A7%92%E5%92%8C%E6%89%AD%E8%BD%AC%E8%A7%92_%E5%9C%A8%E4%B8%8D%E5%90%8C%E7%9A%84%E6%94%BB%E8%A7%92alpha_0%E4%B8%8B%E7%9A%84%E9%98%BB%E5%B0%BC%E5%8A%9B%E9%9A%8F%E6%97%A0%E9%87%8F%E7%BA%B2%E6%97%B6%E9%97%B4%E7%9A%84%E5%8F%98%E5%8C%96.png)

![ConcepDes_FMAV_delta](https://github.com/xijunke/ConcepDes_FMAV_delta/blob/master/pic_png_tif_pdf_eps_bmp/png/%E8%A7%84%E5%AE%9A%E7%9A%84%E8%B0%90%E6%B3%A2%E6%8B%8D%E6%89%93%E8%A7%92%E5%92%8C%E6%89%AD%E8%BD%AC%E8%A7%92_%E5%9C%A8%E4%B8%8D%E5%90%8C%E7%9A%84%E6%94%BB%E8%A7%92alpha_0%E4%B8%8B%E7%9A%84%E9%98%BB%E5%B0%BC%E5%8A%9B%E9%9A%8F%E6%97%A0%E9%87%8F%E7%BA%B2%E6%97%B6%E9%97%B4%E7%9A%84%E5%8F%98%E5%8C%962.png)

![ConcepDes_FMAV_delta](https://github.com/xijunke/ConcepDes_FMAV_delta/blob/master/pic_png_tif_pdf_eps_bmp/png/%E5%8E%8B%E7%94%B5%E9%A9%B1%E5%8A%A8%E5%99%A8%E7%9A%84%E8%B4%A8%E9%87%8F%E7%99%BE%E5%88%86%E6%AF%94vs%E7%BF%85%E8%86%80%E9%95%BF%E5%BA%A6.png)

![ConcepDes_FMAV_delta](https://github.com/xijunke/ConcepDes_FMAV_delta/blob/master/pic_png_tif_pdf_eps_bmp/png/%E5%B7%B2%E7%9F%A5%E6%89%91%E7%BF%BC%E5%BE%AE%E9%A3%9E%E8%A1%8C%E5%99%A8%E8%B4%A8%E9%87%8F_%E9%A3%9E%E8%A1%8C%E6%97%B6%E9%95%BF%E5%8F%96%E5%86%B3%E4%BA%8E%E7%BF%85%E8%86%80%E9%95%BF%E5%BA%A6%E7%9A%84%E4%BA%8C%E6%AC%A1%E6%96%B9.png)

![ConcepDes_FMAV_delta](https://github.com/xijunke/ConcepDes_FMAV_delta/blob/master/pic_png_tif_pdf_eps_bmp/png/%E6%9C%80%E5%B0%8F%E7%BF%85%E8%86%80%E9%95%BF%E5%BA%A6%E4%B8%8EFMAV%E8%B4%A8%E9%87%8F(%E5%8F%A6%E5%A4%96%E9%99%84%E5%8A%A00_1kg%E8%B4%9F%E8%BD%BD)%E7%9A%84%E5%85%B3%E7%B3%BB.png)

![ConcepDes_FMAV_delta](https://github.com/xijunke/ConcepDes_FMAV_delta/blob/master/pic_png_tif_pdf_eps_bmp/png/%E6%9C%80%E5%B0%8F%E7%BF%85%E8%86%80%E9%95%BF%E5%BA%A6%E4%B8%8EFMAV%E8%B4%A8%E9%87%8F%E7%9A%84%E5%85%B3%E7%B3%BB.png)

![ConcepDes_FMAV_delta](https://github.com/xijunke/ConcepDes_FMAV_delta/blob/master/pic_png_tif_pdf_eps_bmp/png/%E7%BF%85%E8%86%80%E6%83%AF%E6%80%A7%E7%BB%93%E6%9E%84%E6%9E%81%E9%99%90%E4%B8%8B%E7%A1%AE%E5%AE%9A%E7%9A%84%E6%9C%80%E5%B0%8F%E7%BF%85%E8%86%80%E9%95%BF%E5%BA%A6%E4%B8%8EFMAV%E8%B4%A8%E9%87%8F%E7%9A%84%E5%85%B3%E7%B3%BB.png)

![ConcepDes_FMAV_delta](https://github.com/xijunke/ConcepDes_FMAV_delta/blob/master/pic_png_tif_pdf_eps_bmp/png/%E7%BF%85%E8%86%80%E6%83%AF%E6%80%A7%E7%BB%93%E6%9E%84%E6%9E%81%E9%99%90%E4%B8%8B%E7%A1%AE%E5%AE%9A%E7%9A%84%E6%9C%80%E5%B0%8F%E7%BF%85%E8%86%80%E9%95%BF%E5%BA%A6%E4%B8%8EFMAV%E8%B4%A8%E9%87%8F%E7%9A%84%E5%85%B3%E7%B3%BB_2.png)

![ConcepDes_FMAV_delta](https://github.com/xijunke/ConcepDes_FMAV_delta/blob/master/pic_png_tif_pdf_eps_bmp/png/%E7%BF%85%E8%86%80%E6%83%AF%E6%80%A7%E7%BB%93%E6%9E%84%E6%9E%81%E9%99%90%E4%B8%8B%E7%A1%AE%E5%AE%9A%E7%9A%84%E6%9C%80%E5%B0%8F%E7%BF%85%E8%86%80%E9%95%BF%E5%BA%A6%E4%B8%8EFMAV%E8%B4%A8%E9%87%8F(%E5%8F%A6%E5%A4%96%E9%99%84%E5%8A%A00_1kg%E8%B4%9F%E8%BD%BD)%E7%9A%84%E5%85%B3%E7%B3%BB_2.png)

![ConcepDes_FMAV_delta](https://github.com/xijunke/ConcepDes_FMAV_delta/blob/master/pic_png_tif_pdf_eps_bmp/png/%E7%BF%85%E8%86%80%E6%83%AF%E6%80%A7%E7%BB%93%E6%9E%84%E6%9E%81%E9%99%90%E4%B8%8B%E7%A1%AE%E5%AE%9A%E7%9A%84%E6%9C%80%E5%B0%8F%E7%BF%85%E8%86%80%E9%95%BF%E5%BA%A6%E4%B8%8EFMAV%E8%B4%A8%E9%87%8F(%E5%8F%A6%E5%A4%96%E9%99%84%E5%8A%A0100mg%E8%B4%9F%E8%BD%BD)%E7%9A%84%E5%85%B3%E7%B3%BB.png)






