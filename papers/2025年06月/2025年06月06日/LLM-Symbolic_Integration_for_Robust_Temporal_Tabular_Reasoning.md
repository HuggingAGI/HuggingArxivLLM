# 大型语言模型与符号积分的融合，实现健壮的时序表格推理

发布时间：2025年06月06日

`LLM应用` `问答系统` `数据库`

> LLM-Symbolic Integration for Robust Temporal Tabular Reasoning

# 摘要

> 时间表格问答任务对大型语言模型（LLMs）提出了重大挑战，要求模型在结构化数据上具备强大的推理能力，而这往往是传统提示方法难以胜任的。这些方法面临记忆化、对表格大小敏感以及在复杂查询上性能下降等挑战。为了解决这些问题，我们引入了TempTabQA-C，一个专为系统化和受控评估设计的合成数据集，同时引入了一种符号中间表达形式，将表格转换为数据库模式。这种结构化方法使LLMs能够生成并执行SQL查询，从而提升泛化能力并减少偏见。通过结合自适应少样本提示和上下文定制化示例，我们的方法实现了更优的鲁棒性、扩展性和性能表现。实验结果一致表明，在关键挑战上取得了显著改进，为LLMs在稳健时间推理方面树立了新的基准。

> Temporal tabular question answering presents a significant challenge for Large Language Models (LLMs), requiring robust reasoning over structured data, which is a task where traditional prompting methods often fall short. These methods face challenges such as memorization, sensitivity to table size, and reduced performance on complex queries. To overcome these limitations, we introduce TempTabQA-C, a synthetic dataset designed for systematic and controlled evaluations, alongside a symbolic intermediate representation that transforms tables into database schemas. This structured approach allows LLMs to generate and execute SQL queries, enhancing generalization and mitigating biases. By incorporating adaptive few-shot prompting with contextually tailored examples, our method achieves superior robustness, scalability, and performance. Experimental results consistently highlight improvements across key challenges, setting a new benchmark for robust temporal reasoning with LLMs.

[Arxiv](https://arxiv.org/abs/2506.05746)