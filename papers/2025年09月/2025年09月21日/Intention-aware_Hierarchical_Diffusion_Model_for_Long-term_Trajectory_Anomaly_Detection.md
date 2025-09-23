# 意图感知的分层扩散模型：长期轨迹异常检测

发布时间：2025年09月21日

`Agent` `交通运输`

> Intention-aware Hierarchical Diffusion Model for Long-term Trajectory Anomaly Detection

# 摘要

> 长期轨迹异常检测是一项极具挑战性的任务，其难点在于轨迹数据的多样性和复杂的时空依赖关系。现有轨迹异常检测方法在分析智能体轨迹时，无法同时兼顾智能体的高层意图和导航的低层细节，这限制了它们捕捉正常轨迹完整多样性的能力。为此，本文提出一种无监督轨迹异常检测方法——意图感知分层扩散模型（IHiD），该方法通过高层意图评估与低层子轨迹分析双管齐下进行异常检测。具体而言，以逆Q学习作为高层模型，基于预测Q值判断子目标是否与智能体意图相符；同时，以扩散模型作为低层模型，根据子目标信息生成子轨迹，并通过重构误差实现异常检测。通过融合这两个模型，IHiD能够有效利用子目标转移知识，从而捕捉正常轨迹的多样分布。实验结果显示，IHiD方法在F1分数上较最先进的基线方法提升了30.2%，显著改善了异常检测性能。

> Long-term trajectory anomaly detection is a challenging problem due to the diversity and complex spatiotemporal dependencies in trajectory data. Existing trajectory anomaly detection methods fail to simultaneously consider both the high-level intentions of agents as well as the low-level details of the agent's navigation when analysing an agent's trajectories. This limits their ability to capture the full diversity of normal trajectories. In this paper, we propose an unsupervised trajectory anomaly detection method named Intention-aware Hierarchical Diffusion model (IHiD), which detects anomalies through both high-level intent evaluation and low-level sub-trajectory analysis. Our approach leverages Inverse Q Learning as the high-level model to assess whether a selected subgoal aligns with an agent's intention based on predicted Q-values. Meanwhile, a diffusion model serves as the low-level model to generate sub-trajectories conditioned on subgoal information, with anomaly detection based on reconstruction error. By integrating both models, IHiD effectively utilises subgoal transition knowledge and is designed to capture the diverse distribution of normal trajectories. Our experiments show that the proposed method IHiD achieves up to 30.2% improvement in anomaly detection performance in terms of F1 score over state-of-the-art baselines.

[Arxiv](https://arxiv.org/abs/2509.17068)