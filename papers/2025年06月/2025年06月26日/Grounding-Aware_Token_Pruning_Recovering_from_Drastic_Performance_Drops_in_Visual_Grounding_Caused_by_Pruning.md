# 基于接地感知的标记剪枝：解决由剪枝引发的视觉定位性能骤降问题。

发布时间：2025年06月26日

`LLM应用` `计算机视觉`

> Grounding-Aware Token Pruning: Recovering from Drastic Performance Drops in Visual Grounding Caused by Pruning

# 摘要

> 近期的多模态大型语言模型（MLLMs）在视觉定位任务中表现出了强大的能力，确立了其作为各类视觉-语言应用通用接口的地位。这一进展推动了旨在缓解处理大量视觉Token所带来高昂计算成本的Token剪枝方法的发展。然而，我们观察到剪枝会显著削弱模型的定位能力，导致错误预测和性能急剧下降。以指代表达理解（REC）为例，剪枝会导致LLaVA在RefCOCO验证集上的准确率从56.14%降至15.34%。我们的分析表明，剪枝后不一致的位置ID是性能下降的主要原因，因为这些ID的顺序和值对保持定位任务的性能至关重要。为了解决这一问题，我们提出了基于定位感知的Token剪枝方法（GAP），这是一种简单但有效的调整位置ID的方法，能够将REC准确率恢复至51.42%，达到无剪枝设置下性能的90%，同时无需额外的训练、内存或计算开销。该方法在Shikra、MiniGPTv2以及LLaVA系列模型上应用时，始终能提升各种Token剪枝策略下的性能表现。

> Recent Multimodal Large Language Models (MLLMs) have demonstrated strong performance in visual grounding, establishing themselves as a general interface for various vision-language applications. This progress has driven the development of token pruning methods to mitigate the high computational costs associated with processing numerous visual tokens. However, we observe that pruning significantly weakens the model's grounding ability, leading to incorrect predictions and drastic performance degradation. In Referring Expression Comprehension (REC), for instance, pruning causes the accuracy of LLaVA on the RefCOCO validation set to drop from 56.14% to 15.34%. Our analysis identifies misaligned position IDs after pruning as the primary cause of this degradation, as both the order and value of these IDs are crucial for maintaining performance in grounding tasks. To address this issue, we propose Grounding-Aware Token Pruning (GAP), a simple yet effective adjustment to position IDs that recovers REC accuracy back to 51.42%, which is 90% of the original performance in the without pruning setting, all while requiring no additional training, memory, or computational overhead. Applied to models such as Shikra, MiniGPTv2, and the LLaVA series, our method consistently improves performance across various token pruning strategies.

[Arxiv](https://arxiv.org/abs/2506.21873)