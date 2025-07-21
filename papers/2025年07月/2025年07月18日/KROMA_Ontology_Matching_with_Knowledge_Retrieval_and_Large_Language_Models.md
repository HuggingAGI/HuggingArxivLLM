# KROMA：融合知识检索与大型语言模型的本体匹配技术

发布时间：2025年07月18日

`RAG` `语义技术` `知识工程`

> KROMA: Ontology Matching with Knowledge Retrieval and Large Language Models

# 摘要

> 本体匹配（OM）是语义互操作性的基石，但现有系统往往依赖于手工规则或适应性有限的专用模型。我们推出KROMA——一个创新的OM框架，它在检索增强生成（RAG）管道中巧妙运用大型语言模型（LLMs），通过结构化、词汇和定义性知识动态丰富OM任务的语义上下文。为优化性能与效率，KROMA整合了基于双相似性的概念匹配和轻量级本体优化步骤，有效筛选候选概念并大幅减少LLMs调用的通信开销。通过在多个基准数据集上的实验证明，结合知识检索与上下文增强的LLMs显著提升了本体匹配效果，不仅超越了传统OM系统，还优于前沿的LLM方法，同时保持了可比的通信效率。本研究凸显了定向知识检索、提示增强和本体优化等优化技术在大规模本体匹配中的巨大潜力与显著优势。

> Ontology Matching (OM) is a cornerstone task of semantic interoperability, yet existing systems often rely on handcrafted rules or specialized models with limited adaptability. We present KROMA, a novel OM framework that harnesses Large Language Models (LLMs) within a Retrieval-Augmented Generation (RAG) pipeline to dynamically enrich the semantic context of OM tasks with structural, lexical, and definitional knowledge. To optimize both performance and efficiency, KROMA integrates a bisimilarity-based concept matching and a lightweight ontology refinement step, which prune candidate concepts and substantially reduce the communication overhead from invoking LLMs. Through experiments on multiple benchmark datasets, we show that integrating knowledge retrieval with context-augmented LLMs significantly enhances ontology matching, outperforming both classic OM systems and cutting-edge LLM-based approaches while keeping communication overhead comparable. Our study highlights the feasibility and benefit of the proposed optimization techniques (targeted knowledge retrieval, prompt enrichment, and ontology refinement) for ontology matching at scale.

[Arxiv](https://arxiv.org/abs/2507.14032)