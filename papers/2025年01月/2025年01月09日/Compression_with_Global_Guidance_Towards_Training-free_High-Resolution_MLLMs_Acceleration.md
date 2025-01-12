# # 全局引导的压缩：实现无需训练的高分辨率多模态大模型加速

发布时间：2025年01月09日

`LLM应用

理由：这篇论文主要讨论的是多模态大型语言模型（MLLMs）在视觉内容理解和推理中的应用，特别是针对其推理效率问题的改进方法。论文提出了一种新的标记压缩方法GlobalCom$^2$，旨在提高MLLMs在高分辨率图像理解中的效率。虽然涉及到了模型的理论改进，但核心关注点仍然是模型在实际应用中的性能优化和效率提升，因此归类为LLM应用更为合适。` `计算机视觉`

> Compression with Global Guidance: Towards Training-free High-Resolution MLLMs Acceleration

# 摘要

> # 摘要
多模态大型语言模型（MLLMs）在视觉内容理解和推理方面表现出色，但其推理效率问题备受关注，尤其是随着多模态上下文长度的增加，计算复杂度呈二次增长。标记压缩技术通过减少视觉标记数量，有效降低了计算成本。然而，这些方法难以跟上MLLMs的快速发展，特别是在高分辨率图像理解中的AnyRes策略背景下。本文提出了一种新颖的标记压缩方法GlobalCom$^2$，专为接收缩略图和多个裁剪的高分辨率MLLMs设计。GlobalCom$^2$将缩略图标记视为整个压缩过程的“指挥官”，指导保留比例的分配和每个裁剪的具体压缩，从而在消除冗余标记的同时，尽可能保留重要局部细节。在10个基准测试中，GlobalCom$^2$在性能和效率之间实现了最佳平衡，并在使用LLaVA-NeXT-7B/13B模型时始终优于现有标记压缩方法。代码已发布在url{https://github.com/xuyang-liu16/GlobalCom2}。

> Multimodal large language models (MLLMs) have attracted considerable attention due to their exceptional performance in visual content understanding and reasoning. However, their inference efficiency has been a notable concern, as the increasing length of multimodal contexts leads to quadratic complexity. Token compression techniques, which reduce the number of visual tokens, have demonstrated their effectiveness in reducing computational costs. Yet, these approaches have struggled to keep pace with the rapid advancements in MLLMs, especially the AnyRes strategy in the context of high-resolution image understanding. In this paper, we propose a novel token compression method, GlobalCom$^2$, tailored for high-resolution MLLMs that receive both the thumbnail and multiple crops. GlobalCom$^2$ treats the tokens derived from the thumbnail as the ``commander'' of the entire token compression process, directing the allocation of retention ratios and the specific compression for each crop. In this way, redundant tokens are eliminated while important local details are adaptively preserved to the highest extent feasible. Empirical results across 10 benchmarks reveal that GlobalCom$^2$ achieves an optimal balance between performance and efficiency, and consistently outperforms state-of-the-art token compression methods with LLaVA-NeXT-7B/13B models. Our code is released at url{https://github.com/xuyang-liu16/GlobalCom2}.

[Arxiv](https://arxiv.org/abs/2501.05179)