# TRIDENT: 通过DFA增强的神经网络遍历实现时间受限推理

发布时间：2025年06月11日

`LLM应用` `生成模型`

> TRIDENT: Temporally Restricted Inference via DFA-Enhanced Neural Traversal

# 摘要

> 大型语言模型（LLMs）和其他神经架构在生成和分类任务中表现卓越，但在满足时间约束方面仍有不足，例如有限轨迹上的线性时态逻辑（LTLf）约束。本文提出TRIDENT：一种通用、无需重新训练的推理算法，确保输出符合此类约束。TRIDENT将LTLf公式编译为确定性有限自动机（DFA），指导束搜索的变体。解码时，屏蔽违规转换，根据模型概率和DFA结构动态调整路径。我们证明TRIDENT生成序列满足LTLf约束，并通过实验验证其提升输出质量。在图像流分类和文本生成任务中，TRIDENT实现完美约束满足，同时展现出高效和高质量。

> Large Language Models (LLMs) and other neural architectures have achieved impressive results across a variety of generative and classification tasks. However, they remain fundamentally ill-equipped to ensure that their outputs satisfy temporal constraints, such as those expressible in Linear Temporal Logic over finite traces (LTLf). In this paper, we introduce TRIDENT: a general and model-agnostic inference-time algorithm that guarantees compliance with such constraints without requiring any retraining. TRIDENT compiles LTLf formulas into a Deterministic Finite Automaton (DFA), which is used to guide a constrained variant of beam search. At each decoding step, transitions that would lead to constraint violations are masked, while remaining paths are dynamically re-ranked based on both the model's probabilities and the DFA's acceptance structure. We formally prove that the resulting sequences are guaranteed to satisfy the given LTLf constraints, and we empirically demonstrate that TRIDENT also improves output quality. We validate our approach on two distinct tasks: temporally constrained image-stream classification and controlled text generation. In both settings, TRIDENT achieves perfect constraint satisfaction, while comparison with the state of the art shows improved efficiency and high standard quality metrics.

[Arxiv](https://arxiv.org/abs/2506.09701)