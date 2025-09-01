# <翻译失败>

发布时间：2025年08月28日

`Agent` `交通运输`

> cMALC-D: Contextual Multi-Agent LLM-Guided Curriculum Learning with Diversity-Based Context Blending

# 摘要

> 许多多智能体强化学习（MARL）算法在固定模拟环境中训练，因此在部署到条件更复杂、不确定性更高的现实场景时往往表现脆弱。情境MARL（cMARL）通过情境变量对环境进行参数化，并训练一种在所有环境配置下均表现优异的情境无关策略，从而解决这一问题。现有的cMARL方法尝试借助课程学习来训练和评估情境无关策略，但它们常依赖不可靠的代理信号（如值估计或广义优势估计），这些信号在多智能体环境中因智能体间动态交互和部分可观测性而噪声大、稳定性差。为解决这些问题，我们提出了基于多样性情境融合的情境多智能体LLM引导课程学习（cMALC-D）——一种利用大型语言模型（LLMs）生成语义合理的课程并提供更稳健评估信号的框架。为防止模式崩溃并促进探索，我们引入了新颖的基于多样性的情境融合机制，通过融合先前情境的特征生成新的训练场景。交通信号控制领域的实验表明，与现有课程学习基线相比，cMALC-D在泛化能力和样本效率上均有显著提升。相关代码已开源至https://github.com/DaRL-LibSignal/cMALC-D。

> Many multi-agent reinforcement learning (MARL) algorithms are trained in fixed simulation environments, making them brittle when deployed in real-world scenarios with more complex and uncertain conditions. Contextual MARL (cMARL) addresses this by parameterizing environments with context variables and training a context-agnostic policy that performs well across all environment configurations. Existing cMARL methods attempt to use curriculum learning to help train and evaluate context-agnostic policies, but they often rely on unreliable proxy signals, such as value estimates or generalized advantage estimates that are noisy and unstable in multi-agent settings due to inter-agent dynamics and partial observability. To address these issues, we propose Contextual Multi-Agent LLM-Guided Curriculum Learning with Diversity-Based Context Blending (cMALC-D), a framework that uses Large Language Models (LLMs) to generate semantically meaningful curricula and provide a more robust evaluation signal. To prevent mode collapse and encourage exploration, we introduce a novel diversity-based context blending mechanism that creates new training scenarios by combining features from prior contexts. Experiments in traffic signal control domains demonstrate that cMALC-D significantly improves both generalization and sample efficiency compared to existing curriculum learning baselines. We provide code at https://github.com/DaRL-LibSignal/cMALC-D.

[Arxiv](https://arxiv.org/abs/2508.20818)