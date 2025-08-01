# DynaSwarm 是一个创新的框架，专为基于 LLM 的多智能体系统设计，能够动态选择和调整图结构。通过优化智能体间的信息流动和交互模式，DynaSwarm 使协作更加高效。这种方法不仅显著提升了系统性能，还为复杂的多智能体场景提供了灵活且可扩展的解决方案。

发布时间：2025年07月31日

`Agent` `人工智能`

> DynaSwarm: Dynamically Graph Structure Selection for LLM-based Multi-agent System

# 摘要

> 现有的多智能体系统（MAS）框架往往依赖于手动设计的静态协作图结构，这限制了系统的适应性和性能表现。为了解决这一问题，我们提出了DynaSwarm，这是一个动态框架，通过两大创新来提升基于LLM的MAS性能：（1）一种actor-critic强化学习（A2C）机制，能够优化图结构，并在稳定性上超越之前的RL方法；（2）一个动态图选择器，通过参数高效的LLM微调，为每个输入样本自适应地选择最优的图结构。DynaSwarm摒弃了僵化的、一刀切的图架构，而是利用样本特有的特性，动态地将查询路由到专门的智能体网络中。我们还提出对演示检索器进行微调，以充分利用in-context学习（ICL）的能力。在问答、数学推理和编码任务上的大量实验表明，DynaSwarm在多个LLM模型上始终优于最先进的单智能体和MAS基线。我们的研究结果突显了在LLM MAS设计中，样本感知的结构灵活性的重要性。

> Current multi-agent systems (MAS) frameworks often rely on manually designed and static collaboration graph structures, limiting adaptability and performance. To address these limitations, we propose DynaSwarm, a dynamic framework that enhances LLM-based MAS through two key innovations: (1) an actor-critic reinforcement learning (A2C) mechanism to optimize graph structures with improved stability over prior RL methods, and (2) a dynamic graph selector that adaptively chooses the optimal graph structure for each input sample via parameter-efficient LLM fine-tuning. DynaSwarm eliminates the need for rigid, one-fits-all graph architectures, instead leveraging sample-specific idiosyncrasies to dynamically route queries through specialized agent networks. (c) We propose to fine-tune the demonstration retriever to fully exploit the power of in-context learning (ICL). Extensive experiments on question answering, mathematical reasoning, and coding tasks demonstrate that DynaSwarm consistently outperforms state-of-the-art single-agent and MAS baselines across multiple LLM backbones. Our findings highlight the importance of sample-aware structural flexibility in LLM MAS designs.

[Arxiv](https://arxiv.org/abs/2507.23261)