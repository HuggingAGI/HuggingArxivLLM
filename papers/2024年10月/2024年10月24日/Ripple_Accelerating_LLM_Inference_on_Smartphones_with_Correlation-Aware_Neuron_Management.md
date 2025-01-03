# Ripple: 利用相关性感知神经元管理加速智能手机上的LLM推理

发布时间：2024年10月24日

`LLM应用

理由：这篇论文主要讨论了如何在智能手机等移动设备上优化大型语言模型（LLMs）的推理过程，特别是通过优化神经元在闪存中的放置来减少I/O操作和提高数据传输效率。虽然涉及了硬件优化和存储管理，但其核心目标是为了更好地部署和应用LLMs，因此应归类为LLM应用。` `移动设备` `人工智能`

> Ripple: Accelerating LLM Inference on Smartphones with Correlation-Aware Neuron Management

# 摘要

> 大型语言模型（LLMs）在各领域表现卓越，但其庞大的计算和内存需求使得在移动设备上部署成为一大挑战。尽管轻量级LLMs已应运而生，但其模型精度却有所下降。相比之下，基于稀疏性的技术通过选择性传输相关神经元至DRAM，同时将完整模型保留在外部存储（如闪存）中，从而最小化DRAM使用。然而，这种方法在IOPS受限的智能手机上，因大量I/O操作而受限。
    本文提出Ripple，一种通过在闪存中优化神经元放置来加速智能手机上LLM推理的新方法。Ripple利用神经元共激活概念，将频繁共激活的神经元链接，以促进连续读取并优化数据传输效率。该方法分为两阶段：离线阶段根据共激活模式重新组织神经元放置，在线阶段则采用定制数据访问和缓存策略，以更好地适配硬件特性。在多种智能手机和LLMs上的评估显示，Ripple在I/O延迟上比现有技术提升最多5.93倍。作为首个在稀疏性下优化存储放置的解决方案，Ripple探索了稀疏性驱动算法与存储级系统协同设计在LLM推理中的新优化空间。

> Large Language Models (LLMs) have achieved remarkable success across various domains, yet deploying them on mobile devices remains an arduous challenge due to their extensive computational and memory demands. While lightweight LLMs have been developed to fit mobile environments, they suffer from degraded model accuracy. In contrast, sparsity-based techniques minimize DRAM usage by selectively transferring only relevant neurons to DRAM while retaining the full model in external storage, such as flash. However, such approaches are critically limited by numerous I/O operations, particularly on smartphones with severe IOPS constraints.
  In this paper, we propose Ripple, a novel approach that accelerates LLM inference on smartphones by optimizing neuron placement in flash memory. Ripple leverages the concept of Neuron Co-Activation, where neurons frequently activated together are linked to facilitate continuous read access and optimize data transfer efficiency. Our approach incorporates a two-stage solution: an offline stage that reorganizes neuron placement based on co-activation patterns, and an online stage that employs tailored data access and caching strategies to align well with hardware characteristics. Evaluations conducted on a variety of smartphones and LLMs demonstrate that Ripple achieves up to 5.93x improvements in I/O latency compared to the state-of-the-art. As the first solution to optimize storage placement under sparsity, Ripple explores a new optimization space at the intersection of sparsity-driven algorithm and storage-level system co-design in LLM inference.

[Arxiv](https://arxiv.org/abs/2410.19274)