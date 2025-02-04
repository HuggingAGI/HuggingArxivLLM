# MINDSTORES: 具身系统中基于记忆的神经决策合成，助力任务强化

发布时间：2025年01月31日

`Agent

理由：这篇论文主要讨论的是如何通过构建和利用心智模型来增强具身代理（embodied agent）的规划能力。论文提出的MINDSTORES框架旨在通过与环境的交互来积累经验，并利用这些经验来优化任务规划。这涉及到代理的学习、记忆和推理能力，属于Agent领域的研究。虽然论文中提到了大型语言模型（LLMs）的使用，但其核心关注点是代理的行为和规划能力，而不是LLM本身的理论或应用。因此，将其分类为Agent更为合适。` `人工智能`

> MINDSTORES: Memory-Informed Neural Decision Synthesis for Task-Oriented Reinforcement in Embodied Systems

# 摘要

> 尽管大型语言模型（LLMs）作为具身代理的零-shot规划器表现出色，但其无法从经验中学习并构建持久心智模型，限制了它们在复杂开放世界（如Minecraft）中的表现。为此，我们提出了MINDSTORES，一个经验增强的规划框架，让具身代理通过与环境的自然交互构建并利用心智模型。借鉴人类构建和优化认知模型的方式，MINDSTORES通过维护一个经验数据库，扩展了现有的零-shot LLM规划能力。其核心创新在于将积累的经验表示为（状态、任务、计划、结果）元组的自然语言嵌入，供LLM规划器高效检索和推理，从而生成见解并优化新任务和状态的规划。在MineDojo环境（一个为Minecraft代理提供低级控制的模拟环境）中的大量实验表明，MINDSTORES在学习和应用知识方面远超现有的基于记忆的LLM规划器，同时保持了零-shot方法的灵活性和泛化优势。这一成果标志着具身AI系统向通过自然经验持续学习迈出了重要一步。

> While large language models (LLMs) have shown promising capabilities as zero-shot planners for embodied agents, their inability to learn from experience and build persistent mental models limits their robustness in complex open-world environments like Minecraft. We introduce MINDSTORES, an experience-augmented planning framework that enables embodied agents to build and leverage mental models through natural interaction with their environment. Drawing inspiration from how humans construct and refine cognitive mental models, our approach extends existing zero-shot LLM planning by maintaining a database of past experiences that informs future planning iterations. The key innovation is representing accumulated experiences as natural language embeddings of (state, task, plan, outcome) tuples, which can then be efficiently retrieved and reasoned over by an LLM planner to generate insights and guide plan refinement for novel states and tasks. Through extensive experiments in the MineDojo environment, a simulation environment for agents in Minecraft that provides low-level controls for Minecraft, we find that MINDSTORES learns and applies its knowledge significantly better than existing memory-based LLM planners while maintaining the flexibility and generalization benefits of zero-shot approaches, representing an important step toward more capable embodied AI systems that can learn continuously through natural experience.

[Arxiv](https://arxiv.org/abs/2501.19318)