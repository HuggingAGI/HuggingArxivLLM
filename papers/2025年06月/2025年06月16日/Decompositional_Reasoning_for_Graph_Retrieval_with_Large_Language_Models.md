# 基于大型语言模型的图检索分解式推理

发布时间：2025年06月16日

`LLM应用` `问答系统` `知识图谱`

> Decompositional Reasoning for Graph Retrieval with Large Language Models

# 摘要

> 大型语言模型 (LLMs) 在许多自然语言处理 (NLP) 任务中表现出色，但在多跳推理和事实一致性方面存在不足，这限制了它们在复杂问答 (QA) 等知识密集型任务中的效果。将知识图谱 (KG) 与 LLMs 结合使用已经取得了令人鼓舞的成果，但 LLMs 通常缺乏在图结构化信息上进行高效推理的能力。为了解决这一问题，我们提出了一种新颖的检索方法，通过查询分解将文本知识图谱整合到 LLM 的推理过程中。我们的方法将复杂问题分解为子问题，检索相关的文本子图，并构建一个特定于问题的知识图谱来指导答案生成。为此，我们采用了一种加权相似度函数，该函数同时关注复杂问题和生成的子问题，以提取相关的子图，从而实现对复杂问题的高效和精确检索，并提高 LLMs 在多跳 QA 任务上的性能。这种结构化的推理管道增强了事实依据和可解释性，同时利用了 LLMs 的生成优势。我们在标准多跳 QA 基准测试上评估了我们的方法，并证明使用较小规模的模型和较少的 LLM 调用次数，我们的方法能够达到与现有竞争方法相当或更优的性能。

> Large Language Models (LLMs) excel at many NLP tasks, but struggle with multi-hop reasoning and factual consistency, limiting their effectiveness on knowledge-intensive tasks like complex question answering (QA). Linking Knowledge Graphs (KG) and LLMs has shown promising results, but LLMs generally lack the ability to reason efficiently over graph-structured information. To tackle this problem, we propose a novel retrieval approach that integrates textual knowledge graphs into the LLM reasoning process via query decomposition. Our method decomposes complex questions into sub-questions, retrieves relevant textual subgraphs, and composes a question-specific knowledge graph to guide answer generation. For that, we use a weighted similarity function that focuses on both the complex question and the generated subquestions to extract a relevant subgraph, which allows efficient and precise retrieval for complex questions and improves the performance of LLMs on multi-hop QA tasks. This structured reasoning pipeline enhances factual grounding and interpretability while leveraging the generative strengths of LLMs. We evaluate our method on standard multi-hop QA benchmarks and show that it achieves comparable or superior performance to competitive existing methods, using smaller models and fewer LLM calls.

[Arxiv](https://arxiv.org/abs/2506.13380)