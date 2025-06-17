# 从经验评估迈向上下文感知增强：利用LLMs修复回归错误

发布时间：2025年06月16日

`LLM应用` `软件工程` `程序修复`

> From Empirical Evaluation to Context-Aware Enhancement: Repairing Regression Errors with LLMs

# 摘要

> 近年来，各种APR方法迅速发展，特别是那些利用大型语言模型（LLMs）的方法，为修复通用软件缺陷提供了新的解决方案。然而，这些先进方法在回归缺陷修复中的有效性仍待深入探索。为填补这一研究空白，我们开展了一项实证研究，旨在评估现代APR技术在修复真实世界回归缺陷中的实际效果。

本研究聚焦于Java回归缺陷，我们为此构建了RegMiner4APR基准，一个集成在专门设计的APR研究框架中的高质量数据集。该基准包含了从32个实际Java GitHub仓库中精心挑选的99个回归缺陷。通过对基准的深入分析，我们验证了其多样性和高质量。在此基础上，我们全面评估了传统APR工具和先进的LLM-based APR方法在回归缺陷修复中的表现。实验结果表明，传统APR工具未能成功修复任何缺陷，而LLM-based APR方法则展现了显著的潜力。为进一步提升修复效果，我们探索了将缺陷引发变更信息融入LLM-based APR方法的可行性。研究发现，这种上下文感知的优化显著提升了LLM-based APR的性能，成功修复的数量较之传统方法提高了1.8倍。

> [...] Since then, various APR approaches, especially those leveraging the power of large language models (LLMs), have been rapidly developed to fix general software bugs. Unfortunately, the effectiveness of these advanced techniques in the context of regression bugs remains largely unexplored. This gap motivates the need for an empirical study evaluating the effectiveness of modern APR techniques in fixing real-world regression bugs.
  In this work, we conduct an empirical study of APR techniques on Java regression bugs. To facilitate our study, we introduce RegMiner4APR, a high-quality benchmark of Java regression bugs integrated into a framework designed to facilitate APR research. The current benchmark includes 99 regression bugs collected from 32 widely used real-world Java GitHub repositories. We begin by conducting an in-depth analysis of the benchmark, demonstrating its diversity and quality. Building on this foundation, we empirically evaluate the capabilities of APR to regression bugs by assessing both traditional APR tools and advanced LLM-based APR approaches. Our experimental results show that classical APR tools fail to repair any bugs, while LLM-based APR approaches exhibit promising potential. Motivated by these results, we investigate impact of incorporating bug-inducing change information into LLM-based APR approaches for fixing regression bugs. Our results highlight that this context-aware enhancement significantly improves the performance of LLM-based APR, yielding 1.8x more successful repairs compared to using LLM-based APR without such context.

[Arxiv](https://arxiv.org/abs/2506.13182)