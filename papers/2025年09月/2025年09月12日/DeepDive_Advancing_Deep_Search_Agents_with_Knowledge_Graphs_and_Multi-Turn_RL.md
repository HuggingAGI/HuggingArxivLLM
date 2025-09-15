# DeepDive：基于知识图谱与多轮强化学习的深度搜索智能体进阶

发布时间：2025年09月12日

`Agent` `基础理论`

> DeepDive: Advancing Deep Search Agents with Knowledge Graphs and Multi-Turn RL

# 摘要

> 为大型语言模型（LLMs）配备浏览工具，极大提升了其作为深度搜索智能体解决复杂现实任务的潜力。然而，开源LLM在这类场景中表现依旧欠佳，主要受限于使用浏览工具时的长程推理能力不足，以及缺乏难度足够的监督数据。为解决这些难题，我们提出DeepDive方案以升级深度搜索智能体。首先，我们提出一种从开放知识图谱自动生成复杂、困难且难以检索的问题的策略。其次，我们采用端到端多轮强化学习（RL），以增强LLM在深度搜索过程中的长程推理能力。实验结果显示，DeepDive-32B在BrowseComp基准测试中创下开源新标杆，性能超越WebSailor、DeepSeek-R1-Browse和Search-o1。我们证实，多轮RL训练不仅提升了深度搜索能力，还显著推动了多个基准测试的性能改进。我们还发现，DeepDive支持测试时的工具调用扩展与并行采样。所有数据集、模型及代码均已在https://github.com/THUDM/DeepDive开源发布。

> Augmenting large language models (LLMs) with browsing tools substantially improves their potential as deep search agents to solve complex, real-world tasks. Yet, open LLMs still perform poorly in such settings due to limited long-horizon reasoning capacity with browsing tools and the lack of sufficiently difficult supervised data. To address these challenges, we present DeepDive to advance deep search agents. First, we propose a strategy to automatically synthesize complex, difficult, and hard-to-find questions from open knowledge graphs. Second, we apply end-to-end multi-turn reinforcement learning (RL) to enhance LLMs' long-horizon reasoning with deep search. Experiments show that DeepDive-32B achieves a new open-source competitive result on BrowseComp, outperforming WebSailor, DeepSeek-R1-Browse, and Search-o1. We demonstrate that multi-turn RL training improves deep search ability and significantly contributes to the performance improvements across multiple benchmarks. We observe that DeepDive enables test-time scaling of tool calls and parallel sampling. All datasets, models, and code are publicly available at https://github.com/THUDM/DeepDive.

[Arxiv](https://arxiv.org/abs/2509.10446)