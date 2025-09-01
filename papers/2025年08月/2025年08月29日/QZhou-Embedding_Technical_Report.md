# QZhou嵌入技术报告

发布时间：2025年08月29日

`RAG` `基础理论`

> QZhou-Embedding Technical Report

# 摘要

> 我们推出QZhou-Embedding——一款具备卓越文本表示能力的通用上下文文本嵌入模型。该模型以Qwen2.5-7B-Instruct为基础，我们设计了统一的多任务框架，融合专门的数据转换与训练策略：数据转换方案可纳入更多样化的文本训练数据，特定任务策略则进一步提升模型学习效率。我们还构建了基于LLM API的数据合成流水线，通过释义、增强及难负例生成等技术，显著提升训练集的语义丰富度与样本挑战性。训练方面采用两阶段策略：先进行检索导向的预训练，再开展全任务微调，让模型在稳健检索性能的基础上拓展能力边界。性能上，QZhou-Embedding在MTEB和CMTEB基准测试中均刷新当前最佳成绩，于2025年8月27日登顶双榜榜首，同时在重排序、聚类等任务中也表现出顶尖水平。研究发现，高质量、多样化的数据是提升检索模型性能的核心，而借助LLM的生成能力优化数据质量，可为嵌入模型带来突破性进展。目前，模型权重已通过Apache 2.0许可证在HuggingFace开放，GitHub上同步提供评估代码与复现指南，确保研究可复现性。

> We present QZhou-Embedding, a general-purpose contextual text embedding model with exceptional text representation capabilities. Built upon the Qwen2.5-7B-Instruct foundation model, we designed a unified multi-task framework comprising specialized data transformation and training strategies. The data transformation scheme enables the incorporation of more diverse textual training datasets, while the task-specific training strategies enhance model learning efficiency. We developed a data synthesis pipeline leveraging LLM API, incorporating techniques such as paraphrasing, augmentation, and hard negative example generation to improve the semantic richness and sample difficulty of the training set. Additionally, we employ a two-stage training strategy, comprising initial retrieval-focused pretraining followed by full-task fine-tuning, enabling the embedding model to extend its capabilities based on robust retrieval performance. Our model achieves state-of-the-art results on the MTEB and CMTEB benchmarks, ranking first on both leaderboards (August 27 2025), and simultaneously achieves state-of-the-art performance on tasks including reranking, clustering, etc. Our findings demonstrate that higher-quality, more diverse data is crucial for advancing retrieval model performance, and that leveraging LLMs generative capabilities can further optimize data quality for embedding model breakthroughs. Our model weights are released on HuggingFace under Apache 2.0 license. For reproducibility, we provide evaluation code and instructions on GitHub.

[Arxiv](https://arxiv.org/abs/2508.21632)