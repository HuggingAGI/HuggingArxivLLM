# 宽进窄出：可撤销解码助力高效有效DLLMs

发布时间：2025年07月24日

`LLM理论`

> Wide-In, Narrow-Out: Revokable Decoding for Efficient and Effective DLLMs

# 摘要

> 扩散式大语言模型（DLLMs）作为一种极具吸引力的替代方案出现，旨在实现快速并行生成，与自回归模型形成对比。然而，现有的DLLMs面临着严重的质量与速度之间的权衡问题，即更快的并行解码会导致性能显著下降。我们将其归因于DLLMs标准解码过程的不可逆性，这种不可逆性容易导致解码方向偏移错误，并且早期错误上下文的积累加剧了这一问题。

为了解决这一问题，我们引入了Wide-In, Narrow-Out (WINO)，这是一种无需训练的解码算法，能够在DLLMs中实现可撤销的解码过程。WINO采用了一种并行的草稿与验证机制，同时积极生成多个令牌，同时利用模型的双向上下文来验证和重新屏蔽可疑的令牌以进行改进。

在LLaDA和MMaDA等开源DLLMs中进行了验证，结果表明WINO能够显著改善质量与速度之间的权衡。例如，在GSM8K数学基准测试中，它将推理速度提高了6【数学公式】倍，同时将准确率提高了2.58%；在Flickr30K图像描述生成任务中，它实现了10【数学公式】倍的速度提升，同时保持了更高的性能。我们还进行了更全面的实验，以展示WINO的优越性，并深入理解其工作原理。

> Diffusion Large Language Models (DLLMs) have emerged as a compelling alternative to Autoregressive models, designed for fast parallel generation. However, existing DLLMs are plagued by a severe quality-speed trade-off, where faster parallel decoding leads to significant performance degradation. We attribute this to the irreversibility of standard decoding in DLLMs, which is easily polarized into the wrong decoding direction along with early error context accumulation. To resolve this, we introduce Wide-In, Narrow-Out (WINO), a training-free decoding algorithm that enables revokable decoding in DLLMs. WINO employs a parallel draft-and-verify mechanism, aggressively drafting multiple tokens while simultaneously using the model's bidirectional context to verify and re-mask suspicious ones for refinement. Verified in open-source DLLMs like LLaDA and MMaDA, WINO is shown to decisively improve the quality-speed trade-off. For instance, on the GSM8K math benchmark, it accelerates inference by 6$\times$ while improving accuracy by 2.58%; on Flickr30K captioning, it achieves a 10$\times$ speedup with higher performance. More comprehensive experiments are conducted to demonstrate the superiority and provide an in-depth understanding of WINO.

[Arxiv](https://arxiv.org/abs/2507.18578)