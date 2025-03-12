# 提出了一种集成大型语言模型的级联协作多智能体框架，用于匝道合并控制

发布时间：2025年03月11日

`Agent

理由：这篇论文主要探讨了强化学习（RL）在多智能体场景中的应用，特别是如何通过结合大型语言模型（LLM）和其他机制来提升多智能体的协作和决策能力。论文的核心在于多智能体系统的优化和协调，因此归类到Agent类别。` `自动驾驶`

> A Cascading Cooperative Multi-agent Framework for On-ramp Merging Control Integrating Large Language Models

# 摘要

> 传统强化学习（RL）在模拟人类行为、实现多智能体场景的高效泛化以及解决固有可解释性难题方面面临挑战。当涉及深度环境理解、智能体间协调及动态优化时，这些挑战变得更加复杂。尽管大型语言模型（LLM）增强方法在泛化与互操作性方面展现出潜力，但它们往往忽视了多智能体协调的重要性。因此，我们提出了级联合作多智能体（CCMA）框架，将用于个体互动的强化学习、用于区域协作的微调LLM、用于全局优化的奖励函数以及检索增强生成机制相结合，实现在复杂驾驶场景中的动态决策优化。实验结果表明，CCMA在复杂驾驶环境中显著超越现有强化学习方法，无论是在微观还是宏观层面，均展现出卓越的性能提升。

> Traditional Reinforcement Learning (RL) suffers from replicating human-like behaviors, generalizing effectively in multi-agent scenarios, and overcoming inherent interpretability issues.These tasks are compounded when deep environment understanding, agent coordination and dynamic optimization are required. While Large Language Model (LLM) enhanced methods have shown promise in generalization and interoperability, they often neglect necessary multi-agent coordination. Therefore, we introduce the Cascading Cooperative Multi-agent (CCMA) framework, integrating RL for individual interactions, a fine-tuned LLM for regional cooperation, a reward function for global optimization, and the Retrieval-augmented Generation mechanism to dynamically optimize decision-making across complex driving scenarios. Our experiments demonstrate that the CCMA outperforms existing RL methods, demonstrating significant improvements in both micro and macro-level performance in complex driving environments.

[Arxiv](https://arxiv.org/abs/2503.08199)