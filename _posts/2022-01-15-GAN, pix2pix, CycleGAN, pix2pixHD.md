---
title: GAN, pix2pix, CycleGAN, pix2pixHD
author: 鹿其
date: 2022-01-15
category: [study, 大创]
layout: post
---
来自文章[一文读懂GAN, pix2pix, CycleGAN和pix2pixHD](https://blog.csdn.net/gdymind/article/details/82696481)  
# 1.GAN
[深度学习----GAN（生成对抗神经网络）原理解析](https://blog.csdn.net/Sakura55/article/details/81512600)  

G为**Generator**，它的作用是生成图片，也就是说，在输入一个**随机编码(random code)** z之后，它将输出一幅由神经网络自动生成的、假的图片G(z)。

#### 学习目标：
[![7Glek4.png](https://s4.ax1x.com/2022/01/15/7Glek4.png)](https://imgtu.com/i/7Glek4)
#### 看不懂了：
[![7GJsYD.png](https://s4.ax1x.com/2022/01/15/7GJsYD.png)](https://imgtu.com/i/7GJsYD)
#### paper:
[Generative Adversarial Nets.pdf
](https://arxiv.org/pdf/1406.2661.pdf?)
#### 大神整理的 **The GAN Zoo**:
[github:The GAN Zoo](https://github.com/hindupuravinash/the-gan-zoo)
#### [github:GAN](https://github.com/goodfeli/adversarial)

# 2.pix2pix
> 我们把**G的输入和输出一起作为D的输入**不就好了？
#### 学习目标
![](https://img-blog.csdn.net/20180914044620941?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2dkeW1pbmQ=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)
#### 体验
[![7Gjhzq.png](https://s4.ax1x.com/2022/01/15/7Gjhzq.png)](https://imgtu.com/i/7Gjhzq)
[![7GjXWR.png](https://s4.ax1x.com/2022/01/15/7GjXWR.png)](https://imgtu.com/i/7GjXWR)
哈哈哈哈哈哈可能真是我画的太抽象了第二个看起来好像兔子
#### paper：
[Image-to-Image Translation with Conditional Adversarial Networks.pdf](https://openaccess.thecvf.com/content_cvpr_2017/papers/Isola_Image-To-Image_Translation_With_CVPR_2017_paper.pdf)
#### [github:pix2pix](https://github.com/phillipi/pix2pix)
#### 介绍页
<https://phillipi.github.io/pix2pix/>
