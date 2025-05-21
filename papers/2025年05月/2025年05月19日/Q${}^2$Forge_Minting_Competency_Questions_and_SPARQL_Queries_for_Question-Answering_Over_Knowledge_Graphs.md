# # Q²锻造：为知识图谱问答生成能力问题与SPARQL查询

发布时间：2025年05月19日

`LLM应用` `知识图谱` `问答系统`

> Q${}^2$Forge: Minting Competency Questions and SPARQL Queries for Question-Answering Over Knowledge Graphs

# 摘要

> SPARQL查询语言是访问知识图谱的标准方法，但编写SPARQL查询对非专业人士来说是一项重大挑战，即使是经验丰富的用户，这一过程也十分耗时。最佳实践建议通过能力问题和示例查询来记录知识图谱，以便为其知识提供上下文并展示其应用潜力。然而，实际情况往往不尽如人意，要么缺少这些文档，要么提供的示例数量有限。大型语言模型正在对话式智能体中得到广泛应用，并在从常识问答到代码生成等众多领域展现出巨大潜力。然而，为了使这些模型能够从自然语言问题生成高质量的SPARQL查询，需要大量问题-查询配对数据集。本文中，我们提出了Q${}^2$Forge，它能够解决为知识图谱生成新的能力问题及其对应SPARQL查询的挑战。该工具通过人类反馈和LLM作为评估器，迭代地验证这些查询。Q${}^2$Forge是开源的、通用的、可扩展且模块化的，这意味着其能力问题生成、查询生成和查询优化模块可以单独使用，也可以作为一个集成管道使用，甚至可以被其他服务替代。最终，它提供了一个从能力问题制定到查询评估的完整流程，支持为任何目标知识图谱创建参考查询集。

> The SPARQL query language is the standard method to access knowledge graphs (KGs). However, formulating SPARQL queries is a significant challenge for non-expert users, and remains time-consuming for the experienced ones. Best practices recommend to document KGs with competency questions and example queries to contextualise the knowledge they contain and illustrate their potential applications. In practice, however, this is either not the case or the examples are provided in limited numbers. Large Language Models (LLMs) are being used in conversational agents and are proving to be an attractive solution with a wide range of applications, from simple question-answering about common knowledge to generating code in a targeted programming language. However, training and testing these models to produce high quality SPARQL queries from natural language questions requires substantial datasets of question-query pairs. In this paper, we present Q${}^2$Forge that addresses the challenge of generating new competency questions for a KG and corresponding SPARQL queries. It iteratively validates those queries with human feedback and LLM as a judge. Q${}^2$Forge is open source, generic, extensible and modular, meaning that the different modules of the application (CQ generation, query generation and query refinement) can be used separately, as an integrated pipeline, or replaced by alternative services. The result is a complete pipeline from competency question formulation to query evaluation, supporting the creation of reference query sets for any target KG.

[Arxiv](https://arxiv.org/abs/2505.13572)