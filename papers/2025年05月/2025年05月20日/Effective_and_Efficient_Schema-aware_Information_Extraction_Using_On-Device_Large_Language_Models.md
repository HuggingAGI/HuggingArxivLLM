# # 摘要
利用设备端大型语言模型实现有效且高效的模式感知信息抽取

发布时间：2025年05月20日

`LLM应用` `信息抽取`

> Effective and Efficient Schema-aware Information Extraction Using On-Device Large Language Models

# 摘要

> 信息抽取 (IE) 是自然语言处理 (NLP) 中的关键技术，它通过将非结构化文本转化为结构化知识来实现其价值。然而，在资源受限的设备上部署计算密集型大型语言模型 (LLMs) 进行信息抽取面临诸多挑战，特别是幻觉、有限上下文长度以及高延迟等问题，尤其是在处理多样化抽取模式时。为了解决这些问题，我们提出了一种名为带增量模式缓存的双 LoRA (DLISC) 的两阶段信息抽取方法，该方法在模式识别和模式感知抽取方面均提升了有效性和效率。具体而言，DLISC 采用了识别 LoRA 模块来检索与给定查询最相关的模式，以及抽取 LoRA 模块来基于先前选择的模式执行信息抽取。为了加速抽取推理，DLISC 引入了增量模式缓存以减少冗余计算，从而显著提升了效率。在多个信息抽取数据集上的广泛实验表明，DLISC 在有效性和效率方面均取得了显著提升。


> Information extraction (IE) plays a crucial role in natural language processing (NLP) by converting unstructured text into structured knowledge. Deploying computationally intensive large language models (LLMs) on resource-constrained devices for information extraction is challenging, particularly due to issues like hallucinations, limited context length, and high latency-especially when handling diverse extraction schemas. To address these challenges, we propose a two-stage information extraction approach adapted for on-device LLMs, called Dual-LoRA with Incremental Schema Caching (DLISC), which enhances both schema identification and schema-aware extraction in terms of effectiveness and efficiency. In particular, DLISC adopts an Identification LoRA module for retrieving the most relevant schemas to a given query, and an Extraction LoRA module for performing information extraction based on the previously selected schemas. To accelerate extraction inference, Incremental Schema Caching is incorporated to reduce redundant computation, substantially improving efficiency. Extensive experiments across multiple information extraction datasets demonstrate notable improvements in both effectiveness and efficiency.

[Arxiv](https://arxiv.org/abs/2505.14992)