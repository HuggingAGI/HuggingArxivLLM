# ReMA：通过多智能体强化学习，为大型语言模型培养元思考能力

发布时间：2025年03月12日

`LLM理论` `人工智能` `机器学习`

> ReMA: Learning to Meta-think for LLMs with Multi-Agent Reinforcement Learning

# 摘要

> 近期，研究者们尝试通过整合元思维能力来进一步提升大型语言模型（LLMs）的推理性能，使模型能够更自主地监控、评估和控制自身的推理过程，从而实现更灵活、更高效的解决问题。然而，现有的单智能体研究方法在获取元思维能力方面缺乏专门设计，导致效果有限。为解决这一问题，我们提出了强化元思维代理（ReMA），这是一种基于多智能体强化学习（MARL）的全新框架，旨在激发模型的元思维行为，引导LLMs实现“思考如何思考”。ReMA将推理过程分解为两个层级分明的代理：高层的元思维代理负责制定战略监督和计划，而低层的推理代理则专注于具体执行。通过具有对齐目标的迭代强化学习，这些代理能够探索和学习协作，从而显著提升模型的泛化能力和鲁棒性。实验结果表明，ReMA在复杂推理任务上超越了单智能体强化学习基线，包括具有竞争力的数学基准测试和LLM作为评估者的基准测试。全面的消融研究进一步揭示了每个独特代理的动态演变过程，为理解元思维推理如何增强LLMs的推理能力提供了深刻的洞见。

> Recent research on Reasoning of Large Language Models (LLMs) has sought to further enhance their performance by integrating meta-thinking -- enabling models to monitor, evaluate, and control their reasoning processes for more adaptive and effective problem-solving. However, current single-agent work lacks a specialized design for acquiring meta-thinking, resulting in low efficacy. To address this challenge, we introduce Reinforced Meta-thinking Agents (ReMA), a novel framework that leverages Multi-Agent Reinforcement Learning (MARL) to elicit meta-thinking behaviors, encouraging LLMs to think about thinking. ReMA decouples the reasoning process into two hierarchical agents: a high-level meta-thinking agent responsible for generating strategic oversight and plans, and a low-level reasoning agent for detailed executions. Through iterative reinforcement learning with aligned objectives, these agents explore and learn collaboration, leading to improved generalization and robustness. Experimental results demonstrate that ReMA outperforms single-agent RL baselines on complex reasoning tasks, including competitive-level mathematical benchmarks and LLM-as-a-Judge benchmarks. Comprehensive ablation studies further illustrate the evolving dynamics of each distinct agent, providing valuable insights into how the meta-thinking reasoning process enhances the reasoning capabilities of LLMs.

[Arxiv](https://arxiv.org/abs/2503.09501)