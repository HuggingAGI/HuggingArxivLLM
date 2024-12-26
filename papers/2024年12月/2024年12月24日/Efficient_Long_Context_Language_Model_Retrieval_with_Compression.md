# 高效的长上下文语言模型检索及压缩

发布时间：2024年12月24日

`LLM应用` `信息检索` `语言模型`

> Efficient Long Context Language Model Retrieval with Compression

# 摘要

> 长上下文语言模型（LCLMs）已成为信息检索（IR）的新范式，能在单个上下文中处理整个语料库，直接摄取和检索信息，展现出超越传统稀疏和密集检索方法的潜力。但在检索的上下文中处理大量段落，计算成本高昂，推理时处理其表示更会延长处理时间。所以，我们致力于通过段落压缩，让 LCLM 检索更高效、更有效。具体来说，我们为 LCLM 检索提出了一种新的压缩方法，训练该方法在最大程度提高检索性能的同时，将压缩段落的长度最小化。为此，我们生成合成数据，自动创建压缩段落，并根据给定查询的检索成功情况标记为选择或拒绝，然后通过偏好优化用此数据训练提出的长上下文检索压缩模型（CoLoR），同时添加长度正则化损失以强制简洁。通过在 9 个数据集上的大量实验，我们表明 CoLoR 在将上下文大小压缩 1.91 倍的同时，检索性能提高了 6%。

> Long Context Language Models (LCLMs) have emerged as a new paradigm to perform Information Retrieval (IR), which enables the direct ingestion and retrieval of information by processing an entire corpus in their single context, showcasing the potential to surpass traditional sparse and dense retrieval methods. However, processing a large number of passages within in-context for retrieval is computationally expensive, and handling their representations during inference further exacerbates the processing time; thus, we aim to make LCLM retrieval more efficient and potentially more effective with passage compression. Specifically, we propose a new compression approach tailored for LCLM retrieval, which is trained to maximize the retrieval performance while minimizing the length of the compressed passages. To accomplish this, we generate the synthetic data, where compressed passages are automatically created and labeled as chosen or rejected according to their retrieval success for a given query, and we train the proposed Compression model for Long context Retrieval (CoLoR) with this data via preference optimization while adding the length regularization loss on top of it to enforce brevity. Through extensive experiments on 9 datasets, we show that CoLoR improves the retrieval performance by 6% while compressing the in-context size by a factor of 1.91.

[Arxiv](https://arxiv.org/abs/2412.18232)