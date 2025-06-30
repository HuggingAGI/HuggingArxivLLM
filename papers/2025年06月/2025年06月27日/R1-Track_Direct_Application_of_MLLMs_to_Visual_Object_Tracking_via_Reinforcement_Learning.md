# R1-Track：直接应用多语言模型（MLLMs）实现视觉目标追踪的强化学习方法

发布时间：2025年06月27日

`LLM应用` `视觉单目标跟踪` `计算机视觉` `人工智能`

> R1-Track: Direct Application of MLLMs to Visual Object Tracking via Reinforcement Learning

# 摘要

> 视觉单目标跟踪的目标是：在仅知道初始状态的情况下，持续定位并估计目标在后续视频帧中的尺度。这一任务传统上被视为一个模板匹配问题，经历了基于相关滤波器、双流网络以及单流网络的几个重要阶段，并取得了显著进展。然而，这些方法存在以下局限：需要显式的分类和回归建模，依赖大规模数据集的监督训练，且仅适用于单一的跟踪任务，缺乏灵活性。近年来，多模态大型语言模型（MLLMs）发展迅猛。以开源模型Qwen2.5-VL为代表的旗舰MLLMs，凭借其强大的基础能力，在接地任务中表现卓越。这激发了将此类模型直接应用于视觉跟踪的尝试。然而，实验表明，Qwen2.5-VL在图像对之间的模板匹配（即跟踪任务）上表现欠佳。受deepseek-R1启发，我们在小规模数据集上采用基于规则奖励函数的组相对策略优化（GRPO）强化学习方法对Qwen2.5-VL进行了微调。由此得到的R1-Track模型在GOT-10k基准上取得了显著性能。R1-Track支持通过边界框或文本描述进行灵活初始化，同时保留了原模型的大部分通用能力。此外，我们还探讨了R1-Track的潜在改进方向。这份简要技术报告总结了截至2025年5月的研究成果。

> Visual single object tracking aims to continuously localize and estimate the scale of a target in subsequent video frames, given only its initial state in the first frame. This task has traditionally been framed as a template matching problem, evolving through major phases including correlation filters, two-stream networks, and one-stream networks with significant progress achieved. However, these methods typically require explicit classification and regression modeling, depend on supervised training with large-scale datasets, and are limited to the single task of tracking, lacking flexibility. In recent years, multi-modal large language models (MLLMs) have advanced rapidly. Open-source models like Qwen2.5-VL, a flagship MLLMs with strong foundational capabilities, demonstrate excellent performance in grounding tasks. This has spurred interest in applying such models directly to visual tracking. However, experiments reveal that Qwen2.5-VL struggles with template matching between image pairs (i.e., tracking tasks). Inspired by deepseek-R1, we fine-tuned Qwen2.5-VL using the group relative policy optimization (GRPO) reinforcement learning method on a small-scale dataset with a rule-based reward function. The resulting model, R1-Track, achieved notable performance on the GOT-10k benchmark. R1-Track supports flexible initialization via bounding boxes or text descriptions while retaining most of the original model's general capabilities. And we further discuss potential improvements for R1-Track. This rough technical report summarizes our findings as of May 2025.

[Arxiv](https://arxiv.org/abs/2506.21980)