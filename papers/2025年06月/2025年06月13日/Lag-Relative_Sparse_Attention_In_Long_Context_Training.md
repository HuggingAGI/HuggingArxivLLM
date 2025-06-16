# 长上下文训练中的相对稀疏注意力机制

发布时间：2025年06月13日

`LLM理论`

> Lag-Relative Sparse Attention In Long Context Training

# 摘要

> 大型语言模型（LLMs）在自然语言处理和生成领域取得了显著进展，但其处理长上下文输入的能力仍受限于注意力计算的二次复杂度和线性增加的键值内存占用。为了降低计算成本和内存消耗，通常在推理时应用键值缓存压缩技术，但这往往导致性能严重下降，因为模型并未经过压缩上下文的训练。尽管存在更复杂的压缩方法，但由于与基于梯度的优化不兼容或计算开销过高，它们通常不适合用于模型微调。为了填补这一空白，我们提出了一种无需额外参数且计算开销极低的Lag-Relative Sparse Attention（LRSA），该方法基于LagKV压缩方法，专为长上下文微调设计。我们的方法采用分块预填策略，在固定大小的滞后窗口中选择前K个最相关的键值对，使模型能够关注突出的历史上下文同时保持高效。实验结果表明，我们的方法显著提升了LLM在键值压缩下的鲁棒性，并在问答微调任务中取得了更好的微调效果。

> Large Language Models (LLMs) have made significant strides in natural language processing and generation, yet their ability to handle long-context input remains constrained by the quadratic complexity of attention computation and linear-increasing key-value memory footprint. To reduce computational costs and memory, key-value cache compression techniques are commonly applied at inference time, but this often leads to severe performance degradation, as models are not trained to handle compressed context. Although there are more sophisticated compression methods, they are typically unsuitable for post-training because of their incompatibility with gradient-based optimization or high computation overhead. To fill this gap with no additional parameter and little computation overhead, we propose Lag-Relative Sparse Attention(LRSA) anchored by the LagKV compression method for long context post-training. Our method performs chunk-by-chunk prefilling, which selects the top K most relevant key-value pairs in a fixed-size lagging window, allowing the model to focus on salient historical context while maintaining efficiency. Experimental results show that our approach significantly enhances the robustness of the LLM with key-value compression and achieves better fine-tuned results in the question-answer tuning task.

[Arxiv](https://arxiv.org/abs/2506.11498)