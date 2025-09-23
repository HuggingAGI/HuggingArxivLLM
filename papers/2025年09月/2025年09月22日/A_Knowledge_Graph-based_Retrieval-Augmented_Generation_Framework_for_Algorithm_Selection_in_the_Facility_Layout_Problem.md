# 基于知识图谱的检索增强生成框架：面向设施布局问题的算法选择

发布时间：2025年09月22日

`RAG` `工业与制造`

> A Knowledge Graph-based Retrieval-Augmented Generation Framework for Algorithm Selection in the Facility Layout Problem

# 摘要

> 设施布局问题（FLP）是一类涉及多目标权衡的NP难优化问题，为其选择求解算法需要深厚的专家知识，这项任务十分复杂。特定算法的性能取决于问题的具体特征，如规模、目标和约束条件。因此，自动化设计系统亟需一种数据驱动的推荐方法来指导算法选择。本文提出了一种新的推荐方法，旨在让这类专业知识触手可及，该方法基于知识图谱的检索增强生成（KG RAG）框架。为此，我们从已发表文献中构建了一个领域特定知识图谱。该方法随后采用多维度检索机制，通过三种不同方式从知识图谱中收集相关证据：精确的图搜索、灵活的向量搜索以及高层的聚类搜索。检索到的证据随后由大型语言模型（LLM）处理，生成具备数据驱动推理的算法推荐。在一系列多样化的真实FLP测试案例中，我们将所提KG-RAG方法与可访问表格形式知识库的商业LLM聊天机器人进行了对比。结果显示，在推荐准确率和推理能力方面，所提方法的表现显著优于商业LLM聊天机器人。

> Selecting a solution algorithm for the Facility Layout Problem (FLP), an NP-hard optimization problem with a multiobjective trade-off, is a complex task that requires deep expert knowledge. The performance of a given algorithm depends on specific problem characteristics such as its scale, objectives, and constraints. This creates a need for a data-driven recommendation method to guide algorithm selection in automated design systems. This paper introduces a new recommendation method to make such expertise accessible, based on a Knowledge Graph-based Retrieval-Augmented Generation (KG RAG) framework. To address this, a domain-specific knowledge graph is constructed from published literature. The method then employs a multi-faceted retrieval mechanism to gather relevant evidence from this knowledge graph using three distinct approaches, which include a precise graph-based search, flexible vector-based search, and high-level cluster-based search. The retrieved evidence is utilized by a Large Language Model (LLM) to generate algorithm recommendations with data-driven reasoning. The proposed KG-RAG method is compared against a commercial LLM chatbot with access to the knowledge base as a table, across a series of diverse, real-world FLP test cases. Based on recommendation accuracy and reasoning capability, the proposed method performed significantly better than the commercial LLM chatbot.

[Arxiv](https://arxiv.org/abs/2509.18054)