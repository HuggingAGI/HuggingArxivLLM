# 融合相关性与推理：检索增强生成中的原理提炼

发布时间：2024年12月11日

`RAG`

> Bridging Relevance and Reasoning: Rationale Distillation in Retrieval-Augmented Generation

# 摘要

> 重排序器和生成器是检索增强生成（即 RAG）流程中的两大关键组成部分，负责相关文档的排序和响应的生成。然而，由于预训练数据和目标存在差异，重排序器认定的相关文档与生成器回答查询所需的文档之间，不可避免地存在差距。为了弥补这一差距，我们提出了 RADIO，这是一个具备原理蒸馏的新颖且实用的偏好对齐框架。具体而言，我们首先提出了一种原理提取方法，借助大型语言模型（LLMs）的推理能力，提取回答查询所需的原理。接着，设计了基于原理的对齐流程，依据提取的原理对文档重新排序，并对重排序器进行微调以实现偏好对齐。我们在三个数据集的两项任务上开展了大量实验，以证明我们的方法相较于基线方法的有效性。我们的代码已在线发布，便于重现。

> The reranker and generator are two critical components in the Retrieval-Augmented Generation (i.e., RAG) pipeline, responsible for ranking relevant documents and generating responses. However, due to differences in pre-training data and objectives, there is an inevitable gap between the documents ranked as relevant by the reranker and those required by the generator to support answering the query. To address this gap, we propose RADIO, a novel and practical preference alignment framework with RAtionale DIstillatiOn. Specifically, We first propose a rationale extraction method that leverages the reasoning capabilities of Large Language Models (LLMs) to extract the rationales necessary for answering the query. Subsequently, a rationale-based alignment process is designed to rerank the documents based on the extracted rationales, and fine-tune the reranker to align the preferences. We conduct extensive experiments on two tasks across three datasets to demonstrate the effectiveness of our approach compared to baseline methods. Our code is released online to ease reproduction.

[Arxiv](https://arxiv.org/abs/2412.08519)