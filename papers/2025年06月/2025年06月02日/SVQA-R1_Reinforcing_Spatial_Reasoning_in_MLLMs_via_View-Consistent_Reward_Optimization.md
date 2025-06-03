# SVQA-R1：通过视角一致的奖励优化增强多模态大语言模型的空间推理能力

发布时间：2025年06月02日

`LLM理论` `计算机视觉` `视觉问答`

> SVQA-R1: Reinforcing Spatial Reasoning in MLLMs via View-Consistent Reward Optimization

# 摘要

> 空间推理是现有视觉语言模型（VLMs）中关键但尚未充分发展的能力，尤其在需要理解相对位置、距离和物体配置的空间视觉问答（Spatial VQA）任务中表现突出。受DeepSeek-R1提出的R1范式启发，该范式通过基于规则的强化学习（RL）提升语言模型推理能力，我们推出SVQA-R1——首个将R1风格训练拓展至空间VQA领域的框架。特别地，我们创新性地提出了Spatial-GRPO，一种分组强化学习策略，通过扰动物体间空间关系（如镜像翻转）构建视角一致的奖励机制，从而引导模型发展出一致且基于实际的空间理解能力。我们的SVQA-R1模型不仅在空间VQA基准测试中实现了显著的性能提升，更在不依赖监督微调（SFT）数据的情况下展现出清晰可解释的推理路径。通过大量实验和可视化分析，我们验证了SVQA-R1在多个空间推理基准测试中的卓越效果。

> Spatial reasoning remains a critical yet underdeveloped capability in existing vision-language models (VLMs), especially for Spatial Visual Question Answering (Spatial VQA) tasks that require understanding relative positions, distances, and object configurations. Inspired by the R1 paradigm introduced in DeepSeek-R1, which enhances reasoning in language models through rule-based reinforcement learning (RL), we propose SVQA-R1, the first framework to extend R1-style training to spatial VQA. In particular, we introduce Spatial-GRPO, a novel group-wise RL strategy that constructs view-consistent rewards by perturbing spatial relations between objects, e.g., mirror flipping, thereby encouraging the model to develop a consistent and grounded understanding of space. Our model, SVQA-R1, not only achieves dramatically improved accuracy on spatial VQA benchmarks but also exhibits interpretable reasoning paths even without using supervised fine-tuning (SFT) data. Extensive experiments and visualization demonstrate the effectiveness of SVQA-R1 across multiple spatial reasoning benchmarks.

[Arxiv](https://arxiv.org/abs/2506.01371)