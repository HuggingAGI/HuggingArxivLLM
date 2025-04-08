# 利用辩证推理论证优化多语言检索增强型语言模型

发布时间：2025年04月07日

`RAG` `信息处理`

> Improving Multilingual Retrieval-Augmented Language Models through Dialectic Reasoning Argumentations

# 摘要

> 检索增强生成（RAG）是提升大型语言模型（LLMs）系统性获取更丰富事实知识的关键。然而，使用RAG也带来了固有的挑战，因为LLMs必须处理潜在的相互冲突的知识，尤其是在多语言检索中，检索到知识的异质性可能导致不同的视角。为了使RAG更具分析性、批判性和扎实性，我们引入了Dialectic-RAG（DRAG），这是一种由论证解释指导的模块化方法，即一种有条理的推理过程，系统地通过比较、对比和解决冲突观点来评估检索信息。给定一个查询和一组多语言相关文档，DRAG会选取并举例说明相关知识，以提供辩证解释：通过批判性权衡对立论点并过滤无关内容，清晰地确定最终响应。通过一系列深入实验，我们展示了我们的框架既作为上下文学习策略，又用于构建演示以指导较小模型的双重影响。最终结果显示，DRAG显著改进了RAG方法，仅需低计算开销，并对知识扰动具有鲁棒性。

> Retrieval-augmented generation (RAG) is key to enhancing large language models (LLMs) to systematically access richer factual knowledge. Yet, using RAG brings intrinsic challenges, as LLMs must deal with potentially conflicting knowledge, especially in multilingual retrieval, where the heterogeneity of knowledge retrieved may deliver different outlooks. To make RAG more analytical, critical and grounded, we introduce Dialectic-RAG (DRAG), a modular approach guided by Argumentative Explanations, i.e., structured reasoning process that systematically evaluates retrieved
  information by comparing, contrasting, and resolving conflicting perspectives. Given a query and a set of multilingual related documents, DRAG selects and exemplifies relevant knowledge for delivering dialectic explanations that, by critically weighing opposing arguments and filtering extraneous content, clearly determine the final response. Through a series of in-depth experiments, we show the impact of our framework both as an in-context learning strategy and for constructing demonstrations to instruct smaller models. The final results demonstrate that DRAG significantly improves RAG approaches, requiring low-impact computational effort and providing robustness to knowledge perturbations.

[Arxiv](https://arxiv.org/abs/2504.04771)