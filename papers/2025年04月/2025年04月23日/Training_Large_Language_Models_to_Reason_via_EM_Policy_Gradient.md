# Training Large Language Models to Reason via EM Policy Gradient

发布时间：2025年04月23日

`LLM理论`

> Training Large Language Models to Reason via EM Policy Gradient

# 摘要

> 近期，OpenAI 的 O1 和 O3 以及 DeepSeek 的 R1 等基础模型展示了通过大规模强化学习（RL）获得的强大推理能力和问题解决技巧，并在数学、编码、科学、智能体和虚拟助手等领域得到了广泛应用。本研究中，我们提出了一种名为 EM 策略梯度的无策略强化学习算法，旨在通过优化推理轨迹的期望回报来提升大语言模型的推理能力。我们将推理任务建模为一个期望最大化（EM）优化问题，通过交替执行多样化推理轨迹的采样和奖励引导的微调来解决问题。与依赖复杂重要性权重和启发式剪裁的 PPO 和 GRPO 不同，我们的方法提供了一种更简单、更原理化的无策略策略梯度方法，在消除复杂性的同时保持了强劲的性能。我们在 GSM8K 和 MATH（HARD）数据集上评估了 EM 策略梯度的有效性，其表现可与或略优于当前最先进的 GRPO 相媲美，同时在可扩展性、简洁性和推理简洁性方面提供了额外优势。此外，使用我们方法进行微调的模型表现出子问题分解、自我验证和回溯等认知行为，突显了其在增强大语言模型推理的可解释性和鲁棒性方面的潜力。

> Recently, foundation models such as OpenAI's O1 and O3, along with DeepSeek's R1, have demonstrated strong reasoning capacities and problem-solving skills acquired through large-scale reinforcement learning (RL), with wide applications in mathematics, coding, science, intelligent agents, and virtual assistants. In this work, we introduce an off-policy reinforcement learning algorithm, EM Policy Gradient, aimed at enhancing LLM reasoning by optimizing expected return over reasoning trajectories. We frame the reasoning task as an Expectation-Maximization (EM) optimization problem, alternating between sampling diverse rationale trajectories and performing reward-guided fine-tuning. Unlike PPO and GRPO, which rely on complex importance weights and heuristic clipping, our method provides a simpler, more principled off-policy policy gradient approach, eliminating these complexities while maintaining strong performance. We evaluate the effectiveness of EM Policy Gradient on the GSM8K and MATH (HARD) datasets, where it achieves performance comparable to or slightly surpassing the state-of-the-art GRPO, while offering additional advantages in scalability, simplicity, and reasoning conciseness. Moreover, models fine-tuned with our method exhibit cognitive behaviors, such as sub-problem decomposition, self-verification, and backtracking, highlighting its potential to enhance both the interpretability and robustness of LLM reasoning.

[Arxiv](https://arxiv.org/abs/2504.18587)