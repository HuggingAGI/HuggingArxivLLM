# Walk&Retrieve：知识图谱游走助力零样本检索增强生成

发布时间：2025年05月22日

`RAG` `知识图谱`

> Walk&Retrieve: Simple Yet Effective Zero-shot Retrieval-Augmented Generation via Knowledge Graph Walks

# 摘要

> 大型语言模型（LLMs）虽然展现了强大的推理能力，但幻觉现象和知识过时的问题依然存在。基于知识图谱（KG）的检索增强生成（RAG）方法通过将LLM的回答与知识库中的结构化外部信息相结合，弥补了这些不足。然而，现有基于KG的RAG方法在知识图谱与文本表示的对齐、检索准确性与效率的平衡、以及对动态更新知识图谱的适应性方面仍面临挑战。本文提出了一种简单而有效的基于知识图谱的框架Walk&Retrieve，该框架利用基于行走的图遍历和知识 verbalization 进行零样本 RAG 的语料生成。我们的方法以高效的KG遍历为核心，无需在特定领域数据上进行微调，从而能够无缝适应KG的更新，降低计算开销，并支持与任何现成的主干LLM进行集成。尽管其设计简洁，Walk&Retrieve在响应准确性和幻觉减少方面表现出色，通常优于现有的RAG系统。此外，它还实现了更低的查询延迟，并在处理大型KG时展现出强大的可扩展性，突显了轻量级检索策略作为未来RAG研究强基线的潜力。

> Large Language Models (LLMs) have showcased impressive reasoning abilities, but often suffer from hallucinations or outdated knowledge. Knowledge Graph (KG)-based Retrieval-Augmented Generation (RAG) remedies these shortcomings by grounding LLM responses in structured external information from a knowledge base. However, many KG-based RAG approaches struggle with (i) aligning KG and textual representations, (ii) balancing retrieval accuracy and efficiency, and (iii) adapting to dynamically updated KGs. In this work, we introduce Walk&Retrieve, a simple yet effective KG-based framework that leverages walk-based graph traversal and knowledge verbalization for corpus generation for zero-shot RAG. Built around efficient KG walks, our method does not require fine-tuning on domain-specific data, enabling seamless adaptation to KG updates, reducing computational overhead, and allowing integration with any off-the-shelf backbone LLM. Despite its simplicity, Walk&Retrieve performs competitively, often outperforming existing RAG systems in response accuracy and hallucination reduction. Moreover, it demonstrates lower query latency and robust scalability to large KGs, highlighting the potential of lightweight retrieval strategies as strong baselines for future RAG research.

[Arxiv](https://arxiv.org/abs/2505.16849)