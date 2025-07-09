# All in One: 视觉描述引导的统一点云分割方案

发布时间：2025年07月07日

`LLM应用` `3D分割` `场景理解`

> All in One: Visual-Description-Guided Unified Point Cloud Segmentation

# 摘要

> 3D点云分割是场景理解的关键，但面临着稀疏结构、标注不足以及复杂环境下细粒度类别区分的多重挑战。现有方法受限于监督信号的不足和多模态提示的多样性缺失，难以有效捕捉语义和上下文信息，导致分类与实例分割效果欠佳。为解决这些问题，我们提出了VDG-Uni3DSeg框架，创新性地整合了预训练视觉-语言模型（如CLIP）与大型语言模型（LLMs），以提升3D分割能力。通过利用LLM生成的文本描述和网络图像，我们的方法引入了丰富的多模态提示，显著改善了细粒度的类别与实例区分能力。我们还设计了语义-视觉对比损失，优化了点特征与多模态查询的对齐，并开发了空间增强模块，有效建模全局场景关系。在基于离线生成多模态知识的封闭集范式下，VDG-Uni3DSeg在语义、实例和全景分割任务上均达到了当前最优水平，为3D理解提供了一种高效实用的解决方案。我们的代码已开源，地址为https://github.com/Hanzy1996/VDG-Uni3DSeg。

> Unified segmentation of 3D point clouds is crucial for scene understanding, but is hindered by its sparse structure, limited annotations, and the challenge of distinguishing fine-grained object classes in complex environments. Existing methods often struggle to capture rich semantic and contextual information due to limited supervision and a lack of diverse multimodal cues, leading to suboptimal differentiation of classes and instances. To address these challenges, we propose VDG-Uni3DSeg, a novel framework that integrates pre-trained vision-language models (e.g., CLIP) and large language models (LLMs) to enhance 3D segmentation. By leveraging LLM-generated textual descriptions and reference images from the internet, our method incorporates rich multimodal cues, facilitating fine-grained class and instance separation. We further design a Semantic-Visual Contrastive Loss to align point features with multimodal queries and a Spatial Enhanced Module to model scene-wide relationships efficiently. Operating within a closed-set paradigm that utilizes multimodal knowledge generated offline, VDG-Uni3DSeg achieves state-of-the-art results in semantic, instance, and panoptic segmentation, offering a scalable and practical solution for 3D understanding. Our code is available at https://github.com/Hanzy1996/VDG-Uni3DSeg.

[Arxiv](https://arxiv.org/abs/2507.05211)