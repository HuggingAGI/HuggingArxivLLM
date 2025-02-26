# 大型语言模型在几何领域的能力更胜一筹：交易环境中基于 LLM 的智能体数值理解研究

发布时间：2025年02月25日

`LLM应用` `股票投资`

> LLM Knows Geometry Better than Algebra: Numerical Understanding of LLM-Based Agents in A Trading Arena

# 摘要

> 大型语言模型（LLMs）的近期进展大大提升了在自然语言处理任务中的表现。然而，它们在动态、未知任务中的泛化能力，尤其是数值推理方面，仍面临挑战。现有基准主要评估LLMs在具有预定义最优解的问题上，但这些可能与现实场景不符，因为现实场景中往往没有明确答案。为解决这一差距，我们设计了Agent Trading Arena——一个通过零和游戏模拟复杂经济系统的虚拟数值游戏，其中智能体进行股票投资组合管理。实验表明，包括GPT-4o在内的LLMs在处理纯文本股票数据时，代数推理能力较弱，常聚焦于局部细节而非全局趋势。相比之下，当面对散点图或K线图等视觉数据时，LLMs在几何推理方面表现显著提升，表明视觉表示可增强数值推理能力。通过引入反思模块，这一能力进一步提升，该模块有助于复杂数据分析与解读。我们在纳斯达克股票数据集上的验证显示，LLMs在视觉数据上的推理能力优于文本数据。我们的代码和数据已公开发布于https://github.com/wekjsdvnm/Agent-Trading-Arena.git。


> Recent advancements in large language models (LLMs) have significantly improved performance in natural language processing tasks. However, their ability to generalize to dynamic, unseen tasks, particularly in numerical reasoning, remains a challenge. Existing benchmarks mainly evaluate LLMs on problems with predefined optimal solutions, which may not align with real-world scenarios where clear answers are absent. To bridge this gap, we design the Agent Trading Arena, a virtual numerical game simulating complex economic systems through zero-sum games, where agents invest in stock portfolios. Our experiments reveal that LLMs, including GPT-4o, struggle with algebraic reasoning when dealing with plain-text stock data, often focusing on local details rather than global trends. In contrast, LLMs perform significantly better with geometric reasoning when presented with visual data, such as scatter plots or K-line charts, suggesting that visual representations enhance numerical reasoning. This capability is further improved by incorporating the reflection module, which aids in the analysis and interpretation of complex data. We validate our findings on NASDAQ Stock dataset, where LLMs demonstrate stronger reasoning with visual data compared to text. Our code and data are publicly available at https://github.com/wekjsdvnm/Agent-Trading-Arena.git.

[Arxiv](https://arxiv.org/abs/2502.17967)