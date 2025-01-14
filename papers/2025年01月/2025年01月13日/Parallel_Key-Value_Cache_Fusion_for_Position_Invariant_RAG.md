# 并行键值缓存融合：实现位置不变的RAG

发布时间：2025年01月13日

`RAG

理由：这篇论文讨论了检索增强生成（RAG）的问题，特别是LLMs在处理上下文信息时的敏感性问题，并提出了一个框架来解决这些问题。因此，它属于RAG分类。` `问答系统`

> Parallel Key-Value Cache Fusion for Position Invariant RAG

# 摘要

> # 摘要
近期大型语言模型（LLMs）的进展凸显了检索增强生成（RAG）利用外部信息的重要性。然而，LLMs对上下文中相关信息的位置极为敏感，当这些信息位于中间时，容易产生错误响应，即“迷失在中间”现象。本文提出了一种框架，能够为仅解码器模型生成一致的输出，不受输入上下文顺序的影响。三个开放域问答任务的实验结果显示，该模型对输入顺序不敏感，且相比现有RAG方法，对无关段落的鲁棒性更佳。

> Recent advancements in Large Language Models (LLMs) underscore the necessity of Retrieval Augmented Generation (RAG) to leverage external information. However, LLMs are sensitive to the position of relevant information within contexts and tend to generate incorrect responses when such information is placed in the middle, known as `Lost in the Middle' phenomenon. In this paper, we introduce a framework that generates consistent outputs for decoder-only models, irrespective of the input context order. Experimental results for three open domain question answering tasks demonstrate position invariance, where the model is not sensitive to input context order, and superior robustness to irrelevent passages compared to prevailing approaches for RAG pipelines.

[Arxiv](https://arxiv.org/abs/2501.07523)