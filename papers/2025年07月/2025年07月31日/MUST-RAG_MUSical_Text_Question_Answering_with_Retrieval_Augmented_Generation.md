# MUST-RAG：基于检索增强生成的音乐文本问答系统

发布时间：2025年07月31日

`RAG` `问答系统`

> MUST-RAG: MUSical Text Question Answering with Retrieval Augmented Generation

# 摘要

> 大型语言模型（LLMs）在多领域展现出了强大的能力，但受限于训练数据中音乐相关知识比例较低，其在音乐应用中的表现仍有提升空间。针对这一问题，我们提出了 MusT-RAG，一个基于检索增强生成（RAG）的框架，旨在将通用 LLMs 适配于音乐问答（MQA）任务。RAG 通过检索相关上下文信息为模型提供外部知识。为优化音乐领域的应用，我们（1）开发了专门的音乐向量数据库 MusWikiDB，并（2）在推理和微调中充分利用上下文信息，成功将通用模型转化为音乐专用模型。实验结果表明，MusT-RAG 在提升音乐领域适应能力方面显著优于传统微调方法，且在内外部 MQA 基准测试中均表现优异。此外，MusWikiDB 的性能和计算效率远超通用维基百科语料库，展现出巨大优势。

> Recent advancements in Large language models (LLMs) have demonstrated remarkable capabilities across diverse domains. While they exhibit strong zero-shot performance on various tasks, LLMs' effectiveness in music-related applications remains limited due to the relatively small proportion of music-specific knowledge in their training data. To address this limitation, we propose MusT-RAG, a comprehensive framework based on Retrieval Augmented Generation (RAG) to adapt general-purpose LLMs for text-only music question answering (MQA) tasks. RAG is a technique that provides external knowledge to LLMs by retrieving relevant context information when generating answers to questions. To optimize RAG for the music domain, we (1) propose MusWikiDB, a music-specialized vector database for the retrieval stage, and (2) utilizes context information during both inference and fine-tuning processes to effectively transform general-purpose LLMs into music-specific models. Our experiment demonstrates that MusT-RAG significantly outperforms traditional fine-tuning approaches in enhancing LLMs' music domain adaptation capabilities, showing consistent improvements across both in-domain and out-of-domain MQA benchmarks. Additionally, our MusWikiDB proves substantially more effective than general Wikipedia corpora, delivering superior performance and computational efficiency.

[Arxiv](https://arxiv.org/abs/2507.23334)