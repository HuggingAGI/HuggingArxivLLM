# Opus：面向复杂工作流生成的提示意图框架

发布时间：2025年07月15日

`LLM应用` `业务流程管理`

> Opus: A Prompt Intention Framework for Complex Workflow Generation

# 摘要

> 本文介绍了Opus Prompt意图框架，旨在利用指令微调的大型语言模型（LLMs）提升复杂工作流的生成效果。我们提出了一种位于用户查询与工作流生成之间的中间意图捕获层，该层实现了Opus工作流意图框架，包括从用户查询中提取工作流信号、将其转化为结构化的意图对象，并根据这些意图生成工作流。实验结果表明，这一层能够使LLMs生成逻辑清晰、意义明确且可靠性随查询复杂度增加而提升的输出。在一个包含1,000个多种意图查询-工作流对的合成基准测试中，将Opus Prompt意图框架应用于工作流生成在语义工作流相似性指标上表现出一致的提升。本文通过将工作流信号和意图的概念应用于LLM驱动的工作流生成，介绍了Opus Prompt意图框架。我们提出了一种可重复、可定制的基于LLM的意图捕获系统，用于从用户查询中提取工作流信号和意图。最后，我们提供了实证证据，证明与直接从用户查询生成工作流相比，所提出的系统显著提高了工作流生成质量，尤其是在涉及混合意图提取的情况下。

> This paper introduces the Opus Prompt Intention Framework, designed to improve complex Workflow Generation with instruction-tuned Large Language Models (LLMs). We propose an intermediate Intention Capture layer between user queries and Workflow Generation, implementing the Opus Workflow Intention Framework, which consists of extracting Workflow Signals from user queries, interpreting them into structured Workflow Intention objects, and generating Workflows based on these Intentions. Our results show that this layer enables LLMs to produce logical and meaningful outputs that scale reliably as query complexity increases. On a synthetic benchmark of 1,000 multi-intent query-Workflow(s) pairs, applying the Opus Prompt Intention Framework to Workflow Generation yields consistent improvements in semantic Workflow similarity metrics. In this paper, we introduce the Opus Prompt Intention Framework by applying the concepts of Workflow Signal and Workflow Intention to LLM-driven Workflow Generation. We present a reproducible, customizable LLM-based Intention Capture system to extract Workflow Signals and Workflow Intentions from user queries. Finally, we provide empirical evidence that the proposed system significantly improves Workflow Generation quality compared to direct generation from user queries, particularly in cases of Mixed Intention Elicitation.

[Arxiv](https://arxiv.org/abs/2507.11288)