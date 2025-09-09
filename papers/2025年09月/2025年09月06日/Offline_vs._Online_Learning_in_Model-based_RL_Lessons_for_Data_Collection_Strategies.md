# 基于模型的强化学习中的离线学习与在线学习：数据收集策略的经验启示

发布时间：2025年09月06日

`强化学习` `基础理论`

> Offline vs. Online Learning in Model-based RL: Lessons for Data Collection Strategies

# 摘要

> 在基于模型的强化学习中，数据收集是学习稳健世界模型的关键。目前主流策略有两种：在线训练时通过与环境交互主动采集轨迹，或直接使用离线数据集训练。乍看之下，世界模型因具备学习任务无关环境动态的特性，本应是离线训练的理想选择。但文献中尚未深入探究在线与离线数据对世界模型的影响，及其对最终任务性能的作用。为此，我们在基于模型的框架下对两种范式展开研究，并在31个不同环境中进行了实验。研究发现，在线智能体的性能显著优于离线智能体。我们发现离线智能体性能下降的核心问题在于：测试时会遇到分布外状态。这一问题源于：离线数据集缺乏在线智能体的自我校正机制，且状态空间覆盖有限，导致智能体的想象轨迹与真实轨迹展开不匹配，进而影响策略训练。我们发现，通过固定或自适应的额外在线交互，可有效缓解该问题，仅需少量交互数据即可恢复在线训练的性能。此外，纳入探索数据也能减轻离线智能体的性能损失。基于上述发现，我们建议在构建大型数据集时加入探索数据——当前研究多仅关注专家数据，这一做法有待改进。

> Data collection is crucial for learning robust world models in model-based reinforcement learning. The most prevalent strategies are to actively collect trajectories by interacting with the environment during online training or training on offline datasets. At first glance, the nature of learning task-agnostic environment dynamics makes world models a good candidate for effective offline training. However, the effects of online vs. offline data on world models and thus on the resulting task performance have not been thoroughly studied in the literature. In this work, we investigate both paradigms in model-based settings, conducting experiments on 31 different environments. First, we showcase that online agents outperform their offline counterparts. We identify a key challenge behind performance degradation of offline agents: encountering Out-Of-Distribution states at test time. This issue arises because, without the self-correction mechanism in online agents, offline datasets with limited state space coverage induce a mismatch between the agent's imagination and real rollouts, compromising policy training. We demonstrate that this issue can be mitigated by allowing for additional online interactions in a fixed or adaptive schedule, restoring the performance of online training with limited interaction data. We also showcase that incorporating exploration data helps mitigate the performance degradation of offline agents. Based on our insights, we recommend adding exploration data when collecting large datasets, as current efforts predominantly focus on expert data alone.

[Arxiv](https://arxiv.org/abs/2509.05735)