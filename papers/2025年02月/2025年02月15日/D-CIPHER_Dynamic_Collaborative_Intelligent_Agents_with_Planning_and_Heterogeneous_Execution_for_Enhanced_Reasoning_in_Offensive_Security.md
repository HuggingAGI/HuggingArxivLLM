# D-CIPHER: 具备规划与异构执行能力的动态协作智能体，提升进攻性安全中的推理能力

发布时间：2025年02月15日

`LLM应用` `网络安全` `智能体系统`

> D-CIPHER: Dynamic Collaborative Intelligent Agents with Planning and Heterogeneous Execution for Enhanced Reasoning in Offensive Security

# 摘要

> 大型语言模型（LLMs）在网络安全领域得到了广泛应用，尤其是在作为智能体系统进行自主安全分析方面。Capture the Flag（CTF）挑战为评估LLM智能体在各种网络安全技能上的自动任务规划能力提供了基准。早期尝试利用LLMs解决CTF挑战时，主要依赖单一智能体系统，其中反馈仅限于单一的推理-行动循环。这种方法被证明不足以应对复杂的CTF任务。受现实世界CTF竞赛中专家团队协作的启发，我们引入了D-CIPHER多智能体LLM框架，用于协作解决CTF挑战。D-CIPHER集成了具有不同角色的智能体，实现了动态反馈循环，从而增强了对CTF挑战的推理能力。它引入了规划器-执行器智能体系统，其中包括一个负责整体问题解决的规划器智能体，以及多个负责具体任务的异构执行器智能体，从而实现了LLM之间责任的高效分配。此外，D-CIPHER还集成了一个自动提示器智能体，通过探索挑战环境并生成一个高度相关的初始提示，从而提升问题解决能力。我们在CTF基准上使用多个LLM模型对D-CIPHER进行了评估，并进行了全面研究以突出改进的影响。我们的结果显示，多智能体D-CIPHER系统在解决挑战方面取得了显著提升，在三个基准上达到了最先进的性能：NYU CTF Bench上的22.0%，Cybench上的22.5%，以及HackTheBox上的44.0%。D-CIPHER可在https://github.com/NYU-LLM-CTF/nyuctf_agents上获得，作为nyuctf_multiagent包。

> Large Language Models (LLMs) have been used in cybersecurity in many ways, including their recent use as intelligent agent systems for autonomous security analysis. Capture the Flag (CTF) challenges serve as benchmarks for assessing the automated task-planning abilities of LLM agents across various cybersecurity skill sets. Early attempts to apply LLMs for solving CTF challenges relied on single-agent systems, where feedback was restricted to a single reasoning-action loop. This approach proved inadequate for handling complex CTF tasks. Drawing inspiration from real-world CTF competitions, where teams of experts collaborate, we introduce the D-CIPHER multi-agent LLM framework for collaborative CTF challenge solving. D-CIPHER integrates agents with distinct roles, enabling dynamic feedback loops to enhance reasoning on CTF challenges. It introduces the Planner-Executor agent system, consisting of a Planner agent for overall problem-solving along with multiple heterogeneous Executor agents for individual tasks, facilitating efficient allocation of responsibilities among the LLMs. Additionally, D-CIPHER incorporates an Auto-prompter agent, which improves problem-solving by exploring the challenge environment and generating a highly relevant initial prompt. We evaluate D-CIPHER on CTF benchmarks using multiple LLM models and conduct comprehensive studies to highlight the impact of our enhancements. Our results demonstrate that the multi-agent D-CIPHER system achieves a significant improvement in challenges solved, setting a state-of-the-art performance on three benchmarks: 22.0% on NYU CTF Bench, 22.5% on Cybench, and 44.0% on HackTheBox. D-CIPHER is available at https://github.com/NYU-LLM-CTF/nyuctf_agents as the nyuctf_multiagent package.

[Arxiv](https://arxiv.org/abs/2502.10931)