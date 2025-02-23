# FLAG-Trader：结合LLM智能体与基于梯度强化学习的金融交易框架

发布时间：2025年02月18日

`LLM应用`

> FLAG-Trader: Fusion LLM-Agent with Gradient-based Reinforcement Learning for Financial Trading

# 摘要

> 大型语言模型（LLMs）在多模态金融数据上的微调展现出了卓越的推理能力，但在涉及交易等交互式金融市场的复杂场景中仍面临挑战。为解决这一问题，我们提出了	extsc{FLAG-Trader}，一个将语言处理与强化学习相结合的统一架构。该架构中，部分微调的LLM作为策略网络，在保持预训练知识的同时，通过参数高效的微调适应金融领域。通过交易奖励驱动的策略优化，我们的框架不仅提升了LLM在交易中的表现，同时也显著改善了其他金融任务的结果。大量实证研究表明了这一提升的有效性。

> Large language models (LLMs) fine-tuned on multimodal financial data have demonstrated impressive reasoning capabilities in various financial tasks. However, they often struggle with multi-step, goal-oriented scenarios in interactive financial markets, such as trading, where complex agentic approaches are required to improve decision-making. To address this, we propose \textsc{FLAG-Trader}, a unified architecture integrating linguistic processing (via LLMs) with gradient-driven reinforcement learning (RL) policy optimization, in which a partially fine-tuned LLM acts as the policy network, leveraging pre-trained knowledge while adapting to the financial domain through parameter-efficient fine-tuning. Through policy gradient optimization driven by trading rewards, our framework not only enhances LLM performance in trading but also improves results on other financial-domain tasks. We present extensive empirical evidence to validate these enhancements.

[Arxiv](https://arxiv.org/abs/2502.11433)