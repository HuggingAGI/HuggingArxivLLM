# Afterburner：强化学习助力代码自我优化效率提升

发布时间：2025年05月29日

`LLM应用` `软件开发`

> Afterburner: Reinforcement Learning Facilitates Self-Improving Code Efficiency Optimization

# 摘要

> 大型语言模型（LLMs）虽然能生成功能正确的代码，但在代码效率上常不尽如人意，这成为实际应用中的主要障碍。本文提出了一种创新的测试时迭代优化框架，通过闭环系统让LLMs根据执行环境的反馈持续优化代码。我们研究了三种训练策略：监督微调（SFT）、直接偏好优化（DPO）和基于强化学习的组相对策略优化（GRPO）。实验结果表明，在我们的Venus数据集和APPS基准测试中，SFT和DPO的效率提升迅速达到上限。而GRPO通过结合强化学习和执行反馈，持续优化代码性能，显著提升了pass@1指标（从47%提升至62%），并大幅增加了在效率上超越人类提交的可能性（从31%提升至45%）。我们的研究不仅展示了在测试时提升代码效率的有效方法，更凸显了强化学习在教会LLMs自我提升代码效率方面的巨大潜力。

> Large Language Models (LLMs) generate functionally correct solutions but often fall short in code efficiency, a critical bottleneck for real-world deployment. In this paper, we introduce a novel test-time iterative optimization framework to address this, employing a closed-loop system where LLMs iteratively refine code based on empirical performance feedback from an execution sandbox. We explore three training strategies: Supervised Fine-Tuning (SFT), Direct Preference Optimization (DPO), and Group Relative Policy Optimization~(GRPO). Experiments on our Venus dataset and the APPS benchmark show that SFT and DPO rapidly saturate in efficiency gains. In contrast, GRPO, using reinforcement learning (RL) with execution feedback, continuously optimizes code performance, significantly boosting both pass@1 (from 47% to 62%) and the likelihood of outperforming human submissions in efficiency (from 31% to 45%). Our work demonstrates effective test-time code efficiency improvement and critically reveals the power of RL in teaching LLMs to truly self-improve code efficiency.

[Arxiv](https://arxiv.org/abs/2505.23387)