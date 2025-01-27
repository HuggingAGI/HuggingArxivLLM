# 利用LLMs提取问题结构，优化SAT局部搜索

发布时间：2025年01月24日

`LLM应用

理由：该论文摘要描述了利用大型语言模型（LLMs）分析基于Python的编码代码，以揭示问题转换为SAT的隐藏结构模式，并自动生成专门的局部搜索算法。这种方法直接应用了LLMs来改进SAT求解器的性能，属于LLM在实际问题中的应用，因此分类为“LLM应用”。` `计算机科学` `软件工程`

> Extracting Problem Structure with LLMs for Optimized SAT Local Search

# 摘要

> 局部搜索预处理通过提供高质量的起始点，显著提升了冲突驱动子句学习（CDCL）求解器的速度，现代SAT求解器已将其纳入预处理步骤。然而，这些工具依赖的基本策略往往忽略了问题中的结构模式。我们提出了一种新方法，利用大型语言模型（LLMs）分析基于Python的编码代码，揭示问题转换为SAT的隐藏结构模式。该方法自动生成专门的局部搜索算法，能够发现这些模式并生成强初始赋值，适用于相同编码类型的任何问题实例。测试结果显示，与基线预处理系统相比，我们的方法显著缩短了求解时间。

> Local search preprocessing makes Conflict-Driven Clause Learning (CDCL) solvers faster by providing high-quality starting points and modern SAT solvers have incorporated this technique into their preprocessing steps. However, these tools rely on basic strategies that miss the structural patterns in problems. We present a method that applies Large Language Models (LLMs) to analyze Python-based encoding code. This reveals hidden structural patterns in how problems convert into SAT. Our method automatically generates specialized local search algorithms that find these patterns and use them to create strong initial assignments. This works for any problem instance from the same encoding type. Our tests show encouraging results, achieving faster solving times compared to baseline preprocessing systems.

[Arxiv](https://arxiv.org/abs/2501.14630)