# # PlanQA：利用结构化表示评估大型语言模型的空间推理能力的基准测试

发布时间：2025年07月10日

`LLM应用` `空间推理` `室内设计`

> PlanQA: A Benchmark for Spatial Reasoning in LLMs using Structured Representations

# 摘要

> 我们推出 PlanQA，一个用于评估大型语言模型（LLMs）几何与空间推理能力的诊断基准。它基于厨房、客厅等室内场景的结构化表示，采用符号格式（如 JSON、XML 布局）编码。PlanQA 包含多种问题类型，不仅涵盖距离、可见性、最短路径等度量和拓扑推理，还包括功能性、净空、平衡和实用性等室内设计约束。我们的实验结果显示，尽管前沿开源和商业 LLM 在浅层查询中表现尚可，但它们往往无法模拟物理约束、保持空间一致性或在布局变化中进行有效泛化。PlanQA 揭示了当前 LLM 的显著短板：它们无法稳定推理真实世界布局。我们期待这个基准能够激发新研究，推动语言模型在实际场景中准确推断和操作空间与几何属性的能力。

> We introduce PlanQA, a diagnostic benchmark for evaluating geometric and spatial reasoning in large-language models (LLMs). PlanQA is grounded in structured representations of indoor scenes, such as kitchens, living rooms, and bedrooms, encoded in a symbolic format (e.g., JSON, XML layouts). The benchmark includes diverse question types that test not only metric and topological reasoning (e.g., distance, visibility, shortest paths) but also interior design constraints such as affordance, clearance, balance, and usability. Our results across a variety of frontier open-source and commercial LLMs show that while models may succeed in shallow queries, they often fail to simulate physical constraints, preserve spatial coherence, or generalize under layout perturbation. PlanQA uncovers a clear blind spot in today's LLMs: they do not consistently reason about real-world layouts. We hope that this benchmark inspires new work on language models that can accurately infer and manipulate spatial and geometric properties in practical settings.

[Arxiv](https://arxiv.org/abs/2507.07644)