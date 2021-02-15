# 《基于OpenCV和OpenMV数字图像处理实战指南》资源
## 引  言
-  作为一本OpenCV和OpenMV混编进阶书籍，本书基于Python语言，系统性串联了数字图像处理到识别再到基于图像处理的机器深度学习过程。涵盖了通用计算机（OpenCV相关）和单片机（OpenMV相关）的数字图像处理技术。属于数字图像处理技术的实际应用。附录含有笔者多年从事嵌入式开发参与的相关OpenCV和OpenMV非涉密项目实例。
-  本书分为“OpenCV上篇”和“OpenMV下篇”两个部分。OpenMV侧重于数字图像处理核心原理应用，主要应用于教学、科研和高端产品研发领域，更偏向于学术研究。OpenMV侧重于降低硬件资源占用，Python也被简化为MicroPython，主要应用于嵌入式开发和对处理器要求不高的领域，更偏向于技术应用。
-  本书适合有Python编程经验或嵌入式开发经验的读者阅读。
-  本书每一小节将阐述相关原理并附带Python实例程序，帮助读者将图像处理理论知识和实际应用联系起来，构建扎实的理论和开发基础。每一节相关技术，笔者会将其和自身经验以及思考融入其中，帮助读者在阅读完本书后对于嵌入式开发能有更为深刻的认识。
<p align="right">
凡尘 2020/07/18 于上海
</p>
##目  录
##OpenCV  上篇

第一章  安装OpenCV最新工程环境
1.1  在Windows上安装Visual Studio + OpenCV + Python
1.2  第一个OpenCV程序HelloWorld.py
1.3  CMake构建C++底层开发环境
1.4  OpenCV社区资源
1.5  本章小结
1.6  思考与练习

第二章  OpenCV基本操作
2.1  图片文件显示及读写操作
2.2  视频文件显示及读写操作
2.3  绘制基本图形
2.4  窗口滑动条
2.5  鼠标事件
2.6  Cameo-从面向过程转向面向对象
2.7  本章小结
2.8  思考与练习

第三章  使用Python对像素集合进行基本数学处理
3.1  向量和矩阵运算
3.2  像素集合逻辑操作
3.3  卡尔曼滤波
3.4  简单傅里叶变换
3.5  自定义内核卷积处理
3.6  思考与练习

第四章  使用Python对图像滤波处理
4.1  线性滤波
4.2  非线性滤波
4.2.1  中值滤波
4.2.2  双边滤波
4.3  形态学滤波
4.3.1  图像腐蚀和膨胀
4.3.2  图像开操作和闭操作
4.4  本章小结
4.5  思考与练习

第五章  使用Python对图像分割处理
5.1  图像阈值化处理
5.1.1  基本全局阈值处理
5.1.2  多阈值处理
5.1.3  可变阈值处理
5.1.4  多变阈值处理
5.2	图像边缘检测处理
5.2.1  简单二值化边缘处理
5.2.2  边缘检测算子检测
5.2.3  局部边缘连接
5.3  轮廓检测
5.4  分水岭和GrabCut算法进行图像分割
5.5  本章小结
5.6  思考与练习

第六章  图像几何变换处理
6.1  移动
6.1.1  平动
6.1.2  转动
6.2  仿射
6.3  透视
6.4  镜像
6.5  像素重映射
6.6  直方图均衡化
6.7  本章小结
6.8  思考与练习

第七章 使用Python对图像压缩处理
7.1  色彩空间转换
7.1.1  BGR转灰度
7.1.2  BGR转YUV
7.2  彩色图像压缩
7.2.1  行程编码压缩
7.2.2  哈夫曼编码压缩
7.2.3  算数编码压缩
7.2  常用压缩编码压缩
7.3.1  PNG转BMP格式
7.3.2  PNG转JPG格式
7.3.3  录屏保存为GIF格式
7.4  本章小结
7.5  思考与练习

第八章 图像识别
8.1	模板匹配
8.2	ORB特征检测
8.3 	Camshift目标跟踪
8.4	几何图形识别
8.4.1  Harris角点检测
8.4.2  霍夫线变换
8.4.3  霍夫圆变换
8.5	人脸检测与识别
8.5.1  静态图像中人脸检测
8.5.2  视频流中人脸检测
8.5.3  不同对象人脸识别
8.6	本章小结
8.7	思考与练习

第九章  基于OpenCV的简单神经网络和深度学习
9.1  人工神经网络
9.2  ANN算法的实现
9.3  基于ANN的手写数字识别
9.4  本章小结
9.5  思考与练习
