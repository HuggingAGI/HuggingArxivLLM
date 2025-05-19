# # ReaCritic：以大型推理Transformer为基础的深度强化学习批评家模型扩展，针对异构网络的扩展研究。

发布时间：2025年05月16日

`LLM应用` `无线通信` `人工智能`

> ReaCritic: Large Reasoning Transformer-based DRL Critic-model Scaling For Heterogeneous Networks

# 摘要

> 异构网络（HetNets）的用户需求多样性和无线环境的时变性为智能管理带来了严峻挑战，这些因素显著增加了决策复杂度，限制了现有深度强化学习（DRL）方法的适应性。在基于值函数或演员-评论家结构的DRL算法中，评论家组件通过估计价值函数在指导策略学习中发挥关键作用。然而，传统的评论家模型通常采用浅层架构，直接将观测映射为标量估计值，限制了其处理多任务复杂性的能力。近期研究显示，大语言模型（LLMs）推理时的扩展生成中间推理步骤能显著提升决策质量。受此启发，我们提出ReaCritic，一种基于大型推理Transformer的评论家模型扩展方案，将推理能力引入DRL。ReaCritic通过并行状态-动作输入实现水平推理，并通过深层Transformer堆叠进行垂直推理。它与多种基于值函数和演员-评论家结构的DRL算法兼容，并在动态无线环境中增强了泛化能力。大量实验表明，ReaCritic在各种HetNet设置和标准OpenAI Gym控制任务中提升了收敛速度和最终性能。

> Heterogeneous Networks (HetNets) pose critical challenges for intelligent management due to the diverse user requirements and time-varying wireless conditions. These factors introduce significant decision complexity, which limits the adaptability of existing Deep Reinforcement Learning (DRL) methods. In many DRL algorithms, especially those involving value-based or actor-critic structures, the critic component plays a key role in guiding policy learning by estimating value functions. However, conventional critic models often use shallow architectures that map observations directly to scalar estimates, limiting their ability to handle multi-task complexity. In contrast, recent progress in inference-time scaling of Large Language Models (LLMs) has shown that generating intermediate reasoning steps can significantly improve decision quality. Motivated by this, we propose ReaCritic, a large reasoning transformer-based criticmodel scaling scheme that brings reasoning ability into DRL. ReaCritic performs horizontal reasoning over parallel state-action inputs and vertical reasoning through deep transformer stacks. It is compatible with a broad range of value-based and actor-critic DRL algorithms and enhances generalization in dynamic wireless environments. Extensive experiments demonstrate that ReaCritic improves convergence speed and final performance across various HetNet settings and standard OpenAI Gym control tasks.

[Arxiv](https://arxiv.org/abs/2505.10992)