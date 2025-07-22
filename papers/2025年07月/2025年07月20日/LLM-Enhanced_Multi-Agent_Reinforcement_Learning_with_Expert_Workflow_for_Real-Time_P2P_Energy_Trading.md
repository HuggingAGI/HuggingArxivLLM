# # 基于LLM增强的多智能体强化学习结合专家工作流，用于实时点对点能源交易

发布时间：2025年07月20日

`Agent`

> LLM-Enhanced Multi-Agent Reinforcement Learning with Expert Workflow for Real-Time P2P Energy Trading

# 摘要

> 实时点对点（P2P）电力市场通过即时价格响应，动态适应可再生能源波动和需求变化，实现经济利益最大化并增强电网灵活性。然而，如何为海量个性化产消者提供扩展化的专家指导，仍面临重大挑战，包括多样化的决策需求和缺乏定制化建模框架。本文提出了一种集成大型语言模型与多智能体强化学习（LLM-MARL）的框架，用于实时P2P能源交易，以应对产消者技术能力有限、缺乏专家经验以及配电网络安全性问题。将大型语言模型引入作为专家，生成个性化策略，在集中训练与分散执行（CTDE）范式下，通过模仿学习引导多智能体强化学习。设计了基于差分注意力的评价网络以提升收敛性能。实验结果表明，LLM生成的策略能够有效替代人类专家。与基线算法相比，所提出的多智能体模仿学习算法在测试集上实现了显著更低的经济成本和电压越限率，同时保持了稳健稳定性。本研究通过将专家知识与智能体学习相结合，为实时P2P电力市场决策提供了一种有效解决方案。

> Real-time peer-to-peer (P2P) electricity markets dynamically adapt to fluctuations in renewable energy and variations in demand, maximizing economic benefits through instantaneous price responses while enhancing grid flexibility. However, scaling expert guidance for massive personalized prosumers poses critical challenges, including diverse decision-making demands and lack of customized modeling frameworks. This paper proposed an integrated large language model-multi-agent reinforcement learning (LLM-MARL) framework for real-time P2P energy trading to address challenges such as the limited technical capability of prosumers, the lack of expert experience, and security issues of distribution networks. LLMs are introduced as experts to generate personalized strategy, guiding MARL under the centralized training with decentralized execution (CTDE) paradigm through imitation learning. A differential attention-based critic network is designed to enhance convergence performance. Experimental results demonstrate that LLM generated strategies effectively substitute human experts. The proposed multi-agent imitation learning algorithms achieve significantly lower economic costs and voltage violation rates on test sets compared to baselines algorithms, while maintaining robust stability. This work provides an effective solution for real-time P2P electricity market decision-making by bridging expert knowledge with agent learning.

[Arxiv](https://arxiv.org/abs/2507.14995)