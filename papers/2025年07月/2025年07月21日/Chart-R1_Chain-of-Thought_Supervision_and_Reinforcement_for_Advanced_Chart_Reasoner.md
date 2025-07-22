# Chart-R1：面向高级图表推理的链式思维监督与强化方法

发布时间：2025年07月21日

`LLM应用

摘要中提到的Chart-R1是一个基于强化学习微调的视觉-语言模型，专注于图表推理任务，属于将大型语言模型应用于特定领域，因此归类为LLM应用。` `多模态` `图表分析`

> Chart-R1: Chain-of-Thought Supervision and Reinforcement for Advanced Chart Reasoner

# 摘要

> 近期，受到 OpenAI-o1/o3 和 Deepseek-R1 的启发，基于强化学习微调的 R1-Style 方法在社区中引发了广泛关注。然而，现有的 R1-Style 方法主要集中在数学推理和代码智能领域，验证其优势在更通用的多模态数据中具有重要的研究价值。图表作为一类重要的多模态数据，蕴含丰富信息，同时也带来了复杂推理的挑战。为此，我们提出了 Chart-R1，这是一个基于强化学习微调的图表领域视觉-语言模型，专注于实现复杂的图表推理能力。为了支持 Chart-R1，我们首先创新性地提出了一种程序化数据合成技术，能够生成涵盖单子图表和多子图表的高质量分步推理数据，有效弥补了图表领域推理数据的空白。随后，我们设计了两阶段训练策略：Chart-COT 和 Chart-RFT。Chart-COT 通过分步链式思维监督，将复杂的图表推理任务分解为细粒度、易于理解的子任务，为强化学习的推理能力提升奠定了基础。Chart-RFT 采用了相对策略优化策略，针对数值响应采用了柔和的奖励机制，特别突出了图表领域中的数值敏感性。我们在开源基准测试和自建的 ChartRQA 数据集上进行了全面实验，结果表明 Chart-R1 在图表推理任务中表现优异，不仅超越了现有图表领域方法，甚至可以与开源或闭源的大规模模型（如 GPT-4o、Claude-3.5）相媲美。

> Recently, inspired by OpenAI-o1/o3 and Deepseek-R1, the R1-Style method based on reinforcement learning fine-tuning has received widespread attention from the community. Previous R1-Style methods mainly focus on mathematical reasoning and code intelligence. It is of great research significance to verify their advantages on more general multimodal data. Chart is an important multimodal data type with rich information, which brings important research challenges in complex reasoning. In this work, we introduce Chart-R1, a chart-domain vision-language model with reinforcement learning fine-tuning to enable complex chart reasoning. To support Chart-R1, we first propose a novel programmatic data synthesis technology to generate high-quality step-by-step chart reasoning data covering single- and multi-subcharts, which makes up for the lack of reasoning data in the chart domain. Then we develop a two-stage training strategy: Chart-COT with step-by-step chain-of-thought supervision, and Chart-RFT with numerically sensitive reinforcement fine-tuning. Chart-COT aims to decompose complex chart reasoning tasks into fine-grained, understandable subtasks through step-by-step supervision, which lays a good foundation for improving the reasoning level of reinforcement learning. Chart-RFT utilize the typical group relative policy optimization strategy, in which a relatively soft reward is adopted for numerical response to emphasize the numerical sensitivity in the chart domain. We conduct extensive experiments on open-source benchmarks and self-built chart reasoning dataset (\emph{i.e., ChartRQA}). Experimental results show that Chart-R1 has significant advantages compared to chart-domain methods, even comparable to open/closed source large-scale models (\emph{e.g., GPT-4o, Claude-3.5}).

[Arxiv](https://arxiv.org/abs/2507.15509)