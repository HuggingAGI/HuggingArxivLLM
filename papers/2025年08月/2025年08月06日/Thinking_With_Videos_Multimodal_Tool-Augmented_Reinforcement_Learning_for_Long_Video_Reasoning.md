# 视频推理新突破：多模态工具增强的强化学习助力长视频理解

发布时间：2025年08月06日

`Agent` `视频处理` `视频理解`

> Thinking With Videos: Multimodal Tool-Augmented Reinforcement Learning for Long Video Reasoning

# 摘要

> 多模态大语言模型的视频推理能力对视频问答和时间定位等任务至关重要。尽管近期方法探索了基于文本的链式推理（CoT）在多模态模型中的应用，但这些方法在跨模态交互和幻觉控制方面存在不足，尤其在处理长视频或复杂推理链时表现更明显。

为解决这些挑战，我们提出了一种全新的端到端智能体视频推理框架——Video Intelligence via Tool-Augmented Learning（VITAL）。借助视觉工具箱，该模型能够按需密集采样新视频帧，并生成多模态链式推理以实现精准的长视频推理。

我们发现，时间定位和问答任务在视频理解任务中相辅相成。因此，我们构建了两个高质量的多任务视频推理数据集：MTVR-CoT-72k用于监督微调，MTVR-RL-110k用于强化学习。此外，我们提出了一种难度感知组相对策略优化算法（DGRPO），以缓解多任务强化学习中的难度失衡问题。

在11个具有挑战性的视频理解基准测试中，VITAL展现了卓越的推理能力，尤其在长视频场景下，视频问答和时间定位任务的表现超越现有方法。所有代码、数据和模型权重将公开发布。

> The video reasoning ability of multimodal large language models (MLLMs) is crucial for downstream tasks like video question answering and temporal grounding. While recent approaches have explored text-based chain-of-thought (CoT) reasoning for MLLMs, these methods often suffer from limited cross-modal interaction and increased hallucination, especially with longer videos or reasoning chains. To address these challenges, we propose Video Intelligence via Tool-Augmented Learning (VITAL), a novel end-to-end agentic video reasoning framework. With a visual toolbox, the model can densely sample new video frames on demand and generate multimodal CoT for precise long video reasoning. We observe that temporal grounding and question answering are mutually beneficial for video understanding tasks. Therefore, we construct two high-quality multi-task video reasoning datasets MTVR-CoT-72k for supervised fine-tuning and MTVR-RL-110k for reinforcement learning. Moreover, we propose a Difficulty-aware Group Relative Policy Optimization algorithm (DGRPO) to mitigate difficulty imbalance in multi-task reinforcement learning. Extensive experiments on 11 challenging video understanding benchmarks demonstrate the advanced reasoning ability of VITAL, outperforming existing methods in video question answering and temporal grounding tasks, especially in long video scenarios. All code, data and model weight will be made publicly available.

[Arxiv](https://arxiv.org/abs/2508.04416)