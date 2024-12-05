# 在一种模式下学习：化解离线强化学习中的多模态难题

发布时间：2024年12月04日

`Agent` `机器学习`

> Learning on One Mode: Addressing Multi-Modality in Offline Reinforcement Learning

# 摘要

> 离线强化学习（RL）旨在从静态数据集里习得最优策略，且无需与环境交互。常见难题在于应对多模态动作分布，即数据中呈现了多种行为。现有的方法往往假定为单模态行为策略，一旦此假定被打破，就会产生次优性能。我们提出了单模态加权模仿学习（LOM）这一新颖方法，它专注于从行为策略的单个有前景的模式中学习。借助高斯混合模型来识别模式，并依据预期回报选取最佳模式，LOM 规避了对冲突动作求平均的弊端。理论上，我们证明 LOM 在保持策略学习简洁性的同时提升了性能。实践中，LOM 在标准的 D4RL 基准测试里胜过现有方法，在复杂的多模态场景中彰显了其有效性。

> Offline reinforcement learning (RL) seeks to learn optimal policies from static datasets without interacting with the environment. A common challenge is handling multi-modal action distributions, where multiple behaviours are represented in the data. Existing methods often assume unimodal behaviour policies, leading to suboptimal performance when this assumption is violated. We propose Weighted Imitation Learning on One Mode (LOM), a novel approach that focuses on learning from a single, promising mode of the behaviour policy. By using a Gaussian mixture model to identify modes and selecting the best mode based on expected returns, LOM avoids the pitfalls of averaging over conflicting actions. Theoretically, we show that LOM improves performance while maintaining simplicity in policy learning. Empirically, LOM outperforms existing methods on standard D4RL benchmarks and demonstrates its effectiveness in complex, multi-modal scenarios.

[Arxiv](https://arxiv.org/abs/2412.03258)