# 通用型文本嵌入在零样本推荐与搜索中的应用评估：真的需要专业化吗？

发布时间：2025年07月07日

`LLM应用`

> Do We Really Need Specialization? Evaluating Generalist Text Embeddings for Zero-Shot Recommendation and Search

# 摘要

> 预训练语言模型（PLMs）在推荐和搜索中被广泛用于提取项目元数据的语义表示。在序列推荐中，它们通过文本元数据增强基于ID的嵌入；而在产品搜索中，则将项目特征与用户意图对齐。尽管近期研究表明特定任务和领域的微调有助于提升表示能力，但本文对此提出挑战。我们发现，通用文本嵌入模型（GTEs）在大规模语料库上预训练后，无需专门适配即可实现强大的零样本性能。实验结果表明，GTEs在序列推荐和产品搜索中均超越传统模型和微调模型。这得益于其更强大的表示能力，GTEs在嵌入空间中更均匀地分布特征。此外，我们发现通过关注最具信息量的方向（如PCA）压缩嵌入维度，可有效降低噪声并提升专用模型的性能。为确保研究的可重复性，我们开源了代码库：https://split.to/gte4ps。


> Pre-trained language models (PLMs) are widely used to derive semantic representations from item metadata in recommendation and search. In sequential recommendation, PLMs enhance ID-based embeddings through textual metadata, while in product search, they align item characteristics with user intent. Recent studies suggest task and domain-specific fine-tuning are needed to improve representational power. This paper challenges this assumption, showing that Generalist Text Embedding Models (GTEs), pre-trained on large-scale corpora, can guarantee strong zero-shot performance without specialized adaptation. Our experiments demonstrate that GTEs outperform traditional and fine-tuned models in both sequential recommendation and product search. We attribute this to a superior representational power, as they distribute features more evenly across the embedding space. Finally, we show that compressing embedding dimensions by focusing on the most informative directions (e.g., via PCA) effectively reduces noise and improves the performance of specialized models. To ensure reproducibility, we provide our repository at https://split.to/gte4ps.

[Arxiv](https://arxiv.org/abs/2507.05006)