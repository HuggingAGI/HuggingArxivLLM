# 对齐即分布学习：你的偏好模型实际上就是一个语言模型

发布时间：2025年06月02日

`LLM理论` `人工智能`

> Alignment as Distribution Learning: Your Preference Model is Explicitly a Language Model

# 摘要

> 强化学习从人类反馈（RLHF）已成为控制大型语言模型（LLMs）输出质量的主要方法。然而，标准的RLHF目标从 `损失 + 正则化` 的角度来看，缺乏理论依据，并且容易导致退化和确定性的解决方案，这一问题也被直接策略优化（DPO）等方法所继承。本文中，我们重新思考对齐问题，将其视为基于配对偏好反馈的分布学习，通过显式建模目标语言模型如何通过偏好数据泄露信息。这种建模方式让我们提出了三个基于原则的学习目标：偏好最大似然估计、偏好蒸馏和逆KL最小化。我们从理论上证明，这三种方法都能以强非渐近的O(1/n)收敛速度接近目标语言模型，自然避免了退化和奖励过拟合。最后，我们通过实验证明，我们的分布学习框架，尤其是偏好蒸馏，在各种任务和模型上始终优于或匹配RLHF和DPO的性能。

> Alignment via reinforcement learning from human feedback (RLHF) has become the dominant paradigm for controlling the quality of outputs from large language models (LLMs). However, when viewed as `loss + regularization,' the standard RLHF objective lacks theoretical justification and incentivizes degenerate, deterministic solutions, an issue that variants such as Direct Policy Optimization (DPO) also inherit. In this paper, we rethink alignment by framing it as \emph{distribution learning} from pairwise preference feedback by explicitly modeling how information about the target language model bleeds through the preference data. This explicit modeling leads us to propose three principled learning objectives: preference maximum likelihood estimation, preference distillation, and reverse KL minimization. We theoretically show that all three approaches enjoy strong non-asymptotic $O(1/n)$ convergence to the target language model, naturally avoiding degeneracy and reward overfitting. Finally, we empirically demonstrate that our distribution learning framework, especially preference distillation, consistently outperforms or matches the performances of RLHF and DPO across various tasks and models.

[Arxiv](https://arxiv.org/abs/2506.01523)