# MCTS-EP：借助在线偏好优化赋能具身规划

发布时间：2025年09月21日

`Agent` `工业与制造`

> MCTS-EP: Empowering Embodied Planning with Online Preference Optimization

# 摘要

> 本文提出了MCTS-EP——一个融合大型语言模型（LLM）与蒙特卡洛树搜索（MCTS）的在线学习框架，旨在训练具身智能体。该框架集成三大核心组件：用于偏好数据收集的MCTS引导探索、高效多模态推理机制，以及基于偏好优化的迭代训练流程。理论证明，在损失函数强凸的情况下，MCTS-EP比传统同策略算法的性能边界更优，且可被表述为GAIL的搜索增强变体。MCTS-EP在多个基准测试中均达到当前最优性能：在ALFWorld中，文本和视觉任务成功率分别达92%和87%；在WebShop中，平均奖励为0.81；在视觉ALFWorld中，平均交互步骤从18.7/19.5步减少至10.2/9.9步。

> This paper introduces MCTS-EP, an online learning framework that combines large language models (LLM) with Monte Carlo Tree Search (MCTS) for training embodied agents. MCTS-EP integrates three key components: MCTS-guided exploration for preference data collection, efficient multi-modal reasoning mechanism, and iterative training pipeline based on preference optimization. We theoretically prove that MCTS-EP achieves better performance bounds than conventional on-policy algorithms when the loss function is strongly convex, and demonstrate that it can be formulated as a search-enhanced variant of GAIL. MCTS-EP achieves state-of-the-art performace across serval benchmarks. In ALFWorld, it achieves 92% and 87% success rates for textual and visual tasks. In WebShop, it reaches an average reward of 0.81. MTCS-EP also reduces average interaction steps from from 18.7/19.5 to 10.2/9.9 steps in visual ALFWorld.Code available at: https://github.com/xuhang-2/Embodied-Agent-Planning

[Arxiv](https://arxiv.org/abs/2509.17116)