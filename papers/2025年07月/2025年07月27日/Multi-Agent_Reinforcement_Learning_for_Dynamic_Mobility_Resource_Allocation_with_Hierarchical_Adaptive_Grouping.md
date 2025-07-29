# 多智能体强化学习用于动态移动资源分配：分层自适应分组

发布时间：2025年07月27日

`Agent` `城市交通` `智能交通系统`

> Multi-Agent Reinforcement Learning for Dynamic Mobility Resource Allocation with Hierarchical Adaptive Grouping

# 摘要

> 在城市环境中平衡出行需求与供给，出行资源的分配至关重要。本文提出了一种名为分层自适应分组参数共享（HAG-PS）的新型多智能体强化学习方法，用于动态出行资源分配。该方法旨在解决两个关键挑战：出行资源分配策略的动态共享机制，以及在城市规模环境中实现高效的参数共享。

HAG-PS通过以下创新设计应对上述挑战：首先，采用分层方法整合出行资源状态的全局与局部信息；其次，基于编码轨迹的相似性，动态拆分或合并代理组；最后，通过可学习的身份嵌入实现更智能的代理专业化。

我们基于真实世界纽约市自行车共享数据（总计超过120万次骑行）进行了广泛实验，结果显示HAG-PS显著优于其他基线方法，特别是在提高自行车可用性方面表现突出。

> Allocating mobility resources (e.g., shared bikes/e-scooters, ride-sharing vehicles) is crucial for rebalancing the mobility demand and supply in the urban environments. We propose in this work a novel multi-agent reinforcement learning named Hierarchical Adaptive Grouping-based Parameter Sharing (HAG-PS) for dynamic mobility resource allocation. HAG-PS aims to address two important research challenges regarding multi-agent reinforcement learning for mobility resource allocation: (1) how to dynamically and adaptively share the mobility resource allocation policy (i.e., how to distribute mobility resources) across agents (i.e., representing the regional coordinators of mobility resources); and (2) how to achieve memory-efficient parameter sharing in an urban-scale setting. To address the above challenges, we have provided following novel designs within HAG-PS. To enable dynamic and adaptive parameter sharing, we have designed a hierarchical approach that consists of global and local information of the mobility resource states (e.g., distribution of mobility resources). We have developed an adaptive agent grouping approach in order to split or merge the groups of agents based on their relative closeness of encoded trajectories (i.e., states, actions, and rewards). We have designed a learnable identity (ID) embeddings to enable agent specialization beyond simple parameter copy. We have performed extensive experimental studies based on real-world NYC bike sharing data (a total of more than 1.2 million trips), and demonstrated the superior performance (e.g., improved bike availability) of HAG-PS compared with other baseline approaches.

[Arxiv](https://arxiv.org/abs/2507.20377)