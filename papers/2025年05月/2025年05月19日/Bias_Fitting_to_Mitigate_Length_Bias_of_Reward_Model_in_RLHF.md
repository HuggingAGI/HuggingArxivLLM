# 通过偏差拟合缓解强化学习中人类反馈的奖励模型的长度偏差

发布时间：2025年05月19日

`LLM应用` `AI伦理`

> Bias Fitting to Mitigate Length Bias of Reward Model in RLHF

# 摘要

> 强化学习中的人类反馈（Reinforcement Learning from Human Feedback，简称RLHF）依赖奖励模型将大型语言模型与人类偏好对齐。然而，RLHF常面临奖励欺骗问题，即策略学习利用训练好的奖励模型中的缺陷，以最大化奖励分数，却未能真正与人类偏好对齐。一个显著的奖励欺骗例子是长度偏见，即奖励模型通常偏好更长的响应，而不考虑实际响应质量。关于长度偏见的先前工作存在显著限制，这些方法要么在不表征偏见形式的情况下缓解偏见，要么简单地假设长度与奖励之间存在线性关系。为了准确建模长度偏见的复杂本质并促进更有效的偏见缓解，我们提出了FiMi-RM（用于RLHF中奖励模型长度偏见的拟合与缓解框架），一个自主学习和纠正潜在偏见模式的框架。我们的方法分为三个阶段：首先，我们训练一个标准奖励模型，该模型固有包含长度偏见。其次，我们部署一个轻量级拟合模型，以明确捕捉长度与奖励之间的非线性关系。最后，我们将这种学习到的关系整合到奖励模型中以去除偏见。实验结果表明，FiMi-RM实现了更平衡的长度-奖励分布。此外，当应用于对齐算法时，我们的去偏奖励模型提高了长度控制下的胜率，同时减少了冗长性，而没有损害其性能。

> Reinforcement Learning from Human Feedback relies on reward models to align large language models with human preferences. However, RLHF often suffers from reward hacking, wherein policy learning exploits flaws in the trained reward model to maximize reward scores without genuinely aligning with human preferences. A significant example of such reward hacking is length bias, where reward models usually favor longer responses irrespective of actual response quality. Previous works on length bias have notable limitations, these approaches either mitigate bias without characterizing the bias form, or simply assume a linear length-reward relation. To accurately model the intricate nature of length bias and facilitate more effective bias mitigation, we propose FiMi-RM (Bias Fitting to Mitigate Length Bias of Reward Model in RLHF), a framework that autonomously learns and corrects underlying bias patterns. Our approach consists of three stages: First, we train a standard reward model which inherently contains length bias. Next, we deploy a lightweight fitting model to explicitly capture the non-linear relation between length and reward. Finally, we incorporate this learned relation into the reward model to debias. Experimental results demonstrate that FiMi-RM achieves a more balanced length-reward distribution. Furthermore, when applied to alignment algorithms, our debiased reward model improves length-controlled win rate and reduces verbosity without compromising its performance.

[Arxiv](https://arxiv.org/abs/2505.12843)