# 通过演示与语言学习组合行为

发布时间：2025年05月28日

`Agent` `机器人技术` `自动化`

> Learning Compositional Behaviors from Demonstration and Language

# 摘要

> 我们提出了行为从语言和演示（BLADE），这是一个结合模仿学习与模型基础规划的长时地平机器人操纵框架。BLADE通过语言标注的演示，从大型语言模型（LLMs）中提取抽象动作知识，并构建结构化的高级动作表示库。这些表示包含基于视觉感知的前提条件和效果，以及由神经网络策略实现的控制器。BLADE无需手动标注即可自动恢复这些结构化表示。在新情况下的泛化能力方面，BLADE表现出色，包括处理新颖的初始状态、外部扰动和新目标。我们通过仿真和真实机器人实验，使用具有关节部件、部分可观测性和几何约束的多样化对象集，验证了方法的有效性。

> We introduce Behavior from Language and Demonstration (BLADE), a framework for long-horizon robotic manipulation by integrating imitation learning and model-based planning. BLADE leverages language-annotated demonstrations, extracts abstract action knowledge from large language models (LLMs), and constructs a library of structured, high-level action representations. These representations include preconditions and effects grounded in visual perception for each high-level action, along with corresponding controllers implemented as neural network-based policies. BLADE can recover such structured representations automatically, without manually labeled states or symbolic definitions. BLADE shows significant capabilities in generalizing to novel situations, including novel initial states, external state perturbations, and novel goals. We validate the effectiveness of our approach both in simulation and on real robots with a diverse set of objects with articulated parts, partial observability, and geometric constraints.

[Arxiv](https://arxiv.org/abs/2505.21981)