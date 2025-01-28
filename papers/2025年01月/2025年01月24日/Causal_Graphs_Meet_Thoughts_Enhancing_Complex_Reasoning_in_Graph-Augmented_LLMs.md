# 因果图与思维碰撞：提升图增强型LLM的复杂推理能力

发布时间：2025年01月24日

`RAG

理由：这篇论文主要讨论了如何通过结合知识图谱和图检索增强生成（Graph RAG）来解决大型语言模型（LLMs）在知识密集型任务中的挑战。论文提出了一种新方法，通过过滤知识图谱以突出因果边，将检索过程与模型的思维链（CoT）对齐，并通过多阶段路径改进增强推理。这些内容明显属于检索增强生成（RAG）的范畴，因此将其分类为RAG。`

> Causal Graphs Meet Thoughts: Enhancing Complex Reasoning in Graph-Augmented LLMs

# 摘要

> 在知识密集型任务中，尤其是在医学和法律等高风险领域，检索相关信息并提供因果推理和可解释性至关重要。尽管大型语言模型（LLMs）在自然语言理解和生成任务中表现出色，但它们常面临融入新知识困难、生成幻觉以及推理过程难以解释等问题。为解决这些挑战，将知识图谱与图检索增强生成（Graph RAG）结合成为了一种有效方案。传统Graph RAG方法依赖简单的图遍历或语义相似性，无法捕捉因果关系或与模型的推理步骤对齐。本文提出了一种新方法，通过过滤知识图谱以突出因果边，将检索过程与模型的思维链（CoT）对齐，并通过多阶段路径改进增强推理。在医学问答任务上的实验表明，该方法在多个LLMs上实现了高达10%的性能提升。这一方法展示了因果推理与逐步检索结合的价值，为复杂查询提供了更具可解释性和逻辑基础的解决方案。

> In knowledge-intensive tasks, especially in high-stakes domains like medicine and law, it is critical not only to retrieve relevant information but also to provide causal reasoning and explainability. Large language models (LLMs) have achieved remarkable performance in natural language understanding and generation tasks. However, they often suffer from limitations such as difficulty in incorporating new knowledge, generating hallucinations, and explaining their reasoning process. To address these challenges, integrating knowledge graphs with Graph Retrieval-Augmented Generation (Graph RAG) has emerged as an effective solution. Traditional Graph RAG methods often rely on simple graph traversal or semantic similarity, which do not capture causal relationships or align well with the model's internal reasoning steps. This paper proposes a novel pipeline that filters large knowledge graphs to emphasize cause-effect edges, aligns the retrieval process with the model's chain-of-thought (CoT), and enhances reasoning through multi-stage path improvements. Experiments on medical question-answering tasks show consistent gains, with up to a 10\% absolute improvement across multiple large language models (LLMs). This approach demonstrates the value of combining causal reasoning with stepwise retrieval, leading to more interpretable and logically grounded solutions for complex queries.

[Arxiv](https://arxiv.org/abs/2501.14892)