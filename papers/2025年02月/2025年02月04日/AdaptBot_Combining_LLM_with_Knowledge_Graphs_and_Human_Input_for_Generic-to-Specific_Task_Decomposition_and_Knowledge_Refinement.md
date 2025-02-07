# AdaptBot：融合LLM、知识图谱与人类输入，实现任务从通用到特定的分解与知识精炼

发布时间：2025年02月04日

`Agent

理由：这篇论文主要讨论的是具身代理（embodied agent）在新场景中完成新任务的能力，以及如何通过结合大型语言模型（LLM）和知识图谱（KG）来增强代理的适应性。论文的核心是代理的行为和决策过程，而不是单纯的语言模型应用或理论。因此，它更适合归类为Agent。` `机器人` `智能家居`

> AdaptBot: Combining LLM with Knowledge Graphs and Human Input for Generic-to-Specific Task Decomposition and Knowledge Refinement

# 摘要

> # 摘要
协助人类的具身代理常需在新场景中完成新任务。例如，一个基于已知食谱在厨房准备特定菜肴的代理，可能会被要求准备新菜肴或在储藏室执行清洁任务。然而，由于时间或标记示例等资源的限制，代理可能无法针对这些新情况进行充分训练。尽管任务、代理或领域特定的限制可能阻碍代理执行动作序列，但在多领域知识上训练的大型语言模型（LLMs）能够预测这些新任务和场景的抽象动作序列。我们的框架通过结合LLM的通用预测和知识图谱（KG）中的领域特定知识，使代理能够快速适应新任务和场景。此外，机器人还会根据需要征求并使用人类输入来完善其知识。通过在模拟领域中对烹饪和清洁任务的实验评估，我们证明了LLM、KG和人类输入的协同作用相比仅使用LLM输出，带来了显著的性能提升。

> Embodied agents assisting humans are often asked to complete a new task in a new scenario. An agent preparing a particular dish in the kitchen based on a known recipe may be asked to prepare a new dish or to perform cleaning tasks in the storeroom. There may not be sufficient resources, e.g., time or labeled examples, to train the agent for these new situations. Large Language Models (LLMs) trained on considerable knowledge across many domains are able to predict a sequence of abstract actions for such new tasks and scenarios, although it may not be possible for the agent to execute this action sequence due to task-, agent-, or domain-specific constraints. Our framework addresses these challenges by leveraging the generic predictions provided by LLM and the prior domain-specific knowledge encoded in a Knowledge Graph (KG), enabling an agent to quickly adapt to new tasks and scenarios. The robot also solicits and uses human input as needed to refine its existing knowledge. Based on experimental evaluation over cooking and cleaning tasks in simulation domains, we demonstrate that the interplay between LLM, KG, and human input leads to substantial performance gains compared with just using the LLM output.

[Arxiv](https://arxiv.org/abs/2502.02067)