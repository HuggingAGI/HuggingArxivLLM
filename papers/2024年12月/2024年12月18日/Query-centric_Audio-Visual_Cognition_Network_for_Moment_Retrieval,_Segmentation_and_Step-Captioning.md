# 以查询为核心的用于时刻检索、分割及步骤字幕的视听认知网络

发布时间：2024年12月18日

`其他` `多媒体`

> Query-centric Audio-Visual Cognition Network for Moment Retrieval, Segmentation and Step-Captioning

# 摘要

> 视频已成为互联网上备受青睐的多媒体格式。为了更优地获取视频内容，提出了新主题 HIREST，涵盖视频检索、瞬间检索、瞬间分割和步骤字幕。开创性工作选用基于预训练的 CLIP 模型用于视频检索，并将其作为多任务学习范式中其他三个挑战性任务的特征提取器。然而，由于忽视了跨模态的层次结构和关联关系，此工作难以习得用户偏好内容的综合认知。在本文中，遵循由浅入深的原则，我们提出了一个以查询为中心的视听认知（QUAG）网络，为瞬间检索、分割和步骤字幕构建可靠的多模态表示。具体而言，我们首先设计模态协同感知，通过对视觉和音频模态间的全局对比对齐和局部细粒度交互进行建模来获取丰富的视听内容。接着，我们设计了以查询为中心的认知，利用深层次的查询对浅层次的视听表示进行时间通道过滤。这能够认知用户偏好的内容，从而为三个任务获取以查询为中心的视听表示。大量实验表明，QUAG 在 HIREST 上取得了 SOTA 结果。此外，我们在基于查询的视频摘要任务上测试了 QUAG，并验证了其良好的泛化能力。

> Video has emerged as a favored multimedia format on the internet. To better gain video contents, a new topic HIREST is presented, including video retrieval, moment retrieval, moment segmentation, and step-captioning. The pioneering work chooses the pre-trained CLIP-based model for video retrieval, and leverages it as a feature extractor for other three challenging tasks solved in a multi-task learning paradigm. Nevertheless, this work struggles to learn the comprehensive cognition of user-preferred content, due to disregarding the hierarchies and association relations across modalities. In this paper, guided by the shallow-to-deep principle, we propose a query-centric audio-visual cognition (QUAG) network to construct a reliable multi-modal representation for moment retrieval, segmentation and step-captioning. Specifically, we first design the modality-synergistic perception to obtain rich audio-visual content, by modeling global contrastive alignment and local fine-grained interaction between visual and audio modalities. Then, we devise the query-centric cognition that uses the deep-level query to perform the temporal-channel filtration on the shallow-level audio-visual representation. This can cognize user-preferred content and thus attain a query-centric audio-visual representation for three tasks. Extensive experiments show QUAG achieves the SOTA results on HIREST. Further, we test QUAG on the query-based video summarization task and verify its good generalization.

[Arxiv](https://arxiv.org/abs/2412.13543)