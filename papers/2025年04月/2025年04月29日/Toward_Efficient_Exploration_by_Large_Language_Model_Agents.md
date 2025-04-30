# 大型语言模型代理实现高效探索之路

发布时间：2025年04月29日

`Agent` `人工智能`

> Toward Efficient Exploration by Large Language Model Agents

# 摘要

> 强化学习（RL）领域中一个蓬勃发展的是围绕大型语言模型（LLMs）设计序列决策代理的领域。尽管由现代LLMs驱动的自主决策代理可以促进许多现实世界的应用，但实现这些成功需要代理具备数据高效的RL能力。在RL中实现数据高效的一个关键障碍是探索，我们证明了这一挑战使得许多最近提出的LLM代理设计难以应对。同时，来自RL文献中已知能够优雅解决探索问题的经典算法需要技术工具，这些工具在纯自然语言环境中可能难以实现。在这项工作中，我们并没有依赖微调或在上下文中学习来引导LLMs隐式模仿RL算法，而是展示了如何利用LLMs来显式实现一个已有的RL算法（基于后验采样的强化学习）——该算法在统计高效探索方面的能力已得到充分研究。我们提供了实证结果，展示了我们基于LLM实现的已知数据高效RL算法在需要审慎探索的自然语言任务中可以显著更有效。


> A burgeoning area within reinforcement learning (RL) is the design of sequential decision-making agents centered around large language models (LLMs). While autonomous decision-making agents powered by modern LLMs could facilitate numerous real-world applications, such successes demand agents that are capable of data-efficient RL. One key obstacle to achieving data efficiency in RL is exploration, a challenge that we demonstrate many recent proposals for LLM agent designs struggle to contend with. Meanwhile, classic algorithms from the RL literature known to gracefully address exploration require technical machinery that can be challenging to operationalize in purely natural language settings. In this work, rather than relying on finetuning or in-context learning to coax LLMs into implicitly imitating a RL algorithm, we illustrate how LLMs can be used to explicitly implement an existing RL algorithm (Posterior Sampling for Reinforcement Learning) whose capacity for statistically-efficient exploration is already well-studied. We offer empirical results demonstrating how our LLM-based implementation of a known, data-efficient RL algorithm can be considerably more effective in natural language tasks that demand prudent exploration.

[Arxiv](https://arxiv.org/abs/2504.20997)