# ReAgent：可逆多智能体推理的知识增强型多跳问答

发布时间：2025年03月10日

`Agent` `问答系统` `信息检索`

> ReAgent: Reversible Multi-Agent Reasoning for Knowledge-Enhanced Multi-Hop QA

# 摘要

> 大型语言模型（LLMs）的最新进展通过直接的链式思维（CoT）推理显著提升了多跳问答（QA）的表现。然而，CoT的不可逆特性导致了错误的累积，使得在多跳推理过程中纠正错误变得困难。本文介绍了ReAgent：一个增强的可逆多智能体协作框架，配备了显式的回溯机制，支持可逆的多跳推理。通过整合文本检索、信息聚合与验证，我们的系统能够在推理过程中检测并修正错误，从而实现更健壮且可解释的问答结果。该框架和实验为未来在容错问答系统方面的工作奠定了基础。在三个基准测试中的实证评估表明了ReAgent的有效性，相较于基线模型，平均提升了约6%的性能。

> Recent advances in large language models (LLMs) have significantly improved multi-hop question answering (QA) through direct Chain-of-Thought (CoT) reasoning. However, the irreversible nature of CoT leads to error accumulation, making it challenging to correct mistakes in multi-hop reasoning. This paper introduces ReAgent: a Reversible multi-Agent collaborative framework augmented with explicit backtracking mechanisms, enabling reversible multi-hop reasoning. By incorporating text-based retrieval, information aggregation and validation, our system can detect and correct errors mid-reasoning, leading to more robust and interpretable QA outcomes. The framework and experiments serve as a foundation for future work on error-tolerant QA systems. Empirical evaluations across three benchmarks indicate ReAgent's efficacy, yielding average about 6\% improvements against baseline models.

[Arxiv](https://arxiv.org/abs/2503.06951)