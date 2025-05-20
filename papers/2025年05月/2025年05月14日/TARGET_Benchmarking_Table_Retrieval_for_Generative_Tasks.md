# 目标：为生成任务建立表格检索基准测试

发布时间：2025年05月14日

`RAG` `数据管理` `数据库`

> TARGET: Benchmarking Table Retrieval for Generative Tasks

# 摘要

> 结构化数据在数据领域中占据重要地位，其价值对组织推动数据分析和机器学习应用至关重要。近期，针对结构化数据的表征学习和生成模型取得显著进展，催生了包括文本到SQL在内的自然语言界面。通过检索增强生成，将上下文交互（无论是对话界面还是智能体组件）应用于结构化数据，可显著提升答案的新鲜度、准确性和全面性。关键问题在于：如何为当前分析任务精准检索到合适的表？为此，我们推出TARGET基准测试，专注于评估生成任务中的表检索能力。通过TARGET，我们不仅评估了不同检索器的孤立性能，还研究了它们对下游任务的影响。研究发现，基于稠密嵌入的检索器远超BM25基线，且在结构化文本检索中表现更优。此外，我们发现检索器对元数据（如缺少表标题）高度敏感，并在不同数据集和任务中展现出显著的性能差异。TARGET基准测试现已开放，访问https://target-benchmark.github.io即可获取。

> The data landscape is rich with structured data, often of high value to organizations, driving important applications in data analysis and machine learning. Recent progress in representation learning and generative models for such data has led to the development of natural language interfaces to structured data, including those leveraging text-to-SQL. Contextualizing interactions, either through conversational interfaces or agentic components, in structured data through retrieval-augmented generation can provide substantial benefits in the form of freshness, accuracy, and comprehensiveness of answers. The key question is: how do we retrieve the right table(s) for the analytical query or task at hand? To this end, we introduce TARGET: a benchmark for evaluating TAble Retrieval for GEnerative Tasks. With TARGET we analyze the retrieval performance of different retrievers in isolation, as well as their impact on downstream tasks. We find that dense embedding-based retrievers far outperform a BM25 baseline which is less effective than it is for retrieval over unstructured text. We also surface the sensitivity of retrievers across various metadata (e.g., missing table titles), and demonstrate a stark variation of retrieval performance across datasets and tasks. TARGET is available at https://target-benchmark.github.io.

[Arxiv](https://arxiv.org/abs/2505.11545)