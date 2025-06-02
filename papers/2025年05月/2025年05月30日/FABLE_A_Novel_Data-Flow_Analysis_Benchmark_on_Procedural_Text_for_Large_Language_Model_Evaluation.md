# FABLE：面向大型语言模型评估的新型过程文本数据流分析基准。

发布时间：2025年05月30日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLMs）在数据流推理方面的应用能力，并引入了一个基准测试（FABLE）来评估LLMs在不同领域中的表现。虽然涉及模型的性能评估，但主要关注点在于模型在特定任务中的应用和基准测试的构建，属于LLM应用的范畴。` `软件工程` `自动化`

> FABLE: A Novel Data-Flow Analysis Benchmark on Procedural Text for Large Language Model Evaluation

# 摘要

> 理解数据如何流动、转换和持久化（即数据流）是过程任务推理的基础。尽管大型语言模型（LLMs）在自然语言和编程语言方面表现出色，但它们在数据流推理能力上的系统性评估仍属空白。尽管LLMs越来越多地被应用于包含过程任务的决策中，但它们在数据流推理方面的系统性能力尚未得到充分评估。我们引入了FABLE，这是一个可扩展的基准测试，旨在通过结构化的程序性文本评估LLMs对数据流的理解。FABLE借鉴了软件工程中的八种经典数据流分析方法：可达定义、非常忙碌表达式、可用表达式、活跃变量分析、区间分析、类型状态分析、污点分析和并发分析。这些分析方法在三个真实世界领域中得到应用：烹饪食谱、旅行路线和自动化计划。该基准测试包含2,400个问答对，每个领域-分析组合有100个示例。我们评估了三种类型的LLMs：专注于推理的模型（DeepSeek-R1 8B）、通用模型（LLaMA 3.1 8B）和特定于代码的模型（Granite Code 8B）。每个模型通过每提示五次采样的多数投票进行测试。结果显示，推理模型的准确率更高，但其推理速度比其他模型慢20多倍。相比之下，通用和特定于代码的模型表现接近随机水平。FABLE提供了首个诊断基准，用于系统性评估数据流推理，并为开发具有更强过程理解能力的模型提供了见解。

> Understanding how data moves, transforms, and persists, known as data flow, is fundamental to reasoning in procedural tasks. Despite their fluency in natural and programming languages, large language models (LLMs), although increasingly being applied to decisions with procedural tasks, have not been systematically evaluated for their ability to perform data-flow reasoning. We introduce FABLE, an extensible benchmark designed to assess LLMs' understanding of data flow using structured, procedural text. FABLE adapts eight classical data-flow analyses from software engineering: reaching definitions, very busy expressions, available expressions, live variable analysis, interval analysis, type-state analysis, taint analysis, and concurrency analysis. These analyses are instantiated across three real-world domains: cooking recipes, travel routes, and automated plans. The benchmark includes 2,400 question-answer pairs, with 100 examples for each domain-analysis combination. We evaluate three types of LLMs: a reasoning-focused model (DeepSeek-R1 8B), a general-purpose model (LLaMA 3.1 8B), and a code-specific model (Granite Code 8B). Each model is tested using majority voting over five sampled completions per prompt. Results show that the reasoning model achieves higher accuracy, but at the cost of over 20 times slower inference compared to the other models. In contrast, the general-purpose and code-specific models perform close to random chance. FABLE provides the first diagnostic benchmark to systematically evaluate data-flow reasoning and offers insights for developing models with stronger procedural understanding.

[Arxiv](https://arxiv.org/abs/2505.24258)