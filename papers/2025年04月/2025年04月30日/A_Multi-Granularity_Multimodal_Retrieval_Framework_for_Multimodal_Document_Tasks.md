# 面向多模态文档任务的多粒度多模态检索框架

发布时间：2025年04月30日

`RAG` `文档检索` `多模态`

> A Multi-Granularity Multimodal Retrieval Framework for Multimodal Document Tasks

# 摘要

> 检索增强生成（RAG）系统主要聚焦于文本检索，这限制了其在处理图文并茂文档时的效能。针对这一问题，我们提出了一种针对MMDocIR和M2KR任务的统一多粒度多模态检索框架。我们的方法结合了层次化编码策略、模态感知检索机制和重排序模块，有效捕捉并利用了文本与视觉模态间的复杂关联。通过现成的视觉-语言模型和无需微调的混合检索策略，我们的框架展现了稳健的性能。实验表明，引入布局感知搜索和重排序模块显著提升了检索准确性，最高评分达65.56。这项研究彰显了可扩展且可复现方案在推动多模态文档检索系统发展中的潜力。

> Retrieval-augmented generation (RAG) systems have predominantly focused on text-based retrieval, limiting their effectiveness in handling visually-rich documents that encompass text, images, tables, and charts. To bridge this gap, we propose a unified multi-granularity multimodal retrieval framework tailored for two benchmark tasks: MMDocIR and M2KR. Our approach integrates hierarchical encoding strategies, modality-aware retrieval mechanisms, and reranking modules to effectively capture and utilize the complex interdependencies between textual and visual modalities. By leveraging off-the-shelf vision-language models and implementing a training-free hybridretrieval strategy, our framework demonstrates robust performance without the need for task-specific fine-tuning. Experimental evaluations reveal that incorporating layout-aware search and reranking modules significantly enhances retrieval accuracy, achieving a top performance score of 65.56. This work underscores the potential of scalable and reproducible solutions in advancing multimodal document retrieval systems.

[Arxiv](https://arxiv.org/abs/2505.01457)