# QueEn：一款用于克丘亚语与英语翻译的大型语言模型

发布时间：2024年12月06日

`RAG` `语言翻译` `濒危语言保护`

> QueEn: A Large Language Model for Quechua-English Translation

# 摘要

> 近期研究显示，大型语言模型（LLMs）是处理自然语言的有力工具，在计算语言学的众多领域带来了进步。但这些模型在应用于低资源语言时面临挑战，原因是训练数据有限以及理解文化细微差异存在困难。在本文中，我们提出了 QueEn，这是一种用于克丘亚语 - 英语翻译的新颖方法，它将检索增强生成（RAG）与参数高效微调技术相结合。我们的方法借助 RAG 利用外部语言资源，并运用低秩自适应（LoRA）实现高效的模型适配。实验结果表明，我们的方法大幅超越基线模型，BLEU 分数达 17.6，而标准 GPT 模型仅为 1.5。RAG 与微调的融合让我们的系统能够应对低资源语言翻译的难题，同时保持计算效率。此项工作有助于通过先进的语言技术达成保护濒危语言这一更宏大的目标。

> Recent studies show that large language models (LLMs) are powerful tools for working with natural language, bringing advances in many areas of computational linguistics. However, these models face challenges when applied to low-resource languages due to limited training data and difficulty in understanding cultural nuances. In this paper, we propose QueEn, a novel approach for Quechua-English translation that combines Retrieval-Augmented Generation (RAG) with parameter-efficient fine-tuning techniques. Our method leverages external linguistic resources through RAG and uses Low-Rank Adaptation (LoRA) for efficient model adaptation. Experimental results show that our approach substantially exceeds baseline models, with a BLEU score of 17.6 compared to 1.5 for standard GPT models. The integration of RAG with fine-tuning allows our system to address the challenges of low-resource language translation while maintaining computational efficiency. This work contributes to the broader goal of preserving endangered languages through advanced language technologies.

[Arxiv](https://arxiv.org/abs/2412.05184)