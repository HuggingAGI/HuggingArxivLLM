# Exo2Ego：基于外在知识驱动的多模态模型助力自我中心视频理解

发布时间：2025年03月12日

`Agent

理由：这篇论文专注于AI个人助手的具身理解能力，探讨如何通过改进多模态模型来提升自我中心视角的视频理解，属于AI代理的应用领域。` `机器人技术` `人工智能`

> Exo2Ego: Exocentric Knowledge Guided MLLM for Egocentric Video Understanding

# 摘要

> 通过机器人或可穿戴设备部署的AI个人助手需要具备具身理解能力，才能与人类有效协作。然而，当前的多模态大语言模型（MLLMs）主要关注第三人称（外在视角）视觉，忽视了第一人称（自我中心视角）视频的独特性。此外，高昂的数据获取成本限制了数据规模，进而影响了MLLM的表现。

为了解决这些问题，我们提出了一种创新的方法，通过学习外在视角与自我中心视角域之间的映射关系，利用现有MLLMs中丰富的外在视角知识，以显著提升自我中心视角视频的理解能力。为此，我们引入了Ego-ExoClip这一预训练数据集，它包含从Ego-Exo4D中提取的110万个同步的自我-外在视角视频-文本配对。

我们的方法采用了一个包含三个阶段的渐进式训练pipeline：教师自我准备、教师-学生指导和学生自我练习。此外，我们还提出了一个多来源的指令微调数据集EgoIT，以强化模型的指令遵循能力，并构建了包含八种不同任务的EgoBench基准测试，以进行全面评估。

在多样化的自我中心视角任务上的广泛实验表明，现有的MLLMs在自我中心视角视频理解上表现欠佳，而我们的模型显著优于这些领先的模型，展现出巨大的潜力和优势。

> AI personal assistants, deployed through robots or wearables, require embodied understanding to collaborate effectively with humans. Current Multimodal Large Language Models (MLLMs) primarily focus on third-person (exocentric) vision, overlooking the unique aspects of first-person (egocentric) videos. Additionally, high acquisition costs limit data size, impairing MLLM performance. To address these challenges, we propose learning the mapping between exocentric and egocentric domains, leveraging the extensive exocentric knowledge within existing MLLMs to enhance egocentric video understanding. To this end, we introduce Ego-ExoClip, a pre-training dataset comprising 1.1M synchronized ego-exo clip-text pairs derived from Ego-Exo4D. Our approach features a progressive training pipeline with three stages: Teacher Self-Preparation, Teacher-Student Guidance, and Student Self-Practice. Additionally, we propose an instruction-tuning data EgoIT from multiple sources to strengthen the model's instruction-following capabilities, along with the EgoBench benchmark comprising eight different tasks for thorough evaluation. Extensive experiments across diverse egocentric tasks reveal that existing MLLMs perform inadequately in egocentric video understanding, while our model significantly outperforms these leading models.

[Arxiv](https://arxiv.org/abs/2503.09143)