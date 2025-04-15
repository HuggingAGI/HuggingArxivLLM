# CLEAR-KGQA：面向知识图谱问答的增强澄清歧义消解

发布时间：2025年04月13日

`LLM应用` `知识图谱` `问答系统`

> CLEAR-KGQA: Clarification-Enhanced Ambiguity Resolution for Knowledge Graph Question Answering

# 摘要

> 本研究聚焦于解决知识图谱问答（KGQA）中的歧义性问题。尽管近期KGQA系统在整合大型语言模型（LLMs）后取得了显著进展，但它们通常假设用户查询明确无歧义，这一假设在实际应用中往往难以成立。为克服这些限制，我们提出了一种创新性框架，通过互动式澄清动态处理实体歧义（例如区分名称相似的实体）和意图歧义（例如澄清用户查询的不同解释）。我们的方法采用贝叶斯推理机制量化查询的歧义性，并在多轮对话框架下指导LLMs决定何时以及如何向用户请求澄清。我们进一步开发了一种两阶段交互框架，其中基于LLM的用户模拟器通过模拟用户反馈实现逻辑形式的迭代优化。在WebQSP和CWQ数据集上的实验结果表明，我们的方法通过有效解决语义歧义显著提升了性能。此外，我们还贡献了一个经过精炼的消歧查询数据集，该数据集基于交互历史，旨在推动未来在这一方向的研究。

> This study addresses the challenge of ambiguity in knowledge graph question answering (KGQA). While recent KGQA systems have made significant progress, particularly with the integration of large language models (LLMs), they typically assume user queries are unambiguous, which is an assumption that rarely holds in real-world applications. To address these limitations, we propose a novel framework that dynamically handles both entity ambiguity (e.g., distinguishing between entities with similar names) and intent ambiguity (e.g., clarifying different interpretations of user queries) through interactive clarification. Our approach employs a Bayesian inference mechanism to quantify query ambiguity and guide LLMs in determining when and how to request clarification from users within a multi-turn dialogue framework. We further develop a two-agent interaction framework where an LLM-based user simulator enables iterative refinement of logical forms through simulated user feedback. Experimental results on the WebQSP and CWQ dataset demonstrate that our method significantly improves performance by effectively resolving semantic ambiguities. Additionally, we contribute a refined dataset of disambiguated queries, derived from interaction histories, to facilitate future research in this direction.

[Arxiv](https://arxiv.org/abs/2504.09665)