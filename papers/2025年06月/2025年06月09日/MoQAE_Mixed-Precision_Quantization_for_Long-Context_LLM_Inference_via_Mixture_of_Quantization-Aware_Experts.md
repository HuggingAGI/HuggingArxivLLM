# MoQAE：通过量化感知专家混合模型实现长上下文LLM的混合精度量化推理

发布时间：2025年06月09日

`LLM应用` `人工智能` `计算机科学`

> MoQAE: Mixed-Precision Quantization for Long-Context LLM Inference via Mixture of Quantization-Aware Experts

# 摘要

> 优化大型语言模型 (LLMs) 的长上下文推理时，面临的主要挑战是键值（KV）缓存的高内存消耗。虽然现有量化方法在减少内存使用方面已初见成效，但目前的量化方案难以兼顾效果与效率。本文提出了一种名为 MoQAE 的创新混合精度量化方法，通过量化感知专家的混合实现。首先，我们将不同的量化位宽配置视为专家，并采用传统的专家混合（MoE）方法选择最优配置。为避免传统 MoE 方法中逐一输入令牌到路由器的低效，我们采用分块输入方式。其次，我们设计了一个轻量级的仅路由器微调过程，使用综合损失函数训练 MoQAE，以平衡模型精度与内存使用。最后，我们引入了路由冻结（RF）和路由共享（RS）机制，进一步降低推理开销。在多个基准数据集上的广泛实验表明，我们的方法在效率和效果上均优于现有的 KV 缓存量化方法。

> One of the primary challenges in optimizing large language models (LLMs) for long-context inference lies in the high memory consumption of the Key-Value (KV) cache. Existing approaches, such as quantization, have demonstrated promising results in reducing memory usage. However, current quantization methods cannot take both effectiveness and efficiency into account. In this paper, we propose MoQAE, a novel mixed-precision quantization method via mixture of quantization-aware experts. First, we view different quantization bit-width configurations as experts and use the traditional mixture of experts (MoE) method to select the optimal configuration. To avoid the inefficiency caused by inputting tokens one by one into the router in the traditional MoE method, we input the tokens into the router chunk by chunk. Second, we design a lightweight router-only fine-tuning process to train MoQAE with a comprehensive loss to learn the trade-off between model accuracy and memory usage. Finally, we introduce a routing freezing (RF) and a routing sharing (RS) mechanism to further reduce the inference overhead. Extensive experiments on multiple benchmark datasets demonstrate that our method outperforms state-of-the-art KV cache quantization approaches in both efficiency and effectiveness.

[Arxiv](https://arxiv.org/abs/2506.07533)