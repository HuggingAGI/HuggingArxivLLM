# 模型预测控制对抗模仿学习用于从观察到规划

发布时间：2025年07月29日

`Agent` `机器人`

> Model Predictive Adversarial Imitation Learning for Planning from Observation

# 摘要

> 人类演示数据通常模糊且不完整，这推动了模仿学习方法的发展，这些方法还能展现出可靠的规划行为。一种常见的规划-从-演示范式是通过逆向强化学习（IRL）学习奖励函数，然后通过模型预测控制（MPC）部署该奖励函数。为了整合这些方法，我们推导出一种将IRL中的策略替换为基于规划的代理的方法。通过与对抗模仿学习的结合，这种表述实现了从仅观察演示的端到端交互式规划器学习。除了在可解释性、复杂性和安全性方面的优势，我们还研究并观察到在样本效率、分布外泛化和鲁棒性方面的显著提升。研究包括使用少量到单个仅观察演示的模拟控制基准和现实世界导航实验的评估。

> Human demonstration data is often ambiguous and incomplete, motivating imitation learning approaches that also exhibit reliable planning behavior. A common paradigm to perform planning-from-demonstration involves learning a reward function via Inverse Reinforcement Learning (IRL) then deploying this reward via Model Predictive Control (MPC). Towards unifying these methods, we derive a replacement of the policy in IRL with a planning-based agent. With connections to Adversarial Imitation Learning, this formulation enables end-to-end interactive learning of planners from observation-only demonstrations. In addition to benefits in interpretability, complexity, and safety, we study and observe significant improvements on sample efficiency, out-of-distribution generalization, and robustness. The study includes evaluations in both simulated control benchmarks and real-world navigation experiments using few-to-single observation-only demonstrations.

[Arxiv](https://arxiv.org/abs/2507.21533)