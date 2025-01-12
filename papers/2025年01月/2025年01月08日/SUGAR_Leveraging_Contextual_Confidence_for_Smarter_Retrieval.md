# SUGAR: 基于上下文置信度的智能检索优化

发布时间：2025年01月08日

`RAG

理由：这篇论文讨论了检索增强生成（RAG）的改进方法，提出了语义不确定性引导的自适应检索（SUGAR），旨在通过动态决定是否检索以及选择单步或多步检索来提升问答任务的性能和推理效率。这直接涉及到RAG技术的应用和优化，因此应归类为RAG。` `问答系统`

> SUGAR: Leveraging Contextual Confidence for Smarter Retrieval

# 摘要

> 鉴于大型语言模型（LLMs）的参数知识有限，检索增强生成（RAG）通过提供相关外部知识，在一定程度上缓解了幻觉问题。然而，统一检索支持上下文导致响应生成效率低下，因为触发检索器并不总是必要，甚至可能不准确，尤其是在模型被嘈杂的检索内容干扰并生成无用答案时。为此，我们提出了语义不确定性引导的自适应检索（SUGAR），利用基于上下文的熵来动态决定是否检索，并进一步选择单步或多步检索。实验表明，基于语义不确定性估计的选择性检索不仅提升了多种问答任务的性能，还实现了更高效的推理。

> Bearing in mind the limited parametric knowledge of Large Language Models (LLMs), retrieval-augmented generation (RAG) which supplies them with the relevant external knowledge has served as an approach to mitigate the issue of hallucinations to a certain extent. However, uniformly retrieving supporting context makes response generation source-inefficient, as triggering the retriever is not always necessary, or even inaccurate, when a model gets distracted by noisy retrieved content and produces an unhelpful answer. Motivated by these issues, we introduce Semantic Uncertainty Guided Adaptive Retrieval (SUGAR), where we leverage context-based entropy to actively decide whether to retrieve and to further determine between single-step and multi-step retrieval. Our empirical results show that selective retrieval guided by semantic uncertainty estimation improves the performance across diverse question answering tasks, as well as achieves a more efficient inference.

[Arxiv](https://arxiv.org/abs/2501.04899)