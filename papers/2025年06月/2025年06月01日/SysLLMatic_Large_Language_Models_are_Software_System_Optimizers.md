# SysLLMatic：大型语言模型成为软件系统的优化者

发布时间：2025年06月01日

`LLM应用` `软件工程` `计算机系统`

> SysLLMatic: Large Language Models are Software System Optimizers

# 摘要

> 自动软件系统优化不仅能提升软件运行速度，还能降低成本并节省能源。传统优化方法主要依赖手动调整和编译器启发式策略，这使得它们在面对不同代码库和系统环境时显得力不从心。近期，基于大型语言模型（LLMs）的优化方法为这一领域带来了自动化解决方案，但这些方法往往难以应对现实世界中复杂软件系统和应用程序的挑战。我们提出了 SysLLMatic，一个结合 LLMs 与基于剖析的反馈和系统性能洞察的系统，旨在实现软件代码的自动优化。我们在 HumanEval_CPP（C++ 竞争性编程）、SciMark2（Java 科学内核）和 DaCapoBench（大型 Java 软件系统）这三个基准套件上进行了评估。结果显示，SysLLMatic 在延迟、吞吐量、能源效率、内存使用和 CPU 利用率等多个方面均能显著提升系统性能。它在微基准测试中表现尤为突出，超越了现有的 LLM 基线水平。在大规模应用程序代码优化中，SysLLMatic 更是超越了传统编译器优化，实现了平均相对延迟提升 1.85 倍、吞吐量提升 2.24 倍的优异成绩。我们的研究发现，通过系统化的思维和适当的性能诊断引导，LLMs 可以成为有效的软件系统优化工具。同时，我们也指出了当前方法的局限性以及在处理复杂应用程序时所面临的挑战。这项工作为跨多种语言、基准和程序规模的优化代码生成奠定了坚实的基础。


> Automatic software system optimization can improve software speed, reduce operating costs, and save energy. Traditional approaches to optimization rely on manual tuning and compiler heuristics, limiting their ability to generalize across diverse codebases and system contexts. Recent methods using Large Language Models (LLMs) offer automation to address these limitations, but often fail to scale to the complexity of real-world software systems and applications. We present SysLLMatic, a system that integrates LLMs with profiling-guided feedback and system performance insights to automatically optimize software code. We evaluate it on three benchmark suites: HumanEval_CPP (competitive programming in C++), SciMark2 (scientific kernels in Java), and DaCapoBench (large-scale software systems in Java). Results show that SysLLMatic can improve system performance, including latency, throughput, energy efficiency, memory usage, and CPU utilization. It consistently outperforms state-of-the-art LLM baselines on microbenchmarks. On large-scale application codes, it surpasses traditional compiler optimizations, achieving average relative improvements of 1.85x in latency and 2.24x in throughput. Our findings demonstrate that LLMs, guided by principled systems thinking and appropriate performance diagnostics, can serve as viable software system optimizers. We further identify limitations of our approach and the challenges involved in handling complex applications. This work provides a foundation for generating optimized code across various languages, benchmarks, and program sizes in a principled manner.

[Arxiv](https://arxiv.org/abs/2506.01249)