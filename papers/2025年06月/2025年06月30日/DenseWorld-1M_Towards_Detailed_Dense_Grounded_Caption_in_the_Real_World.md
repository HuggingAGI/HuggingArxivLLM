# DenseWorld-1M：探索现实世界中更详细、更密集的接地描述

发布时间：2025年06月30日

`LLM应用` `视觉理解` `数据集构建`

> DenseWorld-1M: Towards Detailed Dense Grounded Caption in the Real World

# 摘要

> 多模态大型语言模型（MLLMs）凭借大规模高质量数据集的支持，展现了对场景的复杂理解能力。然而，现有图像描述数据集普遍缺乏视觉实体的场景位置和关系信息，且部分基于场景的图像描述数据集在高分辨率图像上还存在描述细节缺失、关系信息不全等问题。为了解决这些痛点，我们推出了DenseWorld-1M——首个大规模、详细、密集场景描述数据集。我们设计了一个包含开放世界感知、详细物体描述生成和密集描述融合三个阶段的标注流水线。第一阶段获取实体级别的掩膜和标签；第二阶段利用第一阶段的掩膜和标签生成物体级别的详细描述；最终阶段将物体描述和掩膜融合成空间和关系的密集描述。为了加速标注流程并提升描述质量，我们开发了详细区域描述模型和空间描述融合模型两款视觉语言模型。在视觉语言理解、视觉定位和区域描述生成等多种实验设置下，DenseWorld-1M数据集和标注模型均表现出显著的有效性。

> Multimodal Large Language Models (MLLMs) demonstrate a complex understanding of scenes, benefiting from large-scale and high-quality datasets. Most existing caption datasets lack the ground locations and relations for visual entities. Several grounded caption datasets face the problems of missing detailed descriptions, relations, and massive object descriptions on high-resolution images. To fill this gap for the community, we present DenseWorld-1M, the first massive, detailed, dense grounded caption dataset in the real world. We design a three-stage labeling pipeline, containing open-world perception, detailed object caption generation, and dense caption merging. The first stage obtains entity-level masks and labels. The second stage generates the object-level, detailed captions with the guidance of masks and labels from the first stage. The final stage merges object captions and masks into spatial and relational dense captions. To accelerate the labeling process and improve caption quality, we present two VLM models: the Detailed Region Caption model and the Spatial Caption Merging model. Extensive experiments on various settings, including vision-language understanding, visual grounding, and region caption generation, demonstrate the effectiveness of our DenseWorld-1M dataset and labeling models.

[Arxiv](https://arxiv.org/abs/2506.24102)