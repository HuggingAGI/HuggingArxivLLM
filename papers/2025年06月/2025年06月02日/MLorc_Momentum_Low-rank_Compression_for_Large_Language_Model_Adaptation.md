# MLorc：动量低秩压缩技术助力大型语言模型的适应性优化

发布时间：2025年06月02日

`LLM理论` `计算机科学`

> MLorc: Momentum Low-rank Compression for Large Language Model Adaptation

# 摘要

> 大型语言模型（LLMs）规模的不断扩大带来了全参数微调内存需求激增的挑战。为应对这一问题，我们提出了一种名为动量低秩压缩（MLorc）的创新内存高效训练方法。与现有低秩方法（如LoRA和GaLore）不同，MLorc通过直接压缩和重构动量而非梯度，避免了对权重更新矩阵施加固定秩约束，从而更有效地保留了全参数微调的训练动态。实验结果表明，MLorc在内存效率方面表现卓越，其性能可与小秩（例如$r=4$）下的全微调相媲美甚至更优，同时在不同优化器上展现出良好的通用性，且不会影响训练时间和内存效率。此外，我们在合理假设下为MLorc的收敛性提供了理论支持。

> With increasing size of large language models (LLMs), full-parameter fine-tuning imposes substantial memory demands. To alleviate this, we propose a novel memory-efficient training paradigm called Momentum Low-rank compression (MLorc). By directly compressing and reconstructing momentum rather than gradients, MLorc avoids imposing a fixed-rank constraint on weight update matrices and better preserves the training dynamics of full-parameter fine-tuning, in contrast to existing low-rank approaches such as LoRA and GaLore. Empirically, MLorc consistently outperforms other memory-efficient training methods, matches or even exceeds the performance of full fine-tuning with a small rank (e.g., $r=4$), and generalizes well across different optimizers -- all while not compromising time or memory efficiency. Furthermore, we provide a theoretical guarantee for its convergence under reasonable assumptions.

[Arxiv](https://arxiv.org/abs/2506.01897)