# 基于 Pareto 网格引导的大型语言模型实现多目标组合优化中的高效启发式设计

发布时间：2025年07月28日

`LLM应用

摘要讨论了将大型语言模型（LLMs）与进化算法相结合，用于解决多目标组合优化问题。这属于LLMs在特定任务中的实际应用，因此归类为LLM应用。`

> Pareto-Grid-Guided Large Language Models for Fast and High-Quality Heuristics Design in Multi-Objective Combinatorial Optimization

# 摘要

> 多目标组合优化问题（MOCOP）在实际应用中广泛存在，这些问题需要在相互冲突的目标之间寻求平衡。传统进化算法虽然在某些情况下表现出色，但它们通常依赖于领域知识和繁琐的参数调优，这在面对未知的MOCOP实例时显得不够灵活。近年来，大型语言模型（LLMs）与进化计算的结合为自动启发式生成开辟了新途径，利用其先进的语言理解和代码合成能力。然而，现有方法大多集中于单目标任务，往往忽视了多目标环境中运行时效率和启发式多样性等关键因素。为填补这一空白，我们提出了一种基于Pareto网格引导进化的LLMs方法（MPaGE），这是对简单进化多目标优化（SEMO）框架的创新性增强，结合了LLMs与Pareto前沿网格（PFG）技术。通过将目标空间划分为网格并保留表现优异的候选解来指导启发式生成，MPaGE在变体过程中利用LLMs优先生成具有语义差异的逻辑结构启发式，从而提升种群多样性并减少冗余。通过全面评估，MPaGE在现有LLM框架中表现出色，其性能可与传统多目标进化算法（MOEAs）相媲美，且运行速度显著提升。我们的代码可在以下链接获取：https://github.com/langkhachhoha/MPaGE。

> Multi-objective combinatorial optimization problems (MOCOP) frequently arise in practical applications that require the simultaneous optimization of conflicting objectives. Although traditional evolutionary algorithms can be effective, they typically depend on domain knowledge and repeated parameter tuning, limiting flexibility when applied to unseen MOCOP instances. Recently, integration of Large Language Models (LLMs) into evolutionary computation has opened new avenues for automatic heuristic generation, using their advanced language understanding and code synthesis capabilities. Nevertheless, most existing approaches predominantly focus on single-objective tasks, often neglecting key considerations such as runtime efficiency and heuristic diversity in multi-objective settings. To bridge this gap, we introduce Multi-heuristics for MOCOP via Pareto-Grid-guided Evolution of LLMs (MPaGE), a novel enhancement of the Simple Evolutionary Multiobjective Optimization (SEMO) framework that leverages LLMs and Pareto Front Grid (PFG) technique. By partitioning the objective space into grids and retaining top-performing candidates to guide heuristic generation, MPaGE utilizes LLMs to prioritize heuristics with semantically distinct logical structures during variation, thus promoting diversity and mitigating redundancy within the population. Through extensive evaluations, MPaGE demonstrates superior performance over existing LLM-based frameworks, and achieves competitive results to traditional Multi-objective evolutionary algorithms (MOEAs), with significantly faster runtime. Our code is available at: https://github.com/langkhachhoha/MPaGE.

[Arxiv](https://arxiv.org/abs/2507.20923)