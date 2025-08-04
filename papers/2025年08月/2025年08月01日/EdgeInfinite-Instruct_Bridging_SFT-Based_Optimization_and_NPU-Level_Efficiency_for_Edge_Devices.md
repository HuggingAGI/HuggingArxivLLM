# EdgeInfinite-Instruct：连接SFT优化与边缘设备NPU效率

发布时间：2025年08月01日

`LLM应用

理由：这篇论文主要探讨了如何在资源受限的边缘设备上优化大语言模型（LLMs）的部署，特别是针对长序列任务的处理。论文提出了具体的优化策略，如分段监督微调（S-SFT）、后训练量化（PTQ）和固定形状的计算图，以提升模型在边缘设备上的性能和效率。这些工作属于LLM的应用层面，因为它们专注于如何在实际应用中优化和部署LLMs，而不是研究LLM的理论基础或架构设计。因此，这篇论文被归类为LLM应用。` `边缘计算` `移动计算`

> EdgeInfinite-Instruct: Bridging SFT-Based Optimization and NPU-Level Efficiency for Edge Devices

# 摘要

> # 摘要
在资源受限的边缘设备上部署基于Transformer的大语言模型（LLMs）以处理长序列任务仍具挑战性，这主要源于自注意力机制的二次时间复杂度以及不断增长的关键值（KV）缓存需求。尽管现有的KV缓存优化方法提高了内存效率，但它们通常未能减少首词响应时间（TTFT），甚至可能因令牌剪枝而导致性能下降。替代的序列建模架构虽然解决了部分这些限制，但通常需要完整的重新训练且缺乏基础设施支持。

EdgeInfinite通过仅微调一小部分参数提供了一个高效解决方案，在降低计算和内存成本的同时保持质量，包括改进TTFT。然而，其指令遵循能力有限，且缺乏针对移动设备的特定优化。为了解决这些问题，我们提出了EdgeInfinite-Instruct，它引入了一种针对长序列任务（如总结和问答）的分段监督微调（S-SFT）策略。我们进一步通过采用细粒度的后训练量化（PTQ）来降低计算需求同时保持准确性，并通过实现固定形状的计算图来优化EdgeInfinite-Instruct在边缘NPU上的高效部署，该计算图通过针对具体场景定制输入令牌和缓存大小来平衡内存使用和设备效率。

在长上下文基准测试和真实世界移动任务上的实验表明，我们的方法在NPU加速的边缘设备上提升了领域特定性能，同时保持了效率。

> Deploying Transformer-based large language models (LLMs) on resource-constrained edge devices for long-sequence tasks remains challenging due to the quadratic time complexity of self-attention and growing Key-Value (KV) cache demands. While existing KV cache optimizations improve memory efficiency, they often fail to reduce time to first token (TTFT) and may degrade performance through token pruning. Alternative sequence modeling architectures address some of these limitations, but typically require full retraining and lack infrastructure support. EdgeInfinite offers an efficient solution by fine-tuning only a small subset of parameters, maintaining quality while reducing both computational and memory costs, including improved TTFT. However, its instruction-following ability is limited, and it lacks mobile-specific optimizations. To address these issues, we propose EdgeInfinite-Instruct, which introduces a Segmented Supervised Fine-Tuning (S-SFT) strategy tailored to long-sequence tasks such as summarization and question answering. We further optimized EdgeInfinite-Instruct for efficient deployment on edge NPUs by employing fine-grained post-training quantization (PTQ) to reduce computational demands while maintaining accuracy, and by implementing a fixed-shape computation graph that balances memory usage and on-device efficiency through scenario-specific customization of input token and cache sizes. Experiments on long-context benchmarks and real-world mobile tasks show that our approach improves domain-specific performance while maintaining efficiency on NPU-accelerated edge devices.

[Arxiv](https://arxiv.org/abs/2508.00370)