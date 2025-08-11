# 无需预建图的 RAG：自适应推理结构增强的检索生成

发布时间：2025年08月08日

`RAG` `知识检索` `逻辑推理`

> You Don't Need Pre-built Graphs for RAG: Retrieval Augmented Generation with Adaptive Reasoning Structures

# 摘要

> 大型语言模型（LLMs）在处理超出其知识范围的问题时，常常会出现幻觉现象，生成事实错误的陈述。检索增强生成（RAG）通过从知识库中检索相关信息来支持推理，从而有效缓解这一问题。近年来，基于预构建图结构的方法在复杂任务中表现出色，但现有基于图的RAG（GraphRAG）方法存在两个主要问题：一是构建图结构成本高昂，导致令牌成本和更新延迟居高不下；二是预构建的图结构可能无法适应现实世界中多样化查询的逻辑需求，导致知识检索效果不佳。针对这些问题，我们提出了一种全新的	extbf{underline{Logic}}感知的	extbf{underline{R}}etrieval-	extbf{underline{A}}ugmented 	extbf{underline{G}}eneration框架（	extbf{LogicRAG}），它无需预构建图结构，而是在推理时动态提取推理结构以实现自适应检索。具体来说，LogicRAG首先将输入查询分解为一组子问题，并构建有向无环图（DAG）来建模这些子问题之间的逻辑依赖关系。为了支持连贯的多步推理，LogicRAG通过拓扑排序对图进行线性化处理，确保子问题能够以逻辑一致的顺序得到解决。此外，LogicRAG还采用了图剪枝和上下文剪枝技术，有效减少了冗余检索和无关上下文的干扰，从而大幅降低了整体令牌成本。大量实验结果表明，与现有最先进的基线方法相比，LogicRAG在性能和效率方面均实现了显著提升。

> Large language models (LLMs) often suffer from hallucination, generating factually incorrect statements when handling questions beyond their knowledge and perception. Retrieval-augmented generation (RAG) addresses this by retrieving query-relevant contexts from knowledge bases to support LLM reasoning. Recent advances leverage pre-constructed graphs to capture the relational connections among distributed documents, showing remarkable performance in complex tasks. However, existing Graph-based RAG (GraphRAG) methods rely on a costly process to transform the corpus into a graph, introducing overwhelming token cost and update latency. Moreover, real-world queries vary in type and complexity, requiring different logic structures for accurate reasoning. The pre-built graph may not align with these required structures, resulting in ineffective knowledge retrieval. To this end, we propose a \textbf{underline{Logic}}-aware \textbf{underline{R}}etrieval-\textbf{underline{A}}ugmented \textbf{underline{G}}eneration framework (\textbf{LogicRAG}) that dynamically extracts reasoning structures at inference time to guide adaptive retrieval without any pre-built graph. LogicRAG begins by decomposing the input query into a set of subproblems and constructing a directed acyclic graph (DAG) to model the logical dependencies among them. To support coherent multi-step reasoning, LogicRAG then linearizes the graph using topological sort, so that subproblems can be addressed in a logically consistent order. Besides, LogicRAG applies graph pruning to reduce redundant retrieval and uses context pruning to filter irrelevant context, significantly reducing the overall token cost. Extensive experiments demonstrate that LogicRAG achieves both superior performance and efficiency compared to state-of-the-art baselines.

[Arxiv](https://arxiv.org/abs/2508.06105)