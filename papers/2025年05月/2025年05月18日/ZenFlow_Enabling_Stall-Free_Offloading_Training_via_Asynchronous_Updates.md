# ZenFlow：借助异步更新机制实现无阻塞训练任务卸载

发布时间：2025年05月18日

`其他` `计算机体系结构` `并行计算`

> ZenFlow: Enabling Stall-Free Offloading Training via Asynchronous Updates

# 摘要

> 微调大型语言模型 (LLMs) 时，模型经常超出 GPU 内存限制，促使系统将模型状态卸载到 CPU 内存中。然而，现有的卸载训练框架如 ZeRO-Offload 对所有参数一视同仁，并在 CPU 上更新完整模型，导致严重的 GPU 停顿，即快速昂贵的 GPU 闲置等待缓慢的 CPU 更新和带宽有限的 PCIe 传输。
    我们提出了 ZenFlow，一种新的卸载框架，它优先处理重要参数，并将 GPU 和 CPU 之间的更新解耦。ZenFlow 在 GPU 上对重要梯度进行原地更新，同时异步地将不太重要的梯度卸载到 CPU 上进行累积，使 CPU 工作与 GPU 计算完全重叠。
    为了在多 GPU 上扩展，ZenFlow 引入了一种轻量级的梯度选择方法，利用重要梯度的新颖空间和时间局部性属性，避免代价高昂的全局同步。ZenFlow 实现了最高 5 倍的端到端加速， PCIe 传输减少 2 倍，并将 GPU 停顿减少了 85% 以上，同时保持了准确性。
    

> Fine-tuning large language models (LLMs) often exceeds GPU memory limits, prompting systems to offload model states to CPU memory. However, existing offloaded training frameworks like ZeRO-Offload treat all parameters equally and update the full model on the CPU, causing severe GPU stalls, where fast, expensive GPUs sit idle waiting for slow CPU updates and limited-bandwidth PCIe transfers.
  We present ZenFlow, a new offloading framework that prioritizes important parameters and decouples updates between GPU and CPU. ZenFlow performs in-place updates of important gradients on GPU, while asynchronously offloading and accumulating less important ones on CPU, fully overlapping CPU work with GPU computation.
  To scale across GPUs, ZenFlow introduces a lightweight gradient selection method that exploits a novel spatial and temporal locality property of important gradients, avoiding costly global synchronization. ZenFlow achieves up to 5x end-to-end speedup, 2x lower PCIe traffic, and reduces GPU stalls by over 85 percent, all while preserving accuracy.

[Arxiv](https://arxiv.org/abs/2505.12242)