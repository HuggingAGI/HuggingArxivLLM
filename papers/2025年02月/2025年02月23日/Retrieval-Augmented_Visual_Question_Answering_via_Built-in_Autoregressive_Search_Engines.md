# 内置自回归搜索引擎驱动的增强式视觉问答检索

发布时间：2025年02月23日

`RAG` `视觉问答` `多模态`

> Retrieval-Augmented Visual Question Answering via Built-in Autoregressive Search Engines

# 摘要

> 为了解决知识密集型视觉问答（VQA）任务，检索增强生成（RAG）应运而生。当前方法主要通过分离的检索模块和生成模块来获取外部知识和生成答案。我们提出了ReAuSE，作为之前知识型VQA任务中RAG模型的替代方案。ReAuSE将知识检索器无缝集成到生成式多模态大型语言模型中，充当内置搜索引擎。具体来说，我们的模型同时具备生成式检索和精准回答生成的能力。它不仅通过为每个文档生成标识符来帮助从知识库中检索文档，还基于检索到的文档来回答视觉问题。此外，我们还提出了一种基于相关性反馈的强化检索校准模块，以提升检索性能并优化精准回答生成偏好。在两个具有代表性的OKVQA和A-OKVQA数据集上的广泛实验表明，与强基线相比，所有评估指标的改进幅度在2.9%到9.6%之间。


> Retrieval-augmented generation (RAG) has emerged to address the knowledge-intensive visual question answering (VQA) task. Current methods mainly employ separate retrieval and generation modules to acquire external knowledge and generate answers, respectively. We propose ReAuSE, an alternative to the previous RAG model for the knowledge-based VQA task, which seamlessly integrates knowledge retriever into the generative multi-modal large language model, serving as a built-in search engine. Specifically, our model functions both as a generative retriever and an accurate answer generator. It not only helps retrieve documents from the knowledge base by producing identifiers for each document, but it also answers visual questions based on the retrieved documents. Furthermore, we propose a reinforced retrieval calibration module from relevance feedback to improve retrieval performance and align with the preferences for accurate answer generation. Extensive experiments on two representative OKVQA and A-OKVQA datasets demonstrate significant improvements ranging from 2.9\% to 9.6\% across all evaluation metrics when compared to strong baselines.

[Arxiv](https://arxiv.org/abs/2502.16641)