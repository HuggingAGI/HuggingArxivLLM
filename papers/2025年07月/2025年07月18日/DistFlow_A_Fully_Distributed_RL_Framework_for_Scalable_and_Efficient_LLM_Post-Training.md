# DistFlow：专为大型语言模型（LLM）后训练设计的高效、可扩展全分布式强化学习框架。

发布时间：2025年07月18日

`其他` `人工智能` `分布式系统`

> DistFlow: A Fully Distributed RL Framework for Scalable and Efficient LLM Post-Training

# 摘要

> 强化学习（RL）已成为大型语言模型（LLM）后训练阶段的关键技术。在大型语言模型中，有效扩展强化学习能力是解锁高级推理能力并确保安全、目标对齐行为的关键。主流框架通常采用混合控制器架构，其中单一控制器负责整体执行逻辑的分发和管理，以及整体数据传输，而多控制器则执行分布式计算。对于大规模强化学习而言，轻微的负载不平衡可能导致显著的性能瓶颈，最终限制系统的可扩展性。为了解决这一限制，我们引入了DistFlow，一个全新的、完全分布式的强化学习框架，旨在突破扩展限制。我们采用了多控制器范式，将数据传输和执行任务分发给所有工作节点，从而消除了中心化节点。这使得每个工作节点能够独立运行，从而实现近乎线性的扩展，支持数千个GPU，并带来显著的效率提升。此外，我们的架构将资源配置与执行逻辑解耦，使每个工作节点能够拥有独特的执行流程，为快速、经济的算法实验提供了极大的灵活性。大量实验表明，DistFlow实现了卓越的线性扩展能力，并在端到端吞吐量上比最先进（SOTA）框架提升了高达7倍的性能。

> Reinforcement learning (RL) has become the pivotal post-training technique for large language model. Effectively scaling reinforcement learning is now the key to unlocking advanced reasoning capabilities and ensuring safe, goal-aligned behavior in the most powerful LLMs. Mainstream frameworks usually employ a hybrid-controller architecture where a single-controller dispatches the overall execution logic and manages overall data transfer and the multi-controller executes distributed computation. For large-scale reinforcement learning, minor load imbalances can introduce significant bottlenecks, ultimately constraining the scalability of the system. To address this limitation, we introduce DistFlow, a novel, fully distributed RL framework designed to break scaling barrier. We adopt a multi-controller paradigm that dispatches data transfer and execution tasks to all workers, which eliminates the centralized node. This allows each worker to operate independently, leading to near-linear scalability up to thousands of GPUs and dramatic efficiency gains. Furthermore, our architecture decouples resource configuration from execution logic, allowing each worker to have a unique execution flow, offering significant flexibility for rapid and cost-effective algorithmic experimentation. Extensive experiments show that DistFlow achieves excellent linear scalability and up to a 7x end-to-end throughput improvement over state-of-the-art (SOTA) frameworks.

[Arxiv](https://arxiv.org/abs/2507.13833)