# 基于数据影响导向树搜索的高效多智能体系统训练

发布时间：2025年02月02日

`Agent

理由：这篇论文主要讨论了基于蒙特卡洛树搜索（MCTS）的方法在多智能体系统（MAS）中的应用，特别是通过引入影响力分数来优化数据选择过程。论文的核心内容围绕多智能体系统的自我训练能力提升，属于多智能体系统（MAS）的研究范畴，因此应归类为Agent。` `人工智能` `多智能体系统`

> Efficient Multi-Agent System Training with Data Influence-Oriented Tree Search

# 摘要

> 基于蒙特卡洛树搜索（MCTS）的方法为生成合成数据提供了新思路，能够有效提升基于大型语言模型（LLM）的多智能体系统（MAS）的自我训练能力。这些方法通过Q值评估个体智能体的贡献，但仅依赖Q值可能导致数据选择与模型训练目标不一致。为此，我们提出了数据影响力导向的树搜索（DITS），这一创新框架通过引入影响力分数来优化树搜索和数据选择过程。借助影响力分数，我们能够精准识别对系统改进最具价值的数据，从而显著提升模型性能。此外，我们还开发了适用于不可微分指标的影响力分数估计方法，大幅降低了计算开销。在八个多智能体数据集上的实验验证了该方法的鲁棒性和有效性。特别值得一提的是，我们的研究表明，在数据合成过程中，将更多推理资源用于估计影响力分数而非Q值，能够更高效地提升模型训练效果。

> Monte Carlo Tree Search (MCTS) based methods provide promising approaches for generating synthetic data to enhance the self-training of Large Language Model (LLM) based multi-agent systems (MAS). These methods leverage Q-values to estimate individual agent contributions. However, relying solely on Q-values to identify informative data may misalign with the data synthesis objective, as the focus should be on selecting data that best enhances model training. To address this discrepancy, we propose Data Influence-oriented Tree Search (DITS), a novel framework that incorporates influence scores to guide both tree search and data selection. By leveraging influence scores, we effectively identify the most impactful data for system improvement, thereby enhancing model performance. Furthermore, we derive influence score estimation methods tailored for non-differentiable metrics, significantly reducing computational overhead by utilizing inference computations. Extensive experiments on eight multi-agent datasets demonstrate the robustness and effectiveness of the proposed methods. Notably, our findings reveal that allocating more inference resources to estimate influence scores, rather than Q-values, during data synthesis can more effectively and efficiently enhance model training.

[Arxiv](https://arxiv.org/abs/2502.00955)