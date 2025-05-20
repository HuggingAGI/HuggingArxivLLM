# ELITE: 无嵌入检索通过迭代文本探索实现

发布时间：2025年05月17日

`RAG` `问答系统`

> ELITE: Embedding-Less retrieval with Iterative Text Exploration

# 摘要

> 大规模语言模型 (LLMs) 在自然语言处理领域取得了显著进展，但其难以有效保持长期上下文信息，限制了其在文档级或多轮任务中的表现。检索增强生成 (RAG) 通过从外部语料库中检索相关信息来缓解这一问题。然而，现有 RAG 系统通常依赖基于语料级别语义相似性的嵌入式检索，这可能导致检索内容在形式上语义相似，但与问题真实意图不符。此外，近期 RAG 变体通过构建基于图或层次结构的结构来提升检索精度，但这带来了显著的计算与存储开销。本文提出了一种无嵌入的检索框架。我们的方法借助 LLMs 在检索过程中的逻辑推理能力，通过新颖的重要性度量引导的迭代搜索空间优化，并在无需显式图构建的情况下扩展逻辑相关的信息检索。在 NovelQA 和 Marathon 等长上下文问答基准测试中，实验表明我们的方法不仅超越了强基线模型，还实现了存储和运行时间数量级的减少。

> Large Language Models (LLMs) have achieved impressive progress in natural language processing, but their limited ability to retain long-term context constrains performance on document-level or multi-turn tasks. Retrieval-Augmented Generation (RAG) mitigates this by retrieving relevant information from an external corpus. However, existing RAG systems often rely on embedding-based retrieval trained on corpus-level semantic similarity, which can lead to retrieving content that is semantically similar in form but misaligned with the question's true intent. Furthermore, recent RAG variants construct graph- or hierarchy-based structures to improve retrieval accuracy, resulting in significant computation and storage overhead. In this paper, we propose an embedding-free retrieval framework. Our method leverages the logical inferencing ability of LLMs in retrieval using iterative search space refinement guided by our novel importance measure and extend our retrieval results with logically related information without explicit graph construction. Experiments on long-context QA benchmarks, including NovelQA and Marathon, show that our approach outperforms strong baselines while reducing storage and runtime by over an order of magnitude.

[Arxiv](https://arxiv.org/abs/2505.11908)