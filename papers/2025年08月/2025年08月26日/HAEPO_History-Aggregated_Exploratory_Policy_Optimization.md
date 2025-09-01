# HAEPO：历史聚合探索性策略优化

发布时间：2025年08月26日

`强化学习` `基础理论`

> HAEPO: History-Aggregated Exploratory Policy Optimization

# 摘要

> 探索是现代学习的核心，无论是小型神经策略的强化学习环境，还是大型语言模型（LLMs）都离不开它。现有方法（如DPO）通过完整序列的对数似然捕捉模型决策的整个轨迹，而GRPO等方法则将逐token比率聚合为轨迹级更新。但在长程任务中，这两种方法都难以充分探索。为此，我们提出历史聚合探索策略优化（HAEPO）——一种具备历史感知的探索损失函数，专门应对这些局限。HAEPO将每条轨迹压缩为其对数概率之和（即累积对数似然），并在轨迹间应用Plackett-Luce softmax，得到与回报成比例的归一化权重，以此促进更充分的探索。我们引入熵正则化来稳定激进更新，避免过早收敛；同时，针对先前（参考）策略的冻结副本添加软KL惩罚。实验结果显示，HAEPO收敛迅速、探索全面、与真实奖励高度吻合，在各类任务中均展现出优于或媲美PPO、GRPO和DPO的稳健学习能力。因此，HAEPO通过显式利用完整轨迹历史，在探索与稳定性之间取得平衡，为学习任务提供了一个稳定且可解释的框架。

> Exploration is essential in modern learning, from reinforcement learning environments with small neural policies to large language models (LLMs). Existing work, such as DPO, leverages full sequence log-likelihoods to capture an entire trajectory of the model's decisions, while methods like GRPO aggregate per-token ratios into a trajectory-level update. However, both often limit exploration on long-horizon tasks. We introduce History-Aggregated Exploratory Policy Optimization (HAEPO), a history-aware exploratory loss to combat these shortcomings. HAEPO compresses each trajectory into the sum of its logarithmic probabilities (a cumulative logarithmic likelihood), and applies a Plackett-Luce softmax across trajectories to obtain normalized weights proportional to their returns, thus encouraging broader exploration. We add entropy regularization to stabilize the aggressive updates to prevent premature collapse and a soft KL penalty relative to a frozen copy of the previous (reference) policy. Empirically, HAEPO converges fast, explores thoroughly, aligns closely with true rewards, and demonstrates robust learning behavior better or at par with PPO, GRPO, and DPO across diverse tasks. Thus, HAEPO provides a stable and interpretable framework by explicitly leveraging full-trajectory history while balancing exploration and stability.

[Arxiv](https://arxiv.org/abs/2508.18884)