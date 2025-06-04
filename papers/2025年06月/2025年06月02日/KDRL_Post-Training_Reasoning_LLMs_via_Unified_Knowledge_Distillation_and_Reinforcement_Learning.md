# # **KDRL**：通过统一知识蒸馏与强化学习提升大型语言模型的推理能力

发布时间：2025年06月02日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLM）后训练阶段的优化方法，结合强化学习（RL）和知识蒸馏（KD）来提升推理能力。它提出了一种新的统一框架KDRL，属于模型训练和优化的理论层面，因此归类为LLM理论。` `推理模型` `大型语言模型`

> KDRL: Post-Training Reasoning LLMs via Unified Knowledge Distillation and Reinforcement Learning

# 摘要

> 在大型语言模型（LLM）的后训练领域，最近取得了显著进展，主要通过强化学习（RL）和知识蒸馏（KD）两种范式来提升推理能力。虽然RL能够生成复杂的推理行为，但在初始策略难以探索高回报轨迹时，常常面临采样效率低下的问题。相反，KD通过模仿教师模型来提高学习效率，但往往在处理领域外场景时表现不佳。在本研究中，我们提出了	extbf{KDRL}，一个	extit{统一的后训练框架}，通过结合教师监督（KD）和自我探索（RL），对推理模型进行联合优化。具体而言，KDRL利用策略梯度优化，同时最小化学生与教师分布之间的逆向Kullback-Leibler散度（RKL），并最大化基于规则的预期奖励。我们首先提出了一个整合GRPO和KD的统一目标，并系统地探讨了不同KL近似、KL系数以及奖励引导的KD策略对整体后训练动态和性能的影响。在多个推理基准上的实证结果表明，KDRL不仅超越了GRPO和各种KD基线，还在性能与推理令牌效率之间实现了良好的平衡。这些发现表明，将KD与RL相结合，是训练推理LLM的有效且高效策略。

> Recent advances in large language model (LLM) post-training have leveraged two distinct paradigms to enhance reasoning capabilities: reinforcement learning (RL) and knowledge distillation (KD). While RL enables the emergence of complex reasoning behaviors, it often suffers from low sample efficiency when the initial policy struggles to explore high-reward trajectories. Conversely, KD improves learning efficiency via mimicking the teacher model but tends to generalize poorly to out-of-domain scenarios. In this work, we present \textbf{KDRL}, a \textit{unified post-training framework} that jointly optimizes a reasoning model through teacher supervision (KD) and self-exploration (RL). Specifically, KDRL leverages policy gradient optimization to simultaneously minimize the reverse Kullback-Leibler divergence (RKL) between the student and teacher distributions while maximizing the expected rule-based rewards. We first formulate a unified objective that integrates GRPO and KD, and systematically explore how different KL approximations, KL coefficients, and reward-guided KD strategies affect the overall post-training dynamics and performance. Empirical results on multiple reasoning benchmarks demonstrate that KDRL outperforms GRPO and various KD baselines while achieving a favorable balance between performance and reasoning token efficiency. These findings indicate that integrating KD and RL serves as an effective and efficient strategy to train reasoning LLMs.

[Arxiv](https://arxiv.org/abs/2506.02208)