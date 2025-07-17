# 展望未来：强化轨迹预测，基于奖励启发式

发布时间：2025年07月16日

`LLM应用` `自动驾驶`

> Foresight in Motion: Reinforcing Trajectory Prediction with Reward Heuristics

# 摘要

> 道路上交通参与者的运动预测对于自动驾驶系统的安全性至关重要，既是重大挑战，也是关键需求。与现有大多数直接预测未来轨迹的数据驱动方法不同，我们从规划角度重新思考这一任务，提出了一种“先推理后预测”的策略，将行为意图明确作为轨迹预测的空间引导。为此，我们引入了一个基于奖励驱动的意图推理器，该推理器基于一种新颖的基于查询的逆强化学习（IRL）方案。我们的方法首先将交通参与者和场景元素编码为统一的向量化表示，通过基于查询的范式聚合上下文特征，从而推导出奖励分布。这一分布作为目标代理在给定场景中的行为紧凑且信息丰富的表示，通过IRL实现。在该奖励启发的指导下，我们执行策略回滚以推理多个合理意图，为后续轨迹生成提供有价值的先验信息。最后，我们开发了一种分层的DETR-like解码器，结合双向选择性状态空间模型，生成准确的未来轨迹及其相关概率。在大规模Argoverse和nuScenes数据集上的广泛实验表明，我们的方法显著提升了轨迹预测的置信度，并在与现有最先进方法的对比中取得了极具竞争力的性能表现。

> Motion forecasting for on-road traffic agents presents both a significant challenge and a critical necessity for ensuring safety in autonomous driving systems. In contrast to most existing data-driven approaches that directly predict future trajectories, we rethink this task from a planning perspective, advocating a "First Reasoning, Then Forecasting" strategy that explicitly incorporates behavior intentions as spatial guidance for trajectory prediction. To achieve this, we introduce an interpretable, reward-driven intention reasoner grounded in a novel query-centric Inverse Reinforcement Learning (IRL) scheme. Our method first encodes traffic agents and scene elements into a unified vectorized representation, then aggregates contextual features through a query-centric paradigm. This enables the derivation of a reward distribution, a compact yet informative representation of the target agent's behavior within the given scene context via IRL. Guided by this reward heuristic, we perform policy rollouts to reason about multiple plausible intentions, providing valuable priors for subsequent trajectory generation. Finally, we develop a hierarchical DETR-like decoder integrated with bidirectional selective state space models to produce accurate future trajectories along with their associated probabilities. Extensive experiments on the large-scale Argoverse and nuScenes motion forecasting datasets demonstrate that our approach significantly enhances trajectory prediction confidence, achieving highly competitive performance relative to state-of-the-art methods.

[Arxiv](https://arxiv.org/abs/2507.12083)