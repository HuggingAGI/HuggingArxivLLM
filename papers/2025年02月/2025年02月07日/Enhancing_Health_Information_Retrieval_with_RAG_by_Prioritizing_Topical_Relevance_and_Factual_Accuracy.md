# 结合RAG方法，优化健康信息检索：以主题相关与事实准确为优先

发布时间：2025年02月07日

`RAG` `信息检索`

> Enhancing Health Information Retrieval with RAG by Prioritizing Topical Relevance and Factual Accuracy

# 摘要

> 在线健康信息的激增，以及非专业人士的广泛使用，凸显了开发先进健康信息检索模型的迫切需求。这些模型不仅要考虑主题相关性，还需确保信息的事实准确性，因为健康 misinformation 的潜在风险不容忽视。为此，我们提出了一种基于检索增强生成（RAG）的解决方案，利用生成式大语言模型（LLMs）的能力，提升基于科学证据的健康相关文档检索效果。具体而言，我们提出了一个三阶段模型：第一阶段通过用户的查询从科学文献知识库中检索主题相关的段落及其引用；第二阶段将这些段落与初始查询输入 LLMs，生成上下文相关的丰富文本（GenText）；第三阶段从主题相关性和事实准确性两个角度，通过立场检测或语义相似性将其与 GenText 进行比较，从而评估和排名待检索文档。GenText 不仅能计算事实准确性，还能提供可解释性，帮助用户理解检索背后的推理过程。实验评估表明，该模型在提升主题相关和事实准确的健康信息检索方面效果显著，为缓解健康 misinformation 问题迈出了重要一步。

> The exponential surge in online health information, coupled with its increasing use by non-experts, highlights the pressing need for advanced Health Information Retrieval models that consider not only topical relevance but also the factual accuracy of the retrieved information, given the potential risks associated with health misinformation. To this aim, this paper introduces a solution driven by Retrieval-Augmented Generation (RAG), which leverages the capabilities of generative Large Language Models (LLMs) to enhance the retrieval of health-related documents grounded in scientific evidence. In particular, we propose a three-stage model: in the first stage, the user's query is employed to retrieve topically relevant passages with associated references from a knowledge base constituted by scientific literature. In the second stage, these passages, alongside the initial query, are processed by LLMs to generate a contextually relevant rich text (GenText). In the last stage, the documents to be retrieved are evaluated and ranked both from the point of view of topical relevance and factual accuracy by means of their comparison with GenText, either through stance detection or semantic similarity. In addition to calculating factual accuracy, GenText can offer a layer of explainability for it, aiding users in understanding the reasoning behind the retrieval. Experimental evaluation of our model on benchmark datasets and against baseline models demonstrates its effectiveness in enhancing the retrieval of both topically relevant and factually accurate health information, thus presenting a significant step forward in the health misinformation mitigation problem.

[Arxiv](https://arxiv.org/abs/2502.04666)