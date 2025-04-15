# PRM-BAS：通过 PRM 引导的束退火搜索增强多模态推理

发布时间：2025年04月14日

`LLM应用` `多模态` `人工智能`

> PRM-BAS: Enhancing Multimodal Reasoning through PRM-guided Beam Annealing Search

# 摘要

> 近年来，提升多模态大语言模型（MLLMs）推理能力的研究日益增多。在现有方法中，过程奖励模型（PRMs）因其提供密集的分步指导以优化中间推理过程而备受关注。然而，如何将PRMs有效融入搜索策略仍是一个待解难题。本文提出了一种轻量级的PRM引导推理方法——PRM-BAS（PRM引导的束退火搜索）。该方法通过动态调整束大小，从广域搜索空间开始，随着上下文信息的积累逐步聚焦，从而实现性能与效率的平衡。我们还构建了一个统一的数据构建和PRM训练框架。具体而言，我们从现有数据集中精选300k个问题，构建了PRM-BAS-300k数据集，并在每一步执行 rollout 以评估达到正确最终答案的概率。PRM模型通过结合绝对动作质量的价值损失和相对动作质量的排名损失进行训练。实验结果表明，在具有挑战性的多模态推理基准测试中，PRM-BAS不仅显著提升了推理性能，还保持了较低的计算成本。此外，该方法在不同模型规模和架构上表现优异，展现了强大的鲁棒性和即插即用能力。

> Recent work increasingly focuses on improving the reasoning capabilities of Multimodal Large Language Models (MLLMs). Among existing methods, Process Reward Models (PRMs) stand out for offering dense, step-wise supervision to guide intermediate reasoning. However, how to effectively integrate PRMs into search strategies remains an open question. In this paper, we introduce PRM-BAS (PRM-Guided Beam Annealing Search), a lightweight approach for PRM-guided reasoning that dynamically adjusts beam size -- starting with a broader search space and gradually narrowing it as contextual information accumulates, thereby balancing performance and efficiency. We further propose a unified framework for data construction and PRM training. Specifically, we construct the PRM-BAS-300k dataset by selecting 300k questions from existing datasets and performing rollouts at each step to estimate the probability of reaching a correct final answer. The PRM is then trained using a combination of value loss for absolute action quality and rank loss for relative action quality. Extensive experiments on challenging multimodal reasoning benchmarks demonstrate that PRM-BAS significantly improves reasoning performance while maintaining low computational cost. Moreover, it generalizes well across different model scales and architectures, showcasing strong robustness and plug-and-play capability.

[Arxiv](https://arxiv.org/abs/2504.10222)