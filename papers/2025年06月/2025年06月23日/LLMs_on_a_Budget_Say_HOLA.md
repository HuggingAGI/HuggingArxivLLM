# # 预算有限？试试 HOLA
LLMs on a Budget? Say HOLA！HOLA 是一种全新的方法，旨在以更低的成本实现更高效的 LLM 应用。通过 HOLA，我们能够更好地平衡性能与预算，为用户提供更灵活的选择。

发布时间：2025年06月23日

`LLM应用` `边缘计算` `嵌入式系统`

> LLMs on a Budget? Say HOLA

# 摘要

> 在边缘设备上运行大型语言模型 (LLMs) 面临高计算和内存需求的限制，这为医疗、教育和嵌入式系统等领域的实时应用带来了挑战。现有的解决方案如量化、剪枝和检索增强生成 (RAG) 仅提供部分优化，通常需要在速度或准确性上做出权衡。我们推出 HOLA，一个用于高效 LLM 部署的端到端优化框架。通过内部采用分层推测解码 (HSD) 实现更快推理，同时保持质量；外部则通过 AdaComp-RAG 根据上下文需求调整检索复杂度。结合 LoBi 技术，融合结构化剪枝 (LoRA) 和量化，HOLA 在性能上取得了显著突破：在 GSM8K 数据集上提升了 17.6% 的 EMA，在 ARC 数据集上提升了 10.5% 的 MCA，并在 Jetson Nano 等边缘设备上实现了更低的延迟和内存占用，充分展现了其可扩展性和生产就绪能力。

> Running Large Language Models (LLMs) on edge devices is constrained by high compute and memory demands posing a barrier for real-time applications in sectors like healthcare, education, and embedded systems. Current solutions such as quantization, pruning, and retrieval-augmented generation (RAG) offer only partial optimizations and often compromise on speed or accuracy. We introduce HOLA, an end-to-end optimization framework for efficient LLM deployment. Internally, it leverages Hierarchical Speculative Decoding (HSD) for faster inference without quality loss. Externally, AdaComp-RAG adjusts retrieval complexity based on context needs. Together with LoBi, which blends structured pruning (LoRA) and quantization, HOLA delivers significant gains: 17.6% EMA on GSM8K, 10.5% MCA on ARC, and reduced latency and memory on edge devices like Jetson Nano--proving both scalable and production-ready.

[Arxiv](https://arxiv.org/abs/2506.18952)