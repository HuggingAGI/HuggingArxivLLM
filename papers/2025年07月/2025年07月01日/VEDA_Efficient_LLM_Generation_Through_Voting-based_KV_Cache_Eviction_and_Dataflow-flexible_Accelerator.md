# VEDA: 基于投票的键值缓存淘汰机制与数据流灵活加速器实现LLM高效生成

发布时间：2025年07月01日

`LLM应用` `边缘计算` `硬件优化`

> VEDA: Efficient LLM Generation Through Voting-based KV Cache Eviction and Dataflow-flexible Accelerator

# 摘要

> 大型语言模型（LLMs）在自然语言处理任务中表现出色，但在边缘部署中面临计算和内存的巨大挑战。本研究通过算法-硬件-数据流的三重优化，致力于提升LLM推理效率。我们提出了一种基于投票的KV缓存替换算法，通过自适应识别不重要的kv向量，在硬件效率和算法准确性之间取得平衡。从数据流角度，我们引入了灵活的产品数据流和运行时可重构的PE阵列，用于矩阵-向量乘法。该方法有效应对了多样的维度需求，解决了序列长度递增变化的挑战。此外，针对非线性操作（如softmax和层归一化），我们提出了一种元素串行调度方案。实验结果表明，该方法显著降低了延迟，同时将硬件复杂度从O(N)降至O(1)。我们的解决方案在定制设计的VEDA加速器上实现，性能优于现有硬件平台。这项研究在资源受限的边缘设备上实现了LLM推理的重大突破，推动了实时处理、数据隐私保护和模型定制化的发展。

> Large Language Models (LLMs) excel in natural language processing tasks but pose significant computational and memory challenges for edge deployment due to their intensive resource demands. This work addresses the efficiency of LLM inference by algorithm-hardware-dataflow tri-optimizations. We propose a novel voting-based KV cache eviction algorithm, balancing hardware efficiency and algorithm accuracy by adaptively identifying unimportant kv vectors. From a dataflow perspective, we introduce a flexible-product dataflow and a runtime reconfigurable PE array for matrix-vector multiplication. The proposed approach effectively handles the diverse dimensional requirements and solves the challenges of incrementally varying sequence lengths. Additionally, an element-serial scheduling scheme is proposed for nonlinear operations, such as softmax and layer normalization (layernorm). Results demonstrate a substantial reduction in latency, accompanied by a significant decrease in hardware complexity, from O(N) to O(1). The proposed solution is realized in a custom-designed accelerator, VEDA, which outperforms existing hardware platforms. This research represents a significant advancement in LLM inference on resource-constrained edge devices, facilitating real-time processing, enhancing data privacy, and enabling model customization.

[Arxiv](https://arxiv.org/abs/2507.00797)