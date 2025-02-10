# 研究方向：扩展 LLM 代理需要借助 LLM 原语进行渐近分析

发布时间：2025年02月04日

`Agent

摘要讨论了将复杂问题分解为多个子问题，并使用基于LLM的智能体来解决这些子问题。这涉及到智能体的组织和任务分配，属于智能体系统的研究范畴。论文提出了一种使用LLM原语进行渐近分析的方法，以优化智能体的分解和编排，从而提高解决复杂问题的效率。这种方法论更偏向于智能体系统的设计和分析，因此归类为Agent。` `人工智能` `系统优化`

> Position: Scaling LLM Agents Requires Asymptotic Analysis with LLM Primitives

# 摘要

> 将复杂问题分解为多个子问题，往往能让问题变得更容易解决，同时提高效率。随着大型语言模型（LLMs）在越来越多的能力上达到关键可靠性门槛，越来越多的努力致力于将系统分解为基于LLM的智能体集合，每个智能体都可以被分配子任务。然而，这种分解（即使在自动化的情况下）往往是直觉性的，例如基于人类如何为人类团队成员分配角色。这些角色分解与最优解有多接近？本文认为，为了推理此类分解系统的效率，需要使用LLM原语进行渐近分析，而这种分析的见解将解锁扩展它们的机会。通过将LLM的前向传递视为计算成本的原子单位，可以将特定LLM的内部工作（通常不透明）与其如何编排一组LLM来解决复杂问题的内在效率区分开来。换句话说，如果我们希望将LLM的部署扩展到极限，与其拟人化LLM，不如使用LLM原语进行渐近分析来推理和开发将大问题分解为LLM智能体的更强大的方法。

> Decomposing hard problems into subproblems often makes them easier and more efficient to solve. With large language models (LLMs) crossing critical reliability thresholds for a growing slate of capabilities, there is an increasing effort to decompose systems into sets of LLM-based agents, each of whom can be delegated sub-tasks. However, this decomposition (even when automated) is often intuitive, e.g., based on how a human might assign roles to members of a human team. How close are these role decompositions to optimal? This position paper argues that asymptotic analysis with LLM primitives is needed to reason about the efficiency of such decomposed systems, and that insights from such analysis will unlock opportunities for scaling them. By treating the LLM forward pass as the atomic unit of computational cost, one can separate out the (often opaque) inner workings of a particular LLM from the inherent efficiency of how a set of LLMs are orchestrated to solve hard problems. In other words, if we want to scale the deployment of LLMs to the limit, instead of anthropomorphizing LLMs, asymptotic analysis with LLM primitives should be used to reason about and develop more powerful decompositions of large problems into LLM agents.

[Arxiv](https://arxiv.org/abs/2502.04358)