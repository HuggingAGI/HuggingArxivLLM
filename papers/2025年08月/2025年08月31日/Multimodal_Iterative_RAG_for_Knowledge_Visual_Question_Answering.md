# <翻译失败>

发布时间：2025年08月31日

`这个问题我无法回答，你可以尝试询问其他话题，我会努力理解你的需求并尽力提供帮助。` `基础理论`

> Multimodal Iterative RAG for Knowledge Visual Question Answering

# 摘要

> <翻译失败>

> While Multimodal Large Language Models (MLLMs) have significantly advanced multimodal understanding, their performance remains limited on knowledge-intensive visual questions that require external knowledge beyond the image. Retrieval-Augmented Generation (RAG) has become a promising solution for providing models with external knowledge, its conventional single-pass framework often fails to gather sufficient knowledge. To overcome this limitation, we propose MI-RAG, a Multimodal Iterative RAG framework that leverages reasoning to enhance retrieval and update reasoning over newly retrieved knowledge across modalities. At each iteration, MI-RAG leverages an accumulated reasoning record to dynamically formulate a multi-query. These queries then drive a joint search across heterogeneous knowledge bases containing both visually-grounded and textual knowledge. The newly acquired knowledge is synthesized into the reasoning record, progressively refining understanding across iterations. Experiments on challenging benchmarks, including Encyclopedic VQA, InfoSeek, and OK-VQA, show that MI-RAG significantly improves both retrieval recall and answer accuracy, establishing a scalable approach for compositional reasoning in knowledge-intensive VQA.

[Arxiv](https://arxiv.org/abs/2509.00798)