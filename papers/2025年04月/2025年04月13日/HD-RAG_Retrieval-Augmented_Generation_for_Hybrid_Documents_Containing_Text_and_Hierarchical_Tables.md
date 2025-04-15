# HD-RAG：一种用于包含文本和层级表格的混合文档的基于检索增强的生成方法。

发布时间：2025年04月13日

`RAG` `问答系统` `数据集`

> HD-RAG: Retrieval-Augmented Generation for Hybrid Documents Containing Text and Hierarchical Tables

# 摘要

> 大型语言模型（LLMs）的快速发展推动了检索增强生成（RAG）技术的演进，使其能够将生成能力与外部信息检索相结合。混合文档RAG任务旨在整合文本与层级化表格数据，以实现更全面的检索与生成，尤其在复杂场景下。然而，目前尚无专门为此任务设计、同时包含文本和表格数据的数据集。现有方法在检索相关表格数据并将其与文本整合方面存在诸多挑战：基于语义相似度的检索不够精准，而专门针对表格的方法又难以有效处理复杂层级结构。此外，问答任务往往需要复杂的推理与计算，进一步加剧了这些挑战。为此，我们提出了DocRAGLib，一个专为混合文档RAG场景下的问答任务设计的大规模数据集。同时，我们开发了HD-RAG框架，通过引入行和列级别的（RCL）表格表示、结合集成与基于LLMs的检索的两阶段流程，并整合专为文档问答任务设计的多步骤推理与复杂计算组件RECAP，有效应对上述挑战。实验结果表明，HD-RAG在检索准确性和问答性能上均显著优于现有基线，充分证明了其有效性。

> With the rapid advancement of large language models (LLMs), Retrieval-Augmented Generation (RAG) effectively combines LLMs generative capabilities with external retrieval-based information. The Hybrid Document RAG task aims to integrate textual and hierarchical tabular data for more comprehensive retrieval and generation in complex scenarios. However, there is no existing dataset specifically designed for this task that includes both text and tabular data. Additionally, existing methods struggle to retrieve relevant tabular data and integrate it with text. Semantic similarity-based retrieval lacks accuracy, while table-specific methods fail to handle complex hierarchical structures effectively. Furthermore, the QA task requires complex reasoning and calculations, further complicating the challenge. In this paper, we propose a new large-scale dataset, DocRAGLib, specifically designed for the question answering (QA) task scenario under Hybrid Document RAG. To tackle these challenges, we introduce HD-RAG, a novel framework that incorporates a row-and-column level (RCL) table representation, employs a two-stage process combining ensemble and LLM-based retrieval, and integrates RECAP, which is designed for multi-step reasoning and complex calculations in Document-QA tasks. We conduct comprehensive experiments with DocRAGLib, showing that HD-RAG outperforms existing baselines in both retrieval accuracy and QA performance, demonstrating its effectiveness.

[Arxiv](https://arxiv.org/abs/2504.09554)