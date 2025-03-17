# TikZero：零样本文本引导图形程序合成

发布时间：2025年03月14日

`LLM应用` `生成式AI` `计算机图形学`

> TikZero: Zero-Shot Text-Guided Graphics Program Synthesis

# 摘要

> 生成式 AI 的兴起让从文字描述生成图形成为可能，但要实现高精度和可编辑性，需将图形表示为 TikZ 等语言的程序，而这类对齐数据却十分稀少。不过，大量未对齐的图形程序和带描述的栅格图像随手可得。我们推出 TikZero，通过图像表示作为桥梁，将图形生成与文本理解分离，从而实现独立训练，并在推理时进行零样本文本引导的图形合成。实验表明，TikZero 在仅使用对齐数据的模型中表现最佳。更厉害的是，结合对齐数据训练时，TikZero 的表现可与 GPT-4o 等大型商业系统比肩。我们的代码、数据集和模型已开源。

> With the rise of generative AI, synthesizing figures from text captions becomes a compelling application. However, achieving high geometric precision and editability requires representing figures as graphics programs in languages like TikZ, and aligned training data (i.e., graphics programs with captions) remains scarce. Meanwhile, large amounts of unaligned graphics programs and captioned raster images are more readily available. We reconcile these disparate data sources by presenting TikZero, which decouples graphics program generation from text understanding by using image representations as an intermediary bridge. It enables independent training on graphics programs and captioned images and allows for zero-shot text-guided graphics program synthesis during inference. We show that our method substantially outperforms baselines that can only operate with caption-aligned graphics programs. Furthermore, when leveraging caption-aligned graphics programs as a complementary training signal, TikZero matches or exceeds the performance of much larger models, including commercial systems like GPT-4o. Our code, datasets, and select models are publicly available.

[Arxiv](https://arxiv.org/abs/2503.11509)