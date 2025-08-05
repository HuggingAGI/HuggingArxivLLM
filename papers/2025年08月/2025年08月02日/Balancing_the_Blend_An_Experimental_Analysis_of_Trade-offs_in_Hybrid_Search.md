# 混合搜索的平衡之道：权衡的实验研究

发布时间：2025年08月02日

`RAG` `信息检索`

> Balancing the Blend: An Experimental Analysis of Trade-offs in Hybrid Search

# 摘要

> 混合搜索——将词汇和语义检索相结合——已成为现代信息检索系统的重要基石，这一趋势受到如检索增强生成（RAG）等高需求应用的推动。尽管这些系统的架构设计空间广阔且复杂，但目前对于其核心组件——检索范式、组合方案和重排序方法之间的权衡关系，仍缺乏系统性的实证理解。基于我们在构建Infinity开源数据库的经验，我们提出了首个针对先进混合搜索架构的系统性基准测试。我们的框架评估了四种检索范式——全文搜索（FTS）、稀疏向量搜索（SVS）、稠密向量搜索（DVS）和张量搜索（TenS）——并在11个真实世界数据集上对其组合和重排序策略进行了全面测试。研究结果为实践者和研究者揭示了三个关键发现：(1) “最弱环节”现象：单个表现不佳的检索路径可能严重降低整体准确性，强调了在融合前进行路径级质量评估的必要性。(2) 数据驱动的性能权衡图谱：展示了最优配置在很大程度上取决于资源约束和数据特性，超越了“一刀切”的方法。(3) 张量基重排序融合（TRF）：识别为一种高效替代主流融合方法的方案，它以极低的计算和内存成本提供了张量搜索的语义能力。这些发现不仅为设计下一代自适应、可扩展的混合搜索系统提供了具体指导，同时也为未来研究指明了关键方向。

> Hybrid search, the integration of lexical and semantic retrieval, has become a cornerstone of modern information retrieval systems, driven by demanding applications like Retrieval-Augmented Generation (RAG). The architectural design space for these systems is vast and complex, yet a systematic, empirical understanding of the trade-offs among their core components--retrieval paradigms, combination schemes, and re-ranking methods--is critically lacking. To address this, and informed by our experience building the Infinity open-source database, we present the first systematic benchmark of advanced hybrid search architectures. Our framework evaluates four retrieval paradigms--Full-Text Search (FTS), Sparse Vector Search (SVS), Dense Vector Search (DVS), and Tensor Search (TenS)--benchmarking their combinations and re-ranking strategies across 11 real-world datasets. Our results reveal three key findings for practitioners and researchers: (1) A "weakest link" phenomenon, where a single underperforming retrieval path can disproportionately degrade overall accuracy, highlighting the need for path-wise quality assessment before fusion. (2) A data-driven map of the performance trade-offs, demonstrating that optimal configurations depend heavily on resource constraints and data characteristics, moving beyond a one-size-fits-all approach. (3) The identification of Tensor-based Re-ranking Fusion (TRF) as a high-efficacy alternative to mainstream fusion methods, offering the semantic power of tensor search at a fraction of the computational and memory cost. Our findings offer concrete guidelines for designing the next generation of adaptive, scalable hybrid search systems while also identifying key directions for future research.

[Arxiv](https://arxiv.org/abs/2508.01405)