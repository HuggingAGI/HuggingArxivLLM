# 平滑阅读：长上下文任务中循环LLM与自注意力LLM的性能差距探究

发布时间：2025年07月25日

`LLM理论

LLM理论` `文本处理`

> Smooth Reading: Bridging the Gap of Recurrent LLM to Self-Attention LLM on Long-Context Tasks

# 摘要

> 近期，具有线性计算复杂度的循环型大语言模型（Recurrent LLMs）重新崭露头角，成为自注意力机制大语言模型（Self-Attention LLMs）的高效替代方案。然而，Recurrent LLMs 由于固定容量内存的限制，在处理长上下文任务时往往表现欠佳。以往研究主要通过架构创新来提升其内存容量，但尚未使Recurrent LLMs 在长上下文任务上达到Self-Attention LLMs 的水平。我们认为这一限制源于Recurrent LLMs 一次性处理整个上下文并不合适。在本文中，我们提出了一种受人类阅读策略启发的分块推理方法——Smooth Reading。该方法通过分块处理上下文并逐步总结上下文信息，从而降低内存需求，使其更适用于Recurrent LLMs。实验结果表明，该方法显著缩小了Recurrent和Self-Attention LLMs 在长上下文任务上的性能差距，同时保留了Recurrent LLMs 的效率优势。在LongBench基准测试中，我们的Smooth Reading方法使SWA-3B-4k（一种Recurrent LLM）的性能从比Self-Attention LLMs 低5.68%提升至高3.61%。此外，该方法保持了高效率，在64k上下文长度下，训练速度是Self-Attention LLMs 的3倍，推理速度是其2倍。据我们所知，这是首个在长上下文任务上实现Recurrent LLMs 与Self-Attention LLMs 性能相当的研究。我们希望这一方法能为未来研究提供灵感。为了推动进一步发展，我们将开源代码和数据集。

> Recently, recurrent large language models (Recurrent LLMs) with linear computational complexity have re-emerged as efficient alternatives to self-attention-based LLMs (Self-Attention LLMs), which have quadratic complexity. However, Recurrent LLMs often underperform on long-context tasks due to their limited fixed-size memory. Previous research has primarily focused on enhancing the memory capacity of Recurrent LLMs through architectural innovations, but these approaches have not yet enabled Recurrent LLMs to match the performance of Self-Attention LLMs on long-context tasks. We argue that this limitation arises because processing the entire context at once is not well-suited for Recurrent LLMs. In this paper, we propose Smooth Reading, a chunk-wise inference method inspired by human reading strategies. Smooth Reading processes context in chunks and iteratively summarizes the contextual information, thereby reducing memory demands and making the approach more compatible with Recurrent LLMs. Our experimental results show that this method substantially narrows the performance gap between Recurrent and Self-Attention LLMs on long-context tasks, while preserving the efficiency advantages of Recurrent LLMs. Our Smooth Reading boosts SWA-3B-4k (a Recurrent LLM) from 5.68% lower to 3.61% higher performance than Self-Attention LLMs on LongBench. Besides, our method maintains the high efficiency, training 3x faster and inferring 2x faster at 64k context compared to Self-Attention LLMs. To our knowledge, this is the first work to achieve comparable performance using Recurrent LLMs compared with Self-Attention LLMs on long-context tasks. We hope our method will inspire future research in this area. To facilitate further progress, we will release code and dataset.

[Arxiv](https://arxiv.org/abs/2507.19353)