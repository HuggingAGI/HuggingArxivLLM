# 想象所有相关性：情景索引结合知识扩展，助力密集检索

发布时间：2025年03月29日

`RAG

摘要中提到SPIKE框架为检索增强生成（RAG）中的大型语言模型提供了有价值的上下文信息，直接关联到RAG技术的应用。` `信息检索`

> Imagine All The Relevance: Scenario-Profiled Indexing with Knowledge Expansion for Dense Retrieval

# 摘要

> 现有的密集检索模型在处理需要推理的检索任务时表现欠佳，因为它们无法捕捉到需要超越表层语义信息的隐式相关性。为了解决这一问题，我们提出了一种基于知识扩展的场景剖析索引（Scenario-Profiled Indexing with Knowledge Expansion, SPIKE），这是一种通过将文档分解为基于场景的检索单元来显式索引隐式相关性的密集检索框架。SPIKE将文档组织成场景，每个场景都封装了揭示假设信息需求与文档内容之间隐含关系所需的推理过程。SPIKE利用强大的教师大型语言模型（LLM）构建场景增强的数据集，然后将这些推理能力提炼到一个更小、更高效的场景生成器中。在推理过程中，SPIKE结合场景级相关性和文档级相关性，实现了推理感知的检索。大量实验表明，SPIKE在各种查询类型和密集检索器上都显著提升了检索性能。它还通过场景增强了用户的检索体验，并为检索增强生成（RAG）中的大型语言模型提供了有价值的上下文信息。

> Existing dense retrieval models struggle with reasoning-intensive retrieval task as they fail to capture implicit relevance that requires reasoning beyond surface-level semantic information. To address these challenges, we propose Scenario-Profiled Indexing with Knowledge Expansion (SPIKE), a dense retrieval framework that explicitly indexes implicit relevance by decomposing documents into scenario-based retrieval units. SPIKE organizes documents into scenario, which encapsulates the reasoning process necessary to uncover implicit relationships between hypothetical information needs and document content. SPIKE constructs a scenario-augmented dataset using a powerful teacher large language model (LLM), then distills these reasoning capabilities into a smaller, efficient scenario generator. During inference, SPIKE incorporates scenario-level relevance alongside document-level relevance, enabling reasoning-aware retrieval. Extensive experiments demonstrate that SPIKE consistently enhances retrieval performance across various query types and dense retrievers. It also enhances the retrieval experience for users through scenario and offers valuable contextual information for LLMs in retrieval-augmented generation (RAG).

[Arxiv](https://arxiv.org/abs/2503.23033)