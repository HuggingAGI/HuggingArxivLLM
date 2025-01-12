# LargeAD: 自动驾驶中的大规模跨传感器数据预训练

发布时间：2025年01月07日

`其他

理由：这篇论文主要讨论的是视觉基础模型（VFMs）在3D场景理解中的应用，特别是针对自动驾驶场景的多模态数据预训练框架。虽然涉及了多模态表示学习和对比学习策略，但这些内容与Agent、RAG、LLM应用或LLM理论没有直接关联。因此，将其分类为“其他”更为合适。` `自动驾驶` `3D视觉`

> LargeAD: Large-Scale Cross-Sensor Data Pretraining for Autonomous Driving

# 摘要

> # 摘要
视觉基础模型（VFMs）的最新进展彻底革新了2D视觉感知，但其在3D场景理解，尤其是自动驾驶应用中的潜力仍待挖掘。本文提出LargeAD，一个多功能且可扩展的框架，专为跨多种真实驾驶数据集的大规模3D预训练设计。该框架利用VFMs从2D图像中提取语义丰富的超像素，并与LiDAR点云对齐，生成高质量对比样本，促进跨模态表示学习，提升2D与3D数据的语义一致性。我们引入了多项关键创新：i）VFM驱动的超像素生成，用于精细语义表示；ii）VFM辅助的对比学习策略，对齐多模态特征；iii）超点时间一致性，确保跨时间稳定表示；iv）多源数据预训练，适应多种LiDAR配置。我们的方法在LiDAR分割与物体检测的线性探测和微调任务中，显著超越现有技术。在十一个大规模多模态数据集上的广泛实验验证了其卓越性能，展现了在实际自动驾驶场景中的适应性、高效性和鲁棒性。

> Recent advancements in vision foundation models (VFMs) have revolutionized visual perception in 2D, yet their potential for 3D scene understanding, particularly in autonomous driving applications, remains underexplored. In this paper, we introduce LargeAD, a versatile and scalable framework designed for large-scale 3D pretraining across diverse real-world driving datasets. Our framework leverages VFMs to extract semantically rich superpixels from 2D images, which are aligned with LiDAR point clouds to generate high-quality contrastive samples. This alignment facilitates cross-modal representation learning, enhancing the semantic consistency between 2D and 3D data. We introduce several key innovations: i) VFM-driven superpixel generation for detailed semantic representation, ii) a VFM-assisted contrastive learning strategy to align multimodal features, iii) superpoint temporal consistency to maintain stable representations across time, and iv) multi-source data pretraining to generalize across various LiDAR configurations. Our approach delivers significant performance improvements over state-of-the-art methods in both linear probing and fine-tuning tasks for both LiDAR-based segmentation and object detection. Extensive experiments on eleven large-scale multi-modal datasets highlight our superior performance, demonstrating the adaptability, efficiency, and robustness in real-world autonomous driving scenarios.

[Arxiv](https://arxiv.org/abs/2501.04005)