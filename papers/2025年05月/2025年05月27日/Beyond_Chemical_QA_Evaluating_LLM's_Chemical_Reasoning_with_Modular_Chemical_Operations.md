# 超越化学问答：通过模块化化学操作评估大型语言模型的化学推理能力

发布时间：2025年05月27日

`LLM应用` `化学工程`

> Beyond Chemical QA: Evaluating LLM's Chemical Reasoning with Modular Chemical Operations

# 摘要

> 配备链式思维（CoT）推理的大型语言模型（LLMs）在数学和编程领域表现卓越，但在化学领域中系统性推理的潜力仍未被充分挖掘。化学领域需要通过严谨的结构分析来解决实际任务，如药物设计和反应工程。当前的基准测试主要集中在简单的知识检索上，忽视了分子优化和反应预测等复杂任务所需的关键步骤推理。为了解决这一问题，我们提出了ChemCoTBench，一个将分子结构理解与算术启发式操作（包括添加、删除和替换）相结合的推理框架，旨在将化学问题解决形式化为透明、分步的工作流程。通过将分子变换视为模块化的“化学操作”，该框架实现了慢速思考推理，类似于数学证明的逻辑，同时确保解决方案符合实际的化学约束条件。我们评估了模型在两个高影响力任务上的表现：分子性质优化和化学反应预测。这些任务不仅反映了现实世界的挑战，还提供了结构化的可评估性。通过提供标注数据集、推理分类法和基线评估，ChemCoTBench架起了抽象推理方法与实际化学发现之间的桥梁，为推进LLMs作为人工智能驱动科学创新工具奠定了基础。

> While large language models (LLMs) with Chain-of-Thought (CoT) reasoning excel in mathematics and coding, their potential for systematic reasoning in chemistry, a domain demanding rigorous structural analysis for real-world tasks like drug design and reaction engineering, remains untapped. Current benchmarks focus on simple knowledge retrieval, neglecting step-by-step reasoning required for complex tasks such as molecular optimization and reaction prediction. To address this, we introduce ChemCoTBench, a reasoning framework that bridges molecular structure understanding with arithmetic-inspired operations, including addition, deletion, and substitution, to formalize chemical problem-solving into transparent, step-by-step workflows. By treating molecular transformations as modular "chemical operations", the framework enables slow-thinking reasoning, mirroring the logic of mathematical proofs while grounding solutions in real-world chemical constraints. We evaluate models on two high-impact tasks: Molecular Property Optimization and Chemical Reaction Prediction. These tasks mirror real-world challenges while providing structured evaluability. By providing annotated datasets, a reasoning taxonomy, and baseline evaluations, ChemCoTBench bridges the gap between abstract reasoning methods and practical chemical discovery, establishing a foundation for advancing LLMs as tools for AI-driven scientific innovation.

[Arxiv](https://arxiv.org/abs/2505.21318)