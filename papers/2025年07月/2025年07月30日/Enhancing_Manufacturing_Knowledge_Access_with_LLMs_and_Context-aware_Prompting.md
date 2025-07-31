# LLMs与上下文感知提示：提升制造业知识获取能力

发布时间：2025年07月30日

`LLM应用` `制造业` `知识图谱`

> Enhancing Manufacturing Knowledge Access with LLMs and Context-aware Prompting

# 摘要

> 知识图谱（KGs）正在改变制造业的数据管理格局，通过共享和结构化的概念模式，为整合分散的数据源提供了有效手段。然而，对于非专业人士而言，驾驭知识图谱并非易事，因为检索特定信息通常需要编写复杂的SPARQL查询。随着大型语言模型（LLMs）的崛起，自动将自然语言查询转换为SPARQL格式的潜力逐渐显现，从而架起了用户友好界面与知识图谱复杂架构之间的桥梁。然而，如何有效向LLMs传达特定领域知识图谱的相关背景和结构，例如在制造业中，仍然是一个挑战，这将有助于提升生成查询的准确性。

在本文中，我们评估了多种策略，这些策略将LLMs作为中介，以促进从知识图谱中检索信息。我们专注于制造业领域，特别是Bosch生产线信息系统的知识图谱和I40核心信息模型。在我们的评估中，我们比较了将知识图谱的相关背景信息输入LLMs的各种方法，并分析了它们在将现实世界问题转化为SPARQL查询方面的表现。我们的研究发现，当仅向LLMs提供知识图谱模式的适当背景时，它们在生成正确和完整查询方面的性能可以得到显著提升。

这种基于上下文的提示技术帮助LLMs专注于本体的相关部分，并降低幻觉的风险。我们预计，所提出的这些技术将帮助LLMs democratize对复杂数据仓库的访问，并赋能制造业环境中的明智决策。

> Knowledge graphs (KGs) have transformed data management within the manufacturing industry, offering effective means for integrating disparate data sources through shared and structured conceptual schemas. However, harnessing the power of KGs can be daunting for non-experts, as it often requires formulating complex SPARQL queries to retrieve specific information. With the advent of Large Language Models (LLMs), there is a growing potential to automatically translate natural language queries into the SPARQL format, thus bridging the gap between user-friendly interfaces and the sophisticated architecture of KGs. The challenge remains in adequately informing LLMs about the relevant context and structure of domain-specific KGs, e.g., in manufacturing, to improve the accuracy of generated queries. In this paper, we evaluate multiple strategies that use LLMs as mediators to facilitate information retrieval from KGs. We focus on the manufacturing domain, particularly on the Bosch Line Information System KG and the I40 Core Information Model. In our evaluation, we compare various approaches for feeding relevant context from the KG to the LLM and analyze their proficiency in transforming real-world questions into SPARQL queries. Our findings show that LLMs can significantly improve their performance on generating correct and complete queries when provided only the adequate context of the KG schema. Such context-aware prompting techniques help LLMs to focus on the relevant parts of the ontology and reduce the risk of hallucination. We anticipate that the proposed techniques help LLMs to democratize access to complex data repositories and empower informed decision-making in manufacturing settings.

[Arxiv](https://arxiv.org/abs/2507.22619)