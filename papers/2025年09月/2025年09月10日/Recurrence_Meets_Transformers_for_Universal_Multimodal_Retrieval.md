# 循环邂逅Transformer：助力通用多模态检索

发布时间：2025年09月10日

`RAG` `基础理论`

> Recurrence Meets Transformers for Universal Multimodal Retrieval

# 摘要

> 随着多模态检索技术在大型语言模型（LLMs）及多模态大型语言模型中的应用迅猛发展，日益复杂的检索任务不断涌现。现有方法大多依赖视觉-语言模型的特定任务微调，且局限于单模态的查询或文档。本文提出ReT-2——一种支持多模态查询（融合图像与文本）的统一检索模型，能够在文本与图像共存的多模态文档集合中进行检索。ReT-2采用多层表示与带LSTM启发门控机制的循环Transformer架构，动态整合跨层与跨模态信息，精准捕捉细粒度的视觉与文本细节。我们在极具挑战性的M2KR和M-BEIR基准上，针对不同检索配置对ReT-2展开评估。结果显示，ReT-2在不同设置下均稳居最先进性能水平，且相比现有方法，推理速度更快、内存占用更少。将ReT-2集成到检索增强生成流水线后，其在Encyclopedic-VQA和InfoSeek数据集上也显著提升了下游任务性能。我们的源代码与训练模型已公开，地址为：https://github.com/aimagelab/ReT-2

> With the rapid advancement of multimodal retrieval and its application in LLMs and multimodal LLMs, increasingly complex retrieval tasks have emerged. Existing methods predominantly rely on task-specific fine-tuning of vision-language models and are limited to single-modality queries or documents. In this paper, we propose ReT-2, a unified retrieval model that supports multimodal queries, composed of both images and text, and searches across multimodal document collections where text and images coexist. ReT-2 leverages multi-layer representations and a recurrent Transformer architecture with LSTM-inspired gating mechanisms to dynamically integrate information across layers and modalities, capturing fine-grained visual and textual details. We evaluate ReT-2 on the challenging M2KR and M-BEIR benchmarks across different retrieval configurations. Results demonstrate that ReT-2 consistently achieves state-of-the-art performance across diverse settings, while offering faster inference and reduced memory usage compared to prior approaches. When integrated into retrieval-augmented generation pipelines, ReT-2 also improves downstream performance on Encyclopedic-VQA and InfoSeek datasets. Our source code and trained models are publicly available at: https://github.com/aimagelab/ReT-2

[Arxiv](https://arxiv.org/abs/2509.08897)