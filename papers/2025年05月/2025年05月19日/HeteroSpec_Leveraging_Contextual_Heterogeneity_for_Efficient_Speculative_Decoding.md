# HeteroSpec: 借助上下文多样性进行高效推测性解码

发布时间：2025年05月19日

`LLM理论` `模型推理`

> HeteroSpec: Leveraging Contextual Heterogeneity for Efficient Speculative Decoding

# 摘要

> 自回归解码作为大型语言模型推理的标准方法，由于其串行特性，一直是性能瓶颈。尽管推测式解码算法通过并行验证缓解了这一低效问题，但它们未能充分利用语言复杂度的内在异质性，这是导致资源分配次优的关键因素。我们提出了一种异质性自适应的推测式解码框架HeteroSpec，能够根据语言上下文复杂度动态优化计算资源分配。

HeteroSpec引入了两个关键机制：(1) 一种新型的累积元路径Top-$K$熵度量，用于高效识别可预测的上下文。(2) 基于数据驱动的熵划分的动态资源分配策略，支持自适应的推测式扩展和剪枝，可根据局部上下文难度进行调整。

在五个公开基准和四个模型上的评估显示，HeteroSpec实现了平均4.26倍的速度提升。它在加速率、平均接受长度和验证成本方面均优于最先进的EAGLE-3。值得注意的是，HeteroSpec无需重新训练草稿模型，开销极小，并且与其他加速技术互不冲突。它能够通过更强大的草稿模型实现进一步加速，为上下文感知的LLM推理加速开辟了新的范式。

> Autoregressive decoding, the standard approach for Large Language Model (LLM) inference, remains a significant bottleneck due to its sequential nature. While speculative decoding algorithms mitigate this inefficiency through parallel verification, they fail to exploit the inherent heterogeneity in linguistic complexity, a key factor leading to suboptimal resource allocation. We address this by proposing HeteroSpec, a heterogeneity-adaptive speculative decoding framework that dynamically optimizes computational resource allocation based on linguistic context complexity. HeteroSpec introduces two key mechanisms: (1) A novel cumulative meta-path Top-$K$ entropy metric for efficiently identifying predictable contexts. (2) A dynamic resource allocation strategy based on data-driven entropy partitioning, enabling adaptive speculative expansion and pruning tailored to local context difficulty. Evaluated on five public benchmarks and four models, HeteroSpec achieves an average speedup of 4.26$\times$. It consistently outperforms state-of-the-art EAGLE-3 across speedup rates, average acceptance length, and verification cost. Notably, HeteroSpec requires no draft model retraining, incurs minimal overhead, and is orthogonal to other acceleration techniques. It demonstrates enhanced acceleration with stronger draft models, establishing a new paradigm for context-aware LLM inference acceleration.

[Arxiv](https://arxiv.org/abs/2505.13254)