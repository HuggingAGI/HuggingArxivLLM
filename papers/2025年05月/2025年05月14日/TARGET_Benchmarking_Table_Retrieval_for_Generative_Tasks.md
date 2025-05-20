# 目标：面向生成任务的表格检索基准评估

发布时间：2025年05月14日

`RAG` `数据分析` `数据管理`

> TARGET: Benchmarking Table Retrieval for Generative Tasks

# 摘要

> 结构化数据在数据领域中丰富多样，通常对组织具有重要价值，推动了数据分析和机器学习中的重要应用。针对结构化数据的表示学习和生成模型的最新进展，推动了自然语言界面的开发，包括那些利用文本到SQL的技术。通过检索增强生成，在结构化数据中实现情境化的交互（无论是通过对话界面还是智能体组件），都能显著提升回答的新鲜度、准确性和全面性。关键问题是：如何为当前的分析查询或任务检索到合适的表格？为此，我们引入了TARGET：一个用于评估生成任务中表格检索能力的基准。通过TARGET，我们分析了不同检索器在孤立情况下的检索性能，以及它们对下游任务的影响。我们发现，基于密集嵌入的检索器远超BM25基线，而BM25在结构化数据检索中的效果不如其在非结构化文本中的表现。我们还揭示了检索器在各种元数据（例如缺少表标题）上的敏感性，并展示了不同数据集和任务中检索性能的巨大差异。TARGET可在https://target-benchmark.github.io访问。

> The data landscape is rich with structured data, often of high value to organizations, driving important applications in data analysis and machine learning. Recent progress in representation learning and generative models for such data has led to the development of natural language interfaces to structured data, including those leveraging text-to-SQL. Contextualizing interactions, either through conversational interfaces or agentic components, in structured data through retrieval-augmented generation can provide substantial benefits in the form of freshness, accuracy, and comprehensiveness of answers. The key question is: how do we retrieve the right table(s) for the analytical query or task at hand? To this end, we introduce TARGET: a benchmark for evaluating TAble Retrieval for GEnerative Tasks. With TARGET we analyze the retrieval performance of different retrievers in isolation, as well as their impact on downstream tasks. We find that dense embedding-based retrievers far outperform a BM25 baseline which is less effective than it is for retrieval over unstructured text. We also surface the sensitivity of retrievers across various metadata (e.g., missing table titles), and demonstrate a stark variation of retrieval performance across datasets and tasks. TARGET is available at https://target-benchmark.github.io.

[Arxiv](https://arxiv.org/abs/2505.11545)