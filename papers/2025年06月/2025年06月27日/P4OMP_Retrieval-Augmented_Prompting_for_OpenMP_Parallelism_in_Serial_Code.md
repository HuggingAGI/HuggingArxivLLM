# P4OMP：在串行代码中实现OpenMP并行性的检索增强提示方法

发布时间：2025年06月27日

`RAG` `并行编程` `高性能计算`

> P4OMP: Retrieval-Augmented Prompting for OpenMP Parallelism in Serial Code

# 摘要

> 我们提出 P4OMP，一个基于大型语言模型的检索增强框架，用于将串行 C/C++ 代码转换为带有 OpenMP 注释的并行代码。这是首个无需模型微调或编译器插桩，直接利用基于检索的提示生成 OpenMP 指令的系统。通过结合结构化的 OpenMP 教程知识，P4OMP 利用检索增强生成（RAG）技术，显著提升了提示驱动代码生成的可靠性。与仅使用 GPT-3.5-Turbo 的基本方法相比，P4OMP 在语法正确性方面表现更佳。我们在包含 108 个真实世界 C++ 程序的基准测试中，对比了 P4OMP 与基本方法的表现。结果显示，P4OMP 在所有可并行化的案例中实现了 100% 的编译成功率，而基本方法在 20 个案例中未能成功编译。由于 OpenMP 的限制，6 个依赖于非随机访问迭代器或线程不安全构造的案例被排除。详细分析表明，P4OMP 能够有效避免常见作用域错误、语法误用和无效指令组合，这些问题通常会影响基本方法生成的代码。此外，我们在 HPC 集群上展示了 P4OMP 在七个计算密集型基准测试中的卓越运行时扩展能力。P4OMP 提供了一个健壮且模块化的管道，显著提升了 LLM 生成的 OpenMP 代码的可靠性和适用性。

> We present P4OMP, a retrieval-augmented framework for transforming serial C/C++ code into OpenMP-annotated parallel code using large language models (LLMs). To our knowledge, this is the first system to apply retrieval-based prompting for OpenMP pragma correctness without model fine-tuning or compiler instrumentation. P4OMP leverages Retrieval-Augmented Generation (RAG) with structured instructional knowledge from OpenMP tutorials to improve the reliability of prompt-driven code generation. By grounding generation in the retrieved context, P4OMP improves syntactic correctness compared to baseline prompting with GPT-3.5-Turbo. We evaluate P4OMP against a baseline, GPT-3.5-Turbo without retrieval, on a comprehensive benchmark of 108 real-world C++ programs drawn from Stack Overflow, PolyBench, and NAS benchmark suites. P4OMP achieves 100% compilation success on all parallelizable cases, while the baseline fails to compile in 20 out of 108 cases. Six cases that rely on non-random-access iterators or thread-unsafe constructs are excluded due to fundamental OpenMP limitations. A detailed analysis demonstrates how P4OMP consistently avoids scoping errors, syntactic misuse, and invalid directive combinations that commonly affect baseline-generated code. We further demonstrate strong runtime scaling across seven compute-intensive benchmarks on an HPC cluster. P4OMP offers a robust, modular pipeline that significantly improves the reliability and applicability of LLM-generated OpenMP code.

[Arxiv](https://arxiv.org/abs/2506.22703)