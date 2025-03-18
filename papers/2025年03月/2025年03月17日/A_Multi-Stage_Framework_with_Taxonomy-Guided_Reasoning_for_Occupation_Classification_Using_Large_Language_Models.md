# 一种基于大型语言模型的多阶段职业分类框架，采用基于分类学的推理方法进行职业分类

发布时间：2025年03月17日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在职业数据自动标注中的应用，评估其能力并提出了一种多阶段框架来提升分类准确率。研究集中在应用层面，而非模型的理论或机制，因此归类为LLM应用。` `人力资源管理`

> A Multi-Stage Framework with Taxonomy-Guided Reasoning for Occupation Classification Using Large Language Models

# 摘要

> # 自动标注职业数据
为职业数据自动标注标准化职业分类法，即职业分类，对于劳动力市场分析至关重要。然而，这一任务常受数据稀缺和手动标注挑战的限制。尽管大型语言模型（LLMs）凭借其广泛的世界知识和上下文学习能力展现出潜力，但其对职业分类法的知识掌握程度尚不明确，这直接影响了其表现。本研究旨在评估LLMs从分类法生成精确分类实体的能力，并揭示其局限性。为应对这些挑战，我们提出了一种包含推理、检索和重新排序阶段的多阶段框架，并融入分类法指导的推理示例，以实现输出与分类法知识的对齐，从而提升性能。在大规模数据集上的评估表明，该框架显著提高了分类准确率。此外，我们还展示了该框架在多标签技能分类中的良好适应性。实验结果表明，该框架超越了现有的基于LLMs的方法，为职业分类及相关任务提供了一种实用且可扩展的解决方案，适用于多种大型语言模型。

> Automatically annotating job data with standardized occupations from taxonomies, known as occupation classification, is crucial for labor market analysis. However, this task is often hindered by data scarcity and the challenges of manual annotations. While large language models (LLMs) hold promise due to their extensive world knowledge and in-context learning capabilities, their effectiveness depends on their knowledge of occupational taxonomies, which remains unclear. In this study, we assess the ability of LLMs to generate precise taxonomic entities from taxonomy, highlighting their limitations. To address these challenges, we propose a multi-stage framework consisting of inference, retrieval, and reranking stages, which integrates taxonomy-guided reasoning examples to enhance performance by aligning outputs with taxonomic knowledge. Evaluations on a large-scale dataset show significant improvements in classification accuracy. Furthermore, we demonstrate the framework's adaptability for multi-label skill classification. Our results indicate that the framework outperforms existing LLM-based methods, offering a practical and scalable solution for occupation classification and related tasks across LLMs.

[Arxiv](https://arxiv.org/abs/2503.12989)