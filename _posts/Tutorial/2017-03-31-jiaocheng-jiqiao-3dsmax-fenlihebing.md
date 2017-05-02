---
layout: post
title:  "【技巧-3DSMAX】3DSMAX如何快速分离已合并物体"
date:   2017-01-31
desc: "在3DSmax中如何快速的分离已合并物体"
keywords: "3DSMAX，合并，分离"
categories: [Tutorial]
tags: [3DSMAX,技巧，优化修改器]
icon: icon-html
---
在使  用3DSMAX的过程中，有时候需要下载模型使用，有些模型已经被作者附加成一个整体，而我们需要拆开使用，对于简单的几何体来说通过在不同的视图选择多边形进行分离，但是对于复杂的，有套嵌关系的物体来说，进行选择很复杂困难。比如这个齿轮，准备把钢珠分离出来，并没有元素层级，利用多边形框选很麻烦，而且和容易丢失一些小的面。  
![技巧3DS-chilun.png](http://upload-images.jianshu.io/upload_images/1853536-db2d8bcb5509ef54.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
### 使用【修改器-优化】命令，实现快速选择  
给想要处理的物体  
- 1.添加优化命令  
- 2.勾选选择自动边，同时勾选保留：材质边界 平滑边界   
- 3.塌陷模型   
此时模型已经可以方便的选取分离了。分离为元素或者对象，随你喜欢了。  
![技巧3DS-chilun2.png](http://upload-images.jianshu.io/upload_images/1853536-7b3c4cc344b7345f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![技巧3DS--chilun3.png](http://upload-images.jianshu.io/upload_images/1853536-022d07e0d9094c84.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![技巧3DS--chilun4.png](http://upload-images.jianshu.io/upload_images/1853536-44dfd829f44372f2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)  

### 使用经验分享
1 优化命令的另一个使用场景  
当需要渲染产品的线框图时，用这个命令优化线条，然后添加VR-边纹理命令，可以渲染完美线框图了。  
***
### 关于写作
个人很愿意分享学习的过程、思考的结果，碎片知识时代想就知识整理贡献一份力量，具体的思路在[用模块化的思路进行写作，赋予知识以生命]()中有详细的阐述，感兴趣的朋友可以看一下。  
一人经验，一己思考，若有疏漏欢迎交流指正，期待你关于以上问题的补充。  
欢迎添加微信公众号“meng-yongji”,或者点击并扫描[二维码](http://upload-images.jianshu.io/upload_images/1853536-6216bde114999da9.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)。
### 关于版权
因为本文采用的特殊[写作方法]()，为了更好的传播作者思路：
- 本文采用[CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/deed.zh)授权。
