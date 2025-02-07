# 模拟流：一种编程范式，用于控制大型语言模型并借助生成式AI构建复杂系统

发布时间：2025年01月30日

`Agent

理由：这篇论文介绍了Simulation Streams，这是一种专门用于控制和利用大型语言模型（LLMs）进行复杂动态模拟和智能体工作流的编程范式。论文的核心目标是构建一个框架，充分发挥LLMs的智能体能力，并解决其在一致性维护、信息选择性忽略/包含以及严格规则执行方面的不足。Simulation Streams通过基于状态的方法和实体-组件-系统（ECS）架构，增强了输出流的模块化，支持复杂的多实体模拟。这些内容主要涉及智能体（Agent）的设计和应用，因此将其分类为Agent。` `模拟系统` `智能体`

> Simulation Streams: A Programming Paradigm for Controlling Large Language Models and Building Complex Systems with Generative AI

# 摘要

> 我们推出了Simulation Streams，这是一种专为高效控制和利用大型语言模型（LLMs）进行复杂动态模拟和智能体工作流而设计的编程范式。我们的核心目标是构建一个最小干扰的框架，充分发挥LLMs的智能体能力，同时解决其在一致性维护、信息选择性忽略/包含以及严格规则执行方面的不足。Simulation Streams采用基于状态的方法，通过“操作员”按序修改变量，生成重复格式的输出，并遵循状态变量的一致规则。这种方法将LLMs聚焦于特定任务，同时确保上下文流保持“分布内”。该范式结合了实体-组件-系统（ECS）架构，使程序编写更加直观，便于跨组件和实体的工作流复用。ECS架构增强了输出流的模块化，支持复杂的多实体模拟，同时保持格式一致性、信息控制和规则执行。我们提供了一个自定义编辑器，用于创建、运行和分析模拟。通过一个持续进行的市场经济模拟、三个角色在公园玩接球游戏的社会模拟以及一系列经典强化学习基准任务，我们展示了Simulation Streams的多功能性。这些示例证明了Simulation Streams在数百至数千次迭代中处理复杂演变场景的能力，促进不同智能体工作流和模型的比较，并在LLM驱动的模拟中保持一致性和持续有趣的发展。

> We introduce Simulation Streams, a programming paradigm designed to efficiently control and leverage Large Language Models (LLMs) for complex, dynamic simulations and agentic workflows. Our primary goal is to create a minimally interfering framework that harnesses the agentic abilities of LLMs while addressing their limitations in maintaining consistency, selectively ignoring/including information, and enforcing strict world rules. Simulation Streams achieves this through a state-based approach where variables are modified in sequential steps by "operators," producing output on a recurring format and adhering to consistent rules for state variables. This approach focus the LLMs on defined tasks, while aiming to have the context stream remain "in-distribution". The approach incorporates an Entity-Component-System (ECS) architecture to write programs in a more intuitive manner, facilitating reuse of workflows across different components and entities. This ECS approach enhances the modularity of the output stream, allowing for complex, multi-entity simulations while maintaining format consistency, information control, and rule enforcement. It is supported by a custom editor that aids in creating, running, and analyzing simulations. We demonstrate the versatility of simulation streams through an illustrative example of an ongoing market economy simulation, a social simulation of three characters playing a game of catch in a park and a suite of classical reinforcement learning benchmark tasks. These examples showcase Simulation Streams' ability to handle complex, evolving scenarios over 100s-1000s of iterations, facilitate comparisons between different agent workflows and models, and maintain consistency and continued interesting developments in LLM-driven simulations.

[Arxiv](https://arxiv.org/abs/2501.18668)