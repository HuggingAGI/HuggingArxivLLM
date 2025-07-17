# # Xiangqi-R1：强化学习助力大型语言模型提升中国象棋空间战略推理能力

发布时间：2025年07月16日

`LLM应用` `人工智能`

> Xiangqi-R1: Enhancing Spatial Strategic Reasoning in LLMs for Chinese Chess via Reinforcement Learning

# 摘要

> 游戏玩法一直是评估人工通用智能（AGI）的重要基准。大型语言模型（LLMs）虽然在通用推理方面表现出色，但在复杂且完全可观测的棋盘游戏中至关重要的空间战略推理能力仍有待深入探索。本研究选择中国象棋（Xiangqi）作为测试平台，因其规则复杂且空间复杂性较高。为提升LLMs在该领域的能力，我们提出了一种专为Xiangqi设计的训练框架，基于一个包含五百万棋盘-落子配对的大型数据集，并辅以专家注释和引擎评估。在此基础上，我们引入了Xiangqi-R1，这是一个70亿参数的模型，采用多阶段训练方式：首先微调模型以预测合法走子，掌握基本空间规则；其次整合战略注释以提升决策能力；最后通过基于组相对策略优化（GRPO）的强化学习，利用多维奖励信号增强推理稳定性。实验结果表明，尽管通用型LLMs具备强大的规模和能力，但在这些任务中仍难以达到令人满意的性能。与通用型LLMs相比，Xiangqi-R1在走子合法性上提升了18%，在分析准确性上提升了22%。我们的研究结果为在空间复杂领域中构建通用战略智能指明了一条有前景的道路。

> Game playing has long served as a fundamental benchmark for evaluating Artificial General Intelligence (AGI). While Large Language Models (LLMs) have demonstrated impressive capabilities in general reasoning, their effectiveness in spatial strategic reasoning, which is critical for complex and fully observable board games, remains insufficiently explored. In this work, we adopt Chinese Chess (Xiangqi) as a challenging and rich testbed due to its intricate rules and spatial complexity. To advance LLMs' strategic competence in such environments, we propose a training framework tailored to Xiangqi, built upon a large-scale dataset of five million board-move pairs enhanced with expert annotations and engine evaluations. Building on this foundation, we introduce Xiangqi-R1, a 7B-parameter model trained in multi-stage manner: (1) fine-tuning for legal move prediction to capture basic spatial rules, (2) incorporating strategic annotations to improve decision-making, and (3) applying reinforcement learning via Group Relative Policy Optimization (GRPO) with multi-dimensional reward signals to enhance reasoning stability. Our Experimental results indicate that, despite their size and power, general-purpose LLMs struggle to achieve satisfactory performance in these tasks. Compared to general-purpose LLMs, Xiangqi-R1 greatly advances with an 18% rise in move legality and a 22% boost in analysis accuracy. Our results point to a promising path for creating general strategic intelligence in spatially complex areas.

[Arxiv](https://arxiv.org/abs/2507.12215)