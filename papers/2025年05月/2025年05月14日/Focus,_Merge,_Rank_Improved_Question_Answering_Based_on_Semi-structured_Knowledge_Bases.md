# 聚焦、合并、排序：基于半结构化知识库的提升问答效果的新方法

发布时间：2025年05月14日

`LLM应用` `知识图谱` `问答系统`

> Focus, Merge, Rank: Improved Question Answering Based on Semi-structured Knowledge Bases

# 摘要

> 在现实场景中，机器学习模型和交互系统通常能同时处理结构化知识（如知识图谱、表格）和非结构化内容（如自然语言文档）。然而，大多数系统仅依赖其中之一。半结构化知识库（SKBs）通过将非结构化内容与结构化数据中的节点关联，实现了知识访问和使用的全新策略。我们在此介绍 FocusedRetriever，一个基于 SKB 的多跳问答模块化框架。它通过整合多个组件（基于 VSS 的实体搜索、基于 LLM 的 Cypher 查询生成及成对重排序），在涵盖多样化领域和多维度性能指标的三个 STaRK 基准测试集中均超越现有最优方法，平均首次命中率比第二名高出 25.7%。FocusedRetriever 的优势在于：（1）利用大型语言模型（LLMs）从非结构化文本中提取关系事实和实体属性，（2）通过节点集连接根据提取的三元组和约束条件筛选答案候选，（3）借助向量相似性搜索检索和排名相关非结构化内容，以及（4）利用 LLMs 的上下文能力最终排名前 k 个答案。为保持通用性，我们在评估中仅集成了基础 LLMs。然而，对中间结果的分析揭示了进一步升级的机会，包括微调。源代码可在 https://github.com/kramerlab/FocusedRetriever 公开获取。

> In many real-world settings, machine learning models and interactive systems have access to both structured knowledge, e.g., knowledge graphs or tables, and unstructured content, e.g., natural language documents. However, most rely on either. Semi-Structured Knowledge Bases (SKBs) bridge this gap by linking unstructured content to nodes within structured data, thereby enabling new strategies for knowledge access and use. In this work, we present FocusedRetriever, a modular SKB-based framework for multi-hop question answering. It integrates components (VSS-based entity search, LLM-based generation of Cypher queries and pairwise re-ranking) in a way that enables it to outperform state-of-the-art methods across all three STaRK benchmark test sets, covering diverse domains and multiple performance metrics. The average first-hit rate exceeds that of the second-best method by 25.7%. FocusedRetriever leverages (1) the capacity of Large Language Models (LLMs) to extract relational facts and entity attributes from unstructured text, (2) node set joins to filter answer candidates based on these extracted triplets and constraints, (3) vector similarity search to retrieve and rank relevant unstructured content, and (4) the contextual capabilities of LLMs to finally rank the top-k answers. For generality, we only incorporate base LLMs in FocusedRetriever in our evaluation. However, our analysis of intermediate results highlights several opportunities for further upgrades including finetuning. The source code is publicly available at https://github.com/kramerlab/FocusedRetriever .

[Arxiv](https://arxiv.org/abs/2505.09246)