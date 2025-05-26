# VIBE：向量索引嵌入基准测试

发布时间：2025年05月23日

`RAG` `机器学习` `数据处理`

> VIBE: Vector Index Benchmark for Embeddings

# 摘要

> 近似最近邻 (ANN) 搜索是机器学习管道中性能至上的关键组件。评估 ANN 搜索的向量索引性能需要严格的基准测试，然而现有基准测试的数据集已无法代表当前应用场景。为此，我们推出了开源项目 Vector Index Benchmark for Embeddings (VIBE)，用于基准测试 ANN 算法。VIBE 使用现代应用程序中具有代表性的密集嵌入模型（如增强检索生成 RAG）创建基准数据集。为了模拟真实世界的工作负载，我们引入了分布外 (OOD) 数据集，其中查询和语料库来自不同分布。通过 VIBE，我们对 21 种最先进的向量索引进行了全面评估，覆盖了 12 个分布内和 6 个分布外数据集。

> Approximate nearest neighbor (ANN) search is a performance-critical component of many machine learning pipelines. Rigorous benchmarking is essential for evaluating the performance of vector indexes for ANN search. However, the datasets of the existing benchmarks are no longer representative of the current applications of ANN search. Hence, there is an urgent need for an up-to-date set of benchmarks. To this end, we introduce Vector Index Benchmark for Embeddings (VIBE), an open source project for benchmarking ANN algorithms. VIBE contains a pipeline for creating benchmark datasets using dense embedding models characteristic of modern applications, such as retrieval-augmented generation (RAG). To replicate real-world workloads, we also include out-of-distribution (OOD) datasets where the queries and the corpus are drawn from different distributions. We use VIBE to conduct a comprehensive evaluation of SOTA vector indexes, benchmarking 21 implementations on 12 in-distribution and 6 out-of-distribution datasets.

[Arxiv](https://arxiv.org/abs/2505.17810)