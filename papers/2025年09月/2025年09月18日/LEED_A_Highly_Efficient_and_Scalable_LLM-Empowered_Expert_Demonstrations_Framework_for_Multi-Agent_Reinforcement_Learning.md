# LEED：高效可扩展的LLM赋能专家演示框架——面向多智能体强化学习

发布时间：2025年09月18日

`强化学习` `基础理论`

> LEED: A Highly Efficient and Scalable LLM-Empowered Expert Demonstrations Framework for Multi-Agent Reinforcement Learning

# 摘要

> 多智能体强化学习（MARL）在复杂环境的智能决策中展现出巨大潜力，但其随着智能体数量增多，面临协调与可扩展性瓶颈。为此，我们提出LLM赋能的多智能体强化学习专家演示框架（LEED），该框架包含两个模块：演示生成（DG）模块与策略优化（PO）模块。具体而言，DG模块借助大型语言模型生成环境交互指令，进而产出高质量演示；PO模块采用去中心化训练范式，每个智能体利用生成的演示构建专家策略损失，并与自身策略损失相结合。这让每个智能体能够结合专家知识与自身经验，高效个性化并优化本地策略。实验结果显示，与最先进的基线方法相比，LEED在样本效率、时间效率及稳健可扩展性上均表现更优。

> Multi-agent reinforcement learning (MARL) holds substantial promise for intelligent decision-making in complex environments. However, it suffers from a coordination and scalability bottleneck as the number of agents increases. To address these issues, we propose the LLM-empowered expert demonstrations framework for multi-agent reinforcement learning (LEED). LEED consists of two components: a demonstration generation (DG) module and a policy optimization (PO) module. Specifically, the DG module leverages large language models to generate instructions for interacting with the environment, thereby producing high-quality demonstrations. The PO module adopts a decentralized training paradigm, where each agent utilizes the generated demonstrations to construct an expert policy loss, which is then integrated with its own policy loss. This enables each agent to effectively personalize and optimize its local policy based on both expert knowledge and individual experience. Experimental results show that LEED achieves superior sample efficiency, time efficiency, and robust scalability compared to state-of-the-art baselines.

[Arxiv](https://arxiv.org/abs/2509.14680)