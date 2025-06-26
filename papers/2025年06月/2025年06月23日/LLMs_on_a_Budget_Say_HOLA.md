# 预算有限？LLM也能玩转！Hola，一起探索！

发布时间：2025年06月23日

`LLM应用` `嵌入式系统`

> LLMs on a Budget? Say HOLA

# 摘要

> 在边缘设备上运行大型语言模型（LLMs）面临计算和内存需求的高门槛，这对医疗、教育和嵌入式系统等领域的实时应用构成了障碍。现有的解决方案如量化、剪枝和检索增强生成（RAG）仅提供部分优化，通常需要在速度或精度上做出妥协。我们引入了HOLA，这是一个用于高效LLM部署的端到端优化框架。在内部，它利用分层推测解码（HSD）实现更快的推理，同时保持质量不下降。在外部，AdaComp-RAG根据上下文需求调整检索复杂度。结合LoBi（一种结合结构化剪枝（LoRA）和量化的技术），HOLA带来了显著提升：在GSM8K上实现了17.6%的EMA提升，在ARC上实现了10.5%的MCA提升，并在Jetson Nano等边缘设备上减少了延迟和内存占用——证明了其既具备可扩展性，又已准备好投入生产。

> Running Large Language Models (LLMs) on edge devices is constrained by high compute and memory demands posing a barrier for real-time applications in sectors like healthcare, education, and embedded systems. Current solutions such as quantization, pruning, and retrieval-augmented generation (RAG) offer only partial optimizations and often compromise on speed or accuracy. We introduce HOLA, an end-to-end optimization framework for efficient LLM deployment. Internally, it leverages Hierarchical Speculative Decoding (HSD) for faster inference without quality loss. Externally, AdaComp-RAG adjusts retrieval complexity based on context needs. Together with LoBi, which blends structured pruning (LoRA) and quantization, HOLA delivers significant gains: 17.6% EMA on GSM8K, 10.5% MCA on ARC, and reduced latency and memory on edge devices like Jetson Nano--proving both scalable and production-ready.

[Arxiv](https://arxiv.org/abs/2506.18952)