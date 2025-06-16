# STRCMP：图结构先验与语言模型的融合，应用于组合优化

发布时间：2025年05月22日

`LLM应用` `运筹学` `软件工程`

> STRCMP: Integrating Graph Structural Priors with Language Models for Combinatorial Optimization

# 摘要

> 组合优化（CO）问题作为运筹学和理论计算机科学的核心，因其NP难特性而带来显著的计算挑战。大型语言模型（LLMs）已崭露头角，成为解决CO问题的有力工具，既能直接生成解决方案，也能合成特定求解器的代码。然而，现有方法往往忽视了CO问题中固有的关键结构先验，导致解的次优和迭代低效。受人类专家成功利用CO结构进行算法设计的启发，我们提出了STRCMP，一种新颖的基于LLM的结构感知算法发现框架，系统地整合了结构先验以提升解的质量和求解效率。我们的框架结合了用于从CO实例中提取结构嵌入的图神经网络（GNN），以及基于这些嵌入条件的LLM，以识别高性能算法，形式为特定求解器的代码。这种复合架构确保了语法正确性，保留了问题拓扑结构，并与自然语言目标保持一致，同时进化优化过程会迭代优化生成的算法。通过使用九个基准数据集对混合整数线性规划和布尔可满足性问题进行广泛评估，结果表明，与五种强大的神经和基于LLM的方法相比，我们的STRCMP在解的最优性和计算效率方面都显著优越。代码和学习模型将在论文被接受后公开发布。

> Combinatorial optimization (CO) problems, central to operation research and theoretical computer science, present significant computational challenges due to their NP-hard nature. While large language models (LLMs) have emerged as promising tools for CO--either by directly generating solutions or synthesizing solver-specific codes--existing approaches often neglect critical structural priors inherent to CO problems, leading to suboptimality and iterative inefficiency. Inspired by human experts' success in leveraging CO structures for algorithm design, we propose STRCMP, a novel structure-aware LLM-based algorithm discovery framework that systematically integrates structure priors to enhance solution quality and solving efficiency. Our framework combines a graph neural network (GNN) for extracting structural embeddings from CO instances with an LLM conditioned on these embeddings to identify high-performing algorithms in the form of solver-specific codes. This composite architecture ensures syntactic correctness, preserves problem topology, and aligns with natural language objectives, while an evolutionary refinement process iteratively optimizes generated algorithm. Extensive evaluations across Mixed Integer Linear Programming and Boolean Satisfiability problems, using nine benchmark datasets, demonstrate that our proposed STRCMP outperforms five strong neural and LLM-based methods by a large margin, in terms of both solution optimality and computational efficiency. The code and learned model will be publicly available upon the acceptance of the paper.

[Arxiv](https://arxiv.org/abs/2506.11057)