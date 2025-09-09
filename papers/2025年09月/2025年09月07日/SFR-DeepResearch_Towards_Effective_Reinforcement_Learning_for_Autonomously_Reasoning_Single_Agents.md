# SFR-DeepResearch：致力于自主推理单智能体的有效强化学习

发布时间：2025年09月07日

`Agent` `基础理论`

> SFR-DeepResearch: Towards Effective Reinforcement Learning for Autonomously Reasoning Single Agents

# 摘要

> 为大型语言模型（LLMs）赋予复杂交错的推理与工具使用能力，已成为智能体AI研究的核心方向——尤其是在近期推理导向（“思考型”）模型取得突破之后。这些能力正是开启众多重要应用的关键，深度研究（DR）便是其中之一，它需要对海量来源展开广泛的搜索与推理。本文聚焦开发原生自主单智能体模型，专为DR设计，仅需极少的网络爬取与Python工具集成。与多智能体系统不同——后者中智能体承担预定义角色，在静态工作流的每一步都需明确指令——自主单智能体可基于上下文动态决策下一步行动，全程无需人工干预。先前研究多针对基础或指令微调LLMs提出训练方案，而我们则专注于对推理优化模型进行持续强化学习（RL），在保留推理能力的同时进一步提升智能体技能。为此，我们提出一种基于全合成数据的简易RL方案，并将其应用于多种开源LLMs。我们的最优变体SFR-DR-20B在“人类终极考试”基准测试中准确率高达28.7%。此外，我们还通过关键分析实验，为所提方法提供了更多洞见。

> Equipping large language models (LLMs) with complex, interleaved reasoning and tool-use capabilities has become a key focus in agentic AI research, especially with recent advances in reasoning-oriented (``thinking'') models. Such capabilities are key to unlocking a number of important applications. One such application is Deep Research (DR), which requires extensive search and reasoning over many sources. Our work in this paper focuses on the development of native Autonomous Single-Agent models for DR featuring minimal web crawling and Python tool integration. Unlike multi-agent systems, where agents take up pre-defined roles and are told what to do at each step in a static workflow, an autonomous single-agent determines its next action dynamically based on context, without manual directive. While prior work has proposed training recipes for base or instruction-tuned LLMs, we focus on continual reinforcement learning (RL) of reasoning-optimized models to further enhance agentic skills while preserving reasoning ability. Towards this end, we propose a simple RL recipe with entirely synthetic data, which we apply to various open-source LLMs. Our best variant SFR-DR-20B achieves up to 28.7% on Humanity's Last Exam benchmark. In addition, we conduct key analysis experiments to provide more insights into our methodologies.

[Arxiv](https://arxiv.org/abs/2509.06283)