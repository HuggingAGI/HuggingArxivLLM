# 拆解长链式思考：用于长 CoT 蒸馏的结构化推理优化框架

发布时间：2025年03月20日

`LLM理论` `大型语言模型` `长链式推理`

> Deconstructing Long Chain-of-Thought: A Structured Reasoning Optimization Framework for Long CoT Distillation

# 摘要

> 大型语言模型（LLMs）在长链式推理（Chain-of-Thought, CoT）方面展现出了卓越的推理能力。R1蒸馏方案作为一种有效的训练方法，能够提升模型的推理能力同时控制成本。然而，其有效性背后的工作机制仍不明确。本研究探讨了蒸馏数据的通用性，并识别了在LLM蒸馏中高效转移长链推理能力的关键要素。研究发现，从教师模型（如Qwen-QwQ）中提取的长链CoT推理能力在非同源模型上的效果显著下降，这挑战了当前蒸馏方法通用性的假设。为深入理解长链CoT推理的结构和模式，我们提出了DLCoT（Deconstructing Long Chain-of-Thought），一种蒸馏数据增强框架。DLCoT包含三个关键步骤：(1) 数据分段，分解复杂的长链CoT结构；(2) 简化，消除不可解和冗余的解决方案；(3) 中间错误状态的优化。我们的方法显著提升了模型性能和token效率，为开发高性能LLMs提供了有力支持。

> Recent advancements in large language models (LLMs) have demonstrated remarkable reasoning capabilities through long chain-of-thought (CoT) reasoning. The R1 distillation scheme has emerged as a promising approach for training cost-effective models with enhanced reasoning abilities. However, the underlying mechanisms driving its effectiveness remain unclear. This study examines the universality of distillation data and identifies key components that enable the efficient transfer of long-chain reasoning capabilities in LLM distillation. Our findings reveal that the effectiveness of long CoT reasoning distillation from teacher models like Qwen-QwQ degrades significantly on nonhomologous models, challenging the assumed universality of current distillation methods. To gain deeper insights into the structure and patterns of long CoT reasoning, we propose DLCoT (Deconstructing Long Chain-of-Thought), a distillation data enhancement framework. DLCoT consists of three key steps: (1) data segmentation to decompose complex long CoT structures, (2) simplification by eliminating unsolvable and redundant solutions, and (3) optimization of intermediate error states. Our approach significantly improves model performance and token efficiency, facilitating the development of high-performance LLMs.

[Arxiv](https://arxiv.org/abs/2503.16385)