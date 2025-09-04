# 通过双向重构提升大型语言模型（LLMs）的文本嵌入能力

发布时间：2025年09月03日

`LLM应用` `基础理论`

> Training LLMs to be Better Text Embedders through Bidirectional Reconstruction

# 摘要

> 大型语言模型（LLMs）作为高效的文本嵌入工具，其应用探索正不断深入。现有基于LLM的文本嵌入方法多采用最后一个标记的嵌入结果——通常是像[EOS]这样的预留特殊标记。但这些标记并未经过针对性训练来捕捉完整上下文语义，因此在作为文本嵌入时性能受限，尤其在检索和重排序任务中表现不佳。为此，我们提出在对比学习前新增一个训练阶段，用以增强最后一个标记嵌入的语义表达。该阶段引入双向生成重构任务，即EBQ2D（基于嵌入的查询到文档）与EBD2Q（基于嵌入的文档到查询），通过交替执行来锚定[EOS]嵌入，并重构查询-文档对的任意一侧内容。实验结果显示，新增的训练阶段大幅提升了LLM在大规模文本嵌入基准（MTEB）上的表现，在不同基础模型和规模的LLM上均刷新了当前最优结果。

> Large language models (LLMs) have increasingly been explored as powerful text embedders. Existing LLM-based text embedding approaches often leverage the embedding of the final token, typically a reserved special token such as [EOS]. However, these tokens have not been intentionally trained to capture the semantics of the whole context, limiting their capacity as text embeddings, especially for retrieval and re-ranking tasks. We propose to add a new training stage before contrastive learning to enrich the semantics of the final token embedding. This stage employs bidirectional generative reconstruction tasks, namely EBQ2D (Embedding-Based Query-to-Document) and EBD2Q (Embedding-Based Document-to-Query), which interleave to anchor the [EOS] embedding and reconstruct either side of Query-Document pairs. Experimental results demonstrate that our additional training stage significantly improves LLM performance on the Massive Text Embedding Benchmark (MTEB), achieving new state-of-the-art results across different LLM base models and scales.

[Arxiv](https://arxiv.org/abs/2509.03020)