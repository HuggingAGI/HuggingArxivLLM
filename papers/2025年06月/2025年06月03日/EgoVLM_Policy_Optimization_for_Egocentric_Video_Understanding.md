# EgoVLM：自视角视频理解的策略优化研究

发布时间：2025年06月03日

`LLM应用` `人工智能` `视频分析`

> EgoVLM: Policy Optimization for Egocentric Video Understanding

# 摘要

> 新兴的具身AI应用，如可穿戴摄像头和自主智能体，凸显了从第一人称视频流中进行稳健推理的必要性。为此，我们推出EgoVLM——一款专为以自我为中心的视频环境设计的视觉语言模型，旨在整合视觉理解和空间-时间推理。EgoVLM采用组相对策略优化（GRPO）进行微调，这是一种强化学习方法，能有效使模型输出与人类-like推理步骤相匹配。我们沿袭DeepSeek R1-Zero的方法，直接使用强化学习进行调优，无需在链式思维（CoT）数据上进行监督微调。在以自我为中心的视频问答基准测试中，EgoVLM表现优异，显著超越通用视觉语言模型。特别是，我们的EgoVLM-3B仅基于非CoT的自我中心数据训练，在EgoSchema基准上分别比基础Qwen2.5-VL 3B和7B模型高出14.33和13.87的准确率。EgoVLM通过显式生成推理轨迹增强了可解释性，使其非常适合下游应用。此外，我们引入了一种关键帧奖励机制，结合显著帧选择来优化强化学习过程。这种创新的奖励形式为未来在时间定位的自我中心推理探索开辟了富有前景的途径。

> Emerging embodied AI applications, such as wearable cameras and autonomous agents, have underscored the need for robust reasoning from first person video streams. We introduce EgoVLM, a vision-language model specifically designed to integrate visual comprehension and spatial-temporal reasoning within egocentric video contexts. EgoVLM is fine-tuned via Group Relative Policy Optimization (GRPO), a reinforcement learning method adapted to align model outputs with human-like reasoning steps. Following DeepSeek R1-Zero's approach, we directly tune using RL without any supervised fine-tuning phase on chain-of-thought (CoT) data. We evaluate EgoVLM on egocentric video question answering benchmarks and show that domain-specific training substantially improves performance over general-purpose VLMs. Our EgoVLM-3B, trained exclusively on non-CoT egocentric data, outperforms the base Qwen2.5-VL 3B and 7B models by 14.33 and 13.87 accuracy points on the EgoSchema benchmark, respectively. By explicitly generating reasoning traces, EgoVLM enhances interpretability, making it well-suited for downstream applications. Furthermore, we introduce a novel keyframe-based reward that incorporates salient frame selection to guide reinforcement learning optimization. This reward formulation opens a promising avenue for future exploration in temporally grounded egocentric reasoning.

[Arxiv](https://arxiv.org/abs/2506.03097)