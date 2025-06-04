# GraphRAG-Bench：挑战领域特定推理能力，评测图检索增强生成

发布时间：2025年06月02日

`RAG`

> GraphRAG-Bench: Challenging Domain-Specific Reasoning for Evaluating Graph Retrieval-Augmented Generation

# 摘要

> 图检索增强生成（GraphRAG）因其通过结构化组织领域特定语料库并促进复杂推理来提升大型语言模型（LLMs）的潜力而越来越受到关注。然而，目前对GraphRAG模型的评估主要依赖于传统的问答数据集。这些数据集在问题范围和评估指标上的局限性无法全面评估GraphRAG模型带来的推理能力提升。为了解决这一问题，我们引入了GraphRAG-Bench，这是一个大规模、领域特定的基准测试框架，旨在严格评估GraphRAG模型。我们的基准测试框架具有三个关键优势：\((i)\) 具有挑战性的问题设计。基准测试包含需要多跳推理的大学水平领域特定问题，确保简单的内容检索不足以解决问题。例如，某些问题需要数学推理或编程能力。\((ii)\) 任务覆盖广泛。数据集涵盖了多种推理任务，包括多项选择、是非题、多选、开放问答和填空题。它涵盖了20本核心教科书中的16个学科。\((iii)\) 全面的评估框架。GraphRAG-Bench提供了对整个GraphRAG流水线的全面评估，包括图构建、知识检索和答案生成。除了最终答案的正确性，它还评估推理过程的逻辑连贯性。通过将九种当代GraphRAG方法应用于GraphRAG-Bench，我们展示了其在量化基于图的结构如何提升模型推理能力方面的实用性。我们的分析揭示了关于图架构、检索效率和推理能力的关键见解，为研究界提供了可操作的指导建议。
    

> Graph Retrieval Augmented Generation (GraphRAG) has garnered increasing recognition for its potential to enhance large language models (LLMs) by structurally organizing domain-specific corpora and facilitating complex reasoning. However, current evaluations of GraphRAG models predominantly rely on traditional question-answering datasets. Their limited scope in questions and evaluation metrics fails to comprehensively assess the reasoning capacity improvements enabled by GraphRAG models. To address this gap, we introduce GraphRAG-Bench, a large-scale, domain-specific benchmark designed to rigorously evaluate GraphRAG models. Our benchmark offers three key superiorities: \((i)\) Challenging question design. Featuring college-level, domain-specific questions that demand multi-hop reasoning, the benchmark ensures that simple content retrieval is insufficient for problem-solving. For example, some questions require mathematical reasoning or programming. \((ii)\) Diverse task coverage. The dataset includes a broad spectrum of reasoning tasks, multiple-choice, true/false, multi-select, open-ended, and fill-in-the-blank. It spans 16 disciplines in twenty core textbooks. \((iii)\) Holistic evaluation framework. GraphRAG-Bench provides comprehensive assessment across the entire GraphRAG pipeline, including graph construction, knowledge retrieval, and answer generation. Beyond final-answer correctness, it evaluates the logical coherence of the reasoning process. By applying nine contemporary GraphRAG methods to GraphRAG-Bench, we demonstrate its utility in quantifying how graph-based structuring improves model reasoning capabilities. Our analysis reveals critical insights about graph architectures, retrieval efficacy, and reasoning capabilities, offering actionable guidance for the research community.

[Arxiv](https://arxiv.org/abs/2506.02404)