# SE-Agent：基于LLM的智能体在多步推理中的自我进化轨迹优化

发布时间：2025年08月04日

`Agent` `软件工程` `人工智能`

> SE-Agent: Self-Evolution Trajectory Optimization in Multi-Step Reasoning with LLM-Based Agents

# 摘要

> 基于大型语言模型（LLM）的智能体在通过多步与环境交互中展现出了令人瞩目的复杂推理和工具使用能力。尽管这些智能体能够处理复杂任务，但它们的问题解决过程，即导致任务完成的智能体交互轨迹，仍未得到充分挖掘。这些轨迹包含了丰富的反馈信息，能够引导智能体走向正确解决问题的方向。

现有的方法，如蒙特卡洛树搜索（MCTS），虽然能够有效地平衡探索与开发，但它们忽略了各种轨迹之间的相互依赖关系，并且缺乏搜索空间的多样性，这导致了冗余推理和次优结果。为了解决这些挑战，我们提出了SE-Agent，一个允许智能体通过迭代优化其推理过程的自进化框架。

我们的方法通过三种关键操作重新审视并改进先前的试点轨迹：修订、重组和细化。这种进化机制带来了两大关键优势：（1）它通过智能地探索由先前轨迹引导的多样化解决方案路径，超越局部最优，扩展搜索空间；（2）它利用跨轨迹的灵感，高效提升性能，同时减轻次优推理路径的影响。

通过这些机制，SE-Agent实现了持续的自我进化，逐步提升推理质量。我们在SWE-bench Verified上评估SE-Agent，用于解决真实的GitHub问题。在五种强大LLM上的实验结果表明，集成SE-Agent带来了高达55%的相对提升，实现了所有开源智能体在SWE-bench Verified上的最先进性能。我们的代码和演示材料公开可用，链接为https://github.com/wanghuacan/SE-Agent。

> Large Language Model (LLM)-based agents have recently shown impressive capabilities in complex reasoning and tool use via multi-step interactions with their environments. While these agents have the potential to tackle complicated tasks, their problem-solving process, i.e., agents' interaction trajectory leading to task completion, remains underexploited. These trajectories contain rich feedback that can navigate agents toward the right directions for solving problems correctly. Although prevailing approaches, such as Monte Carlo Tree Search (MCTS), can effectively balance exploration and exploitation, they ignore the interdependence among various trajectories and lack the diversity of search spaces, which leads to redundant reasoning and suboptimal outcomes. To address these challenges, we propose SE-Agent, a Self-Evolution framework that enables Agents to optimize their reasoning processes iteratively. Our approach revisits and enhances former pilot trajectories through three key operations: revision, recombination, and refinement. This evolutionary mechanism enables two critical advantages: (1) it expands the search space beyond local optima by intelligently exploring diverse solution paths guided by previous trajectories, and (2) it leverages cross-trajectory inspiration to efficiently enhance performance while mitigating the impact of suboptimal reasoning paths. Through these mechanisms, SE-Agent achieves continuous self-evolution that incrementally improves reasoning quality. We evaluate SE-Agent on SWE-bench Verified to resolve real-world GitHub issues. Experimental results across five strong LLMs show that integrating SE-Agent delivers up to 55% relative improvement, achieving state-of-the-art performance among all open-source agents on SWE-bench Verified. Our code and demonstration materials are publicly available at https://github.com/wanghuacan/SE-Agent.

[Arxiv](https://arxiv.org/abs/2508.02085)