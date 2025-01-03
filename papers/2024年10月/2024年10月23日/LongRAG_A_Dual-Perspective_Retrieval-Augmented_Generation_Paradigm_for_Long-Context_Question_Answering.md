# LongRAG: 长上下文问答的双视角检索增强生成范式

发布时间：2024年10月23日

`RAG

理由：这篇论文主要讨论了如何通过改进检索增强生成（RAG）系统来解决长上下文问答（LCQA）中的问题。论文提出了LongRAG，一种基于LLM的RAG系统范式，旨在提升RAG对复杂长上下文知识的理解。因此，这篇论文的核心内容与RAG相关，应归类为RAG。` `问答系统`

> LongRAG: A Dual-Perspective Retrieval-Augmented Generation Paradigm for Long-Context Question Answering

# 摘要

> # 长上下文问答（LCQA）
长上下文问答（LCQA）是一项颇具挑战的任务，旨在通过对长文档的推理生成准确答案。现有的长上下文LLMs常受困于“迷失在中间”的问题。检索增强生成（RAG）通过引入外部事实证据缓解了这一问题，但其分块策略破坏了全局上下文信息，且长上下文中的低质量检索因噪声过多阻碍了LLMs识别有效细节。为此，我们提出了LongRAG，一种通用、双视角、基于LLM的RAG系统范式，旨在提升RAG对复杂长上下文知识（全局信息与事实细节）的理解。LongRAG设计为即插即用，便于适配不同领域和LLMs。在三个多跳数据集上的实验表明，LongRAG显著优于长上下文LLMs（提升6.94%）、先进RAG（提升6.16%）和Vanilla RAG（提升17.25%）。此外，我们通过定量消融研究和多维分析，验证了系统组件与微调策略的有效性。数据和代码详见https://github.com/QingFei1/LongRAG。

> Long-Context Question Answering (LCQA), a challenging task, aims to reason over long-context documents to yield accurate answers to questions. Existing long-context Large Language Models (LLMs) for LCQA often struggle with the "lost in the middle" issue. Retrieval-Augmented Generation (RAG) mitigates this issue by providing external factual evidence. However, its chunking strategy disrupts the global long-context information, and its low-quality retrieval in long contexts hinders LLMs from identifying effective factual details due to substantial noise. To this end, we propose LongRAG, a general, dual-perspective, and robust LLM-based RAG system paradigm for LCQA to enhance RAG's understanding of complex long-context knowledge (i.e., global information and factual details). We design LongRAG as a plug-and-play paradigm, facilitating adaptation to various domains and LLMs. Extensive experiments on three multi-hop datasets demonstrate that LongRAG significantly outperforms long-context LLMs (up by 6.94%), advanced RAG (up by 6.16%), and Vanilla RAG (up by 17.25%). Furthermore, we conduct quantitative ablation studies and multi-dimensional analyses, highlighting the effectiveness of the system's components and fine-tuning strategies. Data and code are available at https://github.com/QingFei1/LongRAG.

[Arxiv](https://arxiv.org/abs/2410.18050)