# LLM引导的多智能体强化学习：面向点对点电力市场的可扩展公平性塑造

发布时间：2025年08月25日

`强化学习` `能源与环保`

> Scalable Fairness Shaping with LLM-Guided Multi-Agent Reinforcement Learning for Peer-to-Peer Electricity Markets

# 摘要

> 随着屋顶光伏与家庭能源管理系统的普及，点对点（P2P）能源交易正成为现代配电系统的核心。然而，现有市场及强化学习设计多侧重效率或私人利润，在不确定性环境下几乎无法提供实时指导以保障公平结果。为填补这一空白，本文提出一种公平感知的多智能体强化学习框架FairMarket-RL——该框架中，大型语言模型（LLM）评论家在部分可观测性及离散价格-数量动作的连续双重拍卖中塑造投标策略。每个交易时段结束后，LLM会返回标准化的公平分数，包括对电网公平性（FTG）、卖方间公平性（FBS）及定价公平性（FPP）；这些分数通过梯度系数与可调缩放整合至奖励机制，确保公平指导对经济激励起到补充而非主导作用。该环境模拟真实的居民负荷与光伏曲线，并对价格、物理可行性及策略更新稳定性施加硬性约束。通过从小型试点到大型模拟社区，再到混合资产真实数据集的一系列实验验证，该框架不仅推动交易向本地P2P交易转移、较纯电网采购降低了用户成本，还在参与者间维持了高度公平性，并保障了公用事业的可持续性。针对太阳能可得性与总需求的敏感性分析进一步表明其性能稳健，为构建经济高效、社会公平且技术可靠的去中心化电力市场提供了一条可扩展的LLM引导路径。

> Peer-to-peer (P2P) energy trading is becoming central to modern distribution systems as rooftop PV and home energy management systems become pervasive, yet most existing market and reinforcement learning designs emphasize efficiency or private profit and offer little real-time guidance to ensure equitable outcomes under uncertainty. To address this gap, a fairness-aware multiagent reinforcement learning framework, FairMarket-RL, is proposed in which a large language model (LLM) critic shapes bidding policies within a continuous double auction under partial observability and discrete price-quantity actions. After each trading slot, the LLM returns normalized fairness scores Fairness-to-Grid (FTG), Fairness-Between-Sellers (FBS), and Fairness-of-Pricing (FPP) that are integrated into the reward via ramped coefficients and tunable scaling, so that fairness guidance complements, rather than overwhelms, economic incentives. The environment models realistic residential load and PV profiles and enforce hard constraints on prices, physical feasibility, and policy-update stability. Across a progression of experiments from a small pilot to a larger simulated community and a mixed-asset real-world dataset, the framework shifts exchanges toward local P2P trades, lowers consumer costs relative to grid-only procurement, sustains strong fairness across participants, and preserves utility viability. Sensitivity analyses over solar availability and aggregate demand further indicate robust performance, suggesting a scalable, LLM-guided pathway to decentralized electricity markets that are economically efficient, socially equitable, and technically sound.

[Arxiv](https://arxiv.org/abs/2508.18610)