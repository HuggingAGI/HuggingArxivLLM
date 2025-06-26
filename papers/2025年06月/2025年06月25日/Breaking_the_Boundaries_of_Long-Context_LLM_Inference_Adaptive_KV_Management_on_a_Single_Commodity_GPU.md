# 突破长上下文LLM推理的限制：在单张消费级GPU上实现自适应KV管理

发布时间：2025年06月25日

`其他

理由：这篇论文专注于优化大语言模型在普通GPU上的长上下文推理性能，提出了一个高效的系统设计，属于计算系统的优化范畴，而非LLM本身的理论或应用。` `人工智能`

> Breaking the Boundaries of Long-Context LLM Inference: Adaptive KV Management on a Single Commodity GPU

# 摘要

> 先进大语言模型（LLMs）在复杂长上下文自然语言任务中表现优异。然而，普通GPU（如个人电脑）本地执行长上下文LLM推理仍面临挑战，主要由于KV缓存内存需求激增以及隐私顾虑。现有系统通常通过识别重要令牌并选择性卸载其KV数据到GPU和CPU内存来应对。但受限于普通GPU内存容量，KV数据需卸载至磁盘，却因令牌重要性评估开销和磁盘低带宽而受阻。本文提出LeoAM——首个针对单普通GPU的高效重要性感知长上下文LLM推理系统，采用自适应分层GPU-CPU-磁盘KV管理。系统通过根据各层注意力权重偏态分布将KV数据划分为可变块，减少计算与传输开销。我们还提出轻量级KV抽象方法，通过存储和提取块级KV抽象而非完整数据，显著降低传输延迟。此外，LeoAM借助动态压缩与流水线技术进一步加速推理。实验表明，LongInfer实现平均推理延迟3.46倍加速，保持LLM响应质量。在大批次场景下，加速倍数最高可达5.47倍。

> Advanced Large Language Models (LLMs) have achieved impressive performance across a wide range of complex and long-context natural language tasks. However, performing long-context LLM inference locally on a commodity GPU (a PC) with privacy concerns remains challenging due to the increasing memory demands of the key-value (KV) cache. Existing systems typically identify important tokens and selectively offload their KV data to GPU and CPU memory. The KV data needs to be offloaded to disk due to the limited memory on a commodity GPU, but the process is bottlenecked by token importance evaluation overhead and the disk's low bandwidth. In this paper, we present LeoAM, the first efficient importance-aware long-context LLM inference system for a single commodity GPU with adaptive hierarchical GPU-CPU-Disk KV management. Our system employs an adaptive KV management strategy that partitions KV data into variable-sized chunks based on the skewed distribution of attention weights across different layers to reduce computational and additional transmission overheads. Moreover, we propose a lightweight KV abstract method, which minimizes transmission latency by storing and extracting the KV abstract of each chunk on disk instead of the full KV data. LeoAM also leverages the dynamic compression and pipeline techniques to further accelerate inference. Experimental results demonstrate that LongInfer achieves an average inference latency speedup of 3.46x, while maintaining comparable LLM response quality. In scenarios with larger batch sizes, it achieves up to a 5.47x speedup.

[Arxiv](https://arxiv.org/abs/2506.20187)