# VR-RAG：利用RAG辅助的多模态模型实现开放词汇物种识别

发布时间：2025年05月08日

`RAG` `计算机视觉` `生物多样性监测`

> VR-RAG: Open-vocabulary Species Recognition with RAG-Assisted Large Multi-Modal Models

# 摘要

> 开放词汇视觉识别仍是计算机视觉领域的一大难题，尤其在自然界中，每年都有新物种被发现。我们专注于开放词汇的鸟类物种识别，目标是根据描述分类鸟类，而不受预定义 taxonomy 的限制。传统基准如 CUB-200-2011 和 Birdsnap 在封闭词汇范式下评估，难以应对现实中不断涌现的新物种。我们发现，现有系统在开放词汇设置下的性能大幅下降。为此，我们提出了一种整合 11,202 种鸟类维基百科知识的可扩展框架，并通过 GPT-4o 蒸馏成简洁摘要。我们开发了视觉重排序增强生成框架（VR-RAG），利用视觉相似性对多模态编码器检索的候选进行重排序，从而识别未见物种。实验表明，我们的方法显著提升了性能，将 QWEN2.5-VL 的平均表现提升了 15.4%。通过结合百科知识与视觉识别，我们为生物多样性监测和生态研究提供了灵活、可扩展的解决方案。

> Open-vocabulary recognition remains a challenging problem in computer vision, as it requires identifying objects from an unbounded set of categories. This is particularly relevant in nature, where new species are discovered every year. In this work, we focus on open-vocabulary bird species recognition, where the goal is to classify species based on their descriptions without being constrained to a predefined set of taxonomic categories. Traditional benchmarks like CUB-200-2011 and Birdsnap have been evaluated in a closed-vocabulary paradigm, limiting their applicability to real-world scenarios where novel species continually emerge. We show that the performance of current systems when evaluated under settings closely aligned with open-vocabulary drops by a huge margin. To address this gap, we propose a scalable framework integrating structured textual knowledge from Wikipedia articles of 11,202 bird species distilled via GPT-4o into concise, discriminative summaries. We propose Visual Re-ranking Retrieval-Augmented Generation(VR-RAG), a novel, retrieval-augmented generation framework that uses visual similarities to rerank the top m candidates retrieved by a set of multimodal vision language encoders. This allows for the recognition of unseen taxa. Extensive experiments across five established classification benchmarks show that our approach is highly effective. By integrating VR-RAG, we improve the average performance of state-of-the-art Large Multi-Modal Model QWEN2.5-VL by 15.4% across five benchmarks. Our approach outperforms conventional VLM-based approaches, which struggle with unseen species. By bridging the gap between encyclopedic knowledge and visual recognition, our work advances open-vocabulary recognition, offering a flexible, scalable solution for biodiversity monitoring and ecological research.

[Arxiv](https://arxiv.org/abs/2505.05635)