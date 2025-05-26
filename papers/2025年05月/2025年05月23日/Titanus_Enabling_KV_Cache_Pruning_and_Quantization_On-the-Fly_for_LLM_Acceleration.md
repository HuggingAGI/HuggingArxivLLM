# # 摘要  
    最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年05月23日

`LLM应用` `人工智能` `硬件加速`

> Titanus: Enabling KV Cache Pruning and Quantization On-the-Fly for LLM Acceleration

# 摘要

> 大型语言模型（LLMs）在多个领域取得了巨大成功。现有的系统通过在注意力块中缓存键值对来避免重复计算。然而，键值缓存（KV缓存）的大小难以预测，甚至在长上下文长度场景下可能比模型权重大 tens of times。为此，我们提出了 Titanus，一种软硬件协同设计方法，用于实时高效压缩 KV 缓存。我们首先提出了级联剪枝量化（CPQ）方法来减少 KV 缓存的移动。引入了分层量化扩展策略来解决每通道量化不独立的问题。为了进一步减少 KV 缓存的移动，我们仅在加速器和片外内存之间传输非零 KV 缓存。此外，我们为 CPQ 方法定制了一个两阶段设计空间探索框架。设计了一种新型的流水线和并行数据流，以减少第一个 token 的生成时间。实验表明，与 Nvidia A100 GPU 和 FlightLLM 相比，Titanus 在能效和吞吐量方面分别提升了 159.9 倍（49.6 倍）和 34.8 倍（29.2 倍）。 Titanus 的代码可在 https://github.com/peilin-chen/Titanus-for-LLM-acceleration 获取。

> Large language models (LLMs) have gained great success in various domains. Existing systems cache Key and Value within the attention block to avoid redundant computations. However, the size of key-value cache (KV cache) is unpredictable and can even be tens of times larger than the weights in the long context length scenario. In this work, we propose Titanus, a software-hardware co-design to efficiently compress the KV cache on-the-fly. We first propose the cascade pruning-quantization (CPQ) method to reduce the KV cache movement. The hierarchical quantization extension strategy is introduced to tackle the non-independent per-channel quantization issue. To further reduce KV cache movement, we transfer only the non-zero KV cache between the accelerator and off-chip memory. Moreover, we customize a two-stage design space exploration framework for the CPQ method. A novel pipeline and parallelism dataflow is designed to reduce the first token generation time. Experiments show that Titanus achieves 159.9x (49.6x) and 34.8x (29.2x) energy efficiency (throughput) compared to Nvidia A100 GPU and FlightLLM respectively. The code for Titanus is available at https://github.com/peilin-chen/Titanus-for-LLM-acceleration.

[Arxiv](https://arxiv.org/abs/2505.17787)