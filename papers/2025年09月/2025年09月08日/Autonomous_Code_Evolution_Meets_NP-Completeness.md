# 自主代码进化面临NP完全性

发布时间：2025年09月08日

`Agent` `基础理论`

> Autonomous Code Evolution Meets NP-Completeness

# 摘要

> 大型语言模型（LLMs）近来展现出卓越的编码能力，不仅能生成静态代码，还可借助智能体框架实现代码的迭代式自我进化。近期，AlphaEvolve \cite{novikov2025alphaevolve} 已证实，基于LLM的编码智能体可自主改进算法、超越人类专家，不过其能力范围仅局限于数百行代码规模的孤立代码核心。受此启发，我们提出SATLUTION——这是首个将基于LLM的代码进化扩展至完整代码库级别的框架，可覆盖数百个文件及数万行C/C++代码。该框架以布尔可满足性问题（SAT）为目标——这一问题是典型的NP完全问题，亦是理论与应用研究的基石。SATLUTION通过协调LLM智能体，在严格的正确性保障与分布式运行时反馈下，直接进化求解器代码库，同时还能自我优化自身的进化策略与规则。基于2024年SAT竞赛的代码库与基准测试，SATLUTION所进化的求解器不仅显著优于2025年SAT竞赛中人类设计的冠军方案，还在2024年的基准测试中超越了2024年和2025年的竞赛冠军。

> Large language models (LLMs) have recently shown strong coding abilities, enabling not only static code generation but also iterative code self-evolving through agentic frameworks. Recently, AlphaEvolve \cite{novikov2025alphaevolve} demonstrated that LLM-based coding agents can autonomously improve algorithms and surpass human experts, with scopes limited to isolated kernels spanning hundreds of lines of code. Inspired by AlphaEvolve, we present SATLUTION, the first framework to extend LLM-based code evolution to the full repository scale, encompassing hundreds of files and tens of thousands of lines of C/C++ code. Targeting Boolean Satisfiability (SAT), the canonical NP-complete problem and a cornerstone of both theory and applications. SATLUTION orchestrates LLM agents to directly evolve solver repositories under strict correctness guarantees and distributed runtime feedback, while simultaneously self-evolving its own evolution policies and rules. Starting from SAT Competition 2024 codebases and benchmark, SATLUTION evolved solvers that decisively outperformed the human-designed winners of the SAT Competition 2025, and also surpassed both 2024 and 2025 champions on the 2024 benchmarks.

[Arxiv](https://arxiv.org/abs/2509.07367)