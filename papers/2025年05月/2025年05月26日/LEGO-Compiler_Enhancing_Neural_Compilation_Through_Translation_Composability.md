# 积木式编译器：借助翻译组合能力提升神经编译效能

发布时间：2025年05月26日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在编译器和代码转换工具中的应用，具体提出了一种名为LEGO-Compiler的新神经编译系统。该系统利用LLMs将高级语言转换为汇编代码，并通过分解程序模块、拆解编译过程为小步骤以及反馈机制实现自我修正。这些创新点和应用实例都属于将LLMs应用于具体任务的范畴，因此归类为LLM应用。` `编译器` `软件工程`

> LEGO-Compiler: Enhancing Neural Compilation Through Translation Composability

# 摘要

> 大型语言模型 (LLMs) 有望革新编译器与代码转换工具的设计与实现。然而，现有的 LLMs 在处理长篇复杂的程序时仍面临挑战。我们推出 LEGO-Compiler，这是一个全新的神经编译系统，借助 LLMs 将高级语言转换为汇编代码。我们的方法围绕三大核心创新：LEGO 翻译，将输入程序分解为易于处理的模块；通过将其组织为可验证的 LLM 工作流并借助外部测试，将复杂的编译过程拆解为更简单、可验证的小步骤；以及通过反馈机制实现自我修正。LEGO-Compiler 在多种数据集上表现出色，准确率超过 99%（ExeBench）和 97.9%（工业级 AnsiBench），并且在可编译代码规模的扩展性上实现了近一个数量级的提升。这项研究为将 LLMs 应用于系统级任务开辟了新途径，为传统编译技术提供了有力补充。

> Large language models (LLMs) have the potential to revolutionize how we design and implement compilers and code translation tools. However, existing LLMs struggle to handle long and complex programs. We introduce LEGO-Compiler, a novel neural compilation system that leverages LLMs to translate high-level languages into assembly code. Our approach centers on three key innovations: LEGO translation, which decomposes the input program into manageable blocks; breaking down the complex compilation process into smaller, simpler verifiable steps by organizing it as a verifiable LLM workflow by external tests; and a feedback mechanism for self-correction. Supported by formal proofs of translation composability, LEGO-Compiler demonstrates high accuracy on multiple datasets, including over 99% on ExeBench and 97.9% on industrial-grade AnsiBench. Additionally, LEGO-Compiler has also acheived near one order-of-magnitude improvement on compilable code size scalability. This work opens new avenues for applying LLMs to system-level tasks, complementing traditional compiler technologies.

[Arxiv](https://arxiv.org/abs/2505.20356)