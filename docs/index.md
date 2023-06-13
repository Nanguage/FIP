# 使用 ImgFlow 进行荧光显微镜图像处理

本教程将介绍如何使用 ImgFlow 软件以及Python生态处理来自荧光显微镜成像得到的图像，
特别是针对FISH（荧光原位杂交）实验得到的图像进行处理，提取出有用的信息。
本教程大致包含三部分内容：

1. 对于荧光图像处理中涉及到的一些基本概念的介绍。
2. 如何使用 ImgFlow 进行图像处理的基本操作。
3. 如何使用 ImgFlow 完成对于 RNA FISH 图像的定量分析。


## 目录

- part 1
    - 图像处理基础
        - 图像的基本概念与表示
        - 其他常用数据结构
    - ImgFlow
        - 软件安装
        - 基本使用
        - 模块系统
    - 图像的加载、存储与可视化
        - 加载与存储
        - 可视化
- part 2
    - 图像的基本操作
        - 灰度统计以及矫正
        - 滤波器
        - 阈值与二值化
        - 特征提取
            - 特征点提取
            - 轮廓提取
        - 形态学操作
        - 连通域分析
        - 几何变换与图像配准
- part 3
    - RNA FISH 图像处理
        - 基本分析
            - 图像预处理
            - Spot detection
            - Cell segmentation
            - Decode
            - Gene to cell assignment
        - 下游分析
            - 基因共定位分析
            - 细胞类型注释
            - 细胞邻近关系分析


## 参考资料

+ [Introduction to Bioimage Analysis](https://bioimagebook.github.io/index.html)
+ [Scikit-image User Guide](https://scikit-image.org/docs/stable/user_guide/index.html)

