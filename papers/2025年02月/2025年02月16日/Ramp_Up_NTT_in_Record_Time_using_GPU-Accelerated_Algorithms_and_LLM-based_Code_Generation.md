# GPU加速算法与大语言模型代码生成助力NTT实现创纪录提升。

发布时间：2025年02月16日

`其他` `隐私保护` `机器学习`

> Ramp Up NTT in Record Time using GPU-Accelerated Algorithms and LLM-based Code Generation

# 摘要

> 同态加密（HE）是隐私保护机器学习（PPML）的核心技术基石，但其效率瓶颈也广为人知。为此，许多人提出了多种GPU加速的加密方案，但这些方法通常需要针对特定算法进行复杂的修改，并且与特定的GPU和操作系统紧密耦合。如何普遍提供更实用的GPU加速加密算法实现成为一个值得探讨的问题。鉴于大型语言模型（LLMs）强大的代码生成能力，我们旨在探索其潜力，通过CPU友好的代码自动生成GPU友好的算法代码。本文聚焦于HE的核心机制——数论变换（NTT）。我们开发并优化了一个GPU友好的NTT（GNTT）家族，充分利用PyTorch的快速矩阵计算和预计算功能，实现约62倍的速度提升，显著超越现有方案。同时，我们探索了利用DeepSeek-R1、OpenAI o1和o3-mini等LLMs生成GPU友好代码的可能性，并发现了许多有趣的研究结果。例如，令人意外的是，我们的实验表明DeepSeek-R1在性能上远超OpenAI o3-mini和o1，但仍然无法超越我们的优化协议。这些发现为加速PPML和提升LLMs的代码生成能力提供了宝贵的见解。代码可在以下链接获取：https://github.com/LMPC-Lab/GenGPUCrypto.

> Homomorphic encryption (HE) is a core building block in privacy-preserving machine learning (PPML), but HE is also widely known as its efficiency bottleneck. Therefore, many GPU-accelerated cryptographic schemes have been proposed to improve the performance of HE. However, these methods often require complex modifications tailored to specific algorithms and are tightly coupled with specific GPU and operating systems. It is interesting to ask how to generally offer more practical GPU-accelerated cryptographic algorithm implementations. Given the powerful code generation capabilities of large language models (LLMs), we aim to explore their potential to automatically generate practical GPU-friendly algorithm code using CPU-friendly code. In this paper, we focus on number theoretic transform (NTT) -- the core mechanism of HE. We first develop and optimize a GPU-friendly NTT (GNTT) family that exploits PyTorch's fast matrix computation and precomputation, achieving an approximately 62x speedup -- a significant boost over existing ones. Then we explore GPU-friendly code generation using various LLMs, including DeepSeek-R1, OpenAI o1 and o3-mini. We discover many interesting findings throughout the process. For instance, somewhat surprisingly, our experiments demonstrate that DeepSeek-R1 significantly outperforms OpenAI o3-mini and o1, but still cannot beat our optimized protocol. The findings provide valuable insights for turbocharging PPML and enhancing code generation capabilities of LLMs. Codes are available at: https://github.com/LMPC-Lab/GenGPUCrypto.

[Arxiv](https://arxiv.org/abs/2502.11110)