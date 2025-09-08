# KERAG：面向高级问答的知识增强检索增强生成

发布时间：2025年09月04日

`RAG` `基础理论`

> KERAG: Knowledge-Enhanced Retrieval-Augmented Generation for Advanced Question Answering

# 摘要

> 检索增强生成（RAG）通过整合外部数据缓解大型语言模型（LLMs）的幻觉问题，而知识图谱（KGs）则为问答提供关键信息支持。传统知识图谱问答（KGQA）方法依赖语义解析，这类方法通常仅检索生成答案所需的核心知识，然而由于模式要求僵化和语义模糊，其覆盖率往往较低。为此，我们提出了KERAG——一种新颖的基于知识图谱的RAG流水线，它通过检索更广泛的潜在相关子图来提升问答覆盖率。我们提出的“检索-过滤-总结”方法，结合经微调的LLMs对知识子图进行思维链推理，不仅降低了噪声干扰，还同时提升了简单和复杂问题的问答效果。实验结果显示，KERAG在质量上比现有最优解决方案高出约7%，同时较GPT-4o（工具版）提升了10-21%。

> Retrieval-Augmented Generation (RAG) mitigates hallucination in Large Language Models (LLMs) by incorporating external data, with Knowledge Graphs (KGs) offering crucial information for question answering. Traditional Knowledge Graph Question Answering (KGQA) methods rely on semantic parsing, which typically retrieves knowledge strictly necessary for answer generation, thus often suffer from low coverage due to rigid schema requirements and semantic ambiguity. We present KERAG, a novel KG-based RAG pipeline that enhances QA coverage by retrieving a broader subgraph likely to contain relevant information. Our retrieval-filtering-summarization approach, combined with fine-tuned LLMs for Chain-of-Thought reasoning on knowledge sub-graphs, reduces noises and improves QA for both simple and complex questions. Experiments demonstrate that KERAG surpasses state-of-the-art solutions by about 7% in quality and exceeds GPT-4o (Tool) by 10-21%.

[Arxiv](https://arxiv.org/abs/2509.04716)