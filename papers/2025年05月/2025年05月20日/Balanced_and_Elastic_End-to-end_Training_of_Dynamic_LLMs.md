# 动态大型语言模型的平衡与弹性端到端训练方法

发布时间：2025年05月20日

`LLM应用` `人工智能` `高性能计算`

> Balanced and Elastic End-to-end Training of Dynamic LLMs

# 摘要

> 为降低大型语言模型（LLMs）的计算和内存成本，出现了多种动态工作负载减少方案，包括专家混合模型（MoEs）、参数剪枝、层冻结、稀疏注意力机制、早期标记退出和深度混合模型（MoDs）。然而，这些方法带来了严重的负载不平衡问题，限制了其在大规模分布式训练中的实用性。我们提出了DynMo，这是一个自主的动态负载均衡解决方案，能够在训练动态模型时使用管道并行技术确保计算资源的最优分配。DynMo能够自适应地平衡工作负载，动态地将任务打包到更少的工作节点中以释放空闲资源，并且支持多GPU单节点和多节点系统。与静态训练方法（如Megatron-LM和DeepSpeed）相比，DynMo在使用MoEs时训练速度提升1.23倍，在参数剪枝时提升3.18倍，在层冻结时提升2.23倍，在稀疏注意力机制时提升4.02倍，在早期标记退出时提升4.52倍，在深度混合模型时提升1.17倍。DynMo的代码仓库地址为https://anonymous.4open.science/r/DynMo-4D04/。

> To reduce computational and memory costs in Large Language Models (LLMs), dynamic workload reduction schemes like Mixture of Experts (MoEs), parameter pruning, layer freezing, sparse attention, early token exit, and Mixture of Depths (MoDs) have emerged. However, these methods introduce severe workload imbalances, limiting their practicality for large-scale distributed training. We propose DynMo, an autonomous dynamic load balancing solution that ensures optimal compute distribution when using pipeline parallelism in training dynamic models. DynMo adaptively balances workloads, dynamically packs tasks into fewer workers to free idle resources, and supports both multi-GPU single-node and multi-node systems. Compared to static training methods (Megatron-LM, DeepSpeed), DynMo accelerates training by up to 1.23x (MoEs), 3.18x (pruning), 2.23x (layer freezing), 4.02x (sparse attention), 4.52x (early exit), and 1.17x (MoDs). DynMo is available at https://anonymous.4open.science/r/DynMo-4D04/.

[Arxiv](https://arxiv.org/abs/2505.14864)