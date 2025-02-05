# 利用大型语言模型增强知识图谱查询

发布时间：2025年02月03日

`RAG

理由：该论文介绍了SparqLLM框架，该框架利用检索增强生成（RAG）技术来增强知识图谱（KG）的查询能力。RAG技术结合了检索和生成模型，通过从外部知识源检索相关信息来增强生成模型的输出。论文中提到的SparqLLM框架通过ETL管道构建KGs，并利用LLM驱动的自然语言界面生成SPARQL查询，这正符合RAG技术的应用场景。因此，将该论文分类为RAG是合适的。` `工业5.0` `知识图谱`

> Augmented Knowledge Graph Querying leveraging LLMs

# 摘要

> 知识图谱（KGs）作为一种结构化、语义导向的数据表示模型，显著提升了跨领域的数据集成、推理和查询能力，尤其在工业5.0等现代场景中，人类、智能设备和生产过程数据的集成至关重要。然而，非专业用户在使用正式查询语言管理和检索KG数据时，常因技术复杂性而受限。为此，我们推出了SparqLLM框架，利用检索增强生成（RAG）技术，增强KG查询能力。SparqLLM通过ETL管道从原始数据构建KGs，并配备由大型语言模型（LLMs）驱动的自然语言界面，实现自动SPARQL查询生成。通过集成基于模板的方法作为LLM的检索上下文，SparqLLM提升了查询可靠性，减少语义错误，确保更精准高效的KG交互。此外，系统还配备了动态可视化仪表板，根据检索数据的结构自适应展示查询结果，提升用户体验。实验证明，SparqLLM在查询准确性、鲁棒性和用户友好性方面表现出色，成为访问语义数据的理想解决方案。

> Adopting Knowledge Graphs (KGs) as a structured, semantic-oriented, data representation model has significantly improved data integration, reasoning, and querying capabilities across different domains. This is especially true in modern scenarios such as Industry 5.0, in which the integration of data produced by humans, smart devices, and production processes plays a crucial role. However, the management, retrieval, and visualization of data from a KG using formal query languages can be difficult for non-expert users due to their technical complexity, thus limiting their usage inside industrial environments. For this reason, we introduce SparqLLM, a framework that utilizes a Retrieval-Augmented Generation (RAG) solution, to enhance the querying of Knowledge Graphs (KGs). SparqLLM executes the Extract, Transform, and Load (ETL) pipeline to construct KGs from raw data. It also features a natural language interface powered by Large Language Models (LLMs) to enable automatic SPARQL query generation. By integrating template-based methods as retrieved-context for the LLM, SparqLLM enhances query reliability and reduces semantic errors, ensuring more accurate and efficient KG interactions. Moreover, to improve usability, the system incorporates a dynamic visualization dashboard that adapts to the structure of the retrieved data, presenting the query results in an intuitive format. Rigorous experimental evaluations demonstrate that SparqLLM achieves high query accuracy, improved robustness, and user-friendly interaction with KGs, establishing it as a scalable solution to access semantic data.

[Arxiv](https://arxiv.org/abs/2502.01298)