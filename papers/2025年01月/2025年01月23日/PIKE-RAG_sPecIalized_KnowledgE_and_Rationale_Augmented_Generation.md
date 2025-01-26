# PIKE-RAG: 专业知识与推理增强生成

发布时间：2025年01月23日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）系统的改进，提出了专门知识和推理增强生成（PIKE-RAG）方法，专注于提取、理解和应用专门知识，并构建连贯的推理。论文还引入了新的范式来分类任务，并提出了知识原子化和知识感知任务分解的方法。这些内容都与RAG系统的改进和应用密切相关，因此将其分类为RAG是合适的。` `知识管理`

> PIKE-RAG: sPecIalized KnowledgE and Rationale Augmented Generation

# 摘要

> 尽管检索增强生成（RAG）系统通过外部检索扩展了LLM的能力，并取得了显著进展，但这些系统往往难以应对现实工业应用中复杂多样的需求。仅依赖检索无法从专业语料库中提取深层次的领域知识，也无法在逻辑推理中表现出色。为此，我们提出了专门知识和推理增强生成（PIKE-RAG），专注于提取、理解和应用专门知识，同时构建连贯的推理，逐步引导LLM生成准确响应。针对工业任务的多样化挑战，我们引入了一种新范式，根据知识提取和应用的复杂性对任务进行分类，从而系统评估RAG系统的问题解决能力。这一策略为RAG系统的分阶段开发和增强提供了路线图，以满足工业应用的动态需求。此外，我们提出了知识原子化和知识感知任务分解，分别从数据块中提取多维度知识，并基于原始查询和累积知识迭代构建推理，展示了在多个基准测试中的卓越表现。

> Despite notable advancements in Retrieval-Augmented Generation (RAG) systems that expand large language model (LLM) capabilities through external retrieval, these systems often struggle to meet the complex and diverse needs of real-world industrial applications. The reliance on retrieval alone proves insufficient for extracting deep, domain-specific knowledge performing in logical reasoning from specialized corpora. To address this, we introduce sPecIalized KnowledgE and Rationale Augmentation Generation (PIKE-RAG), focusing on extracting, understanding, and applying specialized knowledge, while constructing coherent rationale to incrementally steer LLMs toward accurate responses. Recognizing the diverse challenges of industrial tasks, we introduce a new paradigm that classifies tasks based on their complexity in knowledge extraction and application, allowing for a systematic evaluation of RAG systems' problem-solving capabilities. This strategic approach offers a roadmap for the phased development and enhancement of RAG systems, tailored to meet the evolving demands of industrial applications. Furthermore, we propose knowledge atomizing and knowledge-aware task decomposition to effectively extract multifaceted knowledge from the data chunks and iteratively construct the rationale based on original query and the accumulated knowledge, respectively, showcasing exceptional performance across various benchmarks.

[Arxiv](https://arxiv.org/abs/2501.11551)