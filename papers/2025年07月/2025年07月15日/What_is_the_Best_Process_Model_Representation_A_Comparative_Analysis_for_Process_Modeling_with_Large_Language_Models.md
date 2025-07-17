# 最佳过程模型表示是什么？基于大型语言模型的过程建模比较分析

发布时间：2025年07月15日

`LLM应用

摘要中讨论了大型语言模型（LLMs）在流程建模任务中的应用，特别是流程模型生成（PMG）。研究人员比较了不同流程模型表示方法（PMRs）在基于LLMs的PMo中的表现，并推出了一个新数据集来评估这些方法。这属于将LLMs应用于特定任务的范畴。` `流程建模` `业务流程管理`

> What is the Best Process Model Representation? A Comparative Analysis for Process Modeling with Large Language Models

# 摘要

> 大型语言模型（LLMs）正被越来越多地用于流程建模（PMo）任务，如流程模型生成（PMG）。为了支持这些任务，研究人员提出了多种流程模型表示方法（PMRs），它们既可以作为模型抽象，也可以作为生成目标。然而，这些PMRs在结构、复杂度和实用性上存在显著差异，且从未进行过系统性的比较。此外，近期的PMG方法采用了不同的评估策略和生成技术，进一步增加了比较的难度。本文首次系统地研究了多种PMRs在基于LLMs的PMo中的表现。我们推出了PMo数据集，这是一个包含55个流程描述及其对应九种不同PMRs模型的新数据集。我们从两个维度对PMRs进行评估：其一是适合基于LLMs的PMo的能力，其二是其在PMG中的性能。	extit{Mermaid}在六个PMo标准中表现最佳，而	extit{BPMN文本}在流程元素相似性方面提供了最优的PMG结果。

> Large Language Models (LLMs) are increasingly applied for Process Modeling (PMo) tasks such as Process Model Generation (PMG). To support these tasks, researchers have introduced a variety of Process Model Representations (PMRs) that serve as model abstractions or generation targets. However, these PMRs differ widely in structure, complexity, and usability, and have never been systematically compared. Moreover, recent PMG approaches rely on distinct evaluation strategies and generation techniques, making comparison difficult. This paper presents the first empirical study that evaluates multiple PMRs in the context of PMo with LLMs. We introduce the PMo Dataset, a new dataset containing 55 process descriptions paired with models in nine different PMRs. We evaluate PMRs along two dimensions: suitability for LLM-based PMo and performance on PMG. \textit{Mermaid} achieves the highest overall score across six PMo criteria, whereas \textit{BPMN text} delivers the best PMG results in terms of process element similarity.

[Arxiv](https://arxiv.org/abs/2507.11356)