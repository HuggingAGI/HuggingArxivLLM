# 通过细粒度视觉与语义互动实现全切片图像分类的泛化能力

发布时间：2024年02月29日

`LLM应用`

> Generalizable Whole Slide Image Classification with Fine-Grained Visual-Semantic Interaction

# 摘要

> WSI分类常被视为MIL问题，而VLMs在这一领域崭露头角，表现出优异性能。不过现有技术仅依赖粗糙的病理性描述指导视觉特征学习，难以充分揭示病理性图像复杂多变的视觉特征，导致模型在各类下游任务上的泛化能力受限。同时，处理高分辨率WSI颇具计算挑战。为此，我们创新性地提出了FiVE框架，它聚焦于WSI分类中的“细粒度视觉-语义交互”，通过巧妙设计的查询方式，运用大型语言模型从各式非标准原始报告中提炼出精细的病理描述，并将其转化为训练所需的细粒度标签。借助TFS模块，我们引导模型精准捕捉WSI中的关键视觉信息，有效提升了表示学习效果及模型泛化能力。考虑到病理视觉模式在组织切片间存在冗余分布，我们在训练阶段只选取部分视觉实例进行处理。最终，本方法展现出极强的泛化性和优越的迁移性，在针对TCGA肺癌数据集的少量样本实验中，其准确率至少比其他方法高出9.19%，实现了显著超越。

> Whole Slide Image (WSI) classification is often formulated as a Multiple Instance Learning (MIL) problem. Recently, Vision-Language Models (VLMs) have demonstrated remarkable performance in WSI classification. However, existing methods leverage coarse-grained pathogenetic descriptions for visual representation supervision, which are insufficient to capture the complex visual appearance of pathogenetic images, hindering the generalizability of models on diverse downstream tasks. Additionally, processing high-resolution WSIs can be computationally expensive. In this paper, we propose a novel "Fine-grained Visual-Semantic Interaction" (FiVE) framework for WSI classification. It is designed to enhance the model's generalizability by leveraging the interplay between localized visual patterns and fine-grained pathological semantics. Specifically, with meticulously designed queries, we start by utilizing a large language model to extract fine-grained pathological descriptions from various non-standardized raw reports. The output descriptions are then reconstructed into fine-grained labels used for training. By introducing a Task-specific Fine-grained Semantics (TFS) module, we enable prompts to capture crucial visual information in WSIs, which enhances representation learning and augments generalization capabilities significantly. Furthermore, given that pathological visual patterns are redundantly distributed across tissue slices, we sample a subset of visual instances during training. Our method demonstrates robust generalizability and strong transferability, dominantly outperforming the counterparts on the TCGA Lung Cancer dataset with at least 9.19% higher accuracy in few-shot experiments.

[Arxiv](https://arxiv.org/abs/2402.19326)