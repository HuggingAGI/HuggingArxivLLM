# RAG 与微调：基于 LCMs 的工业代码补全对比研究

发布时间：2025年05月21日

`LLM应用` `软件工程`

> RAG or Fine-tuning? A Comparative Study on LCMs-based Code Completion in Industry

# 摘要

> 代码补全在工业界是一项关键实践，它通过在开发过程中自动建议代码片段，帮助开发人员提高编程效率。随着大型代码模型（LCMs）的出现，这一领域取得了显著进展。由于开源代码库与工业代码库之间在编码模式和内部依赖等方面的固有差异，开发人员在工业界采用 LCMs 时通常会进行领域适应。存在多种适应方法，其中检索增强生成（RAG）和微调（FT）是最流行的两种范式。然而，此前没有研究探讨过这两种方法在工业场景中的权衡。  为了弥补这一差距，我们在本文中对工业代码补全的两种范式——检索增强生成（RAG）和微调（FT）进行了全面比较。我们与腾讯的WXG部门合作，收集了超过16万份内部C++文件作为我们的代码库。然后，我们使用六种 LCMs 从工业从业者关心的三个维度对这两种适应方法进行了比较，包括有效性、效率和参数敏感性。我们的研究发现，当使用适当的嵌入模型将代码片段映射到密集向量表示时，RAG 可以比单独微调实现更高的准确率。具体来说，在研究的 RAG 方法中，BM25 在检索效果和效率方面表现更优。此外，RAG 和微调是相互独立的，它们的结合可以进一步提升性能。我们还观察到，与 FT 相比，RAG 具有更好的可扩展性，随着代码库规模的增大，性能提升更加显著。

> Code completion, a crucial practice in industrial settings, helps developers improve programming efficiency by automatically suggesting code snippets during development. With the emergence of Large Code Models (LCMs), this field has witnessed significant advancements. Due to the natural differences between open-source and industrial codebases, such as coding patterns and unique internal dependencies, it is a common practice for developers to conduct domain adaptation when adopting LCMs in industry. There exist multiple adaptation approaches, among which retrieval-augmented generation (RAG) and fine-tuning are the two most popular paradigms. However, no prior research has explored the trade-off of the two approaches in industrial scenarios.
  To mitigate the gap, we comprehensively compare the two paradigms including Retrieval-Augmented Generation (RAG) and Fine-tuning (FT), for industrial code completion in this paper. In collaboration with Tencent's WXG department, we collect over 160,000 internal C++ files as our codebase. We then compare the two types of adaptation approaches from three dimensions that are concerned by industrial practitioners, including effectiveness, efficiency, and parameter sensitivity, using six LCMs. Our findings reveal that RAG, when implemented with appropriate embedding models that map code snippets into dense vector representations, can achieve higher accuracy than fine-tuning alone. Specifically, BM25 presents superior retrieval effectiveness and efficiency among studied RAG methods. Moreover, RAG and fine-tuning are orthogonal and their combination leads to further improvement. We also observe that RAG demonstrates better scalability than FT, showing more sustained performance gains with larger scales of codebase.

[Arxiv](https://arxiv.org/abs/2505.15179)