# AD-DINOv3：基于异常感知校准的DINOv3零样本异常检测增强方法

发布时间：2025年09月17日

`其他` `工业与制造` `医疗健康`

> AD-DINOv3: Enhancing DINOv3 for Zero-Shot Anomaly Detection with Anomaly-Aware Calibration

# 摘要

> 零样本异常检测（ZSAD）致力于从任意新类别中识别异常，是一种兼具可扩展性与标注高效性的解决方案。传统上，多数ZSAD研究基于CLIP模型，该模型通过计算视觉与文本嵌入的相似度实现异常检测。近年来，DINOv3等视觉基础模型展现出卓越的可迁移表征能力。本研究首次将DINOv3适配于ZSAD任务，然而这一适配面临两大核心挑战：（i）大规模预训练数据与异常检测任务间存在领域偏差，导致特征错位；（ii）预训练表征对全局语义的固有偏向常使细微异常被误判为正常前景对象的一部分，而非被识别为异常区域。

为应对这些挑战，我们提出AD-DINOv3——一种专为ZSAD打造的新型视觉-语言多模态框架。具体而言，我们将异常检测构建为多模态对比学习问题：DINOv3作为视觉主干提取补丁令牌与CLS令牌，CLIP文本编码器则为正常及异常提示生成嵌入。为弥合领域差距，我们在两种模态中引入轻量级适配器，使其表征可针对异常检测任务重新校准。在基线对齐基础上，我们进一步设计异常感知校准模块（AACM），它能明确引导CLS令牌聚焦异常区域而非通用前景语义，进而提升区分能力。

在八个工业与医疗基准数据集上的大量实验证实，AD-DINOv3性能持续媲美甚至超越现有最优方法，充分证明其作为通用零样本异常检测框架的优越性。

> Zero-Shot Anomaly Detection (ZSAD) seeks to identify anomalies from arbitrary novel categories, offering a scalable and annotation-efficient solution. Traditionally, most ZSAD works have been based on the CLIP model, which performs anomaly detection by calculating the similarity between visual and text embeddings. Recently, vision foundation models such as DINOv3 have demonstrated strong transferable representation capabilities. In this work, we are the first to adapt DINOv3 for ZSAD. However, this adaptation presents two key challenges: (i) the domain bias between large-scale pretraining data and anomaly detection tasks leads to feature misalignment; and (ii) the inherent bias toward global semantics in pretrained representations often leads to subtle anomalies being misinterpreted as part of the normal foreground objects, rather than being distinguished as abnormal regions. To overcome these challenges, we introduce AD-DINOv3, a novel vision-language multimodal framework designed for ZSAD. Specifically, we formulate anomaly detection as a multimodal contrastive learning problem, where DINOv3 is employed as the visual backbone to extract patch tokens and a CLS token, and the CLIP text encoder provides embeddings for both normal and abnormal prompts. To bridge the domain gap, lightweight adapters are introduced in both modalities, enabling their representations to be recalibrated for the anomaly detection task. Beyond this baseline alignment, we further design an Anomaly-Aware Calibration Module (AACM), which explicitly guides the CLS token to attend to anomalous regions rather than generic foreground semantics, thereby enhancing discriminability. Extensive experiments on eight industrial and medical benchmarks demonstrate that AD-DINOv3 consistently matches or surpasses state-of-the-art methods, verifying its superiority as a general zero-shot anomaly detection framework.

[Arxiv](https://arxiv.org/abs/2509.14084)