# 迈向利用智能体RAG方法实现安全需求的自动化推导

发布时间：2025年04月15日

`RAG` `自动驾驶`

> Towards Automated Safety Requirements Derivation Using Agent-based RAG

# 摘要

> 我们研究了在自动驾驶场景中，结合大型语言模型 (LLMs) 和基于代理的检索增强生成 (RAG) 来自动推导安全需求的方法。传统方法虽然利用预训练 LLMs 辅助安全分析，但往往缺乏领域专业知识。现有的 RAG 方法虽然弥补了这一不足，但在处理复杂查询时性能下降，且难以高效检索到最相关信息，这对安全相关应用尤为重要。本文中，我们提出了一种基于代理的 RAG 方法来推导安全需求，并证明所检索的信息与查询更加相关。我们在汽车标准文档池和 Apollo 案例研究上实现了一种基于代理的方法，作为自动驾驶感知系统的代表性示例。我们的解决方案在从 Apollo 数据中提取的安全需求问题和答案数据集上进行了测试。通过评估一组选定的 RAG 指标，我们展示了并讨论了基于代理的方法相较于默认 RAG 方法的优势。

> We study the automated derivation of safety requirements in a self-driving vehicle use case, leveraging LLMs in combination with agent-based retrieval-augmented generation. Conventional approaches that utilise pre-trained LLMs to assist in safety analyses typically lack domain-specific knowledge. Existing RAG approaches address this issue, yet their performance deteriorates when handling complex queries and it becomes increasingly harder to retrieve the most relevant information. This is particularly relevant for safety-relevant applications. In this paper, we propose the use of agent-based RAG to derive safety requirements and show that the retrieved information is more relevant to the queries. We implement an agent-based approach on a document pool of automotive standards and the Apollo case study, as a representative example of an automated driving perception system. Our solution is tested on a data set of safety requirement questions and answers, extracted from the Apollo data. Evaluating a set of selected RAG metrics, we present and discuss advantages of a agent-based approach compared to default RAG methods.

[Arxiv](https://arxiv.org/abs/2504.11243)