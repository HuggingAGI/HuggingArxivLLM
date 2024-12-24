# 借助可微缓存增强实现潜在空间中的审议

发布时间：2024年12月23日

`LLM应用` `语言模型` `推理任务`

> Deliberation in Latent Space via Differentiable Cache Augmentation

# 摘要

> 使大型语言模型（LLMs）能通过生成和关注中间推理步骤来“深入思考”的技术，在解决复杂问题时展现出良好前景。然而，标准方法在做出响应前会立即生成离散的标记序列，这可能导致明显的延迟成本，且优化难度大。在本研究中，我们证实一个冻结的 LLM 能够搭配一个在模型键值（kv）缓存上运行的离线协处理器来增强性能。该协处理器利用一组旨在提升后续解码保真度的潜在嵌入来增强缓存。我们基于标准预训练数据中解码器的语言建模损失来训练此协处理器，同时保持解码器自身不变。这种方式让模型能够以端到端可微的形式学习如何将额外的计算提炼进其 kv 缓存。由于解码器未变，协处理器能够离线和异步操作，若协处理器不可用或给定缓存无需额外计算，语言模型仍能正常运作。实验表明，当缓存得到增强时，解码器在众多后续标记上实现了更低的困惑度。而且，即便没有任何针对特定任务的训练，我们的实验也显示，缓存增强始终能降低困惑度，并在一系列推理密集型任务中提升性能。

> Techniques enabling large language models (LLMs) to "think more" by generating and attending to intermediate reasoning steps have shown promise in solving complex problems. However, the standard approaches generate sequences of discrete tokens immediately before responding, and so they can incur significant latency costs and be challenging to optimize. In this work, we demonstrate that a frozen LLM can be augmented with an offline coprocessor that operates on the model's key-value (kv) cache. This coprocessor augments the cache with a set of latent embeddings designed to improve the fidelity of subsequent decoding. We train this coprocessor using the language modeling loss from the decoder on standard pretraining data, while keeping the decoder itself frozen. This approach enables the model to learn, in an end-to-end differentiable fashion, how to distill additional computation into its kv-cache. Because the decoder remains unchanged, the coprocessor can operate offline and asynchronously, and the language model can function normally if the coprocessor is unavailable or if a given cache is deemed not to require extra computation. We show experimentally that when a cache is augmented, the decoder achieves lower perplexity on numerous subsequent tokens. Furthermore, even without any task-specific training, our experiments demonstrate that cache augmentation consistently reduces perplexity and improves performance across a range of reasoning-intensive tasks.

[Arxiv](https://arxiv.org/abs/2412.17747)