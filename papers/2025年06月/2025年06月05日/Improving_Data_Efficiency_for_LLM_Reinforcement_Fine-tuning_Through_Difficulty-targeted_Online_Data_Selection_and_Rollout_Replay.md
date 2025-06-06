# 提升大语言模型强化微调的数据效率：基于难度导向的在线数据选择与回放重播

发布时间：2025年06月05日

`LLM应用` `人工智能`

> Improving Data Efficiency for LLM Reinforcement Fine-tuning Through Difficulty-targeted Online Data Selection and Rollout Replay

# 摘要

> 强化学习（RL）已成为微调大型语言模型（LLMs）的有力手段，尤其在提升其推理能力方面表现突出。然而，RL 微调仍然需要大量资源，现有研究大多忽视了数据效率问题。本文提出两种方法来提升 LLM RL 微调的数据效率：基于难度的目标在线数据选择和回放重演机制。我们引入自适应难度的概念来指导在线数据选择，优先选择难度适中的问题，因为这类问题更有可能提供有用的训练信号。为了高效估算自适应难度，我们开发了一个基于注意力的框架，只需针对少量参考问题集进行回放。其余问题的自适应难度则根据其与该参考集的相似性进行估计。为了进一步降低回放成本，我们引入了回放重演机制，重复利用近期回放结果，从而在保持更新稳定的同时降低了每步计算量。在 6 种 LLM-数据集组合上的大量实验表明，与原版 GRPO 算法相比，我们的方法在达到相同性能水平时，可将 RL 微调时间减少 25% 至 65%。

> Reinforcement learning (RL) has become an effective approach for fine-tuning large language models (LLMs), particularly to enhance their reasoning capabilities. However, RL fine-tuning remains highly resource-intensive, and existing work has largely overlooked the problem of data efficiency. In this paper, we propose two techniques to improve data efficiency in LLM RL fine-tuning: difficulty-targeted online data selection and rollout replay. We introduce the notion of adaptive difficulty to guide online data selection, prioritizing questions of moderate difficulty that are more likely to yield informative learning signals. To estimate adaptive difficulty efficiently, we develop an attention-based framework that requires rollouts for only a small reference set of questions. The adaptive difficulty of the remaining questions is then estimated based on their similarity to this set. To further reduce rollout cost, we introduce a rollout replay mechanism that reuses recent rollouts, lowering per-step computation while maintaining stable updates. Extensive experiments across 6 LLM-dataset combinations show that our method reduces RL fine-tuning time by 25% to 65% to reach the same level of performance as the original GRPO algorithm.

[Arxiv](https://arxiv.org/abs/2506.05316)