# Lugha-Llama：为非洲本地语言量身定制的大型语言模型

发布时间：2025年04月08日

`LLM应用` `非洲语言` `问答系统`

> Lugha-Llama: Adapting Large Language Models for African Languages

# 摘要

> 大型语言模型（LLMs）在各种自然语言应用中展现了卓越的性能，但它们在处理低资源语言，尤其是非洲语言时仍面临挑战，因为这些语言在大型训练语料库中代表性不足。本文探讨了如何将LLMs适应低资源非洲语言。我们发现，将非洲语言的精选数据与高质量的英语教育文本相结合，能够显著提升模型在这些语言上的表现。在具有挑战性的IrokoBench数据集上，我们的模型在同类规模的基线模型中表现最佳，尤其是在知识密集型的多项选择题（AfriMMLU）方面。此外，在跨语言问答基准测试AfriQA上，我们的模型比基础模型高出10%以上。为了深入理解英语数据在训练过程中的作用，我们将2亿个标记的子集翻译成斯瓦希里语，并进行了分析，结果表明，这些数据的内容是模型表现出色的关键。我们公开了我们的模型和数据，以鼓励未来对非洲语言的研究。

> Large language models (LLMs) have achieved impressive results in a wide range of natural language applications. However, they often struggle to recognize low-resource languages, in particular African languages, which are not well represented in large training corpora. In this paper, we consider how to adapt LLMs to low-resource African languages. We find that combining curated data from African languages with high-quality English educational texts results in a training mix that substantially improves the model's performance on these languages. On the challenging IrokoBench dataset, our models consistently achieve the best performance amongst similarly sized baselines, particularly on knowledge-intensive multiple-choice questions (AfriMMLU). Additionally, on the cross-lingual question answering benchmark AfriQA, our models outperform the base model by over 10%. To better understand the role of English data during training, we translate a subset of 200M tokens into Swahili language and perform an analysis which reveals that the content of these data is primarily responsible for the strong performance. We release our models and data to encourage future research on African languages.

[Arxiv](https://arxiv.org/abs/2504.06536)