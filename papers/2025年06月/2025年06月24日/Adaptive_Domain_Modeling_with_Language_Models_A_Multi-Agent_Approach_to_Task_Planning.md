# 利用语言模型的自适应领域建模：一种面向任务规划的多智能体方法

发布时间：2025年06月24日

`Agent` `机器人` `自动化系统`

> Adaptive Domain Modeling with Language Models: A Multi-Agent Approach to Task Planning

# 摘要

> # TAPAS：基于任务的适应与规划多智能体框架
我们推出 TAPAS，一个创新性的多智能体框架，它巧妙地将大型语言模型 (LLMs) 与符号规划相结合，能够在无需手动构建环境模型的情况下解决复杂任务。TAPAS 采用了专门设计的 LLM 驱动智能体，这些智能体能够通过结构化的工具调用机制，协作生成和适应所需的领域模型、初始状态和目标规范。通过这种工具化的交互方式，下游智能体可以向上游智能体发起修改请求，从而实现对新属性和约束的灵活适应，而无需手动重新定义领域。此外，TAPAS 配备了 ReAct（推理+行动）风格的执行智能体，并借助自然语言计划翻译功能，成功地在动态生成的计划与现实世界机器人能力之间架起了桥梁。在基准规划领域和 VirtualHome 模拟现实环境中，TAPAS 都展现出了卓越的性能表现。

> We introduce TAPAS (Task-based Adaptation and Planning using AgentS), a multi-agent framework that integrates Large Language Models (LLMs) with symbolic planning to solve complex tasks without the need for manually defined environment models. TAPAS employs specialized LLM-based agents that collaboratively generate and adapt domain models, initial states, and goal specifications as needed using structured tool-calling mechanisms. Through this tool-based interaction, downstream agents can request modifications from upstream agents, enabling adaptation to novel attributes and constraints without manual domain redefinition. A ReAct (Reason+Act)-style execution agent, coupled with natural language plan translation, bridges the gap between dynamically generated plans and real-world robot capabilities. TAPAS demonstrates strong performance in benchmark planning domains and in the VirtualHome simulated real-world environment.

[Arxiv](https://arxiv.org/abs/2506.19592)