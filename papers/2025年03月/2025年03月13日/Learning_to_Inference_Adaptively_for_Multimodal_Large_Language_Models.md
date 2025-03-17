# 多模态大语言模型的自适应推理学习

发布时间：2025年03月13日

`LLM应用

理由：这篇论文探讨了多模态大型语言模型（MLLMs）在资源受限环境中的应用，并提出了一种自适应推理框架AdaLLaVA，以优化其在不同运行条件下的性能。研究属于将大型语言模型应用于实际问题并进行优化的范畴，因此归类为LLM应用。` `资源受限环境`

> Learning to Inference Adaptively for Multimodal Large Language Models

# 摘要

> 多模态大型语言模型 (MLLMs) 虽然在推理能力上表现出色，但其高昂的计算成本限制了在资源受限环境中的应用。尽管近期为提升 MLLMs 效率做出了诸多努力，但现有解决方案仍难以应对运行时条件的变化，尤其是资源可用性的波动（例如设备上其他程序执行导致的资源争用）。为了解决这一问题，我们提出了 AdaLLaVA，一个自适应推理框架。它能够在推理过程中根据输入数据和延迟预算动态调整 MLLM 的操作。我们在问答、推理和生成等多个基准测试中进行了广泛实验。结果显示，AdaLLaVA 能够有效遵循输入的延迟预算，在运行时实现灵活的准确性和延迟权衡。此外，我们证明了 AdaLLaVA 不仅能够适应输入的延迟和内容，还能够与令牌选择集成以提高效率，并且在多种 MLLMs 上具有良好的通用性。我们的项目网页和代码发布地址为 https://zhuoyan-xu.github.io/ada-llava/。

> Multimodal Large Language Models (MLLMs) have shown impressive capabilities in reasoning, yet come with substantial computational cost, limiting their deployment in resource-constrained settings. Despite recent efforts on improving the efficiency of MLLMs, prior solutions fall short in responding to varying runtime conditions, in particular changing resource availability (e.g., contention due to the execution of other programs on the device). To bridge this gap, we introduce AdaLLaVA, an adaptive inference framework that learns to dynamically reconfigure operations in an MLLM during inference, accounting for the input data and a latency budget. We conduct extensive experiments across benchmarks involving question-answering, reasoning, and hallucination. Our results show that AdaLLaVA effectively adheres to input latency budget, achieving varying accuracy and latency tradeoffs at runtime. Further, we demonstrate that AdaLLaVA adapts to both input latency and content, can be integrated with token selection for enhanced efficiency, and generalizes across MLLMs.Our project webpage with code release is at https://zhuoyan-xu.github.io/ada-llava/.

[Arxiv](https://arxiv.org/abs/2503.10905)