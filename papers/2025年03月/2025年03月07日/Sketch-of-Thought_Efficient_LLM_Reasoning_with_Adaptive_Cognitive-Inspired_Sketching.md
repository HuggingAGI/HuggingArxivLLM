# 思路草图：通过自适应认知启发式草图实现高效LLM推理

发布时间：2025年03月07日

`LLM应用` `人工智能` `推理系统`

> Sketch-of-Thought: Efficient LLM Reasoning with Adaptive Cognitive-Inspired Sketching

# 摘要

> 近期，大型语言模型通过思维链提示（Chain of Thought，CoT）展现出了卓越的推理能力，但这种能力往往伴随着冗长的中间输出，增加了计算负担。我们提出了思路草图（Sketch-of-Thought，SoT），一种结合认知启发式推理范式与语言约束的新型提示框架，旨在在保持推理准确性的同时，最大限度地减少token使用。SoT被设计为一个灵活的框架，能够整合基于认知科学的任何定制推理范式。我们通过三种范式来实现它——概念连锁、分块符号主义和专家词典，每个范式都针对不同的推理任务，并通过轻量级路由模型动态选择。通过在15个推理数据集上进行多语言和多模态场景的全面评估，我们证明了SoT在几乎不影响准确性的前提下，将token使用量减少了76%。在数学推理和多跳推理等特定领域，它甚至在使用显著更少token的同时提高了准确性。我们的代码已公开发布：https://www.github.com/SimonAytes/SoT。

> Recent advances in large language models have demonstrated remarkable reasoning capabilities through Chain of Thought (CoT) prompting, but often at the cost of excessive verbosity in their intermediate outputs, which increases computational overhead. We introduce Sketch-of-Thought (SoT), a novel prompting framework that combines cognitive-inspired reasoning paradigms with linguistic constraints to minimize token usage while preserving reasoning accuracy. SoT is designed as a flexible framework that can incorporate any custom reasoning paradigms based on cognitive science, and we instantiate it with three such paradigms - Conceptual Chaining, Chunked Symbolism, and Expert Lexicons - each tailored to different reasoning tasks and selected dynamically via a lightweight routing model. Through comprehensive evaluation across 15 reasoning datasets with multiple languages and multimodal scenarios, we demonstrate that SoT achieves token reductions of 76% with negligible accuracy impact. In certain domains like mathematical and multi-hop reasoning, it even improves accuracy while using significantly fewer tokens. Our code is publicly available: https://www.github.com/SimonAytes/SoT.

[Arxiv](https://arxiv.org/abs/2503.05179)