# ML-Agent：强化LLM代理，助力自主机器学习工程

发布时间：2025年05月29日

`Agent` `机器学习`

> ML-Agent: Reinforcing LLM Agents for Autonomous Machine Learning Engineering

# 摘要

> 大型语言模型（LLM）智能体的出现显著推动了自主机器学习（ML）工程的发展。然而，现有方法大多严重依赖手动提示工程，未能根据多样化的实验经验进行适应与优化。针对这一问题，我们首次探索了基于学习的智能体机器学习范式，其中LLM智能体通过在线强化学习（RL）在机器学习任务上进行交互式实验学习。为此，我们提出了一种新型的智能体ML训练框架，包含三个关键组件：(1) 增强探索的微调，使LLM智能体能够生成多样化动作，从而提升RL探索效果；(2) 分步式RL，支持在单个动作步骤上进行训练，加速经验收集并提高训练效率；(3) 专门针对智能体ML的任务奖励模块，将多样化的ML反馈信号统一为一致的奖励信号用于RL优化。借助这一框架，我们训练出了ML-Agent，它由一个70亿参数的Qwen-2.5 LLM驱动，实现了自主机器学习。值得注意的是，尽管仅在9个ML任务上进行训练，我们的70亿参数ML-Agent在性能上超越了拥有6710亿参数的DeepSeek-R1智能体。此外，它还实现了持续性能提升，并展现了卓越的任务间泛化能力。

> The emergence of large language model (LLM)-based agents has significantly advanced the development of autonomous machine learning (ML) engineering. However, most existing approaches rely heavily on manual prompt engineering, failing to adapt and optimize based on diverse experimental experiences. Focusing on this, for the first time, we explore the paradigm of learning-based agentic ML, where an LLM agent learns through interactive experimentation on ML tasks using online reinforcement learning (RL). To realize this, we propose a novel agentic ML training framework with three key components: (1) exploration-enriched fine-tuning, which enables LLM agents to generate diverse actions for enhanced RL exploration; (2) step-wise RL, which enables training on a single action step, accelerating experience collection and improving training efficiency; (3) an agentic ML-specific reward module, which unifies varied ML feedback signals into consistent rewards for RL optimization. Leveraging this framework, we train ML-Agent, driven by a 7B-sized Qwen-2.5 LLM for autonomous ML. Remarkably, despite being trained on merely 9 ML tasks, our 7B-sized ML-Agent outperforms the 671B-sized DeepSeek-R1 agent. Furthermore, it achieves continuous performance improvements and demonstrates exceptional cross-task generalization capabilities.

[Arxiv](https://arxiv.org/abs/2505.23723)