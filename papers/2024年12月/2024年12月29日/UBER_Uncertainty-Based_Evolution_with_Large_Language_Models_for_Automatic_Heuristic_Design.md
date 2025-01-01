# UBER：借助大型语言模型基于不确定性进行进化，以实现自动启发式设计

发布时间：2024年12月29日

`LLM应用` `自动启发式设计` `NP-hard 问题`

> UBER: Uncertainty-Based Evolution with Large Language Models for Automatic Heuristic Design

# 摘要

> NP-hard 问题的解决向来依赖启发式算法，然而为复杂问题人工打造有效的启发式算法颇具挑战。尽管像 FunSearch 这类近期成果表明，大型语言模型（LLMs）能够在进化算法（EA）框架里用于启发式设计，但其潜力因在开发和探索上的欠缺而未完全施展。我们推出了 UBER（基于不确定性的改进进化），这是一种在 FunSearch 框架之上融入不确定性，从而强化 LLM + EA 方法以实现自动启发式设计的手段。UBER 带来了两项关键创新：用于自适应平衡探索与开发的不确定性包容进化过程（UIEP），以及用于维持种群多样性的原则性不确定性包容岛屿重置（UIIS）策略。通过针对具有挑战性的 NP 完全问题开展大量实验，UBER 相比 FunSearch 有了显著提升。我们的工作为 LLMs 和 EA 的协同合作指明了新方向，推动了自动启发式设计领域的进步。

> NP-hard problem-solving traditionally relies on heuristics, but manually crafting effective heuristics for complex problems remains challenging. While recent work like FunSearch has demonstrated that large language models (LLMs) can be leveraged for heuristic design in evolutionary algorithm (EA) frameworks, their potential is not fully realized due to its deficiency in exploitation and exploration. We present UBER (Uncertainty-Based Evolution for Refinement), a method that enhances LLM+EA methods for automatic heuristic design by integrating uncertainty on top of the FunSearch framework. UBER introduces two key innovations: an Uncertainty-Inclusive Evolution Process (UIEP) for adaptive exploration-exploitation balance, and a principled Uncertainty-Inclusive Island Reset (UIIS) strategy for maintaining population diversity. Through extensive experiments on challenging NP-complete problems, UBER demonstrates significant improvements over FunSearch. Our work provides a new direction for the synergy of LLMs and EA, advancing the field of automatic heuristic design.

[Arxiv](https://arxiv.org/abs/2412.20694)