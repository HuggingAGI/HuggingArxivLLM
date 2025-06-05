# 在资源受限的 GPU 环境下实现大语言模型推理的并行 CPU-GPU 执行方案

发布时间：2025年06月03日

`LLM应用` `人工智能` `计算机系统`

> Parallel CPU-GPU Execution for LLM Inference on Constrained GPUs

# 摘要

> 在在线推理中部署大型语言模型（LLMs）时，GPU内存限制是一个主要问题，尤其是在自动回归解码过程中KV缓存占用不断增长。混合GPU-CPU执行作为一种有前景的解决方案，通过将KV缓存管理和部分注意力计算卸载到CPU来实现。然而，现有调度器在延迟敏感且带宽受限的解码阶段无法有效重叠CPU卸载任务与GPU执行，这对实时且解码密集型的应用（如聊天、链式推理）造成了严重影响，尤其在内存压力较大的边缘或低成本部署环境中，现有系统尚未提供良好支持。

我们提出了一种全新的、基于性能分析的调度策略APEX，旨在在混合LLM推理过程中最大化CPU与GPU的并行性。与依赖静态规则或纯启发式方法的系统不同，APEX通过预测CPU和GPU子任务的执行时间，动态地将计算任务分配到异构资源上，以实现最大化的任务重叠，同时避免调度开销。我们通过使用LLaMa-2-7B和LLaMa-3.1-8B模型，在多样化的 workload 和 GPU 架构（NVIDIA T4、A10）上对APEX进行了评估。与仅使用GPU的调度器（如VLLM）相比，APEX在T4 GPU上提升了84%-96%的吞吐量，在A10 GPU上提升了11%-89%的吞吐量，同时保持了延迟水平。与现有最佳混合调度器相比，在长输出场景下，APEX实现了最高49%（T4）和37%（A10）的吞吐量提升。APEX显著提升了在内存受限硬件上的混合LLM推理效率，为异构AI系统中的调度提供了蓝图，填补了高效实时LLM应用的关键空白。


> Deploying large language models (LLMs) for online inference is often constrained by limited GPU memory, particularly due to the growing KV cache during auto-regressive decoding. Hybrid GPU-CPU execution has emerged as a promising solution by offloading KV cache management and parts of attention computation to the CPU. However, a key bottleneck remains: existing schedulers fail to effectively overlap CPU-offloaded tasks with GPU execution during the latency-critical, bandwidth-bound decode phase. This particularly penalizes real-time, decode-heavy applications (e.g., chat, Chain-of-Thought reasoning) which are currently underserved by existing systems, especially under memory pressure typical of edge or low-cost deployments.
  We present APEX, a novel, profiling-informed scheduling strategy that maximizes CPU-GPU parallelism during hybrid LLM inference. Unlike systems relying on static rules or purely heuristic approaches, APEX dynamically dispatches compute across heterogeneous resources by predicting execution times of CPU and GPU subtasks to maximize overlap while avoiding scheduling overheads.We evaluate APEX on diverse workloads and GPU architectures (NVIDIA T4, A10), using LLaMa-2-7B and LLaMa-3.1-8B models. Compared to GPU-only schedulers like VLLM, APEX improves throughput by 84% - 96% on T4 and 11% - 89% on A10 GPUs, while preserving latency. Against the best existing hybrid schedulers, it delivers up to 49% (T4) and 37% (A10) higher throughput in long-output settings.APEX significantly advances hybrid LLM inference efficiency on such memory-constrained hardware and provides a blueprint for scheduling in heterogeneous AI systems, filling a critical gap for efficient real-time LLM applications.

[Arxiv](https://arxiv.org/abs/2506.03296)