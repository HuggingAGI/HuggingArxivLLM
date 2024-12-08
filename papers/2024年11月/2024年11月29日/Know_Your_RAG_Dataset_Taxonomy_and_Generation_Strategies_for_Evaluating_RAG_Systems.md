# 了解您的 RAG：评估 RAG 系统的数据集分类及生成策略

发布时间：2024年11月29日

`RAG` `语言模型` `系统开发`

> Know Your RAG: Dataset Taxonomy and Generation Strategies for Evaluating RAG Systems

# 摘要

> 检索增强生成（RAG）系统在行业中是大型语言模型（LLMs）的广泛应用。虽然有众多工具助力开发者构建自己的系统，但在本地用能反映系统使用案例的数据集来衡量其性能，是个技术难题。此难题的解决方案，从非特定且廉价的（多数公共数据集）到特定且昂贵的（从本地文档生成数据）都有。在本文中，我们指出用公共问答（Q&A）数据集评估检索性能可能致使系统设计非最优，常见的 RAG 数据集生成工具可能造成数据不均衡。我们基于通过标签和针对标签的数据生成对 RAG 数据集的特性描述，提出了这些问题的解决办法。最后，我们表明经过微调的小型 LLMs 能够高效生成 Q&A 数据集。我们认为这些观察对于 RAG 系统开发中“了解您的数据”这一步骤极具价值。

> Retrieval Augmented Generation (RAG) systems are a widespread application of Large Language Models (LLMs) in the industry. While many tools exist empowering developers to build their own systems, measuring their performance locally, with datasets reflective of the system's use cases, is a technological challenge. Solutions to this problem range from non-specific and cheap (most public datasets) to specific and costly (generating data from local documents). In this paper, we show that using public question and answer (Q&A) datasets to assess retrieval performance can lead to non-optimal systems design, and that common tools for RAG dataset generation can lead to unbalanced data. We propose solutions to these issues based on the characterization of RAG datasets through labels and through label-targeted data generation. Finally, we show that fine-tuned small LLMs can efficiently generate Q&A datasets. We believe that these observations are invaluable to the know-your-data step of RAG systems development.

[Arxiv](https://arxiv.org/abs/2411.19710)