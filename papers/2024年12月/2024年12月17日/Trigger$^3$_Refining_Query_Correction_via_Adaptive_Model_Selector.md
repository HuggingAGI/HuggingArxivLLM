# Trigger$^3$: 借助自适应模型选择器优化查询校正

发布时间：2024年12月17日

`LLM应用` `查询校正`

> Trigger$^3$: Refining Query Correction via Adaptive Model Selector

# 摘要

> 在搜索场景中，因拼写错误、语音失误或知识短板导致的错误查询，可能会影响用户体验。所以，查询校正对搜索引擎而言至关重要。当下的校正模型，往往是基于特定数据训练的小型模型，在应对超出训练范畴或需要结合上下文理解的查询时，常常力不从心。尽管大型语言模型（LLMs）的出现带来了潜在的解决办法，但其仍受预训练数据和推理成本的制约，特别是面对复杂查询时，并非总能有效地进行查询校正。为应对这些情况，我们提出了 Trigger$^3$ ，这是一个大小模型协作的框架，将传统校正模型与 LLM 相融合用于查询校正，能够依据查询以及传统校正模型和 LLM 的校正结果，自适应地选取恰当的校正方法。Trigger$^3$ 首先运用校正触发器筛除正确的查询。不正确的查询接着由传统校正模型校正。若此方法无效，则激活 LLM 触发器，调用 LLM 进行校正。最后，对于任何模型都无法校正的查询，回退触发器决定返回原始查询。大量实验表明，Trigger$^3$ 在保持效率的同时，表现优于校正基线。

> In search scenarios, user experience can be hindered by erroneous queries due to typos, voice errors, or knowledge gaps. Therefore, query correction is crucial for search engines. Current correction models, usually small models trained on specific data, often struggle with queries beyond their training scope or those requiring contextual understanding. While the advent of Large Language Models (LLMs) offers a potential solution, they are still limited by their pre-training data and inference cost, particularly for complex queries, making them not always effective for query correction. To tackle these, we propose Trigger$^3$, a large-small model collaboration framework that integrates the traditional correction model and LLM for query correction, capable of adaptively choosing the appropriate correction method based on the query and the correction results from the traditional correction model and LLM. Trigger$^3$ first employs a correction trigger to filter out correct queries. Incorrect queries are then corrected by the traditional correction model. If this fails, an LLM trigger is activated to call the LLM for correction. Finally, for queries that no model can correct, a fallback trigger decides to return the original query. Extensive experiments demonstrate Trigger$^3$ outperforms correction baselines while maintaining efficiency.

[Arxiv](https://arxiv.org/abs/2412.12701)