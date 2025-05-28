# 企业系统中特定领域检索的困难负样本挖掘

发布时间：2025年05月23日

`RAG` `企业服务` `知识管理`

> Hard Negative Mining for Domain-Specific Retrieval in Enterprise Systems

# 摘要

> 企业搜索系统常因语义不匹配和术语重叠而难以准确检索领域特定信息，这会影响知识管理、客户服务和检索增强生成代理等应用的性能。为解决这一问题，我们提出了一种专门针对领域特定企业数据的可扩展困难负样本挖掘框架。

我们的方法整合多种嵌入模型，执行降维并独特选择困难负样本，确保计算效率和语义精确度。在专有云服务语料库上的评估显示，与现有基线相比，MRR@3和MRR@10分别提升了15%和19%。在FiQA、Climate Fever和TechQA等公共数据集上的验证证实了方法的泛化能力，使其具备实际应用价值。

> Enterprise search systems often struggle to retrieve accurate, domain-specific information due to semantic mismatches and overlapping terminologies. These issues can degrade the performance of downstream applications such as knowledge management, customer support, and retrieval-augmented generation agents. To address this challenge, we propose a scalable hard-negative mining framework tailored specifically for domain-specific enterprise data. Our approach dynamically selects semantically challenging but contextually irrelevant documents to enhance deployed re-ranking models.
  Our method integrates diverse embedding models, performs dimensionality reduction, and uniquely selects hard negatives, ensuring computational efficiency and semantic precision. Evaluation on our proprietary enterprise corpus (cloud services domain) demonstrates substantial improvements of 15\% in MRR@3 and 19\% in MRR@10 compared to state-of-the-art baselines and other negative sampling techniques. Further validation on public domain-specific datasets (FiQA, Climate Fever, TechQA) confirms our method's generalizability and readiness for real-world applications.

[Arxiv](https://arxiv.org/abs/2505.18366)