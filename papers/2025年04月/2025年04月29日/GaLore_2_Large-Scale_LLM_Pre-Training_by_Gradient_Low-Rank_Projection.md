# **基于梯度低秩投影的大规模LLM预训练方法——GaLore 2**

发布时间：2025年04月29日

`LLM理论` `人工智能` `计算机科学`

> GaLore 2: Large-Scale LLM Pre-Training by Gradient Low-Rank Projection

# 摘要

> 大型语言模型（LLMs）彻底改变了自然语言理解和生成领域，但在训练过程中面临显著的内存瓶颈。GaLore（梯度低秩投影）通过利用权重梯度的内在低秩结构，解决了这一问题，实现了内存占用的大幅减少，同时保持了性能不减。最近的研究进一步从多个方面扩展了GaLore，包括低比特量化和高阶张量结构。然而，GaLore仍面临一些挑战，例如子空间更新中SVD计算的额外开销，以及与最先进的训练并行化策略（如FSDP）的整合问题。本文中，我们提出了GaLore 2，这是一个高效且可扩展的GaLore框架，旨在解决这些挑战并整合最新进展。此外，我们通过使用高达5000亿个训练令牌从头开始预训练Llama 7B，展示了GaLore 2的可扩展性，突显了其在真实LLM预训练场景中的潜在影响。

> Large language models (LLMs) have revolutionized natural language understanding and generation but face significant memory bottlenecks during training. GaLore, Gradient Low-Rank Projection, addresses this issue by leveraging the inherent low-rank structure of weight gradients, enabling substantial memory savings without sacrificing performance. Recent works further extend GaLore from various aspects, including low-bit quantization and higher-order tensor structures. However, there are several remaining challenges for GaLore, such as the computational overhead of SVD for subspace updates and the integration with state-of-the-art training parallelization strategies (e.g., FSDP). In this paper, we present GaLore 2, an efficient and scalable GaLore framework that addresses these challenges and incorporates recent advancements. In addition, we demonstrate the scalability of GaLore 2 by pre-training Llama 7B from scratch using up to 500 billion training tokens, highlighting its potential impact on real LLM pre-training scenarios.

[Arxiv](https://arxiv.org/abs/2504.20437)