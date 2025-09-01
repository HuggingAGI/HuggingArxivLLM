# SwizzlePerf：硬件感知大型语言模型助力GPU内核性能优化

发布时间：2025年08月27日

`Agent` `工业与制造`

> SwizzlePerf: Hardware-Aware LLMs for GPU Kernel Performance Optimization

# 摘要

> 大型语言模型（LLMs）在GPU内核性能工程领域虽有进展，却依赖低效的基于搜索的方法——这类方法仅围绕运行时展开优化。但现有方案均缺失人类性能工程师实现近最优硬件利用率的核心能力：硬件感知。通过结合工作负载的特定内存访问模式、架构规格、过滤后的性能分析日志及历史性能反思，我们可针对性地对底层硬件进行软件级优化。SwizzlePerf正是通过赋予LLMs明确的硬件感知能力，为分布式架构上的GPU内核自动生成空间优化方案。
  以GEMM内核为例，SwizzlePerf生成特定硬件的最优混洗模式仅需不到5分钟，而专业性能工程师完成这项工作则需2周。在包含10个不同机器学习与科学内核的测试套件中，SwizzlePerf可为其中9个生成混洗模式，实现最高2.06倍的加速比和70%的L2命中率提升。这项研究是系统性构建硬件感知LLM性能工程智能体的开创性探索，未来还将有更多后续工作。

> Large language models (LLMs) have shown progress in GPU kernel performance engineering using inefficient search-based methods that optimize around runtime. Any existing approach lacks a key characteristic that human performance engineers rely on for near-optimal utilization -- hardware-awareness. By leveraging the workload's specific memory access patterns, architecture specifications, filtered profiling logs, and reflections on historical performance, we can make software-level optimizations that are tailored to the underlying hardware. SwizzlePerf automatically generates spatial optimizations for GPU kernels on disaggregated architectures by giving LLMs explicit hardware-awareness.
  For a GEMM kernel, SwizzlePerf takes less than 5 minutes to generate the same hardware-specific optimal swizzling pattern that took expert performance engineers 2 weeks to find. On a suite of 10 diverse ML and Science kernels, SwizzlePerf can generate swizzling patterns for 9 of the kernels that achieve up to a 2.06x speedup and 70% improvement in L2 hit rate. This work is the first of many steps toward systematically creating hardware-aware LLM performance engineering agents.

[Arxiv](https://arxiv.org/abs/2508.20258)