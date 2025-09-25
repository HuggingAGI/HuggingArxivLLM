# Meow：自动学术综述的端到端大纲写作

发布时间：2025年09月19日

`LLM应用` `基础理论`

> Meow: End-to-End Outline Writing for Automatic Academic Survey

# 摘要

> 随着学术论文发表数量呈指数级激增，利用大型语言模型（LLMs）自动生成深度综述已成为必然趋势。大纲撰写作为系统梳理相关研究的核心环节，对自动化综述生成起着关键作用。然而，现有自动综述方法往往将大纲撰写简化为整体流程中的一个普通步骤，这类模板化流程生成的大纲不仅对综述主题缺乏深入理解，风格也不够细腻。为突破这些局限，我们提出Meow——首个元数据驱动的大纲撰写框架，可高效生成结构规整、内容忠实的大纲。具体而言，我们首先将大纲撰写建模为端到端任务：直接从论文元数据生成层级结构化大纲。接着，我们从arXiv、bioRxiv和medRxiv三大预印本平台构建了高质量综述数据集，并制定了大纲质量评估的系统指标体系。最后，我们采用“监督微调+强化学习”的两阶段训练策略。实验表明，我们的8B推理模型性能卓越，不仅结构忠实度高，风格也保持连贯统一。

> As academic paper publication numbers grow exponentially, conducting in-depth surveys with LLMs automatically has become an inevitable trend. Outline writing, which aims to systematically organize related works, is critical for automated survey generation. Yet existing automatic survey methods treat outline writing as mere workflow steps in the overall pipeline. Such template-based workflows produce outlines that lack in-depth understanding of the survey topic and fine-grained styles. To address these limitations, we propose Meow, the first metadata-driven outline writing framework that produces organized and faithful outlines efficiently. Specifically, we first formulate outline writing as an end-to-end task that generates hierarchical structured outlines from paper metadata. We then curate a high-quality dataset of surveys from arXiv, bioRxiv, and medRxiv, and establish systematic evaluation metrics for outline quality assessment. Finally, we employ a two-stage training approach combining supervised fine-tuning and reinforcement learning. Our 8B reasoning model demonstrates strong performance with high structural fidelity and stylistic coherence.

[Arxiv](https://arxiv.org/abs/2509.19370)