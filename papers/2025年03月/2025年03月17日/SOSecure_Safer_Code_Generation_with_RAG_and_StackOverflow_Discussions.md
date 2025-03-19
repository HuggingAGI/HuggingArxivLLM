# SOSecure：基于RAG与Stack Overflow讨论的更安全代码生成方案

发布时间：2025年03月17日

`RAG` `代码生成` `软件开发`

> SOSecure: Safer Code Generation with RAG and StackOverflow Discussions

# 摘要

> 大型语言模型（LLMs）在自动化代码生成领域得到了广泛应用。然而，由于其依赖的预训练数据更新频率较低，LLMs往往无法及时捕捉到新发现的安全漏洞和不断演进的安全标准，从而容易生成存在安全隐患的代码。相比之下，Stack Overflow（SO）上的开发者社区则提供了一个不断演进的知识库，其中安全漏洞通过集体专业知识被积极讨论和解决。然而，这些由社区驱动的安全见解尚未被LLMs充分挖掘。本研究提出了SOSecure——一个检索增强生成（RAG）系统，它通过利用Stack Overflow讨论中蕴含的集体安全专业知识，显著提升了LLM生成代码的安全性。我们构建了一个专注于安全的知识库，其中包含了从Stack Overflow中提取的明确识别漏洞的答案和评论。与常见的RAG应用不同，SOSecure在代码生成后被触发，用于查找识别类似代码中漏洞的讨论。这些讨论随后被整合到提示中，供LLM参考以考虑对代码进行修改。在SALLM、LLMSecEval和LMSys三个数据集上的评估结果显示，SOSecure分别实现了71.7%、91.3%和96.7%的修复率，显著优于直接对GPT-4进行提示（49.1%、56.5%和37.5%）以及多个其他基线模型。SOSecure作为一个与语言无关的补充工具，能够无缝集成到现有的LLM中，无需进行重新训练或微调，因此非常易于部署。我们的研究结果凸显了维护活跃的开发者论坛的重要性，然而随着LLM的普及，这类论坛的使用量已大幅下降。

> Large Language Models (LLMs) are widely used for automated code generation. Their reliance on infrequently updated pretraining data leaves them unaware of newly discovered vulnerabilities and evolving security standards, making them prone to producing insecure code. In contrast, developer communities on Stack Overflow (SO) provide an ever-evolving repository of knowledge, where security vulnerabilities are actively discussed and addressed through collective expertise. These community-driven insights remain largely untapped by LLMs. This paper introduces SOSecure, a Retrieval-Augmented Generation (RAG) system that leverages the collective security expertise found in SO discussions to improve the security of LLM-generated code. We build a security-focused knowledge base by extracting SO answers and comments that explicitly identify vulnerabilities. Unlike common uses of RAG, SOSecure triggers after code has been generated to find discussions that identify flaws in similar code. These are used in a prompt to an LLM to consider revising the code. Evaluation across three datasets (SALLM, LLMSecEval, and LMSys) show that SOSecure achieves strong fix rates of 71.7%, 91.3%, and 96.7% respectively, compared to prompting GPT-4 without relevant discussions (49.1%, 56.5%, and 37.5%), and outperforms multiple other baselines. SOSecure operates as a language-agnostic complement to existing LLMs, without requiring retraining or fine-tuning, making it easy to deploy. Our results underscore the importance of maintaining active developer forums, which have dropped substantially in usage with LLM adoptions.

[Arxiv](https://arxiv.org/abs/2503.13654)