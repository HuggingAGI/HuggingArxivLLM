# 用于 LLM 代理训练的 Group-in-Group 策略优化

发布时间：2025年05月16日

`Agent` `智能体训练`

> Group-in-Group Policy Optimization for LLM Agent Training

# 摘要

> # 摘要
基于群组的强化学习（RL）近期的进展推动了前沿大型语言模型（LLMs）在单轮任务（如数学推理）中的应用。然而，这些方法在长时地平线的LLM代理训练中的扩展性仍然有限。与静态任务不同，智能体与环境的交互会持续多个步骤，并且常常产生稀疏或延迟的奖励，这使得在各个步骤之间进行有效的信用分配变得极具挑战性。

在本研究中，我们提出了组内组策略优化（GiGPO），这是一种新型的RL算法，能够在保持基于群组RL的吸引力特性（无需批评者、低内存占用和稳定收敛）的同时，实现对LLM代理的精细信用分配。GiGPO引入了一种两级结构来估计相对优势：（i）在轨迹级别，GiGPO基于完整轨迹的群组计算宏观相对优势；（ii）在步骤级别，GiGPO引入了一种锚定状态分组机制，通过识别跨轨迹的重复环境状态，回顾性地构建步骤级别的群组。同一状态下产生的动作会被分组，从而实现微观相对优势的估计。这种分层结构能够有效捕捉全局轨迹质量和局部步骤有效性，而无需依赖辅助模型或额外的轨迹生成。

我们在两个具有挑战性的智能体基准测试ALFWorld和WebShop上，使用Qwen2.5-1.5B-Instruct和Qwen2.5-7B-Instruct对GiGPO进行了评估。至关重要的是，GiGPO提供了精细的每一步信用信号，并在ALFWorld上实现了比GRPO基线高出>12%的性能提升，在WebShop上实现了>9%的性能提升：这一切均在保持相同的GPU内存占用、相同的LLM轨迹生成以及几乎不增加额外时间成本的前提下实现。


> Recent advances in group-based reinforcement learning (RL) have driven frontier large language models (LLMs) in single-turn tasks like mathematical reasoning. However, their scalability to long-horizon LLM agent training remains limited. Unlike static tasks, agent-environment interactions unfold over many steps and often yield sparse or delayed rewards, making credit assignment across individual steps significantly more challenging. In this work, we propose Group-in-Group Policy Optimization (GiGPO), a novel RL algorithm that achieves fine-grained credit assignment for LLM agents while preserving the appealing properties of group-based RL: critic-free, low memory, and stable convergence. GiGPO introduces a two-level structure for estimating relative advantage: (i) At the episode-level, GiGPO computes macro relative advantages based on groups of complete trajectories; (ii) At the step-level, GiGPO introduces an anchor state grouping mechanism that retroactively constructs step-level groups by identifying repeated environment states across trajectories. Actions stemming from the same state are grouped together, enabling micro relative advantage estimation. This hierarchical structure effectively captures both global trajectory quality and local step effectiveness without relying on auxiliary models or additional rollouts. We evaluate GiGPO on two challenging agent benchmarks, ALFWorld and WebShop, using Qwen2.5-1.5B-Instruct and Qwen2.5-7B-Instruct. Crucially, GiGPO delivers fine-grained per-step credit signals and achieves performance gains of > 12\% on ALFWorld and > 9\% on WebShop over the GRPO baseline: all while maintaining the same GPU memory overhead, identical LLM rollout, and incurring little to no additional time cost.

[Arxiv](https://arxiv.org/abs/2505.10978)