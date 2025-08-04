# # 摘要
ITUNLP团队在SemEval-2025任务8中，针对表格数据问答系统提出了基于零样本方法的解决方案，通过LLM驱动的代码生成技术实现任务目标。

发布时间：2025年08月01日

`LLM应用

摘要中提到论文使用大型语言模型的代码生成能力来处理表格数据的问答任务，属于应用层面的研究。` `数据处理` `问答系统`

> ITUNLP at SemEval-2025 Task 8: Question-Answering over Tabular Data: A Zero-Shot Approach using LLM-Driven Code Generation

# 摘要

> 本文介绍了我们在 SemEval-2025 任务8：DataBench 中的问答系统，专注于处理来自不同领域的表格数据。该任务分为两个子任务：DataBench QA（子任务I）和DataBench Lite QA（子任务II）。我们开发了一种零样本解决方案，重点利用大型语言模型（LLM）的代码生成能力。具体而言，我们提出了一种基于先进开源LLM的Python代码生成框架，通过优化的提示策略生成可执行的Pandas代码。实验结果表明，不同LLM在Python代码生成方面表现各异。此外，Python代码生成方法在表格问答任务中优于其他方法。尽管在本文提交时我们对零样本系统的排名尚不清楚，但在开源模型类别中，我们的系统在30个优于基线的系统中，子任务I获得第八名，子任务II获得第六名。

> This paper presents our system for SemEval-2025 Task 8: DataBench, Question-Answering over Tabular Data. The primary objective of this task is to perform question answering on given tabular datasets from diverse domains under two subtasks: DataBench QA (Subtask I) and DataBench Lite QA (Subtask II). To tackle both subtasks, we developed a zero-shot solution with a particular emphasis on leveraging Large Language Model (LLM)-based code generation. Specifically, we propose a Python code generation framework utilizing state-of-the-art open-source LLMs to generate executable Pandas code via optimized prompting strategies. Our experiments reveal that different LLMs exhibit varying levels of effectiveness in Python code generation. Additionally, results show that Python code generation achieves superior performance in tabular question answering compared to alternative approaches. Although our ranking among zero-shot systems is unknown at the time of this paper's submission, our system achieved eighth place in Subtask I and sixth place in Subtask~II among the 30 systems that outperformed the baseline in the open-source models category.

[Arxiv](https://arxiv.org/abs/2508.00762)