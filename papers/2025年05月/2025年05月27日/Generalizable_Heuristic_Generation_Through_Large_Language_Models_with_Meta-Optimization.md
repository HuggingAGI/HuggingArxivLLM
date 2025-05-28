# 元优化驱动的大型语言模型实现通用启发式生成

发布时间：2025年05月27日

`LLM应用` `运筹学` `计算机科学`

> Generalizable Heuristic Generation Through Large Language Models with Meta-Optimization

# 摘要

> 基于大语言模型的启发式设计在解决组合优化问题方面展现出巨大潜力。然而，现有方法通常受限于手动预定义的进化计算优化器和单一任务训练方案，这不仅限制了多样化启发式算法的探索，还影响了最终启发式方法的泛化能力。为了解决这些问题，我们提出了一种名为元优化启发式（MoH）的新颖框架。MoH在优化器级别运行，通过元学习的原则发现有效的优化器。具体来说，MoH利用大语言模型迭代地精炼一个元优化器，该元优化器通过（自我）调用来自主构造多样化的优化器，从而摆脱了对预定义进化计算优化器的依赖。这些构造的优化器随后演化解的下游任务，从而实现更广泛的启发式探索。此外，MoH采用了多任务训练方案以促进其泛化能力。在经典组合优化问题上的实验表明，MoH构建了一个有效且可解释的元优化器，在各种下游任务中，特别是在跨规模设置中，实现了最先进的性能。

> Heuristic design with large language models (LLMs) has emerged as a promising approach for tackling combinatorial optimization problems (COPs). However, existing approaches often rely on manually predefined evolutionary computation (EC) optimizers and single-task training schemes, which may constrain the exploration of diverse heuristic algorithms and hinder the generalization of the resulting heuristics. To address these issues, we propose Meta-Optimization of Heuristics (MoH), a novel framework that operates at the optimizer level, discovering effective optimizers through the principle of meta-learning. Specifically, MoH leverages LLMs to iteratively refine a meta-optimizer that autonomously constructs diverse optimizers through (self-)invocation, thereby eliminating the reliance on a predefined EC optimizer. These constructed optimizers subsequently evolve heuristics for downstream tasks, enabling broader heuristic exploration. Moreover, MoH employs a multi-task training scheme to promote its generalization capability. Experiments on classic COPs demonstrate that MoH constructs an effective and interpretable meta-optimizer, achieving state-of-the-art performance across various downstream tasks, particularly in cross-size settings.

[Arxiv](https://arxiv.org/abs/2505.20881)