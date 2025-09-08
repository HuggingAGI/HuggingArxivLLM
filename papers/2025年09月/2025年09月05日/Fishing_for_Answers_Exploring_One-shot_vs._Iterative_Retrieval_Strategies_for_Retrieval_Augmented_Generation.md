# 求索答案：探究检索增强生成的单轮与迭代检索策略

发布时间：2025年09月05日

`RAG` `法律科技`

> Fishing for Answers: Exploring One-shot vs. Iterative Retrieval Strategies for Retrieval Augmented Generation

# 摘要

> 基于大型语言模型（LLMs）的检索增强生成（RAG）是理解并查询行业闭源文档的高效解决方案。然而，在法律与监管领域的复杂问答任务中，基础RAG常显乏力，尤其面对海量政府文件时：top-$k$策略往往会漏掉关键信息片段，进而造成答案残缺或失准。为突破这些检索瓶颈，我们提出两种策略以提升证据覆盖率与答案质量。第一种是One-SHOT检索方法：根据token预算自适应筛选片段，在模型上下文窗口内尽可能纳入更多相关内容，同时设计模块对片段进行二次过滤与优化。第二种是基于推理智能体RAG框架的迭代检索策略：由推理LLM动态生成搜索查询，评估检索结果，并通过多轮交互逐步完善上下文。我们还识别出查询漂移与检索惰性问题，并针对性设计两个模块加以解决。通过在政府文件数据集上的大量实验，我们期望为法律与监管领域的实际应用提供实用参考与落地指引。

> Retrieval-Augmented Generation (RAG) based on Large Language Models (LLMs) is a powerful solution to understand and query the industry's closed-source documents. However, basic RAG often struggles with complex QA tasks in legal and regulatory domains, particularly when dealing with numerous government documents. The top-$k$ strategy frequently misses golden chunks, leading to incomplete or inaccurate answers. To address these retrieval bottlenecks, we explore two strategies to improve evidence coverage and answer quality. The first is a One-SHOT retrieval method that adaptively selects chunks based on a token budget, allowing as much relevant content as possible to be included within the model's context window. Additionally, we design modules to further filter and refine the chunks. The second is an iterative retrieval strategy built on a Reasoning Agentic RAG framework, where a reasoning LLM dynamically issues search queries, evaluates retrieved results, and progressively refines the context over multiple turns. We identify query drift and retrieval laziness issues and further design two modules to tackle them. Through extensive experiments on a dataset of government documents, we aim to offer practical insights and guidance for real-world applications in legal and regulatory domains.

[Arxiv](https://arxiv.org/abs/2509.04820)