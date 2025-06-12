# 大型语言模型在设计结构矩阵优化中的应用

发布时间：2025年06月11日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在解决复杂工程系统中的组合优化问题中的应用。具体来说，研究者提出了一种基于LLMs的框架，结合网络拓扑和领域知识，用于优化设计结构矩阵（DSM）中的元素排序。这项研究的重点在于展示LLMs在实际工程问题中的潜力，并提出了一种新的应用方法。因此，它属于LLM应用类别。` `工程设计` `组合优化`

> Large Language Models for Design Structure Matrix Optimization

# 摘要

> 在复杂工程系统中，组件或开发活动的相互依赖关系通常通过设计结构矩阵（DSM）进行建模和分析。重新排列 DSM 中的元素以减少反馈循环并提升模块化或流程效率，是一个具有挑战性的组合优化（CO）问题，在工程设计和运营中尤为突出。随着问题规模的扩大和依赖网络的复杂化，传统优化方法往往难以捕捉到情境中的细微差别，因而难以提供有效的解决方案。本研究探索了大型语言模型（LLMs）在借助其高级推理和情境理解能力来辅助解决此类 CO 问题的潜力。我们提出了一种新颖的 LLM 基础框架，将网络拓扑与情境领域知识相结合，用于 DSM 元素排序的迭代优化——这是一个常见的 CO 问题。在多种 DSM 案例的实验中，我们的方法在收敛速度和解决方案质量上均优于随机和确定性基线。值得注意的是，无论选择哪种 LLM 架构，融入领域知识都能显著提升优化效果。这些发现凸显了 LLMs 在结合语义和数学推理解决复杂工程 CO 问题方面的潜力。这一方法为基于 LLM 的工程设计优化开辟了新的范式。

> In complex engineering systems, the interdependencies among components or development activities are often modeled and analyzed using Design Structure Matrix (DSM). Reorganizing elements within a DSM to minimize feedback loops and enhance modularity or process efficiency constitutes a challenging combinatorial optimization (CO) problem in engineering design and operations. As problem sizes increase and dependency networks become more intricate, traditional optimization methods that solely use mathematical heuristics often fail to capture the contextual nuances and struggle to deliver effective solutions. In this study, we explore the potential of Large Language Models (LLMs) for helping solve such CO problems by leveraging their capabilities for advanced reasoning and contextual understanding. We propose a novel LLM-based framework that integrates network topology with contextual domain knowledge for iterative optimization of DSM element sequencing - a common CO problem. Experiments on various DSM cases show that our method consistently achieves faster convergence and superior solution quality compared to both stochastic and deterministic baselines. Notably, we find that incorporating contextual domain knowledge significantly enhances optimization performance regardless of the chosen LLM backbone. These findings highlight the potential of LLMs to solve complex engineering CO problems by combining semantic and mathematical reasoning. This approach paves the way towards a new paradigm in LLM-based engineering design optimization.

[Arxiv](https://arxiv.org/abs/2506.09749)