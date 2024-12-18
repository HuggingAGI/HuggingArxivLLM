# 《告诉我要跟踪什么：为增强参考多对象跟踪注入有力的语言引导》

发布时间：2024年12月17日

`其他` `多目标跟踪` `视频处理`

> Tell Me What to Track: Infusing Robust Language Guidance for Enhanced Referring Multi-Object Tracking

# 摘要

> referring multi-object tracking（RMOT）是一项新兴的跨模态任务，旨在依据语言表述在视频里定位任意数量的目标，并持续追踪它们。这一复杂任务包含对多模态数据的推理以及具有时间关联的精准目标定位。然而，由于任务的特性，先前的研究忽略了新生目标与现有目标间数据分布的不平衡。另外，它们只是间接融合多模态特征，难以给新生目标检测提供清晰的指引。为解决上述问题，我们采用了协同匹配策略来减轻不平衡带来的影响，提升新生目标的检测能力，同时保持跟踪性能。在编码器中，我们整合并强化了跨模态和多尺度融合，突破了先前工作中特征图之间多模态信息共享和交互有限的瓶颈。在解码器中，我们还开发了一种引用注入式的自适应，通过查询令牌提供明确的引用指导。实验表明，我们的模型性能优越（+3.42%），优于先前的工作，证明了我们设计的有效性。

> Referring multi-object tracking (RMOT) is an emerging cross-modal task that aims to localize an arbitrary number of targets based on a language expression and continuously track them in a video. This intricate task involves reasoning on multi-modal data and precise target localization with temporal association. However, prior studies overlook the imbalanced data distribution between newborn targets and existing targets due to the nature of the task. In addition, they only indirectly fuse multi-modal features, struggling to deliver clear guidance on newborn target detection. To solve the above issues, we conduct a collaborative matching strategy to alleviate the impact of the imbalance, boosting the ability to detect newborn targets while maintaining tracking performance. In the encoder, we integrate and enhance the cross-modal and multi-scale fusion, overcoming the bottlenecks in previous work, where limited multi-modal information is shared and interacted between feature maps. In the decoder, we also develop a referring-infused adaptation that provides explicit referring guidance through the query tokens. The experiments showcase the superior performance of our model (+3.42%) compared to prior works, demonstrating the effectiveness of our designs.

[Arxiv](https://arxiv.org/abs/2412.12561)