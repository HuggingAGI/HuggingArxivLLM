# 关于大型语言模型中查询优化的一项调研

发布时间：2024年12月23日

`RAG` `语言模型` `查询优化`

> A Survey of Query Optimization in Large Language Models

# 摘要

> 	extit{查询优化}（QO）指的是用于提升大型语言模型（LLMs）理解和回答查询（尤其是在检索增强生成（RAG）等场景中的复杂查询）的效率与质量的技术。具体而言，RAG 通过动态检索和利用最新的相关信息，缓解了 LLMs 的局限性，为 LLMs 可能产生看似合理但不准确的回答这一难题提供了经济有效的解决方案。近来，随着 RAG 不断发展并融入多个影响其性能的组件，QO 已成为关键要素，在决定 RAG 检索阶段能否准确获取回答查询所需的多个证据方面发挥着重要作用。在本文中，我们通过总结和分析重要研究来追溯 QO 技术的发展历程。借助有条理的框架和分类，我们致力于整合 RAG 中现有的 QO 技术，阐明其技术基础，并突显其增强 LLMs 通用性和应用的潜力。

> \textit{Query Optimization} (QO) refers to techniques aimed at enhancing the efficiency and quality of Large Language Models (LLMs) in understanding and answering queries, especially complex ones in scenarios like Retrieval-Augmented Generation (RAG). Specifically, RAG mitigates the limitations of LLMs by dynamically retrieving and leveraging up-to-date relevant information, which provides a cost-effective solution to the challenge of LLMs producing plausible but potentially inaccurate responses. Recently, as RAG evolves and incorporates multiple components that influence its performance, QO has emerged as a critical element, playing a pivotal role in determining the effectiveness of RAG's retrieval stage in accurately sourcing the necessary multiple pieces of evidence to answer queries correctly. In this paper, we trace the evolution of QO techniques by summarizing and analyzing significant studies. Through an organized framework and categorization, we aim to consolidate existing QO techniques in RAG, elucidate their technological foundations, and highlight their potential to enhance the versatility and applications of LLMs.

[Arxiv](https://arxiv.org/abs/2412.17558)