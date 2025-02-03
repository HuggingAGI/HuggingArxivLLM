# SETS: 通过自我验证与自我纠正提升测试扩展能力

发布时间：2025年01月31日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）的自我验证和自我纠正能力来提升复杂推理任务的性能。具体来说，论文提出了一种名为“自我增强测试时扩展（SETS）”的方法，该方法通过整合采样、自我验证和自我纠正来优化测试时计算。这些内容直接涉及LLM在实际应用中的性能提升和优化，因此应归类为“LLM应用”。` `人工智能`

> SETS: Leveraging Self-Verification and Self-Correction for Improved Test-Time Scaling

# 摘要

> # 摘要
最近大型语言模型（LLMs）的突破性进展为通过测试时计算提升复杂推理任务性能开辟了新途径。然而，传统方法如多数投票的重复采样或奖励模型评分，随着测试时计算规模的扩大，往往面临收益递减的问题，且需要昂贵的任务特定奖励模型训练。本文提出了一种新颖的方法——自我增强测试时扩展（SETS），它利用先进LLMs的自我验证和自我纠正能力，克服了这些限制。SETS将采样、自我验证和自我纠正整合到一个统一框架中，实现了高效且可扩展的测试时计算，从而提升了复杂任务的能力。通过在多个具有挑战性的规划和推理基准上的实验，我们证明了SETS在性能提升和测试时扩展规律方面均优于其他方法。

> Recent advancements in Large Language Models (LLMs) have created new opportunities to enhance performance on complex reasoning tasks by leveraging test-time computation. However, conventional approaches such as repeated sampling with majority voting or reward model scoring, often face diminishing returns as test-time compute scales, in addition to requiring costly task-specific reward model training. In this paper, we present Self-Enhanced Test-Time Scaling (SETS), a novel method that leverages the self-verification and self-correction capabilities of recent advanced LLMs to overcome these limitations. SETS integrates sampling, self-verification, and self-correction into a unified framework, enabling efficient and scalable test-time computation for improved capabilities at complex tasks. Through extensive experiments on challenging planning and reasoning benchmarks, compared to the alternatives, we demonstrate that SETS achieves significant performance improvements and more favorable test-time scaling laws.

[Arxiv](https://arxiv.org/abs/2501.19306)