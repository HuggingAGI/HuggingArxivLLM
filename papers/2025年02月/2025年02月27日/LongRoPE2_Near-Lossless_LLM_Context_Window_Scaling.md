# # LongRoPE2: LLM 上下文窗口的近无损缩放

发布时间：2025年02月27日

`LLM理论` `人工智能`

> LongRoPE2: Near-Lossless LLM Context Window Scaling

# 摘要

> LongRoPE2 是一种创新方法，能够将预训练大型语言模型（LLMs）的有效上下文窗口扩展至目标长度，同时保持其在原始较短上下文窗口上的性能。这一方法的核心在于三大贡献：(1) 提出 RoPE 高维空间训练不足是现有方法中持续存在分布外（OOD）问题的根本原因；(2) 提出一种基于“针驱动”困惑度指导的进化搜索的 RoPE 重缩放算法，有效解决了训练不足的问题；(3) 采用混合上下文窗口训练方法，通过对模型权重进行微调，使其能够使用重缩放后的 RoPE 处理长上下文序列，同时保留原始 RoPE 在短上下文上的性能。在 LLaMA3-8B 和 Phi3-mini-3.8B 模型上进行的跨多种基准测试的广泛实验验证了这一假设，并证明了 LongRoPE2 的有效性。值得注意的是，LongRoPE2 仅使用 10B 个令牌（比 Meta 的方法少 80 倍），就成功将 LLaMA3-8B 的有效上下文长度扩展至 128K，同时保留了超过 98.5% 的短上下文性能，而 Meta 的方法未能达到目标有效上下文长度。代码将在 https://github.com/microsoft/LongRoPE 上提供。

> LongRoPE2 is a novel approach that extends the effective context window of pre-trained large language models (LLMs) to the target length, while preserving the performance on the original shorter context window. This is achieved by three contributions: (1) a hypothesis that insufficient training in higher RoPE dimensions contributes to the persistent out-of-distribution (OOD) issues observed in existing methods; (2) an effective RoPE rescaling algorithm that adopts evolutionary search guided by "needle-driven" perplexity to address the insufficient training problem; (3) a mixed context window training approach that fine-tunes model weights to adopt rescaled RoPE for long-context sequences while preserving the short-context performance with the original RoPE. Extensive experiments on LLaMA3-8B and Phi3-mini-3.8B across various benchmarks validate the hypothesis and demonstrate the effectiveness of LongRoPE2. Remarkably, LongRoPE2 extends LLaMA3-8B to achieve a 128K effective context length while retaining over 98.5% of short-context performance, using only 10B tokens -- 80x fewer than Meta's approach, which fails to reach the target effective context length. Code will be available at https://github.com/microsoft/LongRoPE.

[Arxiv](https://arxiv.org/abs/2502.20082)