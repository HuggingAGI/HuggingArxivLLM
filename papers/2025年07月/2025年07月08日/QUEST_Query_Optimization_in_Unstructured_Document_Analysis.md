# QUEST：非结构化文档分析中的查询优化

发布时间：2025年07月08日

`LLM应用` `数据系统` `数据库`

> QUEST: Query Optimization in Unstructured Document Analysis

# 摘要

> 最近，研究人员开始构建由大型语言模型（LLMs）驱动的数据系统，使用户能够像使用数据库一样分析非结构化文本文档。由于LLMs在从文档中提取属性方面非常有效，因此这些系统允许用户进行类似的分析。然而，在这些系统中，基于LLM的提取操作构成了查询执行的性能瓶颈，原因在于高昂的经济成本和缓慢的LLM推理速度。现有系统通常借用在关系型数据库中广受欢迎的查询优化原则来生成查询执行计划，但这些方法在最小化LLM成本方面效果不佳。为填补这一空白，我们提出了QUEST，它为非结构化文档分析提供了一系列新颖的优化策略。首先，我们引入了一种基于索引的策略，以最小化每次提取操作的成本。通过这一索引，QUEST能够快速检索与目标属性相关的文本片段，并仅将这些片段输入LLMs。此外，我们设计了一种增强型检索策略，以降低遗漏相关片段的可能性。而且，我们开发了一种针对实例的优化查询执行策略：由于属性提取成本在不同文档间可能有显著差异，QUEST会为不同文档生成不同的执行计划。对于每份文档，QUEST都会制定一个计划，以尽量减少属性提取的频率。创新点包括考虑LLM成本的操作符顺序策略，以及一种优化的连接执行方法，该方法将连接转换为过滤操作。在3个真实世界数据集上的广泛实验表明，QUEST优于现有的先进基线，实现了30%-6倍的成本节省，同时将F1分数提高了10%-27%。

> Most recently, researchers have started building large language models (LLMs) powered data systems that allow users to analyze unstructured text documents like working with a database because LLMs are very effective in extracting attributes from documents. In such systems, LLM-based extraction operations constitute the performance bottleneck of query execution due to the high monetary cost and slow LLM inference. Existing systems typically borrow the query optimization principles popular in relational databases to produce query execution plans, which unfortunately are ineffective in minimizing LLM cost. To fill this gap, we propose QUEST, which features a bunch of novel optimization strategies for unstructured document analysis. First, we introduce an index-based strategy to minimize the cost of each extraction operation. With this index, QUEST quickly retrieves the text segments relevant to the target attributes and only feeds them to LLMs. Furthermore, we design an evidence-augmented retrieval strategy to reduce the possibility of missing relevant segments. Moreover, we develop an instance-optimized query execution strategy: because the attribute extraction cost could vary significantly document by document, QUEST produces different plans for different documents. For each document, QUEST produces a plan to minimize the frequency of attribute extraction. The innovations include LLM cost-aware operator ordering strategies and an optimized join execution approach that transforms joins into filters. Extensive experiments on 3 real-world datasets demonstrate the superiority of QUEST, achieving 30%-6x cost savings while improving the F1 score by 10% -27% compared with state-of-the-art baselines.

[Arxiv](https://arxiv.org/abs/2507.06515)