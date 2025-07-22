# Docopilot：优化多模态模型，提升文档级理解能力

发布时间：2025年07月19日

`LLM应用` `文档处理` `多模态`

> Docopilot: Improving Multimodal Models for Document-Level Understanding

# 摘要

> 尽管多模态大型语言模型（MLLMs）取得了显著进展，但它们在处理复杂多页文档理解任务上的表现仍然不尽如人意，这主要归因于缺乏高质量的文档级别数据集。当前的检索增强生成（RAG）方法虽然提供了一些解决方案，但仍然面临检索上下文碎片化、多阶段误差累积以及检索带来的额外时间成本等挑战。在本研究中，我们推出一个高质量的文档级别数据集Doc-750K，旨在支持对多模态文档的深入理解。该数据集包含多样化的文档结构、广泛的跨页依赖关系以及从原始文档中提取的真实问答对。基于此数据集，我们开发了一个原生的多模态模型Docopilot，它能够准确处理文档级别的依赖关系，无需依赖RAG方法。实验结果表明，Docopilot在文档理解任务和多轮交互中展现了卓越的连贯性、准确性和效率，为文档级别的多模态理解设定了新的基准。数据、代码和模型已在GitHub上开放，链接为https://github.com/OpenGVLab/Docopilot

> Despite significant progress in multimodal large language models (MLLMs), their performance on complex, multi-page document comprehension remains inadequate, largely due to the lack of high-quality, document-level datasets. While current retrieval-augmented generation (RAG) methods offer partial solutions, they suffer from issues, such as fragmented retrieval contexts, multi-stage error accumulation, and extra time costs of retrieval. In this work, we present a high-quality document-level dataset, Doc-750K, designed to support in-depth understanding of multimodal documents. This dataset includes diverse document structures, extensive cross-page dependencies, and real question-answer pairs derived from the original documents. Building on the dataset, we develop a native multimodal model, Docopilot, which can accurately handle document-level dependencies without relying on RAG. Experiments demonstrate that Docopilot achieves superior coherence, accuracy, and efficiency in document understanding tasks and multi-turn interactions, setting a new baseline for document-level multimodal understanding. Data, code, and models are released at https://github.com/OpenGVLab/Docopilot

[Arxiv](https://arxiv.org/abs/2507.14675)