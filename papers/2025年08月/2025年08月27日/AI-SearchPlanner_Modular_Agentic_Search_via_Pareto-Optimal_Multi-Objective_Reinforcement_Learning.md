# AI-SearchPlanner：通过帕累托最优多目标强化学习实现的模块化智能体搜索

发布时间：2025年08月27日

`强化学习` `基础理论`

> AI-SearchPlanner: Modular Agentic Search via Pareto-Optimal Multi-Objective Reinforcement Learning

# 摘要

> 近年来，研究人员探索将大型语言模型（LLMs）与搜索引擎相结合，以同时利用LLMs的内部预训练知识和外部信息。具体来说，强化学习（RL）凭借与搜索引擎的多轮交互提升LLM推理能力，已成为一种极具潜力的技术范式。然而，现有基于RL的搜索智能体依赖单个LLM端到端地兼顾搜索规划与问答（QA）任务，这导致其难以同时优化两种能力。在实际应用中，先进的AI搜索系统常采用大型冻结LLM（如GPT-4、DeepSeek-R1）来保障高质量问答。因此，一种更高效的方案是引入小型可训练LLM，专门负责搜索规划。为此，本文提出**AI-SearchPlanner**——一种新型强化学习框架，通过聚焦搜索规划来提升冻结问答模型的性能。具体包括三大核心创新：1）搜索规划器与生成器的架构解耦；2）搜索规划的双奖励对齐机制；3）规划效用与成本的帕累托优化，从而达成目标。在真实数据集上的大量实验验证，AI SearchPlanner在有效性与效率上均超越现有基于RL的搜索智能体，并在多种冻结QA模型及数据领域展现出优异的泛化能力。

> Recent studies have explored integrating Large Language Models (LLMs) with search engines to leverage both the LLMs' internal pre-trained knowledge and external information. Specially, reinforcement learning (RL) has emerged as a promising paradigm for enhancing LLM reasoning through multi-turn interactions with search engines. However, existing RL-based search agents rely on a single LLM to handle both search planning and question-answering (QA) tasks in an end-to-end manner, which limits their ability to optimize both capabilities simultaneously. In practice, sophisticated AI search systems often employ a large, frozen LLM (e.g., GPT-4, DeepSeek-R1) to ensure high-quality QA. Thus, a more effective and efficient approach is to utilize a small, trainable LLM dedicated to search planning. In this paper, we propose \textbf{AI-SearchPlanner}, a novel reinforcement learning framework designed to enhance the performance of frozen QA models by focusing on search planning. Specifically, our approach introduces three key innovations: 1) Decoupling the Architecture of the Search Planner and Generator, 2) Dual-Reward Alignment for Search Planning, and 3) Pareto Optimization of Planning Utility and Cost, to achieve the objectives. Extensive experiments on real-world datasets demonstrate that AI SearchPlanner outperforms existing RL-based search agents in both effectiveness and efficiency, while exhibiting strong generalization capabilities across diverse frozen QA models and data domains.

[Arxiv](https://arxiv.org/abs/2508.20368)