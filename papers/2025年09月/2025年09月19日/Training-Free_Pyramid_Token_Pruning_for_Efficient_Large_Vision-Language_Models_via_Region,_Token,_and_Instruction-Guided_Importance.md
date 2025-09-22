# 无需训练的金字塔式令牌剪枝：基于区域、令牌与指令引导的重要性实现高效大型视觉语言模型

发布时间：2025年09月19日

`LLM应用` `基础理论`

> Training-Free Pyramid Token Pruning for Efficient Large Vision-Language Models via Region, Token, and Instruction-Guided Importance

# 摘要

> 大型视觉语言模型（LVLMs）极大推动了多模态理解的发展，但在高效处理高分辨率图像时仍面临挑战。近期方法将高分辨率图像分割成多个子图，这会大幅增加视觉标记数量，并在推理时带来指数级计算开销。为解决这些问题，我们提出一种无需训练的标记剪枝策略——金字塔标记剪枝（PTP），它融合了区域和标记级别的自底向上视觉显著性与自顶向下的指令引导重要性。借鉴人类视觉注意机制，PTP会选择性保留视觉显著区域的更多标记，并进一步利用文本指令精确定位与特定多模态任务最相关的标记。在13个不同基准上的大量实验显示，我们的方法能在性能损失极小的情况下，大幅降低计算开销和推理延迟。

> Large Vision-Language Models (LVLMs) have significantly advanced multimodal understanding but still struggle with efficiently processing high-resolution images. Recent approaches partition high-resolution images into multiple sub-images, dramatically increasing the number of visual tokens and causing exponential computational overhead during inference. To address these limitations, we propose a training-free token pruning strategy, Pyramid Token Pruning (PTP), that integrates bottom-up visual saliency at both region and token levels with top-down instruction-guided importance. Inspired by human visual attention mechanisms, PTP selectively retains more tokens from visually salient regions and further leverages textual instructions to pinpoint tokens most relevant to specific multimodal tasks. Extensive experiments across 13 diverse benchmarks demonstrate that our method substantially reduces computational overhead and inference latency with minimal performance loss.

[Arxiv](https://arxiv.org/abs/2509.15704)