# 大型语言模型在冷启动切割平面分离器配置中的应用

发布时间：2024年12月16日

`LLM应用

理由：该论文提出了一种基于大型语言模型（LLM）的新框架，用于配置混合整数线性规划（MILP）求解器的参数。这种方法利用LLM的能力来处理实例特征（如问题描述和LaTeX公式），并通过总结研究文献来增强LLM的性能。论文的重点在于如何应用LLM来解决实际问题（即MILP求解器的参数配置），而不是探讨LLM的理论基础或构建新的LLM模型。因此，它属于LLM应用的范畴。` `机器学习`

> LLMs for Cold-Start Cutting Plane Separator Configuration

# 摘要

> # 摘要
混合整数线性规划（MILP）求解器附带大量参数，这些参数对性能影响巨大，但对非专家用户来说难以预先选择。现有机器学习（ML）方法配置求解器需要大量训练数据，泛化能力差，且集成复杂。本文提出了一种基于LLM的新框架，通过实例特征（如问题描述和LaTeX公式）配置切割平面分离器，几乎无需训练数据。我们通过总结研究文献增强LLM，并提出一种集成策略，通过聚类和聚合配置创建高性能配置组合。该方法无需自定义接口，仅需少量MILP求解即可找到高性能配置，且通过简单API调用即可快速生成配置。实验表明，该方法在经典组合优化问题和真实数据集上，仅用少量数据和计算时间，便能与现有方法竞争。

> Mixed integer linear programming (MILP) solvers ship with a staggering number of parameters that are challenging to select a priori for all but expert optimization users, but can have an outsized impact on the performance of the MILP solver. Existing machine learning (ML) approaches to configure solvers require training ML models by solving thousands of related MILP instances, generalize poorly to new problem sizes, and often require implementing complex ML pipelines and custom solver interfaces that can be difficult to integrate into existing optimization workflows. In this paper, we introduce a new LLM-based framework to configure which cutting plane separators to use for a given MILP problem with little to no training data based on characteristics of the instance, such as a natural language description of the problem and the associated LaTeX formulation. We augment these LLMs with descriptions of cutting plane separators available in a given solver, grounded by summarizing the existing research literature on separators. While individual solver configurations have a large variance in performance, we present a novel ensembling strategy that clusters and aggregates configurations to create a small portfolio of high-performing configurations. Our LLM-based methodology requires no custom solver interface, can find a high-performing configuration by solving only a small number of MILPs, and can generate the configuration with simple API calls that run in under a second. Numerical results show our approach is competitive with existing configuration approaches on a suite of classic combinatorial optimization problems and real-world datasets with only a fraction of the training data and computation time.

[Arxiv](https://arxiv.org/abs/2412.12038)