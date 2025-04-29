# 乌鸦能否孵出猎鹰？模型的来源对其性能预测至关重要。
乌鸦能否孵出猎鹰？大型语言模型的性能预测与其来源密切相关。

发布时间：2025年04月28日

`LLM应用` `人工智能` `模型优化`

> Can a Crow Hatch a Falcon? Lineage Matters in Predicting Large Language Model Performance

# 摘要

> 精准预测大型语言模型（LLM）性能，能在微调或合并前大幅节省计算成本和开发时间。现有方法如缩放法则虽考虑了参数规模等全局因素，却忽视了模型间的“血缘”关系。为此，我们提出了一种基于谱系正则化的矩阵分解框架（LRMF），通过图拉普拉斯正则化器捕捉LLM间的谱系联系。凭借多跳的父子连接关系，LRMF在实例级和基准级预测中均超越传统方法。我们的研究覆盖2,934个Hugging Face模型及21,000多个实例，结果表明谱系约束使预测与实际性能的相关性提升7-10个百分点。此外，LRMF还解决了冷启动问题，即使数据极少，也能精准预测新模型性能。这种谱系引导的策略为现代LLM开发提供了高效资源解决方案，可用于超参数调整、数据选择和模型组合。

> Accurately forecasting the performance of Large Language Models (LLMs) before extensive fine-tuning or merging can substantially reduce both computational expense and development time. Although prior approaches like scaling laws account for global factors such as parameter size or training tokens, they often overlook explicit lineage relationships - i.e., which models are derived or merged from which parents. In this work, we propose a novel Lineage-Regularized Matrix Factorization (LRMF) framework that encodes ancestral ties among LLMs via a graph Laplacian regularizer. By leveraging multi-hop parent-child connections, LRMF consistently outperforms conventional matrix factorization and collaborative filtering methods in both instance-level and benchmark-level performance prediction. Our large-scale study includes 2,934 publicly available Hugging Face models and 21,000+ instances across 6 major benchmarks, showing that lineage constraints yield up to 7-10 percentage points higher correlation with actual performance compared to baselines. Moreover, LRMF effectively addresses the cold-start problem, providing accurate estimates for newly derived or merged models even with minimal data. This lineage-guided strategy thus offers a resource-efficient way to inform hyperparameter tuning, data selection, and model combination in modern LLM development.

[Arxiv](https://arxiv.org/abs/2504.19811)