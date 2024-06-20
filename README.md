[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/8oH8aWc3)



### 论文复现及改进

### 一种基于双重注意力网络的高动态范围图像重建及色调映射方法



### 前言

​	在高动态范围(High Dynamic Range，HDR)图像重建任务中，当输入图像过曝光或者欠曝光时，常见的基于深度学习的 HDR 图像重建方法容易出现细节信息丢失和色彩饱和度差的问题。为了解决这一问题，本文提出了一种基于双重注意力网络的 HDR 图像重建方法。首先，该方法利用双重注意力模块(Dual Attention Module，DAM)分别从像素和通道两个维度的注意力机制对过曝光和欠曝光的两张源图像进行特征提取并融合，得到一张初步融合图像。接着，在此基础上构建特征增强模块(Feature Enhancement Module，FEM)分别对初步融合图像进行细节增强和颜色校正。然后，将图像传入色调映射模块(Visual-Salience-Based Tone Mapping，VsbTM)，利用显著性感知加权和所提出的滤波器的HDR图像局部色调映射算法，改善注意显著区域的视觉质量。最后，引用对比学习使生成图像更加接近参考图像的同时远离源图像。经过多次训练，最终生成 HDR 图像。实验结果表明本文方法在 PSNR、SSIM和 LPIPS 指标上取得最优评价结果，生成的 HDR 图像色彩饱和度好且细节信息精准完整，且HDR 图像色调映射LDR图像无色晕伪影。



### 复现文档

​	方法在 PSNR、SSIM和 LPIPS 指标上取得最优评价结果，生成的 HDR 图像色彩饱和度好且细节信息精准完整，且HDR 图像色调映射LDR图像无色晕伪影。



### 复现演示地址



### 技术选型



### 数据集



### 成果展示



### 致谢

​	我们的复现文章受文章[《基于双重注意力网络的高动态范围图像重建》](https://kns.cnki.net/kcms2/article/abstract?v=f1ZyUc11mdp2Qm0cZuNbrjJiBOJ7oHoKX0mQCajH5KW61RJgv1UjTeS75D9cV5CYQRGjypth9MSb487U0hLVOBefSFJLv-TqOJ_DS2rBz-hTC6EI-d2Wf_O7zistXOA25XuJg81ef3Y=&uniplatform=NZKPT&language=CHS)和文章[《Visual-Salience-Based Tone Mapping for High Dynamic Range Images》](https://ieeexplore.ieee.org/abstract/document/6779648)启发，再次感谢。



