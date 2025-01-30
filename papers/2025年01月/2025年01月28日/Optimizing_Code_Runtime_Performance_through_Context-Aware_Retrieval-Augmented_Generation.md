# 基于上下文感知的检索增强生成优化代码运行性能

发布时间：2025年01月28日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）来自动生成优化代码，以提高软件的执行速度和效率。AUTOPATCH方法通过上下文学习和自动化管道，展示了LLMs在程序优化中的应用潜力。因此，这篇论文属于LLM应用的范畴。` `软件工程` `自动化`

> Optimizing Code Runtime Performance through Context-Aware Retrieval-Augmented Generation

# 摘要

> 通过自动化代码优化提升软件性能，为提高执行速度和效率开辟了新途径。尽管LLMs近期取得了显著进展，但其在深入程序分析方面的能力仍有不足。本研究提出了AUTOPATCH，一种基于上下文学习的方法，旨在通过LLMs自动生成优化代码来填补这一空白。AUTOPATCH借鉴了程序员优化软件的学习方式，包含三大核心：(1) 类比驱动框架，将LLM优化与人类认知过程对齐；(2) 统一方法，整合历史代码示例和CFG分析，实现上下文感知学习；(3) 自动化管道，通过上下文提示生成优化代码。实验显示，AUTOPATCH在常见生成代码上的执行效率比GPT-4o提升了7.3%，展现了其在自动化程序运行时优化中的巨大潜力。

> Optimizing software performance through automated code refinement offers a promising avenue for enhancing execution speed and efficiency. Despite recent advancements in LLMs, a significant gap remains in their ability to perform in-depth program analysis. This study introduces AUTOPATCH, an in-context learning approach designed to bridge this gap by enabling LLMs to automatically generate optimized code. Inspired by how programmers learn and apply knowledge to optimize software, AUTOPATCH incorporates three key components: (1) an analogy-driven framework to align LLM optimization with human cognitive processes, (2) a unified approach that integrates historical code examples and CFG analysis for context-aware learning, and (3) an automated pipeline for generating optimized code through in-context prompting. Experimental results demonstrate that AUTOPATCH achieves a 7.3% improvement in execution efficiency over GPT-4o across common generated executable code, highlighting its potential to advance automated program runtime optimization.

[Arxiv](https://arxiv.org/abs/2501.16692)