# MAPGD：多智能体提示梯度下降——协同提示优化方法

发布时间：2025年09月14日

`Agent` `基础理论`

> MAPGD: Multi-Agent Prompt Gradient Descent for Collaborative Prompt Optimization

# 摘要

> 提示工程是充分发挥大型语言模型（LLMs）能力的关键，然而现有方法往往依赖单一优化路径，不仅限制了适应性与效率，还存在视角局限、梯度冲突及计算成本高昂等问题。为此，我们提出MAPGD（多智能体提示梯度下降）——一个融合多智能体协作与梯度优化的框架。MAPGD的核心特点包括：针对任务明确、示例选择、格式设计及风格优化的专业化智能体；用于冲突解决的语义梯度协调机制；基于bandit的候选选择策略以实现高效探索与利用；以及理论上的收敛保证。在分类、生成及推理任务上的实验表明，MAPGD在准确性和效率方面均优于单智能体与随机基线方法。消融实验进一步证实，梯度融合、智能体专业化及冲突解决机制带来显著优势，为稳健且可解释的提示优化提供了一种统一的、梯度启发式多智能体方案。

> Prompt engineering is crucial for leveraging large language models (LLMs), but existing methods often rely on a single optimization trajectory, limiting adaptability and efficiency while suffering from narrow perspectives, gradient conflicts, and high computational cost. We propose MAPGD (Multi-Agent Prompt Gradient Descent), a framework integrating multi-agent collaboration with gradient-based optimization. MAPGD features specialized agents for task clarity, example selection, format design, and stylistic refinement; semantic gradient coordination to resolve conflicts; bandit-based candidate selection for efficient exploration-exploitation; and theoretical convergence guarantees. Experiments on classification, generation, and reasoning tasks show MAPGD outperforms single-agent and random baselines in accuracy and efficiency. Ablations confirm the benefits of gradient fusion, agent specialization, and conflict resolution, providing a unified, gradient-inspired multi-agent approach to robust and interpretable prompt optimization.

[Arxiv](https://arxiv.org/abs/2509.11361)