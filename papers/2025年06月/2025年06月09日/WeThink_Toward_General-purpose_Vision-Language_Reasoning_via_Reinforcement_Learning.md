# WeThink：迈向通用视觉语言推理的强化学习方法

发布时间：2025年06月09日

`LLM应用` `多模态` `视觉-语言`

> WeThink: Toward General-purpose Vision-Language Reasoning via Reinforcement Learning

# 摘要

> 在DeepSeek-R1等基于文本的推理模型成功的基础上，将其能力扩展到多模态推理领域具有巨大潜力。尽管近期研究尝试将DeepSeek-R1风格的强化学习（RL）训练范式应用于多模态大型语言模型（MLLM），并专注于数学和视觉感知等特定领域任务，但如何通过强化学习实现通用的视觉-语言推理能力仍然是一个关键问题。为了解决这一挑战，我们进行了三项关键努力：

1. 开发了一种新型的可扩展多模态问答合成管道，能够从给定的图像中自主生成具有上下文感知且以推理为中心的问题-答案（QA）对。
2. 构建了开源的WeThink数据集，包含超过12万个多模态问答对，这些问答对带有标注的推理路径，从18个多样化的数据源中整理而来，涵盖各种问题领域。
3. 在我们的数据集上对强化学习进行了全面探索，采用结合基于规则的验证与基于模型的评估的混合奖励机制，以优化跨不同任务领域的强化学习训练效率。

在14个多样化的MLLM基准测试中，我们的WeThink数据集显著提升了模型性能，从数学推理到各种通用多模态任务均表现出色。此外，我们的自动化数据管道能够持续增加数据多样性，从而进一步提升模型性能。

> Building on the success of text-based reasoning models like DeepSeek-R1, extending these capabilities to multimodal reasoning holds great promise. While recent works have attempted to adapt DeepSeek-R1-style reinforcement learning (RL) training paradigms to multimodal large language models (MLLM), focusing on domain-specific tasks like math and visual perception, a critical question remains: How can we achieve the general-purpose visual-language reasoning through RL? To address this challenge, we make three key efforts: (1) A novel Scalable Multimodal QA Synthesis pipeline that autonomously generates context-aware, reasoning-centric question-answer (QA) pairs directly from the given images. (2) The open-source WeThink dataset containing over 120K multimodal QA pairs with annotated reasoning paths, curated from 18 diverse dataset sources and covering various question domains. (3) A comprehensive exploration of RL on our dataset, incorporating a hybrid reward mechanism that combines rule-based verification with model-based assessment to optimize RL training efficiency across various task domains. Across 14 diverse MLLM benchmarks, we demonstrate that our WeThink dataset significantly enhances performance, from mathematical reasoning to diverse general multimodal tasks. Moreover, we show that our automated data pipeline can continuously increase data diversity to further improve model performance.

[Arxiv](https://arxiv.org/abs/2506.07905)