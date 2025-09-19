# ToolSample：结合课程学习的双重动态采样——面向强化学习工具学习

发布时间：2025年09月18日

`强化学习` `基础理论`

> ToolSample: Dual Dynamic Sampling Methods with Curriculum Learning for RL-based Tool Learning

# 摘要

> 强化学习（RL）在基于LLM的工具学习中应用越来越广泛，但训练过程中大量简单样本会逐渐降低学习价值，从而影响效率。现有动态采样技术难以适配工具学习特有的多任务结构和细粒度奖励机制。为此，本文提出动态采样与课程学习（DSCL）框架，该框架专门针对工具学习的独特特征——多个相互依赖的子任务和多值奖励函数，以应对上述挑战。DSCL包含两个核心组件：基于奖励的动态采样（利用多维奖励统计量（均值和方差）筛选高价值数据）和基于任务的动态课程学习（自适应聚焦于未充分掌握的子任务进行训练）。大量实验表明，DSCL大幅提升了训练效率和模型性能，不仅优于强基线，在BFCLv3基准上还实现了3.29%的性能提升。该方法通过有效利用工具学习中的复杂奖励信号和子任务动态，为这一领域提供了定制化解决方案，最终取得了优异效果。

> While reinforcement learning (RL) is increasingly used for LLM-based tool learning, its efficiency is often hampered by an overabundance of simple samples that provide diminishing learning value as training progresses. Existing dynamic sampling techniques are ill-suited for the multi-task structure and fine-grained reward mechanisms inherent to tool learning. This paper introduces Dynamic Sampling with Curriculum Learning (DSCL), a framework specifically designed to address this challenge by targeting the unique characteristics of tool learning: its multiple interdependent sub-tasks and multi-valued reward functions. DSCL features two core components: Reward-Based Dynamic Sampling, which uses multi-dimensional reward statistics (mean and variance) to prioritize valuable data, and Task-Based Dynamic Curriculum Learning, which adaptively focuses training on less-mastered sub-tasks. Through extensive experiments, we demonstrate that DSCL significantly improves training efficiency and model performance over strong baselines, achieving a 3.29\% improvement on the BFCLv3 benchmark. Our method provides a tailored solution that effectively leverages the complex reward signals and sub-task dynamics within tool learning to achieve superior results.

[Arxiv](https://arxiv.org/abs/2509.14718)