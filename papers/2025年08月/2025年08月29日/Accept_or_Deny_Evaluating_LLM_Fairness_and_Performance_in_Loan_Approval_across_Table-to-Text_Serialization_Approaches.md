# 批准还是拒绝？基于表格转文本序列化方法评估贷款审批中大型语言模型的公平性与性能

发布时间：2025年08月29日

`LLM应用` `金融科技`

> Accept or Deny? Evaluating LLM Fairness and Performance in Loan Approval across Table-to-Text Serialization Approaches

# 摘要

> 大型语言模型（LLMs）正越来越多地应用于贷款审批等高风险决策任务中。尽管其应用已扩展到多个领域，LLMs在处理表格数据、保障公平性及生成可靠预测方面仍面临挑战。本研究评估了LLMs在三个不同地区（加纳、德国、美国）的序列化贷款审批数据集上的性能与公平性，重点关注模型的零样本和上下文学习（ICL）能力。结果显示，序列化格式（即将表格数据转换为LLMs可处理文本格式的过程）的选择对LLMs的性能和公平性影响显著：部分格式（如GReat和LIFT）虽能提升F1分数，却会加剧公平性差异。值得注意的是，ICL虽较零样本基线将模型性能提升了4.9-59.6%，但其对公平性的影响在不同数据集间差异显著。本研究强调，有效的表格数据表示方法与公平感知模型对于提升LLMs在金融决策中的可靠性至关重要。

> Large Language Models (LLMs) are increasingly employed in high-stakes decision-making tasks, such as loan approvals. While their applications expand across domains, LLMs struggle to process tabular data, ensuring fairness and delivering reliable predictions. In this work, we assess the performance and fairness of LLMs on serialized loan approval datasets from three geographically distinct regions: Ghana, Germany, and the United States. Our evaluation focuses on the model's zero-shot and in-context learning (ICL) capabilities. Our results reveal that the choice of serialization (Serialization refers to the process of converting tabular data into text formats suitable for processing by LLMs.) format significantly affects both performance and fairness in LLMs, with certain formats such as GReat and LIFT yielding higher F1 scores but exacerbating fairness disparities. Notably, while ICL improved model performance by 4.9-59.6% relative to zero-shot baselines, its effect on fairness varied considerably across datasets. Our work underscores the importance of effective tabular data representation methods and fairness-aware models to improve the reliability of LLMs in financial decision-making.

[Arxiv](https://arxiv.org/abs/2508.21512)