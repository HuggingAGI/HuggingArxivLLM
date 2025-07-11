# SAND：通过自我学习的动作思考机制助力LLM代理的提升

发布时间：2025年07月10日

`Agent` `人工智能` `智能代理`

> SAND: Boosting LLM Agents with Self-Taught Action Deliberation

# 摘要

> 大型语言模型 (LLM) 代理通常通过监督微调 ReAct 风格的专家轨迹或基于成对滚动的偏好优化进行调优。这些方法大多专注于模仿特定的专家行为或推广选定的推理思想和行动。然而，由于有限的动作空间探索，这些方法可能导致 LLM 代理过度承诺看似合理但次优的行动。为了解决这一问题，我们提出了 Self-taught ActioN Deliberation (SAND) 框架，使 LLM 代理能够在承诺前对候选行动进行明确的权衡。为应对大规模动作空间和步骤级动作评估中的权衡时机和内容选择挑战，我们整合了自我一致性动作采样和执行引导的动作批评，以帮助利用 LLM 代理的基础模型合成逐步动作权衡思想。通过迭代方式，权衡轨迹随后用于微调 LLM 代理自身。在两个具有代表性的交互式代理任务上进行评估，SAND 较初始监督微调平均提升了 20%，同时也超越了现有的最优代理调优方法。

> Large Language Model (LLM) agents are commonly tuned with supervised finetuning on ReAct-style expert trajectories or preference optimization over pairwise rollouts. Most of these methods focus on imitating specific expert behaviors or promoting chosen reasoning thoughts and actions over rejected ones. However, without reasoning and comparing over alternatives actions, LLM agents finetuned with these methods may over-commit towards seemingly plausible but suboptimal actions due to limited action space exploration. To address this, in this paper we propose Self-taught ActioN Deliberation (SAND) framework, enabling LLM agents to explicitly deliberate over candidate actions before committing to one. To tackle the challenges of when and what to deliberate given large action space and step-level action evaluation, we incorporate self-consistency action sampling and execution-guided action critique to help synthesize step-wise action deliberation thoughts using the base model of the LLM agent. In an iterative manner, the deliberation trajectories are then used to finetune the LLM agent itself. Evaluating on two representative interactive agent tasks, SAND achieves an average 20% improvement over initial supervised finetuning and also outperforms state-of-the-art agent tuning approaches.

[Arxiv](https://arxiv.org/abs/2507.07441)