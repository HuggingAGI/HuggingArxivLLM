# 截断近端策略优化（Truncated Proximal Policy Optimization）

发布时间：2025年06月17日

`LLM理论

理由：这篇论文主要讨论了在训练大型语言模型（LLMs）时使用强化学习（RL）中的近端策略优化（PPO）算法，并提出了一种改进的算法——截断近端策略优化（T-PPO）。论文的重点在于优化训练过程中的策略更新和计算效率，属于大型语言模型的训练和优化理论，因此归类为LLM理论。` `人工智能`

> Truncated Proximal Policy Optimization

# 摘要

> 最近，通过生成长链式思维（CoT），测试时扩展的大型语言模型（LLMs）在科学和专业任务中展现了卓越的推理能力。作为开发这些推理模型的关键技术，强化学习（RL）——以近端策略优化（PPO）及其变体为代表——使模型能够通过试错法进行学习。然而，由于其内在的策略性本质，PPO可能会耗费大量时间，这一问题在面对日益增长的响应长度时变得更加突出。在本研究中，我们提出了截断近端策略优化（T-PPO），这是对PPO的一种新颖扩展，通过优化策略更新和限制响应长度生成，提升了训练效率。T-PPO有效缓解了全同步长生成流程中硬件利用率低下的固有缺陷，在等待完整回放完成的过程中，资源常常闲置。我们的贡献包括两个方面。首先，我们提出了扩展广义优势估计（EGAE），能够在不完整响应的基础上进行优势估计，同时保持策略学习的完整性。其次，我们设计了一种计算优化机制，允许策略和价值模型的独立优化。通过选择性筛选提示和截断令牌，该机制减少了冗余计算，加速了训练进程，同时保持了收敛性能。我们在AIME 2024上使用320亿参数规模的基础模型验证了T-PPO的有效性和高效性。实验结果表明，T-PPO将推理LLMs的训练效率提升了2.5倍，并超越了现有的竞争对手。

> Recently, test-time scaling Large Language Models (LLMs) have demonstrated exceptional reasoning capabilities across scientific and professional tasks by generating long chains-of-thought (CoT). As a crucial component for developing these reasoning models, reinforcement learning (RL), exemplified by Proximal Policy Optimization (PPO) and its variants, allows models to learn through trial and error. However, PPO can be time-consuming due to its inherent on-policy nature, which is further exacerbated by increasing response lengths. In this work, we propose Truncated Proximal Policy Optimization (T-PPO), a novel extension to PPO that improves training efficiency by streamlining policy update and length-restricted response generation. T-PPO mitigates the issue of low hardware utilization, an inherent drawback of fully synchronized long-generation procedures, where resources often sit idle during the waiting periods for complete rollouts. Our contributions are two-folds. First, we propose Extended Generalized Advantage Estimation (EGAE) for advantage estimation derived from incomplete responses while maintaining the integrity of policy learning. Second, we devise a computationally optimized mechanism that allows for the independent optimization of the policy and value models. By selectively filtering prompt and truncated tokens, this mechanism reduces redundant computations and accelerates the training process without sacrificing convergence performance. We demonstrate the effectiveness and efficacy of T-PPO on AIME 2024 with a 32B base model. The experimental results show that T-PPO improves the training efficiency of reasoning LLMs by up to 2.5x and outperforms its existing competitors.

[Arxiv](https://arxiv.org/abs/2506.15050)