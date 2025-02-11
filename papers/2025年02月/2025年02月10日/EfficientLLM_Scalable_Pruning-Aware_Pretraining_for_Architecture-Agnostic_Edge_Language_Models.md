# EfficientLLM：打造高效边缘语言模型的可扩展剪枝感知预训练方法

发布时间：2025年02月10日

`LLM应用` `边缘计算`

> EfficientLLM: Scalable Pruning-Aware Pretraining for Architecture-Agnostic Edge Language Models

# 摘要

> 由缩放定律驱动的现代大型语言模型 (LLMs) 在大规模模型中实现了智能应急。然而，随着对云成本、延迟和隐私问题的日益关注，开发紧凑的边缘语言模型变得尤为迫切。与传统受缩放定律限制的直接预训练方法不同，本研究提出了剪枝感知预训练，专注于保留更大优化模型的性能。其主要特点包括：1）数据可扩展性：我们在 LLM 中引入最小参数组，并持续优化结构化剪枝，将后训练剪枝方法（如 LLM-Pruner 和 SparseGPT）扩展到预训练阶段。2）架构无关性：LLM 的架构通过基于显著性的剪枝方法自动设计，这是现代预训练中首次超越人工设计的最优 LLM。我们发现，通过扩展 LLM 压缩并拓展其边界，可以实现高质量的边缘语言模型，命名为 EfficientLLM。EfficientLLM 在常识基准测试中显著优于具有 $100M \sim 1B$ 参数的最优基线模型，如 MobileLLM、SmolLM、Qwen2.5-0.5B、OLMo-1B 和 Llama3.2-1B。作为首次尝试，EfficientLLM 桥接了传统 LLM 压缩方法与直接预训练方法之间的性能差距，我们将在 https://github.com/Xingrun-Xing2/EfficientLLM 上完全开源。

> Modern large language models (LLMs) driven by scaling laws, achieve intelligence emergency in large model sizes. Recently, the increasing concerns about cloud costs, latency, and privacy make it an urgent requirement to develop compact edge language models. Distinguished from direct pretraining that bounded by the scaling law, this work proposes the pruning-aware pretraining, focusing on retaining performance of much larger optimized models. It features following characteristics: 1) Data-scalable: we introduce minimal parameter groups in LLM and continuously optimize structural pruning, extending post-training pruning methods like LLM-Pruner and SparseGPT into the pretraining phase. 2) Architecture-agnostic: the LLM architecture is auto-designed using saliency-driven pruning, which is the first time to exceed SoTA human-designed LLMs in modern pretraining. We reveal that it achieves top-quality edge language models, termed EfficientLLM, by scaling up LLM compression and extending its boundary. EfficientLLM significantly outperforms SoTA baselines with $100M \sim 1B$ parameters, such as MobileLLM, SmolLM, Qwen2.5-0.5B, OLMo-1B, Llama3.2-1B in common sense benchmarks. As the first attempt, EfficientLLM bridges the performance gap between traditional LLM compression and direct pretraining methods, and we will fully open source at https://github.com/Xingrun-Xing2/EfficientLLM.

[Arxiv](https://arxiv.org/abs/2502.06663)