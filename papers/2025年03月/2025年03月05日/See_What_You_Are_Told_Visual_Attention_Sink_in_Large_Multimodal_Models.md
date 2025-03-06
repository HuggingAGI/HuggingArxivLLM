# 看见即所知：大型多模态模型中的视觉注意力机制

发布时间：2025年03月05日

`LLM理论` `计算机视觉` `多模态学习`

> See What You Are Told: Visual Attention Sink in Large Multimodal Models

# 摘要

> 大型多模态模型（LMMs）通过 transformer 解码器中的文本-视觉标记注意力机制来“观察”图像。理想状态下，这些模型应聚焦于与文本相关的视觉信息。然而，最新研究发现，LMMs 存在一种独特倾向：即使某些视觉标记与文本无关，模型也会持续赋予这些标记高注意力权重。本研究深入探讨了这一现象背后的机制，发现这种行为源于特定隐藏状态维度的过度激活，与语言模型中的“注意力陷阱”机制类似。因此，我们将其命名为“视觉注意力陷阱”。有趣的是，尽管这些无关视觉标记获得了高注意力权重，但移除它们并不会影响模型性能。基于此，我们提出了一种创新解决方案：将这些标记的注意力视为冗余资源进行回收，重新分配注意力预算以增强模型对图像的关注。为此，我们开发了视觉注意力重分配（VAR）方法，专注于以图像为中心的注意力头（这些头天然专注于视觉信息）。VAR 具有广泛的适用性，可无缝应用于各类 LMMs，无需额外训练或推理步骤，即可显著提升包括通用视觉-语言任务、视觉幻觉任务和视觉中心任务在内的多项任务性能。实验结果表明，VAR 通过优化 LMMs 的内部注意力机制，显著提升了视觉信息的处理效率，为增强 LMMs 的多模态能力开辟了新方向。

> Large multimodal models (LMMs) "see" images by leveraging the attention mechanism between text and visual tokens in the transformer decoder. Ideally, these models should focus on key visual information relevant to the text token. However, recent findings indicate that LMMs have an extraordinary tendency to consistently allocate high attention weights to specific visual tokens, even when these tokens are irrelevant to the corresponding text. In this study, we investigate the property behind the appearance of these irrelevant visual tokens and examine their characteristics. Our findings show that this behavior arises due to the massive activation of certain hidden state dimensions, which resembles the attention sink found in language models. Hence, we refer to this phenomenon as the visual attention sink. In particular, our analysis reveals that removing the irrelevant visual sink tokens does not impact model performance, despite receiving high attention weights. Consequently, we recycle the attention to these tokens as surplus resources, redistributing the attention budget to enhance focus on the image. To achieve this, we introduce Visual Attention Redistribution (VAR), a method that redistributes attention in image-centric heads, which we identify as innately focusing on visual information. VAR can be seamlessly applied across different LMMs to improve performance on a wide range of tasks, including general vision-language tasks, visual hallucination tasks, and vision-centric tasks, all without the need for additional training, models, or inference steps. Experimental results demonstrate that VAR enables LMMs to process visual information more effectively by adjusting their internal attention mechanisms, offering a new direction to enhancing the multimodal capabilities of LMMs.

[Arxiv](https://arxiv.org/abs/2503.03321)