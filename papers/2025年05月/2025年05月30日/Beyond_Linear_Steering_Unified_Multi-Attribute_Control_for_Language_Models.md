# 超越线性调控：语言模型的统一多属性控制

发布时间：2025年05月30日

`LLM理论

这篇论文探讨了大型语言模型中行为控制的理论问题，提出了一种新的引导方法K-Steering，属于模型机制的理论研究。因此，它被归类为LLM理论。` `人工智能`

> Beyond Linear Steering: Unified Multi-Attribute Control for Language Models

# 摘要

> 在大型语言模型 (LLMs) 中，推理时控制多个行为属性面临两大挑战：属性间的相互干扰以及线性引导方法的局限性。线性引导方法假设激活空间中的行为可加，并需针对每个属性单独调整。我们提出了一种统一灵活的解决方案——K-Steering。该方法通过在隐藏激活上训练一个非线性多标签分类器，并在推理时利用梯度计算干预方向。这不仅避免了线性假设，还无需存储和调整单独的属性向量，更能在不重新训练的情况下动态组合行为。为验证方法效果，我们推出了两个新基准测试 ToneBank 和 DebateMix，专注于组合行为控制。实验结果表明，K-Steering 在准确引导多个行为方面超越了现有强基线方法。

> Controlling multiple behavioral attributes in large language models (LLMs) at inference time is a challenging problem due to interference between attributes and the limitations of linear steering methods, which assume additive behavior in activation space and require per-attribute tuning. We introduce K-Steering, a unified and flexible approach that trains a single non-linear multi-label classifier on hidden activations and computes intervention directions via gradients at inference time. This avoids linearity assumptions, removes the need for storing and tuning separate attribute vectors, and allows dynamic composition of behaviors without retraining. To evaluate our method, we propose two new benchmarks, ToneBank and DebateMix, targeting compositional behavioral control. Empirical results across 3 model families, validated by both activation-based classifiers and LLM-based judges, demonstrate that K-Steering outperforms strong baselines in accurately steering multiple behaviors.

[Arxiv](https://arxiv.org/abs/2505.24535)