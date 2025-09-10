# Astra：面向GPU内核性能优化的多智能体系统

发布时间：2025年09月09日

`Agent` `基础理论`

> Astra: A Multi-Agent System for GPU Kernel Performance Optimization

# 摘要

> GPU内核优化一直是高性能计算与机器学习交叉领域的核心难题。高效内核是加速大型语言模型（LLM）训练与服务的关键，但要实现高性能往往需大量手动调优。基于编译器的系统虽减轻了部分负担，却仍需投入大量手动设计与工程精力。近期研究尝试用LLM生成GPU内核，不过此前工作多聚焦于将高级PyTorch模块转译为CUDA代码。本文推出Astra——首个基于LLM的多智能体GPU内核优化系统。与以往不同，Astra并非以PyTorch模块为基准，而是从SGLang（一款广泛部署的LLM服务框架）中提取现有CUDA实现作为起点。在Astra中，专用LLM智能体通过迭代代码生成、测试、分析与规划协同工作，产出兼具正确性与高性能的内核。针对SGLang中的内核，Astra借助OpenAI o4-mini的零样本提示，平均实现1.32倍加速。详细案例研究进一步显示，LLM能自主应用循环变换、优化内存访问模式、利用CUDA内在函数及快速数学运算，带来显著性能提升。我们的研究表明，多智能体LLM系统有望成为GPU内核优化的全新范式。

> GPU kernel optimization has long been a central challenge at the intersection of high-performance computing and machine learning. Efficient kernels are crucial for accelerating large language model (LLM) training and serving, yet attaining high performance typically requires extensive manual tuning. Compiler-based systems reduce some of this burden, but still demand substantial manual design and engineering effort. Recently, researchers have explored using LLMs for GPU kernel generation, though prior work has largely focused on translating high-level PyTorch modules into CUDA code. In this work, we introduce Astra, the first LLM-based multi-agent system for GPU kernel optimization. Unlike previous approaches, Astra starts from existing CUDA implementations extracted from SGLang, a widely deployed framework for serving LLMs, rather than treating PyTorch modules as the specification. Within Astra, specialized LLM agents collaborate through iterative code generation, testing, profiling, and planning to produce kernels that are both correct and high-performance. On kernels from SGLang, Astra achieves an average speedup of 1.32x using zero-shot prompting with OpenAI o4-mini. A detailed case study further demonstrates that LLMs can autonomously apply loop transformations, optimize memory access patterns, exploit CUDA intrinsics, and leverage fast math operations to yield substantial performance gains. Our work highlights multi-agent LLM systems as a promising new paradigm for GPU kernel optimization.

[Arxiv](https://arxiv.org/abs/2509.07506)