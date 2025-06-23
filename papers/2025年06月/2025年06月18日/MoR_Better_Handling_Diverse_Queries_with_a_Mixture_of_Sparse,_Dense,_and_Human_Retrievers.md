# MoR：通过稀疏、密集与人工检索器的混合更高效地处理多样化查询

发布时间：2025年06月18日

`RAG` `信息检索` `问答系统`

> MoR: Better Handling Diverse Queries with a Mixture of Sparse, Dense, and Human Retrievers

# 摘要

> 检索增强生成（RAG）功能强大，但其效果取决于检索器的选择和使用方式。不同的检索器提供独特且互补的信号：BM25 捕捉词汇匹配，密集检索器则捕捉语义相似性。然而，实践中我们通常基于启发式固定使用单一检索器，这种方法无法很好地适应多样化的信息需求。能否为每个独立查询动态选择并整合多个检索器，而无需人工选择？在我们的研究中，我们通过定量分析验证了这一直觉，并引入了检索器混合：一种零样本、加权异构检索器组合。大量实验表明，这种混合方法既有效又高效。尽管总参数量仅为 0.8B，但与每个单一检索器相比，平均性能提升了 +10.8%，甚至超越了更大的 7B 模型，提升了 +3.9%。进一步分析还表明，这种混合框架可以帮助整合专业的非 oracle 人类信息源作为检索器，实现良好的协作，与仅模拟人类相比，相对性能提升了 58.9%。

> Retrieval-augmented Generation (RAG) is powerful, but its effectiveness hinges on which retrievers we use and how. Different retrievers offer distinct, often complementary signals: BM25 captures lexical matches; dense retrievers, semantic similarity. Yet in practice, we typically fix a single retriever based on heuristics, which fails to generalize across diverse information needs. Can we dynamically select and integrate multiple retrievers for each individual query, without the need for manual selection? In our work, we validate this intuition with quantitative analysis and introduce mixture of retrievers: a zero-shot, weighted combination of heterogeneous retrievers. Extensive experiments show that such mixtures are effective and efficient: Despite totaling just 0.8B parameters, this mixture outperforms every individual retriever and even larger 7B models by +10.8% and +3.9% on average, respectively. Further analysis also shows that this mixture framework can help incorporate specialized non-oracle human information sources as retrievers to achieve good collaboration, with a 58.9% relative performance improvement over simulated humans alone.

[Arxiv](https://arxiv.org/abs/2506.15862)