# HEAL：用于提升检索和表示学习的分层嵌入对齐损失

发布时间：2024年12月05日

`RAG` `医疗保健` `材料科学`

> HEAL: Hierarchical Embedding Alignment Loss for Improved Retrieval and Representation Learning

# 摘要

> 检索增强生成（RAG）通过整合外部文档检索，为大型语言模型（LLMs）提供特定领域或最新知识，以此增强其性能。RAG 的效果取决于所检索文档的相关性，而这又受嵌入与领域专业内容语义对齐的影响。虽然完全微调能让语言模型与特定领域适配，但计算成本高且需要大量数据。本文引入了分层嵌入对齐损失（HEAL）这一新颖方法，它在对比学习中借助分层模糊聚类和矩阵分解，高效地将 LLM 嵌入与特定领域内容对齐。HEAL 计算层级/深度的对比损失，并融入分层惩罚，使嵌入与标签层次结构中的底层关系相匹配。此方法提升了检索相关性和文档分类效果，有效减少了 LLM 输出中的幻觉。在实验中，我们在医疗保健、材料科学、网络安全和应用数学等多个领域对 HEAL 进行了基准测试和评估。

> Retrieval-Augmented Generation (RAG) enhances Large Language Models (LLMs) by integrating external document retrieval to provide domain-specific or up-to-date knowledge. The effectiveness of RAG depends on the relevance of retrieved documents, which is influenced by the semantic alignment of embeddings with the domain's specialized content. Although full fine-tuning can align language models to specific domains, it is computationally intensive and demands substantial data. This paper introduces Hierarchical Embedding Alignment Loss (HEAL), a novel method that leverages hierarchical fuzzy clustering with matrix factorization within contrastive learning to efficiently align LLM embeddings with domain-specific content. HEAL computes level/depth-wise contrastive losses and incorporates hierarchical penalties to align embeddings with the underlying relationships in label hierarchies. This approach enhances retrieval relevance and document classification, effectively reducing hallucinations in LLM outputs. In our experiments, we benchmark and evaluate HEAL across diverse domains, including Healthcare, Material Science, Cyber-security, and Applied Maths.

[Arxiv](https://arxiv.org/abs/2412.04661)