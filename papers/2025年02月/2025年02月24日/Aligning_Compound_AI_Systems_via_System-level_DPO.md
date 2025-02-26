# 对齐复合型AI系统的系统级DPO方法

发布时间：2025年02月24日

`Agent` `人工智能系统` `系统对齐`

> Aligning Compound AI Systems via System-level DPO

# 摘要

> 由多个相互作用的组件（如LLM代理和外部工具）组成的复合AI系统，在各种任务中都展现出卓越的表现。因此，将系统内的各个组件进行对齐，以生成与人类预期相符的一致性结果至关重要。然而，传统的对齐方法，如直接偏好优化（DPO），并不直接适用于复合AI系统。这些挑战包括组件之间的非可微分交互，使得端到端的梯度优化不可行。此外，系统级的偏好无法直接转化为组件级的偏好，进一步增加了对齐的难度。我们通过将复合AI系统建模为有向无环图（DAG），捕捉到代理之间的连接以及数据生成过程，来解决这些问题。我们提出了一种系统级的DPO（SysDPO），通过将DPO适应于这些DAG，来联合对齐复合系统。我们通过研究一个LLM和一个扩散模型的联合对齐，来展示我们方法的有效性。我们的探索为复合AI系统的对齐提供了见解，并为未来的发展奠定了基础。

> Compound AI systems, comprising multiple interacting components such as LLM agents and external tools, demonstrate state-of-the-art results across diverse tasks. It is hence crucial to align components within the system to produce consistent results that match human expectations. However, conventional alignment methods, such as Direct Preference Optimization (DPO), are not directly applicable to compound AI systems. These challenges include the non-differentiable interactions between components, making end-to-end gradient optimization infeasible. Additionally, system-level preferences cannot be directly translated into component-level preferences, further complicating alignment. We address the issues by formulating compound AI systems as Directed Acyclic Graphs (DAGs), capturing the connections between agents and the data generation processes. We propose a system-level DPO (SysDPO) to jointly align compound systems by adapting the DPO to operate on these DAGs. We study the joint alignment of an LLM and a diffusion model to demonstrate the effectiveness of our approach. Our exploration provides insights into the alignment of compound AI systems and lays a foundation for future advancements.

[Arxiv](https://arxiv.org/abs/2502.17721)