# R-Stitch: 动态轨迹拼接助力高效推理

发布时间：2025年07月23日

`LLM应用`

> R-Stitch: Dynamic Trajectory Stitching for Efficient Reasoning

# 摘要

> 链式推理（Chain-of-thought，CoT）通过鼓励逐步中间推理，显著提升了大型语言模型的问题解决能力。然而，CoT推理依赖于对长令牌序列的自回归解码，导致了较大的计算开销。现有的加速策略主要分为两类：一类通过早期停止或压缩奖励设计来缩短序列长度，另一类则利用较小模型的推测性解码来提升解码速度。然而，推测性解码在小模型与大模型一致性较低时，加速效果有限，且未能充分发挥小模型在生成简洁中间推理方面的潜力。

针对这一问题，我们提出了R-Stitch——一种基于令牌的、信心驱动的混合解码框架。该框架通过在推理过程中在小语言模型（SLM）和大语言模型（LLM）之间智能切换，显著加速了CoT推理。R-Stitch默认采用SLM生成令牌，仅在SLM的信心水平低于预设阈值时，才会将任务转交给LLM。这种设计巧妙地避免了完整的序列回滚，同时在推理过程中的不确定步骤选择性地调用LLM，从而在保证推理质量的同时，显著提升了效率。

R-Stitch具有广泛的适用性：它支持多种模型架构，无需额外训练，且能够无缝集成到现有的解码流程中。实验结果表明，在数学推理基准测试中，R-Stitch成功将推理延迟降低了高达85%，同时保持了极高的准确率。这一成果充分证明了R-Stitch在加速CoT推理方面的实际应用价值。


> Chain-of-thought (CoT) reasoning enhances the problem-solving capabilities of large language models by encouraging step-by-step intermediate reasoning during inference. While effective, CoT introduces substantial computational overhead due to its reliance on autoregressive decoding over long token sequences. Existing acceleration strategies either reduce sequence length through early stopping or compressive reward designs, or improve decoding speed via speculative decoding with smaller models. However, speculative decoding suffers from limited speedup when the agreement between small and large models is low, and fails to exploit the potential advantages of small models in producing concise intermediate reasoning. In this paper, we present R-Stitch, a token-level, confidence-based hybrid decoding framework that accelerates CoT inference by switching between a small language model (SLM) and a large language model (LLM) along the reasoning trajectory. R-Stitch uses the SLM to generate tokens by default and delegates to the LLM only when the SLM's confidence falls below a threshold. This design avoids full-sequence rollback and selectively invokes the LLM on uncertain steps, preserving both efficiency and answer quality. R-Stitch is model-agnostic, training-free, and compatible with standard decoding pipelines. Experiments on math reasoning benchmarks demonstrate that R-Stitch achieves up to 85\% reduction in inference latency with negligible accuracy drop, highlighting its practical effectiveness in accelerating CoT reasoning.

[Arxiv](https://arxiv.org/abs/2507.17307)