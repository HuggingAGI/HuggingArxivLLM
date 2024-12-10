# Chimera：借助特定领域专家提升通才模型

发布时间：2024年12月08日

`LLM应用` `多模态` `特定领域`

> Chimera: Improving Generalist Model with Domain-Specific Experts

# 摘要

> 近期大型多模态模型（LMMs）的进展凸显了通过增加图像-文本配对数据来扩展规模的重要性，在一般任务上表现出色。尽管通才模型在广泛应用中成效显著，但主要在以自然图像为主的网络规模数据集中训练，致使在需要大量领域先验知识的特定领域任务中专业能力不足。而且，由于通才模型与专家之间存在表示差异和优化不平衡，直接整合特定领域的专家模型颇具难度。为应对这些挑战，我们推出了奇美拉（Chimera），这是一种可扩展且成本低的多模态管道，旨在借助特定领域专家提升现有 LMMs 的能力。具体来说，我们设计了一种渐进式训练策略，将专家模型的特征融入通才 LMM 的输入。为解决由良好对齐的通用视觉编码器导致的优化不平衡问题，我们引入了新颖的通才-专家协作掩蔽（GSCM）机制。由此产生了一个在图表、表格、数学和文档等领域均表现卓越的多功能模型，在多模态推理和视觉内容提取任务上达到了先进水平，这两项任务对于评估现有 LMMs 颇具挑战性。

> Recent advancements in Large Multi-modal Models (LMMs) underscore the importance of scaling by increasing image-text paired data, achieving impressive performance on general tasks. Despite their effectiveness in broad applications, generalist models are primarily trained on web-scale datasets dominated by natural images, resulting in the sacrifice of specialized capabilities for domain-specific tasks that require extensive domain prior knowledge. Moreover, directly integrating expert models tailored for specific domains is challenging due to the representational gap and imbalanced optimization between the generalist model and experts. To address these challenges, we introduce Chimera, a scalable and low-cost multi-modal pipeline designed to boost the ability of existing LMMs with domain-specific experts. Specifically, we design a progressive training strategy to integrate features from expert models into the input of a generalist LMM. To address the imbalanced optimization caused by the well-aligned general visual encoder, we introduce a novel Generalist-Specialist Collaboration Masking (GSCM) mechanism. This results in a versatile model that excels across the chart, table, math, and document domains, achieving state-of-the-art performance on multi-modal reasoning and visual content extraction tasks, both of which are challenging tasks for assessing existing LMMs.

[Arxiv](https://arxiv.org/abs/2412.05983)