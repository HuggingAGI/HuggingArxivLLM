# 高效且感知负载的LLM服务：基于运行时层交换与KV缓存调整

发布时间：2025年05月24日

`LLM应用` `服务框架`

> Efficient and Workload-Aware LLM Serving via Runtime Layer Swapping and KV Cache Resizing

# 摘要

> 在动态和突发性工作负载下高效部署大型语言模型 (LLMs) 是实际应用中的关键挑战。现有服务框架和静态模型压缩技术无法适应工作负载波动，导致全精度服务下出现 SLO 违约，或静态量化下持续出现准确性下降。我们提出了 MorphServe，这是一个基于形态适应的动态、工作负载感知型 LLM 服务框架。MorphServe 引入了两个异步的、基于令牌的运行时机制：量化层替换和压力感知的 KV 缓存调整。这些机制实现了具有最小运行时开销的状态保留转换，并与现代调度和注意力技术完全兼容。在真实工作负载下对 Vicuna 和 Llama 家族模型的广泛实验表明，与全精度服务相比，MorphServe 将平均 SLO 违约减少了 92.45%，并将 P95 TTFT 延迟提高了 2.2x-3.9x，同时保持了生成质量。这些结果确立了 MorphServe 作为动态环境下 LLM 部署的实际弹性解决方案。

> Efficiently serving large language models (LLMs) under dynamic and bursty workloads remains a key challenge for real-world deployment. Existing serving frameworks and static model compression techniques fail to adapt to workload fluctuations, leading to either service-level objective (SLO) violations under full-precision serving or persistent accuracy degradation with static quantization. We present MorphServe, a dynamic, workload-aware LLM serving framework based on morphological adaptation. MorphServe introduces two asynchronous, token-level runtime mechanisms: quantized layer swapping, which selectively replaces less impactful layers with quantized alternatives during high-load periods, and pressure-aware KV cache resizing, which dynamically adjusts KV cache capacity in response to memory pressure. These mechanisms enable state-preserving transitions with minimum runtime overhead and are fully compatible with modern scheduling and attention techniques. Extensive experiments on Vicuna and Llama family models with real-world workloads demonstrate that MorphServe reduces average SLO violations by 92.45 percent and improves the P95 TTFT latency by 2.2x-3.9x compared to full-precision serving, without compromising generation quality. These results establish MorphServe as a practical and elastic solution for LLM deployment in dynamic environments.

[Arxiv](https://arxiv.org/abs/2506.02006)