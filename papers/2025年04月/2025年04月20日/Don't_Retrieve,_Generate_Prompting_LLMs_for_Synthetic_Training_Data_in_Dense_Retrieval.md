# 不要检索，要生成：通过提示工程为LLMs生成合成训练数据用于稠密检索

发布时间：2025年04月20日

`LLM应用` `信息检索`

> Don't Retrieve, Generate: Prompting LLMs for Synthetic Training Data in Dense Retrieval

# 摘要

> 传统的密集检索模型训练通常依赖于从文档语料库中通过BM25或交叉编码器（CE）等方法挖掘的困难负样本（HN），这些方法计算资源消耗大且需要完整的语料库访问。然而，传统方法在计算资源和语料库访问方面存在显著限制。本文提出了一种全新的端到端解决方案：首先利用大型语言模型（LLM）从段落中生成查询，然后仅基于该查询文本生成困难负样本。这种无语料库的负样本生成方法与传统技术形成鲜明对比。我们使用E5-Base和GTE-Base模型在多个BEIR基准数据集上对这一LLM查询→LLM HN方法进行了全面评估，并将其与传统的LLM查询→BM25 HN和LLM查询→CE HN流水线进行了对比。实验结果表明，全LLM流水线在nDCG@10、Precision@10和Recall@100等关键指标上达到了与BM25和计算密集型CE基线相同的性能水平。这一发现证明，我们的无语料库负样本生成方法在效果上与复杂且依赖语料库的传统挖掘技术相当，为训练高性能检索器提供了一条更简单、更高效的路径，同时保持了相同的结果质量。为方便研究，我们公开发布了包含所有三种方法的查询和困难负样本的数据集，访问链接为https://huggingface.co/collections/chungimungi/arxiv-hard-negatives-68027bbc601ff6cc8eb1f449。

> Training effective dense retrieval models often relies on hard negative (HN) examples mined from the document corpus via methods like BM25 or cross-encoders (CE), processes that can be computationally demanding and require full corpus access. This paper introduces a different approach, an end-to-end pipeline where a Large Language Model (LLM) first generates a query from a passage, and then generates a hard negative example using \emph{only} that query text. This corpus-free negative generation contrasts with standard mining techniques. We evaluated this \textsc{LLM Query $\rightarrow$ LLM HN} approach against traditional \textsc{LLM Query $\rightarrow$ BM25 HN} and \textsc{LLM Query $\rightarrow$ CE HN} pipelines using E5-Base and GTE-Base models on several BEIR benchmark datasets. Our results show the proposed all-LLM pipeline achieves performance identical to both the BM25 and the computationally intensive CE baselines across nDCG@10, Precision@10, and Recall@100 metrics. This demonstrates that our corpus-free negative generation method matches the effectiveness of complex, corpus-dependent mining techniques, offering a potentially simpler and more efficient pathway for training high-performance retrievers without sacrificing results. We make the dataset including the queries and the hard-negatives for all three methods publicly available https://huggingface.co/collections/chungimungi/arxiv-hard-negatives-68027bbc601ff6cc8eb1f449.

[Arxiv](https://arxiv.org/abs/2504.21015)