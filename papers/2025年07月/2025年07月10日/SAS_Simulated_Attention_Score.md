# SAS：模拟注意力分数

发布时间：2025年07月10日

`LLM理论` `计算机视觉`

> SAS: Simulated Attention Score

# 摘要

> 注意力机制是Transformer架构的核心。为了计算注意力分数，人们开发了多种方法，包括多头注意力（MHA）、多查询注意力、组查询注意力等。我们深入分析了MHA，发现当每个注意力头的隐藏层足够大时，增加注意力头数量能显著提升性能。因此，以极小的参数代价同时增加注意力头数和每个头的隐藏层大小，可带来显著性能提升。基于此，我们提出了模拟注意力分数（SAS），它保持模型紧凑的同时，模拟了更多注意力头和更高特征维度。通过将低维注意力头表示投影到高维空间，SAS有效提升了注意力容量，而无需增加参数。我们还将模拟方法扩展到键和查询嵌入的特征维度，模仿大模型行为以增强表达，同时保持模型大小。为控制参数成本，我们提出了参数高效的注意力聚合（PEAA）。实验表明，SAS方法在多种数据集和任务上显著优于现有注意力变体。

> The attention mechanism is a core component of the Transformer architecture. Various methods have been developed to compute attention scores, including multi-head attention (MHA), multi-query attention, group-query attention and so on. We further analyze the MHA and observe that its performance improves as the number of attention heads increases, provided the hidden size per head remains sufficiently large. Therefore, increasing both the head count and hidden size per head with minimal parameter overhead can lead to significant performance gains at a low cost. Motivated by this insight, we introduce Simulated Attention Score (SAS), which maintains a compact model size while simulating a larger number of attention heads and hidden feature dimension per head. This is achieved by projecting a low-dimensional head representation into a higher-dimensional space, effectively increasing attention capacity without increasing parameter count. Beyond the head representations, we further extend the simulation approach to feature dimension of the key and query embeddings, enhancing expressiveness by mimicking the behavior of a larger model while preserving the original model size. To control the parameter cost, we also propose Parameter-Efficient Attention Aggregation (PEAA). Comprehensive experiments on a variety of datasets and tasks demonstrate the effectiveness of the proposed SAS method, achieving significant improvements over different attention variants.

[Arxiv](https://arxiv.org/abs/2507.07694)