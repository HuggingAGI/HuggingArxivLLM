# 基于FPGA的快速增量学习的高能效分层神经网络

发布时间：2025年09月18日

`其他` `能源与环保`

> The Energy-Efficient Hierarchical Neural Network with Fast FPGA-Based Incremental Learning

# 摘要

> 深度学习（尤其是基础模型和大型语言模型（LLMs）等大规模架构）日益增长的计算与能源需求，给可持续发展带来了严峻挑战。传统基于梯度的训练方法效率低下，不仅需要大量迭代更新，还会消耗高额能源。为解决这些问题，我们提出一种混合框架，它将层次分解与基于FPGA的直接方程求解及增量学习相融合。该方法将神经网络分为两个功能层：低层通过FPGA单步方程求解优化，实现高效可并行的特征提取；高层则采用自适应增量学习，支持无需全量重训练的持续更新。在此基础上，我们进一步提出复合LLM框架，在两个层级明确部署LLM模块：低层LLM以极低的能源开销处理可复用的表示学习，高层LLM通过能源感知更新实现自适应决策。这种集成设计提升了可扩展性，减少了冗余计算，且符合可持续AI的理念。理论分析与架构设计表明，我们的方法在保持模型高性能的同时大幅降低了计算成本，非常适合边缘部署及能源受限环境下的实时适配。

> The rising computational and energy demands of deep learning, particularly in large-scale architectures such as foundation models and large language models (LLMs), pose significant challenges to sustainability. Traditional gradient-based training methods are inefficient, requiring numerous iterative updates and high power consumption. To address these limitations, we propose a hybrid framework that combines hierarchical decomposition with FPGA-based direct equation solving and incremental learning. Our method divides the neural network into two functional tiers: lower layers are optimized via single-step equation solving on FPGAs for efficient and parallelizable feature extraction, while higher layers employ adaptive incremental learning to support continual updates without full retraining. Building upon this foundation, we introduce the Compound LLM framework, which explicitly deploys LLM modules across both hierarchy levels. The lower-level LLM handles reusable representation learning with minimal energy overhead, while the upper-level LLM performs adaptive decision-making through energy-aware updates. This integrated design enhances scalability, reduces redundant computation, and aligns with the principles of sustainable AI. Theoretical analysis and architectural insights demonstrate that our method reduces computational costs significantly while preserving high model performance, making it well-suited for edge deployment and real-time adaptation in energy-constrained environments.

[Arxiv](https://arxiv.org/abs/2509.15097)