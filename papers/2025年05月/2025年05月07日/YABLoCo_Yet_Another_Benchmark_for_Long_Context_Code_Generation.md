# YABLoCo：长上下文代码生成的又一个基准

发布时间：2025年05月07日

`LLM应用` `软件工程` `代码生成`

> YABLoCo: Yet Another Benchmark for Long Context Code Generation

# 摘要

> 大型语言模型在代码生成等编程任务中表现出色。然而，现有研究主要针对包含数千行代码的小型或中型上下文窗口进行性能评估。而现实中的软件项目往往涉及数百万行代码。本文通过构建长上下文代码生成基准测试（YABLoCo），填补了这一研究空白。该基准测试包含从四个大型代码库中精选的215个函数，每个代码库都包含数千个函数。数据集涵盖了函数的元数据、不同依赖级别的上下文、文档字符串、函数主体和调用图。本文的主要贡献体现在三个方面：首先，该基准测试专注于C和C++语言的大型代码库中的函数主体生成，弥补了以往研究的空白；其次，基准测试涵盖了规模从20万到200万行代码的大型代码库；最后，我们提供了一个可扩展的评估流水线和一个可视化分析工具，用于高效计算目标指标和分析生成代码。这些贡献使在C和C++大型代码库中全面评估代码生成能力成为可能。
    

> Large Language Models demonstrate the ability to solve various programming tasks, including code generation. Typically, the performance of LLMs is measured on benchmarks with small or medium-sized context windows of thousands of lines of code. At the same time, in real-world software projects, repositories can span up to millions of LoC. This paper closes this gap by contributing to the long context code generation benchmark (YABLoCo). The benchmark featured a test set of 215 functions selected from four large repositories with thousands of functions. The dataset contained metadata of functions, contexts of the functions with different levels of dependencies, docstrings, functions bodies, and call graphs for each repository. This paper presents three key aspects of the contribution. First, the benchmark aims at function body generation in large repositories in C and C++, two languages not covered by previous benchmarks. Second, the benchmark contains large repositories from 200K to 2,000K LoC. Third, we contribute a scalable evaluation pipeline for efficient computing of the target metrics and a tool for visual analysis of generated code. Overall, these three aspects allow for evaluating code generation in large repositories in C and C++.

[Arxiv](https://arxiv.org/abs/2505.04406)