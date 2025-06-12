# FLoRIST：通过奇异值阈值化实现大型语言模型的高效且准确联邦微调

发布时间：2025年06月10日

`LLM理论` `联邦学习` `分布式计算`

> FLoRIST: Singular Value Thresholding for Efficient and Accurate Federated Fine-Tuning of Large Language Models

# 摘要

> 将低秩适配（LoRA）融入联邦学习，为在不共享本地数据的前提下实现大型语言模型（LLMs）的参数高效微调提供了全新解决方案。然而，现有针对联邦LoRA设计的方法在平衡通信效率、模型精度和计算成本方面面临重大挑战，尤其是在异构客户端环境中。这些方法存在以下问题：依赖简单平均操作导致聚合噪声、传输大量堆叠适配器引发通信低效，或需重构内存密集型全局权重更新矩阵并进行昂贵分解以设计客户端特定适配器。为解决这些问题，我们提出了FLoRIST框架，该框架通过数学精确聚合实现了联邦微调，同时避免了高昂的通信和计算开销。与传统方法在服务器端构建完整全局权重更新矩阵不同，FLoRIST通过对堆叠本地适配器进行独立奇异值分解，构建了高效的分解流水线。这种方法在紧凑的中间空间内运作，有效表征了各客户端LoRA的累积信息。我们还引入了可调节的奇异值阈值方法，用于服务器端的最优秩选择，从而构建了一对由所有客户端共享的全局低秩适配器。实验结果表明，FLoRIST在同构和异构设置下，始终能在卓越的通信效率和具有竞争力的性能之间取得最佳平衡。

> Integrating Low-Rank Adaptation (LoRA) into federated learning offers a promising solution for parameter-efficient fine-tuning of Large Language Models (LLMs) without sharing local data. However, several methods designed for federated LoRA present significant challenges in balancing communication efficiency, model accuracy, and computational cost, particularly among heterogeneous clients. These methods either rely on simplistic averaging of local adapters, which introduces aggregation noise, require transmitting large stacked local adapters, leading to poor communication efficiency, or necessitate reconstructing memory-dense global weight-update matrix and performing computationally expensive decomposition to design client-specific low-rank adapters. In this work, we propose FLoRIST, a federated fine-tuning framework that achieves mathematically accurate aggregation without incurring high communication or computational overhead. Instead of constructing the full global weight-update matrix at the server, FLoRIST employs an efficient decomposition pipeline by performing singular value decomposition on stacked local adapters separately. This approach operates within a compact intermediate space to represent the accumulated information from local LoRAs. We introduce tunable singular value thresholding for server-side optimal rank selection to construct a pair of global low-rank adapters shared by all clients. Extensive empirical evaluations across multiple datasets and LLMs demonstrate that FLoRIST consistently strikes the best balance between superior communication efficiency and competitive performance in both homogeneous and heterogeneous setups.

[Arxiv](https://arxiv.org/abs/2506.09199)