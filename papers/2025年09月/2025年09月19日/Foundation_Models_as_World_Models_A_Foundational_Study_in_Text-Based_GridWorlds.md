# 基础模型作为世界模型：基于文本网格世界的基础研究

发布时间：2025年09月19日

`Agent` `基础理论`

> Foundation Models as World Models: A Foundational Study in Text-Based GridWorlds

# 摘要

> 尽管从零开始的强化学习借助高效模拟器在解决序列决策任务上成效显著，但现实世界中交互成本高昂的应用场景亟需更样本高效的智能体。基础模型（FMs）凭借丰富的知识储备与推理能力，本是提升样本效率的理想之选，然而如何将其有效融入强化学习框架仍是未解难题。为此，本文提出并重点评估了两种颇具潜力的策略：其一，构建基础世界模型（FWMs）——借助FMs的先验知识，实现智能体的模拟交互训练与评估；其二，设计基础智能体（FAs）——直接利用FMs的推理能力进行决策。我们在一系列适配当前大型语言模型（LLMs）的网格世界环境中，对两种方法展开了实证研究。研究结果显示：LLMs的性能提升已直接带来FWMs与FAs的优化；基于现有LLMs的FAs在简单环境中已能生成优异策略；FWMs与强化学习智能体的耦合则在含部分可观测性和随机因素的复杂场景中展现出巨大潜力。

> While reinforcement learning from scratch has shown impressive results in solving sequential decision-making tasks with efficient simulators, real-world applications with expensive interactions require more sample-efficient agents. Foundation models (FMs) are natural candidates to improve sample efficiency as they possess broad knowledge and reasoning capabilities, but it is yet unclear how to effectively integrate them into the reinforcement learning framework. In this paper, we anticipate and, most importantly, evaluate two promising strategies. First, we consider the use of foundation world models (FWMs) that exploit the prior knowledge of FMs to enable training and evaluating agents with simulated interactions. Second, we consider the use of foundation agents (FAs) that exploit the reasoning capabilities of FMs for decision-making. We evaluate both approaches empirically in a family of grid-world environments that are suitable for the current generation of large language models (LLMs). Our results suggest that improvements in LLMs already translate into better FWMs and FAs; that FAs based on current LLMs can already provide excellent policies for sufficiently simple environments; and that the coupling of FWMs and reinforcement learning agents is highly promising for more complex settings with partial observability and stochastic elements.

[Arxiv](https://arxiv.org/abs/2509.15915)