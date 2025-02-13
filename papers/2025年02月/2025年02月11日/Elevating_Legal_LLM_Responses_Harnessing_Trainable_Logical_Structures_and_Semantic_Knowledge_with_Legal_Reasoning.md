# 提升法律LLM的回答：通过法律推理，利用可训练的逻辑结构和语义知识

发布时间：2025年02月11日

`LLM应用` `问答系统`

> Elevating Legal LLM Responses: Harnessing Trainable Logical Structures and Semantic Knowledge with Legal Reasoning

# 摘要

> 大型语言模型（LLMs）在众多领域展现出了卓越的能力，但在法律问答任务中仍存在明显不足。LLMs 生成的回答往往过于泛化，缺乏专家级法律咨询所需的逻辑具体性，且容易出现幻觉现象，提供看似正确但不可靠的答案。检索增强生成（RAG）技术为这一挑战提供了部分解决方案，但现有方法通常仅关注语义相似性，忽视了法律推理中至关重要的逻辑结构。本文提出了一种名为逻辑-语义整合模型（LSIM）的新型监督框架，旨在连接语义和逻辑连贯性。LSIM 包含三个组件：强化学习用于为每个问题预测结构化的事实-规则链，可训练的深度结构化语义模型（DSSM）通过整合语义和逻辑特征检索最相关的问题，以及通过检索内容生成最终答案的 in-context 学习。我们在一个经过自动评估指标和人工评估验证的真实法律问答数据集上进行的实验表明，与现有方法相比，LSIM 显著提高了准确性和可靠性。

> Large Language Models (LLMs) have achieved impressive results across numerous domains, yet they experience notable deficiencies in legal question-answering tasks. LLMs often generate generalized responses that lack the logical specificity required for expert legal advice and are prone to hallucination, providing answers that appear correct but are unreliable. Retrieval-Augmented Generation (RAG) techniques offer partial solutions to address this challenge, but existing approaches typically focus only on semantic similarity, neglecting the logical structure essential to legal reasoning. In this paper, we propose the Logical-Semantic Integration Model (LSIM), a novel supervised framework that bridges semantic and logical coherence. LSIM comprises three components: reinforcement learning predicts a structured fact-rule chain for each question, a trainable Deep Structured Semantic Model (DSSM) retrieves the most relevant candidate questions by integrating semantic and logical features, and in-context learning generates the final answer using the retrieved content. Our experiments on a real-world legal QA dataset-validated through both automated metrics and human evaluation-demonstrate that LSIM significantly enhances accuracy and reliability compared to existing methods.

[Arxiv](https://arxiv.org/abs/2502.07912)