# IMTP: 基于搜索的内存张量程序代码生成

发布时间：2024年12月27日

`LLM应用

理由：这篇论文主要讨论了DRAM-PIM技术在加速大型语言模型（LLMs）中的应用，并提出了一个名为IMTP的张量编译器来优化DRAM-PIM系统的性能。虽然论文涉及硬件优化，但其核心目标是提升LLMs的性能，因此应归类为LLM应用。` `计算机硬件` `内存优化`

> IMTP: Search-based Code Generation for In-memory Tensor Programs

# 摘要

> # 摘要
DRAM-PIM（Processing-in-DRAM）技术在现代应用（如大型语言模型，LLMs）中展现出加速内存密集型操作的巨大潜力。然而，当前的DRAM-PIM软件栈面临诸多挑战，包括手工调优库的限制、高级抽象支持的不足以及缺乏系统化优化框架。为此，我们推出了IMTP，一个专为UPMEM设计的基于搜索的优化张量编译器。IMTP的核心亮点包括：（1）自动搜索主机与内核张量程序的联合空间，（2）针对边界条件的高效PIM感知优化，以及（3）适用于UPMEM系统扩展搜索空间的改进搜索算法。实验结果显示，IMTP在UPMEM硬件上实现了UPMEM基准内核性能提升高达8.21倍，GPT-J层性能提升5.33倍。IMTP是首个为DRAM-PIM系统提供全自动、集成自动调优代码生成的张量编译器。通过连接高级张量计算抽象与低级硬件需求，IMTP为提升DRAM-PIM的可编程性和优化效率奠定了基础。

> Processing-in-DRAM (DRAM-PIM) has emerged as a promising technology for accelerating memory-intensive operations in modern applications, such as Large Language Models (LLMs). Despite its potential, current software stacks for DRAM-PIM face significant challenges, including reliance on hand-tuned libraries that hinder programmability, limited support for high-level abstractions, and the lack of systematic optimization frameworks. To address these limitations, we present IMTP, a search-based optimizing tensor compiler for UPMEM. Key features of IMTP include: (1) automated searches of the joint search space for host and kernel tensor programs, (2) PIM-aware optimizations for efficiently handling boundary conditions, and (3) improved search algorithms for the expanded search space of UPMEM systems. Our experimental results on UPMEM hardware demonstrate performance gains of up to 8.21x for various UPMEM benchmark kernels and 5.33x for GPT-J layers. To the best of our knowledge, IMTP is the first tensor compiler to provide fully automated, autotuning-integrated code generation support for a DRAM-PIM system. By bridging the gap between high-level tensor computation abstractions and low-level hardware-specific requirements, IMTP establishes a foundation for advancing DRAM-PIM programmability and enabling streamlined optimization.

[Arxiv](https://arxiv.org/abs/2412.19630)