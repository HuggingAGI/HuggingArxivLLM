# DHEvo：一种数据-算法驱动的启发式进化方法，面向可泛化的MILP求解

发布时间：2025年07月21日

`LLM应用` `优化算法` `进化计算`

> DHEvo: Data-Algorithm Based Heuristic Evolution for Generalizable MILP Solving

# 摘要

> 原始启发式算法对提升混合整数线性规划（MILP）求解器的效率至关重要。鉴于大型语言模型（LLMs）在代码生成方面的卓越能力，近期研究致力于将进化计算方法与LLMs相结合，以生成高效的原始启发式算法。尽管生成的启发式算法在性能上超越了适应性较弱的手工启发式算法，但现有基于LLM的方法仅限于处理同一问题类中的少量MILP实例。这是因为它们未能捕捉到同一问题类中实例的特征（从同一数学模型生成的MILP实例被视为一个问题类）。由于MILP实例在结构和特征分布上存在显著差异，进化过程中忽视这些特征导致了在同一问题类内的泛化能力不足。为解决这一难题，我们提出了一种数据-算法协同进化框架（DHEvo），通过迭代选择代表性实例并优化相应的启发式算法。基于初始的实例分布，我们开发了一个基于LLM的多智能体系统，同时生成数据-代码对。这些数据-代码对根据其适应度分数进行迭代优化，最终识别出在整个问题类中最有效的启发式算法。在多种MILP基准上的广泛实验表明，我们的方法在性能上显著优于人工设计的启发式算法和现有的基于LLM的方法。

> Primal heuristics play a critical role in improving the efficiency of mixed integer programming (MILP) solvers. As large language models (LLMs) have demonstrated superior code generation abilities, recent MILP works are devoted to leveraging the evolutionary computation approaches with LLMs to generate effective primal heuristics. Although the generated heuristics have achieved better solving performance than the hand-crafted ones with little adaptability, the advantage of current LLM-based methods is limited to few MILP instances in one problem class, as they fail to capture the instance characteristics in the problem class (the MILP instances generated from the same mathematical model are defined as a problem class). Since MILP instances often differ significantly in structure and feature distribution, the neglect of their characteristics in the evolution process results in poor generalization within the same problem class. To overcome this challenge, we propose a data-algorithm co-evolution framework (DHEvo) that iteratively selects representative instances and evolves corresponding heuristics. With the initial instance distribution, we develop an LLM-based multi-agent system to generate data-code pairs simultaneously. These data-code pairs are iteratively refined based on their fitness scores, leading to the identification of the most effective heuristic over the entire problem class. Extensive experiments across diverse MILP benchmarks demonstrate that our approach significantly outperforms both human-designed heuristics and existing LLM-based methods.

[Arxiv](https://arxiv.org/abs/2507.15615)