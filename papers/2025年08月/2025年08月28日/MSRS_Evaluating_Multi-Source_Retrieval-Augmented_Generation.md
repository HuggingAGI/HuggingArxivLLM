# MSRS：多源检索增强生成的评估

发布时间：2025年08月28日

`RAG` `基础理论`

> MSRS: Evaluating Multi-Source Retrieval-Augmented Generation

# 摘要

> 检索增强系统的评估场景通常较为局限：要么回答查询所需的信息能在单一来源中找到，要么答案是简短的事实性内容。然而，许多实际应用却要求系统具备整合、总结分散在多源信息的能力——此时没有任何单一来源能独立回应用户的问题。在这类场景中，RAG流程的检索组件需识别多样化的相关性信号，生成组件则要实现多源信息的关联与融合。为此，我们提出了一个可扩展框架，用于构建评估基准，专门考验RAG系统整合多源信息并生成长篇回复的能力。基于该框架，我们构建了两个多源检索与综合新基准——MSRS-Story和MSRS-Meet，分别对应叙事综合与总结任务，且均需从大规模数据集中检索信息。我们通过多种RAG流程（含稀疏/密集检索器与前沿LLM的组合）开展了大量实验，结果显示：生成质量与检索效果高度相关，且检索效果因任务差异显著。值得注意的是，即便在理想检索条件下，多源综合仍是一大难点，但推理模型在这一关键环节的表现明显优于标准LLM。

> Retrieval-augmented systems are typically evaluated in settings where information required to answer the query can be found within a single source or the answer is short-form or factoid-based. However, many real-world applications demand the ability to integrate and summarize information scattered across multiple sources, where no single source is sufficient to respond to the user's question. In such settings, the retrieval component of a RAG pipeline must recognize a variety of relevance signals, and the generation component must connect and synthesize information across multiple sources. We present a scalable framework for constructing evaluation benchmarks that challenge RAG systems to integrate information across distinct sources and generate long-form responses. Using our framework, we build two new benchmarks on Multi-Source Retrieval and Synthesis: MSRS-Story and MSRS-Meet, representing narrative synthesis and summarization tasks, respectively, that require retrieval from large collections. Our extensive experiments with various RAG pipelines -- including sparse and dense retrievers combined with frontier LLMs -- reveal that generation quality is highly dependent on retrieval effectiveness, which varies greatly by task. While multi-source synthesis proves challenging even in an oracle retrieval setting, we find that reasoning models significantly outperform standard LLMs at this distinct step.

[Arxiv](https://arxiv.org/abs/2508.20867)