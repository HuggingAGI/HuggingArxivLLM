# DynamicMind：大型语言模型的三模式思维系统

发布时间：2025年06月06日

`LLM应用

摘要中提到的DynamicMind是一种创新的三模式思维系统，旨在优化大型语言模型在不同任务中的推理深度和计算资源使用。通过提示工程和自主选择思维模式，DynamicMind提升了模型的零样本问答能力，并在多个基准测试中表现出色。这些改进属于对LLM的应用优化，因此归类为LLM应用。` `问答系统` `人工智能`

> DynamicMind: A Tri-Mode Thinking System for Large Language Models

# 摘要

> 现代大型语言模型 (LLMs) 在应对不同复杂度的任务时，往往难以灵活调整推理深度，导致性能不佳或资源浪费。为解决这一问题，我们推出了 DynamicMind，一个创新的三模式思维系统。通过认知启发的提示工程，DynamicMind 让 LLMs 能够自主选择快速、正常或慢速思维模式，以应对零样本问答任务。我们的框架有三大核心创新：(1) 将传统的快慢双进程思维框架扩展为三模式系统，新增正常思维模式以保留 LLM 的原生能力；(2) 提出“思维密度”指标，实现计算资源与问题复杂性的精准匹配；(3) 开发“思维模式容量”(TMC) 数据集和轻量级“心智路由器”，用于预测最优思维模式。在数学、常识和科学问答等多个基准测试中，DynamicMind 不仅展现了卓越的零样本问答能力，还在性能与计算效率之间达到了理想的平衡。

> Modern large language models (LLMs) often struggle to dynamically adapt their reasoning depth to varying task complexities, leading to suboptimal performance or inefficient resource utilization. To address this, we introduce DynamicMind, a novel tri-mode thinking system. DynamicMind empowers LLMs to autonomously select between Fast, Normal, and Slow thinking modes for zero-shot question answering (ZSQA) tasks through cognitive-inspired prompt engineering. Our framework's core innovations include: (1) expanding the established dual-process framework of fast and slow thinking into a tri-mode thinking system involving a normal thinking mode to preserve the intrinsic capabilities of LLM; (2) proposing the Thinking Density metric, which aligns computational resource allocation with problem complexity; and (3) developing the Thinking Mode Capacity (TMC) dataset and a lightweight Mind Router to predict the optimal thinking mode. Extensive experiments across diverse mathematical, commonsense, and scientific QA benchmarks demonstrate that DynamicMind achieves superior ZSQA capabilities while establishing an effective trade-off between performance and computational efficiency.

[Arxiv](https://arxiv.org/abs/2506.05936)