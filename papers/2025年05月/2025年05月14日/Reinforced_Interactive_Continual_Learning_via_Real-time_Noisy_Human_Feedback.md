# 基于实时噪声人类反馈的强化交互式持续学习

发布时间：2025年05月14日

`LLM应用` `AI模型` `持续学习`

> Reinforced Interactive Continual Learning via Real-time Noisy Human Feedback

# 摘要

> 本文提出了一种交互式持续学习范式，让AI模型在保留已有知识的同时，能够从实时的人类反馈中动态学习新技能。这一范式巧妙地解决了传统持续学习的两大难题：(1) 采用流式、实时的人类标注数据进行动态模型更新，摆脱了对静态数据集和固定标签的依赖；(2) 通过显式处理现实交互中常见的噪声反馈，突破了对干净标签的假设限制。为应对这些挑战，我们推出了RiCL框架，一种结合大型语言模型（LLMs）从动态反馈中高效学习新技能的强化交互式持续学习方法。RiCL的核心由三大模块组成：时间一致性感知的净化器，能够自动识别数据流中的干净与噪声样本；交互感知的直接偏好优化策略，通过协调AI生成的反馈与人类提供的反馈，确保模型行为与人类意图高度一致；以及抗噪声对比学习模块，通过挖掘数据内在关系，捕获鲁棒表示，从而避免对潜在不可靠标签的依赖。在FewRel 和 TACRED 两个基准数据集上进行的广泛实验中，这些数据集被注入了现实噪声模式，结果表明，我们的RiCL方法在性能上显著优于现有结合先进在线持续学习与噪声标签学习方法的组合。

> This paper introduces an interactive continual learning paradigm where AI models dynamically learn new skills from real-time human feedback while retaining prior knowledge. This paradigm distinctively addresses two major limitations of traditional continual learning: (1) dynamic model updates using streaming, real-time human-annotated data, rather than static datasets with fixed labels, and (2) the assumption of clean labels, by explicitly handling the noisy feedback common in real-world interactions. To tackle these problems, we propose RiCL, a Reinforced interactive Continual Learning framework leveraging Large Language Models (LLMs) to learn new skills effectively from dynamic feedback. RiCL incorporates three key components: a temporal consistency-aware purifier to automatically discern clean from noisy samples in data streams; an interaction-aware direct preference optimization strategy to align model behavior with human intent by reconciling AI-generated and human-provided feedback; and a noise-resistant contrastive learning module that captures robust representations by exploiting inherent data relationships, thus avoiding reliance on potentially unreliable labels. Extensive experiments on two benchmark datasets (FewRel and TACRED), contaminated with realistic noise patterns, demonstrate that our RiCL approach substantially outperforms existing combinations of state-of-the-art online continual learning and noisy-label learning methods.

[Arxiv](https://arxiv.org/abs/2505.09925)