# OG-RAG: 本体驱动的检索增强生成技术应用于大型语言模型

发布时间：2024年12月11日

`RAG

理由：这篇论文提出了一种基于本体论的检索增强生成方法（OG-RAG），旨在通过将检索过程锚定在特定领域的本体论中，提升LLM生成的响应质量。该方法通过构建领域文档的超图表示，并利用优化算法检索最小超边集，为LLM构建精确且概念化的上下文。这种方法明显属于检索增强生成（RAG）的范畴，因为它结合了检索和生成的过程，以提高LLM在特定领域任务中的表现。` `医疗保健`

> OG-RAG: Ontology-Grounded Retrieval-Augmented Generation For Large Language Models

# 摘要

> # 摘要
本文提出了一种基于本体论的检索增强生成方法——OG-RAG，旨在通过将检索过程锚定在特定领域的本体论中，提升LLM生成的响应质量。尽管LLM在问答和搜索等任务中表现优异，但在缺乏昂贵微调或次优检索方法的情况下，它们难以适应工业工作流程或知识工作等专业知识。现有的检索增强模型（如RAG）虽有所改进，但未能充分利用结构化领域知识，导致上下文生成效果不佳。本体论通过定义实体及其相互关系，为领域知识提供了结构化表示，填补了这一空白。OG-RAG构建了领域文档的超图表示，每个超边封装了基于特定领域本体论的事实知识集群。优化算法随后检索最小超边集，为LLM构建精确且概念化的上下文。这种方法在保持实体间复杂关系的同时，实现了高效检索。OG-RAG适用于基于事实推理至关重要的领域，特别是在需要遵循预定义规则和程序的工作流程或决策步骤中，如医疗保健、法律和农业领域的工业工作流程，以及新闻、调查性研究、咨询等知识驱动任务。我们的评估显示，OG-RAG在四种不同LLM中将准确事实的召回率提升了55%，响应正确性提高了40%。此外，与基线方法相比，OG-RAG使响应归因于上下文的速度提升了30%，基于事实的推理准确性提高了27%。

> This paper presents OG-RAG, an Ontology-Grounded Retrieval Augmented Generation method designed to enhance LLM-generated responses by anchoring retrieval processes in domain-specific ontologies. While LLMs are widely used for tasks like question answering and search, they struggle to adapt to specialized knowledge, such as industrial workflows or knowledge work, without expensive fine-tuning or sub-optimal retrieval methods. Existing retrieval-augmented models, such as RAG, offer improvements but fail to account for structured domain knowledge, leading to suboptimal context generation. Ontologies, which conceptually organize domain knowledge by defining entities and their interrelationships, offer a structured representation to address this gap. OG-RAG constructs a hypergraph representation of domain documents, where each hyperedge encapsulates clusters of factual knowledge grounded using domain-specific ontology. An optimization algorithm then retrieves the minimal set of hyperedges that constructs a precise, conceptually grounded context for the LLM. This method enables efficient retrieval while preserving the complex relationships between entities. OG-RAG applies to domains where fact-based reasoning is essential, particularly in tasks that require workflows or decision-making steps to follow predefined rules and procedures. These include industrial workflows in healthcare, legal, and agricultural sectors, as well as knowledge-driven tasks such as news journalism, investigative research, consulting and more. Our evaluations demonstrate that OG-RAG increases the recall of accurate facts by 55% and improves response correctness by 40% across four different LLMs. Additionally, OG-RAG enables 30% faster attribution of responses to context and boosts fact-based reasoning accuracy by 27% compared to baseline methods.

[Arxiv](https://arxiv.org/abs/2412.15235)