# Pel：专为 AI 代理编排设计的编程语言

发布时间：2025年04月03日

`Agent` `计算机科学` `人工智能`

> Pel, A Programming Language for Orchestrating AI Agents

# 摘要

> 大型语言模型（LLMs）的蓬勃发展为计算领域开辟了新的前沿，但如何有效控制和编排其能力以实现超越简单文本生成的目标仍然是一个挑战。当前的方法，如函数调用与工具调用、直接代码生成等，在表达性、可扩展性、成本、安全性以及实现细粒度控制方面均存在局限性。

本文提出了一种全新的编程语言Pel，旨在填补这一空白。Pel汲取了Lisp、Elixir、Gleam和Haskell等语言的精髓，提供了一个语法简洁、符号自洽且语义丰富的平台，使LLMs能够安全高效地表达复杂动作、控制流以及跨智能体通信。

Pel的设计以一种最小化且易于修改的语法规则为核心，专为受限的LLM生成场景量身定制，通过在语法层面实现能力控制，从而避免了复杂沙盒机制的需要。Pel的主要特性包括：强大的管道机制支持线性组合、一等闭包支持部分应用和函数式编程模式、内置对LLM评估的自然语言条件的支持，以及带有Common Lisp风格重启和LLM驱动辅助代理的先进Read-Eval-Print-Loop（REPeL），可实现自动化错误修复。此外，Pel还通过静态依赖分析实现了独立操作的自动并行化，这对于高性能智能体系统至关重要。

我们主张，Pel为LLM编排提供了一种更强大、安全和表达力丰富的范式，为构建更复杂可靠的AI智能体框架奠定了基础。

> The proliferation of Large Language Models (LLMs) has opened new frontiers in computing, yet controlling and orchestrating their capabilities beyond simple text generation remains a challenge. Current methods, such as function/tool calling and direct code generation, suffer from limitations in expressiveness, scalability, cost, security, and the ability to enforce fine-grained control. This paper introduces Pel, a novel programming language specifically designed to bridge this gap. Inspired by the strengths of Lisp, Elixir, Gleam, and Haskell, Pel provides a syntactically simple, homoiconic, and semantically rich platform for LLMs to express complex actions, control flow, and inter-agent communication safely and efficiently. Pel's design emphasizes a minimal, easily modifiable grammar suitable for constrained LLM generation, eliminating the need for complex sandboxing by enabling capability control at the syntax level. Key features include a powerful piping mechanism for linear composition, first-class closures enabling easy partial application and functional patterns, built-in support for natural language conditions evaluated by LLMs, and an advanced Read-Eval-Print-Loop (REPeL) with Common Lisp-style restarts and LLM-powered helper agents for automated error correction. Furthermore, Pel incorporates automatic parallelization of independent operations via static dependency analysis, crucial for performant agentic systems. We argue that Pel offers a more robust, secure, and expressive paradigm for LLM orchestration, paving the way for more sophisticated and reliable AI agentic frameworks.

[Arxiv](https://arxiv.org/abs/2505.13453)