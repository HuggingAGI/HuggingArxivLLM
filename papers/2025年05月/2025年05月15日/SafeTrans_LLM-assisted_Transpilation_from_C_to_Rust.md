# SafeTrans：从C语言到Rust语言的转译工具，借助LLM实现

发布时间：2025年05月15日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在自动将C代码转译为Rust代码方面的应用，特别是通过引入SafeTrans框架，利用LLMs进行代码转译和错误修复。它属于LLM的实际应用，展示了LLMs在编程任务中的潜力和实用性。` `编程语言`

> SafeTrans: LLM-assisted Transpilation from C to Rust

# 摘要

> Rust 作为内存安全的系统编程语言，是 C 的强劲对手，但将海量的 C 代码迁移到 Rust 是一项极具挑战性的任务。本文探讨了大型语言模型（LLMs）在自动将 C 代码转译为地道 Rust 代码方面的潜力，同时确保转译后的代码能有效缓解原始代码中的内存漏洞。为此，我们推出了 SafeTrans 框架，它利用 LLMs 实现两大功能：i) 将 C 代码转译为 Rust；ii) 迭代修复转译代码中的编译和运行时错误。我们的创新之处在于引入了一种基于少量示例的引导修复技术，针对特定错误类型提供上下文信息和代码示例，引导 LLM 找到正确解决方案。此外，我们还评估了转译过程的安全性，即原始 C 代码中的漏洞是否在转译后的 Rust 代码中得到妥善处理。我们使用六种领先的 LLM 和包含 2,653 个 C 程序的实验集（附带全面单元测试）对 SafeTrans 进行了测试。实验结果表明，我们的迭代修复策略将最佳 LLM（GPT-4o）的成功转译率从 54% 提升至 80%，并且所有在原始 C 代码中发现的漏洞在转译后的 Rust 代码中均得到了有效缓解。

> Rust is a strong contender for a memory-safe alternative to C as a "systems" programming language, but porting the vast amount of existing C code to Rust is a daunting task. In this paper, we evaluate the potential of large language models (LLMs) to automate the transpilation of C code to idiomatic Rust, while ensuring that the generated code mitigates any memory-related vulnerabilities present in the original code. To that end, we present the design and implementation of SafeTrans, a framework that uses LLMs to i) transpile C code into Rust and ii) iteratively fix any compilation and runtime errors in the resulting code. A key novelty of our approach is the introduction of a few-shot guided repair technique for translation errors, which provides contextual information and example code snippets for specific error types, guiding the LLM toward the correct solution. Another novel aspect of our work is the evaluation of the security implications of the transpilation process, i.e., whether potential vulnerabilities in the original C code have been properly addressed in the translated Rust code. We experimentally evaluated SafeTrans with six leading LLMs and a set of 2,653 C programs accompanied by comprehensive unit tests, which were used for validating the correctness of the translated code. Our results show that our iterative repair strategy improves the rate of successful translations from 54% to 80% for the best-performing LLM (GPT-4o), and that all types of identified vulnerabilities in the original C code are effectively mitigated in the translated Rust code.

[Arxiv](https://arxiv.org/abs/2505.10708)