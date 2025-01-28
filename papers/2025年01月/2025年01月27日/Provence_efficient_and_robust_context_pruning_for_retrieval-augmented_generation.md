# Provence: 检索增强生成中的高效鲁棒上下文剪枝

发布时间：2025年01月27日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）中的上下文修剪问题，并提出了一个名为Provence的上下文修剪器。RAG是一种结合了检索和生成的技术，用于提升大型语言模型（LLM）的生成能力。论文的核心内容围绕如何通过上下文修剪来优化RAG的性能，因此应归类为RAG。` `问答系统`

> Provence: efficient and robust context pruning for retrieval-augmented generation

# 摘要

> 检索增强生成（RAG）虽然提升了LLMs的生成能力，但长上下文带来的计算开销和不相关信息的传播问题依然存在。上下文修剪通过移除不相关部分解决了这些问题，但现有方法在广泛场景下表现有限。为此，我们提出了Provence，一个高效且鲁棒的问答上下文修剪器，能够动态调整修剪量，并适用于多种领域。Provence的核心在于将上下文修剪任务形式化为序列标注、统一修剪与重排序能力，并在多样化数据上训练。实验表明，Provence在各种场景下实现了高效的上下文修剪，性能几乎无损，且成本极低。我们还通过深入分析和消融实验，为未来上下文修剪器的训练提供了宝贵见解。

> Retrieval-augmented generation improves various aspects of large language models (LLMs) generation, but suffers from computational overhead caused by long contexts as well as the propagation of irrelevant retrieved information into generated responses. Context pruning deals with both aspects, by removing irrelevant parts of retrieved contexts before LLM generation. Existing context pruning approaches are however limited, and do not provide a universal model that would be both efficient and robust in a wide range of scenarios, e.g., when contexts contain a variable amount of relevant information or vary in length, or when evaluated on various domains. In this work, we close this gap and introduce Provence (Pruning and Reranking Of retrieVEd relevaNt ContExts), an efficient and robust context pruner for Question Answering, which dynamically detects the needed amount of pruning for a given context and can be used out-of-the-box for various domains. The three key ingredients of Provence are formulating the context pruning task as sequence labeling, unifying context pruning capabilities with context reranking, and training on diverse data. Our experimental results show that Provence enables context pruning with negligible to no drop in performance, in various domains and settings, at almost no cost in a standard RAG pipeline. We also conduct a deeper analysis alongside various ablations to provide insights into training context pruners for future work.

[Arxiv](https://arxiv.org/abs/2501.16214)