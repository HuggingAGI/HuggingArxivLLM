# Divide-Then-Align: 基于 RAG 知识边界的诚实对齐

发布时间：2025年05月27日

`RAG` `信息检索` `问答系统`

> Divide-Then-Align: Honest Alignment based on the Knowledge Boundary of RAG

# 摘要

> 大型语言模型（LLMs）结合检索系统后，通过整合外部知识来源，显著提升了自然语言处理任务的表现，使模型能够生成更准确且内容丰富的回答。为了增强这些系统在面对噪声检索时的鲁棒性，检索增强微调（RAFT）作为一种广泛应用的方法应运而生。然而，RAFT使得模型即使在缺乏可靠知识的情况下也能生成答案，这种行为在高风险领域中削弱了其可靠性，因为在这些领域中承认不确定性至关重要。为了解决这一问题，我们提出了Divide-Then-Align（DTA），这是一种后训练方法，旨在赋予RAG系统在检索内容和模型内部知识均无法满足查询需求时，能够回应"I don't know"的能力。DTA通过将数据样本划分为四个知识象限，并为每个象限构建定制的偏好数据，从而生成用于直接偏好优化（DPO）的精选数据集。在三个基准数据集上的实验结果表明，DTA能够有效平衡准确性和适当的弃权，从而提升检索增强系统的可靠性和可信度。

> Large language models (LLMs) augmented with retrieval systems have significantly advanced natural language processing tasks by integrating external knowledge sources, enabling more accurate and contextually rich responses. To improve the robustness of such systems against noisy retrievals, Retrieval-Augmented Fine-Tuning (RAFT) has emerged as a widely adopted method. However, RAFT conditions models to generate answers even in the absence of reliable knowledge. This behavior undermines their reliability in high-stakes domains, where acknowledging uncertainty is critical. To address this issue, we propose Divide-Then-Align (DTA), a post-training approach designed to endow RAG systems with the ability to respond with "I don't know" when the query is out of the knowledge boundary of both the retrieved passages and the model's internal knowledge. DTA divides data samples into four knowledge quadrants and constructs tailored preference data for each quadrant, resulting in a curated dataset for Direct Preference Optimization (DPO). Experimental results on three benchmark datasets demonstrate that DTA effectively balances accuracy with appropriate abstention, enhancing the reliability and trustworthiness of retrieval-augmented systems.

[Arxiv](https://arxiv.org/abs/2505.20871)