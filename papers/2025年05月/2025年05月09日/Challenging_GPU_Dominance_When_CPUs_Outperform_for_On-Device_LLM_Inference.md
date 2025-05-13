# 挑战 GPU 主导地位：CPU 在设备端 LLM 推理中的出色表现

发布时间：2025年05月09日

`LLM应用` `移动计算` `人工智能`

> Challenging GPU Dominance: When CPUs Outperform for On-Device LLM Inference

# 摘要

> 在设备端AI领域，人们普遍认为GPU凭借其强大的并行处理能力，始终为大型语言模型（LLM）推理提供最佳性能。然而，本研究通过实证演示，在特定条件下，CPU在移动端设备上的LLM推理性能可超越GPU。通过在iPhone 15 Pro上部署经llama.cpp实现的10亿参数级LLM，我们发现仅CPU配置（两线程，F16精度）可实现每秒17个tokens的推理速度，超越GPU加速的每秒12.8个tokens。我们分析了导致这一反直觉结果的架构因素，揭示GPU内存传输开销和CPU线程优化发挥着关键作用。此外，我们探讨了线程超额订阅、量化策略及硬件约束的影响，为设备端AI的高效执行提供了新见解。我们的发现挑战了传统的GPU优先思维，凸显了优化CPU推理的未开发潜力，并为移动端AI的智能部署策略铺平了道路。然而，由于iOS上低级分析工具的访问受限，完全解释观察到的CPU优势仍具挑战性。

> The common assumption in on-device AI is that GPUs, with their superior parallel processing, always provide the best performance for large language model (LLM) inference. In this work, we challenge this notion by empirically demonstrating that, under certain conditions, CPUs can outperform GPUs for LLM inference on mobile devices. Using a 1-billion-parameter LLM deployed via llama.cpp on the iPhone 15 Pro, we show that a CPU-only configuration (two threads, F16 precision) achieves 17 tokens per second, surpassing the 12.8 tokens per second obtained with GPU acceleration. We analyze the architectural factors driving this counterintuitive result, revealing that GPU memory transfer overhead and CPU thread optimization play a critical role. Furthermore, we explore the impact of thread oversubscription, quantization strategies, and hardware constraints, providing new insights into efficient on-device AI execution. Our findings challenge conventional GPU-first thinking, highlighting the untapped potential of optimized CPU inference and paving the way for smarter deployment strategies in mobile AI. However, fully explaining the observed CPU advantage remains difficult due to limited access to low-level profiling tools on iOS.

[Arxiv](https://arxiv.org/abs/2505.06461)