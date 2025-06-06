# A Graph-Retrieval-Augmented Generation Framework Enhances Decision-Making in the Circular Economy
提出了一种基于图检索增强的生成框架，旨在提升循环经济中的决策能力。

发布时间：2025年06月01日

`RAG` `可持续制造` `循环经济`

> A Graph-Retrieval-Augmented Generation Framework Enhances Decision-Making in the Circular Economy

# 摘要

> 大型语言模型（LLMs）在可持续制造领域展现出巨大潜力，但常常生成不真实的工业代码和排放因子，影响监管和投资决策。为此，我们提出了CircuGraphRAG，这是一个基于检索增强生成（RAG）的框架，通过将LLMs的输出与循环经济领域的专用知识图谱相结合，提升其可靠性。该知识图谱连接了117,380个工业和废物实体，涵盖分类代码和GWP100排放数据，支持结构化的多跳推理。自然语言查询会被转换为SPARQL查询，通过检索验证过的子图来确保结果的准确性和可追溯性。与独立的LLMs和简单的RAG方法相比，CircuGraphRAG在单跳和多跳问答任务中表现更优，ROUGE-L F1分数达到1.0，而基线分数低于0.08。此外，它还显著提高了效率，将代表性任务的响应时间减半，并减少了16%的令牌使用量。CircuGraphRAG为循环经济规划提供了经过事实核查、符合监管要求的支持，推动了可靠、低碳的资源决策。

> Large language models (LLMs) hold promise for sustainable manufacturing, but often hallucinate industrial codes and emission factors, undermining regulatory and investment decisions. We introduce CircuGraphRAG, a retrieval-augmented generation (RAG) framework that grounds LLMs outputs in a domain-specific knowledge graph for the circular economy. This graph connects 117,380 industrial and waste entities with classification codes and GWP100 emission data, enabling structured multi-hop reasoning. Natural language queries are translated into SPARQL and verified subgraphs are retrieved to ensure accuracy and traceability. Compared with Standalone LLMs and Naive RAG, CircuGraphRAG achieves superior performance in single-hop and multi-hop question answering, with ROUGE-L F1 scores up to 1.0, while baseline scores below 0.08. It also improves efficiency, halving the response time and reducing token usage by 16% in representative tasks. CircuGraphRAG provides fact-checked, regulatory-ready support for circular economy planning, advancing reliable, low-carbon resource decision making.

[Arxiv](https://arxiv.org/abs/2506.04252)