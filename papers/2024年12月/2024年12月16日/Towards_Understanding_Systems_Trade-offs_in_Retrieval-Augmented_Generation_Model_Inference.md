# 探索检索增强生成模型推理中的系统权衡

发布时间：2024年12月16日

`RAG` `语言模型` `系统性能`

> Towards Understanding Systems Trade-offs in Retrieval-Augmented Generation Model Inference

# 摘要

> 大型语言模型（LLMs）参数数量的快速增长大幅提升了微调与重新训练 LLMs 的成本，而这对于让模型保持更新并提高准确性是必需的。检索增强生成（RAG）提供了一种无需重新训练就能提升 LLMs 能力和准确性的颇具前景的方法。虽然 RAG 无需为更新模型数据而持续重新训练，但它带来了模型推理时间变慢的权衡。所以，在利用 RAG 增强 LLMs 的准确性和能力时，往往因其设计而存在各种性能影响和权衡。为了从系统视角着手处理和减轻与 RAG 相关的性能损失，本文针对 LLMs 的 RAG 生态系统中的不同元素引入了详细的分类和特性描述，以探究在延迟、吞吐量和内存方面的权衡。我们的研究揭示了系统部署中 RAG 的潜在低效问题，可能导致 TTFT 延迟翻倍以及未优化的数据存储占用数太字节的存储空间。

> The rapid increase in the number of parameters in large language models (LLMs) has significantly increased the cost involved in fine-tuning and retraining LLMs, a necessity for keeping models up to date and improving accuracy. Retrieval-Augmented Generation (RAG) offers a promising approach to improving the capabilities and accuracy of LLMs without the necessity of retraining. Although RAG eliminates the need for continuous retraining to update model data, it incurs a trade-off in the form of slower model inference times. Resultingly, the use of RAG in enhancing the accuracy and capabilities of LLMs often involves diverse performance implications and trade-offs based on its design. In an effort to begin tackling and mitigating the performance penalties associated with RAG from a systems perspective, this paper introduces a detailed taxonomy and characterization of the different elements within the RAG ecosystem for LLMs that explore trade-offs within latency, throughput, and memory. Our study reveals underlying inefficiencies in RAG for systems deployment, that can result in TTFT latencies that are twice as long and unoptimized datastores that consume terabytes of storage.

[Arxiv](https://arxiv.org/abs/2412.11854)