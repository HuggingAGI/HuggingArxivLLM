# AutoPrep: 基于多智能体框架的自然语言问题感知数据准备

发布时间：2024年12月10日

`Agent

理由：这篇论文提出了一个基于大型语言模型（LLM）的多代理框架AUTOPREP，用于表格问答（TQA）中的数据准备。该框架通过多个专业化代理（如规划器、程序员和执行器）协同工作，处理表格上的自然语言问题。由于论文的核心是围绕多代理系统的设计和应用，因此将其分类为Agent。` `数据管理`

> AutoPrep: Natural Language Question-Aware Data Preparation with a Multi-Agent Framework

# 摘要

> # 摘要
表格问答（TQA）旨在回答关于表格的自然语言问题，它能够帮助用户快速高效地从结构化数据中提取有价值的信息，弥合了人类语言与机器可读格式之间的鸿沟。许多表格数据来源于网络或现实场景，因此需要精心准备数据以确保答案的准确性。与传统数据准备不同，问题感知的数据准备引入了新的需求，例如针对特定问题的列增强、过滤以及值规范化或转换。由于这些任务各具特点，单一模型难以在所有场景中表现优异。为此，我们提出了AUTOPREP，一个基于大型语言模型（LLM）的多代理框架，通过多个专业化代理协同工作，确保更准确且符合上下文的数据准备。AUTOPREP通过三个核心组件处理表格上的自然语言问题：规划器负责制定逻辑计划，程序员将逻辑计划转化为可执行的代码，执行器则迭代调试代码以确保结果正确。为了支持这一框架，我们设计了链式思维推理机制用于高级操作建议，并采用工具增强方法生成低级代码。实验表明，AUTOPREP通过问题感知的数据准备显著提升了现有TQA解决方案的性能。

> Answering natural language (NL) questions about tables, which is referred to as Tabular Question Answering (TQA), is important because it enables users to extract meaningful insights quickly and efficiently from structured data, bridging the gap between human language and machine-readable formats. Many of these tables originate from web sources or real-world scenarios, necessitating careful data preparation (or data prep for short) to ensure accurate answers. However, unlike traditional data prep, question-aware data prep introduces new requirements, which include tasks such as column augmentation and filtering for given questions, and question-aware value normalization or conversion. Because each of the above tasks is unique, a single model (or agent) may not perform effectively across all scenarios. In this paper, we propose AUTOPREP, a large language model (LLM)-based multi-agent framework that leverages the strengths of multiple agents, each specialized in a certain type of data prep, ensuring more accurate and contextually relevant responses. Given an NL question over a table, AUTOPREP performs data prep through three key components. Planner: Determines a logical plan, outlining a sequence of high-level operations. Programmer: Translates this logical plan into a physical plan by generating the corresponding low-level code. Executor: Iteratively executes and debugs the generated code to ensure correct outcomes. To support this multi-agent framework, we design a novel chain-of-thought reasoning mechanism for high-level operation suggestion, and a tool-augmented method for low-level code generation. Extensive experiments on real-world TQA datasets demonstrate that AUTOPREP can significantly improve the SOTA TQA solutions through question-aware data prep.

[Arxiv](https://arxiv.org/abs/2412.10422)