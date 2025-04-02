# 通过类似R1-Zero的训练方法，提升视觉空间推理能力

发布时间：2025年04月01日

`LLM应用` `视觉-空间智能` `多模态模型`

> Improved Visual-Spatial Reasoning via R1-Zero-Like Training

# 摘要

> 近期，提升多模态大型语言模型（MLLMs）推理能力的研究受到了越来越多的关注。作为在物理世界中运行的AI代理的基础，基于视频的视觉-空间智能（VSI）成为了MLLMs中最关键的推理能力之一。本研究首次深入探讨了通过类似于R1-Zero的训练方法提升MLLMs的视觉-空间推理能力。

在技术层面，我们首先发现小型至中型的Qwen2-VL模型无法通过Chain of Thought（CoT）提示激活其视觉-空间推理能力。随后，我们借鉴DeepSeek-R1-Zero的方法，利用精心整理的VSI-100k数据集，引入了GRPO训练以提升视觉-空间推理能力。在研究过程中，我们发现即使使用较小的惩罚值，保持KL惩罚项也是必要的。

仅需120个GPU小时的训练时间，我们的vsGRPO-2B模型（基于Qwen2-VL-2B微调）就能比基础模型提升12.1%的性能，并超越GPT-4o。此外，我们的vsGRPO-7B模型（基于Qwen2-VL-7B微调）的性能可与开源最佳模型LLaVA-NeXT-Video-72B相媲美。同时，我们将vsGRPO与监督微调和直接偏好优化基准进行了对比，发现其表现出显著的性能优势。

代码和数据集即将发布。

> Increasing attention has been placed on improving the reasoning capacities of multi-modal large language models (MLLMs). As the cornerstone for AI agents that function in the physical realm, video-based visual-spatial intelligence (VSI) emerges as one of the most pivotal reasoning capabilities of MLLMs. This work conducts a first, in-depth study on improving the visual-spatial reasoning of MLLMs via R1-Zero-like training. Technically, we first identify that the visual-spatial reasoning capacities of small- to medium-sized Qwen2-VL models cannot be activated via Chain of Thought (CoT) prompts. We then incorporate GRPO training for improved visual-spatial reasoning, using the carefully curated VSI-100k dataset, following DeepSeek-R1-Zero. During the investigation, we identify the necessity to keep the KL penalty (even with a small value) in GRPO. With just 120 GPU hours, our vsGRPO-2B model, fine-tuned from Qwen2-VL-2B, can outperform the base model by 12.1% and surpass GPT-4o. Moreover, our vsGRPO-7B model, fine-tuned from Qwen2-VL-7B, achieves performance comparable to that of the best open-source model LLaVA-NeXT-Video-72B. Additionally, we compare vsGRPO to supervised fine-tuning and direct preference optimization baselines and observe strong performance superiority. The code and dataset will be available soon.

[Arxiv](https://arxiv.org/abs/2504.00883)