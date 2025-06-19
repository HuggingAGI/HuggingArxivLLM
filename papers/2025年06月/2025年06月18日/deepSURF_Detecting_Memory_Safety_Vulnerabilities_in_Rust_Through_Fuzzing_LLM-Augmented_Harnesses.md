# deepSURF: 通过增强LLM的模糊测试工具检测Rust中的内存安全漏洞

发布时间：2025年06月18日

`LLM应用

理由：这篇论文展示了如何将大型语言模型（LLM）应用于检测Rust代码中的内存漏洞。具体来说，它结合了静态分析和LLM引导的模糊测试框架，以提高内存漏洞的检测能力。这项工作属于将LLM技术应用于实际问题（内存安全检测）的范畴，因此应归类为LLM应用。` `Rust` `内存安全`

> deepSURF: Detecting Memory Safety Vulnerabilities in Rust Through Fuzzing LLM-Augmented Harnesses

# 摘要

> Rust 虽然默认确保内存安全，但允许使用不安全代码，误用时可能引入内存漏洞。现有 Rust 内存 bug 检测工具通常检测能力有限，难以处理 Rust 特定类型，或严重依赖手动操作。
    我们推出 deepSURF，结合静态分析与大型语言模型 (LLM) 引导的模糊测试框架生成，专注于识别 Rust 库中的内存漏洞，尤其针对不安全代码。deepSURF 创新性地处理泛型，通过自定义类型替换和特征实现定制，让模糊测试器模拟用户定义行为。同时，deepSURF 利用 LLM 动态增强模糊测试框架，探索复杂 API 交互，大幅提升内存漏洞暴露概率。在 27 个真实 Rust 代码库的评估中，deepSURF 重新发现 20 个已知内存漏洞，并揭示 6 个未知漏洞，显著优于现有工具。

> Although Rust ensures memory safety by default, it also permits the use of unsafe code, which can introduce memory safety vulnerabilities if misused. Unfortunately, existing tools for detecting memory bugs in Rust typically exhibit limited detection capabilities, inadequately handle Rust-specific types, or rely heavily on manual intervention.
  To address these limitations, we present deepSURF, a tool that integrates static analysis with Large Language Model (LLM)-guided fuzzing harness generation to effectively identify memory safety vulnerabilities in Rust libraries, specifically targeting unsafe code. deepSURF introduces a novel approach for handling generics by substituting them with custom types and generating tailored implementations for the required traits, enabling the fuzzer to simulate user-defined behaviors within the fuzzed library. Additionally, deepSURF employs LLMs to augment fuzzing harnesses dynamically, facilitating exploration of complex API interactions and significantly increasing the likelihood of exposing memory safety vulnerabilities. We evaluated deepSURF on 27 real-world Rust crates, successfully rediscovering 20 known memory safety bugs and uncovering 6 previously unknown vulnerabilities, demonstrating clear improvements over state-of-the-art tools.

[Arxiv](https://arxiv.org/abs/2506.15648)