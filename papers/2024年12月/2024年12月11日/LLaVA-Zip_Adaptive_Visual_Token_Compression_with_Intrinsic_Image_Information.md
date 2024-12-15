# LLaVA-Zip：借助内在图像信息的自适应视觉标记压缩

发布时间：2024年12月11日

`LLM应用`

> LLaVA-Zip: Adaptive Visual Token Compression with Intrinsic Image Information

# 摘要

> 多模态大型语言模型（MLLMs），像利用了遵循指令数据的 LLaVA 等，在业界已取得显著进展。然而，这类模型存在一个主要局限，即视觉标记在大型语言模型（LLMs）的最大标记限制中占据大量份额，当提示包含多个图像或视频时，会致使计算需求上升、性能降低。行业里往往通过提升计算能力来应对此问题，但在资源有限的学术环境中，这种方式可行性不高。本研究基于 LLaVA-1.5 提出了动态特征图压缩（DFMR），旨在解决视觉标记过载的难题。DFMR 能动态压缩视觉标记，释放标记容量。我们的实验结果显示，将 DFMR 融入 LLaVA-1.5 显著提升了 LLaVA 在不同视觉标记长度下的性能，为在资源受限的学术环境中拓展 LLaVA 以处理多图像和视频场景提供了颇具前景的解决方案，同时它也能在行业环境中用于数据增强，有助于缓解持续预训练阶段开放域图像 - 文本对数据集的稀缺状况。

> Multi-modal large language models (MLLMs) utilizing instruction-following data, such as LLaVA, have achieved great progress in the industry. A major limitation in these models is that visual tokens consume a substantial portion of the maximum token limit in large language models (LLMs), leading to increased computational demands and decreased performance when prompts include multiple images or videos. Industry solutions often mitigate this issue by increasing computational power, but this approach is less feasible in academic environments with limited resources. In this study, we propose Dynamic Feature Map Reduction (DFMR) based on LLaVA-1.5 to address the challenge of visual token overload. DFMR dynamically compresses the visual tokens, freeing up token capacity. Our experimental results demonstrate that integrating DFMR into LLaVA-1.5 significantly improves the performance of LLaVA in varied visual token lengths, offering a promising solution for extending LLaVA to handle multi-image and video scenarios in resource-constrained academic environments and it can also be applied in industry settings for data augmentation to help mitigate the scarcity of open-domain image-text pair datasets in the continued pretraining stage.

[Arxiv](https://arxiv.org/abs/2412.08771)