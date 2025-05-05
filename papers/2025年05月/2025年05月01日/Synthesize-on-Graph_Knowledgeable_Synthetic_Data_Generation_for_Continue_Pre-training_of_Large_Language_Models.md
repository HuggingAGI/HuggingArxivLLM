# 基于图的合成数据生成：为大规模语言模型的持续预训练提供知识导向的合成数据

发布时间：2025年05月01日

`LLM应用` `数据生成`

> Synthesize-on-Graph: Knowledgeable Synthetic Data Generation for Continue Pre-training of Large Language Models

# 摘要

> 大型语言模型（LLMs）虽然取得了显著成功，但在处理小型、专业化的语料库时仍显数据低效，尤其在数据有限且专有的情况下。现有用于持续预训练的合成数据生成方法多关注文档内部内容，忽视跨文档知识关联，导致内容多样性和深度受限。为此，我们提出了一种名为Synthetic-on-Graph（SoG）的合成数据生成框架，通过整合跨文档知识关联实现高效的语料库扩展。SoG通过从原始语料库中提取实体和概念，构建跨文档关联图，并采用图游走策略进行知识关联采样，从而提升合成数据的多样性和连贯性，帮助模型学习复杂知识结构并处理罕见知识。为了进一步优化合成数据质量，我们引入Chain-of-Thought（CoT）和Contrastive Clarifying（CC）合成方法，增强推理过程和判别能力。实验结果表明，SoG在多跳文档问答数据集上超越现有最优方法（SOTA），并在阅读理解任务数据集上与SOTA方法表现相当，凸显了其出色的泛化能力。我们的研究推动了合成数据生成领域的发展，为大型语言模型在数据有限领域的高效知识获取提供了实用解决方案。

> Large Language Models (LLMs) have achieved remarkable success but remain data-inefficient, especially when learning from small, specialized corpora with limited and proprietary data. Existing synthetic data generation methods for continue pre-training focus on intra-document content and overlook cross-document knowledge associations, limiting content diversity and depth. We propose Synthetic-on-Graph (SoG), a synthetic data generation framework that incorporates cross-document knowledge associations for efficient corpus expansion. SoG constructs a context graph by extracting entities and concepts from the original corpus, representing cross-document associations, and employing a graph walk strategy for knowledge-associated sampling. This enhances synthetic data diversity and coherence, enabling models to learn complex knowledge structures and handle rare knowledge. To further improve synthetic data quality, we integrate Chain-of-Thought (CoT) and Contrastive Clarifying (CC) synthetic, enhancing reasoning processes and discriminative power. Experiments show that SoG outperforms the state-of-the-art (SOTA) method in a multi-hop document Q&A dataset while performing comparably to the SOTA method on the reading comprehension task datasets, which also underscores the better generalization capability of SoG. Our work advances synthetic data generation and provides practical solutions for efficient knowledge acquisition in LLMs, especially in domains with limited data availability.

[Arxiv](https://arxiv.org/abs/2505.00979)