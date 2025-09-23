# MO R-CNN：面向遥感图像目标检测的多光谱定向R-CNN

发布时间：2025年09月21日

`其他` `交通运输`

> MO R-CNN: Multispectral Oriented R-CNN for Object Detection in Remote Sensing Image

# 摘要

> 多光谱图像的定向目标检测因模态内及模态间的差异而面临严峻挑战。尽管现有方法借助复杂网络架构提升了检测精度，但高昂的计算复杂度和内存消耗严重制约了其性能。受大核卷积在遥感领域应用成功的启发，我们提出了MO R-CNN——一个面向多光谱定向检测的轻量级框架，该框架融合了异质特征提取网络（HFEN）、单模态监督（SMS）和基于条件的多模态标签融合（CMLF）三大核心模块。HFEN模块借助模态间差异，自适应地对齐、融合并增强多模态特征；SMS通过约束多尺度特征，让模型得以从多模态数据中学习；CMLF则依据特定规则融合多模态标签，为模型提供更鲁棒且一致的监督信号。在DroneVehicle、VEDAI和OGSOD数据集上的实验结果验证了我们方法的优越性。源代码已开源，地址为：https://github.com/Iwill-github/MORCNN。

> Oriented object detection for multi-spectral imagery faces significant challenges due to differences both within and between modalities. Although existing methods have improved detection accuracy through complex network architectures, their high computational complexity and memory consumption severely restrict their performance. Motivated by the success of large kernel convolutions in remote sensing, we propose MO R-CNN, a lightweight framework for multi-spectral oriented detection featuring heterogeneous feature extraction network (HFEN), single modality supervision (SMS), and condition-based multimodal label fusion (CMLF). HFEN leverages inter-modal differences to adaptively align, merge, and enhance multi-modal features. SMS constrains multi-scale features and enables the model to learn from multiple modalities. CMLF fuses multimodal labels based on specific rules, providing the model with a more robust and consistent supervisory signal. Experiments on the DroneVehicle, VEDAI and OGSOD datasets prove the superiority of our method. The source code is available at:https://github.com/Iwill-github/MORCNN.

[Arxiv](https://arxiv.org/abs/2509.16957)