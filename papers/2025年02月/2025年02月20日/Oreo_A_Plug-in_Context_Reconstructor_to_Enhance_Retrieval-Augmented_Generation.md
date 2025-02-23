# Oreo：一款增强检索增强生成的插件式上下文重构器

发布时间：2025年02月20日

`RAG

理由：这篇论文专注于检索增强生成（RAG）方法，探讨如何优化外部知识源以提升生成效果，属于RAG的具体应用与改进。` `NLP` `信息检索`

> Oreo: A Plug-in Context Reconstructor to Enhance Retrieval-Augmented Generation

# 摘要

> 大型语言模型（LLMs）在NLP任务中表现卓越，但受限于其参数化知识和领域专业性的不足，仍易出现幻觉。为解决这一问题，检索增强生成（RAG）通过整合外部文档检索来扩充LLMs的知识库。具体而言，RAG根据查询从外部语料库中检索文档片段，并将其作为下游语言模型生成答案的上下文。然而，检索到的知识来源常包含不相关或错误信息，影响了RAG在下游任务中的效果。为克服这一限制，我们提出了一种紧凑、高效且可插拔的模块，用于优化外部知识源。该模块通过提取最相关和支持的信息并进行重构，将其组织成简洁且与查询相关的格式。通过监督微调、对比多任务学习以及基于强化学习的对齐这三阶段训练范式，该模块优先考虑关键知识并使其与生成器的偏好保持一致。这种方法使LLMs能够生成更准确、可靠且语境恰当的输出。

> Despite the remarkable capabilities of Large Language Models (LLMs) in various NLP tasks, they remain vulnerable to hallucinations due to their limited parametric knowledge and lack of domain-specific expertise. Retrieval-Augmented Generation (RAG) addresses this challenge by incorporating external document retrieval to augment the knowledge base of LLMs. In this approach, RAG retrieves document chunks from an external corpus in response to a query, which are then used as context for the downstream language model to generate an answer. However, these retrieved knowledge sources often include irrelevant or erroneous information, undermining the effectiveness of RAG in downstream tasks. To overcome this limitation, we introduce a compact, efficient, and pluggable module designed to refine external knowledge sources before feeding them to the generator. The module reconstructs retrieved content by extracting the most relevant and supportive information and reorganising it into a concise, query-specific format. Through a three-stage training paradigm - comprising supervised fine-tuning, contrastive multi-task learning, and reinforcement learning-based alignment - it prioritises critical knowledge and aligns it with the generator's preferences. This method enables LLMs to produce outputs that are more accurate, reliable, and contextually appropriate.

[Arxiv](https://arxiv.org/abs/2502.13019)