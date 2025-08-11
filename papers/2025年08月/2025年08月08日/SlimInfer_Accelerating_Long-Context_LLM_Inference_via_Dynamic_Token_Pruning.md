# SlimInfer：利用动态标记剪枝加速长上下文 LLM 推理过程

发布时间：2025年08月08日

`LLM应用

理由：这篇论文主要讨论了大型语言模型（LLMs）在长上下文推理中的计算效率问题，并提出了一种名为SlimInfer的框架来优化推理过程。论文的重点在于通过剪枝不重要的提示词来提高LLMs的推理速度和效率，同时保持其性能。这属于对大型语言模型的实际应用和优化，因此归类为“LLM应用”。` `人工智能` `推理加速`

> SlimInfer: Accelerating Long-Context LLM Inference via Dynamic Token Pruning

# 摘要

> 大型语言模型（LLMs）的长上下文推理因高计算需求而受到限制。现有方法虽然优化了注意力计算，但仍然处理每一层完整的隐藏状态，导致效率受限。我们提出了SlimInfer框架，通过在推理过程中直接剪枝不重要的提示词来加速推理。我们的关键发现是：关键提示词的信息在各层传播时会扩散到整个序列，这表明即使在隐藏状态中剪枝掉大量提示词（包括关键提示词），LLMs仍能保持语义完整性。SlimInfer引入了动态细粒度剪枝机制，可准确移除中间层的冗余提示词。这种分层剪枝支持了一个无需复杂预测器的异步KV缓存管理器，通过预取所需提示块来降低内存和I/O成本。实验表明，SlimInfer在单个RTX 4090上可使LLaMA3.1-8B-Instruct的首次令牌响应时间（TTFT）提升高达【数学公式】倍，端到端延迟减少【数学公式】倍，同时在LongBench上保持性能。我们的代码将在接收后发布。

> Long-context inference for Large Language Models (LLMs) is heavily limited by high computational demands. While several existing methods optimize attention computation, they still process the full set of hidden states at each layer, limiting overall efficiency. In this work, we propose SlimInfer, an innovative framework that aims to accelerate inference by directly pruning less critical prompt tokens during the forward pass. Our key insight is an information diffusion phenomenon: As information from critical tokens propagates through layers, it becomes distributed across the entire sequence. This diffusion process suggests that LLMs can maintain their semantic integrity when excessive tokens, even including these critical ones, are pruned in hidden states. Motivated by this, SlimInfer introduces a dynamic fine-grained pruning mechanism that accurately removes redundant tokens of hidden state at intermediate layers. This layer-wise pruning naturally enables an asynchronous KV cache manager that prefetches required token blocks without complex predictors, reducing both memory usage and I/O costs. Extensive experiments show that SlimInfer can achieve up to $\mathbf{2.53\times}$ time-to-first-token (TTFT) speedup and $\mathbf{1.88\times}$ end-to-end latency reduction for LLaMA3.1-8B-Instruct on a single RTX 4090, without sacrificing performance on LongBench. Our code will be released upon acceptance.

[Arxiv](https://arxiv.org/abs/2508.06447)