# ZenFlow：无阻塞卸载训练的实现之道

发布时间：2025年05月18日

`LLM理论

理由：这篇论文主要探讨了在微调大型语言模型时的内存管理和训练效率优化问题，提出了一种新的卸载框架ZenFlow，通过优化参数处理和计算流程，显著提升了训练效率。这属于大型语言模型的训练方法和优化策略，因此归类到LLM理论。` `人工智能`

> ZenFlow: Enabling Stall-Free Offloading Training via Asynchronous Updates

# 摘要

> 微调大型语言模型（LLMs）时，模型状态经常超出GPU内存限制，迫使系统将模型状态卸载到CPU内存中。然而，现有框架如ZeRO-Offload将所有参数一视同仁，导致GPU空闲等待。我们提出ZenFlow，一种新的卸载框架，它通过优先处理重要参数并解耦GPU与CPU更新，显著提升训练效率。
    
    ZenFlow在GPU上对重要梯度进行原地更新，同时异步处理不重要梯度，使CPU工作与GPU计算完全重叠。通过创新的梯度选择方法，ZenFlow实现了端到端速度提升高达5倍，PCIe流量减半，GPU空闲时间降低85%，同时保持模型精度。
    

> Fine-tuning large language models (LLMs) often exceeds GPU memory limits, prompting systems to offload model states to CPU memory. However, existing offloaded training frameworks like ZeRO-Offload treat all parameters equally and update the full model on the CPU, causing severe GPU stalls, where fast, expensive GPUs sit idle waiting for slow CPU updates and limited-bandwidth PCIe transfers.
  We present ZenFlow, a new offloading framework that prioritizes important parameters and decouples updates between GPU and CPU. ZenFlow performs in-place updates of important gradients on GPU, while asynchronously offloading and accumulating less important ones on CPU, fully overlapping CPU work with GPU computation.
  To scale across GPUs, ZenFlow introduces a lightweight gradient selection method that exploits a novel spatial and temporal locality property of important gradients, avoiding costly global synchronization. ZenFlow achieves up to 5x end-to-end speedup, 2x lower PCIe traffic, and reduces GPU stalls by over 85 percent, all while preserving accuracy.

[Arxiv](https://arxiv.org/abs/2505.12242)