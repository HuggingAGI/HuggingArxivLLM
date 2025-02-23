# # 摘要  
TritonBench：评估大型语言模型生成Triton算子的能力

发布时间：2025年02月20日

`LLM应用

这篇论文探讨了如何将大型语言模型（LLMs）应用于生成优化的GPU代码，特别是针对Triton语言。通过引入TritonBench基准测试，研究了LLMs在高性能代码生成中的表现，属于LLM的应用领域。` `人工智能` `计算机体系结构`

> TritonBench: Benchmarking Large Language Model Capabilities for Generating Triton Operators

# 摘要

> Triton 是一种专为构建高效 GPU 内核设计的高级 Python 类语言，凭借其可移植性、灵活性和易用性，在深度学习框架中被广泛采用。然而，Triton 的编程和并行优化仍充满挑战，需要开发者不断尝试和调整。尽管大型语言模型（LLMs）在传统代码生成方面取得了显著进展，但它们难以生成既准确又性能优化的 Triton 代码，原因在于缺乏对 Triton 规范和 GPU 编程复杂性的深入理解。更关键的是，针对 Triton 的系统化评估需求迫切。为此，我们推出了 TritonBench，这是首个全面的 Triton 算子生成基准测试。TritonBench 拥有两个评估渠道：从 GitHub 精选的 184 个真实世界算子，以及与 PyTorch 接口一致的算子集合。与传统代码基准侧重功能正确性不同，TritonBench 还评估了在与行业应用对齐的广泛部署 GPU 上的效率性能。我们的研究表明，当前最先进的代码 LLM 在生成高效 Triton 算子方面表现乏力，凸显了高性能代码生成领域的显著差距。TritonBench 将在 https://github.com/thunlp/TritonBench 上公开发布。

> Triton, a high-level Python-like language designed for building efficient GPU kernels, is widely adopted in deep learning frameworks due to its portability, flexibility, and accessibility. However, programming and parallel optimization still require considerable trial and error from Triton developers. Despite advances in large language models (LLMs) for conventional code generation, these models struggle to generate accurate, performance-optimized Triton code, as they lack awareness of its specifications and the complexities of GPU programming. More critically, there is an urgent need for systematic evaluations tailored to Triton. In this work, we introduce TritonBench, the first comprehensive benchmark for Triton operator generation. TritonBench features two evaluation channels: a curated set of 184 real-world operators from GitHub and a collection of operators aligned with PyTorch interfaces. Unlike conventional code benchmarks prioritizing functional correctness, TritonBench also profiles efficiency performance on widely deployed GPUs aligned with industry applications. Our study reveals that current state-of-the-art code LLMs struggle to generate efficient Triton operators, highlighting a significant gap in high-performance code generation. TritonBench will be available at https://github.com/thunlp/TritonBench.

[Arxiv](https://arxiv.org/abs/2502.14752)