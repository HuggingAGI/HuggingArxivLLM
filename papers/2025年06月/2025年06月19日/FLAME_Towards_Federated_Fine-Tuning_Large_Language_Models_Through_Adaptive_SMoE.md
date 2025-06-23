# FLAME：探索利用自适应SMoE技术实现联合微调大型语言模型

发布时间：2025年06月19日

`LLM理论` `分布式系统` `资源管理`

> FLAME: Towards Federated Fine-Tuning Large Language Models Through Adaptive SMoE

# 摘要

> 现有的资源自适应 LoRA 联邦微调方法允许客户端使用全局 LoRA 矩阵的压缩版本对模型进行微调，以适应客户端之间的各种计算资源。然而，这种压缩要求会导致由于信息丢失而性能不佳。为了解决这个问题，我们提出了 FLAME，一个基于稀疏专家混合（Sparse Mixture-of-Experts，SMoE）架构的新型联邦学习框架。

与之前的方法不同，FLAME 保留完整的（未压缩）全局 LoRA 矩阵，并通过调整每个客户端激活的专家数量来实现客户端的自适应能力。然而，将 SMoE 引入联邦学习带来了独特的挑战，具体来说，是部分专家激活导致的输出幅度不匹配，以及客户端之间专家训练质量的不平衡。FLAME 通过一种轻量级的重新缩放机制和一种感知激活的聚合方案来解决这些挑战。

在各种计算设置下的实验证明，FLAME 一致优于现有方法，为资源自适应的联邦学习提供了一个强大而有效的解决方案。


> Existing resource-adaptive LoRA federated fine-tuning methods enable clients to fine-tune models using compressed versions of global LoRA matrices, in order to accommodate various compute resources across clients. This compression requirement will lead to suboptimal performance due to information loss. To address this, we propose FLAME, a novel federated learning framework based on the Sparse Mixture-of-Experts (SMoE) architecture. Unlike prior approaches, FLAME retains full (uncompressed) global LoRA matrices and achieves client-side adaptability by varying the number of activated experts per client. However, incorporating SMoE into federated learning introduces unique challenges, specifically, the mismatch in output magnitude from partial expert activation and the imbalance in expert training quality across clients. FLAME tackles these challenges through a lightweight rescaling mechanism and an activation-aware aggregation scheme. Empirical results across diverse computational settings demonstrate that FLAME consistently outperforms existing methods, providing a robust and effective solution for resource-adaptive federated learning.

[Arxiv](https://arxiv.org/abs/2506.16600)