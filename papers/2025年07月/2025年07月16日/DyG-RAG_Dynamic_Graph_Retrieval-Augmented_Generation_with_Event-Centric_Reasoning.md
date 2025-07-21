# DyG-RAG：基于事件中心推理的动态图检索增强生成

发布时间：2025年07月16日

`RAG` `时间推理` `检索增强生成`

> DyG-RAG: Dynamic Graph Retrieval-Augmented Generation with Event-Centric Reasoning

# 摘要

> 图检索增强生成已成为一种强大的范式，用于将大型语言模型与外部结构化知识相结合。然而，现有的图RAG方法在时间推理方面存在困难，因为它们无法建模现实世界事件不断演变的结构和顺序。在本研究中，我们引入了DyG-RAG，这是一种基于事件的动态图检索增强生成框架，旨在捕捉和推理嵌入在非结构化文本中的时间知识。

为了消除传统检索单元中的时间歧义，DyG-RAG提出了动态事件单元（DEUs），这些单元显式编码语义内容和精确的时间锚点，从而实现准确且可解释的时间感知检索。为了捕捉事件之间的时间和因果依赖关系，DyG-RAG通过连接共享实体且在时间上接近的DEUs构建事件图，支持高效且有意义的多跳推理。为了确保时间一致的生成，DyG-RAG引入了一个基于时间感知遍历的事件时间线检索管道，并提出了时间链式推理策略，用于生成基于时间的答案。

这一统一的管道使DyG-RAG能够检索连贯且按时间顺序排列的事件序列，并回答标准RAG系统无法解决的复杂、时间敏感的查询。在时间问答基准上的大量实验表明，DyG-RAG显著提高了三种典型时间推理问题的准确性和召回率，为更忠实和时间感知的生成铺平了道路。DyG-RAG可在https://github.com/RingBDStack/DyG-RAG获取。

> Graph Retrieval-Augmented Generation has emerged as a powerful paradigm for grounding large language models with external structured knowledge. However, existing Graph RAG methods struggle with temporal reasoning, due to their inability to model the evolving structure and order of real-world events. In this work, we introduce DyG-RAG, a novel event-centric dynamic graph retrieval-augmented generation framework designed to capture and reason over temporal knowledge embedded in unstructured text. To eliminate temporal ambiguity in traditional retrieval units, DyG-RAG proposes Dynamic Event Units (DEUs) that explicitly encode both semantic content and precise temporal anchors, enabling accurate and interpretable time-aware retrieval. To capture temporal and causal dependencies across events, DyG-RAG constructs an event graph by linking DEUs that share entities and occur close in time, supporting efficient and meaningful multi-hop reasoning. To ensure temporally consistent generation, DyG-RAG introduces an event timeline retrieval pipeline that retrieves event sequences via time-aware traversal, and proposes a Time Chain-of-Thought strategy for temporally grounded answer generation. This unified pipeline enables DyG-RAG to retrieve coherent, temporally ordered event sequences and to answer complex, time-sensitive queries that standard RAG systems cannot resolve. Extensive experiments on temporal QA benchmarks demonstrate that DyG-RAG significantly improves the accuracy and recall of three typical types of temporal reasoning questions, paving the way for more faithful and temporal-aware generation. DyG-RAG is available at https://github.com/RingBDStack/DyG-RAG.

[Arxiv](https://arxiv.org/abs/2507.13396)