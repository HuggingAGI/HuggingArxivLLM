# CCI4.0：助力大型语言模型推理的双语预训练数据集

发布时间：2025年06月09日

`其他` `人工智能`

> CCI4.0: A Bilingual Pretraining Dataset for Enhancing Reasoning in Large Language Models

# 摘要

> 我们推出 CCI4.0，一个专为优质数据和多样化人类推理模式设计的大规模双语预训练数据集。CCI4.0 占据 35TB 磁盘空间，包含两个子集：CCI4.0-M2-Base 和 CCI4.0-M2-CoT。CCI4.0-M2-Base 整合了 5.2TB 中文网络语料库、22.5TB 英文子集及多领域数据。尽管数据来源可靠，但跨领域质量把控仍具挑战。为此，我们开发了创新的数据处理流水线，通过两阶段去重、多分类器评分和领域感知过滤确保数据质量。我们提取了 45 亿条 CoT（思维链）模板，命名为 CCI4.0-M2-CoT。与传统 CoT 蒸馏不同，我们的分阶段提取方法展现了多样化推理模式，大幅降低了幻觉风险。实验证明，基于 CCI4.0 预训练的 LLM 在下游任务中表现更优，尤其在数学和代码推理方面。我们的研究凸显了高质量数据整理和人类思维模板在提升 LLM 性能中的重要作用，为预训练语料库的自动化处理提供了新思路。

> We introduce CCI4.0, a large-scale bilingual pre-training dataset engineered for superior data quality and diverse human-like reasoning trajectory. CCI4.0 occupies roughly $35$ TB of disk space and comprises two sub-datasets: CCI4.0-M2-Base and CCI4.0-M2-CoT. CCI4.0-M2-Base combines a $5.2$ TB carefully curated Chinese web corpus, a $22.5$ TB English subset from Nemotron-CC, and diverse sources from math, wiki, arxiv, and code. Although these data are mostly sourced from well-processed datasets, the quality standards of various domains are dynamic and require extensive expert experience and labor to process. So, we propose a novel pipeline justifying data quality mainly based on models through two-stage deduplication, multiclassifier quality scoring, and domain-aware fluency filtering. We extract $4.5$ billion pieces of CoT(Chain-of-Thought) templates, named CCI4.0-M2-CoT. Differing from the distillation of CoT from larger models, our proposed staged CoT extraction exemplifies diverse reasoning patterns and significantly decreases the possibility of hallucination. Empirical evaluations demonstrate that LLMs pre-trained in CCI4.0 benefit from cleaner, more reliable training signals, yielding consistent improvements in downstream tasks, especially in math and code reflection tasks. Our results underscore the critical role of rigorous data curation and human thinking templates in advancing LLM performance, shedding some light on automatically processing pretraining corpora.

[Arxiv](https://arxiv.org/abs/2506.07463)