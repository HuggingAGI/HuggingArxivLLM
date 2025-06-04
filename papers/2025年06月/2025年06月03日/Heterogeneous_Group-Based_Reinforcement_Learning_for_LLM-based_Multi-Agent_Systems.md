# 异构群体强化学习在LLM多智能体系统中的应用研究

发布时间：2025年06月03日

`Agent` `搜索引擎` `多智能体系统`

> Heterogeneous Group-Based Reinforcement Learning for LLM-based Multi-Agent Systems

# 摘要

> 大型语言模型（LLMs）在自然语言处理领域取得了卓越的成果，但受限于固定的知识截止点和单次推理生成可控、准确输出的困难，其实际应用仍具挑战。由专门的LLM智能体构建的多智能体系统（MAS）提供了一种解决方案，实现了动态协作与迭代推理。然而，优化这些系统仍面临挑战，传统方法如提示工程和监督微调成本高昂且适应性有限。强化学习（RL），特别是多智能体强化学习（MARL），通过系统级反馈优化智能体策略，提供了一个可扩展的框架。然而，现有MARL算法如MAPPO依赖Critic网络，可能引发训练不稳定并增加计算负担。针对Multi-Agent Search System（MASS），我们提出Multi-Agent Heterogeneous Group Policy Optimization（MHGPO），一种创新的无 Critic 算法。该算法通过估计不同智能体群体的相对奖励优势来优化策略。MHGPO无需Critic网络，提升了训练稳定性并降低了计算成本。此外，我们引入了三种群体采样策略，在效率与效果之间实现平衡。实验结果表明，MHGPO在多智能体LLM搜索引擎中，无论任务性能还是计算效率均显著优于MAPPO，且无需预热阶段，展现了其在优化复杂LLM驱动MAS方面的巨大潜力。

> Large Language Models (LLMs) have achieved remarkable success across diverse natural language processing tasks, yet their deployment in real-world applications is hindered by fixed knowledge cutoffs and difficulties in generating controllable, accurate outputs in a single inference. Multi-agent systems (MAS) built from specialized LLM agents offer a promising solution, enabling dynamic collaboration and iterative reasoning. However, optimizing these systems remains a challenge, as conventional methods such as prompt engineering and supervised fine-tuning entail high engineering overhead and limited adaptability. Reinforcement learning (RL), particularly multi-agent reinforcement learning (MARL), provides a scalable framework by refining agent policies based on system-level feedback. Nevertheless, existing MARL algorithms, such as Multi-Agent Proximal Policy Optimization (MAPPO), rely on Critic networks, which can cause training instability and increase computational burden. To address these limitations and target the prototypical Multi-Agent Search System (MASS), we propose Multi-Agent Heterogeneous Group Policy Optimization (MHGPO), a novel Critic-free algorithm that guides policy updates by estimating relative reward advantages across heterogeneous groups of rollouts. MHGPO eliminates the need for Critic networks, enhancing stability and reducing computational overhead. Additionally, we introduce three group rollout sampling strategies that trade off between efficiency and effectiveness. Experiments on a multi-agent LLM-based search system demonstrate that MHGPO consistently outperforms MAPPO in both task performance and computational efficiency, without requiring warm-up, underscoring its potential for stable and scalable optimization of complex LLM-based MAS.

[Arxiv](https://arxiv.org/abs/2506.02718)