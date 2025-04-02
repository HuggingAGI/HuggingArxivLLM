# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年04月01日

`RAG

分类理由：这篇论文主要研究了多语言RAG（mRAG）系统中，大型语言模型如何处理不同语言的检索段落，并评估了模型在多语言上下文中的表现。它探讨了LLMs在跨语言检索和生成中的能力，属于检索增强生成（RAG）领域的研究。` `多语言问答系统`

> On the Consistency of Multilingual Context Utilization in Retrieval-Augmented Generation

# 摘要

> 基于大型语言模型的检索增强生成（RAG）在多语言问答（QA）任务中表现强劲，通过利用从语料库中检索的相关段落。在多语言RAG（mRAG）中，检索到的段落可能使用与用户输入查询语言不同的语言编写，这对LLMs有效利用提供的信息构成了挑战。近期研究表明，从多语言语料库中检索段落可以提升RAG性能，尤其是对低资源语言。然而，LLMs在独立于检索质量的情况下，能够利用不同类型的多语言上下文生成准确答案的能力仍然研究不足。

本文对LLMs在以下三方面的能力进行了全面评估：(i) 不管相关段落的语言如何，能否持续利用该段落；(ii) 是否能以预期语言作答；(iii) 即使上下文中提供了多种不同语言的“干扰”段落，能否专注于相关段落。我们在涵盖48种语言的三个QA数据集上对四个LLMs进行了实验，结果发现LLMs从非目标语言段落中提取相关信息的能力令人惊讶，但以正确语言完整作答的能力相对较弱。我们的分析基于准确性和特征归因技术，进一步表明，干扰段落无论语言如何都会降低答案质量，但与查询语言相同的干扰段落影响稍大。综合来看，我们的研究深化了对LLMs在mRAG系统中如何利用上下文的理解，为未来改进提供了方向。

> Retrieval-augmented generation (RAG) with large language models (LLMs) has demonstrated strong performance in multilingual question-answering (QA) tasks by leveraging relevant passages retrieved from corpora. In multilingual RAG (mRAG), the retrieved passages can be written in languages other than that of the query entered by the user, making it challenging for LLMs to effectively utilize the provided information. Recent research suggests that retrieving passages from multilingual corpora can improve RAG performance, particularly for low-resource languages. However, the extent to which LLMs can leverage different kinds of multilingual contexts to generate accurate answers, *independently from retrieval quality*, remains understudied. In this paper, we conduct an extensive assessment of LLMs' ability to (i) make consistent use of a relevant passage regardless of its language, (ii) respond in the expected language, and (iii) focus on the relevant passage even when multiple `distracting' passages in different languages are provided in the context. Our experiments with four LLMs across three QA datasets covering a total of 48 languages reveal a surprising ability of LLMs to extract the relevant information from out-language passages, but a much weaker ability to formulate a full answer in the correct language. Our analysis, based on both accuracy and feature attribution techniques, further shows that distracting passages negatively impact answer quality regardless of their language. However, distractors in the query language exert a slightly stronger influence. Taken together, our findings deepen the understanding of how LLMs utilize context in mRAG systems, providing directions for future improvements.

[Arxiv](https://arxiv.org/abs/2504.00597)