# # 借助大型语言模型摘要实现源代码主题建模
本研究致力于探索如何利用大型语言模型生成的摘要来提升源代码主题建模的效果。通过对LLMs在代码理解方面的潜力进行深入分析，我们提出了一种创新方法，能够更高效地从海量代码库中提取关键主题信息。

发布时间：2025年04月24日

`LLM应用` `软件工程`

> Towards Leveraging Large Language Model Summaries for Topic Modeling in Source Code

# 摘要

> 理解源代码一直是软件工程领域备受关注的话题，因为它能助力程序员完成软件维护和重用等重要任务。近期，大型语言模型（LLMs）的突破性进展展现了卓越的程序理解能力，而基于Transformer的主题建模技术则为从文本中提取语义信息提供了有效途径。本文提出了一种结合这两种技术优势的全新方法，旨在自动识别Python程序语料库中的有意义主题。具体来说，我们的方法通过让LLM对代码进行总结，然后对这些描述进行主题建模。为了验证提取主题的内在一致性，我们将这些主题与仅基于函数名称推断的主题，以及现有文档字符串派生的主题进行了对比。实验结果表明，利用LLM生成的摘要能够提供对代码结构的可解释且语义丰富的表示。这些有前景的结果表明，我们的方法可以成功应用于自动文档生成、代码搜索、软件重构以及大型代码仓库中的知识发现等软件工程任务。

> Understanding source code is a topic of great interest in the software engineering community, since it can help programmers in various tasks such as software maintenance and reuse. Recent advances in large language models (LLMs) have demonstrated remarkable program comprehension capabilities, while transformer-based topic modeling techniques offer effective ways to extract semantic information from text. This paper proposes and explores a novel approach that combines these strengths to automatically identify meaningful topics in a corpus of Python programs. Our method consists in applying topic modeling on the descriptions obtained by asking an LLM to summarize the code. To assess the internal consistency of the extracted topics, we compare them against topics inferred from function names alone, and those derived from existing docstrings. Experimental results suggest that leveraging LLM-generated summaries provides interpretable and semantically rich representation of code structure. The promising results suggest that our approach can be fruitfully applied in various software engineering tasks such as automatic documentation and tagging, code search, software reorganization and knowledge discovery in large repositories.

[Arxiv](https://arxiv.org/abs/2504.17426)