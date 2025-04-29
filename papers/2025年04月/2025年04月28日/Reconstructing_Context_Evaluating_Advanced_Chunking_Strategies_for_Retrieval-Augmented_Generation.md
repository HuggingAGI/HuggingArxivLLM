# 上下文重构：评估应用于增强检索生成的高级分块策略

发布时间：2025年04月28日

`RAG` `RAG系统`

> Reconstructing Context: Evaluating Advanced Chunking Strategies for Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）通过将大型语言模型（LLMs）与外部知识结合，成为提升模型性能的变革性方法。然而，如何在LLMs的输入限制内高效管理海量外部知识仍是一个关键挑战。传统方法通过将文档分割成固定大小的片段来应对这一问题，虽然缓解了输入限制，却导致上下文断裂，影响了检索完整性和生成连贯性。为解决这些问题，延迟切分和上下文检索这两种方法应运而生，均旨在保留全局上下文。尽管它们潜力巨大，但各自的优势与局限性尚不明确。本研究深入分析了这两种方法，评估其在优化RAG系统方面的有效性与效率。研究发现，上下文检索在保持语义连贯性方面表现更优，但需要更多计算资源；而延迟切分则更高效，却可能在相关性和完整性上有所牺牲。

> Retrieval-augmented generation (RAG) has become a transformative approach for enhancing large language models (LLMs) by grounding their outputs in external knowledge sources. Yet, a critical question persists: how can vast volumes of external knowledge be managed effectively within the input constraints of LLMs? Traditional methods address this by chunking external documents into smaller, fixed-size segments. While this approach alleviates input limitations, it often fragments context, resulting in incomplete retrieval and diminished coherence in generation. To overcome these shortcomings, two advanced techniques, late chunking and contextual retrieval, have been introduced, both aiming to preserve global context. Despite their potential, their comparative strengths and limitations remain unclear. This study presents a rigorous analysis of late chunking and contextual retrieval, evaluating their effectiveness and efficiency in optimizing RAG systems. Our results indicate that contextual retrieval preserves semantic coherence more effectively but requires greater computational resources. In contrast, late chunking offers higher efficiency but tends to sacrifice relevance and completeness.

[Arxiv](https://arxiv.org/abs/2504.19754)