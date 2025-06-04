# # 高效且感知工作负载的LLM服务：通过运行时层交换与KV缓存调整实现

发布时间：2025年05月24日

`LLM应用` `服务框架` `动态负载管理`

> Efficient and Workload-Aware LLM Serving via Runtime Layer Swapping and KV Cache Resizing

# 摘要

> 在动态且突发的工作负载下高效部署大型语言模型 (LLMs) 仍是一个重要挑战。现有服务框架和静态压缩技术无法适应负载波动，导致全精度服务出现 SLO 违约，或静态量化下精度持续下降。我们提出 MorphServe，一个基于形态适应的动态 LLM 服务框架。MorphServe 采用两项创新机制：量化层交换和压力感知 KV 缓存调整，实现低开销的状态转换，同时兼容现代调度和注意力机制。实验证明，MorphServe 将 SLO 违约减少 92.45%，提升 P95 TTFT 延迟 2.2-3.9 倍，且不降低生成质量。MorphServe 成为动态环境下的实用弹性部署方案。

> Efficiently serving large language models (LLMs) under dynamic and bursty workloads remains a key challenge for real-world deployment. Existing serving frameworks and static model compression techniques fail to adapt to workload fluctuations, leading to either service-level objective (SLO) violations under full-precision serving or persistent accuracy degradation with static quantization. We present MorphServe, a dynamic, workload-aware LLM serving framework based on morphological adaptation. MorphServe introduces two asynchronous, token-level runtime mechanisms: quantized layer swapping, which selectively replaces less impactful layers with quantized alternatives during high-load periods, and pressure-aware KV cache resizing, which dynamically adjusts KV cache capacity in response to memory pressure. These mechanisms enable state-preserving transitions with minimum runtime overhead and are fully compatible with modern scheduling and attention techniques. Extensive experiments on Vicuna and Llama family models with real-world workloads demonstrate that MorphServe reduces average SLO violations by 92.45 percent and improves the P95 TTFT latency by 2.2x-3.9x compared to full-precision serving, without compromising generation quality. These results establish MorphServe as a practical and elastic solution for LLM deployment in dynamic environments.

[Arxiv](https://arxiv.org/abs/2506.02006)