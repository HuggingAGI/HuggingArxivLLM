# 分布式深度学习中的操作符级并行规划——一种基于混合整数规划的自动方法

发布时间：2025年03月12日

`其他` `人工智能` `大规模AI部署`

> Automatic Operator-level Parallelism Planning for Distributed Deep Learning -- A Mixed-Integer Programming Approach

# 摘要

> 步入拥有数十亿参数的大模型时代，分布式训练与推理已成为人工智能领域的核心命题。尽管数据、模型、序列和流水线等并行策略在主流硬件上的神经网络中已见成效，但优化分布式部署仍需深厚的专业积累与手动调试。现有框架虽以简单链式结构为主，却在面对复杂非线性架构时显得捉襟见肘。混合专家模型与多模态模型的复杂MIMO拓扑与丰富分支，要求更精细的操作级别并行化，这已超出传统框架的能力范畴。

我们提出将并行规划建模为一个混合整数规划的调度优化问题，并构建了一个双层解决方案框架，既追求最优性又兼顾计算效率。该框架能自动生成兼顾现代神经网络异构结构与硬件约束的分布式计划。在与深度求索DualPipe等专家设计策略的对比实验中，我们的框架不仅性能相当，在相同内存约束下更将计算瓶颈减少一半。其灵活性不仅限于吞吐量优化，更可扩展至硬件利用率最大化、内存容量限制等多维度考量。

这一解决方案不仅为探索最优并行化策略提供了宝贵的研究工具，更为大规模AI部署提供了切实可行的工业级方案。

> As the artificial intelligence community advances into the era of large models with billions of parameters, distributed training and inference have become essential. While various parallelism strategies-data, model, sequence, and pipeline-have been successfully implemented for popular neural networks on main-stream hardware, optimizing the distributed deployment schedule requires extensive expertise and manual effort. Further more, while existing frameworks with most simple chain-like structures, they struggle with complex non-linear architectures. Mixture-of-experts and multi-modal models feature intricate MIMO and branch-rich topologies that require fine-grained operator-level parallelization beyond the capabilities of existing frameworks. We propose formulating parallelism planning as a scheduling optimization problem using mixed-integer programming. We propose a bi-level solution framework balancing optimality with computational efficiency, automatically generating effective distributed plans that capture both the heterogeneous structure of modern neural networks and the underlying hardware constraints. In experiments comparing against expert-designed strategies like DeepSeek's DualPipe, our framework achieves comparable or superior performance, reducing computational bubbles by half under the same memory constraints. The framework's versatility extends beyond throughput optimization to incorporate hardware utilization maximization, memory capacity constraints, and other considerations or potential strategies. Such capabilities position our solution as both a valuable research tool for exploring optimal parallelization strategies and a practical industrial solution for large-scale AI deployment.

[Arxiv](https://arxiv.org/abs/2503.09357)