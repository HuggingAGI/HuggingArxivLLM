# 迈向 RLHF 的奖励公平：从资源分配的视角

发布时间：2025年05月29日

`LLM理论` `人工智能` `社会学`

> Towards Reward Fairness in RLHF: From a Resource Allocation Perspective

# 摘要

> 奖励作为人类偏好的代理，在从人类反馈中进行强化学习（RLHF）中扮演着关键角色。然而，奖励若存在不完美性并带有各种偏见，可能对大型语言模型（LLMs）的对齐产生不利影响。本文将奖励中的偏见问题定义为奖励不公平性问题，并提出了一种与偏见无关的方法，从资源分配的角度解决奖励公平性问题。我们无需针对每种偏见类型进行特定设计，却能有效缓解这些问题。具体来说，我们将偏好学习建模为资源分配问题，将奖励视为待分配的资源，同时考虑其分配过程中效用与公平性之间的权衡。我们提出了公平正则化和公平系数两种方法，以实现奖励公平。在验证和强化学习两种场景中应用我们的方法，分别获得了一个公平奖励模型和一个策略模型。实验结果表明，我们的方法能够以更加公平的方式将LLMs与人类偏好对齐。

> Rewards serve as proxies for human preferences and play a crucial role in Reinforcement Learning from Human Feedback (RLHF). However, if these rewards are inherently imperfect, exhibiting various biases, they can adversely affect the alignment of large language models (LLMs). In this paper, we collectively define the various biases present in rewards as the problem of reward unfairness. We propose a bias-agnostic method to address the issue of reward fairness from a resource allocation perspective, without specifically designing for each type of bias, yet effectively mitigating them. Specifically, we model preference learning as a resource allocation problem, treating rewards as resources to be allocated while considering the trade-off between utility and fairness in their distribution. We propose two methods, Fairness Regularization and Fairness Coefficient, to achieve fairness in rewards. We apply our methods in both verification and reinforcement learning scenarios to obtain a fairness reward model and a policy model, respectively. Experiments conducted in these scenarios demonstrate that our approach aligns LLMs with human preferences in a more fair manner.

[Arxiv](https://arxiv.org/abs/2505.23349)