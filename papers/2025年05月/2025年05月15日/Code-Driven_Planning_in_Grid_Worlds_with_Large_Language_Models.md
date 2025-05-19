# # 基于大型语言模型的代码驱动规划在网格世界中的应用

发布时间：2025年05月15日

`LLM应用` `智能体策略` `代码生成`

> Code-Driven Planning in Grid Worlds with Large Language Models

# 摘要

> 我们提出了一种迭代程序化规划（IPP）框架，用于通过大型语言模型（LLMs）用代码合成可解释的智能体策略来解决基于网格的任务。与传统的搜索方法或强化学习不同，我们的方法利用代码生成作为策略合成的手段，其中 LLM 输出将环境状态映射到动作序列的可执行程序。我们的架构整合了多种提示策略，包括直接代码生成、基于伪代码的细化以及基于课程的提示，同时包含一个迭代细化机制，该机制根据任务性能反馈更新代码。我们使用六种领先的 LLM 和两个具有挑战性的基于网格的基准测试（GRASP 和 MiniGrid）来评估我们的方法。在五个模型上，我们的 IPP 框架在性能上较直接代码生成提升了 10% 到 10 倍，并为 GRASP 建立了新的最先进结果。 IPP 在从 GPT-o3-mini 中直接提取解决方案方面表现显著优于（在 MiniGrid 上提升 63%，在 GRASP 上提升 116%），证明了整体方法的可行性。所有代码生成方法的计算成本相似。虽然代码生成的初始提示成本高于直接解决方案提取（每任务 0.08 美元，而 GPT-o3-mini 每实例 0.002 美元），但代码可以重复用于任意数量的实例，从而大幅降低分摊成本（在完整的 GRASP 基准测试中，GPT-o3-mini 的成本降低了 400 倍）。

> We propose an iterative programmatic planning (IPP) framework for solving grid-based tasks by synthesizing interpretable agent policies expressed in code using large language models (LLMs). Instead of relying on traditional search or reinforcement learning, our approach uses code generation as policy synthesis, where the LLM outputs executable programs that map environment states to action sequences. Our proposed architecture incorporates several prompting strategies, including direct code generation, pseudocode-conditioned refinement, and curriculum-based prompting, but also includes an iterative refinement mechanism that updates code based on task performance feedback. We evaluate our approach using six leading LLMs and two challenging grid-based benchmarks (GRASP and MiniGrid). Our IPP framework demonstrates improvements over direct code generation ranging from 10\% to as much as 10x across five of the six models and establishes a new state-of-the-art result for GRASP. IPP is found to significantly outperform direct elicitation of a solution from GPT-o3-mini (by 63\% on MiniGrid to 116\% on GRASP), demonstrating the viability of the overall approach. Computational costs of all code generation approaches are similar. While code generation has a higher initial prompting cost compared to direct solution elicitation (\$0.08 per task vs. \$0.002 per instance for GPT-o3-mini), the code can be reused for any number of instances, making the amortized cost significantly lower (by 400x on GPT-o3-mini across the complete GRASP benchmark).

[Arxiv](https://arxiv.org/abs/2505.10749)