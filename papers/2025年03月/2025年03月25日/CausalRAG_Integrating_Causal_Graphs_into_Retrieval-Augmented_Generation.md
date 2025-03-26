# 因果图融入检索增强生成：CausalRAG模型

发布时间：2025年03月25日

`RAG` `知识密集型任务`

> CausalRAG: Integrating Causal Graphs into Retrieval-Augmented Generation

# 摘要

> 大型语言模型（LLMs）彻底改变了自然语言处理（NLP）领域，尤其是通过检索增强生成（RAG）方法，该方法通过整合外部知识增强了LLMs的能力。然而，传统的RAG系统在实际应用中面临两大关键挑战：文本分块导致的上下文完整性中断，以及过度依赖语义相似度进行检索。针对这些问题，我们提出了CausalRAG——一个将因果图融入检索过程的创新框架。通过构建并追踪因果关系，CausalRAG不仅保持了上下文的连贯性，还显著提升了检索的精准度，从而生成更准确且易于解释的响应。我们对CausalRAG与传统RAG及基于图的RAG方法进行了全面对比评估，结果表明CausalRAG在多个关键指标上表现更优。我们的研究发现表明，将检索过程建立在因果推理基础之上，为知识密集型任务提供了一个极具潜力的解决方案。


> Large language models (LLMs) have revolutionized natural language processing (NLP), particularly through Retrieval-Augmented Generation (RAG), which enhances LLM capabilities by integrating external knowledge. However, traditional RAG systems face critical limitations, including disrupted contextual integrity due to text chunking, and over-reliance on semantic similarity for retrieval. To address these issues, we propose CausalRAG, a novel framework that incorporates causal graphs into the retrieval process. By constructing and tracing causal relationships, CausalRAG preserves contextual continuity and improves retrieval precision, leading to more accurate and interpretable responses. We evaluate CausalRAG against regular RAG and graph-based RAG approaches, demonstrating its superiority across several metrics. Our findings suggest that grounding retrieval in causal reasoning provides a promising approach to knowledge-intensive tasks.

[Arxiv](https://arxiv.org/abs/2503.19878)