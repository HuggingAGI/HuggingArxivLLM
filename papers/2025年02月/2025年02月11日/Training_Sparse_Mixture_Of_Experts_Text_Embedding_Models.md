# # 训练稀疏的专家混合文本嵌入模型

发布时间：2025年02月11日

`LLM应用` `文本嵌入` `检索增强生成`

> Training Sparse Mixture Of Experts Text Embedding Models

# 摘要

> 基于Transformer的文本嵌入模型通过增加参数数量，在MIRACL和BEIR等基准测试中表现更优。然而，这种扩展方法带来了显著的部署挑战，包括推理延迟和内存使用量的增加。这些挑战在检索增强生成（RAG）应用中尤为突出，大型模型的内存需求增加限制了数据集的摄入能力，而更高的延迟直接影响了查询性能。虽然因果语言模型通过使用专家混合（MoE）架构解决了类似的效率问题，但这一方法尚未成功应用于通用文本嵌入设置。本文中，我们介绍了Nomic Embed v2，首个通用专家混合文本嵌入模型。我们的模型在单语和多语种基准测试中均超越了同规模模型，同时在双倍规模的模型中也保持了竞争力。我们开源了所有代码、模型和评估数据，确保了训练流程的完全可重复性。

> Transformer-based text embedding models have improved their performance on benchmarks like MIRACL and BEIR by increasing their parameter counts. However, this scaling approach introduces significant deployment challenges, including increased inference latency and memory usage. These challenges are particularly severe in retrieval-augmented generation (RAG) applications, where large models' increased memory requirements constrain dataset ingestion capacity, and their higher latency directly impacts query-time performance. While causal language models have addressed similar efficiency challenges using Mixture of Experts (MoE) architectures, this approach hasn't been successfully adapted to the general text embedding setting. In this paper, we introduce Nomic Embed v2, the first general purpose MoE text embedding model. Our model outperforms models in the same parameter class on both monolingual and multilingual benchmarks while also maintaining competitive performance with models twice its size. We open-source all code, models, and evaluation data to ensure full reproducibility of our training pipeline.

[Arxiv](https://arxiv.org/abs/2502.07972)