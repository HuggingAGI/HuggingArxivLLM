# URLs 帮助，主题引导：探索元数据在 LLM 训练中的价值

发布时间：2025年05月22日

`LLM理论` `人工智能`

> URLs Help, Topics Guide: Understanding Metadata Utility in LLM Training

# 摘要

> 大型语言模型（LLMs）通常在不利用来源、质量或主题等上下文元数据的情况下进行预训练，导致了一种无上下文的学习范式。尽管近期研究表明，将URL信息等元数据作为上下文（即不用于损失计算的辅助输入）可以提升训练效率和下游性能，但关于哪些类型的元数据真正有效以及在何种条件下有效，仍缺乏深入理解。本研究进行了系统性评估，发现并非所有元数据类型都同等有效。唯有URL上下文能够加速训练，而质量评分和主题/格式领域信息则无明显优势。此外，URL条件提升的下游性能仅在推理时使用更长的提示时才显现。我们还证明，与无上下文预训练相比，基于上下文的预训练能够实现更可控的生成，采用无分类器引导的方式。尽管主题和格式元数据无法加速训练，但它们能有效引导输出，为生成提供人类可解释的控制能力。

> Large Language Models (LLMs) are commonly pretrained on vast corpora of text without utilizing contextual metadata such as source, quality, or topic, leading to a context-free learning paradigm. While recent studies suggest that adding metadata like URL information as context (i.e., auxiliary inputs not used in the loss calculation) can improve training efficiency and downstream performance, they offer limited understanding of which types of metadata are truly effective and under what conditions. In this work, we conduct a systematic evaluation and find that not all metadata types contribute equally. Only URL context speeds up training, whereas quality scores and topic/format domain information offer no clear benefit. Furthermore, the improved downstream performances of URL conditioning emerge only when longer prompts are used at inference time. In addition, we demonstrate that context-aware pretraining enables more controllable generation than context-free pretraining, in a classifier-free guidance fashion. Although topic and format metadata do not accelerate training, they are effective for steering outputs, offering human-interpretable control over generation.

[Arxiv](https://arxiv.org/abs/2505.16570)