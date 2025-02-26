# # 检索增强对社会偏见影响的评估
评估检索增强对社会偏见的影响

发布时间：2025年02月24日

`RAG` `自然语言生成` `社会偏见`

> Evaluating the Effect of Retrieval Augmentation on Social Biases

# 摘要

> 检索增强生成（RAG）作为一种方法，在大型语言模型（LLM）为基础的自然语言生成（NLG）系统中，因其能够方便地整合未在预训练阶段见过的新事实而广受欢迎。然而，LLMs 被广泛认为编码了显著的社会偏见不公平性。RAG 在 NLG 系统中对这些偏见的调制作用尚不明确。本文系统性地研究了 RAG 系统的不同组件与文本生成过程中呈现的社会偏见之间的关系，涵盖了三种语言（即英语、日语和中文）以及四种社会偏见类型（即性别、种族、年龄和宗教）。具体而言，我们使用带有不同程度刻板偏见的文档集合，基于 Bias Question Answering（BBQ）基准数据集，评估了 RAG 响应中的社会偏见，采用了多种作为生成器的 LLM。我们发现，即使生成 LLM 本身表现出较低水平的偏见，文档集合中的偏见在生成的响应中往往会放大。我们的发现引发了对将 RAG 作为向 NLG 系统注入新事实的技术使用的担忧，并呼吁在实际应用部署前，对 RAG 应用中的潜在社会偏见进行谨慎评估。

> Retrieval Augmented Generation (RAG) has gained popularity as a method for conveniently incorporating novel facts that were not seen during the pre-training stage in Large Language Model (LLM)-based Natural Language Generation (NLG) systems. However, LLMs are known to encode significant levels of unfair social biases. The modulation of these biases by RAG in NLG systems is not well understood. In this paper, we systematically study the relationship between the different components of a RAG system and the social biases presented in the text generated across three languages (i.e. English, Japanese and Chinese) and four social bias types (i.e. gender, race, age and religion). Specifically, using the Bias Question Answering (BBQ) benchmark datasets, we evaluate the social biases in RAG responses from document collections with varying levels of stereotypical biases, employing multiple LLMs used as generators. We find that the biases in document collections are often amplified in the generated responses, even when the generating LLM exhibits a low-level of bias. Our findings raise concerns about the use of RAG as a technique for injecting novel facts into NLG systems and call for careful evaluation of potential social biases in RAG applications before their real-world deployment.

[Arxiv](https://arxiv.org/abs/2502.17611)