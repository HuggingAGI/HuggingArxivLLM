# S$^4$C：基于语法与语义连贯性的推测采样，提升大型语言模型推理效率

发布时间：2025年06月16日

`LLM应用` `实时应用`

> S$^4$C: Speculative Sampling with Syntactic and Semantic Coherence for Efficient Inference of Large Language Models

# 摘要

> 大型语言模型（LLMs）在各类下游任务中表现出色，但其自回归特性导致推理延迟，影响了实时应用的性能。为解决这一问题，我们提出了基于句法和语义连贯性的推测采样框架（S$^4$C）。该框架通过多头起草实现快速令牌生成，并借助持续验证树进行高效候选验证和特征重用。实验结果表明，S$^4$C在主流任务中表现优异，不仅提升了效率和并行性，还以更少的计算资源生成了更多有效令牌。在Spec-bench基准测试中，S$^4$C实现了2.26倍至2.60倍的加速比，超越了当前最先进的方法。

> Large language models (LLMs) exhibit remarkable reasoning capabilities across diverse downstream tasks. However, their autoregressive nature leads to substantial inference latency, posing challenges for real-time applications. Speculative sampling mitigates this issue by introducing a drafting phase followed by a parallel validation phase, enabling faster token generation and verification. Existing approaches, however, overlook the inherent coherence in text generation, limiting their efficiency. To address this gap, we propose a Speculative Sampling with Syntactic and Semantic Coherence (S$^4$C) framework, which extends speculative sampling by leveraging multi-head drafting for rapid token generation and a continuous verification tree for efficient candidate validation and feature reuse. Experimental results demonstrate that S$^4$C surpasses baseline methods across mainstream tasks, offering enhanced efficiency, parallelism, and the ability to generate more valid tokens with fewer computational resources. On Spec-bench benchmarks, S$^4$C achieves an acceleration ratio of 2.26x-2.60x, outperforming state-of-the-art methods.

[Arxiv](https://arxiv.org/abs/2506.14158)