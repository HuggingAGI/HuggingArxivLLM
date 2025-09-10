# 散度的选择：可验证奖励强化学习中缓解多样性崩溃的被忽视关键因素

发布时间：2025年09月09日

`强化学习` `基础理论`

> The Choice of Divergence: A Neglected Key to Mitigating Diversity Collapse in Reinforcement Learning with Verifiable Reward

# 摘要

> 在利用带可验证奖励的强化学习（RLVR）微调大型语言模型（LLMs）时，存在一个核心悖论：尽管单尝试准确率（Pass@1）有所提高，但多尝试性能（Pass@k）却常常下降。这种现象常伴随灾难性遗忘——模型会丢失已习得的技能。尽管已有多种方法被提出，但作为一种主动解决方案，散度项的选择与作用却意外地未被深入探讨。我们认为，标准RLVR目标（无论是采用寻求模态的反向KL散度的目标，还是完全不使用散度项的目标）都缺少知识保留的关键机制。反向KL散度会通过收窄策略主动加剧这种衰减，而不使用散度项则无法防止模型偏离其多样化的知识基础。我们提出一种根本性的视角转变：将散度项本身作为解决方案。我们的框架——保多样性混合强化学习（DPH-RL）——利用质量覆盖f散度（如前向KL散度和JS散度）来充当排练机制。该方法通过持续参考初始策略，迫使模型保持广泛的解决方案覆盖范围。在数学和SQL生成任务上的大量实验表明，DPH-RL不仅解决了Pass@k下降的问题，还在域内和域外同时提升了Pass@1和Pass@k性能。此外，DPH-RL的训练效率更高，因为它利用生成器函数计算f散度，只需从初始策略采样，无需在线参考模型。我们的研究强调了一个被忽视但对改进RLVR至关重要的方向，证明正确选择散度度量是构建更通用、更多样化推理模型的有力工具。

> A central paradox in fine-tuning Large Language Models (LLMs) with Reinforcement Learning with Verifiable Reward (RLVR) is the frequent degradation of multi-attempt performance (Pass@k) despite improvements in single-attempt accuracy (Pass@1). This is often accompanied by catastrophic forgetting, where models lose previously acquired skills. While various methods have been proposed, the choice and function of the divergence term have been surprisingly unexamined as a proactive solution. We argue that standard RLVR objectives -- both those using the mode-seeking reverse KL-divergence and those forgoing a divergence term entirely -- lack a crucial mechanism for knowledge retention. The reverse-KL actively accelerates this decay by narrowing the policy, while its absence provides no safeguard against the model drifting from its diverse knowledge base. We propose a fundamental shift in perspective: using the divergence term itself as the solution. Our framework, Diversity-Preserving Hybrid RL (DPH-RL), leverages mass-covering f-divergences (like forward-KL and JS-divergence) to function as a rehearsal mechanism. By continuously referencing the initial policy, this approach forces the model to maintain broad solution coverage. Extensive experiments on math and SQL generation demonstrate that DPH-RL not only resolves the Pass@k degradation but improves both Pass@1 and Pass@k in- and out-of-domain. Additionally, DPH-RL is more training-efficient because it computes f-divergence using generator functions, requiring only sampling from the initial policy and no online reference model. Our work highlights a crucial, overlooked axis for improving RLVR, demonstrating that the proper selection of a divergence measure is a powerful tool for building more general and diverse reasoning models.

[Arxiv](https://arxiv.org/abs/2509.07430)