# SwingArena: 专为长上下文GitHub问题解决打造的竞技编程平台

发布时间：2025年05月29日

`LLM应用` `软件工程`

> SwingArena: Competitive Programming Arena for Long-context GitHub Issue Solving

# 摘要

> 我们推出 SwingArena，一个与真实软件开发流程高度契合的 LLM 评估框架。与传统静态基准不同，SwingArena 模拟了软件迭代的协作流程，将 LLMs 分别作为补丁生成者和代码审查者进行配对。为支持这一创新评估方式，我们开发了检索增强的代码生成模块，能够从大型代码库中高效提取语法和语义相关的代码片段，支持 C++、Python、Rust 和 Go 等多种编程语言。这一设计使框架在遵守令牌限制的同时，能够灵活应对各类任务和开发场景。基于从 2,300 个问题中精选的 400 多个真实 GitHub 问题的实验表明，GPT-4o 在激进补丁生成方面表现突出，而 DeepSeek 和 Gemini 则更注重 CI 验证的正确性。SwingArena 为在现实、CI 驱动的软件开发环境中评估 LLMs 提供了一种可扩展且灵活的方法论。更多详情请访问我们的项目页面：swing-bench.github.io

> We present SwingArena, a competitive evaluation framework for Large Language Models (LLMs) that closely mirrors real-world software development workflows. Unlike traditional static benchmarks, SwingArena models the collaborative process of software iteration by pairing LLMs as submitters, who generate patches, and reviewers, who create test cases and verify the patches through continuous integration (CI) pipelines. To support these interactive evaluations, we introduce a retrieval-augmented code generation (RACG) module that efficiently handles long-context challenges by providing syntactically and semantically relevant code snippets from large codebases, supporting multiple programming languages (C++, Python, Rust, and Go). This enables the framework to scale across diverse tasks and contexts while respecting token limitations. Our experiments, using over 400 high-quality real-world GitHub issues selected from a pool of 2,300 issues, show that models like GPT-4o excel at aggressive patch generation, whereas DeepSeek and Gemini prioritize correctness in CI validation. SwingArena presents a scalable and extensible methodology for evaluating LLMs in realistic, CI-driven software development settings. More details are available on our project page: swing-bench.github.io

[Arxiv](https://arxiv.org/abs/2505.23932)