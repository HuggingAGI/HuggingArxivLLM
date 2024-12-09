# KaLM：借助双视图知识图对比学习达成知识对齐的自回归语言建模

发布时间：2024年12月06日

`LLM应用` `知识图谱` `语言模型`

> KaLM: Knowledge-aligned Autoregressive Language Modeling via Dual-view Knowledge Graph Contrastive Learning

# 摘要

> 自回归大型语言模型（LLMs）通过下一个标记预测进行预训练，在生成任务上本就表现出色。但在知识驱动类任务（比如事实知识查询）中，其表现却差强人意。知识图谱（KGs）作为优质的结构化知识库，能为LLMs提供可靠知识，有望弥补LLMs的知识短板。让LLMs与KGs中的明确、结构化知识相匹配一直是难题；过往尝试要么无法有效匹配知识表示，要么削弱了LLMs的生成能力，致使效果欠佳。本文提出了	extbf{KaLM}，即一种	extit{知识对齐语言建模}方法，通过显式知识对齐和隐式知识对齐的联合目标来微调自回归LLMs，使其与KG知识对齐。显式知识对齐目标旨在通过双视图知识图谱对比学习直接优化LLMs的知识表示。隐式知识对齐目标着重于通过三元组完成语言建模将知识的文本模式融入LLMs。值得注意的是，我们的方法在知识驱动任务的评估中成绩斐然，特别是在基于嵌入的知识图谱完成和基于生成的知识图谱问答方面。

> Autoregressive large language models (LLMs) pre-trained by next token prediction are inherently proficient in generative tasks. However, their performance on knowledge-driven tasks such as factual knowledge querying remains unsatisfactory. Knowledge graphs (KGs), as high-quality structured knowledge bases, can provide reliable knowledge for LLMs, potentially compensating for their knowledge deficiencies. Aligning LLMs with explicit, structured knowledge from KGs has been a challenge; previous attempts either failed to effectively align knowledge representations or compromised the generative capabilities of LLMs, leading to less-than-optimal outcomes. This paper proposes \textbf{KaLM}, a \textit{Knowledge-aligned Language Modeling} approach, which fine-tunes autoregressive LLMs to align with KG knowledge via the joint objective of explicit knowledge alignment and implicit knowledge alignment. The explicit knowledge alignment objective aims to directly optimize the knowledge representation of LLMs through dual-view knowledge graph contrastive learning. The implicit knowledge alignment objective focuses on incorporating textual patterns of knowledge into LLMs through triple completion language modeling. Notably, our method achieves a significant performance boost in evaluations of knowledge-driven tasks, specifically embedding-based knowledge graph completion and generation-based knowledge graph question answering.

[Arxiv](https://arxiv.org/abs/2412.04948)