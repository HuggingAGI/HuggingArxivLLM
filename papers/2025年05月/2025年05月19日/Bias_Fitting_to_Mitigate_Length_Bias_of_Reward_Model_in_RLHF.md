# 通过偏差拟合解决强化学习中奖励模型的长度偏差问题——一种创新的解决方案

发布时间：2025年05月19日

`LLM应用`

> Bias Fitting to Mitigate Length Bias of Reward Model in RLHF

# 摘要

> 强化学习从人类反馈（RLHF）依赖奖励模型使大型语言模型与人类偏好保持一致，但常遭受“奖励欺骗”问题。其中，“长度偏见”尤为突出，即奖励模型偏好更长的响应，而不考虑质量。现有方法在缓解长度偏见时存在局限，要么无法表征偏见形式，要么假设线性关系。为此，我们提出FiMi-RM框架，通过三步流程自主学习并纠正偏见模式：1）训练标准奖励模型；2）部署轻量级拟合模型捕捉非线性关系；3）整合关系去除偏见。实验表明，FiMi-RM实现了更平衡的长度-奖励分布，提升了对齐算法的性能。

> Reinforcement Learning from Human Feedback relies on reward models to align large language models with human preferences. However, RLHF often suffers from reward hacking, wherein policy learning exploits flaws in the trained reward model to maximize reward scores without genuinely aligning with human preferences. A significant example of such reward hacking is length bias, where reward models usually favor longer responses irrespective of actual response quality. Previous works on length bias have notable limitations, these approaches either mitigate bias without characterizing the bias form, or simply assume a linear length-reward relation. To accurately model the intricate nature of length bias and facilitate more effective bias mitigation, we propose FiMi-RM (Bias Fitting to Mitigate Length Bias of Reward Model in RLHF), a framework that autonomously learns and corrects underlying bias patterns. Our approach consists of three stages: First, we train a standard reward model which inherently contains length bias. Next, we deploy a lightweight fitting model to explicitly capture the non-linear relation between length and reward. Finally, we incorporate this learned relation into the reward model to debias. Experimental results demonstrate that FiMi-RM achieves a more balanced length-reward distribution. Furthermore, when applied to alignment algorithms, our debiased reward model improves length-controlled win rate and reduces verbosity without compromising its performance.

[Arxiv](https://arxiv.org/abs/2505.12843)