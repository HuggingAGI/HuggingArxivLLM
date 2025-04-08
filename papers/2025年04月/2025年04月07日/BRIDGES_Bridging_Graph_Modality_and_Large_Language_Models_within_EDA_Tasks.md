# BRIDGES：构建EDA任务中的图模态与大型语言模型桥梁

发布时间：2025年04月07日

`LLM应用

理由：这篇论文讨论了将图数据整合到大型语言模型（LLM）中，以提升在电子设计自动化（EDA）任务中的性能。作者提出了BRIDGES框架，通过生成包含图结构的数据集和设计跨模态投影器，使LLM能够更有效地利用图数据，从而在多个任务中显著提升了性能。这一研究属于LLM的应用层面，旨在将LLM技术应用于特定领域并提升其效果。` `电子设计自动化` `EDA`

> BRIDGES: Bridging Graph Modality and Large Language Models within EDA Tasks

# 摘要

> 尽管许多EDA任务涉及基于图的数据，但现有的EDA中的LLMs主要要么将图表示为序列文本，要么忽略可能有益的图结构数据，如RTL代码的数据流图。近期研究发现，当图被表示为序列文本时，LLM性能会受到影响，而使用额外的图信息会显著提升性能。为了解决这些挑战，我们引入了BRIDGES框架，该框架旨在将图模态整合到EDA任务的LLMs中。BRIDGES集成了一个自动数据生成工作流、一个结合图模态与LLM的解决方案，以及一个全面的评估套件。

首先，我们建立了一个由LLM驱动的工作流，用于生成RTL和网表级别的数据，并将它们转换为带有功能描述的数据流和网表图。此工作流生成了一个包含超过500,000个图实例和15亿个标记的大型数据集。其次，我们提出了一种轻量级的跨模态投影器，将图表示编码为与文本兼容的提示，使LLMs能够有效利用图数据，而无需进行架构修改。实验结果表明，与仅使用文本的基线相比，BRIDGES在多个任务上实现了2到10倍的性能提升，包括设计检索的准确性、类型预测以及功能描述的困惑度，且计算开销可以忽略不计（模型权重增加不到1%，额外运行时开销不到30%）。即使没有额外的LLM微调，我们的结果也远超仅使用文本的方法。我们计划发布BRIDGES，包括数据集、模型和训练流程。


> While many EDA tasks already involve graph-based data, existing LLMs in EDA primarily either represent graphs as sequential text, or simply ignore graph-structured data that might be beneficial like dataflow graphs of RTL code. Recent studies have found that LLM performance suffers when graphs are represented as sequential text, and using additional graph information significantly boosts performance. To address these challenges, we introduce BRIDGES, a framework designed to incorporate graph modality into LLMs for EDA tasks. BRIDGES integrates an automated data generation workflow, a solution that combines graph modality with LLM, and a comprehensive evaluation suite. First, we establish an LLM-driven workflow to generate RTL and netlist-level data, converting them into dataflow and netlist graphs with function descriptions. This workflow yields a large-scale dataset comprising over 500,000 graph instances and more than 1.5 billion tokens. Second, we propose a lightweight cross-modal projector that encodes graph representations into text-compatible prompts, enabling LLMs to effectively utilize graph data without architectural modifications. Experimental results demonstrate 2x to 10x improvements across multiple tasks compared to text-only baselines, including accuracy in design retrieval, type prediction and perplexity in function description, with negligible computational overhead (<1% model weights increase and <30% additional runtime overhead). Even without additional LLM finetuning, our results outperform text-only by a large margin. We plan to release BRIDGES, including the dataset, models, and training flow.

[Arxiv](https://arxiv.org/abs/2504.05180)