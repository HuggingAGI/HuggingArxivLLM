# PRIMA：用于推理分割的多图像视觉语言模型

发布时间：2024年12月19日

`LLM应用` `计算机视觉` `图像理解`

> PRIMA: Multi-Image Vision-Language Models for Reasoning Segmentation

# 摘要

> 尽管大型视觉语言模型（LVLMs）进步显著，可现有的像素基础模型仅适用于单图像场景，这限制了它们在多图像间进行细致、细粒度比较的能力。反之，当下的多图像理解模型缺少像素级基础。我们的工作致力于填补这一空缺，引入了多图像像素基础推理分割任务以及 PRIMA，这是一种新型的 LVLM，它将像素级基础与强大的多图像推理能力相融合，从而生成富含上下文、基于像素的解释。PRIMA 的关键在于一个高效的视觉模块，能查询多图像中的细粒度视觉表征，使 TFLOPs 降低 25.3%。为支持训练和评估，我们整理了 $M^4Seg$，这是一个新的推理分割基准，包含约 224K 个问答对，需要对多图像进行细粒度的视觉理解。实验结果显示，PRIMA 优于现有的先进基线。

> Despite significant advancements in Large Vision-Language Models (LVLMs), existing pixel-grounding models operate on single-image settings, limiting their ability to perform detailed, fine-grained comparisons across multiple images. Conversely, current multi-image understanding models lack pixel-level grounding. Our work addresses this gap by introducing the task of multi-image pixel-grounded reasoning segmentation, and PRIMA, a novel LVLM that integrates pixel-level grounding with robust multi-image reasoning capabilities to produce contextually rich, pixel-grounded explanations. Central to PRIMA is an efficient vision module that queries fine-grained visual representations across multiple images, reducing TFLOPs by $25.3\%$. To support training and evaluation, we curate $M^4Seg$, a new reasoning segmentation benchmark consisting of $\sim$224K question-answer pairs that require fine-grained visual understanding across multiple images. Experimental results demonstrate PRIMA outperforms state-of-the-art baselines.

[Arxiv](https://arxiv.org/abs/2412.15209)