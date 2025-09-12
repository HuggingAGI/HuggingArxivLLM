# 融合知识与语言：基于知识图谱的问答与LLMs的对比研究

发布时间：2025年09月11日

`RAG` `基础理论`

> Fusing Knowledge and Language: A Comparative Study of Knowledge Graph-Based Question Answering with LLMs

# 摘要

> 知识图谱作为一种通过关系三元组对信息进行结构化的强大工具，最近已成为增强问答系统的新主流方法。传统的检索增强生成（RAG）方法虽擅长从简洁文本中提取基于事实和局部上下文的信息，但在理解复杂冗长文本的主题与整体含义时却存在局限，这类任务往往需要对文本及上下文进行更深层次的分析。本文针对三种构建知识图谱三元组并将其与大型语言模型（LLMs）集成以实现问答功能的方法（spaCy、Stanford CoreNLP-OpenIE和GraphRAG，均基于开源技术）展开了全面的技术对比研究。通过分析这些方法的性能、发展现状及其对基于LLM的问答系统性能的影响，我们评估了它们的有效性、可行性与适应性。实验结果显示，OpenIE能提供最全面的三元组覆盖，而GraphRAG在三者中展现出更出色的推理能力。最后，本文讨论了每种方法的优势与局限，并为改进基于知识图谱的问答系统的未来方向提供了见解。

> Knowledge graphs, a powerful tool for structuring information through relational triplets, have recently become the new front-runner in enhancing question-answering systems. While traditional Retrieval Augmented Generation (RAG) approaches are proficient in fact-based and local context-based extraction from concise texts, they encounter limitations when addressing the thematic and holistic understanding of complex, extensive texts, requiring a deeper analysis of both text and context. This paper presents a comprehensive technical comparative study of three different methodologies for constructing knowledge graph triplets and integrating them with Large Language Models (LLMs) for question answering: spaCy, Stanford CoreNLP-OpenIE, and GraphRAG, all leveraging open source technologies. We evaluate the effectiveness, feasibility, and adaptability of these methods by analyzing their capabilities, state of development, and their impact on the performance of LLM-based question answering. Experimental results indicate that while OpenIE provides the most comprehensive coverage of triplets, GraphRAG demonstrates superior reasoning abilities among the three. We conclude with a discussion on the strengths and limitations of each method and provide insights into future directions for improving knowledge graph-based question answering.

[Arxiv](https://arxiv.org/abs/2509.09272)