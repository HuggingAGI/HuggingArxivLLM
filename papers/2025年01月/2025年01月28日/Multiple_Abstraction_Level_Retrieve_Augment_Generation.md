# 多层次抽象检索增强生成

发布时间：2025年01月28日

`RAG

理由：这篇论文摘要讨论了基于大型语言模型（LLM）的检索增强生成（RAG）模型，并提出了一种新颖的RAG方法，采用多抽象级别（MAL）的块来应对跨多个抽象级别的信息需求。该方法在糖科学领域的实验中表现出色，提升了问答正确性。因此，这篇论文应归类为RAG。` `糖科学` `问答系统`

> Multiple Abstraction Level Retrieve Augment Generation

# 摘要

> 基于大型语言模型（LLM）的检索增强生成（RAG）模型，为适应新数据和知识提供了更快、更经济的解决方案，并生成比预训练LLM更专业的响应。然而，现有方法大多依赖检索前缀大小的块来支持问答（Q/A），难以应对跨多个抽象级别的信息需求。在RAG中，尽管LLM能在提供足够细节时有效总结和回答问题，但检索过多信息常导致“迷失在中间”问题并超出令牌限制。我们提出了一种新颖的RAG方法，采用多抽象级别（MAL）的块，涵盖多句子、段落、章节和文档级别。该方法在糖科学领域的实验中表现出色，相比传统单级别RAG方法，AI评估的糖相关论文问答正确性提升了25.739%。

> A Retrieval-Augmented Generation (RAG) model powered by a large language model (LLM) provides a faster and more cost-effective solution for adapting to new data and knowledge. It also delivers more specialized responses compared to pre-trained LLMs. However, most existing approaches rely on retrieving prefix-sized chunks as references to support question-answering (Q/A). This approach is often deployed to address information needs at a single level of abstraction, as it struggles to generate answers across multiple levels of abstraction. In an RAG setting, while LLMs can summarize and answer questions effectively when provided with sufficient details, retrieving excessive information often leads to the 'lost in the middle' problem and exceeds token limitations. We propose a novel RAG approach that uses chunks of multiple abstraction levels (MAL), including multi-sentence-level, paragraph-level, section-level, and document-level. The effectiveness of our approach is demonstrated in an under-explored scientific domain of Glycoscience. Compared to traditional single-level RAG approaches, our approach improves AI evaluated answer correctness of Q/A by 25.739\% on Glyco-related papers.

[Arxiv](https://arxiv.org/abs/2501.16952)