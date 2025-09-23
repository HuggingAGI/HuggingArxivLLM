# 大型语言模型赋能的决策转换器：面向无人机数据收集

发布时间：2025年09月19日

`强化学习` `交通运输`

> Large Language Model-Empowered Decision Transformer for UAV-Enabled Data Collection

# 摘要

> 利用无人机（UAVs）从空间分布式设备进行可靠且节能的数据收集，在支持各类物联网（IoT）应用方面前景广阔。但无人机续航能力与通信范围有限，因此智能轨迹规划至关重要。尽管强化学习（RL）已广泛用于无人机轨迹优化，但其交互特性在实际环境中存在高昂成本与风险。离线强化学习虽能缓解这些问题，却易受训练不稳定影响，且严重依赖专家级数据集。为应对这些挑战，我们提出联合无人机轨迹规划与资源分配问题，以最大化数据收集的节能效率。首先将资源分配子问题转化为等效线性规划模型，并以多项式时间复杂度实现最优求解。接着，我们提出一种大型语言模型（LLM）增强的评论家正则化决策转换器（DT）框架（LLM-CRDT），用于学习高效的无人机控制策略。该框架通过引入评论家网络对DT模型训练进行正则化，将DT的序列建模能力与基于评论家的价值引导相结合，从而能从次优数据集中学习有效策略。此外，为缓解转换器模型的数据饥渴特性，我们采用预训练LLM作为DT的转换器骨干网络，并借助参数高效微调策略（如LoRA），实现了在小规模数据集和低计算开销下对无人机控制任务的快速适配。大量仿真显示，LLM-CRDT性能优于基准在线及离线强化学习方法，与当前最先进的DT方法相比，节能效率提升高达36.7%。

> The deployment of unmanned aerial vehicles (UAVs) for reliable and energy-efficient data collection from spatially distributed devices holds great promise in supporting diverse Internet of Things (IoT) applications. Nevertheless, the limited endurance and communication range of UAVs necessitate intelligent trajectory planning. While reinforcement learning (RL) has been extensively explored for UAV trajectory optimization, its interactive nature entails high costs and risks in real-world environments. Offline RL mitigates these issues but remains susceptible to unstable training and heavily rely on expert-quality datasets. To address these challenges, we formulate a joint UAV trajectory planning and resource allocation problem to maximize energy efficiency of data collection. The resource allocation subproblem is first transformed into an equivalent linear programming formulation and solved optimally with polynomial-time complexity. Then, we propose a large language model (LLM)-empowered critic-regularized decision transformer (DT) framework, termed LLM-CRDT, to learn effective UAV control policies. In LLM-CRDT, we incorporate critic networks to regularize the DT model training, thereby integrating the sequence modeling capabilities of DT with critic-based value guidance to enable learning effective policies from suboptimal datasets. Furthermore, to mitigate the data-hungry nature of transformer models, we employ a pre-trained LLM as the transformer backbone of the DT model and adopt a parameter-efficient fine-tuning strategy, i.e., LoRA, enabling rapid adaptation to UAV control tasks with small-scale dataset and low computational overhead. Extensive simulations demonstrate that LLM-CRDT outperforms benchmark online and offline RL methods, achieving up to 36.7\% higher energy efficiency than the current state-of-the-art DT approaches.

[Arxiv](https://arxiv.org/abs/2509.13934)