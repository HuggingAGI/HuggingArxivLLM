# 步骤3：大型且经济实惠：模型与系统协同打造高效解码方案

发布时间：2025年07月25日

`LLM应用` `人工智能` `计算技术`

> Step-3 is Large yet Affordable: Model-system Co-design for Cost-effective Decoding

# 摘要

> 大型语言模型在解码过程中往往面临硬件效率低下的问题，尤其是在处理长上下文推理任务时。本文介绍了一种名为 Step-3 的 3210 亿参数视觉语言模型 (VLM)，它通过硬件感知的模型-系统协同设计，特别优化以实现解码成本的最小化。Step-3 在两个关键维度上实现了创新：(1) 一种全新的多矩阵因子化注意力 (MFA) 机制，该机制在保持高度注意力表达能力的同时，显著降低了 KV 缓存大小和计算量；(2) 注意力-前馈网络分离 (AFD)，一种分布式推理系统，将注意力和前馈网络 (FFN) 层解耦为专用子系统。这种协同设计实现了前所未有的成本效率：与 DeepSeek-V3 和 Qwen3 MoE 235B 等模型相比，Step-3 在理论上大幅降低了解码成本，且随着上下文长度的增加，优势更加明显。Step-3 在每令牌激活 380 亿参数的同时实现了低成本（远超 DeepSeek-V3 和 Qwen3 MoE 235B），证明了与硬件对齐的注意力运算强度、MoE 稀疏性和 AFD 对成本效益的关键作用。我们在 DeepSeek-V3 的有利场景下进行了直接对比。在 Hopper GPU 上的实现，在 50ms TPOT 服务级别协议 (4K 上下文，FP8，无 MTP) 下，达到了每 GPU 每秒 4,039 个令牌的解码吞吐量。这一数字高于 DeepSeek-V3 在相同配置下的 2,324，为 LLM 解码设定了新的帕累托前沿。


> Large language models (LLMs) face low hardware efficiency during decoding, especially for long-context reasoning tasks. This paper introduces Step-3, a 321B-parameter VLM with hardware-aware model-system co-design optimized for minimizing decoding costs. Step-3 innovates in two key dimensions: (1) A novel Multi-Matrix Factorization Attention (MFA) mechanism that significantly reduces both KV cache size and computation while maintaining high attention expressiveness, and (2) Attention-FFN Disaggregation (AFD), a distributed inference system that decouples attention and Feed-Forward Network (FFN) layers into specialized subsystems. This co-design achieves unprecedented cost efficiency: Step-3 significantly reduces theoretical decoding costs compared with models like DeepSeek-V3 and Qwen3 MoE 235B, with the gains widening at longer context. Step-3 achieves low cost while activating 38B parameters per token (more than DeepSeek-V3 and Qwen3 MoE 235B), demonstrating that hardware-aligned attention arithmetic intensity, MoE sparsity, and AFD are critical to cost-effectiveness. We perform a head-to-head comparison with DeepSeek-V3 in its favorable scenarios. Our implementation on Hopper GPUs achieves a decoding throughput of up to 4,039 tokens per second per GPU under 50ms TPOT SLA (4K context, FP8, no MTP). It is higher than DeepSeek-V3's 2,324 in the same setup and sets a new Pareto frontier for LLM decoding.

[Arxiv](https://arxiv.org/abs/2507.19427)