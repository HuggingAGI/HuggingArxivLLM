# ACoRN：增强型检索语言模型中的噪声鲁棒摘要压缩方法

发布时间：2025年04月17日

`RAG` `信息检索` `问答系统`

> ACoRN: Noise-Robust Abstractive Compression in Retrieval-Augmented Language Models

# 摘要

> 抽取式压缩通过使用较小的语言模型浓缩与查询相关的上下文，有效降低了检索增强生成（RAG）中的计算成本。然而，尽管检索到的文档具有高相关性评分，它们常常包含与回答无关或因事实错误而具有误导性的信息。这种现象表明，抽取式压缩器在长上下文中更可能忽略对正确答案至关重要的信息。为了解决这一问题，我们对检索到的文档进行了更细致的分类，并提出了抗噪声的抽取式压缩方法（ACoRN），该方法引入了两项创新性训练步骤。首先，我们在训练数据集上采用离线数据增强，以提升压缩器在面对两类检索噪声时的鲁棒性。其次，鉴于基于语言模型的压缩器存在信息利用率不足和位置偏见问题，我们进行了微调，使其能够生成围绕直接支持正确答案的关键信息的摘要。实验结果表明，使用ACoRN训练的T5-large作为压缩器，在保持答案字符串的同时，显著提升了精确匹配（EM）和F1分数，这些结果可作为直接证据。ACoRN在包含大量降低准确性的文档的数据集上表现出色，使其在实际应用中具有重要价值。

> Abstractive compression utilizes smaller langauge models to condense query-relevant context, reducing computational costs in retrieval-augmented generation (RAG). However,retrieved documents often include information that is either irrelevant to answering the query or misleading due to factual incorrect content, despite having high relevance scores. This behavior indicates that abstractive compressors are more likely to omit important information essential for the correct answer, especially in long contexts where attention dispersion occurs. To address this issue, we categorize retrieved documents in a more fine-grained manner and propose Abstractive Compression Robust against Noise (ACoRN), which introduces two novel training steps. First, we use offline data augmentation on the training dataset to enhance compressor robustness against two distinct types of retrieval noise. Second, since the language modelbased compressor cannot fully utilize information from multiple retrieved documents and exhibits positional bias, we perform finetuning to generate summaries centered around key information that directly supports the correct answer. Our experiments demonstrate that T5-large, trained with ACoRN as a compressor, improves EM and F1 scores while preserving the answer string, which could serve as direct evidence. ACoRN excels on datasets with many accuracy-reducing documents, making it highly useful in real-world scenarios.

[Arxiv](https://arxiv.org/abs/2504.12673)