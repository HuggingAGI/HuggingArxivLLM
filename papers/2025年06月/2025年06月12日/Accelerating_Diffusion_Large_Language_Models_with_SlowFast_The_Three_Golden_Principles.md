# 加速扩散式大语言模型：SlowFast方法的三大黄金准则

发布时间：2025年06月12日

`LLM应用` `计算效率`

> Accelerating Diffusion Large Language Models with SlowFast: The Three Golden Principles

# 摘要

> 基于扩散的语言模型（dLLMs）通过实现并行令牌生成和显著降低推理延迟，展现出对传统自回归LLMs的潜在优势。然而，现有的dLLMs采样策略，如基于置信度或半自回归解码，常常受限于静态行为，导致效率低下和灵活性不足。本文提出了一种名为SlowFast Sampling的新型动态采样策略，能够自适应地在探索性解码与加速解码阶段之间切换。我们的方法遵循三大核心原则：确定性原则、收敛性原则和位置性原则，这些原则指导着何时以及何地可以自信且高效地解码令牌。此外，我们还将该策略与dLLM-Cache相结合，以减少冗余计算。在多个基准测试和模型上的广泛实验表明，SlowFast Sampling在LLaDA上实现了高达15.63倍的速度提升，且准确度损失极小；与缓存结合时，速度提升更是达到了34.22倍。值得注意的是，与强大的自回归基线模型如LLaMA3 8B相比，我们的方法在吞吐量上表现更优，证明了精心设计的采样策略能够充分释放dLLMs的潜力，实现快速且高质量的生成。

> Diffusion-based language models (dLLMs) have emerged as a promising alternative to traditional autoregressive LLMs by enabling parallel token generation and significantly reducing inference latency. However, existing sampling strategies for dLLMs, such as confidence-based or semi-autoregressive decoding, often suffer from static behavior, leading to suboptimal efficiency and limited flexibility. In this paper, we propose SlowFast Sampling, a novel dynamic sampling strategy that adaptively alternates between exploratory and accelerated decoding stages. Our method is guided by three golden principles: certainty principle, convergence principle, and positional principle, which govern when and where tokens can be confidently and efficiently decoded. We further integrate our strategy with dLLM-Cache to reduce redundant computation. Extensive experiments across benchmarks and models show that SlowFast Sampling achieves up to 15.63$\times$ speedup on LLaDA with minimal accuracy drop, and up to 34.22$\times$ when combined with caching. Notably, our approach outperforms strong autoregressive baselines like LLaMA3 8B in throughput, demonstrating that well-designed sampling can unlock the full potential of dLLMs for fast and high-quality generation.

[Arxiv](https://arxiv.org/abs/2506.10848)