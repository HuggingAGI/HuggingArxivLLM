# GET: 探索与定位：大规模未知环境中的目标导向方法

发布时间：2025年05月27日

`LLM应用` `机器人领域` `机器人导航`

> GET: Goal-directed Exploration and Targeting for Large-Scale Unknown Environments

# 摘要

> 在大规模、非结构化的环境中进行物体搜索仍然是机器人领域的重要挑战，特别是在动态或广阔场景中，例如户外自主探索。这一任务需要强大的空间推理能力和利用先前经验的能力。虽然大型语言模型（LLMs）提供了强大的语义能力，但它们在具身环境中的应用受到空间推理中接地差距的限制，以及记忆整合和决策一致性机制的不足。为了应对这些挑战，我们提出了GET（目标导向的探索与定位），一个通过结合基于LLM的推理和经验引导的探索来增强物体搜索的框架。其核心是DoUT（统一思维图），一个推理模块，通过基于角色的反馈循环促进实时决策，整合任务特定标准和外部记忆。对于重复任务，GET基于高斯混合模型维护一个概率任务图，允许随着环境的变化不断更新物体位置的先验。在真实世界的大规模环境中进行的实验表明，GET在多个LLM和任务设置中提高了搜索效率和鲁棒性，显著超越了启发式和仅LLM的基线方法。这些结果表明，结构化的LLM集成提供了一种在复杂环境中可扩展且通用的具身决策方法。

> Object search in large-scale, unstructured environments remains a fundamental challenge in robotics, particularly in dynamic or expansive settings such as outdoor autonomous exploration. This task requires robust spatial reasoning and the ability to leverage prior experiences. While Large Language Models (LLMs) offer strong semantic capabilities, their application in embodied contexts is limited by a grounding gap in spatial reasoning and insufficient mechanisms for memory integration and decision consistency.To address these challenges, we propose GET (Goal-directed Exploration and Targeting), a framework that enhances object search by combining LLM-based reasoning with experience-guided exploration. At its core is DoUT (Diagram of Unified Thought), a reasoning module that facilitates real-time decision-making through a role-based feedback loop, integrating task-specific criteria and external memory. For repeated tasks, GET maintains a probabilistic task map based on a Gaussian Mixture Model, allowing for continual updates to object-location priors as environments evolve.Experiments conducted in real-world, large-scale environments demonstrate that GET improves search efficiency and robustness across multiple LLMs and task settings, significantly outperforming heuristic and LLM-only baselines. These results suggest that structured LLM integration provides a scalable and generalizable approach to embodied decision-making in complex environments.

[Arxiv](https://arxiv.org/abs/2505.20828)