# # **ParetoHqD**：基于帕累托高质量数据的大型语言模型快速离线多目标对齐方法

发布时间：2025年04月23日

`LLM理论` `人机交互` `人工智能`

> ParetoHqD: Fast Offline Multiobjective Alignment of Large Language Models using Pareto High-quality Data

# 摘要

> 确保大型语言模型与多个人类期望和价值观对齐，是其更好服务于多样化用户需求的关键。为此，基于离线多目标对齐算法（如Rewards-in-Context算法）的性能和效率表现突出。然而，不恰当的偏好表示和奖励分数不平衡的训练限制了这些算法的性能。为此，我们提出了ParetoHqD方法，通过将人类偏好表示为目标空间中的偏好方向，并将Pareto前沿附近的数据显示为“高质量”数据，从而解决了上述问题。对于每个偏好，ParetoHqD遵循一个两阶段的监督微调过程，每个阶段使用一个与偏好方向最佳匹配的个体Pareto高质量训练集。实验结果表明，ParetoHqD在两个多目标对齐任务中优于五个基线方法。

> Aligning large language models with multiple human expectations and values is crucial for ensuring that they adequately serve a variety of user needs. To this end, offline multiobjective alignment algorithms such as the Rewards-in-Context algorithm have shown strong performance and efficiency. However, inappropriate preference representations and training with imbalanced reward scores limit the performance of such algorithms. In this work, we introduce ParetoHqD that addresses the above issues by representing human preferences as preference directions in the objective space and regarding data near the Pareto front as ''high-quality'' data. For each preference, ParetoHqD follows a two-stage supervised fine-tuning process, where each stage uses an individual Pareto high-quality training set that best matches its preference direction. The experimental results have demonstrated the superiority of ParetoHqD over five baselines on two multiobjective alignment tasks.

[Arxiv](https://arxiv.org/abs/2504.16628)