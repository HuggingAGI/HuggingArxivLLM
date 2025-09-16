# GeoGPT-RAG 技术报告

发布时间：2025年09月14日

`RAG` `基础理论`

> GeoGPT-RAG Technical Report

# 摘要

> GeoGPT是一款开放式大型语言模型系统，专为推动地球科学研究而打造。为提升其领域专长，我们融入了检索增强生成（RAG）技术——它能从外部知识源调取相关信息，为模型输出增效。GeoGPT借助RAG技术从GeoGPT库中汲取知识——这是一个专为地球科学内容精心构建的专业语料库，从而能生成准确且贴合上下文的答案。用户也能上传个人出版物列表，搭建专属知识库，让GeoGPT直接调用这些材料进行检索与作答。为进一步提升检索质量与领域适配性，我们对嵌入模型和排序模型均做了微调——排序模型会依据与查询的相关性，为检索到的段落打分。这些改进让RAG在地球科学场景中更高效，同时大幅增强了系统输出精准可信结果的能力。GeoGPT秉持协作、透明与社区驱动的发展理念，彰显了对开放科学的坚定投入。为践行这一理念，我们开源了两个核心RAG组件——GeoEmbedding与GeoReranker，为全球地球科学家、研究人员及专业人士提供强大且易用的AI工具支持。

> GeoGPT is an open large language model system built to advance research in the geosciences. To enhance its domain-specific capabilities, we integrated Retrieval Augmented Generation(RAG), which augments model outputs with relevant information retrieved from an external knowledge source. GeoGPT uses RAG to draw from the GeoGPT Library, a specialized corpus curated for geoscientific content, enabling it to generate accurate, context-specific answers. Users can also create personalized knowledge bases by uploading their own publication lists, allowing GeoGPT to retrieve and respond using user-provided materials. To further improve retrieval quality and domain alignment, we fine-tuned both the embedding model and a ranking model that scores retrieved passages by relevance to the query. These enhancements optimize RAG for geoscience applications and significantly improve the system's ability to deliver precise and trustworthy outputs. GeoGPT reflects a strong commitment to open science through its emphasis on collaboration, transparency, and community driven development. As part of this commitment, we have open-sourced two core RAG components-GeoEmbedding and GeoReranker-to support geoscientists, researchers, and professionals worldwide with powerful, accessible AI tools.

[Arxiv](https://arxiv.org/abs/2509.09686)