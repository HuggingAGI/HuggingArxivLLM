# # PromptPrism：语言学启发的提示分类框架

发布时间：2025年05月18日

`LLM应用

论文摘要讨论了提示语在大型语言模型中的作用，并提出了一种新的分类法（PromptPrism）来分析和优化提示语，从而提升模型性能。这属于将大型语言模型应用于实际问题和优化的范畴，因此归类为LLM应用。` `数据科学`

> PromptPrism: A Linguistically-Inspired Taxonomy for Prompts

# 摘要

> 提示语是大型语言模型（LLMs）能力的接口，理解其结构和组成部分对分析模型行为和优化性能至关重要。然而，目前该领域缺乏一个全面的框架来进行系统的提示语分析和理解。我们引入了PromptPrism，一个以语言学为启发的分类法，能够在功能结构、语义组件和句法模式三个层次上进行提示语分析。通过将其应用于三个实际应用场景，我们展示了PromptPrism的实用价值：（1）一种基于分类法的提示语优化方法，能够自动提升提示语质量并增强模型在多种任务中的性能；（2）一种多维度的数据集分析方法，可以从提示语数据集中提取和聚合结构、语义和句法特征，从而实现对提示语分布和模式的全面分析；（3）一种用于提示语敏感性分析的控制实验框架，通过量化语义重新排序和分隔符修改对LLM性能的影响来实现。实验结果验证了该分类法在这些应用场景中的有效性，表明PromptPrism为优化、分析和理解提示语提供了一个坚实的基础。

> Prompts are the interface for eliciting the capabilities of large language models (LLMs). Understanding their structure and components is critical for analyzing LLM behavior and optimizing performance. However, the field lacks a comprehensive framework for systematic prompt analysis and understanding. We introduce PromptPrism, a linguistically-inspired taxonomy that enables prompt analysis across three hierarchical levels: functional structure, semantic component, and syntactic pattern. We show the practical utility of PromptPrism by applying it to three applications: (1) a taxonomy-guided prompt refinement approach that automatically improves prompt quality and enhances model performance across a range of tasks; (2) a multi-dimensional dataset profiling method that extracts and aggregates structural, semantic, and syntactic characteristics from prompt datasets, enabling comprehensive analysis of prompt distributions and patterns; (3) a controlled experimental framework for prompt sensitivity analysis by quantifying the impact of semantic reordering and delimiter modifications on LLM performance. Our experimental results validate the effectiveness of our taxonomy across these applications, demonstrating that PromptPrism provides a foundation for refining, profiling, and analyzing prompts.

[Arxiv](https://arxiv.org/abs/2505.12592)