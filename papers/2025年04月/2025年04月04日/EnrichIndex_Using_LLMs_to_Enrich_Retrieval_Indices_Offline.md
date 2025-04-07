# EnrichIndex: 利用LLMs离线增强检索索引

发布时间：2025年04月04日

`LLM应用

摘要讨论了利用大型语言模型（LLMs）来改进信息检索系统的性能，特别是通过离线构建语义增强的索引来提升检索效率。这属于将LLM应用于具体任务（信息检索）的范畴，因此归类为LLM应用。` `信息检索` `文档处理`

> EnrichIndex: Using LLMs to Enrich Retrieval Indices Offline

# 摘要

> 现有信息检索系统在目标文档语言与用户查询语言高度匹配时表现出色。但在实际应用中，系统通常需要隐式判断文档的相关性。例如，技术文本或表格可能通过特定术语或结构隐含与用户查询的相关性，而非在内容中明确表达。大型语言模型（LLMs）在识别这种隐含相关性方面具有巨大潜力，得益于其强大的推理能力。然而，当前基于LLM的增强检索受限于高延迟和计算成本，因为LLM通常需要在线为每个新查询计算查询-文档相关性。为解决这一问题，我们引入了EnrichIndex方法。该方法在文档摄取阶段对检索语料库中的所有文档进行一次遍历，利用LLM离线构建语义增强的检索索引。此外，语义增强的索引可以与现有在线检索方法互补，提升LLM重排序器的性能。我们在涉及段落和表格的五个检索任务上评估了EnrichIndex，发现它优于强大的在线LLM基线系统。与强基线相比，其在召回率@10和NDCG@10指标上分别提升了11.7和10.6个点。在在线调用LLM方面，它处理的token数量减少了293.3倍，大幅降低了在线延迟和成本。总体而言，EnrichIndex是一种有效的方法，通过利用LLM强大的推理能力，离线构建更好的检索索引。

> Existing information retrieval systems excel in cases where the language of target documents closely matches that of the user query. However, real-world retrieval systems are often required to implicitly reason whether a document is relevant. For example, when retrieving technical texts or tables, their relevance to the user query may be implied through a particular jargon or structure, rather than explicitly expressed in their content. Large language models (LLMs) hold great potential in identifying such implied relevance by leveraging their reasoning skills. Nevertheless, current LLM-augmented retrieval is hindered by high latency and computation cost, as the LLM typically computes the query-document relevance online, for every query anew. To tackle this issue we introduce EnrichIndex, a retrieval approach which instead uses the LLM offline to build semantically-enriched retrieval indices, by performing a single pass over all documents in the retrieval corpus once during ingestion time. Furthermore, the semantically-enriched indices can complement existing online retrieval approaches, boosting the performance of LLM re-rankers. We evaluated EnrichIndex on five retrieval tasks, involving passages and tables, and found that it outperforms strong online LLM-based retrieval systems, with an average improvement of 11.7 points in recall @ 10 and 10.6 points in NDCG @ 10 compared to strong baselines. In terms of online calls to the LLM, it processes 293.3 times fewer tokens which greatly reduces the online latency and cost. Overall, EnrichIndex is an effective way to build better retrieval indices offline by leveraging the strong reasoning skills of LLMs.

[Arxiv](https://arxiv.org/abs/2504.03598)