# 深入分析专家失败案例，优化LLM代理调优效果

发布时间：2025年04月17日

`Agent` `智能体` `机器学习`

> Exploring Expert Failures Improves LLM Agent Tuning

# 摘要

> 大型语言模型（LLMs）在作为智能体方面展现了巨大潜力，尤其擅长需要多轮推理和交互的任务。拒绝采样微调（RFT）是训练LLMs成为智能体的有效方法：它首先模仿专家生成的成功轨迹，再通过迭代微调成功自生成轨迹进一步提升智能体技能。然而，由于专家（如GPT-4）主要在简单子任务上成功，且RFT本质上偏好简单场景，许多复杂子任务仍悬而未决并持续处于分布外（OOD）。通过研究这些难题，我们发现失败的专家轨迹常蕴含宝贵指导，例如计划和关键行动，这些指导能显著提升智能体的探索效率和关键技能获取。受此启发，我们提出探索专家失败（EEF），从失败专家轨迹中提取有益动作并整合到训练数据中。潜在有害动作会被严格排除，以防止污染模型学习过程。通过利用专家失败中的有益动作，EEF成功攻克了一些此前无法解决的子任务，并显著提升了智能体微调性能。值得注意的是，我们的方法在WebShop中取得了62%的胜率，超越了RFT（53.6%）和GPT-4（35.6%），据我们所知，这是首个在WebShop中突破0.81分并在SciWorld中超过81分的方法，树立了新的研究前沿。

> Large Language Models (LLMs) have shown tremendous potential as agents, excelling at tasks that require multiple rounds of reasoning and interactions. Rejection Sampling Fine-Tuning (RFT) has emerged as an effective method for finetuning LLMs as agents: it first imitates expert-generated successful trajectories and further improves agentic skills through iterative fine-tuning on successful, self-generated trajectories. However, since the expert (e.g., GPT-4) succeeds primarily on simpler subtasks and RFT inherently favors simpler scenarios, many complex subtasks remain unsolved and persistently out-of-distribution (OOD). Upon investigating these challenging subtasks, we discovered that previously failed expert trajectories can often provide valuable guidance, e.g., plans and key actions, that can significantly improve agent exploration efficiency and acquisition of critical skills. Motivated by these observations, we propose Exploring Expert Failures (EEF), which identifies beneficial actions from failed expert trajectories and integrates them into the training dataset. Potentially harmful actions are meticulously excluded to prevent contamination of the model learning process. By leveraging the beneficial actions in expert failures, EEF successfully solves some previously unsolvable subtasks and improves agent tuning performance. Remarkably, our approach achieved a 62\% win rate in WebShop, outperforming RFT (53. 6\%) and GPT-4 (35. 6\%), and to the best of our knowledge, setting a new state-of-the-art as the first method to surpass a score of 0.81 in WebShop and exceed 81 in SciWorld.

[Arxiv](https://arxiv.org/abs/2504.13145)