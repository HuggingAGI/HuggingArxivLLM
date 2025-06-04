# 突破二次计算瓶颈：面向超长上下文的非注意力架构大型语言模型

发布时间：2025年05月08日

`LLM理论

摘要中提到的论文专注于大型语言模型（LLMs）的架构创新，提出了一种非注意力机制，替代传统的自注意力机制，以提高处理长上下文的能力。这属于模型理论层面的研究。` `人工智能`

> Breaking Quadratic Barriers: A Non-Attention LLM for Ultra-Long Context Horizons

# 摘要

> 我们提出了一种全新的非注意力机制的大型语言模型（LLMs）架构，能够高效处理超长上下文窗口，处理范围在数十万到数百万个标记之间。与传统的Transformer架构不同，传统设计由于自注意力机制的特性会带来二次方的内存和计算负载，而我们的模型完全避免了标记间的注意力机制。相反，它结合了以下互补组件：受S4启发的状态空间块（State Space blocks），用于学习连续时间卷积核，并且其规模随序列长度近似线性增长；多分辨率卷积层（Multi Resolution Convolution layers），用于捕捉不同扩张级别下的局部上下文；一个轻量级循环监督器（Recurrent Supervisor），用于在顺序块间维护全局隐藏状态；以及检索增强的外部记忆（Retrieval Augmented External Memory），用于存储和检索高级块嵌入，而不会重新引入二次方操作。

> We present a novel non attention based architecture for large language models (LLMs) that efficiently handles very long context windows, on the order of hundreds of thousands to potentially millions of tokens. Unlike traditional Transformer designs, which suffer from quadratic memory and computation overload due to the nature of the self attention mechanism, our model avoids token to token attention entirely. Instead, it combines the following complementary components: State Space blocks (inspired by S4) that learn continuous time convolution kernels and scale near linearly with sequence length, Multi Resolution Convolution layers that capture local context at different dilation levels, a lightweight Recurrent Supervisor to maintain a global hidden state across sequential chunks, and Retrieval Augmented External Memory that stores and retrieves high-level chunk embeddings without reintroducing quadratic operations.

[Arxiv](https://arxiv.org/abs/2506.01963)