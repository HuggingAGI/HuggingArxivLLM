# VidHalluc：评估多模态大型语言模型在视频理解中的时间幻觉

发布时间：2024年12月04日

`LLM应用` `人工智能`

> VidHalluc: Evaluating Temporal Hallucinations in Multimodal Large Language Models for Video Understanding

# 摘要

> 多模态大型语言模型（MLLMs）近来在视频理解领域进展显著，于内容推理和遵循指令的任务中表现出众。然而，幻觉问题，也就是模型生成不准确或有误导性内容的情况，在视频领域尚未得到充分探究。鉴于 MLLMs 的视觉编码器常常难以区分视觉有别但语义相近的视频对这一现象，我们推出了 VidHalluc，这是用于检验 MLLMs 在视频理解任务中幻觉情况的最大基准。VidHalluc 从三个关键维度评估幻觉：（1）动作；（2）时间序列；（3）场景转换。VidHalluc 由 5002 个视频组成，依据语义相似性和视觉差异进行配对，聚焦于最可能产生幻觉的情形。经过全面测试，我们的实验表明，多数 MLLMs 在这些维度上都易出现幻觉。此外，我们提出了 DINO-HEAL，这是一种无需训练的方法，它在推理时融入来自 DINOv2 的空间显著信息来重新加权视觉特征，从而减少幻觉。我们的结果显示，DINO-HEAL 在 VidHalluc 上持续提升性能，在所有任务中减轻幻觉方面平均提升了 3.02%。VidHalluc 基准和 DINO-HEAL 代码均可通过 $\href{https://vid-halluc.github.io/}{	ext{此链接}}$ 获取。

> Multimodal large language models (MLLMs) have recently shown significant advancements in video understanding, excelling in content reasoning and instruction-following tasks. However, the problem of hallucination, where models generate inaccurate or misleading content, remains underexplored in the video domain. Building on the observation that the visual encoder of MLLMs often struggles to differentiate between video pairs that are visually distinct but semantically similar, we introduce VidHalluc, the largest benchmark designed to examine hallucinations in MLLMs for video understanding tasks. VidHalluc assesses hallucinations across three critical dimensions: (1) action, (2) temporal sequence, and (3) scene transition. VidHalluc consists of 5,002 videos, paired based on semantic similarity and visual differences, focusing on cases where hallucinations are most likely to occur. Through comprehensive testing, our experiments show that most MLLMs are vulnerable to hallucinations across these dimensions. Furthermore, we propose DINO-HEAL, a training-free method that reduces hallucinations by incorporating spatial saliency information from DINOv2 to reweight visual features during inference. Our results demonstrate that DINO-HEAL consistently improves performance on VidHalluc, achieving an average improvement of 3.02% in mitigating hallucinations among all tasks. Both the VidHalluc benchmark and DINO-HEAL code can be accessed via $\href{https://vid-halluc.github.io/}{\text{this link}}$.

[Arxiv](https://arxiv.org/abs/2412.03735)