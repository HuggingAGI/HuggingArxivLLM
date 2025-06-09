# CompilerGPT：借助大型语言模型分析与处理编译器优化报告

发布时间：2025年06月06日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLM）在编译器优化中的应用，提出了一种名为CompilerGPT的框架，用于自动化处理编译器优化报告并自动重写代码以提高性能。这属于将LLM技术应用于特定领域的实际问题解决，因此归类为LLM应用。` `编译技术` `软件工程`

> CompilerGPT: Leveraging Large Language Models for Analyzing and Acting on Compiler Optimization Reports

# 摘要

> 编译器优化报告往往包含复杂的技术信息，这让程序员难以有效理解和采取行动。本文旨在研究大型语言模型（LLM）是否能够理解这些报告并自动重写代码以优化性能。

为此，我们提出了一种名为CompilerGPT的创新框架，该框架能够自动化编译器、LLM与用户自定义测试评估工具之间的交互流程。CompilerGPT通过多次迭代运行，持续优化并报告结果。

实验结果令人鼓舞：使用GPT-4o和Claude Sonnet两种主流LLM模型，结合Clang和GCC编译器的优化报告，以及五个基准代码进行测试，最高实现了6.5倍的性能提升。虽然提升幅度在不同测试中有所差异，但这一方法为提升编译器易用性和优化软件开发流程提供了重要启示。

> Current compiler optimization reports often present complex, technical information that is difficult for programmers to interpret and act upon effectively. This paper assesses the capability of large language models (LLM) to understand compiler optimization reports and automatically rewrite the code accordingly.
  To this end, the paper introduces CompilerGPT, a novel framework that automates the interaction between compilers, LLMs, and user defined test and evaluation harness. CompilerGPT's workflow runs several iterations and reports on the obtained results.
  Experiments with two leading LLM models (GPT-4o and Claude Sonnet), optimization reports from two compilers (Clang and GCC), and five benchmark codes demonstrate the potential of this approach. Speedups of up to 6.5x were obtained, though not consistently in every test. This method holds promise for improving compiler usability and streamlining the software optimization process.

[Arxiv](https://arxiv.org/abs/2506.06227)