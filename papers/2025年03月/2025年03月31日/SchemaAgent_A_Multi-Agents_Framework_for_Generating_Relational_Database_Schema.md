# SchemaAgent：一个生成关系型数据库模式的多智能体系统

发布时间：2025年03月31日

`LLM应用

理由：这篇论文主要探讨了如何将大型语言模型（LLMs）应用于数据库架构生成的具体任务。通过提出SchemaAgent框架，展示了LLMs在自动化数据库设计中的实际应用，属于LLM的应用层面研究。` `数据库` `软件工程`

> SchemaAgent: A Multi-Agents Framework for Generating Relational Database Schema

# 摘要

> 关系型数据库设计根据用户需求生成架构，定义表结构及其相互关系。从需求到架构的准确转化涉及多个复杂子任务，需要数据库专业知识和特定领域知识。这对关系型数据库的自动化设计提出了独特挑战。现有方法多基于定制规则或传统深度学习模型，生成的架构往往不够理想。最近，大型语言模型（LLMs）在智能应用开发方面取得了显著进展。本文提出SchemaAgent，一个基于LLM的统一多智能体框架，用于自动生成高质量数据库架构。SchemaAgent首次将LLMs应用于架构生成，通过为智能体分配专门角色并促进协作，模拟手动设计流程以优化子任务。架构生成流程中，直接应用多智能体框架可能导致错误累积。为此，我们引入反思和检查角色，并设计创新的错误检测与纠正机制，跨阶段识别并修复问题。为评估，我们构建了包含500多对需求描述与架构的	extit{RSchema}基准。实验结果表明，与主流LLMs相比，SchemaAgent在关系型数据库架构生成方面具有显著优势。

> The relational database design would output a schema based on user's requirements, which defines table structures and their interrelated relations. Translating requirements into accurate schema involves several non-trivial subtasks demanding both database expertise and domain-specific knowledge. This poses unique challenges for automated design of relational databases. Existing efforts are mostly based on customized rules or conventional deep learning models, often producing suboptimal schema. Recently, large language models (LLMs) have significantly advanced intelligent application development across various domains. In this paper, we propose SchemaAgent, a unified LLM-based multi-agent framework for the automated generation of high-quality database schema. SchemaAgent is the first to apply LLMs for schema generation, which emulates the workflow of manual schema design by assigning specialized roles to agents and enabling effective collaboration to refine their respective subtasks. Schema generation is a streamlined workflow, where directly applying the multi-agent framework may cause compounding impact of errors. To address this, we incorporate dedicated roles for reflection and inspection, alongside an innovative error detection and correction mechanism to identify and rectify issues across various phases. For evaluation, we present a benchmark named \textit{RSchema}, which contains more than 500 pairs of requirement description and schema. Experimental results on this benchmark demonstrate the superiority of our approach over mainstream LLMs for relational database schema generation.

[Arxiv](https://arxiv.org/abs/2503.23886)