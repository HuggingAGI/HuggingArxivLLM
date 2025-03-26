# AgentDropout：动态智能体淘汰，实现Token高效与高性能的LLM多智能体协作

发布时间：2025年03月24日

`Agent` `人工智能` `计算机科学`

> AgentDropout: Dynamic Agent Elimination for Token-Efficient and High-Performance LLM-Based Multi-Agent Collaboration

# 摘要

> 基于大型语言模型（LLMs）的多智能体系统（MAS）在协作问题解决方面展现出巨大潜力。然而，通信效率低下和任务表现不佳仍是亟待解决的难题，因此智能体通信拓扑结构的设计至关重要。受管理理论启发，我们提出了AgentDropout方法。该方法通过优化通信图的邻接矩阵，识别并消除不同通信轮次中的冗余智能体及通信，从而提升令牌效率和任务表现。与现有最优方法相比，AgentDropout实现了提示令牌消耗平均减少21.6%，完成令牌消耗平均减少18.4%，同时任务表现提升了1.14。此外，扩展实验表明，AgentDropout在领域迁移和结构鲁棒性方面表现优异，进一步证明了其可靠性和有效性。我们已将代码发布在https://github.com/wangzx1219/AgentDropout。

> Multi-agent systems (MAS) based on large language models (LLMs) have demonstrated significant potential in collaborative problem-solving. However, they still face substantial challenges of low communication efficiency and suboptimal task performance, making the careful design of the agents' communication topologies particularly important. Inspired by the management theory that roles in an efficient team are often dynamically adjusted, we propose AgentDropout, which identifies redundant agents and communication across different communication rounds by optimizing the adjacency matrices of the communication graphs and eliminates them to enhance both token efficiency and task performance. Compared to state-of-the-art methods, AgentDropout achieves an average reduction of 21.6% in prompt token consumption and 18.4% in completion token consumption, along with a performance improvement of 1.14 on the tasks. Furthermore, the extended experiments demonstrate that AgentDropout achieves notable domain transferability and structure robustness, revealing its reliability and effectiveness. We release our code at https://github.com/wangzx1219/AgentDropout.

[Arxiv](https://arxiv.org/abs/2503.18891)