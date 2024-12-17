# MVImgNet2.0：一个规模更大的多视图图像数据集

发布时间：2024年12月02日

`其他` `计算机视觉` `3D 重建`

> MVImgNet2.0: A Larger-scale Dataset of Multi-view Images

# 摘要

> 摘要：MVImgNet 是一个大规模数据集，涵盖 238 个类别中约 22 万个真实物体的多视图图像。作为 ImageNet 的对应，它借由多视图拍摄引入 3D 视觉信号，在 2D 与 3D 视觉间架起一座软性桥梁。本文构建了 MVImgNet2.0 数据集，将 MVImgNet 拓展至总计约 52 万个物体和 515 个类别，由此得出一个规模更大、与 2D 领域更具可比性的 3D 数据集。除了数据集规模和类别范围的扩展，MVImgNet2.0 还凭借四个新特性具备了比 MVImgNet 更高的质量：（i）多数拍摄能捕捉物体的 360 度视图，可支持完整的物体重建学习；（ii）分割方式先进，能生成更精准的前景物体掩码；（iii）采用更强大的运动结构方法，为每一帧导出估计误差更低的相机姿态；（iv）通过先进方法为 360 度视图中捕获的物体重建更高质量的密集点云，可服务于下游应用。大量实验证实了所提出的 MVImgNet2.0 在提升大型 3D 重建模型性能方面的价值。MVImgNet2.0 将在这个 http URL 公开，包括所有 52 万个物体的多视图图像、重建的高质量点云和数据注释代码，期望能激励更广泛的视觉领域。

> 
Abstract:MVImgNet is a large-scale dataset that contains multi-view images of ~220k real-world objects in 238 classes. As a counterpart of ImageNet, it introduces 3D visual signals via multi-view shooting, making a soft bridge between 2D and 3D vision. This paper constructs the MVImgNet2.0 dataset that expands MVImgNet into a total of ~520k objects and 515 categories, which derives a 3D dataset with a larger scale that is more comparable to ones in the 2D domain. In addition to the expanded dataset scale and category range, MVImgNet2.0 is of a higher quality than MVImgNet owing to four new features: (i) most shoots capture 360-degree views of the objects, which can support the learning of object reconstruction with completeness; (ii) the segmentation manner is advanced to produce foreground object masks of higher accuracy; (iii) a more powerful structure-from-motion method is adopted to derive the camera pose for each frame of a lower estimation error; (iv) higher-quality dense point clouds are reconstructed via advanced methods for objects captured in 360-degree views, which can serve for downstream applications. Extensive experiments confirm the value of the proposed MVImgNet2.0 in boosting the performance of large 3D reconstruction models. MVImgNet2.0 will be public at this http URL, including multi-view images of all 520k objects, the reconstructed high-quality point clouds, and data annotation codes, hoping to inspire the broader vision community.
    

[Arxiv](https://arxiv.org/pdf/2412.01430)