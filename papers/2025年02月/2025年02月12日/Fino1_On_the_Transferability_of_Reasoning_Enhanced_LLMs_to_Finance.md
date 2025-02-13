# Fino1：研究增强推理的大语言模型在金融领域的迁移能力

发布时间：2025年02月12日

`LLM应用`

> Fino1: On the Transferability of Reasoning Enhanced LLMs to Finance

# 摘要

> 大型语言模型（LLMs）近期的突破性进展展现了强大的通用推理能力，但其在财务推理领域的潜力尚未得到充分挖掘。本研究全面评估了16个强大的推理型和通用型LLMs在涉及财务文本、表格数据和方程的三项复杂任务中的表现，重点考察了数值推理、表格解读、财务术语理解、长上下文处理和基于方程的问题解决能力。研究发现，尽管更优质的数据集和预训练方法能有效提升财务推理能力，但通用增强方法如CoT微调并不总是带来稳定的性能提升。此外，所有推理策略在应对长上下文和多表格任务时均面临挑战。为解决这些局限性，我们基于Llama-3.1-8B-Instruct开发了一个增强的财务推理模型，通过CoT微调和领域特定推理路径的强化学习进行优化。即使仅使用一个财务数据集进行简单的微调，我们的模型在各项任务中也实现了平均10%的性能提升，超越了所有8B规模的模型，甚至在平均性能上超过了Llama3-70B-Instruct和Llama3.1-70B-Instruct。研究结果凸显了在财务任务中进行领域特定适应的重要性，并为未来研究指明了方向，包括多表格推理、长上下文处理和财务术语理解。所有数据集、模型和代码均已公开发布，同时我们还引入了一个排行榜，以便未来对数据集和模型进行基准测试。

> Recent advancements in large language models (LLMs) have shown strong general reasoning abilities, yet their effectiveness in financial reasoning remains underexplored. In this study, we comprehensively evaluate 16 powerful reasoning and general LLMs on three complex financial tasks involving financial text, tabular data, and equations, assessing numerical reasoning, tabular interpretation, financial terminology comprehension, long-context processing, and equation-based problem solving. Our results show that while better datasets and pretraining improve financial reasoning, general enhancements like CoT fine-tuning do not always yield consistent gains. Moreover, all reasoning strategies face challenges in improving performance on long-context and multi-table tasks. To address these limitations, we develop a financial reasoning-enhanced model based on Llama-3.1-8B-Instruct, by CoT fine-tuning and reinforcement learning with domain-specific reasoning paths. Even with simple fine-tuning with one financial dataset, our model achieves a consistent 10% performance improvement across tasks, surpassing all 8B models and even Llama3-70B-Instruct and Llama3.1-70B-Instruct on average. Our results highlight the need for domain-specific adaptations in financial tasks, emphasizing future directions such as multi-table reasoning, long-context processing, and financial terminology comprehension. All our datasets, models, and codes are publicly available. Furthermore, we introduce a leaderboard for benchmarking future datasets and models.

[Arxiv](https://arxiv.org/abs/2502.08127)