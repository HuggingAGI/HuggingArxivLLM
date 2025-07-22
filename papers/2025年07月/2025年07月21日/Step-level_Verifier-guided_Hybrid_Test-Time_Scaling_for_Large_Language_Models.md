# 基于分层验证器的混合型测试时间缩放方法在大型语言模型中的应用

发布时间：2025年07月21日

`LLM应用` `人工智能` `模型推理`

> Step-level Verifier-guided Hybrid Test-Time Scaling for Large Language Models

# 摘要

> 测试时缩放（TTS）是一种在推理过程中逐步激发模型智能的充满潜力的方法。近期，基于训练的TTS方法如持续强化学习（RL） popularity 大增，而训练-free的TTS方法则逐渐淡出。然而，训练带来的额外计算开销加重了测试时缩放的负担。本文聚焦于训练-free的TTS方法在推理中的应用。我们设计了条件步级自我优化，这是一种由过程验证引导的细粒度序列缩放方法。除了其有效性，我们进一步在步级将其与其他经典的并行缩放方法相结合，从而引入了一种名为混合测试时缩放的新推理范式。在不同规模（3B-14B）和家族的五个指令微调大型语言模型上进行的广泛实验表明，采用多种训练-free的TTS方法在细粒度层面的混合策略，对于扩展大型语言模型的推理性能边界具有相当大的潜力。

> Test-Time Scaling (TTS) is a promising approach to progressively elicit the model's intelligence during inference. Recently, training-based TTS methods, such as continued reinforcement learning (RL), have further surged in popularity, while training-free TTS methods are gradually fading from prominence. However, the additional computation overhead of training amplifies the burden on test-time scaling. In this paper, we focus on training-free TTS methods for reasoning. We first design Conditional Step-level Self-refinement, a fine-grained sequential scaling method guided by process verification. On top of its effectiveness, we further combine it with other classical parallel scaling methods at the step level, to introduce a novel inference paradigm called Hybrid Test-Time Scaling. Extensive experiments on five instruction-tuned LLMs across different scales (3B-14B) and families demonstrate that hybrid strategy incorporating various training-free TTS methods at a fine granularity has considerable potential for expanding the reasoning performance boundaries of LLMs.

[Arxiv](https://arxiv.org/abs/2507.15512)