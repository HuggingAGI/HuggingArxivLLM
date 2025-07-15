# Pimba：面向后变压器时代大语言模型服务的内存计算加速方案

发布时间：2025年07月14日

`LLM理论` `大型语言模型` `硬件加速器`

> Pimba: A Processing-in-Memory Acceleration for Post-Transformer Large Language Model Serving

# 摘要

> Transformer是当今大型语言模型（LLMs）的核心驱动力，为它们的性能和灵活性奠定了基础。然而，随着序列长度的增加，其计算和内存成本也在不断攀升，这对长上下文推理的扩展性提出了挑战。为此，算法社区正在探索替代架构，例如状态空间模型（SSMs）、线性注意力和循环神经网络（RNNs），我们将这些统称为后Transformer模型。这一转变带来了关键挑战：如何在一个统一框架内高效支持Transformer和后Transformer LLMs的服务系统。为此，我们分析了Transformer和后Transformer LLMs的性能特点。尽管它们在算法上存在差异，但两者在批量推理中都因Transformer中的注意力机制和后Transformer中的状态更新而受到内存带宽的限制。进一步分析揭示了两个额外的见解：（1）与注意力机制不同，状态更新操作会带来高昂的硬件成本，使得基于每个存储单元的PIM加速效率低下；（2）不同的低精度算术方法提供了各异的准确性和面积权衡，而我们发现微软的MX是帕累托最优的选择。基于这些见解，我们设计了Pimba，作为一个由状态更新处理单元（SPUs）组成的阵列，每个SPU由两个存储单元共享，以实现对PIM的交错访问。每个SPU包含一个状态更新处理引擎（SPE），该引擎由基于MX的量化算术实现的逐元素乘法器和加法器组成，能够高效执行状态更新和注意力操作。我们的评估表明，与优化的LLM GPU系统和GPU+PIM系统相比，Pimba分别实现了高达3.2倍和2.1倍的令牌生成吞吐量提升。

> Transformers are the driving force behind today's Large Language Models (LLMs), serving as the foundation for their performance and versatility. Yet, their compute and memory costs grow with sequence length, posing scalability challenges for long-context inferencing. In response, the algorithm community is exploring alternative architectures, such as state space models (SSMs), linear attention, and recurrent neural networks (RNNs), which we refer to as post-transformers. This shift presents a key challenge: building a serving system that efficiently supports both transformer and post-transformer LLMs within a unified framework. To address this challenge, we analyze the performance characteristics of transformer and post-transformer LLMs. Despite their algorithmic differences, both are fundamentally limited by memory bandwidth under batched inference due to attention in transformers and state updates in post-transformers. Further analyses suggest two additional insights: (1) state update operations, unlike attention, incur high hardware cost, making per-bank PIM acceleration inefficient, and (2) different low-precision arithmetic methods offer varying accuracy-area tradeoffs, while we identify Microsoft's MX as the Pareto-optimal choice. Building on these insights, we design Pimba as an array of State-update Processing Units (SPUs), each shared between two banks to enable interleaved access to PIM. Each SPU includes a State-update Processing Engine (SPE) that comprises element-wise multipliers and adders using MX-based quantized arithmetic, enabling efficient execution of state update and attention operations. Our evaluation shows that, compared to LLM-optimized GPU and GPU+PIM systems, Pimba achieves up to 3.2x and 2.1x higher token generation throughput, respectively.

[Arxiv](https://arxiv.org/abs/2507.10178)