# RPO: 检索偏好优化，助力检索增强生成更稳健

发布时间：2025年01月23日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）的改进方法，提出了检索偏好优化（RPO）来解决RAG在生成过程中依赖检索上下文质量和准确性的问题。论文的核心内容围绕如何优化RAG的性能，因此应归类为RAG。` `信息检索`

> RPO: Retrieval Preference Optimization for Robust Retrieval-Augmented Generation

# 摘要

> 尽管检索增强生成（RAG）在利用外部知识方面表现出色，但其生成过程高度依赖检索上下文的质量和准确性。当外部检索的非参数知识与内部记忆不一致时，大型语言模型（LLMs）难以评估其正确性，导致生成响应时出现知识冲突。为此，我们提出了检索偏好优化（RPO），这是一种轻量且高效的对齐方法，能够基于检索相关性自适应地整合多源知识。通过将检索相关性的隐式表示融入奖励模型，RPO将检索评估和响应生成合二为一，解决了以往方法需额外评估检索质量的问题。值得一提的是，RPO是唯一在训练中量化检索相关性意识的RAG专用对齐方法，成功克服了数学难题。在四个数据集上的实验表明，RPO在无需额外组件的情况下，准确率比RAG高出4-10%，展现了其卓越的泛化能力。

> While Retrieval-Augmented Generation (RAG) has exhibited promise in utilizing external knowledge, its generation process heavily depends on the quality and accuracy of the retrieved context. Large language models (LLMs) struggle to evaluate the correctness of non-parametric knowledge retrieved externally when it differs from internal memorization, leading to knowledge conflicts during response generation. To this end, we introduce the Retrieval Preference Optimization (RPO), a lightweight and effective alignment method to adaptively leverage multi-source knowledge based on retrieval relevance. An implicit representation of retrieval relevance is derived and incorporated into the reward model to integrate retrieval evaluation and response generation into a single model, solving the problem that previous methods necessitate the additional procedure to assess the retrieval quality. Notably, RPO is the only RAG-dedicated alignment approach that quantifies the awareness of retrieval relevance in training, overcoming mathematical obstacles. Experiments on four datasets demonstrate that RPO outperforms RAG by 4-10% in accuracy without any extra component, exhibiting its robust generalization.

[Arxiv](https://arxiv.org/abs/2501.13726)