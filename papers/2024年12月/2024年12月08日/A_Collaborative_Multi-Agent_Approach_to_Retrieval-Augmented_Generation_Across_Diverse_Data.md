# 一种针对跨不同数据的检索增强生成的协作式多智能体方法

发布时间：2024年12月08日

`RAG` `数据库` `生成式 AI`

> A Collaborative Multi-Agent Approach to Retrieval-Augmented Generation Across Diverse Data

# 摘要

> 检索增强生成（RAG）能将外部特定领域的数据融入生成过程，从而强化大型语言模型（LLMs）。尽管 LLMs 能力出众，但常依赖静态的预训练数据集，这限制了其整合动态或私有数据的能力。传统 RAG 系统一般采用单代理架构处理查询生成、数据检索和响应合成。然而，在应对关系数据库、文档存储和图形数据库等多样数据源时，此方法效率低下，易造成性能瓶颈和准确性降低。本文提出一种多代理 RAG 系统以克服这些局限。专门的代理各自针对特定数据源进行优化，负责关系型、NoSQL 和基于文档的系统的查询生成。这些代理在模块化框架内协作，查询执行交由为兼容各类数据库类型而设计的环境。这种分布式方式能确保每个代理专注自身专门任务，从而提高查询效率、减少令牌开销、提升响应准确性。所提系统可扩展且适应性强，是需要与各种动态或私有数据源集成的生成式 AI 工作流的理想之选。借由专门代理和模块化执行环境，该系统为处理生成式 AI 应用中的复杂异构数据环境提供了高效且强大的解决方案。

> Retrieval-Augmented Generation (RAG) enhances Large Language Models (LLMs) by incorporating external, domain-specific data into the generative process. While LLMs are highly capable, they often rely on static, pre-trained datasets, limiting their ability to integrate dynamic or private data. Traditional RAG systems typically use a single-agent architecture to handle query generation, data retrieval, and response synthesis. However, this approach becomes inefficient when dealing with diverse data sources, such as relational databases, document stores, and graph databases, often leading to performance bottlenecks and reduced accuracy. This paper proposes a multi-agent RAG system to address these limitations. Specialized agents, each optimized for a specific data source, handle query generation for relational, NoSQL, and document-based systems. These agents collaborate within a modular framework, with query execution delegated to an environment designed for compatibility across various database types. This distributed approach enhances query efficiency, reduces token overhead, and improves response accuracy by ensuring that each agent focuses on its specialized task. The proposed system is scalable and adaptable, making it ideal for generative AI workflows that require integration with diverse, dynamic, or private data sources. By leveraging specialized agents and a modular execution environment, the system provides an efficient and robust solution for handling complex, heterogeneous data environments in generative AI applications.

[Arxiv](https://arxiv.org/abs/2412.05838)