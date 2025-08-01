# DICE：基于高效知识迁移的大型语言模型智能体中的动态上下文示例选择

发布时间：2025年07月31日

`Agent` `人工智能`

> DICE: Dynamic In-Context Example Selection in LLM Agents via Efficient Knowledge Transfer

# 摘要

> 基于上下文学习 (ICL) 的大型语言模型 (LLM) 智能体在复杂推理和工具使用任务中表现出了强大的能力。然而，现有研究表明，ICL 的有效性对示例选择极为敏感，次优的示例常常导致不稳定或性能下降。尽管先前的研究探讨了示例选择，包括在某些智能体或多步设置中，现有方法通常依赖于启发式或特定任务的设计，缺乏一个通用的、理论基础的准则来判断什么构成有效的推理步骤中的示例。因此，开发一种原理性、通用的方法来选择始终有利于智能体性能的示例并非易事。本文中，我们通过 DICE（动态上下文示例选择框架）来应对这一挑战，这是一个针对智能体任务的理论基础 ICL 框架，能够在推理的每一步选择最相关的示例。我们的方法通过因果视角将示例知识分解为可转移和不可转移的组件，展示了后者如何引入影响泛化的虚假依赖关系。我们还提出了一种逐步选择标准，并给出了提升智能体性能的正式保证。重要的是，DICE 是一个通用的、框架无关的解决方案，可以作为插件模块集成到现有智能体框架中，无需额外的训练成本。跨多个领域的广泛实验展示了我们方法的有效性和通用性，突显了基于原理、感知上下文的示例选择对于构建稳健和高效 LLM 智能体的重要性。

> Large language model-based agents, empowered by in-context learning (ICL), have demonstrated strong capabilities in complex reasoning and tool-use tasks. However, existing works have shown that the effectiveness of ICL is highly sensitive to the choice of demonstrations, with suboptimal examples often leading to unstable or degraded performance. While prior work has explored example selection, including in some agentic or multi-step settings, existing approaches typically rely on heuristics or task-specific designs and lack a general, theoretically grounded criterion for what constitutes an effective demonstration across reasoning steps. Therefore, it is non-trivial to develop a principled, general-purpose method for selecting demonstrations that consistently benefit agent performance. In this paper, we address this challenge with DICE, Dynamic In-Context Example Selection for LLM Agents, a theoretically grounded ICL framework for agentic tasks that selects the most relevant demonstrations at each step of reasoning. Our approach decomposes demonstration knowledge into transferable and non-transferable components through a causal lens, showing how the latter can introduce spurious dependencies that impair generalization. We further propose a stepwise selection criterion with a formal guarantee of improved agent performance. Importantly, DICE is a general, framework-agnostic solution that can be integrated as a plug-in module into existing agentic frameworks without any additional training cost. Extensive experiments across diverse domains demonstrate our method's effectiveness and generality, highlighting the importance of principled, context-aware demo selection for robust and efficient LLM agents.

[Arxiv](https://arxiv.org/abs/2507.23554)