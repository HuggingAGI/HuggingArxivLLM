# 基于知识检索的课堂大型语言模型（LLMs）对齐——一项比较性RAG研究

发布时间：2025年09月09日

`RAG` `教育科技`

> Aligning LLMs for the Classroom with Knowledge-Based Retrieval -- A Comparative RAG Study

# 摘要

> 如今ChatGPT等大型语言模型在课堂中的应用日益广泛，但它们时常给出过时或虚构的信息，容易误导学生。检索增强生成（RAG）技术通过将回答锚定在外部资源上，有效提升了大型语言模型的可靠性。我们深入研究了两种易于部署的RAG范式——基于向量的检索和基于图的检索，旨在找出课堂问答（QA）的最佳实践方案。然而现有对比研究往往忽略了教学相关因素，比如学科差异、问题类型以及实际部署成本。为此，我们构建了全新数据集EduScopeQA，涵盖3176个跨学科问题，并以此评估系统在各类教育查询上的表现——从具体事实查询到宽泛的主题讨论。同时，我们还利用系统性篡改的教科书数据集（其中内容与大型语言模型固有知识相冲突），对系统一致性进行了验证。研究发现，OpenAI向量搜索RAG（代表基于向量的RAG）作为低成本通用方案表现出色，尤其擅长快速事实检索；而GraphRAG Global则在主题查询中展现优势，能提供教学内容丰富的答案；当语料库完整性成为关键时，GraphRAG Local在内容密集的篡改教科书中准确率最高。考虑到GraphRAG（代表基于图的RAG）的资源消耗比向量检索高出10-20倍，我们提出一种动态分支框架——通过将查询路由至最优检索方法，既能提升回答的保真度，又能提高效率。这些发现为教育工作者和系统设计者提供了切实可行的指导，助力他们将RAG增强型大型语言模型高效融入学习场景。

> Large language models like ChatGPT are increasingly used in classrooms, but they often provide outdated or fabricated information that can mislead students. Retrieval Augmented Generation (RAG) improves reliability of LLMs by grounding responses in external resources. We investigate two accessible RAG paradigms, vector-based retrieval and graph-based retrieval to identify best practices for classroom question answering (QA). Existing comparative studies fail to account for pedagogical factors such as educational disciplines, question types, and practical deployment costs. Using a novel dataset, EduScopeQA, of 3,176 questions across academic subjects, we measure performance on various educational query types, from specific facts to broad thematic discussions. We also evaluate system alignment with a dataset of systematically altered textbooks that contradict the LLM's latent knowledge. We find that OpenAI Vector Search RAG (representing vector-based RAG) performs well as a low-cost generalist, especially for quick fact retrieval. On the other hand, GraphRAG Global excels at providing pedagogically rich answers to thematic queries, and GraphRAG Local achieves the highest accuracy with the dense, altered textbooks when corpus integrity is critical. Accounting for the 10-20x higher resource usage of GraphRAG (representing graph-based RAG), we show that a dynamic branching framework that routes queries to the optimal retrieval method boosts fidelity and efficiency. These insights provide actionable guidelines for educators and system designers to integrate RAG-augmented LLMs into learning environments effectively.

[Arxiv](https://arxiv.org/abs/2509.07846)