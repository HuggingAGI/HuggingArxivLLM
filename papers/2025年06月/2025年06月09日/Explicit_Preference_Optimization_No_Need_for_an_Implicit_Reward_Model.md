# 显式偏好优化：告别隐式奖励模型

发布时间：2025年06月09日

`LLM理论` `机器学习`

> Explicit Preference Optimization: No Need for an Implicit Reward Model

# 摘要

> 大型语言模型 (LLMs) 的生成响应通常通过基于人类反馈的强化学习 (RLHF) 微调以符合人类偏好。由于 RLHF 需要先独立训练奖励模型，再将其应用于 LLM 策略更新，这一过程具有挑战性。因此，研究者致力于寻找更直接的方法。直接偏好优化 (DPO) 及其衍生方法绕过了独立训练奖励模型的步骤，通过巧妙使用诱导 	extit{隐式} 奖励的重新参数化技巧，将学习过程整合为最小化单一损失函数。然而，尽管 DPO 在某些实际场景中表现优异，我们发现其仍存在次优正则化和违反直觉的插值行为，这些现象源于其基础重新参数化方法的未被充分重视的副作用。为此，我们提出了一个名为 EXPO 的 	extit{显式} 偏好优化框架，无需重新参数化即可实现隐式奖励。与 DPO 不同，我们从头提出了一些直观上具有吸引力的正则化因子，这些因子透明地避免了 DPO 变体的潜在陷阱，并且能够证明满足先前方法无法达到的正则化需求。实证结果支持了我们的分析，并展示了 EXPO 的有效性。

> The generated responses of large language models (LLMs) are often fine-tuned to human preferences through a process called reinforcement learning from human feedback (RLHF). As RLHF relies on a challenging training sequence, whereby a separate reward model is independently learned and then later applied to LLM policy updates, ongoing research effort has targeted more straightforward alternatives. In this regard, direct preference optimization (DPO) and its many offshoots circumvent the need for a separate reward training step. Instead, through the judicious use of a reparameterization trick that induces an \textit{implicit} reward, DPO and related methods consolidate learning to the minimization of a single loss function. And yet despite demonstrable success in some real-world settings, we prove that DPO-based objectives are nonetheless subject to sub-optimal regularization and counter-intuitive interpolation behaviors, underappreciated artifacts of the reparameterizations upon which they are based. To this end, we introduce an \textit{explicit} preference optimization framework termed EXPO that requires no analogous reparameterization to achieve an implicit reward. Quite differently, we merely posit intuitively-appealing regularization factors from scratch that transparently avoid the potential pitfalls of key DPO variants, provably satisfying regularization desiderata that prior methods do not. Empirical results serve to corroborate our analyses and showcase the efficacy of EXPO.

[Arxiv](https://arxiv.org/abs/2506.07492)