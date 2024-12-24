# 用于少样本异常检测的内核感知图提示学习

发布时间：2024年12月23日

`其他` `计算机视觉` `异常检测`

> Kernel-Aware Graph Prompt Learning for Few-Shot Anomaly Detection

# 摘要

> 少样本异常检测（FSAD）旨在借助同一类别的极少数正常支持图像的引导，检测未曾见过的异常区域。现有的 FSAD 方法通常直接设计复杂的文本提示，在主流的大型视觉语言模型范式下将其与视觉特征对齐来发现异常。然而，这些方法几乎都忽略了视觉特征中的内在上下文信息，比如不同视觉层之间的相互作用关系，而这是全面检测异常的关键线索。为此，我们提出了一个名为 KAG-prompt 的内核感知图提示学习框架，用于推理视觉特征的跨层关系以实现 FSAD。具体而言，将关注不同大小异常区域的不同层特征作为节点构建内核感知分层图，同时，任意节点对之间的关系即为图的边。通过在该图上进行消息传递，KAG-prompt 能够捕获跨层上下文信息，从而实现更精准的异常预测。此外，为整合预测图中多个重要异常信号的信息，我们提出了一种基于多级信息融合的新型图像级评分方法。在 MVTecAD 和 VisA 数据集上的大量实验表明，KAG-prompt 在图像级/像素级异常检测方面取得了最先进的 FSAD 成果。代码可在 https://github.com/CVL-hub/KAG-prompt.git 获取。

> Few-shot anomaly detection (FSAD) aims to detect unseen anomaly regions with the guidance of very few normal support images from the same class. Existing FSAD methods usually find anomalies by directly designing complex text prompts to align them with visual features under the prevailing large vision-language model paradigm. However, these methods, almost always, neglect intrinsic contextual information in visual features, e.g., the interaction relationships between different vision layers, which is an important clue for detecting anomalies comprehensively. To this end, we propose a kernel-aware graph prompt learning framework, termed as KAG-prompt, by reasoning the cross-layer relations among visual features for FSAD. Specifically, a kernel-aware hierarchical graph is built by taking the different layer features focusing on anomalous regions of different sizes as nodes, meanwhile, the relationships between arbitrary pairs of nodes stand for the edges of the graph. By message passing over this graph, KAG-prompt can capture cross-layer contextual information, thus leading to more accurate anomaly prediction. Moreover, to integrate the information of multiple important anomaly signals in the prediction map, we propose a novel image-level scoring method based on multi-level information fusion. Extensive experiments on MVTecAD and VisA datasets show that KAG-prompt achieves state-of-the-art FSAD results for image-level/pixel-level anomaly detection. Code is available at https://github.com/CVL-hub/KAG-prompt.git.

[Arxiv](https://arxiv.org/abs/2412.17619)