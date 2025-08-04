# GLiDRE：通用轻量级文档级关系抽取模型

发布时间：2025年08月01日

`其他` `信息抽取`

> GLiDRE: Generalist Lightweight model for Document-level Relation Extraction

# 摘要

> 关系抽取（RE）是自然语言处理的基础任务，而文档级别的关系抽取由于需要建模跨句实体间的复杂交互，更具挑战性。目前基于ATLOP架构的方法主要在DocRED和Re-DocRED等基准数据集上进行评估。然而，由于任务复杂性，这些方法在零样本或少样本设置下的性能仍 largely underexplored。最近，GLiNER模型表明，一个紧凑的NER模型可以超越更大的大型语言模型。出于相似的动机，我们提出了GLiDRE，一个基于GliNER关键思想的新文档级别关系抽取模型。我们在Re-DocRED数据集上，针对各种数据设置，将GLiDRE与现有最先进的模型进行了基准测试。结果显示，GLiDRE在少样本场景中达到了最先进的性能。我们的代码已公开可用。

> Relation Extraction (RE) is a fundamental task in Natural Language Processing, and its document-level variant poses significant challenges, due to the need to model complex interactions between entities across sentences. Current approaches, largely based on the ATLOP architecture, are commonly evaluated on benchmarks like DocRED and Re-DocRED. However, their performance in zero-shot or few-shot settings remains largely underexplored due to the task's complexity. Recently, the GLiNER model has shown that a compact NER model can outperform much larger Large Language Models. With a similar motivation, we introduce GLiDRE, a new model for document-level relation extraction that builds on the key ideas of GliNER. We benchmark GLiDRE against state-of-the-art models across various data settings on the Re-DocRED dataset. Our results demonstrate that GLiDRE achieves state-of-the-art performance in few-shot scenarios. Our code is publicly available.

[Arxiv](https://arxiv.org/abs/2508.00757)