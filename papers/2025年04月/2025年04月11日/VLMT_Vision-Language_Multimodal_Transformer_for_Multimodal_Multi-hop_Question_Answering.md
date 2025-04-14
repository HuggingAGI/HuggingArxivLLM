# VLMT：视觉-语言多模态变换器，专为多模态多跳问答设计

发布时间：2025年04月11日

`其他` `信息检索` `问答系统`

> VLMT: Vision-Language Multimodal Transformer for Multimodal Multi-hop Question Answering

# 摘要

> 文本、表格和图像等多模态数据的普及带来了开发复杂跨模态推理模型的新挑战。现有方法在处理这类任务时往往面临推理能力有限、依赖模态转换以及视觉与文本表示对齐不足的问题。本文提出了一种统一架构——视觉-语言多模态变换器（VLMT），它将基于Transformer的视觉编码器与序列到序列语言模型相结合。VLMT通过直接的token级注入机制，在共享嵌入空间中融合视觉和文本输入，无需中间投影层。我们还提出了一种三阶段预训练策略，逐步对齐视觉-语言表示，提升模型的多模态理解能力。基于预训练主干模型，我们构建了一个两阶段MMQA框架：一个多模态重排序器用于预测文档相关性并检索上下文；一个多模态问答模型用于生成基于证据的答案。实验结果表明，VLMT-Large在MultimodalQA验证集上实现了76.5%的Exact Match和80.1%的F1，分别比现有方法高出+9.1%和+8.8%。在WebQA上，其得分达到47.6，超越了包括PERQA在内的先前模型。这些结果证明了VLMT在多模态推理方面的强大能力，为推动现实世界的信息检索和问答系统提供了新思路。

> The increasing availability of multimodal data across text, tables, and images presents new challenges for developing models capable of complex cross-modal reasoning. Existing methods for Multimodal Multi-hop Question Answering (MMQA) often suffer from limited reasoning capabilities, reliance on modality conversion, and inadequate alignment between visual and textual representations. To address these limitations, this paper introduces Vision-Language Multimodal Transformer (VLMT), a unified architecture that integrates a transformer-based vision encoder with a sequence-to-sequence language model. VLMT employs a direct token-level injection mechanism to fuse visual and textual inputs within a shared embedding space, eliminating the need for intermediate projection layers. To enhance cross-modal alignment and reasoning, a three-stage pretraining strategy is proposed to progressively align vision-language representations and improve the model's capacity for multimodal understanding. Based on the pretrained backbone, two task-specific modules are instantiated to form a two-stage MMQA framework: a multimodal reranker that predicts document relevance scores and utilizes a relative threshold with top-k strategy for context retrieval, and a multimodal question answering model that generates contextually grounded answers based on the retrieved evidence. Comprehensive experiments on two benchmark datasets demonstrate the effectiveness of the proposed approach. On MultimodalQA validation set, VLMT-Large achieves 76.5% Exact Match and 80.1% F1, outperforming the previous state-of-the-art by +9.1% in Exact Match and +8.8% in F1. On WebQA, it attains a QA score of 47.6, surpassing prior models such as PERQA by +3.2. These results highlight VLMT's strong capabilities in multimodal reasoning and its potential to advance real-world information retrieval and question answering systems.

[Arxiv](https://arxiv.org/abs/2504.08269)