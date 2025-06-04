# 突破二次复杂度限制：非注意力机制的大型语言模型，专为超长上下文范围设计

发布时间：2025年05月08日

`LLM理论` `长序列处理`

> Breaking Quadratic Barriers: A Non-Attention LLM for Ultra-Long Context Horizons

# 摘要

> 我们提出了一种创新的非注意力机制大型语言模型架构，能够高效处理超长上下文窗口（数万到数百万个令牌）。与传统基于自注意力的Transformer架构不同，我们的模型完全避免了令牌间的注意力计算，从而有效解决了二次内存和计算过载问题。该模型通过四个互补组件实现：受S4启发的状态空间块，用于学习连续时间卷积核并在序列长度上近线性扩展；多分辨率卷积层，用于在不同扩张级别捕获局部上下文；轻量级循环监督模块，用于在序列块间维护全局隐藏状态；以及增强的检索式外部存储，用于存储和检索高层次的块嵌入，同时避免二次操作的重新引入。这一设计不仅提高了模型的效率，还显著提升了处理长序列任务的能力。

> We present a novel non attention based architecture for large language models (LLMs) that efficiently handles very long context windows, on the order of hundreds of thousands to potentially millions of tokens. Unlike traditional Transformer designs, which suffer from quadratic memory and computation overload due to the nature of the self attention mechanism, our model avoids token to token attention entirely. Instead, it combines the following complementary components: State Space blocks (inspired by S4) that learn continuous time convolution kernels and scale near linearly with sequence length, Multi Resolution Convolution layers that capture local context at different dilation levels, a lightweight Recurrent Supervisor to maintain a global hidden state across sequential chunks, and Retrieval Augmented External Memory that stores and retrieves high-level chunk embeddings without reintroducing quadratic operations.

[Arxiv](https://arxiv.org/abs/2506.01963)