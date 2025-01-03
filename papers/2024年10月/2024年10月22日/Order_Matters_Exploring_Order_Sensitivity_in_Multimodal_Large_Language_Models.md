# 顺序至关重要：多模态大语言模型中的顺序敏感性探究

发布时间：2024年10月22日

`LLM应用

**理由**：这篇论文主要讨论了多模态大型语言模型（MLLMs）在处理多模态输入时的性能波动问题，并提出了优化模型推理效果的具体策略。这些内容属于如何应用和改进大型语言模型（LLM）在实际任务中的表现，因此归类为LLM应用。` `人工智能` `多模态学习`

> Order Matters: Exploring Order Sensitivity in Multimodal Large Language Models

# 摘要

> 多模态大型语言模型（MLLMs）通过整合文本、图像或视频等多模态上下文来解决复杂任务。然而，我们发现，改变输入顺序会导致模型性能在高效与随机猜测之间大幅波动，这一现象在单模态（仅文本或图像）和混合模态（图像-文本对）场景中均存在。有趣的是，主流MLLMs对上下文中的特定位置（如开头和结尾）尤为敏感。基于这一发现，我们将关键视频帧和重要图像/文本内容置于这些特殊位置，显著提升了模型推理效果：视频字幕匹配任务性能平均提升14.7%，视觉问答任务提升17.8%。此外，我们提出了位置不变准确率（PIA）这一新指标，以消除MLLM评估中的顺序偏差。这些研究成果不仅深化了对多模态上下文学习（MMICL）的理解，还为在不增加计算负担的情况下优化MLLM性能提供了切实可行的策略。

> Multimodal Large Language Models (MLLMs) utilize multimodal contexts consisting of text, images, or videos to solve various multimodal tasks. However, we find that changing the order of multimodal input can cause the model's performance to fluctuate between advanced performance and random guessing. This phenomenon exists in both single-modality (text-only or image-only) and mixed-modality (image-text-pair) contexts. Furthermore, we demonstrate that popular MLLMs pay special attention to certain multimodal context positions, particularly the beginning and end. Leveraging this special attention, we place key video frames and important image/text content in special positions within the context and submit them to the MLLM for inference. This method results in average performance gains of 14.7% for video-caption matching and 17.8% for visual question answering tasks. Additionally, we propose a new metric, Position-Invariant Accuracy (PIA), to address order bias in MLLM evaluation. Our research findings contribute to a better understanding of Multi-Modal In-Context Learning (MMICL) and provide practical strategies for enhancing MLLM performance without increasing computational costs.

[Arxiv](https://arxiv.org/abs/2410.16983)