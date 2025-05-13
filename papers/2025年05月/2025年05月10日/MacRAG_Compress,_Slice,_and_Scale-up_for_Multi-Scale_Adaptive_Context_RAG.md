# MacRAG：压缩、切片与扩展，实现多尺度自适应上下文RAG

发布时间：2025年05月10日

`RAG` `问答系统`

> MacRAG: Compress, Slice, and Scale-up for Multi-Scale Adaptive Context RAG

# 摘要

> 长上下文（LC）大型语言模型（LLMs）与检索增强生成（RAG）的结合，在处理复杂多跳和大文档任务时展现出巨大潜力。然而，现有RAG系统在实际应用中常常面临三大挑战：检索不精准、受限上下文窗口下的覆盖不完整，以及信息碎片化问题。为了解决这些问题，我们提出了多尺度自适应上下文RAG（MacRAG），这是一种创新的分层检索框架。MacRAG通过将文档压缩并划分为从粗到细的不同粒度，然后实时进行块级和文档级扩展，自适应地合并相关上下文。其独特之处在于从最精细级别的检索开始，逐步整合更高级别和更广泛的上下文，从而构建出既精准又覆盖全面的查询特定长上下文。在HotpotQA、2WikiMultihopQA和Musique的LongBench扩展数据集上的实验结果表明，MacRAG在Llama-3.1-8B、Gemini-1.5-pro和GPT-4o模型上，均显著超越了传统RAG管道在单步和多步生成任务中的表现。这充分证明了MacRAG是一种高效且可扩展的解决方案，能够很好地应对现实世界中的长上下文多跳推理需求。我们的代码已在GitHub上开源，地址为https://github.com/Leezekun/MacRAG。

> Long-context (LC) Large Language Models (LLMs) combined with Retrieval-Augmented Generation (RAG) hold strong potential for complex multi-hop and large-document tasks. However, existing RAG systems often suffer from imprecise retrieval, incomplete context coverage under constrained context windows, and fragmented information caused by suboptimal context construction. We introduce Multi-scale Adaptive Context RAG (MacRAG), a hierarchical retrieval framework that compresses and partitions documents into coarse-to-fine granularities, then adaptively merges relevant contexts through chunk- and document-level expansions in real time. By starting from the finest-level retrieval and progressively incorporating higher-level and broader context, MacRAG constructs effective query-specific long contexts, optimizing both precision and coverage. Evaluations on the challenging LongBench expansions of HotpotQA, 2WikiMultihopQA, and Musique confirm that MacRAG consistently surpasses baseline RAG pipelines on single- and multi-step generation with Llama-3.1-8B, Gemini-1.5-pro, and GPT-4o. Our results establish MacRAG as an efficient, scalable solution for real-world long-context, multi-hop reasoning. Our code is available at https://github.com/Leezekun/MacRAG.

[Arxiv](https://arxiv.org/abs/2505.06569)