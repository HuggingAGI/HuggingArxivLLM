# 迈向多模态LLM的元认知知识编辑

发布时间：2025年09月06日

`LLM应用` `基础理论`

> Towards Meta-Cognitive Knowledge Editing for Multimodal LLMs

# 摘要

> 知识编辑技术让多模态大型语言模型（MLLMs）得以高效更新过时或错误信息。然而，现有基准多聚焦于认知层面的修改，却忽略了对更深层元认知过程的关注。为此，我们提出了新型基准CogEdit，旨在从三个维度评估MLLMs的元认知知识编辑能力：（1）反事实驱动编辑——评估模型对知识正确性变化的自我觉察能力；（2）边界约束编辑——确保模型在合理泛化的同时避免意外干扰；（3）噪声鲁棒编辑——推动对不确定信息的反思性评估。为推动元认知编辑研究，我们进一步提出MIND（元认知集成动态知识编辑）框架：该框架通过构建元知识记忆实现自我觉察，采用博弈论交互机制监控知识激活过程，并结合标签优化策略实现噪声鲁棒更新。大量实验结果显示，MIND显著优于现有认知编辑方法，在传统及元认知知识编辑两类基准测试中均表现卓越。

> Knowledge editing enables multimodal large language models (MLLMs) to efficiently update outdated or incorrect information. However, existing benchmarks primarily emphasize cognitive-level modifications while lacking a focus on deeper meta-cognitive processes. To bridge this gap, we introduce CogEdit, a novel benchmark designed to evaluate MLLMs' meta-cognitive knowledge editing abilities across three levels: (1) Counterfactual-Driven Editing, assessing self-awareness of knowledge correctness changes; (2) Boundary Constraint Editing, ensuring appropriate generalization without unintended interference; and (3) Noise-Robust Editing, promoting reflective evaluation of uncertain information. To advance meta-cognitive editing, we propose MIND (Meta-cognitive INtegrated Dynamic Knowledge Editing), a framework that constructs a meta-knowledge memory for self-awareness, employs game-theoretic interactions to monitor knowledge activation, and incorporates label refinement for noise-robust updates. Extensive experiments show that MIND significantly outperforms existing cognitive editing approaches, achieving strong performance on both traditional and meta-cognitive knowledge editing benchmarks.

[Arxiv](https://arxiv.org/abs/2509.05714)