# 大型语言模型中的推理阶段奖励机制操控

发布时间：2025年06月23日

`LLM理论` `人工智能` `算法工程`

> Inference-Time Reward Hacking in Large Language Models

# 摘要

> 提升大型语言模型性能的重要方法之一是优化奖励模型。奖励模型通过为LLM输出赋予数值分数来评估结果质量，例如判断哪些回应更符合用户偏好或安全目标。然而，奖励模型并非完美，它们只能作为正确性、有用性和安全性等复杂目标的代理。过分优化一个欠佳的奖励模型，不仅可能违背预期目标，还可能降低整体性能——这种现象被称为奖励欺骗。本研究深入分析了奖励欺骗在推理时对齐中的表现，并提出通过依赖代理奖励来缓解这一问题。我们重点研究了最佳-of-n（BoN）和软最佳-of-n（SBoN）机制下的欺骗现象，并创新性地提出了最佳-of-Poisson（BoP）方法，它能在推理时高效地近似最优奖励-KL散度策略。我们发现，实践中观察到的奖励先升后降的欺骗模式，实际上是包括BoN和BoP在内的一大类推理机制的必然属性。为了有效应对这一挑战，我们提出了一种对冲策略，避免过度依赖可能误导的高代理奖励信号。为此，我们开发了HedgeTune算法，用于高效寻找最优推理参数并防止奖励欺骗。实验结果表明，通过引入对冲机制，不仅能够有效缓解奖励欺骗问题，还能在极小计算开销下实现更优的失真-奖励权衡。

> A common paradigm to improve the performance of large language models is optimizing for a reward model. Reward models assign a numerical score to LLM outputs indicating, for example, which response would likely be preferred by a user or is most aligned with safety goals. However, reward models are never perfect. They inevitably function as proxies for complex desiderata such as correctness, helpfulness, and safety. By overoptimizing for a misspecified reward, we can subvert intended alignment goals and reduce overall performance -- a phenomenon commonly referred to as reward hacking. In this work, we characterize reward hacking in inference-time alignment and demonstrate when and how we can mitigate it by hedging on the proxy reward. We study this phenomenon under Best-of-$n$ (BoN) and Soft-Best-of-$n$ (SBoN), and we introduce Best-of-Poisson (BoP) that provides an efficient, near-exact approximation of the optimal reward-KL divergence policy at inference time. We show that the characteristic pattern of hacking as observed in practice (where the true reward first increases before declining) is an inevitable property of a broad class of inference-time mechanisms, including BoN and BoP. To counter this effect, hedging offers a tactical choice to avoid placing undue confidence in high but potentially misleading proxy reward signals. We introduce HedgeTune, an efficient algorithm to find the optimal inference-time parameter and avoid reward hacking. We demonstrate through experiments that hedging mitigates reward hacking and achieves superior distortion-reward tradeoffs with minimal computational overhead.

[Arxiv](https://arxiv.org/abs/2506.19248)