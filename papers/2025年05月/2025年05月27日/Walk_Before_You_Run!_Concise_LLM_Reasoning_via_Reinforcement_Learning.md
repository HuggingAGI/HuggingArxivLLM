# 先走稳再跑！通过强化学习实现 LLM 的简洁推理

发布时间：2025年05月27日

`LLM应用` `数学问题解决` `人工智能`

> Walk Before You Run! Concise LLM Reasoning via Reinforcement Learning

# 摘要

> 在大型语言模型（LLMs）开发中，测试时的扩展已成为关键研究前沿。现代且先进的后训练方法日益关注延长长链式思维（CoT）响应的生成长度，以提升推理能力，达到类似DeepSeek R1的性能。然而，近期研究表明，最先进的推理模型中存在持续的过度思考现象，表现为长CoT响应中的冗余过多或重复性思维模式。为了解决这一问题，本文提出了一种简单而有效的两阶段强化学习框架，旨在实现LLMs中的简洁推理，命名为ConciseR。第一阶段通过更多的训练步骤，采用带有clip-higher和动态采样组件的组相对策略优化（GRPO++）来激励模型的推理能力；第二阶段则通过更少的训练步骤，利用长度感知的组相对策略优化（L-GRPO）显式地强制简洁性并提高效率。值得注意的是，ConciseR遵循“先走稳再跑快”的原则，仅在样本的所有 rollout 都正确时才优化响应长度。实验结果表明，我们的ConciseR模型生成更简洁的CoT推理响应，在AIME 2024、MATH-500、AMC 2023、Minerva和奥林匹克基准测试中，超越了近期最先进的推理模型，且无需采用强化学习范式。

> As test-time scaling becomes a pivotal research frontier in Large Language Models (LLMs) development, contemporary and advanced post-training methodologies increasingly focus on extending the generation length of long Chain-of-Thought (CoT) responses to enhance reasoning capabilities toward DeepSeek R1-like performance. However, recent studies reveal a persistent overthinking phenomenon in state-of-the-art reasoning models, manifesting as excessive redundancy or repetitive thinking patterns in long CoT responses. To address this issue, in this paper, we propose a simple yet effective two-stage reinforcement learning framework for achieving concise reasoning in LLMs, named ConciseR. Specifically, the first stage, using more training steps, aims to incentivize the model's reasoning capabilities via Group Relative Policy Optimization with clip-higher and dynamic sampling components (GRPO++), and the second stage, using fewer training steps, explicitly enforces conciseness and improves efficiency via Length-aware Group Relative Policy Optimization (L-GRPO). Significantly, ConciseR only optimizes response length once all rollouts of a sample are correct, following the "walk before you run" principle. Extensive experimental results demonstrate that our ConciseR model, which generates more concise CoT reasoning responses, outperforms recent state-of-the-art reasoning models with zero RL paradigm across AIME 2024, MATH-500, AMC 2023, Minerva, and Olympiad benchmarks.

[Arxiv](https://arxiv.org/abs/2505.21178)