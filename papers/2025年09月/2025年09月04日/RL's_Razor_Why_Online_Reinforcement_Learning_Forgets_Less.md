# 强化学习的剃刀：为何在线强化学习更少遗忘

发布时间：2025年09月04日

`强化学习` `基础理论`

> RL's Razor: Why Online Reinforcement Learning Forgets Less

# 摘要

> 比较强化学习（RL）与监督微调（SFT）的微调模型后发现，尽管两者在新任务上表现相近，但RL对先验知识和能力的保留效果显著更优。我们发现遗忘程度取决于分布偏移，其可通过新任务上微调策略与基础策略的KL散度来量化。分析显示，在众多新任务解决方案中，在线策略RL会隐式倾向于KL最小化的方案，而SFT则可能收敛到与基础模型差异极大的分布。我们通过大型语言模型和机器人基础模型的实验验证了上述发现，并从理论上解释了为何在线策略RL更新会带来更小的KL变化。我们将这一原理命名为【数学公式】：在所有新任务解决方案中，RL更偏好与原始模型KL距离最近的方法。

> Comparison of fine-tuning models with reinforcement learning (RL) and supervised fine-tuning (SFT) reveals that, despite similar performance at a new task, RL preserves prior knowledge and capabilities significantly better. We find that the degree of forgetting is determined by the distributional shift, measured as the KL-divergence between the fine-tuned and base policy evaluated on the new task. Our analysis reveals that on-policy RL is implicitly biased towards KL-minimal solutions among the many that solve the new task, whereas SFT can converge to distributions arbitrarily far from the base model. We validate these findings through experiments with large language models and robotic foundation models and further provide theoretical justification for why on-policy RL updates lead to a smaller KL change. We term this principle $\textit{RL's Razor}$: among all ways to solve a new task, RL prefers those closest in KL to the original model.

[Arxiv](https://arxiv.org/abs/2509.04259)