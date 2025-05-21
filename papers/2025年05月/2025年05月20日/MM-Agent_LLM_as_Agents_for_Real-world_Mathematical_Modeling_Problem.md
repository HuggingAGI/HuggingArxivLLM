# MM-Agent：用大型语言模型（LLM）赋能现实世界的数学建模问题

发布时间：2025年05月20日

`LLM应用` `数学建模`

> MM-Agent: LLM as Agents for Real-world Mathematical Modeling Problem

# 摘要

> 数学建模是科学发现与工程实践的基石，它将现实世界问题转化为物理、生物、经济等领域的形式化系统。与假设预定义公式的数学推理不同，建模需要进行开放性问题分析、抽象和系统化形式化。尽管大型语言模型（LLMs）展现了强大的推理能力，但在严格的模型构建方面仍显不足，限制了其在实际问题解决中的应用。为此，我们提出了基于LLM的现实世界数学建模任务，其中智能体需分析问题、构建领域适用的公式化模型，并生成完整的端到端解决方案。我们引入了MM-Bench，一个精选的基准测试集，包含2000年至2025年来自数学建模竞赛（MCM/ICM）的111个问题，涵盖物理、生物、经济等十个多样化领域。为解决这一任务，我们提出了MM-Agent，一个受专家启发的框架，将数学建模分解为四个阶段：开放性问题分析、结构化模型公式化、计算问题求解和报告生成。在MM-Bench上的实验表明，MM-Agent显著优于基线模型，相比人类专家解决方案提升了11.88%，且每任务仅需15分钟和$0.88的计算成本（使用GPT-4o）。此外，在官方MCM/ICM竞赛中，MM-Agent协助两支本科生团队在2025年MCM/ICM竞赛中获得Finalist Award（	extbf{27,456支队伍中排名前2.0%}），证明了其作为建模协作者的实际有效性。我们的代码可在https://github.com/usail-hkust/LLM-MM-Agent获取。


> Mathematical modeling is a cornerstone of scientific discovery and engineering practice, enabling the translation of real-world problems into formal systems across domains such as physics, biology, and economics. Unlike mathematical reasoning, which assumes a predefined formulation, modeling requires open-ended problem analysis, abstraction, and principled formalization. While Large Language Models (LLMs) have shown strong reasoning capabilities, they fall short in rigorous model construction, limiting their utility in real-world problem-solving. To this end, we formalize the task of LLM-powered real-world mathematical modeling, where agents must analyze problems, construct domain-appropriate formulations, and generate complete end-to-end solutions. We introduce MM-Bench, a curated benchmark of 111 problems from the Mathematical Contest in Modeling (MCM/ICM), spanning the years 2000 to 2025 and across ten diverse domains such as physics, biology, and economics. To tackle this task, we propose MM-Agent, an expert-inspired framework that decomposes mathematical modeling into four stages: open-ended problem analysis, structured model formulation, computational problem solving, and report generation. Experiments on MM-Bench show that MM-Agent significantly outperforms baseline agents, achieving an 11.88\% improvement over human expert solutions while requiring only 15 minutes and \$0.88 per task using GPT-4o. Furthermore, under official MCM/ICM protocols, MM-Agent assisted two undergraduate teams in winning the Finalist Award (\textbf{top 2.0\% among 27,456 teams}) in MCM/ICM 2025, demonstrating its practical effectiveness as a modeling copilot. Our code is available at https://github.com/usail-hkust/LLM-MM-Agent

[Arxiv](https://arxiv.org/abs/2505.14148)