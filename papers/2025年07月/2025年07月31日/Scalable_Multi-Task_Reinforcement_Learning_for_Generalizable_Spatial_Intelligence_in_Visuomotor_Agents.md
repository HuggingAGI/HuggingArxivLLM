# 面向视觉运动智能体的通用化空间智能可扩展多任务强化学习研究

发布时间：2025年07月31日

`Agent` `机器人学` `计算机图形学`

> Scalable Multi-Task Reinforcement Learning for Generalizable Spatial Intelligence in Visuomotor Agents

# 摘要

> 尽管强化学习 (RL) 在语言建模领域取得了显著成功，但其优势尚未完全转化为视觉运动代理的性能。RL 模型的主要挑战在于容易过度拟合特定任务或环境，从而限制了其在不同设置下获得通用行为的能力。本文通过展示在 Minecraft 中经过 RL 微调的视觉运动代理能够实现对未见世界的零-shot 推广，初步回答了这一挑战。具体而言，我们探讨了 RL 提升三维世界中通用空间推理和交互能力的潜力。

为了解决多任务 RL 表示的挑战，我们分析并建立跨视角目标规范作为视觉运动策略的统一多任务目标空间。此外，为克服手动任务设计这一重大瓶颈，我们提出在高度可定制的 Minecraft 环境中进行大规模多任务 RL 训练的自动化任务合成，并构建了一个高效的分布式 RL 框架来支持这一点。实验结果表明，RL 显著提高了交互成功率（4倍），并实现了在各种环境中对空间推理的零-shot 推广，包括真实世界场景。我们的研究发现强调了在三维模拟环境中进行 RL 训练的巨大潜力，特别是那些适合大规模任务生成的环境，这将显著推动视觉运动代理的空间推理能力。

> While Reinforcement Learning (RL) has achieved remarkable success in language modeling, its triumph hasn't yet fully translated to visuomotor agents. A primary challenge in RL models is their tendency to overfit specific tasks or environments, thereby hindering the acquisition of generalizable behaviors across diverse settings. This paper provides a preliminary answer to this challenge by demonstrating that RL-finetuned visuomotor agents in Minecraft can achieve zero-shot generalization to unseen worlds. Specifically, we explore RL's potential to enhance generalizable spatial reasoning and interaction capabilities in 3D worlds. To address challenges in multi-task RL representation, we analyze and establish cross-view goal specification as a unified multi-task goal space for visuomotor policies. Furthermore, to overcome the significant bottleneck of manual task design, we propose automated task synthesis within the highly customizable Minecraft environment for large-scale multi-task RL training, and we construct an efficient distributed RL framework to support this. Experimental results show RL significantly boosts interaction success rates by $4\times$ and enables zero-shot generalization of spatial reasoning across diverse environments, including real-world settings. Our findings underscore the immense potential of RL training in 3D simulated environments, especially those amenable to large-scale task generation, for significantly advancing visuomotor agents' spatial reasoning.

[Arxiv](https://arxiv.org/abs/2507.23698)