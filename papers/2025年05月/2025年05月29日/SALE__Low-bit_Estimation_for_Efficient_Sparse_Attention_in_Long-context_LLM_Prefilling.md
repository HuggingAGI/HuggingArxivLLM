# SALE：面向长上下文LLM预填的高效稀疏注意力低比特量化估计方法

发布时间：2025年05月29日

`LLM应用` `大型语言模型`

> SALE : Low-bit Estimation for Efficient Sparse Attention in Long-context LLM Prefilling

# 摘要

> # 摘要
许多先进的大型语言模型（LLM）应用需要处理长上下文，但自注意力模块在推理的预填充阶段成为了瓶颈，因为它的计算复杂度与序列长度呈二次关系。现有的稀疏注意力方法通过跳过注意力图中不太重要的区域来加速注意力计算，但这些方法通常对注意力图进行粗粒度的检查，导致模型精度显著下降。

在本文中，我们提出了SALE，一种细粒度稀疏注意力方法，它在长上下文预填充阶段加速了LLM，同时几乎不损失模型精度。SALE通过4位量化的查询-键乘积实现了快速且准确的细粒度注意力权重估计，随后通过块稀疏注意力加速预填充计算。对于查询-键对的重要性评估，我们采用了我们的相对注意力分数指标，这在我们的框架中提供了显著更高的效率。

我们为我们的方法实现了一个优化的自定义CUDA内核，以提高硬件效率，将额外的开销降至全注意力延迟的大约11%。值得注意的是，SALE无需参数训练，可以通过简单的代码修改无缝集成到现有系统中。在长上下文基准上的实验表明，我们的方法在精度-效率权衡方面优于现有方法，对于超过64K长度的序列，在Llama-3.1-8B上实现了至少3.36倍的速度提升，同时保持了模型质量。

> Many advanced Large Language Model (LLM) applications require long-context processing, but the self-attention module becomes a bottleneck during the prefilling stage of inference due to its quadratic time complexity with respect to sequence length. Existing sparse attention methods accelerate attention computation by skipping less significant regions of the attention map. However, these approaches typically perform coarse-grained inspection of the attention map, rendering considerable loss in model accuracy. In this paper, we propose SALE, a fine-grained sparse attention method that accelerates the long-context prefilling stage of LLM with negligible loss in model accuracy. SALE achieves fast and accurate fine-grained attention weight estimation through 4-bit quantized query-key products, followed by block-sparse attention to accelerate prefilling computations. For importance evaluation for query-key pairs, we adopt our Relative Attention Score metric, which offers significantly higher efficiency within our framework. We implement a custom CUDA kernel optimized for our approach for hardware efficiency, reducing the additional overhead to approximately 11% of the full attention latency. Notably, SALE requires no parameter training and can be seamlessly integrated into existing systems with trivial code modifications. Experiments on long-context benchmarks demonstrate that our method outperforms existing approaches in accuracy-efficiency trade-offs, achieving at least 3.36x speedups on Llama-3.1-8B for sequences longer than 64K while maintaining model quality.

[Arxiv](https://arxiv.org/abs/2505.24179)