# 通过强化学习为联邦脑肿瘤分割挑选合作伙伴

发布时间：2024年12月28日

`其他` `联邦学习`

> Election of Collaborators via Reinforcement Learning for Federated Brain Tumor Segmentation

# 摘要

> 联邦学习（FL）能在保障数据隐私的前提下，于分散的数据集中开展协作式模型训练。但在动态的 FL 环境里，如何最优地挑选参与协作的伙伴仍困难重重。我们推出了 RL-HSimAgg，这是一种创新的强化学习（RL）与采用调和均值的相似性加权聚合（simAgg）算法，用于处置异常数据点。本文建议运用多臂老虎机算法来优化协作伙伴的选择以及模型的泛化能力。通过平衡探索与利用之间的关系，这些 RL 方法能够推动不同数据集下的资源高效训练。我们证实了 Epsilon-greedy（EG）和上置信界（UCB）算法在联邦脑损伤分割中的成效。在针对内部和外部验证集的模拟实验中，带有 UCB 协作伙伴的 RL-HSimAgg 在所有指标上都胜过 EG 方法，在增强肿瘤（0.7334 对比 0.6797）、肿瘤核心（0.7432 对比 0.6821）和整个肿瘤（0.8252 对比 0.7931）分割方面斩获了更高的 Dice 分数。所以，针对联邦肿瘤分割挑战（FeTS 2024），我们将 UCB 视为多模态 MRI 联邦胶质母细胞瘤病变分割中的主要客户端选择方式。总之，我们的研究表明，基于 RL 的协作伙伴管理，比如使用 UCB，有潜力在分布式学习环境中增强模型的稳健性和灵活性，特别是在脑肿瘤分割这类领域。

> Federated learning (FL) enables collaborative model training across decentralized datasets while preserving data privacy. However, optimally selecting participating collaborators in dynamic FL environments remains challenging. We present RL-HSimAgg, a novel reinforcement learning (RL) and similarity-weighted aggregation (simAgg) algorithm using harmonic mean to manage outlier data points. This paper proposes applying multi-armed bandit algorithms to improve collaborator selection and model generalization. By balancing exploration-exploitation trade-offs, these RL methods can promote resource-efficient training with diverse datasets. We demonstrate the effectiveness of Epsilon-greedy (EG) and upper confidence bound (UCB) algorithms for federated brain lesion segmentation. In simulation experiments on internal and external validation sets, RL-HSimAgg with UCB collaborator outperformed the EG method across all metrics, achieving higher Dice scores for Enhancing Tumor (0.7334 vs 0.6797), Tumor Core (0.7432 vs 0.6821), and Whole Tumor (0.8252 vs 0.7931) segmentation. Therefore, for the Federated Tumor Segmentation Challenge (FeTS 2024), we consider UCB as our primary client selection approach in federated Glioblastoma lesion segmentation of multi-modal MRIs. In conclusion, our research demonstrates that RL-based collaborator management, e.g. using UCB, can potentially improve model robustness and flexibility in distributed learning environments, particularly in domains like brain tumor segmentation.

[Arxiv](https://arxiv.org/abs/2412.20253)