# 点燃视觉语言模型（VLMs），进军具身空间

发布时间：2025年09月15日

`Agent` `工业与制造`

> Igniting VLMs toward the Embodied Space

# 摘要

> 尽管基础模型在语言与视觉领域已展现非凡进展，现有视觉语言模型（VLMs）对空间和具身认知的理解仍显不足。将其迁移至具身场景时，模态、预训练分布与训练目标间的根本性错位逐渐显现，动作理解与生成由此成为通用人工智能（AGI）发展的核心瓶颈。
  为此，我们提出WALL-OSS——一个端到端具身基础模型，通过大规模多模态预训练实现三大能力：（1）具身感知的视觉语言理解；（2）语言与动作的强关联；（3）稳健的操作技能。
  该模型采用紧密耦合的架构与多策略训练方案，构建出统一跨层级思维链（Unified Cross-Level CoT），能在单一可微分框架内无缝融合指令推理、子目标分解与细粒度动作合成。
  实验结果显示，WALL-OSS在复杂长程操作中成功率显著，不仅具备出色的指令遵循与复杂推理能力，还超越了现有强基线模型，为VLMs向具身基础模型的演进提供了可靠且可扩展的解决方案。

> While foundation models show remarkable progress in language and vision, existing vision-language models (VLMs) still have limited spatial and embodiment understanding. Transferring VLMs to embodied domains reveals fundamental mismatches between modalities, pretraining distributions, and training objectives, leaving action comprehension and generation as a central bottleneck on the path to AGI.
  We introduce WALL-OSS, an end-to-end embodied foundation model that leverages large-scale multimodal pretraining to achieve (1) embodiment-aware vision-language understanding, (2) strong language-action association, and (3) robust manipulation capability.
  Our approach employs a tightly coupled architecture and multi-strategies training curriculum that enables Unified Cross-Level CoT-seamlessly unifying instruction reasoning, subgoal decomposition, and fine-grained action synthesis within a single differentiable framework.
  Our results show that WALL-OSS attains high success on complex long-horizon manipulations, demonstrates strong instruction-following capabilities, complex understanding and reasoning, and outperforms strong baselines, thereby providing a reliable and scalable path from VLMs to embodied foundation models.

[Arxiv](https://arxiv.org/abs/2509.11766)