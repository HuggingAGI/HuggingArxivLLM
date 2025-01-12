# 阅读与意图 -- 意图中和

发布时间：2025年01月06日

`RAG

理由：这篇论文主要讨论了RAG（Retrieval-Augmented Generation）系统在处理互联网内容时遇到的挑战，特别是上下文段落中不同语气对模型性能的影响。论文提出了一个情感翻译模型来解决这一问题，并将其应用于Reading with Intent任务。因此，这篇论文的核心内容与RAG系统的应用和改进密切相关，适合归类为RAG。` `情感分析`

> Reading with Intent -- Neutralizing Intent

# 摘要

> 对大型语言模型（LLMs）的查询通常分为指令/问题和上下文两部分。在大多数基准测试中，RAG系统的上下文来自维基百科或类似的中立、事实性文本。然而，当RAG系统检索互联网内容时，会遇到多样化的语气和语言风格，这给下游任务带来了挑战。Reading with Intent任务通过评估上下文段落中不同语气对模型性能的影响来解决这一问题。基于之前对讽刺的研究，我们通过更好的合成数据生成方法构建了一个数据集，将上下文段落转化为11种不同情感。利用该数据集，我们训练了一个情感翻译模型，系统地将段落调整为指定情感语气。人类评估显示，经过微调的情感翻译器LLM从合成数据中获益。最终，情感翻译器被用于Reading with Intent任务，将段落转化为中性语气，缓解了讽刺段落带来的挑战，并将任务整体结果提升了约3%。

> Queries to large language models (LLMs) can be divided into two parts: the instruction/question and the accompanying context. The context for retrieval-augmented generation (RAG) systems in most benchmarks comes from Wikipedia or Wikipedia-like texts which are written in a neutral and factual tone. However, when RAG systems retrieve internet-based content, they encounter text with diverse tones and linguistic styles, introducing challenges for downstream tasks. The Reading with Intent task addresses this issue by evaluating how varying tones in context passages affect model performance. Building on prior work that focused on sarcasm, we extend this paradigm by constructing a dataset where context passages are transformed to $11$ distinct emotions using a better synthetic data generation approach. Using this dataset, we train an emotion translation model to systematically adapt passages to specified emotional tones. The human evaluation shows that the LLM fine-tuned to become the emotion-translator benefited from the synthetically generated data. Finally, the emotion-translator is used in the Reading with Intent task to transform the passages to a neutral tone. By neutralizing the passages, it mitigates the challenges posed by sarcastic passages and improves overall results on this task by about $3\%$.

[Arxiv](https://arxiv.org/abs/2501.03475)