# ANTS：基于MLLM的自适应负文本空间塑造用于OOD检测

发布时间：2025年09月04日

`LLM应用` `基础理论`

> ANTS: Shaping the Adaptive Negative Textual Space by MLLM for OOD Detection

# 摘要

> 引入负标签（NLs）已被证实能有效提升分布外（OOD）检测性能。然而，现有方法往往对OOD图像缺乏深入理解，导致难以构建准确的负空间。此外，假负标签的存在还会严重影响其近OOD检测效果。针对这些问题，我们提出借助多模态大型语言模型（MLLMs）的理解与推理能力，构建自适应负文本空间（ANTS）。具体做法是：先将疑似OOD样本的图像识别为负图像，再提示MLLM对这些图像进行描述，生成富有表现力的负句子——这些句子既能精准刻画OOD分布，又能提升远OOD检测效果。在近OOD场景中，OOD样本与分布内（ID）子集较为相似。对此，我们先识别出与负图像视觉相似的ID类子集，再利用MLLMs的推理能力生成针对该子集的定制化视觉相似负标签，进而有效减少假负样本，提升近OOD检测性能。为平衡这两种负文本空间，我们设计了自适应加权分数，让方法无需依赖特定任务的先验知识就能应对不同的OOD任务场景（近OOD和远OOD），因此在开放环境中具备很强的适应性。在ImageNet基准测试中，我们的ANTS将FPR95大幅降低4.2%，刷新了最先进水平。值得一提的是，该方法无需训练且支持零样本，因此具备很强的可扩展性。

> The introduction of negative labels (NLs) has proven effective in enhancing Out-of-Distribution (OOD) detection. However, existing methods often lack an understanding of OOD images, making it difficult to construct an accurate negative space. In addition, the presence of false negative labels significantly degrades their near-OOD performance. To address these issues, we propose shaping an Adaptive Negative Textual Space (ANTS) by leveraging the understanding and reasoning capabilities of multimodal large language models (MLLMs). Specifically, we identify images likely to be OOD samples as negative images and prompt the MLLM to describe these images, generating expressive negative sentences that precisely characterize the OOD distribution and enhance far-OOD detection. For the near-OOD setting, where OOD samples resemble the in-distribution (ID) subset, we first identify the subset of ID classes that are visually similar to negative images and then leverage the reasoning capability of MLLMs to generate visually similar negative labels tailored to this subset, effectively reducing false negatives and improving near-OOD detection. To balance these two types of negative textual spaces, we design an adaptive weighted score that enables the method to handle different OOD task settings (near-OOD and far-OOD) without relying on task-specific prior knowledge, making it highly adaptable in open environments. On the ImageNet benchmark, our ANTS significantly reduces the FPR95 by 4.2\%, establishing a new state-of-the-art. Furthermore, our method is training-free and zero-shot, enabling high scalability.

[Arxiv](https://arxiv.org/abs/2509.03951)