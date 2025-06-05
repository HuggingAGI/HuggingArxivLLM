# R-Search：利用多奖励强化学习赋能大型语言模型推理，通过搜索实现

发布时间：2025年06月04日

`LLM应用` `人工智能`

> R-Search: Empowering LLM Reasoning with Search via Multi-Reward Reinforcement Learning

# 摘要

> 大型语言模型 (LLMs) 在多步骤和长链推理方面取得了显著进展。然而，要将它们的推理能力扩展到与搜索的深度交互仍然面临巨大挑战。现有模型常常难以识别最优的推理-搜索交互轨迹，导致响应质量不尽如人意。针对这一问题，我们提出了 R-Search，一个创新性的强化学习框架，专门用于推理与搜索的深度整合。通过多奖励信号机制，R-Search 赋能 LLMs 实现自主的多步骤推理，并学习最优的推理-搜索交互轨迹，从而显著提升复杂逻辑和知识密集型任务中的响应质量。在训练过程中，R-Search 提供多阶段、多类型的奖励信号，实现推理与搜索轨迹的联合优化。实验结果表明，R-Search 在七个数据集上的表现均超越现有先进 RAG 基线，领域内和领域外分别提升 32.2% 和 25.1%。代码和数据已开源，详情请访问 https://github.com/QingFei1/R-Search。

> Large language models (LLMs) have notably progressed in multi-step and long-chain reasoning. However, extending their reasoning capabilities to encompass deep interactions with search remains a non-trivial challenge, as models often fail to identify optimal reasoning-search interaction trajectories, resulting in suboptimal responses. We propose R-Search, a novel reinforcement learning framework for Reasoning-Search integration, designed to enable LLMs to autonomously execute multi-step reasoning with deep search interaction, and learn optimal reasoning search interaction trajectories via multi-reward signals, improving response quality in complex logic- and knowledge-intensive tasks. R-Search guides the LLM to dynamically decide when to retrieve or reason, while globally integrating key evidence to enhance deep knowledge interaction between reasoning and search. During RL training, R-Search provides multi-stage, multi-type rewards to jointly optimize the reasoning-search trajectory. Experiments on seven datasets show that R-Search outperforms advanced RAG baselines by up to 32.2% (in-domain) and 25.1% (out-of-domain). The code and data are available at https://github.com/QingFei1/R-Search.

[Arxiv](https://arxiv.org/abs/2506.04185)