# 迈向鲁棒智能体驱动的CUDA内核基准测试、验证与优化

发布时间：2025年09月16日

`Agent` `工业与制造`

> Towards Robust Agentic CUDA Kernel Benchmarking, Verification, and Optimization

# 摘要

> 大型语言模型（LLMs）的最新进展表明，它们在扩展软件工程任务的测试时计算方面成效显著。但这些方法往往聚焦于高层级解决方案，对低层级CUDA内核实现的优化关注不足。此外，现有内核生成基准存在可利用的漏洞，且测试条件多样性不足，阻碍了对真实泛化能力的评估。为解决这些问题，我们提出了robust-kbench——一个能在多样场景下对内核性能和正确性进行严格评估的新基准。同时，我们还提出了一个全面的智能体框架，可自动完成CUDA内核的发现、验证与优化。该流程让前沿LLMs能将torch代码转换为CUDA内核，并在我们的稳健评估环境中迭代提升运行时性能。我们的顺序工作流程首先将PyTorch代码转换为等效的CUDA内核，随后通过一种专为CUDA生态系统定制的新型进化元生成过程优化运行时性能——这一过程由基于LLM的验证器提供指导，确保正确性并实现高效过滤。经robust-kbench评估，我们的方法生成的CUDA内核在实际应用中（包括前向和反向传播）性能超过torch实现。该方法还能融合操作并部署多种运行时优化策略。验证器工作流程可准确识别错误内核，从而提升硬件验证效率。

> Recent advances in large language models (LLMs) demonstrate their effectiveness in scaling test-time compute for software engineering tasks. However, these approaches often focus on high-level solutions, with limited attention to optimizing low-level CUDA kernel implementations. Additionally, existing kernel generation benchmarks suffer from exploitable loopholes and insufficient diversity in testing conditions, hindering true generalization assessment. To address these limitations, we introduce robust-kbench, a new benchmark for rigorous evaluation of kernel performance and correctness across varied scenarios. Furthermore, we present a comprehensive agentic framework that automates CUDA kernel discovery, verification, and optimization. This pipeline enables frontier LLMs to translate torch code to CUDA kernels and iteratively improve their runtime within our robust evaluation setting. Our sequential workflow first translates PyTorch code into equivalent CUDA kernels. It then optimizes their runtime using a novel evolutionary meta-generation procedure tailored to the CUDA ecosystem, guided by LLM-based verifiers for correctness and efficient filtering. Evaluated on robust-kbench, our approach produces CUDA kernels outperforming torch implementations for practical applications, including forward and backward passes. It can fuse operations and deploy various runtime optimization strategies. The verifier workflow accurately classifies incorrect kernels, enhancing hardware verification efficiency.

[Arxiv](https://arxiv.org/abs/2509.14279)