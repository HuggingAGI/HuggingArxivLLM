# PolyVer：多语言系统建模与验证的组合式方法

发布时间：2025年03月05日

`其他` `软件工程` `形式化方法`

> PolyVer: A Compositional Approach for Polyglot System Modeling and Verification

# 摘要

> 多语言软件系统由多种编程语言编写的程序组成。现有的验证工具大多针对单一语言定制，难以直接处理多语言系统。本文提出了一种创新方法——PolyVer，通过抽象、组合推理和综合技术，实现对多语言系统的直接验证。PolyVer将多语言系统建模为状态转移系统，其中更新函数使用目标语言（如C或Rust）实现。在验证过程中，PolyVer通过预/后置条件契约将状态转移系统的模型检测器与特定语言的验证器连接起来。这些契约由基于语法引导合成或大型语言模型（LLMs）的综合 oracle 自动生成，并由特定语言的验证器进行验证。模型检测器利用这些契约对多语言系统模型进行整体系统级属性验证。PolyVer通过反例引导的抽象细化（CEGAR）和反例引导的归纳综合（CEGIS）迭代优化，直到属性被验证或发现真实的系统级反例。我们通过UCLID5模型检测器分别与CBMC和Kani验证器（针对C和Rust）的连接，展示了PolyVer在验证Lingua Franca多语言语言程序中的实用价值。

> Several software systems are polyglot; that is, they comprise programs implemented in a combination of programming languages. Verifiers that directly run on mainstream programming languages are currently customized for single languages. Thus, to verify polyglot systems, one usually translates them into a common verification language or formalism on which the verifier runs. In this paper, we present an alternative approach, PolyVer, which employs abstraction, compositional reasoning, and synthesis to directly perform polyglot verification. PolyVer constructs a formal model of the original polyglot system as a transition system where the update functions associated with transitions are implemented in target languages such as C or Rust. To perform verification, PolyVer then connects a model checker for transition systems with language-specific verifiers (e.g., for C or Rust) using pre/post-condition contracts for the update functions. These contracts are automatically generated by synthesis oracles based on syntax-guided synthesis or large language models (LLMs), and checked by the language-specific verifiers. The contracts form abstractions of the update functions using which the model checker verifies the overall system-level property on the polyglot system model. PolyVer iterates between counterexample-guided abstraction-refinement (CEGAR) and counterexample-guided inductive synthesis (CEGIS) until the property is verified or a true system-level counterexample is found. We demonstrate the utility of PolyVer for verifying programs in the Lingua Franca polyglot language using the UCLID5 model checker connected with the CBMC and Kani verifiers for C and Rust respectively.

[Arxiv](https://arxiv.org/abs/2503.03207)