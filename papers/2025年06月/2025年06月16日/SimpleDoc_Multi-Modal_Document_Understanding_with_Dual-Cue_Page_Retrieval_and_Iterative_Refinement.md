# # SimpleDoc：多模态文档理解系统，采用双提示页面检索与迭代优化技术

发布时间：2025年06月16日

`RAG` `文档处理` `视觉问答`

> SimpleDoc: Multi-Modal Document Understanding with Dual-Cue Page Retrieval and Iterative Refinement

# 摘要

> 文档视觉问答（DocVQA）是一项实用且具挑战性的任务，它需要根据文档内容回答问题，同时参考多页和多种模态的信息，例如图像和表格。为了处理多模态信息，近期的方法采用了一种类似的检索增强生成（RAG）流水线，但利用了基于视觉语言模型（VLM）的嵌入模型来嵌入并检索相关页面作为图像，并使用能够接受图像作为输入的VLM生成答案。本文中，我们引入了SimpleDoc，这是一个轻量级却强大的检索增强型DocVQA框架。它通过首先根据嵌入相似性检索候选页面，然后基于页面摘要对这些候选页面进行过滤和重新排序，从而提升证据页面的收集效果。一个基于VLM的推理代理会反复调用这个双线索检索器，逐步将新鲜页面拉入工作记忆，直到问题能够自信地被回答。在4个DocVQA数据集上，SimpleDoc平均比之前的基线模型高出3.2%，并且检索的页面数量大幅减少。我们的代码可在https://github.com/ag2ai/SimpleDoc获取。


> Document Visual Question Answering (DocVQA) is a practical yet challenging task, which is to ask questions based on documents while referring to multiple pages and different modalities of information, e.g, images and tables. To handle multi-modality, recent methods follow a similar Retrieval Augmented Generation (RAG) pipeline, but utilize Visual Language Models (VLMs) based embedding model to embed and retrieve relevant pages as images, and generate answers with VLMs that can accept an image as input. In this paper, we introduce SimpleDoc, a lightweight yet powerful retrieval - augmented framework for DocVQA. It boosts evidence page gathering by first retrieving candidates through embedding similarity and then filtering and re-ranking these candidates based on page summaries. A single VLM-based reasoner agent repeatedly invokes this dual-cue retriever, iteratively pulling fresh pages into a working memory until the question is confidently answered. SimpleDoc outperforms previous baselines by 3.2% on average on 4 DocVQA datasets with much fewer pages retrieved. Our code is available at https://github.com/ag2ai/SimpleDoc.

[Arxiv](https://arxiv.org/abs/2506.14035)