# 大型语言模型在关联学习方面表现出色

发布时间：2025年06月06日

`LLM应用` `人工智能` `数据分析`

> Large Language Models are Good Relational Learners

# 摘要

> 大型语言模型（LLMs）在多个领域展现了卓越的能力，但在关系深度学习（RDL）中的应用潜力尚未得到充分挖掘。现有方法通过将结构化数据转换为文本文档来适配LLMs，但这种方法忽视了数据中的关系结构，导致冗余且超出模型处理范围。我们提出Rel-LLM，一种结合图神经网络（GNN）和检索增强生成（RAG）的新架构，能够有效处理复杂关系。通过提取实体间的局部关系子图，Rel-LLM构建包含时间依赖性的特征表示，并生成结构化提示供LLM推理。实验结果表明，Rel-LLM在RDL任务中表现优异，为LLMs与结构化数据的结合提供了高效解决方案。项目代码已开源。

> Large language models (LLMs) have demonstrated remarkable capabilities across various domains, yet their application to relational deep learning (RDL) remains underexplored. Existing approaches adapt LLMs by traversing relational links between entities in a database and converting the structured data into flat text documents. Still, this text-based serialization disregards critical relational structures, introduces redundancy, and often exceeds standard LLM context lengths. We introduce Rel-LLM, a novel architecture that utilizes a graph neural network (GNN)- based encoder to generate structured relational prompts for LLMs within a retrieval-augmented generation (RAG) framework. Unlike traditional text-based serialization approaches, our method preserves the inherent relational structure of databases while enabling LLMs to effectively process and reason over complex entity relationships. Specifically, the GNN encoder extracts a local subgraph around an entity to build feature representations that contain relevant entity relationships and temporal dependencies. These representations are transformed into structured prompts using a denormalization process, effectively allowing the LLM to reason over relational structures. Through extensive experiments, we demonstrate that Rel-LLM outperforms existing methods on key RDL tasks, offering a scalable and efficient approach to integrating LLMs with structured data sources. Code is available at https://github.com/smiles724/Rel-LLM.

[Arxiv](https://arxiv.org/abs/2506.05725)