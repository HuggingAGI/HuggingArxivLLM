# MTSA: 通过多轮红队测试实现LLMs的多轮安全对齐

发布时间：2025年05月22日

`LLM应用` `人工智能安全`

> MTSA: Multi-turn Safety Alignment for LLMs through Multi-round Red-teaming

# 摘要

> 针对大型语言模型 (LLMs) 的越狱攻击日益增多，凸显了建立可靠防护措施的必要性。然而，在多轮对话中，恶意意图可能隐藏在互动过程中，导致 LLMs 更容易生成有害回应。本文中，我们提出了 	extbf{M}ulti-	extbf{T}urn 	extbf{S}afety 	extbf{A}lignment (\ourapproach) 框架，以应对多轮互动中 LLMs 安全防护的挑战。该框架包含两个阶段：在思想引导的攻击学习阶段，红队模型学习思想引导的多轮越狱攻击，生成对抗性提示。在对抗性迭代优化阶段，红队模型和目标模型在互动中不断改进自身能力。此外，我们还引入了一种基于未来奖励的多轮强化学习算法，以增强安全对齐的稳健性。实验结果表明，红队模型展现出最先进的攻击能力，而目标模型在安全基准上的性能也得到了显著提升。

> The proliferation of jailbreak attacks against large language models (LLMs) highlights the need for robust security measures. However, in multi-round dialogues, malicious intentions may be hidden in interactions, leading LLMs to be more prone to produce harmful responses. In this paper, we propose the \textbf{M}ulti-\textbf{T}urn \textbf{S}afety \textbf{A}lignment (\ourapproach) framework, to address the challenge of securing LLMs in multi-round interactions. It consists of two stages: In the thought-guided attack learning stage, the red-team model learns about thought-guided multi-round jailbreak attacks to generate adversarial prompts. In the adversarial iterative optimization stage, the red-team model and the target model continuously improve their respective capabilities in interaction. Furthermore, we introduce a multi-turn reinforcement learning algorithm based on future rewards to enhance the robustness of safety alignment. Experimental results show that the red-team model exhibits state-of-the-art attack capabilities, while the target model significantly improves its performance on safety benchmarks.

[Arxiv](https://arxiv.org/abs/2505.17147)