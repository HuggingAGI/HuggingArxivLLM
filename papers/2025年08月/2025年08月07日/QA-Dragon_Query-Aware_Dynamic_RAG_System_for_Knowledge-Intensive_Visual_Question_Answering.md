# QA-Dragon：针对知识密集型视觉问答的基于查询感知的动态RAG系统。

发布时间：2025年08月07日

`RAG` `视觉问答` `多模态处理`

> QA-Dragon: Query-Aware Dynamic RAG System for Knowledge-Intensive Visual Question Answering

# 摘要

> 检索增强生成（RAG）通过引入外部知识到生成过程，有效缓解了多模态大型语言模型（MLLMs）中的幻觉问题，成为知识密集型视觉问答（VQA）的主流方法。然而，现有RAG方法通常孤立地从文本或图像中检索信息，限制了其处理复杂查询的能力，尤其是那些需要多跳推理或最新事实知识的任务。为解决这一问题，我们提出了QA-Dragon，一个面向知识密集型VQA的查询感知动态RAG系统。该系统通过领域路由器识别查询的主题领域，结合动态选择最优检索策略的搜索路由器，实现了多模态、多轮和多跳推理的支持。在2025年KDD杯Meta CRAG-MM挑战赛中，QA-Dragon显著提升了基础模型在复杂场景下的推理性能。我们的框架在答案准确性和知识重叠分数方面均取得了显著提升，分别在单源任务上比基线高出5.06%，多源任务上高出6.35%，以及多轮任务上高出5.03%。

> Retrieval-Augmented Generation (RAG) has been introduced to mitigate hallucinations in Multimodal Large Language Models (MLLMs) by incorporating external knowledge into the generation process, and it has become a widely adopted approach for knowledge-intensive Visual Question Answering (VQA). However, existing RAG methods typically retrieve from either text or images in isolation, limiting their ability to address complex queries that require multi-hop reasoning or up-to-date factual knowledge. To address this limitation, we propose QA-Dragon, a Query-Aware Dynamic RAG System for Knowledge-Intensive VQA. Specifically, QA-Dragon introduces a domain router to identify the query's subject domain for domain-specific reasoning, along with a search router that dynamically selects optimal retrieval strategies. By orchestrating both text and image search agents in a hybrid setup, our system supports multimodal, multi-turn, and multi-hop reasoning, enabling it to tackle complex VQA tasks effectively. We evaluate our QA-Dragon on the Meta CRAG-MM Challenge at KDD Cup 2025, where it significantly enhances the reasoning performance of base models under challenging scenarios. Our framework achieves substantial improvements in both answer accuracy and knowledge overlap scores, outperforming baselines by 5.06% on the single-source task, 6.35% on the multi-source task, and 5.03% on the multi-turn task.

[Arxiv](https://arxiv.org/abs/2508.05197)