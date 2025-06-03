# 迈向结构化知识推理：基于经验的对比检索增强生成

发布时间：2025年06月01日

`LLM应用

摘要讨论了大型语言模型在处理结构化数据时的挑战，并提出了一种名为CoRE的框架来改进模型在这些任务中的表现。这属于将LLMs应用于特定任务的范畴，因此归类为LLM应用。` `数据处理` `数据管理`

> Toward Structured Knowledge Reasoning: Contrastive Retrieval-Augmented Generation on Experience

# 摘要

> 大型语言模型（LLMs）在纯文本任务中表现出色，但面对表格和数据库等结构化数据时却力不从心。这可能源于其在预训练过程中对结构化数据的接触不足，以及 rigid 的文本到结构转换机制。与人类能够无缝地将学习到的模式应用于不同数据模态不同，LLMs 在没有明确结构指导的情况下，难以推断出表格格式中蕴含的隐含关系。为了弥合这一认知差距，我们提出了一种名为 CoRE（经验增强对比检索生成）的框架。该框架通过构建经验记忆表示，并利用对比式 In-Context Learning（ICL）增强泛化能力，以模拟人类知识的迁移。在 Text-to-SQL 和 TableQA 任务上的实验表明，CoRE 显著提升了性能，平均提升了 3.44% 和 4.24%，在具有挑战性的任务上甚至提升了 17.2%。我们的基于蒙特卡洛树搜索（MCTS）生成的经验记忆将训练数据扩展了 8-9 倍，增强了多样性和领域覆盖。这一无需额外训练且支持持续学习的方法，推动了 LLMs 向结构化知识专家迈进。

> Large language models (LLMs) achieve strong performance on plain text tasks but underperform on structured data like tables and databases. Potential challenges arise from their underexposure during pre-training and rigid text-to-structure transfer mechanisms. Unlike humans who seamlessly apply learned patterns across data modalities, LLMs struggle to infer implicit relationships embedded in tabular formats, especially in the absence of explicit structural guidance. To bridge this cognitive gap, we introduce Contrastive Retrieval-Augmented Generation on Experience (CoRE), a framework that builds experience memory representations and enhances generalization through contrastive In-Context Learning (ICL) to simulate human-like knowledge transfer. Experiments on Text-to-SQL and TableQA show CoRE significantly improves performance, achieving average gains of 3.44% and 4.24%, with up to 17.2% on challenging tasks. Our Monte Carlo Tree Search (MCTS)-generated Experience Memory expands training data 8-9x, enhancing diversity and domain coverage. This training-free and continual method propels LLMs toward structured knowledge expertise.

[Arxiv](https://arxiv.org/abs/2506.00842)