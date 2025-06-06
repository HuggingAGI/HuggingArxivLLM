# 解构大型语言模型中的逻辑推理：一项细致的评估与监督研究

发布时间：2025年06月05日

`LLM理论` `人工智能`

> Dissecting Logical Reasoning in LLMs: A Fine-Grained Evaluation and Supervision Study

# 摘要

> 逻辑推理是大型语言模型（LLMs）在众多应用中的核心能力，但现有基准测试往往只关注最终答案的准确性，忽视了推理过程的质量和结构。为此，我们提出了FineLogic——一个细粒度的评估框架，从整体基准准确性、逐步合理性和表示级别一致性三个维度全面评估逻辑推理能力。此外，为了深入理解推理能力的形成机制，我们系统研究了微调过程中监督格式的影响。我们设计了四种监督风格（一种自然语言，三种符号变体），分别用于训练LLMs。研究发现，自然语言监督在分布外和长上下文任务上展现出强大的泛化能力，而符号推理风格则生成了结构更合理且原子化的推理链。进一步的表示级别探测表明，微调主要通过逐步生成改进推理行为，而非增强捷径预测或内在正确性。总的来说，FineLogic框架和分析为评估和提升LLMs的逻辑推理能力提供了一个更严格且可解释的视角。

> Logical reasoning is a core capability for many applications of large language models (LLMs), yet existing benchmarks often rely solely on final-answer accuracy, failing to capture the quality and structure of the reasoning process. We propose FineLogic, a fine-grained evaluation framework that assesses logical reasoning across three dimensions: overall benchmark accuracy, stepwise soundness, and representation-level alignment. In addition, to better understand how reasoning capabilities emerge, we conduct a comprehensive study on the effects of supervision format during fine-tuning. We construct four supervision styles (one natural language and three symbolic variants) and train LLMs under each. Our findings reveal that natural language supervision yields strong generalization even on out-of-distribution and long-context tasks, while symbolic reasoning styles promote more structurally sound and atomic inference chains. Further, our representation-level probing shows that fine-tuning primarily improves reasoning behaviors through step-by-step generation, rather than enhancing shortcut prediction or internalized correctness. Together, our framework and analysis provide a more rigorous and interpretable lens for evaluating and improving logical reasoning in LLMs.

[Arxiv](https://arxiv.org/abs/2506.04810)