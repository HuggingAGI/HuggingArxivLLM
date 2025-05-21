# Q²Forge：生成能力问题与SPARQL查询，助力知识图谱问答系统

发布时间：2025年05月19日

`LLM应用

<example>
论文摘要：将文本信息表示为实数嵌入已成为 NLP 的规范。此外，随着公众对大型语言模型 (LLM) 兴趣的增加，嵌入即服务 (EaaS) 作为一种商业模式迅速受到关注。这并非没有突出的安全风险，因为之前的研究已经证明，即使不了解生成敏感数据的底层模型，也可以从嵌入中重建敏感数据。然而，此类工作因其仅关注英语而受到限制，使得所有其他语言都容易受到恶意行为者的攻击。由于许多国际和多语言公司利用 EaaS，迫切需要研究多语言 LLM 安全性。为此，本工作从多语言嵌入反转的角度研究LLM安全性。具体来说，我们定义了黑盒多语言和跨语言反转攻击问题，特别关注跨域场景。我们的研究结果表明，多语言模型可能比单语言模型更容易受到反转攻击。这是因为在底层语言事先未知的情况下，实现可比较的反演性能所需的数据量减少了。据我们所知，这项工作是第一个在反转攻击的背景下深入研究多语言性的工作，我们的发现强调了在 NLP 安全领域进一步调查和加强防御的必要性。
LLM应用
</example>

论文摘要：SPARQL查询语言是访问知识图谱（KGs）的标准方法。然而，编写SPARQL查询对非专家用户来说是一项重大挑战，即使是经验丰富的用户，这一过程仍然耗时费力。最佳实践建议通过能力问题和示例查询来记录KGs，以便为所包含的知识提供上下文，并展示其潜在应用。然而，在实际操作中，这种情况要么不存在，要么提供的示例数量非常有限。大语言模型（LLMs）正在被应用于对话式智能体，并且在从常见知识的简单问答到特定编程语言的代码生成等广泛的应用中展现出吸引力。然而，要训练和测试这些模型，使其能够从自然语言问题生成高质量的SPARQL查询，需要大量包含问题-查询对的数据集。本文中，我们介绍了Q${}^2$Forge，它能够解决为KG生成新的能力问题及其对应的SPARQL查询的挑战。该工具通过人工反馈和LLM作为评估者，对这些查询进行迭代验证。Q${}^2$Forge是开源的、通用的、可扩展且模块化的，这意味着应用的不同模块（CQ生成、查询生成和查询优化）可以单独使用，作为集成管道使用，或被其他服务替代。最终，它提供了一个从能力问题制定到查询评估的完整管道，支持为任何目标KG创建参考查询集。
LLM应用` `知识图谱` `数据查询`

> Q${}^2$Forge: Minting Competency Questions and SPARQL Queries for Question-Answering Over Knowledge Graphs

# 摘要

> SPARQL查询语言是访问知识图谱（KGs）的标准方法。然而，编写SPARQL查询对非专家用户来说是一项重大挑战，即使是经验丰富的用户，这一过程仍然耗时费力。最佳实践建议通过能力问题和示例查询来记录KGs，以便为所包含的知识提供上下文，并展示其潜在应用。然而，在实际操作中，这种情况要么不存在，要么提供的示例数量非常有限。大语言模型（LLMs）正在被应用于对话式智能体，并且在从常见知识的简单问答到特定编程语言的代码生成等广泛的应用中展现出吸引力。然而，要训练和测试这些模型，使其能够从自然语言问题生成高质量的SPARQL查询，需要大量包含问题-查询对的数据集。本文中，我们介绍了Q${}^2$Forge，它能够解决为KG生成新的能力问题及其对应的SPARQL查询的挑战。该工具通过人工反馈和LLM作为评估者，对这些查询进行迭代验证。Q${}^2$Forge是开源的、通用的、可扩展且模块化的，这意味着应用的不同模块（CQ生成、查询生成和查询优化）可以单独使用，作为集成管道使用，或被其他服务替代。最终，它提供了一个从能力问题制定到查询评估的完整管道，支持为任何目标KG创建参考查询集。

> The SPARQL query language is the standard method to access knowledge graphs (KGs). However, formulating SPARQL queries is a significant challenge for non-expert users, and remains time-consuming for the experienced ones. Best practices recommend to document KGs with competency questions and example queries to contextualise the knowledge they contain and illustrate their potential applications. In practice, however, this is either not the case or the examples are provided in limited numbers. Large Language Models (LLMs) are being used in conversational agents and are proving to be an attractive solution with a wide range of applications, from simple question-answering about common knowledge to generating code in a targeted programming language. However, training and testing these models to produce high quality SPARQL queries from natural language questions requires substantial datasets of question-query pairs. In this paper, we present Q${}^2$Forge that addresses the challenge of generating new competency questions for a KG and corresponding SPARQL queries. It iteratively validates those queries with human feedback and LLM as a judge. Q${}^2$Forge is open source, generic, extensible and modular, meaning that the different modules of the application (CQ generation, query generation and query refinement) can be used separately, as an integrated pipeline, or replaced by alternative services. The result is a complete pipeline from competency question formulation to query evaluation, supporting the creation of reference query sets for any target KG.

[Arxiv](https://arxiv.org/abs/2505.13572)