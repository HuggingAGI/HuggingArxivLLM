# # 3D点云基础模型：综述与展望

发布时间：2025年01月30日

`LLM应用

理由：这篇论文主要讨论了如何利用大型预训练语言模型（LLMs）来增强3D视觉理解，特别是在3D点云表示和3D视觉任务中的应用。虽然论文也涉及基础模型（FMs）在3D领域的应用，但其核心关注点是通过LLMs来提升3D理解能力，因此归类为LLM应用更为合适。` `3D视觉` `人工智能`

> Foundational Models for 3D Point Clouds: A Survey and Outlook

# 摘要

> 3D点云表示在保持物理世界几何保真度方面至关重要，使得复杂3D环境更加精确。尽管人类通过多感官系统自然理解物体间的复杂关系，但AI系统尚未完全复制这一能力。为弥合这一差距，整合多种模态变得不可或缺。能够无缝整合并跨模态推理的模型称为基础模型（FMs）。得益于大规模数据集的丰富性，2D模态（如图像和文本）的FMs开发进展显著。然而，由于标记数据稀缺和高计算开销，3D领域发展滞后。为此，近期研究开始探索将FMs应用于3D任务的潜力，通过利用现有2D知识克服挑战。此外，语言凭借其抽象推理和环境描述能力，为通过大型预训练语言模型（LLMs）增强3D理解提供了新途径。尽管近年来3D视觉任务的FMs发展迅速，但全面深入的文献综述仍显不足。本文旨在填补这一空白，全面概述利用FMs进行3D视觉理解的最先进方法。我们首先回顾了构建3D FMs的各种策略，然后分类总结了不同FMs在感知任务等中的应用。最后，本文展望了该领域未来的研究方向。为方便读者，我们整理了相关论文列表：https://github.com/vgthengane/Awesome-FMs-in-3D。

> The 3D point cloud representation plays a crucial role in preserving the geometric fidelity of the physical world, enabling more accurate complex 3D environments. While humans naturally comprehend the intricate relationships between objects and variations through a multisensory system, artificial intelligence (AI) systems have yet to fully replicate this capacity. To bridge this gap, it becomes essential to incorporate multiple modalities. Models that can seamlessly integrate and reason across these modalities are known as foundation models (FMs). The development of FMs for 2D modalities, such as images and text, has seen significant progress, driven by the abundant availability of large-scale datasets. However, the 3D domain has lagged due to the scarcity of labelled data and high computational overheads. In response, recent research has begun to explore the potential of applying FMs to 3D tasks, overcoming these challenges by leveraging existing 2D knowledge. Additionally, language, with its capacity for abstract reasoning and description of the environment, offers a promising avenue for enhancing 3D understanding through large pre-trained language models (LLMs). Despite the rapid development and adoption of FMs for 3D vision tasks in recent years, there remains a gap in comprehensive and in-depth literature reviews. This article aims to address this gap by presenting a comprehensive overview of the state-of-the-art methods that utilize FMs for 3D visual understanding. We start by reviewing various strategies employed in the building of various 3D FMs. Then we categorize and summarize use of different FMs for tasks such as perception tasks. Finally, the article offers insights into future directions for research and development in this field. To help reader, we have curated list of relevant papers on the topic: https://github.com/vgthengane/Awesome-FMs-in-3D.

[Arxiv](https://arxiv.org/abs/2501.18594)