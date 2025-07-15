# # 基于大型语言模型的二语口语能力评估

发布时间：2025年07月14日

`LLM应用`

> Natural Language-based Assessment of L2 Oral Proficiency using LLMs

# 摘要

> 基于自然语言的评估（NLA）是一种用于第二语言评估的方法，通过使用can-do描述符的形式给出指令，这些指令原本是为人类考官设计的，目的是考察大型语言模型（LLMs）是否能像人类评估一样理解和应用这些指令。在本研究中，我们尝试将这些描述符与开源的LLM——Qwen 2.5 72B结合，用于评估公开可用的S&I语料库中的响应，测试环境为零样本设置。实验结果表明，这种仅依赖文本信息的方法表现优异：虽然未能超越针对该任务进行微调的最先进语音LLMs，但其性能远超专门为此设计的BERT模型。NLA在任务不匹配的场景下尤为出色，且能够扩展至其他数据类型和语言，同时具备更高的可解释性，因为其基于清晰易懂、广泛应用的语言描述符。


> Natural language-based assessment (NLA) is an approach to second language assessment that uses instructions - expressed in the form of can-do descriptors - originally intended for human examiners, aiming to determine whether large language models (LLMs) can interpret and apply them in ways comparable to human assessment. In this work, we explore the use of such descriptors with an open-source LLM, Qwen 2.5 72B, to assess responses from the publicly available S&I Corpus in a zero-shot setting. Our results show that this approach - relying solely on textual information - achieves competitive performance: while it does not outperform state-of-the-art speech LLMs fine-tuned for the task, it surpasses a BERT-based model trained specifically for this purpose. NLA proves particularly effective in mismatched task settings, is generalisable to other data types and languages, and offers greater interpretability, as it is grounded in clearly explainable, widely applicable language descriptors.

[Arxiv](https://arxiv.org/abs/2507.10200)