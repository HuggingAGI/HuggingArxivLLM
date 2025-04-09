# 棱镜：基于蒙特卡洛树搜索的LLMs代码生成动态灵活评测

发布时间：2025年04月07日

`LLM理论

摘要讨论了大型语言模型的评估方法，提出了Prism框架，属于评估理论和方法的研究，因此归类为LLM理论。` `人工智能`

> Prism: Dynamic and Flexible Benchmarking of LLMs Code Generation with Monte Carlo Tree Search

# 摘要

> 大型语言模型（LLMs）的发展速度已经超越了传统的评估方法。静态基准测试无法全面捕捉LLM的能力，最终会被淘汰，而大多数动态方法要么过度依赖基于LLM的评估，要么受限于预定义的测试集。为此，我们推出了Prism——一个灵活且动态的基准测试框架，专为全面评估LLM而设计。Prism的核心由三大组件构成：(1) 基于树的状态表示方法，将评估建模为马尔可夫决策过程；(2) 适应性蒙特卡罗树搜索算法，用于发现具有挑战性的评估场景；(3) 多智能体评估管道，支持同时评估多种能力。为了确保评估的稳健性，Prism将对树探索模式的结构测量与不同难度级别的性能指标相结合，提供对错误模式、测试覆盖率和解决方案方法的详细诊断。通过对五种最先进的LLM进行广泛实验，我们深入分析了模型架构和规模如何影响代码生成性能在不同任务难度下的表现。实验结果不仅验证了Prism作为动态基准测试框架的有效性，还揭示了LLM在实际应用中的潜在局限性，为未来的研究和优化提供了宝贵的见解。

> The rapid advancement of Large Language Models (LLMs) has outpaced traditional evaluation methods. Static benchmarks fail to capture the depth and breadth of LLM capabilities and eventually become obsolete, while most dynamic approaches either rely too heavily on LLM-based evaluation or remain constrained by predefined test sets. We introduce Prism, a flexible, dynamic benchmarking framework designed for comprehensive LLM assessment. Prism builds on three key components: (1) a tree-based state representation that models evaluation as a Markov Decision Process, (2) a Monte Carlo Tree Search algorithm adapted to uncover challenging evaluation scenarios, and (3) a multi-agent evaluation pipeline that enables simultaneous assessment of diverse capabilities. To ensure robust evaluation, Prism integrates structural measurements of tree exploration patterns with performance metrics across difficulty levels, providing detailed diagnostics of error patterns, test coverage, and solution approaches. Through extensive experiments on five state-of-the-art LLMs, we analyze how model architecture and scale influence code generation performance across varying task difficulties. Our results demonstrate Prism's effectiveness as a dynamic benchmark that evolves with model advancements while offering deeper insights into their limitations.

[Arxiv](https://arxiv.org/abs/2504.05500)