# MindFlow+：一个自我进化的电子商务客服智能体。

发布时间：2025年07月24日

`LLM应用

理由：这篇论文主要探讨了如何将大型语言模型（LLMs）应用于电商客服对话系统中，通过结合模仿学习和离线强化学习，构建领域特定的行为模型。论文提出的方法和实验结果展示了LLMs在实际对话场景中的应用潜力，因此归类为LLM应用。`

> MindFlow+: A Self-Evolving Agent for E-Commerce Customer Service

# 摘要

> 高质量对话在电商客服中不可或缺，但传统基于意图的系统难以应对动态多轮对话。为此，我们推出MindFlow+，它通过结合大型语言模型（LLMs）与模仿学习和离线强化学习（RL），实现领域特定行为的自我演进。MindFlow+创新性地引入了两个数据驱动机制：工具增强的演示构建，让模型接触知识增强和智能体（ReAct风格）交互，从而实现有效工具使用；以及基于奖励的数据建模，利用奖励信号确保响应与任务目标高度对齐。为了量化AI在对话中的贡献，我们引入了AI贡献比率这一全新指标。在真实电商对话场景中，MindFlow+在上下文相关性、灵活性和任务准确性等方面均超越现有强基线模型。这些结果充分证明了将LLMs工具推理能力与奖励引导学习相结合，能够打造领域专用、上下文感知的对话系统的巨大潜力。

> High-quality dialogue is crucial for e-commerce customer service, yet traditional intent-based systems struggle with dynamic, multi-turn interactions. We present MindFlow+, a self-evolving dialogue agent that learns domain-specific behavior by combining large language models (LLMs) with imitation learning and offline reinforcement learning (RL). MindFlow+ introduces two data-centric mechanisms to guide learning: tool-augmented demonstration construction, which exposes the model to knowledge-enhanced and agentic (ReAct-style) interactions for effective tool use; and reward-conditioned data modeling, which aligns responses with task-specific goals using reward signals. To evaluate the model's role in response generation, we introduce the AI Contribution Ratio, a novel metric quantifying AI involvement in dialogue. Experiments on real-world e-commerce conversations show that MindFlow+ outperforms strong baselines in contextual relevance, flexibility, and task accuracy. These results demonstrate the potential of combining LLMs tool reasoning, and reward-guided learning to build domain-specialized, context-aware dialogue systems.

[Arxiv](https://arxiv.org/abs/2507.18884)