# Birdie: 基于可微分搜索索引的自然语言驱动表发现

发布时间：2025年04月29日

`LLM应用` `数据分析`

> Birdie: Natural Language-Driven Table Discovery Using Differentiable Search Index

# 摘要

> 自然语言（NL）驱动的表格发现方法能够根据自然语言查询从大规模表格仓库中精准识别相关表格。尽管当前基于深度学习的方法利用传统的密集向量搜索管道（即表示-索引-搜索）实现了显著的准确性，但它们仍然面临几个关键限制：(i) 表格表示和索引阶段的累积错误会影响后续搜索的准确性；(ii) 查询与表格之间交互不足，阻碍了有效的语义对齐，从而限制了准确性的提升。在本文中，我们提出了一种名为Birdie的新颖框架，采用可微分搜索索引。它将索引和搜索过程统一到一个编码器-解码器语言模型中，从而避免了错误的累积。Birdie首先为每个表格分配一个前缀感知标识符，并利用基于大型语言模型的查询生成器为每个表格创建合成查询。然后，它将合成查询/表格与其对应的表格标识符之间的映射编码到编码器-解码器语言模型的参数中，从而实现深度的查询-表格交互。在搜索过程中，训练好的模型可以直接为给定的查询生成表格标识符。为了支持动态表格的持续索引，我们引入了一种通过参数隔离实现的索引更新策略，以缓解灾难性遗忘的问题。大量实验表明，Birdie在准确性方面比最先进的密集方法高出16.8%，并且与其它持续学习方法相比，遗忘率降低了90%以上。

> Natural language (NL)-driven table discovery identifies relevant tables from large table repositories based on NL queries. While current deep-learning-based methods using the traditional dense vector search pipeline, i.e., representation-index-search, achieve remarkable accuracy, they face several limitations that impede further performance improvements: (i) the errors accumulated during the table representation and indexing phases affect the subsequent search accuracy; and (ii) insufficient query-table interaction hinders effective semantic alignment, impeding accuracy improvements. In this paper, we propose a novel framework Birdie, using a differentiable search index. It unifies the indexing and search into a single encoder-decoder language model, thus getting rid of error accumulations. Birdie first assigns each table a prefix-aware identifier and leverages a large language model-based query generator to create synthetic queries for each table. It then encodes the mapping between synthetic queries/tables and their corresponding table identifiers into the parameters of an encoder-decoder language model, enabling deep query-table interactions. During search, the trained model directly generates table identifiers for a given query. To accommodate the continual indexing of dynamic tables, we introduce an index update strategy via parameter isolation, which mitigates the issue of catastrophic forgetting. Extensive experiments demonstrate that Birdie outperforms state-of-the-art dense methods by 16.8% in accuracy, and reduces forgetting by over 90% compared to other continual learning approaches.

[Arxiv](https://arxiv.org/abs/2504.21282)