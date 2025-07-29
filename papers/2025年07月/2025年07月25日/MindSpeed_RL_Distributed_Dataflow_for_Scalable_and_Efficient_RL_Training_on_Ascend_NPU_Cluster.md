# MindSpeed RL：基于分布式数据流的昇腾NPU集群强化学习高效训练解决方案。MindSpeed RL 通过创新的分布式数据流技术，助力实现高效且可扩展的强化学习训练，为昇腾NPU集群提供强大的支持。

发布时间：2025年07月25日

`其他` `大规模训练`

> MindSpeed RL: Distributed Dataflow for Scalable and Efficient RL Training on Ascend NPU Cluster

# 摘要

> 强化学习（RL）正日益成为对齐大型语言模型的重要范式。传统RL算法通常采用多节点协同方式，并可通过图结构进行建模，其中节点代表工作节点状态，边则表示节点间的数据流动。然而，由于节点间存在大量跨节点依赖关系，RL训练系统往往面临集群扩展性差和内存利用率低的挑战。本文介绍的MindSpeed RL是一个高效的大规模RL训练系统。与现有集中式方法不同，MindSpeed RL从分布式视角重新设计了RL训练中的关键数据依赖关系，即样本流和分片流。一方面，基于传统回放缓冲区机制，我们提出了一种分布式传输码头策略，有效降低了样本流中的调度开销；同时，通过创新的allgather--swap策略，成功消除了分片流中的冗余内存占用。此外，MindSpeed RL还集成了多种并行化策略和加速技术，实现系统级优化。实验结果表明，在Qwen2.5-Dense-7B/32B、Qwen3-MoE-30B和DeepSeek-R1-MoE-671B等流行模型的RL训练中，MindSpeed RL的吞吐量比现有系统提升了1.42~3.97倍。最终，我们开源了MindSpeed RL，并在昇腾超级计算集群（配备384个神经处理单元）上完成了所有实验，充分展示了昇腾平台的强大性能和可靠性。

> Reinforcement learning (RL) is a paradigm increasingly used to align large language models. Popular RL algorithms utilize multiple workers and can be modeled as a graph, where each node is the status of a worker and each edge represents dataflow between nodes. Owing to the heavy cross-node dependencies, the RL training system usually suffers from poor cluster scalability and low memory utilization. In this article, we introduce MindSpeed RL, an effective and efficient system for large-scale RL training. Unlike existing centralized methods, MindSpeed RL organizes the essential data dependencies in RL training, i.e., sample flow and resharding flow, from a distributed view. On the one hand, a distributed transfer dock strategy, which sets controllers and warehouses on the basis of the conventional replay buffer, is designed to release the dispatch overhead in the sample flow. A practical allgather--swap strategy is presented to eliminate redundant memory usage in resharding flow. In addition, MindSpeed RL further integrates numerous parallelization strategies and acceleration techniques for systematic optimization. Compared with existing state-of-the-art systems, comprehensive experiments on the RL training of popular Qwen2.5-Dense-7B/32B, Qwen3-MoE-30B, and DeepSeek-R1-MoE-671B show that MindSpeed RL increases the throughput by 1.42 ~ 3.97 times. Finally, we open--source MindSpeed RL and perform all the experiments on a super pod of Ascend with 384 neural processing units (NPUs) to demonstrate the powerful performance and reliability of Ascend.

[Arxiv](https://arxiv.org/abs/2507.19017)