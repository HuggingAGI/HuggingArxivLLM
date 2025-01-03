# 自动图像标注：映射特征检测

发布时间：2024年12月11日

`其他

理由：这篇论文主要讨论的是道路特征检测和自动驾驶技术，特别是通过多模态自动标注方法来提升杆状物检测的精度。虽然涉及深度学习和数据标注，但核心内容与LLM（大型语言模型）、Agent（智能体）、RAG（检索增强生成）或LLM理论没有直接关联。因此，将其分类为“其他”更为合适。` `自动驾驶`

> Automatic Image Annotation for Mapped Features Detection

# 摘要

> 道路特征检测是自动驾驶和定位的核心技术。例如，精准识别道路环境中常见的杆状物能显著提升定位精度。现代深度学习感知系统依赖大量标注数据，而自动标注则能有效避免耗时且昂贵的手动标注。然而，自动方法易出错，因此管理标注不确定性对确保学习过程至关重要。融合多源标注数据是减少错误的有效策略，不仅能提升标注质量，还能优化感知模型的学习效果。本文探讨了三种自动标注方法的融合：基于高精度矢量地图与激光雷达的特征投影、图像分割及激光雷达分割。实验结果表明，多模态自动标注在杆状物检测中具有显著优势。最终，我们利用多模态融合技术，通过未标记数据微调目标检测模型，实现了杆状物基础检测的整体性能提升。该数据集已公开。

> Detecting road features is a key enabler for autonomous driving and localization. For instance, a reliable detection of poles which are widespread in road environments can improve localization. Modern deep learning-based perception systems need a significant amount of annotated data. Automatic annotation avoids time-consuming and costly manual annotation. Because automatic methods are prone to errors, managing annotation uncertainty is crucial to ensure a proper learning process. Fusing multiple annotation sources on the same dataset can be an efficient way to reduce the errors. This not only improves the quality of annotations, but also improves the learning of perception models. In this paper, we consider the fusion of three automatic annotation methods in images: feature projection from a high accuracy vector map combined with a lidar, image segmentation and lidar segmentation. Our experimental results demonstrate the significant benefits of multi-modal automatic annotation for pole detection through a comparative evaluation on manually annotated images. Finally, the resulting multi-modal fusion is used to fine-tune an object detection model for pole base detection using unlabeled data, showing overall improvements achieved by enhancing network specialization. The dataset is publicly available.

[Arxiv](https://arxiv.org/abs/2412.10438)