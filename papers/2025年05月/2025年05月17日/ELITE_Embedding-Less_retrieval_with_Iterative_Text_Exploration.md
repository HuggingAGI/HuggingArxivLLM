# ELITE：无嵌入式检索与迭代文本探索方法

发布时间：2025年05月17日

`RAG` `问答系统` `信息检索`

> ELITE: Embedding-Less retrieval with Iterative Text Exploration

# 摘要

> 大型语言模型（LLMs）在自然语言处理领域取得了令人瞩目的进展，但其在保留长期上下文方面的能力有限，这限制了其在文档级别或多轮任务上的性能。检索增强生成（RAG）通过从外部语料库中检索相关信息来缓解这一问题。然而，现有的RAG系统通常依赖于基于语料库级语义相似性的嵌入式检索，这可能导致检索到与问题形式上语义相似但与真实意图不符的内容。此外，近期的RAG变体通过构建基于图或层次结构来提高检索准确性，这带来了显著的计算和存储开销。在本文中，我们提出了一种无嵌入式的检索框架。我们的方法利用大型语言模型在检索中的逻辑推理能力，通过我们新颖的重要性度量引导的迭代搜索空间细化，并在无需显式图构建的情况下，扩展检索结果以包含逻辑相关的更多信息。在长上下文问答基准测试（包括NovelQA和Marathon）上的实验表明，我们的方法在超越强基线的同时，将存储和运行时间减少了超过一个数量级。

> Large Language Models (LLMs) have achieved impressive progress in natural language processing, but their limited ability to retain long-term context constrains performance on document-level or multi-turn tasks. Retrieval-Augmented Generation (RAG) mitigates this by retrieving relevant information from an external corpus. However, existing RAG systems often rely on embedding-based retrieval trained on corpus-level semantic similarity, which can lead to retrieving content that is semantically similar in form but misaligned with the question's true intent. Furthermore, recent RAG variants construct graph- or hierarchy-based structures to improve retrieval accuracy, resulting in significant computation and storage overhead. In this paper, we propose an embedding-free retrieval framework. Our method leverages the logical inferencing ability of LLMs in retrieval using iterative search space refinement guided by our novel importance measure and extend our retrieval results with logically related information without explicit graph construction. Experiments on long-context QA benchmarks, including NovelQA and Marathon, show that our approach outperforms strong baselines while reducing storage and runtime by over an order of magnitude.

[Arxiv](https://arxiv.org/abs/2505.11908)