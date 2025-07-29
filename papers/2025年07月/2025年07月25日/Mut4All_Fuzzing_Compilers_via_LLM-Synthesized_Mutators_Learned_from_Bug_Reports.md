# Mut4All：通过 LLM 生成的变异器进行编译器模糊测试，这些变异器是基于错误报告训练而成。

发布时间：2025年07月25日

`LLM应用` `编译器漏洞检测` `软件工程`

> Mut4All: Fuzzing Compilers via LLM-Synthesized Mutators Learned from Bug Reports

# 摘要

> 变异式模糊测试在发现编译器漏洞方面表现出色，但对于包含复杂结构（如模板、宏）的现代语言来说，设计高质量的变异器仍是一项难题。现有方法主要依赖手动设计或人机交互式修正，这限制了其扩展性和跨语言通用性。

我们推出Mut4All——一个完全自动化、语言无关的框架，它利用大型语言模型（LLMs）和编译器特定知识（从错误报告中提取）来合成变异器。该框架由三个核心代理组成：（1）变异器发明代理，通过编译器相关见解识别变异目标并生成元数据；（2）变异器实现综合代理，专门优化以生成初始实现方案；（3）变异器优化代理，通过单元测试反馈验证并修正变异器。

Mut4All分析了1000个错误报告（500个Rust，500个C++），借助GPT-4o生成了319个Rust变异器和403个C++变异器，每个成本仅约$0.08。我们的定制模糊测试工具利用这些变异器，在Rust编译器中发现了62个漏洞（38个全新发现，7个已修复），在C++编译器中发现了34个漏洞（16个全新发现，1个已修复）。与现有方法相比，Mut4All在唯一崩溃检测和覆盖率方面均表现优异，在Rust领域排名第一，在C++领域紧随其后。


> Mutation-based fuzzing is effective for uncovering compiler bugs, but designing high-quality mutators for modern languages with complex constructs (e.g., templates, macros) remains challenging. Existing methods rely heavily on manual design or human-in-the-loop correction, limiting scalability and cross-language generalizability.
  We present Mut4All, a fully automated, language-agnostic framework that synthesizes mutators using Large Language Models (LLMs) and compiler-specific knowledge from bug reports. It consists of three agents: (1) a mutator invention agent that identifies mutation targets and generates mutator metadata using compiler-related insights; (2) a mutator implementation synthesis agent, fine-tuned to produce initial implementations; and (3) a mutator refinement agent that verifies and corrects the mutators via unit-test feedback.
  Mut4All processes 1000 bug reports (500 Rust, 500 C++), yielding 319 Rust and 403 C++ mutators at ~$0.08 each via GPT-4o. Our customized fuzzer, using these mutators, finds 62 bugs in Rust compilers (38 new, 7 fixed) and 34 bugs in C++ compilers (16 new, 1 fixed). Mut4All outperforms existing methods in both unique crash detection and coverage, ranking first on Rust and second on C++.

[Arxiv](https://arxiv.org/abs/2507.19275)