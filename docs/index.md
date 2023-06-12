# 荧光显微镜图像处理

本教程将介绍如何使用 Python 以及 ImgFlow 软件处理来自荧光显微镜成像得到的图像，
特别是针对FISH（荧光原位杂交）实验得到的图像进行处理，提取出有用的信息。
本教程包含对于荧光图像处理中涉及到的一些基本数据结构的介绍，
以及针对这些数据结构的一些基本操作，如读取、存储、运算、可视化等。

## 目录

- 图像处理基础
    - 图像的基本概念与表示
    - 其他常用数据结构
- ImgFlow
    - 软件安装
    - 基本使用
    - 模块系统
- 图像的加载与存储与可视化
    - 图像格式
    - 加载与存储
    - 可视化
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

