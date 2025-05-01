# 基于知识推理的操纵内容检测方法

发布时间：2025年04月29日

`LLM应用` `信息检测`

> Detecting Manipulated Contents Using Knowledge-Grounded Inference

# 摘要

> 近年来，虚假新闻的一种常见形式——篡改内容的检测受到了广泛关注。现有解决方案虽然在基于历史事件的事实核查和虚假新闻分析中表现出色，但它们依赖于训练过程中获得的内在知识或人工整理的上下文，这限制了它们处理零日伪造内容的能力，这类内容只能通过实时上下文信息来识别。为此，我们提出了Manicod，一种专为检测零日伪造内容设计的工具。Manicod首先从主流搜索引擎中获取输入声明的上下文信息，随后通过检索增强生成（RAG）将上下文向量化，供大型语言模型（LLM）使用。基于LLM的推理能够生成一个“真实”或“篡改”的决策，并提供对该决策的文本解释。为了验证Manicod的有效性，我们还提出了一组数据集，其中包括从2500条近期真实新闻头条中衍生出的4270条伪造虚假新闻。在这一数据集上，Manicod实现了0.856的总体F1分数，并在事实核查和声明验证的基准测试中，其F1分数比现有方法高出1.9倍。

> The detection of manipulated content, a prevalent form of fake news, has been widely studied in recent years. While existing solutions have been proven effective in fact-checking and analyzing fake news based on historical events, the reliance on either intrinsic knowledge obtained during training or manually curated context hinders them from tackling zero-day manipulated content, which can only be recognized with real-time contextual information. In this work, we propose Manicod, a tool designed for detecting zero-day manipulated content. Manicod first sources contextual information about the input claim from mainstream search engines, and subsequently vectorizes the context for the large language model (LLM) through retrieval-augmented generation (RAG). The LLM-based inference can produce a "truthful" or "manipulated" decision and offer a textual explanation for the decision. To validate the effectiveness of Manicod, we also propose a dataset comprising 4270 pieces of manipulated fake news derived from 2500 recent real-world news headlines. Manicod achieves an overall F1 score of 0.856 on this dataset and outperforms existing methods by up to 1.9x in F1 score on their benchmarks on fact-checking and claim verification.

[Arxiv](https://arxiv.org/abs/2504.21165)