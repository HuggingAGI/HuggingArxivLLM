# # 强化学习优化大型语言模型中的稀疏子网络

发布时间：2025年07月22日

`LLM理论

摘要中探讨了强化学习在调整大型语言模型中的机制，特别是参数更新的稀疏性现象，属于模型理论层面的研究。`

> Reinforcement Learning Fine-Tunes a Sparse Subnetwork in Large Language Models

# 摘要

> 强化学习（RL）是调整大型语言模型（LLMs）以适应复杂任务和人类偏好的关键步骤。人们通常认为，RL微调需要更新模型的大部分参数，但我们的研究揭示了一个令人惊讶的现象：RL微调实际上只修改了一个小型子网络（通常占总权重的5-30%），而大部分参数保持不变。我们称这一现象为“强化学习诱导的参数更新稀疏性”。这一现象自然形成，无需任何稀疏性约束或参数高效微调，且普遍存在于多种RL算法（如PPO、DPO、SimPO、PRIME）和各类模型（如OpenAI、Meta和开源LLMs）中。更有趣的是，RL更新的子网络在不同种子、数据集和算法间呈现出显著的重叠，远超随机水平，这表明预训练模型中可能存在可部分转移的结构。我们发现，只需微调这一稀疏子网络，即可恢复整个模型的性能，其效果几乎与全面微调无异。通过分析，我们认为这种稀疏性源于RL在模型原始分布附近运行，仅需针对性的参数调整即可实现目标。KL惩罚、梯度裁剪和策略动态等因素对稀疏性模式的影响微乎其微。这些发现揭示了RL适应模型的独特机制：不是全面调整所有权重，而是聚焦于一个小型、持续更新的子网络。这一发现不仅为更高效的RL方法铺平了道路，还通过彩票假设的视角重新诠释了稀疏性的本质。


> Reinforcement learning (RL) is a key post-pretraining step for aligning large language models (LLMs) with complex tasks and human preferences. While it is often assumed that RL fine-tuning requires updating most of a model's parameters, we challenge this assumption with a surprising finding: RL fine-tuning consistently modifies only a small subnetwork (typically 5-30% of weights), leaving most parameters unchanged. We call this phenomenon RL-induced parameter update sparsity. It arises naturally, without any sparsity constraints or parameter-efficient tuning, and appears across multiple RL algorithms (e.g., PPO, DPO, SimPO, PRIME) and model families (e.g., OpenAI, Meta, and open-source LLMs). Moreover, the subnetworks updated by RL show substantial overlap across different seeds, datasets, and algorithms-far exceeding chance-suggesting a partially transferable structure in the pretrained model. We show that fine-tuning only this sparse subnetwork recovers full model performance and yields parameters nearly identical to the fully fine-tuned model. Our analysis suggests this sparsity emerges because RL operates near the model's original distribution, requiring only targeted changes. KL penalties, gradient clipping, and on-policy dynamics have limited effect on the sparsity pattern. These findings shed new light on how RL adapts models: not by shifting all weights, but by focusing training on a small, consistently updated subnetwork. This insight enables more efficient RL methods and reframes sparsity through the lens of the lottery ticket hypothesis.

[Arxiv](https://arxiv.org/abs/2507.17107)