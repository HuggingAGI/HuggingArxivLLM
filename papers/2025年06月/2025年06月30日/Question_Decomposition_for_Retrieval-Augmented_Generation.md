# # 检索增强生成中的问题分解

发布时间：2025年06月30日

`RAG` `问答系统` `信息检索`

> Question Decomposition for Retrieval-Augmented Generation

# 摘要

> 将大型语言模型（LLMs）与可验证的外部资料结合，是生成可靠答案的成熟策略。检索增强生成（RAG）就是这样一种方法，尤其适用于问答任务：它通过检索与问题语义相关的段落，并基于这些证据对模型进行条件控制。然而，像“2023年NVIDIA、苹果和谷歌中哪家公司的利润最高？”这样的多跳问题对RAG提出了挑战，因为相关事实通常分散在多个文档中，而不是出现在单一来源中，这让传统RAG难以获取足够信息。

为了解决这一问题，我们提出了一种结合问题分解的RAG流水线：（i）LLM将原始查询分解为子问题，（ii）为每个子问题检索段落，（iii）对合并后的候选池进行重排序以提升检索证据的覆盖范围和精度。我们发现问题分解能够有效整合互补文档，而重排序则减少了噪音并提升了生成答案前的相关段落排名。

尽管重排序本身是标准流程，但我们证明将现成的交叉编码重排序器与LLM驱动的问题分解相结合，能够弥补多跳问题中的检索缺口，并提供一种实用且可直接使用的增强方案，无需额外训练或特殊索引。我们在MultiHop-RAG和HotpotQA数据集上的评估显示，与标准RAG基线相比，我们的方法在检索（MRR@10：+36.7%）和答案准确性（F1：+11.6%）方面均有显著提升。

> Grounding large language models (LLMs) in verifiable external sources is a well-established strategy for generating reliable answers. Retrieval-augmented generation (RAG) is one such approach, particularly effective for tasks like question answering: it retrieves passages that are semantically related to the question and then conditions the model on this evidence. However, multi-hop questions, such as "Which company among NVIDIA, Apple, and Google made the biggest profit in 2023?," challenge RAG because relevant facts are often distributed across multiple documents rather than co-occurring in one source, making it difficult for standard RAG to retrieve sufficient information. To address this, we propose a RAG pipeline that incorporates question decomposition: (i) an LLM decomposes the original query into sub-questions, (ii) passages are retrieved for each sub-question, and (iii) the merged candidate pool is reranked to improve the coverage and precision of the retrieved evidence. We show that question decomposition effectively assembles complementary documents, while reranking reduces noise and promotes the most relevant passages before answer generation. Although reranking itself is standard, we show that pairing an off-the-shelf cross-encoder reranker with LLM-driven question decomposition bridges the retrieval gap on multi-hop questions and provides a practical, drop-in enhancement, without any extra training or specialized indexing. We evaluate our approach on the MultiHop-RAG and HotpotQA, showing gains in retrieval (MRR@10: +36.7%) and answer accuracy (F1: +11.6%) over standard RAG baselines.

[Arxiv](https://arxiv.org/abs/2507.00355)