# SRPO：大型语言模型上大规模跨域强化学习的实现方案

发布时间：2025年04月22日

`LLM理论`

> SRPO: A Cross-Domain Implementation of Large-Scale Reinforcement Learning on LLM

# 摘要

> 以 OpenAI 的 o1 和 DeepSeek 的 R1 为代表的推理模型近期取得了显著进展，凸显了强化学习 (RL) 在提升大型语言模型 (LLMs) 推理能力方面的巨大潜力。然而，由于方法透明度有限，将这些进展复制到不同领域仍具挑战性。在此研究中，我们提出了两阶段历史重采样策略优化 (SRPO)，其在 AIME24 和 LiveCodeBench 基准测试中的表现超越了 DeepSeek-R1-Zero-32B。SRPO 采用与 DeepSeek 相同的基线模型（即 Qwen2.5-32B），仅需 DeepSeek-R1-Zero-32B 约 1/10 的训练步骤，展现出卓越的效率。基于组相对策略优化 (GRPO)，我们引入了两项关键创新：（1）一种两阶段跨领域训练范式，旨在平衡数学推理与编程能力的发展；（2）历史重采样 (HR) 技术，用于解决低效样本问题。我们的全面实验验证了该方法的有效性，为跨任务扩展 LLM 推理能力提供了宝贵的见解。

> Recent advances of reasoning models, exemplified by OpenAI's o1 and DeepSeek's R1, highlight the significant potential of Reinforcement Learning (RL) to enhance the reasoning capabilities of Large Language Models (LLMs). However, replicating these advancements across diverse domains remains challenging due to limited methodological transparency. In this work, we present two-Staged history-Resampling Policy Optimization (SRPO), which surpasses the performance of DeepSeek-R1-Zero-32B on the AIME24 and LiveCodeBench benchmarks. SRPO achieves this using the same base model as DeepSeek (i.e. Qwen2.5-32B), using only about 1/10 of the training steps required by DeepSeek-R1-Zero-32B, demonstrating superior efficiency. Building upon Group Relative Policy Optimization (GRPO), we introduce two key methodological innovations: (1) a two-stage cross-domain training paradigm designed to balance the development of mathematical reasoning and coding proficiency, and (2) History Resampling (HR), a technique to address ineffective samples. Our comprehensive experiments validate the effectiveness of our approach, offering valuable insights into scaling LLM reasoning capabilities across diverse tasks.

[Arxiv](https://arxiv.org/abs/2504.14286)