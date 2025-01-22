# 利用强化学习与推理扩展提升语言模型推理能力

发布时间：2025年01月20日

`LLM应用

理由：这篇论文主要讨论了如何通过强化学习（RL）和合成思维链数据来扩展大型语言模型（LLMs）的推理能力，并在数学推理基准上取得了卓越的表现。论文的核心是改进LLM在复杂推理任务中的应用，属于LLM在实际任务中的应用研究，因此应归类为LLM应用。` `人工智能` `数学推理`

> Advancing Language Model Reasoning through Reinforcement Learning and Inference Scaling

# 摘要

> 大型语言模型（LLMs）在复杂推理任务中表现出色，但现有方法主要依赖模仿学习，难以有效扩展测试时间。尽管强化学习（RL）有望实现自我探索和反馈学习，但近期尝试在复杂推理上仅取得有限进展。本文提出T1，通过鼓励探索和理解推理扩展来扩展RL。我们首先使用集成试错和自我验证的合成思维链数据初始化LLM，并通过过采样提升采样多样性。此外，我们采用熵奖励作为辅助损失，并配合动态锚点进行正则化，以优化奖励。实验表明，以开放LLMs为基础的T1展现出推理扩展行为，并在数学推理基准上表现卓越。例如，以Qwen2.5-32B为基础的T1在MATH500、AIME2024和Omni-math-500上优于Qwen QwQ-32B-Preview模型。更重要的是，我们提出了一种简单策略来检验推理扩展，增加推理预算可直接提升T1性能，无需额外验证。我们将在url{https://github.com/THUDM/T1}开源T1模型及其训练数据。

> Large language models (LLMs) have demonstrated remarkable capabilities in complex reasoning tasks. However, existing approaches mainly rely on imitation learning and struggle to achieve effective test-time scaling. While reinforcement learning (RL) holds promise for enabling self-exploration and learning from feedback, recent attempts yield only modest improvements in complex reasoning. In this paper, we present T1 to scale RL by encouraging exploration and understand inference scaling. We first initialize the LLM using synthesized chain-of-thought data that integrates trial-and-error and self-verification. To scale RL training, we promote increased sampling diversity through oversampling. We further employ an entropy bonus as an auxiliary loss, alongside a dynamic anchor for regularization to facilitate reward optimization. We demonstrate that T1 with open LLMs as its base exhibits inference scaling behavior and achieves superior performance on challenging math reasoning benchmarks. For example, T1 with Qwen2.5-32B as the base model outperforms the recent Qwen QwQ-32B-Preview model on MATH500, AIME2024, and Omni-math-500. More importantly, we present a simple strategy to examine inference scaling, where increased inference budgets directly lead to T1's better performance without any additional verification. We will open-source the T1 models and the data used to train them at url{https://github.com/THUDM/T1}.

[Arxiv](https://arxiv.org/abs/2501.11651)