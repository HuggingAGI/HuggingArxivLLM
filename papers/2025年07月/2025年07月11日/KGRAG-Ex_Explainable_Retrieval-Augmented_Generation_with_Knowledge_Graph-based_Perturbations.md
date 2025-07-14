# KGRAG-Ex：基于知识图谱扰动的可解释检索增强生成

发布时间：2025年07月11日

`RAG` `知识图谱` `问答系统`

> KGRAG-Ex: Explainable Retrieval-Augmented Generation with Knowledge Graph-based Perturbations

# 摘要

> 检索增强生成（RAG）通过将外部信息作为响应基础来提升语言模型，但解释性仍然是一个关键挑战，尤其是在依赖非结构化文本检索时。知识图谱（KGs）通过引入结构化、语义丰富的实体及其关系表示，提供了解决方案，实现了透明的检索路径和可解释的推理。在本研究中，我们提出了KGRAG-Ex，这是一个RAG系统，通过利用基于提示的信息抽取构建的领域特定知识图谱，提升了事实依据和解释性。针对用户查询，KGRAG-Ex在图中识别相关实体和语义路径，随后将其转换为伪段落：对图子结构的自然语言表示，用于引导语料库检索。为了提高可解释性和支持推理透明度，我们引入了基于扰动的解释方法，评估特定知识图谱衍生组件对生成答案的影响。我们进行了一系列实验，分析系统对不同扰动方法的敏感性，图组件重要性与其结构位置的关系，语义节点类型的影响，以及图度量如何与解释过程中组件的影响相对应。

> Retrieval-Augmented Generation (RAG) enhances language models by grounding responses in external information, yet explainability remains a critical challenge, particularly when retrieval relies on unstructured text. Knowledge graphs (KGs) offer a solution by introducing structured, semantically rich representations of entities and their relationships, enabling transparent retrieval paths and interpretable reasoning. In this work, we present KGRAG-Ex, a RAG system that improves both factual grounding and explainability by leveraging a domain-specific KG constructed via prompt-based information extraction. Given a user query, KGRAG-Ex identifies relevant entities and semantic paths in the graph, which are then transformed into pseudo-paragraphs: natural language representations of graph substructures that guide corpus retrieval. To improve interpretability and support reasoning transparency, we incorporate perturbation-based explanation methods that assess the influence of specific KG-derived components on the generated answers. We conduct a series of experiments to analyze the sensitivity of the system to different perturbation methods, the relationship between graph component importance and their structural positions, the influence of semantic node types, and how graph metrics correspond to the influence of components within the explanations process.

[Arxiv](https://arxiv.org/abs/2507.08443)