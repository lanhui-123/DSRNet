# DSRNet

This is the official code of "DSRNet: Depth Super-Resolution Network Guided by Blurry Depth and Clear Intensity Edges", 
the Preprint submitted to Signal Processing: Image Communication

DSRNet is a color guided depth super-resolution method, this is a part of code and result images. 
After the paper is officially released, we will provide more results and code.

# Description

images: test results on Middlebury dataset with different sampling factor (x2, x4, x8, x16).

SRNet_2: test code of sampling factor x2

SRNet_4: test code of sampling factor x4

SRNet_8: test code of sampling factor x8

SRNet_16: test code of sampling factor x16


![github](https://user-images.githubusercontent.com/55533905/222022366-14e3ac86-c1b3-4be9-9070-f8e0d8140f44.png)

In this figure, (a) is the HR color image, (b) is the interpolated HR depth map by bicubic, and (c) is the SR depth map by DSRNet

# Dependencies

pytorch 1.8.0
