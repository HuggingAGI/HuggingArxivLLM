# SM3Det：多模态遥感目标检测的统一模型

发布时间：2024年12月29日

`其他` `对象检测`

> SM3Det: A Unified Model for Multi-Modal Remote Sensing Object Detection

# 摘要

> 随着遥感技术的迅猛进步，高分辨率多模态影像如今更易于获取。传统的对象检测模型仅在单个数据集上训练，往往受限于特定的成像方式和标注格式。然而，这种做法忽略了跨多模态的宝贵共享知识，限制了模型在更多元场景中的适用性。本文引入了一项名为遥感多模态数据集与多任务对象检测（M2Det）的新任务，旨在从任何传感器模态精确检测水平或定向对象。该任务面临挑战，原因在于：1）多模态建模中的权衡；2）多任务优化的复杂性。为应对这些挑战，我们构建了一个基准数据集，并提出了统一模型 SM3Det（用于多模态数据集和多任务对象检测的单一模型）。SM3Det 借助网格级稀疏 MoE 骨干实现联合知识学习，同时为不同模态保留独特的特征表示。此外，它通过动态调整学习率整合了一致性和同步优化策略，能够有效应对不同模态和任务的不同学习难度水平。大量实验表明，SM3Det 高效且通用，在各个数据集上的表现始终优于专门模型。代码可在 https://github.com/zcablii/SM3Det 获取。

> With the rapid advancement of remote sensing technology, high-resolution multi-modal imagery is now more widely accessible. Conventional Object detection models are trained on a single dataset, often restricted to a specific imaging modality and annotation format. However, such an approach overlooks the valuable shared knowledge across multi-modalities and limits the model's applicability in more versatile scenarios. This paper introduces a new task called Multi-Modal Datasets and Multi-Task Object Detection (M2Det) for remote sensing, designed to accurately detect horizontal or oriented objects from any sensor modality. This task poses challenges due to 1) the trade-offs involved in managing multi-modal modelling and 2) the complexities of multi-task optimization. To address these, we establish a benchmark dataset and propose a unified model, SM3Det (Single Model for Multi-Modal datasets and Multi-Task object Detection). SM3Det leverages a grid-level sparse MoE backbone to enable joint knowledge learning while preserving distinct feature representations for different modalities. Furthermore, it integrates a consistency and synchronization optimization strategy using dynamic learning rate adjustment, allowing it to effectively handle varying levels of learning difficulty across modalities and tasks. Extensive experiments demonstrate SM3Det's effectiveness and generalizability, consistently outperforming specialized models on individual datasets. The code is available at https://github.com/zcablii/SM3Det.

[Arxiv](https://arxiv.org/abs/2412.20665)