# SparseAccelerate：为中端 GPU 实现高效的长上下文推理

发布时间：2024年12月08日

`LLM应用`

> SparseAccelerate: Efficient Long-Context Inference for Mid-Range GPUs

# 摘要

> 随着大型语言模型（LLMs）的上下文窗口不断变长，注意力机制的计算成本（通常随输入长度呈二次方增长）给实时和内存受限的部署带来了重大挑战。现有的稀疏注意力技术虽试图降低这一复杂性，但往往会带来显著的额外开销或影响准确性，在中端硬件的大上下文场景中实用性欠佳。本文中，我们推出了 SparseAccelerate 这一动态稀疏注意力方法，它能依据输入特征调整稀疏模式，有效拉平注意力复杂度曲线。该方法在输入长度从 16K 个标记起有效，并能在双 NVIDIA A5000 GPU（各 24GB）上高效扩展至 128K 个标记。实验结果显示，在 32K 个标记时，SparseAccelerate 能使首次标记的时间（TTFT）延迟最多降低 1.04 倍，同时大幅节省内存。这些改进为内存需求大的应用和以往标准注意力无法处理的长上下文任务带来了切实好处。除了降低延迟，SparseAccelerate 从根本上改变了扩展趋势，在竞争方法中，相对于上下文长度，其 TTFT 增长梯度最小。正在进行的各类基准测试评估证实了其可扩展性，使 SparseAccelerate 成为在常见硬件上实现高效、实时和大上下文 LLM 推理的重要突破。

> As Large Language Models (LLMs) scale to longer context windows, the computational cost of attention mechanisms, which traditionally grows quadratically with input length, presents a critical challenge for real-time and memory-constrained deployments. Existing sparse attention techniques have sought to reduce this complexity, but they often incur significant overhead or compromise accuracy, making them less practical for large contexts on mid-range hardware. In this paper, we introduce SparseAccelerate, a dynamic sparse attention method that adapts its sparsity patterns based on input characteristics, effectively flattening the attention complexity curve. Our approach is effective for input lengths starting at 16K tokens and scales efficiently up to 128K tokens on dual NVIDIA A5000 GPUs (24GB each). Experimental results show that SparseAccelerate achieves up to a 1.04x reduction in Time-To-First-Token (TTFT) latency at 32K tokens, while also providing substantial memory savings. These improvements yield practical gains for memory-intensive applications and long-context tasks that were previously infeasible with standard attention. Beyond latency reductions, SparseAccelerate fundamentally shifts the scaling trend, demonstrating the smallest TTFT growth gradient relative to context length among competing methods. Ongoing evaluations on diverse benchmarks confirm its scalability, positioning SparseAccelerate as a critical advancement toward efficient, real-time, and large-context LLM inference on accessible hardware.

[Arxiv](https://arxiv.org/abs/2412.06198)