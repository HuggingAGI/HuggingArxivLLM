# # CUDA-LLM：LLMs 能够编写高效的 CUDA 内核

发布时间：2025年06月10日

`LLM应用` `高性能计算` `GPU编程`

> CUDA-LLM: LLMs Can Write Efficient CUDA Kernels

# 摘要

> 大型语言模型（LLMs）在通用代码生成方面表现卓越，但在生成深度硬件特定、架构感知且性能关键的代码，尤其是针对大规模并行GPU的代码时，仍面临巨大挑战。本研究致力于探索LLMs在CUDA程序自动化生成与优化中的应用，目标是生成能够充分挖掘底层硬件潜力的高性能GPU内核。

为解决这一难题，我们提出了一种名为	extbf{特征搜索与强化（FSR）}的创新框架。FSR通过广泛的多样化测试用例验证，同时优化编译和功能性正确性，并通过实际测量目标GPU上的内核执行延迟来评估运行时性能。这一方法不仅使LLMs能够生成语法和语义正确的CUDA代码，还能根据GPU架构的特点，进行迭代优化以提升效率。

我们在涵盖AI工作负载和计算密集型算法的具有代表性的CUDA内核上评估了FSR。实验结果表明，配备FSR的LLMs不仅始终保证正确性，其自动生成的内核在执行速度上更是比普通人工编写代码快了最高179倍。这一发现凸显了将LLMs与性能强化相结合，用于自动化针对硬件特定、架构敏感且性能关键应用的GPU编程的巨大潜力。

> Large Language Models (LLMs) have demonstrated strong capabilities in general-purpose code generation. However, generating the code which is deeply hardware-specific, architecture-aware, and performance-critical, especially for massively parallel GPUs, remains a complex challenge. In this work, we explore the use of LLMs for the automated generation and optimization of CUDA programs, with the goal of producing high-performance GPU kernels that fully exploit the underlying hardware. To address this challenge, we propose a novel framework called \textbf{Feature Search and Reinforcement (FSR)}. FSR jointly optimizes compilation and functional correctness, as well as the runtime performance, which are validated through extensive and diverse test cases, and measured by actual kernel execution latency on the target GPU, respectively. This approach enables LLMs not only to generate syntactically and semantically correct CUDA code but also to iteratively refine it for efficiency, tailored to the characteristics of the GPU architecture. We evaluate FSR on representative CUDA kernels, covering AI workloads and computational intensive algorithms. Our results show that LLMs augmented with FSR consistently guarantee correctness rates. Meanwhile, the automatically generated kernels can outperform general human-written code by a factor of up to 179$\times$ in execution speeds. These findings highlight the potential of combining LLMs with performance reinforcement to automate GPU programming for hardware-specific, architecture-sensitive, and performance-critical applications.

[Arxiv](https://arxiv.org/abs/2506.09092)