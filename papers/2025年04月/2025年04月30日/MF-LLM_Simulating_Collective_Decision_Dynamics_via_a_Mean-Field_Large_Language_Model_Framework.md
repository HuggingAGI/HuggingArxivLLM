# MF-LLM：利用均场大规模语言模型框架模拟集体决策动力学

发布时间：2025年04月30日

`LLM应用` `社会模拟` `集体决策`

> MF-LLM: Simulating Collective Decision Dynamics via a Mean-Field Large Language Model Framework

# 摘要

> 集体决策的模拟不仅需要个体行为的简单聚合，更源于个体间的动态互动。尽管大型语言模型（LLMs）在社会模拟领域展现出潜力，但现有方法往往与现实数据存在偏差。为填补这一空白，我们提出了基于均场理论的LLM框架（MF-LLM），该框架通过显式建模微观决策与宏观群体间的反馈循环，实现了更精准的社会模拟。MF-LLM框架由两个核心模型组成：一个基于个体状态和群体信息生成个体行为的策略模型，以及一个通过最新个体决策更新群体分布的均场模型。两者的协同工作能够有效模拟集体决策的动态演变过程。为了更好地匹配现实数据，我们引入了基于信息瓶颈原理的IB-Tune微调方法，该方法在最大化群体分布对未来行为的相关性的同时，显著降低了与历史数据的冗余。我们在真实社会数据集上的评估显示，MF-LLM与人类群体分布的KL散度相比传统非均场基线降低了47%，并实现了精准的趋势预测和干预规划。该框架在七个不同领域和四种主流LLM架构上均表现出良好的泛化能力，为高保真的社会模拟提供了坚实的技术基础。

> Simulating collective decision-making involves more than aggregating individual behaviors; it arises from dynamic interactions among individuals. While large language models (LLMs) show promise for social simulation, existing approaches often exhibit deviations from real-world data. To address this gap, we propose the Mean-Field LLM (MF-LLM) framework, which explicitly models the feedback loop between micro-level decisions and macro-level population. MF-LLM alternates between two models: a policy model that generates individual actions based on personal states and group-level information, and a mean field model that updates the population distribution from the latest individual decisions. Together, they produce rollouts that simulate the evolving trajectories of collective decision-making. To better match real-world data, we introduce IB-Tune, a fine-tuning method for LLMs grounded in the information bottleneck principle, which maximizes the relevance of population distributions to future actions while minimizing redundancy with historical data. We evaluate MF-LLM on a real-world social dataset, where it reduces KL divergence to human population distributions by 47 percent over non-mean-field baselines, and enables accurate trend forecasting and intervention planning. It generalizes across seven domains and four LLM backbones, providing a scalable foundation for high-fidelity social simulation.

[Arxiv](https://arxiv.org/abs/2504.21582)