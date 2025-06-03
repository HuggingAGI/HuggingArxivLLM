# # 重新思考混合检索：小嵌入+LLM重排，轻松超越大模型

发布时间：2025年05月28日

`RAG` `信息检索` `问答系统`

> Rethinking Hybrid Retrieval: When Small Embeddings and LLM Re-ranking Beat Bigger Models

# 摘要

> 本文研究了三模态混合检索中嵌入模型的比较，应用于生成增强的检索系统（RAG）。我们探讨了密集语义、稀疏词法和基于图的嵌入融合，重点关注MiniLM-v6和BGE-Large架构的性能表现。与传统假设相反，我们的实验结果表明，在与基于LLM的重排序集成于我们的三模态混合框架中时，紧凑的MiniLM-v6表现优于更大的BGE-Large。在SciFact、FIQA和NFCorpus数据集上的实验结果显示，采用MiniLM-v6配置可显著提升检索质量。特别是在智能体重排序场景中，性能差异尤为明显，表明MiniLM-v6的嵌入空间与LLM推理有更好的对齐。我们的研究结果表明，RAG系统中嵌入模型的选择应优先考虑与多信号融合及与LLM的对齐，而不仅仅依赖于模型的大小。这种方法不仅能够提高检索准确性和效率，还可能降低计算需求。

> This paper presents a comparison of embedding models in tri-modal hybrid retrieval for Retrieval-Augmented Generation (RAG) systems. We investigate the fusion of dense semantic, sparse lexical, and graph-based embeddings, focusing on the performance of the MiniLM-v6 and BGE-Large architectures. Contrary to conventional assumptions, our results show that the compact MiniLM-v6 outperforms the larger BGE-Large when integrated with LLM-based re-ranking within our tri-modal hybrid framework. Experiments conducted on the SciFact, FIQA, and NFCorpus datasets demonstrate significant improvements in retrieval quality with the MiniLM-v6 configuration. The performance difference is particularly pronounced in agentic re-ranking scenarios, indicating better alignment between MiniLM-v6's embedding space and LLM reasoning. Our findings suggest that embedding model selection for RAG systems should prioritize compatibility with multi-signal fusion and LLM alignment, rather than relying solely on larger models. This approach may reduce computational requirements while improving retrieval accuracy and efficiency.

[Arxiv](https://arxiv.org/abs/2506.00049)