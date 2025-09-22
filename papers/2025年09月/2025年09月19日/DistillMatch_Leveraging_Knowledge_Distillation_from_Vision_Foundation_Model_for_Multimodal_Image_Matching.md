# DistillMatch：借助视觉基础模型的知识蒸馏实现多模态图像匹配

发布时间：2025年09月19日

`其他` `基础理论`

> DistillMatch: Leveraging Knowledge Distillation from Vision Foundation Model for Multimodal Image Matching

# 摘要

> 多模态图像匹配致力于寻找不同模态图像间的像素级对应关系，这对跨模态感知、融合与分析而言至关重要。但模态间巨大的外观差异给这项任务带来了不小挑战。由于高质量标注数据集稀缺，现有通过提取模态共有特征进行匹配的深度学习方法不仅表现欠佳，还缺乏对多样化场景的适应能力。而视觉基础模型（VFM）经大规模数据训练后，能生成兼具泛化性与鲁棒性的特征表示，可适配多种模态的数据与任务，多模态匹配也不例外。为此，我们提出DistillMatch——一种基于视觉基础模型知识蒸馏的多模态图像匹配方法。该方法通过知识蒸馏构建轻量级学生模型，从视觉基础模型（如DINOv2和DINOv3）中提取高层语义特征，进而辅助跨模态匹配。

> Multimodal image matching seeks pixel-level correspondences between images of different modalities, crucial for cross-modal perception, fusion and analysis. However, the significant appearance differences between modalities make this task challenging. Due to the scarcity of high-quality annotated datasets, existing deep learning methods that extract modality-common features for matching perform poorly and lack adaptability to diverse scenarios. Vision Foundation Model (VFM), trained on large-scale data, yields generalizable and robust feature representations adapted to data and tasks of various modalities, including multimodal matching. Thus, we propose DistillMatch, a multimodal image matching method using knowledge distillation from VFM. DistillMatch employs knowledge distillation to build a lightweight student model that extracts high-level semantic features from VFM (including DINOv2 and DINOv3) to assist matching across modalities. To retain modality-specific information, it extracts and injects modality category information into the other modality's features, which enhances the model's understanding of cross-modal correlations. Furthermore, we design V2I-GAN to boost the model's generalization by translating visible to pseudo-infrared images for data augmentation. Experiments show that DistillMatch outperforms existing algorithms on public datasets.

[Arxiv](https://arxiv.org/abs/2509.16017)