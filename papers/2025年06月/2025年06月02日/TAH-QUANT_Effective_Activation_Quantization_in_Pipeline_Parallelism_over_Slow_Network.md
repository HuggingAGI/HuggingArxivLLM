# TAH-QUANT：在慢网络环境下实现流水线并行中的有效激活量化

发布时间：2025年06月02日

`LLM应用` `人工智能` `分布式计算`

> TAH-QUANT: Effective Activation Quantization in Pipeline Parallelism over Slow Network

# 摘要

> 大型语言模型的去中心化训练为地理分布的参与者整合计算资源提供了机会，但在管道并行设置中面临显著的网络通信瓶颈。管道并行通过跨设备划分模型层来处理大规模模型，但需要频繁通信中间激活，这在网络带宽有限时尤为棘手。现有的激活压缩方法如AQ-SGD通过误差补偿缓解量化误差，但因存储先前激活导致了高昂的内存开销。

为解决这些问题，我们提出了TAH-Quant（基于瓷砖的自适应Hadamard量化），一种专为管道并行设计的新型激活量化框架。该方法结合了细粒度瓷砖量化实现精准控制，熵引导的基于标记的自适应位分配以优化位使用，以及基于Hadamard变换并结合枢轴元素交换的方法，有效抑制量化异常值。

我们进一步提供理论分析，证明了配备TAH-Quant的管道并行训练保持了$\mathcal{O}(1/\sqrt{T})$的收敛速率，与普通随机梯度下降相同。在多种大型语言模型任务上的广泛实验表明，TAH-Quant实现了激进的3-4位激活量化比率，提供了高达4.3倍的端到端加速，同时保持训练收敛性，达到了最先进的方法水平，且无额外内存开销，在不同训练场景下表现优异。


> Decentralized training of large language models offers the opportunity to pool computational resources across geographically distributed participants but faces significant network communication bottlenecks, particularly in pipeline-parallel settings. While pipeline parallelism partitions model layers across devices to handle large-scale models, it necessitates frequent communication of intermediate activations, creating challenges when network bandwidth is limited. Existing activation compression methods, such as AQ-SGD, mitigate quantization-induced errors through error compensation but impose prohibitive memory overhead by requiring storage of previous activations. To address these issues, we introduce TAH-Quant (Tile-wise Adaptive Hadamard Quantization), a novel activation quantization framework designed specifically for pipeline parallelism. Our approach integrates fine-grained tile-wise quantization for precise control, entropy-guided token-level adaptive bit allocation for optimal bit usage, and a Hadamard-based transform with pivot element swapping to effectively suppress quantization outliers. We further provide a theoretical analysis, proving that pipeline parallel training equipped with TAH-Quant maintains a convergence rate of $\mathcal{O}(1/\sqrt{T})$, matching that of vanilla stochastic gradient descent. Extensive experiments on diverse LLM tasks demonstrate that TAH-Quant achieves aggressive activation quantization (3-4 bits) ratio, which provides up to 4.3$\times$ end-to-end speedup without compromising training convergence, matches state-of-the-art methods, incurs no extra memory overhead, and generalizes well across different training scenarios.

[Arxiv](https://arxiv.org/abs/2506.01352)