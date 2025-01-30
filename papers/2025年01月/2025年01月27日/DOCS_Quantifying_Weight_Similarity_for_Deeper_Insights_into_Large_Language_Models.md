# DOCS: 量化权重相似性，深入洞察大型语言模型

发布时间：2025年01月27日

`LLM理论` `人工智能` `机器学习`

> DOCS: Quantifying Weight Similarity for Deeper Insights into Large Language Models

# 摘要

> 我们提出了一种新指标——余弦相似度分布（DOCS），用于量化大型语言模型（LLMs）中权重矩阵的相似性，旨在简化其复杂架构的分析。通过DOCS，我们发现最新开源LLMs中一个有趣的现象：相邻层往往具有高度相似的权重，并形成集群，暗示了深度方向上的功能专业化。此外，我们证明了DOCS在理论上能有效量化正交矩阵的相似性，这一点尤为重要，因为LLMs中广泛使用正交初始化。这项研究深化了对LLM架构和行为的理解，并为开发更高效、可解释的模型提供了潜在工具。

> We introduce a novel index, the Distribution of Cosine Similarity (DOCS), for quantitatively assessing the similarity between weight matrices in Large Language Models (LLMs), aiming to facilitate the analysis of their complex architectures. Leveraging DOCS, our analysis uncovers intriguing patterns in the latest open-source LLMs: adjacent layers frequently exhibit high weight similarity and tend to form clusters, suggesting depth-wise functional specialization. Additionally, we prove that DOCS is theoretically effective in quantifying similarity for orthogonal matrices, a crucial aspect given the prevalence of orthogonal initializations in LLMs. This research contributes to a deeper understanding of LLM architecture and behavior, offering tools with potential implications for developing more efficient and interpretable models.

[Arxiv](https://arxiv.org/abs/2501.16650)