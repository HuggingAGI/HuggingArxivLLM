# 性能提升的海市蜃楼：对比解码为何无法应对多模态幻觉问题

发布时间：2025年04月14日

`LLM应用` `多模态`

> The Mirage of Performance Gains: Why Contrastive Decoding Fails to Address Multimodal Hallucination

# 摘要

> 对比解码策略常用于减少多模态大语言模型中的幻觉现象，但本文揭示这些方法的实际效果并不理想。在 POPE 基准测试中，性能提升主要源于两个误导性因素：一是对模型输出分布的简单调整，二是自适应合理性约束导致的采样策略简化。通过引入一系列看似改进的方法与对比解码技术进行对比，实验结果表明，对比解码的所谓提升与其缓解幻觉的目标无关。这一发现挑战了人们对对比解码策略有效性的常规认知，为开发真正有效的 MLLMs 幻觉解决方案提供了新方向。

> Contrastive decoding strategies are widely used to reduce hallucinations in multimodal large language models (MLLMs). These methods work by constructing contrastive samples to induce hallucinations and then suppressing them in the output distribution. However, this paper demonstrates that such approaches fail to effectively mitigate the hallucination problem. The performance improvements observed on POPE Benchmark are largely driven by two misleading factors: (1) crude, unidirectional adjustments to the model's output distribution and (2) the adaptive plausibility constraint, which reduces the sampling strategy to greedy search. To further illustrate these issues, we introduce a series of spurious improvement methods and evaluate their performance against contrastive decoding techniques. Experimental results reveal that the observed performance gains in contrastive decoding are entirely unrelated to its intended goal of mitigating hallucinations. Our findings challenge common assumptions about the effectiveness of contrastive decoding strategies and pave the way for developing genuinely effective solutions to hallucinations in MLLMs.

[Arxiv](https://arxiv.org/abs/2504.10020)